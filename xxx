<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Free online tool to compress your images while maintaining quality. Reduce file size for JPG, PNG, and WebP images.">
    <meta name="keywords" content="image compressor, reduce image size, optimize images, free image tool, webp converter">
    <title>ImageCompressorPro | Free Online Image Optimization Tool</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR_ADSENSE_ID" crossorigin="anonymous"></script>
    <style>
        :root {
            --primary: #4361ee;
            --primary-dark: #3a56d4;
            --secondary: #3f37c9;
            --accent: #4895ef;
            --light: #f8f9fa;
            --dark: #212529;
            --gray: #6c757d;
            --light-gray: #e9ecef;
            --success: #4cc9f0;
            --warning: #f72585;
            --radius: 12px;
            --shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
            --transition: all 0.3s ease;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
            line-height: 1.6;
            color: var(--dark);
            background-color: #f5f7ff;
            overflow-x: hidden;
        }

        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header */
        header {
            background-color: white;
            box-shadow: var(--shadow);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
            text-decoration: none;
        }

        .logo-icon {
            color: var(--primary);
            font-size: 24px;
        }

        .logo-text {
            font-size: 20px;
            font-weight: 700;
            color: var(--dark);
            background: linear-gradient(to right, var(--primary), var(--accent));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 25px;
        }

        nav a {
            text-decoration: none;
            color: var(--gray);
            font-weight: 500;
            transition: var(--transition);
            font-size: 15px;
        }

        nav a:hover {
            color: var(--primary);
        }

        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            font-size: 24px;
            color: var(--dark);
            cursor: pointer;
        }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 60px 0 40px;
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 15px;
            background: linear-gradient(to right, var(--primary), var(--accent));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            line-height: 1.2;
        }

        .hero p {
            color: var(--gray);
            max-width: 700px;
            margin: 0 auto 30px;
            font-size: 1.1rem;
        }

        /* Main Tool Container */
        .tool-container {
            background-color: white;
            border-radius: var(--radius);
            box-shadow: var(--shadow);
            overflow: hidden;
            margin-bottom: 40px;
        }

        /* Upload Section */
        .upload-section {
            padding: 30px;
            border-bottom: 1px solid var(--light-gray);
        }

        .upload-area {
            border: 2px dashed var(--light-gray);
            border-radius: var(--radius);
            padding: 40px 20px;
            text-align: center;
            cursor: pointer;
            transition: var(--transition);
            position: relative;
            background-color: #fafbff;
        }

        .upload-area:hover {
            border-color: var(--primary);
            background-color: rgba(67, 97, 238, 0.03);
        }

        .upload-area.active {
            border-color: var(--success);
            background-color: rgba(76, 201, 240, 0.05);
        }

        .upload-icon {
            font-size: 48px;
            color: var(--primary);
            margin-bottom: 15px;
        }

        .upload-text {
            margin-bottom: 10px;
            font-weight: 500;
        }

        .upload-hint {
            color: var(--gray);
            font-size: 14px;
        }

        .upload-area input {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            opacity: 0;
            cursor: pointer;
        }

        /* Controls Section */
        .controls-section {
            padding: 30px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .control-group {
            margin-bottom: 15px;
        }

        .control-group h3 {
            margin-bottom: 15px;
            color: var(--dark);
            font-size: 18px;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .control-group h3 i {
            color: var(--primary);
        }

        .slider-container {
            margin-bottom: 20px;
        }

        .slider-container label {
            display: flex;
            justify-content: space-between;
            margin-bottom: 8px;
            font-size: 14px;
            color: var(--gray);
        }

        .slider-container input[type="range"] {
            width: 100%;
            height: 8px;
            -webkit-appearance: none;
            background: var(--light-gray);
            border-radius: 10px;
            outline: none;
        }

        .slider-container input[type="range"]::-webkit-slider-thumb {
            -webkit-appearance: none;
            width: 20px;
            height: 20px;
            background: var(--primary);
            border-radius: 50%;
            cursor: pointer;
            box-shadow: 0 2px 6px rgba(67, 97, 238, 0.3);
            transition: var(--transition);
        }

        .slider-container input[type="range"]::-webkit-slider-thumb:hover {
            transform: scale(1.1);
        }

        .format-options {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(80px, 1fr));
            gap: 10px;
            margin-top: 15px;
        }

        .format-option input {
            display: none;
        }

        .format-option label {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 12px 10px;
            background-color: var(--light-gray);
            border-radius: 8px;
            cursor: pointer;
            transition: var(--transition);
            font-size: 14px;
        }

        .format-option label i {
            font-size: 20px;
            margin-bottom: 5px;
            color: var(--gray);
        }

        .format-option input:checked + label {
            background-color: var(--primary);
            color: white;
        }

        .format-option input:checked + label i {
            color: white;
        }

        /* Action Buttons */
        .action-buttons {
            display: flex;
            gap: 15px;
            padding: 0 30px 30px;
        }

        .btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            padding: 12px 24px;
            border: none;
            border-radius: var(--radius);
            font-weight: 500;
            cursor: pointer;
            transition: var(--transition);
            font-size: 15px;
        }

        .btn-primary {
            background-color: var(--primary);
            color: white;
            box-shadow: 0 4px 12px rgba(67, 97, 238, 0.2);
        }

        .btn-primary:hover {
            background-color: var(--primary-dark);
            transform: translateY(-2px);
        }

        .btn-secondary {
            background-color: white;
            color: var(--gray);
            border: 1px solid var(--light-gray);
        }

        .btn-secondary:hover {
            background-color: var(--light);
            border-color: var(--gray);
        }

        .btn:disabled {
            opacity: 0.6;
            cursor: not-allowed;
            transform: none !important;
        }

        /* Loading Spinner */
        .spinner-container {
            display: none;
            padding: 30px;
            text-align: center;
        }

        .spinner {
            width: 50px;
            height: 50px;
            border: 4px solid rgba(67, 97, 238, 0.1);
            border-radius: 50%;
            border-top: 4px solid var(--primary);
            animation: spin 1s linear infinite;
            margin: 0 auto 20px;
        }

        .spinner-text {
            color: var(--gray);
            font-size: 15px;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        /* Results Section */
        .results-section {
            display: none;
            padding: 30px;
            border-top: 1px solid var(--light-gray);
        }

        .results-title {
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
            color: var(--dark);
        }

        .results-title i {
            color: var(--success);
        }

        .comparison {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin-bottom: 25px;
        }

        .image-card {
            background-color: white;
            border-radius: var(--radius);
            overflow: hidden;
            box-shadow: var(--shadow);
        }

        .image-container {
            position: relative;
            padding-top: 56.25%;
            overflow: hidden;
        }

        .image-container img {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: contain;
            background-color: var(--light);
        }

        .image-info {
            padding: 18px;
        }

        .image-info h3 {
            margin-bottom: 12px;
            font-size: 16px;
        }

        .image-stats {
            display: grid;
            gap: 8px;
        }

        .stat-item {
            display: flex;
            justify-content: space-between;
            font-size: 14px;
        }

        .stat-label {
            color: var(--gray);
        }

        .stat-value {
            font-weight: 500;
        }

        .savings {
            color: var(--success);
            font-weight: 600;
        }

        .download-btn {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            width: 100%;
            padding: 12px;
            background-color: var(--success);
            color: white;
            border: none;
            border-radius: 0 0 var(--radius) var(--radius);
            font-weight: 500;
            cursor: pointer;
            transition: var(--transition);
        }

        .download-btn:hover {
            background-color: #3ab5d8;
        }

        /* Ad Containers */
        .ad-container {
            background-color: white;
            border-radius: var(--radius);
            padding: 20px;
            margin: 40px 0;
            text-align: center;
            box-shadow: var(--shadow);
        }

        .ad-label {
            font-size: 12px;
            color: var(--gray);
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 10px;
        }

        /* Features Section */
        .features-section {
            margin: 50px 0;
        }

        .section-title {
            text-align: center;
            margin-bottom: 40px;
            font-size: 28px;
            color: var(--dark);
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }

        .feature-card {
            background-color: white;
            border-radius: var(--radius);
            padding: 30px;
            box-shadow: var(--shadow);
            transition: var(--transition);
        }

        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
        }

        .feature-icon {
            width: 60px;
            height: 60px;
            background-color: rgba(67, 97, 238, 0.1);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 20px;
            color: var(--primary);
            font-size: 24px;
        }

        .feature-card h3 {
            margin-bottom: 15px;
            font-size: 18px;
        }

        .feature-card p {
            color: var(--gray);
            font-size: 15px;
            line-height: 1.6;
        }

        /* Footer */
        footer {
            background-color: var(--dark);
            color: white;
            padding: 60px 0 30px;
        }

        .footer-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 40px;
            margin-bottom: 40px;
        }

        .footer-logo {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-bottom: 20px;
            font-size: 20px;
            font-weight: 700;
            color: white;
            text-decoration: none;
        }

        .footer-logo i {
            color: var(--accent);
        }

        .footer-about p {
            color: #adb5bd;
            margin-bottom: 20px;
            font-size: 14px;
            line-height: 1.6;
        }

        .social-links {
            display: flex;
            gap: 15px;
        }

        .social-link {
            width: 36px;
            height: 36px;
            border-radius: 50%;
            background-color: rgba(255, 255, 255, 0.1);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            transition: var(--transition);
        }

        .social-link:hover {
            background-color: var(--primary);
            transform: translateY(-3px);
        }

        .footer-heading {
            font-size: 18px;
            margin-bottom: 20px;
            position: relative;
            padding-bottom: 10px;
        }

        .footer-heading::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 40px;
            height: 2px;
            background-color: var(--accent);
        }

        .footer-links {
            list-style: none;
        }

        .footer-links li {
            margin-bottom: 12px;
        }

        .footer-links a {
            color: #adb5bd;
            text-decoration: none;
            transition: var(--transition);
            font-size: 14px;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .footer-links a:hover {
            color: white;
            transform: translateX(5px);
        }

        .footer-links a i {
            font-size: 12px;
            color: var(--accent);
        }

        .copyright {
            text-align: center;
            padding-top: 30px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: #adb5bd;
            font-size: 14px;
        }

        /* Responsive Styles */
        @media (max-width: 992px) {
            .hero h1 {
                font-size: 2.2rem;
            }
        }

        @media (max-width: 768px) {
            .header-container {
                padding: 15px 0;
            }

            nav {
                position: fixed;
                top: 70px;
                left: 0;
                width: 100%;
                background-color: white;
                box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
                padding: 20px;
                transform: translateY(-150%);
                transition: var(--transition);
                z-index: 99;
            }

            nav.active {
                transform: translateY(0);
            }

            nav ul {
                flex-direction: column;
                gap: 15px;
            }

            .mobile-menu-btn {
                display: block;
            }

            .hero {
                padding: 40px 0 30px;
            }

            .hero h1 {
                font-size: 2rem;
            }

            .hero p {
                font-size: 1rem;
            }

            .action-buttons {
                flex-direction: column;
            }

            .btn {
                width: 100%;
            }
        }

        @media (max-width: 576px) {
            .hero h1 {
                font-size: 1.8rem;
            }

            .upload-section, .controls-section, .action-buttons {
                padding: 20px;
            }

            .control-group {
                margin-bottom: 25px;
            }

            .features-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container header-container">
            <a href="#" class="logo">
                <i class="fas fa-compress-alt logo-icon"></i>
                <span class="logo-text">ImageCompressorPro</span>
            </a>
            
            <nav id="mainNav">
                <ul>
                    <li><a href="#"><i class="fas fa-home"></i> Home</a></li>
                    <li><a href="#"><i class="fas fa-question-circle"></i> How It Works</a></li>
                    <li><a href="#"><i class="fas fa-star"></i> Features</a></li>
                    <li><a href="#"><i class="fas fa-envelope"></i> Contact</a></li>
                </ul>
            </nav>
            
            <button class="mobile-menu-btn" id="mobileMenuBtn">
                <i class="fas fa-bars"></i>
            </button>
        </div>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Hero Section -->
        <section class="hero">
            <div class="container">
                <h1>Optimize Your Images in Seconds</h1>
                <p>Reduce image file size without sacrificing quality. Perfect for websites, social media, and email attachments.</p>
            </div>
        </section>

        <!-- Ad Container -->
        <div class="container">
            <div class="ad-container">
                <div class="ad-label">Advertisement</div>
                <!-- Replace with your AdSense ad unit -->
                <ins class="adsbygoogle"
                     style="display:block"
                     data-ad-client="ca-pub-YOUR_ADSENSE_ID"
                     data-ad-slot="YOUR_AD_SLOT_ID"
                     data-ad-format="auto"
                     data-full-width-responsive="true"></ins>
                <script>
                     (adsbygoogle = window.adsbygoogle || []).push({});
                </script>
            </div>
        </div>

        <!-- Tool Container -->
        <div class="container">
            <div class="tool-container">
                <!-- Upload Section -->
                <div class="upload-section">
                    <div class="upload-area" id="uploadArea">
                        <i class="fas fa-cloud-upload-alt upload-icon"></i>
                        <p class="upload-text">Drag & drop your image here or click to browse</p>
                        <p class="upload-hint">Supports: JPG, PNG, WebP (Max 10MB)</p>
                        <input type="file" id="fileInput" accept="image/jpeg, image/png, image/webp">
                    </div>
                </div>

                <!-- Controls Section -->
                <div class="controls-section">
                    <div class="control-column">
                        <div class="control-group">
                            <h3><i class="fas fa-sliders-h"></i> Compression Settings</h3>
                            <div class="slider-container">
                                <label for="qualityRange">
                                    <span>Quality</span>
                                    <span id="qualityValue">80%</span>
                                </label>
                                <input type="range" id="qualityRange" min="1" max="100" value="80">
                            </div>
                            <div class="slider-container">
                                <label for="resizeRange">
                                    <span>Resize</span>
                                    <span id="resizeValue">100%</span>
                                </label>
                                <input type="range" id="resizeRange" min="10" max="100" value="100">
                            </div>
                        </div>
                    </div>
                    
                    <div class="control-column">
                        <div class="control-group">
                            <h3><i class="fas fa-file-image"></i> Output Format</h3>
                            <div class="format-options">
                                <div class="format-option">
                                    <input type="radio" id="formatOriginal" name="format" value="original" checked>
                                    <label for="formatOriginal">
                                        <i class="fas fa-file"></i>
                                        Original
                                    </label>
                                </div>
                                <div class="format-option">
                                    <input type="radio" id="formatJpg" name="format" value="jpg">
                                    <label for="formatJpg">
                                        <i class="fas fa-file-image"></i>
                                        JPG
                                    </label>
                                </div>
                                <div class="format-option">
                                    <input type="radio" id="formatPng" name="format" value="png">
                                    <label for="formatPng">
                                        <i class="fas fa-file-image"></i>
                                        PNG
                                    </label>
                                </div>
                                <div class="format-option">
                                    <input type="radio" id="formatWebp" name="format" value="webp">
                                    <label for="formatWebp">
                                        <i class="fas fa-file-image"></i>
                                        WebP
                                    </label>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Loading Spinner -->
                <div class="spinner-container" id="spinnerContainer">
                    <div class="spinner"></div>
                    <p class="spinner-text">Compressing your image...</p>
                </div>

                <!-- Action Buttons -->
                <div class="action-buttons">
                    <button id="compressBtn" class="btn btn-primary" disabled>
                        <i class="fas fa-compress-alt"></i> Compress Image
                    </button>
                    <button id="resetBtn" class="btn btn-secondary">
                        <i class="fas fa-redo"></i> Reset
                    </button>
                </div>

                <!-- Results Section -->
                <div class="results-section" id="resultsSection">
                    <h2 class="results-title">
                        <i class="fas fa-check-circle"></i> Compression Results
                    </h2>
                    
                    <div class="comparison">
                        <!-- Original Image Card -->
                        <div class="image-card">
                            <div class="image-container">
                                <img id="originalImage" src="" alt="Original image">
                            </div>
                            <div class="image-info">
                                <h3>Original Image</h3>
                                <div class="image-stats">
                                    <div class="stat-item">
                                        <span class="stat-label">File Size:</span>
                                        <span class="stat-value" id="originalSize">0 KB</span>
                                    </div>
                                    <div class="stat-item">
                                        <span class="stat-label">Dimensions:</span>
                                        <span class="stat-value" id="originalDimensions">0 × 0 px</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                        
                        <!-- Compressed Image Card -->
                        <div class="image-card">
                            <div class="image-container">
                                <img id="compressedImage" src="" alt="Compressed image">
                            </div>
                            <div class="image-info">
                                <h3>Compressed Image</h3>
                                <div class="image-stats">
                                    <div class="stat-item">
                                        <span class="stat-label">File Size:</span>
                                        <span class="stat-value" id="compressedSize">0 KB</span>
                                    </div>
                                    <div class="stat-item">
                                        <span class="stat-label">Dimensions:</span>
                                        <span class="stat-value" id="compressedDimensions">0 × 0 px</span>
                                    </div>
                                    <div class="stat-item">
                                        <span class="stat-label">Reduction:</span>
                                        <span class="stat-value savings" id="savings">0%</span>
                                    </div>
                                </div>
                            </div>
                            <button id="downloadBtn" class="download-btn">
                                <i class="fas fa-download"></i> Download Compressed Image
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Ad Container -->
        <div class="container">
            <div class="ad-container">
                <div class="ad-label">Advertisement</div>
                <!-- Replace with your AdSense ad unit -->
                <ins class="adsbygoogle"
                     style="display:block"
                     data-ad-client="ca-pub-YOUR_ADSENSE_ID"
                     data-ad-slot="YOUR_AD_SLOT_ID"
                     data-ad-format="auto"
                     data-full-width-responsive="true"></ins>
                <script>
                     (adsbygoogle = window.adsbygoogle || []).push({});
                </script>
            </div>
        </div>

        <!-- Features Section -->
        <section class="features-section">
            <div class="container">
                <h2 class="section-title">Why Choose Our Image Compressor?</h2>
                
                <div class="features-grid">
                    <div class="feature-card">
                        <div class="feature-icon">
                            <i class="fas fa-bolt"></i>
                        </div>
                        <h3>Lightning Fast</h3>
                        <p>Our advanced algorithms compress images in seconds without uploading to any servers - all processing happens in your browser.</p>
                    </div>
                    
                    <div class="feature-card">
                        <div class="feature-icon">
                            <i class="fas fa-lock"></i>
                        </div>
                        <h3>100% Private</h3>
                        <p>Your images never leave your device. We don't store or access your files, ensuring complete privacy and security.</p>
                    </div>
                    
                    <div class="feature-card">
                        <div class="feature-icon">
                            <i class="fas fa-mobile-alt"></i>
                        </div>
                        <h3>Mobile Friendly</h3>
                        <p>Works perfectly on all devices including smartphones and tablets. Compress images anytime, anywhere.</p>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-grid">
                <div class="footer-about">
                    <a href="#" class="footer-logo">
                        <i class="fas fa-compress-alt"></i>
                        <span>ImageCompressorPro</span>
                    </a>
                    <p>The free online tool to compress your images while maintaining visual quality. Perfect for web developers, designers, and photographers.</p>
                    <div class="social-links">
                        <a href="#" class="social-link"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-github"></i></a>
                    </div>
                </div>
                
                <div class="footer-links-container">
                    <h3 class="footer-heading">Quick Links</h3>
                    <ul class="footer-links">
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Home</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> How It Works</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Features</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> FAQ</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Contact</a></li>
                    </ul>
                </div>
                
                <div class="footer-links-container">
                    <h3 class="footer-heading">Resources</h3>
                    <ul class="footer-links">
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Image Optimization Guide</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> WebP vs JPEG</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> PNG Compression</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Blog</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Privacy Policy</a></li>
                    </ul>
                </div>
                
                <div class="footer-links-container">
                    <h3 class="footer-heading">Support</h3>
                    <ul class="footer-links">
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Help Center</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Contact Us</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Feedback</a></li>
                        <li><a href="#"><i class="fas fa-chevron-right"></i> Report Issue</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="copyright">
                &copy; <span id="currentYear"></span> ImageCompressorPro. All rights reserved.
            </div>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Set current year in footer
            const currentYear = new Date().getFullYear();
            document.getElementById('currentYear').textContent = currentYear;
            
            // Mobile menu toggle
            const mobileMenuBtn = document.getElementById('mobileMenuBtn');
            const mainNav = document.getElementById('mainNav');
            
            mobileMenuBtn.addEventListener('click', function() {
                mainNav.classList.toggle('active');
                this.innerHTML = mainNav.classList.contains('active') ? 
                    '<i class="fas fa-times"></i>' : '<i class="fas fa-bars"></i>';
            });
            
            // Close mobile menu when clicking on a link
            document.querySelectorAll('nav a').forEach(link => {
                link.addEventListener('click', () => {
                    if (window.innerWidth <= 768) {
                        mainNav.classList.remove('active');
                        mobileMenuBtn.innerHTML = '<i class="fas fa-bars"></i>';
                    }
                });
            });
            
            // Image compression functionality
            const fileInput = document.getElementById('fileInput');
            const uploadArea = document.getElementById('uploadArea');
            const compressBtn = document.getElementById('compressBtn');
            const resetBtn = document.getElementById('resetBtn');
            const qualityRange = document.getElementById('qualityRange');
            const qualityValue = document.getElementById('qualityValue');
            const resizeRange = document.getElementById('resizeRange');
            const resizeValue = document.getElementById('resizeValue');
            const resultsSection = document.getElementById('resultsSection');
            const spinnerContainer = document.getElementById('spinnerContainer');
            const downloadBtn = document.getElementById('downloadBtn');
            
            let originalFile = null;
            let compressedBlob = null;
            
            // Update quality value display
            qualityRange.addEventListener('input', function() {
                qualityValue.textContent = this.value + '%';
            });
            
            // Update resize value display
            resizeRange.addEventListener('input', function() {
                resizeValue.textContent = this.value + '%';
            });
            
            // Handle file selection
            fileInput.addEventListener('change', function(e) {
                if (e.target.files.length > 0) {
                    originalFile = e.target.files[0];
                    
                    // Validate file type
                    const validTypes = ['image/jpeg', 'image/png', 'image/webp'];
                    if (!validTypes.includes(originalFile.type)) {
                        showError('Please select a valid image file (JPG, PNG, or WebP)');
                        resetAll();
                        return;
                    }
                    
                    // Validate file size (10MB max)
                    if (originalFile.size > 10 * 1024 * 1024) {
                        showError('File size exceeds 10MB limit');
                        resetAll();
                        return;
                    }
                    
                    // Update UI
                    uploadArea.innerHTML = `
                        <i class="fas fa-check-circle upload-icon" style="color: var(--success)"></i>
                        <p class="upload-text"><strong>${originalFile.name}</strong></p>
                        <p class="upload-hint">${formatFileSize(originalFile.size)} - Ready to compress</p>
                        <input type="file" id="fileInput" accept="image/jpeg, image/png, image/webp">
                    `;
                    uploadArea.classList.add('active');
                    
                    compressBtn.disabled = false;
                    
                    // Display original image info
                    displayOriginalImage(originalFile);
                }
            });
            
            // Handle drag and drop
            ['dragenter', 'dragover', 'dragleave', 'drop'].forEach(eventName => {
                uploadArea.addEventListener(eventName, preventDefaults, false);
                document.body.addEventListener(eventName, preventDefaults, false);
            });
            
            function preventDefaults(e) {
                e.preventDefault();
                e.stopPropagation();
            }
            
            ['dragenter', 'dragover'].forEach(eventName => {
                uploadArea.addEventListener(eventName, highlight, false);
            });
            
            ['dragleave', 'drop'].forEach(eventName => {
                uploadArea.addEventListener(eventName, unhighlight, false);
            });
            
            function highlight() {
                uploadArea.classList.add('highlight');
                uploadArea.style.borderColor = 'var(--primary)';
                uploadArea.style.backgroundColor = 'rgba(67, 97, 238, 0.05)';
            }
            
            function unhighlight() {
                uploadArea.classList.remove('highlight');
                uploadArea.style.borderColor = '';
                uploadArea.style.backgroundColor = '';
            }
            
            uploadArea.addEventListener('drop', function(e) {
                const dt = e.dataTransfer;
                const files = dt.files;
                
                if (files.length > 0) {
                    fileInput.files = files;
                    const event = new Event('change');
                    fileInput.dispatchEvent(event);
                }
            });
            
            // Compress button click
            compressBtn.addEventListener('click', function() {
                if (!originalFile) return;
                
                // Show loading state
                spinnerContainer.style.display = 'block';
                resultsSection.style.display = 'none';
                compressBtn.disabled = true;
                compressBtn.innerHTML = '<i class="fas fa-spinner fa-spin"></i> Processing...';
                
                // Use setTimeout to allow UI to update before compression starts
                setTimeout(() => {
                    compressImage(originalFile);
                }, 100);
            });
            
            // Reset button click
            resetBtn.addEventListener('click', resetAll);
            
            // Download button click
            downloadBtn.addEventListener('click', function() {
                if (!compressedBlob) return;
                
                const url = URL.createObjectURL(compressedBlob);
                const a = document.createElement('a');
                a.href = url;
                
                // Get the selected format
                const selectedFormat = document.querySelector('input[name="format"]:checked').value;
                let extension = originalFile.name.split('.').pop().toLowerCase();
                
                if (selectedFormat !== 'original') {
                    extension = selectedFormat;
                }
                
                // Create download filename
                const filename = originalFile.name.replace(/\.[^/.]+$/, "") + '-compressed.' + extension;
                a.download = filename;
                
                document.body.appendChild(a);
                a.click();
                
                // Clean up
                setTimeout(() => {
                    document.body.removeChild(a);
                    URL.revokeObjectURL(url);
                }, 100);
            });
            
            // Display original image info
            function displayOriginalImage(file) {
                const reader = new FileReader();
                
                reader.onload = function(e) {
                    const img = new Image();
                    
                    img.onload = function() {
                        document.getElementById('originalImage').src = e.target.result;
                        document.getElementById('originalSize').textContent = formatFileSize(file.size);
                        document.getElementById('originalDimensions').textContent = `${img.width} × ${img.height} px`;
                    };
                    
                    img.onerror = function() {
                        showError('Error loading image. Please try another file.');
                        resetAll();
                    };
                    
                    img.src = e.target.result;
                };
                
                reader.onerror = function() {
                    showError('Error reading file. Please try again.');
                    resetAll();
                };
                
                reader.readAsDataURL(file);
            }
            
            // Compress image function
            function compressImage(file) {
                const reader = new FileReader();
                
                reader.onload = function(e) {
                    const img = new Image();
                    
                    img.onload = function() {
                        // Get compression settings
                        const quality = parseInt(qualityRange.value) / 100;
                        const resizePercentage = parseInt(resizeRange.value) / 100;
                        const selectedFormat = document.querySelector('input[name="format"]:checked').value;
                        
                        // Calculate new dimensions while maintaining aspect ratio
                        const newWidth = Math.round(img.width * resizePercentage);
                        const newHeight = Math.round(img.height * resizePercentage);
                        
                        // Create canvas
                        const canvas = document.createElement('canvas');
                        const ctx = canvas.getContext('2d');
                        
                        // Set canvas dimensions
                        canvas.width = newWidth;
                        canvas.height = newHeight;
                        
                        // Apply image smoothing for better quality
                        ctx.imageSmoothingQuality = 'high';
                        
                        // Draw image with new dimensions
                        ctx.drawImage(img, 0, 0, newWidth, newHeight);
                        
                        // Determine output format
                        let mimeType = file.type;
                        if (selectedFormat !== 'original') {
                            mimeType = `image/${selectedFormat}`;
                        }
                        
                        // Convert to blob with specified quality
                        canvas.toBlob(function(blob) {
                            // Hide spinner and restore button
                            spinnerContainer.style.display = 'none';
                            compressBtn.disabled = false;
                            compressBtn.innerHTML = '<i class="fas fa-compress-alt"></i> Compress Image';
                            
                            if (!blob) {
                                showError('Compression failed. Please try again.');
                                return;
                            }
                            
                            compressedBlob = blob;
                            
                            // Display results
                            document.getElementById('compressedImage').src = URL.createObjectURL(blob);
                            document.getElementById('compressedSize').textContent = formatFileSize(blob.size);
                            document.getElementById('compressedDimensions').textContent = `${newWidth} × ${newHeight} px`;
                            
                            const reduction = Math.round(((file.size - blob.size) / file.size) * 100);
                            document.getElementById('savings').textContent = `${reduction}%`;
                            
                            resultsSection.style.display = 'block';
                            
                            // Scroll to results smoothly
                            resultsSection.scrollIntoView({ behavior: 'smooth', block: 'start' });
                            
                        }, mimeType, quality);
                    };
                    
                    img.onerror = function() {
                        showError('Error loading image. Please try another file.');
                        resetCompressionUI();
                    };
                    
                    img.src = e.target.result;
                };
                
                reader.onerror = function() {
                    showError('Error reading file. Please try again.');
                    resetCompressionUI();
                };
                
                reader.readAsDataURL(file);
            }
            
            // Reset all fields
            function resetAll() {
                fileInput.value = '';
                originalFile = null;
                compressedBlob = null;
                
                uploadArea.innerHTML = `
                    <i class="fas fa-cloud-upload-alt upload-icon"></i>
                    <p class="upload-text">Drag & drop your image here or click to browse</p>
                    <p class="upload-hint">Supports: JPG, PNG, WebP (Max 10MB)</p>
                    <input type="file" id="fileInput" accept="image/jpeg, image/png, image/webp">
                `;
                uploadArea.classList.remove('active', 'highlight');
                
                compressBtn.disabled = true;
                compressBtn.innerHTML = '<i class="fas fa-compress-alt"></i> Compress Image';
                
                qualityRange.value = 80;
                qualityValue.textContent = '80%';
                
                resizeRange.value = 100;
                resizeValue.textContent = '100%';
                
                document.getElementById('formatOriginal').checked = true;
                
                resultsSection.style.display = 'none';
                spinnerContainer.style.display = 'none';
                
                // Reset file input event listeners
                const newFileInput = uploadArea.querySelector('#fileInput');
                newFileInput.addEventListener('change', fileInput.onchange);
            }
            
            // Reset just the compression UI (when errors occur)
            function resetCompressionUI() {
                spinnerContainer.style.display = 'none';
                compressBtn.disabled = false;
                compressBtn.innerHTML = '<i class="fas fa-compress-alt"></i> Compress Image';
            }
            
            // Format file size
            function formatFileSize(bytes) {
                if (bytes === 0) return '0 Bytes';
                const k = 1024;
                const sizes = ['Bytes', 'KB', 'MB', 'GB'];
                const i = Math.floor(Math.log(bytes) / Math.log(k));
                return parseFloat((bytes / Math.pow(k, i)).toFixed(2)) + ' ' + sizes[i];
            }
            
            // Show error message
            function showError(message) {
                const errorDiv = document.createElement('div');
                errorDiv.style.position = 'fixed';
                errorDiv.style.top = '20px';
                errorDiv.style.left = '50%';
                errorDiv.style.transform = 'translateX(-50%)';
                errorDiv.style.backgroundColor = 'var(--warning)';
                errorDiv.style.color = 'white';
                errorDiv.style.padding = '12px 24px';
                errorDiv.style.borderRadius = 'var(--radius)';
                errorDiv.style.boxShadow = 'var(--shadow)';
                errorDiv.style.zIndex = '1000';
                errorDiv.style.animation = 'fadeIn 0.3s ease';
                errorDiv.textContent = message;
                
                document.body.appendChild(errorDiv);
                
                // Remove after 5 seconds
                setTimeout(() => {
                    errorDiv.style.animation = 'fadeOut 0.3s ease';
                    setTimeout(() => {
                        document.body.removeChild(errorDiv);
                    }, 300);
                }, 5000);
                
                // Add keyframes for animation
                const style = document.createElement('style');
                style.textContent = `
                    @keyframes fadeIn {
                        from { opacity: 0; transform: translateX(-50%) translateY(-20px); }
                        to { opacity: 1; transform: translateX(-50%) translateY(0); }
                    }
                    @keyframes fadeOut {
                        from { opacity: 1; transform: translateX(-50%) translateY(0); }
                        to { opacity: 0; transform: translateX(-50%) translateY(-20px); }
                    }
                `;
                document.head.appendChild(style);
            }
        });
    </script>
</body>
</html>
