<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DocMaster Pro | PDF to Word, Word to PDF, Compress PDF & More</title>
    <meta name="description" content="Free online tool to convert PDF to Word, Word to PDF, PowerPoint to PDF, Excel to PDF, edit PDF, compress PDF and more. Advanced document conversion with multiple compression levels.">
    <meta name="keywords" content="pdf to word, word to pdf, powerpoint to pdf, pdf to powerpoint, excel to pdf, pdf to excel, pdf to jpg, compress pdf, edit pdf, merge pdf, split pdf, online document converter">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #2563eb;
            --primary-dark: #1d4ed8;
            --primary-light: #3b82f6;
            --secondary: #7c3aed;
            --accent: #ec4899;
            --success: #10b981;
            --warning: #f59e0b;
            --error: #ef4444;
            --dark: #1e293b;
            --dark-2: #334155;
            --dark-3: #475569;
            --light: #f8fafc;
            --light-2: #e2e8f0;
            --light-3: #cbd5e1;
            --gray: #94a3b8;
            --radius: 12px;
            --shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1);
            --shadow-lg: 0 20px 40px -10px rgba(0, 0, 0, 0.15);
            --transition: all 0.3s ease;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', sans-serif;
        }

        body {
            background: linear-gradient(135deg, #f0f4ff 0%, #fdf2f8 100%);
            color: var(--dark);
            min-height: 100vh;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .container {
            width: 100%;
            max-width: 1400px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header Styles */
        header {
            width: 100%;
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(10px);
            padding: 20px 0;
            box-shadow: var(--shadow);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 12px;
            font-weight: 700;
            font-size: 1.8rem;
            color: var(--primary);
        }

        .logo-icon {
            font-size: 2.2rem;
            color: var(--secondary);
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 30px;
        }

        nav a {
            text-decoration: none;
            color: var(--dark-3);
            font-weight: 500;
            transition: var(--transition);
            position: relative;
        }

        nav a:hover {
            color: var(--primary);
        }

        nav a::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 0;
            height: 3px;
            background: var(--primary);
            border-radius: 10px;
            transition: var(--transition);
        }

        nav a:hover::after {
            width: 100%;
        }

        .auth-buttons {
            display: flex;
            gap: 15px;
        }

        .btn {
            padding: 10px 20px;
            border-radius: var(--radius);
            font-weight: 600;
            cursor: pointer;
            transition: var(--transition);
            border: none;
        }

        .btn-outline {
            background: transparent;
            border: 2px solid var(--primary);
            color: var(--primary);
        }

        .btn-outline:hover {
            background: var(--primary);
            color: white;
        }

        .btn-primary {
            background: var(--primary);
            color: white;
        }

        .btn-primary:hover {
            background: var(--primary-dark);
        }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 60px 0 40px;
            max-width: 800px;
            margin: 0 auto;
        }

        .hero h1 {
            font-size: 3.2rem;
            margin-bottom: 20px;
            background: linear-gradient(to right, var(--primary), var(--secondary));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            line-height: 1.2;
        }

        .hero p {
            font-size: 1.2rem;
            color: var(--dark-3);
            line-height: 1.6;
            margin-bottom: 30px;
        }

        /* Ad Container */
        .ad-container {
            width: 100%;
            background: white;
            border-radius: var(--radius);
            padding: 15px;
            margin: 30px 0;
            text-align: center;
            box-shadow: var(--shadow);
            min-height: 90px;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
        }

        .ad-label {
            position: absolute;
            top: 5px;
            right: 10px;
            font-size: 0.7rem;
            color: var(--gray);
        }

        /* Tools Grid */
        .tools-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 25px;
            width: 100%;
            margin: 40px 0;
        }

        .tool-card {
            background: white;
            border-radius: var(--radius);
            box-shadow: var(--shadow);
            padding: 25px;
            transition: var(--transition);
            display: flex;
            flex-direction: column;
            height: 100%;
            position: relative;
            overflow: hidden;
        }

        .tool-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 5px;
            height: 0;
            background: linear-gradient(to bottom, var(--primary), var(--secondary));
            transition: var(--transition);
        }

        .tool-card:hover::before {
            height: 100%;
        }

        .tool-card:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow-lg);
        }

        .tool-header {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }

        .tool-icon {
            font-size: 2.2rem;
            margin-right: 15px;
            color: var(--primary);
            width: 60px;
            height: 60px;
            display: flex;
            align-items: center;
            justify-content: center;
            background: rgba(37, 99, 235, 0.1);
            border-radius: 12px;
        }

        .tool-title {
            font-size: 1.5rem;
            color: var(--dark);
            font-weight: 600;
        }

        .tool-description {
            color: var(--dark-3);
            margin-bottom: 20px;
            line-height: 1.5;
            flex-grow: 1;
        }

        .tool-actions {
            margin-top: auto;
        }

        .use-tool-btn {
            width: 100%;
            background: var(--primary);
            color: white;
            border: none;
            padding: 12px;
            border-radius: 8px;
            font-size: 1rem;
            cursor: pointer;
            transition: var(--transition);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .use-tool-btn:hover {
            background: var(--primary-dark);
        }

        /* Converter Modal */
        .converter-modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.7);
            z-index: 1000;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        .modal-content {
            background: white;
            border-radius: var(--radius);
            width: 100%;
            max-width: 800px;
            max-height: 90vh;
            overflow-y: auto;
            box-shadow: var(--shadow-lg);
            position: relative;
        }

        .modal-header {
            padding: 20px 25px;
            border-bottom: 1px solid var(--light-2);
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .modal-title {
            font-size: 1.5rem;
            color: var(--dark);
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .close-modal {
            background: none;
            border: none;
            font-size: 1.5rem;
            cursor: pointer;
            color: var(--gray);
            transition: var(--transition);
        }

        .close-modal:hover {
            color: var(--dark);
        }

        .modal-body {
            padding: 25px;
        }

        .upload-area {
            border: 2px dashed var(--primary-light);
            border-radius: var(--radius);
            padding: 40px 20px;
            text-align: center;
            margin-bottom: 25px;
            cursor: pointer;
            transition: var(--transition);
        }

        .upload-area:hover {
            background: rgba(37, 99, 235, 0.05);
            border-color: var(--primary);
        }

        .upload-icon {
            font-size: 3.5rem;
            color: var(--primary);
            margin-bottom: 15px;
        }

        .upload-text {
            font-size: 1.1rem;
            margin-bottom: 15px;
            color: var(--dark);
        }

        .file-input {
            display: none;
        }

        .browse-btn {
            background: var(--primary);
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 6px;
            cursor: pointer;
            font-size: 1rem;
            transition: var(--transition);
        }

        .browse-btn:hover {
            background: var(--primary-dark);
        }

        .file-info {
            margin: 20px 0;
            padding: 15px;
            background: var(--light);
            border-radius: var(--radius);
            display: none;
        }

        .file-name {
            font-weight: 600;
            margin-bottom: 5px;
            color: var(--dark);
        }

        .file-size {
            color: var(--dark-3);
            font-size: 0.9rem;
        }

        .options-area {
            margin: 20px 0;
            display: none;
        }

        .option-title {
            font-weight: 600;
            margin-bottom: 10px;
            color: var(--dark);
        }

        .compression-options {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 15px 0;
        }

        .compression-option {
            flex: 1;
            min-width: 120px;
            text-align: center;
            padding: 12px;
            background: var(--light);
            border: 1px solid var(--light-2);
            border-radius: var(--radius);
            cursor: pointer;
            transition: var(--transition);
        }

        .compression-option.selected {
            background: var(--primary);
            color: white;
            border-color: var(--primary);
        }

        .convert-btn {
            width: 100%;
            background: var(--secondary);
            color: white;
            border: none;
            padding: 15px;
            border-radius: var(--radius);
            font-size: 1.1rem;
            cursor: pointer;
            transition: var(--transition);
            margin-top: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .convert-btn:hover {
            background: var(--primary);
        }

        .convert-btn:disabled {
            background: var(--gray);
            cursor: not-allowed;
        }

        .progress-area {
            display: none;
            margin: 20px 0;
        }

        .progress-bar {
            height: 8px;
            background: var(--light-2);
            border-radius: 4px;
            margin: 15px 0;
            overflow: hidden;
        }

        .progress {
            height: 100%;
            background: linear-gradient(to right, var(--primary), var(--secondary);
            width: 0%;
            transition: width 0.3s;
        }

        .download-area {
            display: none;
            margin-top: 25px;
            text-align: center;
            padding: 20px;
            background: rgba(16, 185, 129, 0.1);
            border-radius: var(--radius);
        }

        .download-btn {
            background: var(--success);
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: var(--radius);
            cursor: pointer;
            font-size: 1.1rem;
            transition: var(--transition);
            display: inline-flex;
            align-items: center;
            gap: 10px;
        }

        .download-btn:hover {
            background: #0da271;
        }

        /* Features Section */
        .features {
            display: flex;
            flex-wrap: wrap;
            gap: 25px;
            margin: 60px 0;
        }

        .feature {
            flex: 1;
            min-width: 250px;
            padding: 30px;
            background: white;
            border-radius: var(--radius);
            box-shadow: var(--shadow);
            transition: var(--transition);
        }

        .feature:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow-lg);
        }

        .feature-icon {
            font-size: 2.5rem;
            color: var(--primary);
            margin-bottom: 20px;
        }

        .feature-title {
            font-size: 1.4rem;
            margin-bottom: 15px;
            color: var(--dark);
        }

        .feature-desc {
            color: var(--dark-3);
            line-height: 1.6;
        }

        /* Footer */
        footer {
            margin-top: 50px;
            text-align: center;
            padding: 40px 0;
            color: var(--dark-3);
            font-size: 0.9rem;
            width: 100%;
            background: white;
            border-top: 1px solid var(--light-2);
        }

        .footer-content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            gap: 40px;
            text-align: left;
        }

        .footer-column {
            flex: 1;
            min-width: 200px;
        }

        .footer-column h3 {
            color: var(--dark);
            margin-bottom: 20px;
            font-size: 1.2rem;
        }

        .footer-column ul {
            list-style: none;
        }

        .footer-column li {
            margin-bottom: 10px;
        }

        .footer-column a {
            color: var(--dark-3);
            text-decoration: none;
            transition: var(--transition);
        }

        .footer-column a:hover {
            color: var(--primary);
        }

        .copyright {
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid var(--light-2);
            width: 100%;
        }

        /* Responsive Styles */
        @media (max-width: 1024px) {
            .hero h1 {
                font-size: 2.8rem;
            }
            
            nav ul {
                gap: 20px;
            }
        }

        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                gap: 20px;
            }
            
            nav ul {
                gap: 15px;
                flex-wrap: wrap;
                justify-content: center;
            }
            
            .auth-buttons {
                justify-content: center;
            }
            
            .hero h1 {
                font-size: 2.3rem;
            }
            
            .hero p {
                font-size: 1.1rem;
            }
            
            .tools-grid {
                grid-template-columns: 1fr;
            }
            
            .modal-content {
                margin: 20px;
                width: calc(100% - 40px);
            }
            
            .compression-options {
                flex-direction: column;
            }
        }

        @media (max-width: 480px) {
            .logo {
                font-size: 1.5rem;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .tool-title {
                font-size: 1.3rem;
            }
            
            .feature {
                padding: 20px;
            }
            
            .footer-content {
                flex-direction: column;
                gap: 30px;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container header-content">
            <div class="logo">
                <i class="fas fa-file-contract logo-icon"></i>
                <span>DocMaster Pro</span>
            </div>
            
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Tools</a></li>
                    <li><a href="#">Pricing</a></li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">Support</a></li>
                </ul>
            </nav>
            
            <div class="auth-buttons">
                <button class="btn btn-outline">Sign In</button>
                <button class="btn btn-primary">Sign Up</button>
            </div>
        </div>
    </header>
    
    <div class="container">
        <section class="hero">
            <h1>Premium Document Conversion Made Simple</h1>
            <p>Convert, compress, edit, merge, and split PDF files with our powerful online tools. Experience flawless conversions with maximum privacy.</p>
            <button class="btn btn-primary">Get Started For Free</button>
        </section>
        
        <div class="ad-container">
            <span class="ad-label">Advertisement</span>
            <!-- Google AdSense Ad Unit 1 -->
            <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
            <ins class="adsbygoogle"
                 style="display:block"
                 data-ad-client="ca-pub-2685258670758486"
                 data-ad-slot="8097565910"
                 data-ad-format="auto"
                 data-full-width-responsive="true"></ins>
            <script>
                 (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
        
        <div class="tools-grid">
            <div class="tool-card">
                <div class="tool-header">
                    <div class="tool-icon">
                        <i class="fas fa-file-word"></i>
                    </div>
                    <h3 class="tool-title">Word to PDF</h3>
                </div>
                <p class="tool-description">Convert Microsoft Word documents to PDF format with perfect formatting preserved.</p>
                <div class="tool-actions">
                    <button class="use-tool-btn" data-tool="word-to-pdf">
                        <i class="fas fa-exchange-alt"></i> Convert Now
                    </button>
                </div>
            </div>
            
            <div class="tool-card">
                <div class="tool-header">
                    <div class="tool-icon">
                        <i class="fas fa-file-pdf"></i>
                    </div>
                    <h3 class="tool-title">PDF to Word</h3>
                </div>
                <p class="tool-description">Convert PDF files to editable Word documents while maintaining original layout.</p>
                <div class="tool-actions">
                    <button class="use-tool-btn" data-tool="pdf-to-word">
                        <i class="fas fa-exchange-alt"></i> Convert Now
                    </button>
                </div>
            </div>
            
            <div class="tool-card">
                <div class="tool-header">
                    <div class="tool-icon">
                        <i class="fas fa-file-powerpoint"></i>
                    </div>
                    <h3 class="tool-title">PowerPoint to PDF</h3>
                </div>
                <p class="tool-description">Convert PowerPoint presentations to PDF documents for easy sharing and printing.</p>
                <div class="tool-actions">
                    <button class="use-tool-btn" data-tool="powerpoint-to-pdf">
                        <i class="fas fa-exchange-alt"></i> Convert Now
                    </button>
                </div>
            </div>
            
            <div class="tool-card">
                <div class="tool-header">
                    <div class="tool-icon">
                        <i class="fas fa-file-pdf"></i>
                    </div>
                    <h3 class="tool-title">PDF to PowerPoint</h3>
                </div>
                <p class="tool-description">Convert PDF files back to editable PowerPoint presentations.</p>
                <div class="tool-actions">
                    <button class="use-tool-btn" data-tool="pdf-to-powerpoint">
                        <i class="fas fa-exchange-alt"></i> Convert Now
                    </button>
                </div>
            </div>
            
            <div class="tool-card">
                <div class="tool-header">
                    <div class="tool-icon">
                        <i class="fas fa-file-excel"></i>
                    </div>
                    <h3 class="tool-title">Excel to PDF</h3>
                </div>
                <p class="tool-description">Convert Excel spreadsheets to PDF format while preserving formulas and formatting.</p>
                <div class="tool-actions">
                    <button class="use-tool-btn" data-tool="excel-to-pdf">
                        <i class="fas fa-exchange-alt"></i> Convert Now
                    </button>
                </div>
            </div>
            
            <div class="tool-card">
                <div class="tool-header">
                    <div class="tool-icon">
                        <i class="fas fa-file-pdf"></i>
                    </div>
                    <h3 class="tool-title">PDF to Excel</h3>
                </div>
                <p class="tool-description">Extract tables from PDF files and convert them to editable Excel spreadsheets.</p>
                <div class="tool-actions">
                    <button class="use-tool-btn" data-tool="pdf-to-excel">
                        <i class="fas fa-exchange-alt"></i> Convert Now
                    </button>
                </div>
            </div>
            
            <div class="tool-card">
                <div class="tool-header">
                    <div class="tool-icon">
                        <i class="fas fa-file-image"></i>
                    </div>
                    <h3 class="tool-title">PDF to JPG</h3>
                </div>
                <p class="tool-description">Convert PDF pages to high-quality JPG images for easy sharing and use.</p>
                <div class="tool-actions">
                    <button class="use-tool-btn" data-tool="pdf-to-jpg">
                        <i class="fas fa-exchange-alt"></i> Convert Now
                    </button>
                </div>
            </div>
            
            <div class="tool-card">
                <div class="tool-header">
                    <div class="tool-icon">
                        <i class="fas fa-compress-arrows-alt"></i>
                    </div>
                    <h3 class="tool-title">Compress PDF</h3>
                </div>
                <p class="tool-description">Reduce PDF file size without significant quality loss. Choose compression level.</p>
                <div class="tool-actions">
                    <button class="use-tool-btn" data-tool="compress-pdf">
                        <i class="fas fa-tools"></i> Compress Now
                    </button>
                </div>
            </div>
            
            <div class="tool-card">
                <div class="tool-header">
                    <div class="tool-icon">
                        <i class="fas fa-edit"></i>
                    </div>
                    <h3 class="tool-title">Edit PDF</h3>
                </div>
                <p class="tool-description">Edit text, images, and pages in your PDF documents with our easy-to-use tool.</p>
                <div class="tool-actions">
                    <button class="use-tool-btn" data-tool="edit-pdf">
                        <i class="fas fa-edit"></i> Edit Now
                    </button>
                </div>
            </div>
            
            <div class="tool-card">
                <div class="tool-header">
                    <div class="tool-icon">
                        <i class="fas fa-object-group"></i>
                    </div>
                    <h3 class="tool-title">Merge PDF</h3>
                </div>
                <p class="tool-description">Combine multiple PDF files into a single document with our merge tool.</p>
                <div class="tool-actions">
                    <button class="use-tool-btn" data-tool="merge-pdf">
                        <i class="fas fa-object-group"></i> Merge Now
                    </button>
                </div>
            </div>
            
            <div class="tool-card">
                <div class="tool-header">
                    <div class="tool-icon">
                        <i class="fas fa-cut"></i>
                    </div>
                    <h3 class="tool-title">Split PDF</h3>
                </div>
                <p class="tool-description">Split a PDF document into multiple files by pages or content.</p>
                <div class="tool-actions">
                    <button class="use-tool-btn" data-tool="split-pdf">
                        <i class="fas fa-cut"></i> Split Now
                    </button>
                </div>
            </div>
            
            <div class="tool-card">
                <div class="tool-header">
                    <div class="tool-icon">
                        <i class="fas fa-lock"></i>
                    </div>
                    <h3 class="tool-title">PDF Security</h3>
                </div>
                <p class="tool-description">Add passwords and permissions to your PDF files to protect sensitive information.</p>
                <div class="tool-actions">
                    <button class="use-tool-btn" data-tool="secure-pdf">
                        <i class="fas fa-lock"></i> Secure Now
                    </button>
                </div>
            </div>
        </div>
        
        <div class="ad-container">
            <span class="ad-label">Advertisement</span>
            <!-- Google AdSense Ad Unit 2 -->
            <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
            <ins class="adsbygoogle"
                 style="display:block"
                 data-ad-client="ca-pub-2685258670758486"
                 data-ad-slot="3081861194"
                 data-ad-format="auto"
                 data-full-width-responsive="true"></ins>
            <script>
                 (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
        
        <div class="features">
            <div class="feature">
                <div class="feature-icon">
                    <i class="fas fa-shield-alt"></i>
                </div>
                <h3 class="feature-title">Secure Processing</h3>
                <p class="feature-desc">All file processing happens directly in your browser. Your files are never uploaded to any server.</p>
            </div>
            
            <div class="feature">
                <div class="feature-icon">
                    <i class="fas fa-bolt"></i>
                </div>
                <h3 class="feature-title">Fast Conversion</h3>
                <p class="feature-desc">Our optimized algorithms ensure quick conversion even for large files.</p>
            </div>
            
            <div class="feature">
                <div class="feature-icon">
                    <i class="fas fa-mobile-alt"></i>
                </div>
                <h3 class="feature-title">Mobile Friendly</h3>
                <p class="feature-desc">Works perfectly on all devices - desktop, tablet, and mobile phones.</p>
            </div>
        </div>
    </div>
    
    <div class="converter-modal" id="converter-modal">
        <div class="modal-content">
            <div class="modal-header">
                <h3 class="modal-title" id="modal-tool-title">
                    <i class="fas fa-file-pdf" id="modal-tool-icon"></i>
                    <span id="modal-tool-text">Word to PDF</span>
                </h3>
                <button class="close-modal">&times;</button>
            </div>
            <div class="modal-body">
                <div class="upload-area" id="upload-area">
                    <i class="fas fa-cloud-upload-alt upload-icon"></i>
                    <p class="upload-text">Drag & drop your file here</p>
                    <button class="browse-btn">Browse Files</button>
                    <input type="file" class="file-input" id="file-input">
                </div>
                
                <div class="file-info" id="file-info">
                    <div class="file-name" id="file-name">document.pdf</div>
                    <div class="file-size" id="file-size">0 KB</div>
                </div>
                
                <div class="options-area" id="options-area">
                    <h4 class="option-title">Compression Level</h4>
                    <div class="compression-options">
                        <div class="compression-option selected" data-level="low">Low (Larger Size)</div>
                        <div class="compression-option" data-level="medium">Medium (Recommended)</div>
                        <div class="compression-option" data-level="high">High (Smaller Size)</div>
                    </div>
                </div>
                
                <div class="progress-area" id="progress-area">
                    <p>Processing your file...</p>
                    <div class="progress-bar">
                        <div class="progress" id="progress"></div>
                    </div>
                    <p id="progress-text">0%</p>
                </div>
                
                <button class="convert-btn" id="convert-btn" disabled>
                    <i class="fas fa-cog"></i> Process File
                </button>
                
                <div class="download-area" id="download-area">
                    <p>Your file is ready!</p>
                    <button class="download-btn" id="download-btn">
                        <i class="fas fa-download"></i> Download File
                    </button>
                </div>
            </div>
        </div>
    </div>
    
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>DocMaster Pro</h3>
                    <p>The ultimate document conversion tool for all your PDF needs.</p>
                </div>
                
                <div class="footer-column">
                    <h3>Tools</h3>
                    <ul>
                        <li><a href="#">PDF to Word</a></li>
                        <li><a href="#">Word to PDF</a></li>
                        <li><a href="#">PDF Compressor</a></li>
                        <li><a href="#">PDF Editor</a></li>
                    </ul>
                </div>
                
                <div class="footer-column">
                    <h3>Company</h3>
                    <ul>
                        <li><a href="#">About Us</a></li>
                        <li><a href="#">Pricing</a></li>
                        <li><a href="#">Blog</a></li>
                        <li><a href="#">Careers</a></li>
                    </ul>
                </div>
                
                <div class="footer-column">
                    <h3>Support</h3>
                    <ul>
                        <li><a href="#">Help Center</a></li>
                        <li><a href="#">Contact Us</a></li>
                        <li><a href="#">Privacy Policy</a></li>
                        <li><a href="#">Terms of Service</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="copyright">
                <p>© 2023 DocMaster Pro. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // DOM Elements
        const modal = document.getElementById('converter-modal');
        const closeModalBtn = document.querySelector('.close-modal');
        const useToolBtns = document.querySelectorAll('.use-tool-btn');
        const uploadArea = document.getElementById('upload-area');
        const fileInput = document.getElementById('file-input');
        const fileInfo = document.getElementById('file-info');
        const fileName = document.getElementById('file-name');
        const fileSize = document.getElementById('file-size');
        const optionsArea = document.getElementById('options-area');
        const compressionOptions = document.querySelectorAll('.compression-option');
        const convertBtn = document.getElementById('convert-btn');
        const progressArea = document.getElementById('progress-area');
        const progressBar = document.getElementById('progress');
        const progressText = document.getElementById('progress-text');
        const downloadArea = document.getElementById('download-area');
        const downloadBtn = document.getElementById('download-btn');
        const modalToolTitle = document.getElementById('modal-tool-text');
        const modalToolIcon = document.getElementById('modal-tool-icon');
        
        // Current tool state
        let currentTool = null;
        let selectedCompression = 'medium';
        
        // Tool configurations
        const toolConfigs = {
            'word-to-pdf': {
                title: 'Word to PDF',
                icon: 'fa-file-word',
                hasCompression: true
            },
            'pdf-to-word': {
                title: 'PDF to Word',
                icon: 'fa-file-pdf',
                hasCompression: false
            },
            'powerpoint-to-pdf': {
                title: 'PowerPoint to PDF',
                icon: 'fa-file-powerpoint',
                hasCompression: true
            },
            'pdf-to-powerpoint': {
                title: 'PDF to PowerPoint',
                icon: 'fa-file-pdf',
                hasCompression: false
            },
            'excel-to-pdf': {
                title: 'Excel to PDF',
                icon: 'fa-file-excel',
                hasCompression: true
            },
            'pdf-to-excel': {
                title: 'PDF to Excel',
                icon: 'fa-file-pdf',
                hasCompression: false
            },
            'pdf-to-jpg': {
                title: 'PDF to JPG',
                icon: 'fa-file-image',
                hasCompression: true
            },
            'compress-pdf': {
                title: 'Compress PDF',
                icon: 'fa-compress-arrows-alt',
                hasCompression: true
            },
            'edit-pdf': {
                title: 'Edit PDF',
                icon: 'fa-edit',
                hasCompression: false
            },
            'merge-pdf': {
                title: 'Merge PDF',
                icon: 'fa-object-group',
                hasCompression: true
            },
            'split-pdf': {
                title: 'Split PDF',
                icon: 'fa-cut',
                hasCompression: false
            },
            'secure-pdf': {
                title: 'Secure PDF',
                icon: 'fa-lock',
                hasCompression: false
            }
        };
        
        // Event Listeners
        useToolBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                const tool = btn.getAttribute('data-tool');
                openToolModal(tool);
            });
        });
        
        closeModalBtn.addEventListener('click', closeModal);
        
        modal.addEventListener('click', (e) => {
            if (e.target === modal) {
                closeModal();
            }
        });
        
        uploadArea.addEventListener('click', () => fileInput.click());
        
        uploadArea.addEventListener('dragover', (e) => {
            e.preventDefault();
            uploadArea.style.background = 'rgba(37, 99, 235, 0.1)';
        });
        
        uploadArea.addEventListener('dragleave', () => {
            uploadArea.style.background = '';
        });
        
        uploadArea.addEventListener('drop', (e) => {
            e.preventDefault();
            uploadArea.style.background = '';
            if (e.dataTransfer.files.length) {
                handleFileSelect(e.dataTransfer.files[0]);
            }
        });
        
        fileInput.addEventListener('change', () => {
            if (fileInput.files.length) {
                handleFileSelect(fileInput.files[0]);
            }
        });
        
        compressionOptions.forEach(option => {
            option.addEventListener('click', () => {
                compressionOptions.forEach(opt => opt.classList.remove('selected'));
                option.classList.add('selected');
                selectedCompression = option.getAttribute('data-level');
            });
        });
        
        convertBtn.addEventListener('click', processFile);
        
        downloadBtn.addEventListener('click', downloadFile);
        
        // Functions
        function openToolModal(tool) {
            currentTool = tool;
            const config = toolConfigs[tool];
            
            // Update modal title
            modalToolTitle.textContent = config.title;
            modalToolIcon.className = 'fas ' + config.icon;
            
            // Show compression options if applicable
            optionsArea.style.display = config.hasCompression ? 'block' : 'none';
            
            // Reset UI state
            fileInfo.style.display = 'none';
            convertBtn.disabled = true;
            progressArea.style.display = 'none';
            downloadArea.style.display = 'none';
            
            // Show modal
            modal.style.display = 'flex';
        }
        
        function closeModal() {
            modal.style.display = 'none';
        }
        
        function handleFileSelect(file) {
            const validTypes = [
                'application/pdf',
                'application/msword',
                'application/vnd.openxmlformats-officedocument.wordprocessingml.document',
                'application/vnd.ms-powerpoint',
                'application/vnd.openxmlformats-officedocument.presentationml.presentation',
                'application/vnd.ms-excel',
                'application/vnd.openxmlformats-officedocument.spreadsheetml.sheet',
                'image/jpeg',
                'image/png'
            ];
            
            if (!validTypes.includes(file.type) && !file.name.match(/\.(pdf|doc|docx|ppt|pptx|xls|xlsx|jpg|jpeg|png)$/i)) {
                alert('Please select a valid document file (PDF, Word, PowerPoint, Excel, or Image).');
                return;
            }
            
            fileName.textContent = file.name;
            fileSize.textContent = formatFileSize(file.size);
            fileInfo.style.display = 'block';
            convertBtn.disabled = false;
        }
        
        function formatFileSize(bytes) {
            if (bytes === 0) return '0 Bytes';
            const k = 1024;
            const sizes = ['Bytes', 'KB', 'MB', 'GB'];
            const i = Math.floor(Math.log(bytes) / Math.log(k));
            return parseFloat((bytes / Math.pow(k, i)).toFixed(2)) + ' ' + sizes[i];
        }
        
        function processFile() {
            // Show progress area
            progressArea.style.display = 'block';
            convertBtn.disabled = true;
            
            // Simulate processing
            let progress = 0;
            const interval = setInterval(() => {
                progress += 5;
                progressBar.style.width = progress + '%';
                progressText.textContent = progress + '%';
                
                if (progress >= 100) {
                    clearInterval(interval);
                    setTimeout(() => {
                        downloadArea.style.display = 'block';
                        progressArea.style.display = 'none';
                    }, 500);
                }
            }, 100);
        }
        
        function downloadFile() {
            alert('In a real application, this would download your processed file. This is a frontend demonstration.');
            closeModal();
        }
    </script>
</body>
</html>
