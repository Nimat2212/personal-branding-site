<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Branding Model</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        .section {
            background: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
        }
        .visual {
            text-align: center;
            margin-top: 20px;
        }
        .visual img {
            max-width: 100%;
            border-radius: 10px;
        }
        footer {
            text-align: center;
            padding: 15px;
            background: #333;
            color: white;
        }
        .form-group {
            margin-bottom: 15px;
        }
        label {
            font-weight: bold;
        }
        select, input, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background: #333;
            color: white;
            padding: 10px 15px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            display: block;
            margin-top: 10px;
        }
        button:hover {
            background: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>Personal Branding Model</h1>
    </header>
    <div class="container">
        <div class="section">
            <h2>Introduction</h2>
            <p>Personal branding is essential for success in today's world. A strong personal brand increases credibility, helps build a following, and differentiates you from competitors.</p>
            <div class="visual">
                <img src="branding_model.jpg" alt="Branding Model Visualization">
            </div>
        </div>
        <div class="section">
            <h2>Case Studies</h2>
            <p>Explore how different individuals have built strong personal brands.</p>
            <div class="visual">
                <img src="case_studies_chart.jpg" alt="Case Studies Overview">
            </div>
            <ul>
                <li><strong>Oprah Winfrey</strong> - Media & Empowerment</li>
                <li><strong>Elon Musk</strong> - Innovation & Social Media</li>
                <li><strong>Kim Kardashian</strong> - Luxury & Lifestyle</li>
                <li><strong>Gary Vaynerchuk</strong> - Digital Marketing</li>
                <li><strong>Michelle Obama</strong> - Leadership & Advocacy</li>
                <li><strong>MrBeast</strong> - Content & Philanthropy</li>
            </ul>
        </div>
        <div class="section">
            <h2>Branding Model</h2>
            <p>Our model categorizes branding strategies into essential components:</p>
            <div class="visual">
                <img src="branding_components.jpg" alt="Branding Strategy Components">
            </div>
            <ul>
                <li><strong>Authenticity:</strong> Staying true to your values and personality.</li>
                <li><strong>Digital Presence:</strong> Utilizing social media, blogs, and personal websites.</li>
                <li><strong>Partnerships:</strong> Collaborating with industry leaders and influencers.</li>
                <li><strong>Adaptability:</strong> Evolving as trends and industries change.</li>
                <li><strong>Strategic Messaging:</strong> Communicating your story effectively.</li>
            </ul>
        </div>
        <div class="section">
            <h2>Interactive Branding Builder</h2>
            <p>Define your personal brand by selecting key traits below.</p>
            <form id="brandForm">
                <div class="form-group">
                    <label for="persona">What best describes your brand persona?</label>
                    <select id="persona">
                        <option value="innovative">Innovative</option>
                        <option value="influential">Influential</option>
                        <option value="creative">Creative</option>
                        <option value="entrepreneurial">Entrepreneurial</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="platform">Which platform do you use the most?</label>
                    <select id="platform">
                        <option value="social media">Social Media</option>
                        <option value="personal website">Personal Website</option>
                        <option value="public speaking">Public Speaking</option>
                        <option value="video content">Video Content</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="goal">What is your main branding goal?</label>
                    <select id="goal">
                        <option value="build influence">Build Influence</option>
                        <option value="grow audience">Grow Audience</option>
                        <option value="increase credibility">Increase Credibility</option>
                        <option value="expand business">Expand Business</option>
                    </select>
                </div>
                <button type="button" onclick="displayBrandingStrategy()">Generate Branding Strategy</button>
            </form>
            <div id="result" class="section" style="display:none;">
                <h2>Your Branding Strategy</h2>
                <p id="advice"></p>
            </div>
        </div>
    </div>
    <footer>
        <p>&copy; 2025 Personal Branding Model | All Rights Reserved</p>
    </footer>
    <script>
        function displayBrandingStrategy() {
            const persona = document.getElementById('persona').value;
            const platform = document.getElementById('platform').value;
            const goal = document.getElementById('goal').value;
            
            const strategy = `You should focus on being a ${persona} individual. Utilize ${platform} to establish your brand presence. Your primary goal should be to ${goal}, so tailor your content and interactions accordingly.`;
            
            document.getElementById('advice').innerText = strategy;
            document.getElementById('result').style.display = 'block';
        }
    </script>
</body>
</html>
