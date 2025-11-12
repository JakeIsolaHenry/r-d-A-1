<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>System1 - Monetizing Content for Creators</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Arial, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            background-attachment: fixed;
            overflow-x: hidden;
            min-height: 100vh;
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .solar-flow-section .container {
            background: transparent;
        }

        .header {
            text-align: center;
            padding: 60px 20px 40px;
            color: white;
        }

        .header h1 {
            font-size: 48px;
            font-weight: 700;
            margin-bottom: 20px;
            letter-spacing: -1px;
        }

        .system1-logo {
            font-size: 24px;
            margin-bottom: 10px;
            font-weight: 600;
        }

        .tab-container {
            display: flex;
            justify-content: center;
            gap: 10px;
            padding: 20px;
            flex-wrap: wrap;
        }

        .tab-button {
            background: rgba(255, 255, 255, 0.2);
            color: white;
            border: 2px solid rgba(255, 255, 255, 0.3);
            padding: 12px 32px;
            border-radius: 25px;
            font-size: 16px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            backdrop-filter: blur(10px);
        }

        .tab-button:hover {
            background: rgba(255, 255, 255, 0.3);
            transform: translateY(-2px);
        }

        .tab-button.active {
            background: white;
            color: #667eea;
            border-color: white;
        }

        .flow-section {
            min-height: 400vh;
            position: relative;
            display: none;
        }

        .flow-section.active {
            display: block;
        }

        .solar-flow-section .flow-section {
            background: transparent;
        }

        .sticky-container {
            position: sticky;
            top: 0;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .solar-flow-section .sticky-container {
            background: transparent;
        }

        .phone-container-wrapper {
            display: flex;
            align-items: center;
            gap: 80px;
            justify-content: center;
        }

        .phone-with-controls {
            display: flex;
            align-items: center;
            gap: 40px;
        }

        .phone-container {
            display: flex;
            gap: 80px;
            align-items: center;
            justify-content: center;
        }

        .phone {
            width: 320px;
            height: 650px;
            background: #1a1a1a;
            border-radius: 40px;
            padding: 12px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.4);
            position: relative;
            opacity: 0;
            transform: translateY(100px);
            transition: all 0.8s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .phone.visible {
            opacity: 1;
            transform: translateY(0);
        }

        .phone-screen {
            width: 100%;
            height: 100%;
            background: white;
            border-radius: 32px;
            overflow: hidden;
            position: relative;
        }

        .phone-notch {
            position: absolute;
            top: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 150px;
            height: 28px;
            background: #1a1a1a;
            border-radius: 0 0 20px 20px;
            z-index: 10;
        }

        .arrow {
            font-size: 60px;
            color: white;
            opacity: 0;
            transform: scale(0);
            transition: all 0.6s cubic-bezier(0.68, -0.55, 0.265, 1.55);
        }

        .arrow.visible {
            opacity: 1;
            transform: scale(1);
        }

        .phone-content {
            padding: 40px 20px 20px;
            height: 100%;
            overflow-y: auto;
        }

        .phone-content::-webkit-scrollbar {
            width: 4px;
        }

        .phone-content::-webkit-scrollbar-thumb {
            background: #ccc;
            border-radius: 2px;
        }

        .linktree {
            background: linear-gradient(180deg, #FFB6D9 0%, #FFC9E3 100%);
            height: 100%;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .linktree.blue {
            background: linear-gradient(180deg, #a8edea 0%, #fed6e3 100%);
        }

        .linktree.purple {
            background: linear-gradient(180deg, #d4a5ff 0%, #e8c4ff 100%);
        }

        .linktree.green {
            background: linear-gradient(180deg, #a8e6cf 0%, #dcedc1 100%);
        }

        .profile-pic {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            background: #FFD93D;
            margin: 20px 0;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 32px;
            font-weight: 700;
            color: #333;
        }

        .username {
            font-size: 18px;
            font-weight: 600;
            margin-bottom: 10px;
        }

        .bio {
            font-size: 12px;
            text-align: center;
            margin-bottom: 20px;
            padding: 0 20px;
            color: #333;
        }

        .social-icons {
            display: flex;
            gap: 15px;
            margin-bottom: 30px;
        }

        .social-icon {
            width: 30px;
            height: 30px;
            background: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 14px;
        }

        .link-button {
            width: 260px;
            padding: 15px;
            background: white;
            border-radius: 25px;
            margin: 8px 0;
            text-align: center;
            font-size: 13px;
            font-weight: 500;
            cursor: pointer;
            transition: transform 0.2s;
        }

        .link-button:hover {
            transform: scale(1.05);
        }

        .link-button.highlight {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            font-weight: 600;
        }

        .link-button.highlight-alt1 {
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
            color: white;
            font-weight: 600;
        }

        .link-button.highlight-alt2 {
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
            color: white;
            font-weight: 600;
        }

        .link-button.highlight-alt3 {
            background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%);
            color: white;
            font-weight: 600;
        }

        .article {
            padding: 40px 20px 20px;
            background: linear-gradient(180deg, #FFB6D9 0%, #FFC9E3 100%);
            height: 100%;
        }

        .article.blue {
            background: linear-gradient(180deg, #a8edea 0%, #fed6e3 100%);
        }

        .article.purple {
            background: linear-gradient(180deg, #d4a5ff 0%, #e8c4ff 100%);
        }

        .article.green {
            background: linear-gradient(180deg, #a8e6cf 0%, #dcedc1 100%);
        }

        .article.solar {
            background: linear-gradient(180deg, #ffeaa7 0%, #fdcb6e 100%);
        }

        .article-header {
            display: flex;
            align-items: center;
            gap: 12px;
            margin-bottom: 20px;
            background: white;
            padding: 15px;
            border-radius: 20px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        .article-avatar {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: #FFD93D;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 16px;
            font-weight: 700;
            color: #333;
        }

        .author-info h3 {
            font-size: 16px;
            margin-bottom: 3px;
        }

        .author-link {
            font-size: 12px;
            color: #667eea;
        }

        .article-title {
            font-size: 20px;
            font-weight: 700;
            margin-bottom: 15px;
            line-height: 1.3;
        }

        .article-content-block .article-title {
            margin-top: 0;
        }

        .article-text {
            font-size: 13px;
            line-height: 1.6;
            color: #444;
            margin-bottom: 15px;
        }

        .article-content-block {
            background: white;
            padding: 20px;
            border-radius: 20px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            margin-bottom: 20px;
        }

        .article-content-block .article-text:last-child {
            margin-bottom: 0;
        }

        .related-searches {
            background: white;
            border-radius: 20px;
            padding: 15px;
            margin-bottom: 20px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        .search-title {
            font-size: 12px;
            color: #666;
            margin-bottom: 12px;
            font-weight: 600;
        }

        .search-chip {
            display: inline-block;
            background: #f8f9fa;
            padding: 8px 16px;
            border-radius: 20px;
            margin: 4px;
            font-size: 13px;
            cursor: pointer;
            border: 1px solid #e0e0e0;
            transition: all 0.2s;
        }

        .search-chip:hover {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border-color: transparent;
            transform: scale(1.05);
        }

        .search-chip.alt1:hover {
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
        }

        .search-chip.alt2:hover {
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
        }

        .search-chip.alt3:hover {
            background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%);
        }

        .serp {
            padding: 40px 20px 20px;
            background: linear-gradient(180deg, #FFB6D9 0%, #FFC9E3 100%);
            height: 100%;
        }

        .serp.blue {
            background: linear-gradient(180deg, #a8edea 0%, #fed6e3 100%);
        }

        .serp.purple {
            background: linear-gradient(180deg, #d4a5ff 0%, #e8c4ff 100%);
        }

        .serp.green {
            background: linear-gradient(180deg, #a8e6cf 0%, #dcedc1 100%);
        }

        .serp.solar {
            background: linear-gradient(180deg, #ffeaa7 0%, #fdcb6e 100%);
        }

        .search-bar {
            background: white;
            padding: 12px 16px;
            border-radius: 24px;
            font-size: 14px;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        .sponsored-badge {
            display: inline-block;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 4px 10px;
            border-radius: 12px;
            font-size: 10px;
            font-weight: 600;
            margin-bottom: 10px;
        }

        .sponsored-badge.alt1 {
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
        }

        .sponsored-badge.alt2 {
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
        }

        .sponsored-badge.alt3 {
            background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%);
        }

        .serp-result {
            padding: 20px;
            border-radius: 25px;
            margin-bottom: 16px;
            background: white;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        .result-url {
            font-size: 11px;
            color: #5f6368;
            margin-bottom: 4px;
        }

        .result-link {
            color: #1a73e8;
            font-size: 13px;
            text-decoration: none;
            display: block;
            margin-bottom: 6px;
        }

        .result-title {
            font-size: 16px;
            font-weight: 600;
            color: #1a0dab;
            margin-bottom: 6px;
        }

        .result-description {
            font-size: 12px;
            color: #4d5156;
            line-height: 1.5;
        }

        .visit-button {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 12px 24px;
            border-radius: 25px;
            border: none;
            font-size: 14px;
            font-weight: 600;
            margin-top: 12px;
            cursor: pointer;
            transition: all 0.2s;
            width: 100%;
        }

        .visit-button:hover {
            transform: scale(1.02);
            box-shadow: 0 4px 12px rgba(102, 126, 234, 0.4);
        }

        .visit-button.alt1 {
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
        }

        .visit-button.alt1:hover {
            box-shadow: 0 4px 12px rgba(240, 147, 251, 0.4);
        }

        .visit-button.alt2 {
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
        }

        .visit-button.alt2:hover {
            box-shadow: 0 4px 12px rgba(79, 172, 254, 0.4);
        }

        .visit-button.alt3 {
            background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%);
        }

        .visit-button.alt3:hover {
            box-shadow: 0 4px 12px rgba(67, 233, 123, 0.4);
        }

        .stage-label {
            position: absolute;
            top: -60px;
            left: 50%;
            transform: translateX(-50%);
            background: white;
            padding: 12px 24px;
            border-radius: 25px;
            font-size: 14px;
            font-weight: 600;
            color: #667eea;
            white-space: nowrap;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            opacity: 0;
            transition: opacity 0.6s;
        }

        .phone.visible .stage-label {
            opacity: 1;
        }

        .solar-flow-section {
            background: transparent;
            padding: 80px 20px;
            border-top: 3px solid rgba(255, 255, 255, 0.2);
        }

        .solar-flow-header {
            text-align: center;
            color: white;
            margin-bottom: 60px;
        }

        .solar-flow-header h2 {
            font-size: 42px;
            margin-bottom: 15px;
        }

        .solar-flow-header p {
            font-size: 18px;
            opacity: 0.9;
        }

        .solar-entry-controls {
            text-align: center;
            margin-bottom: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .solar-entry-label {
            background: white;
            padding: 10px 20px;
            border-radius: 20px;
            font-size: 13px;
            font-weight: 600;
            color: #667eea;
            display: inline-block;
            margin-bottom: 15px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            white-space: nowrap;
        }

        .solar-toggle-container {
            display: flex;
            justify-content: center;
            gap: 8px;
            flex-wrap: wrap;
        }

        .toggle-btn {
            background: rgba(255, 255, 255, 0.2);
            border: 2px solid rgba(255, 255, 255, 0.5);
            padding: 10px 16px;
            border-radius: 20px;
            cursor: pointer;
            transition: all 0.3s;
            font-size: 12px;
            font-weight: 600;
            color: white;
            backdrop-filter: blur(10px);
            text-align: center;
        }

        .toggle-btn.active {
            background: white;
            color: #667eea;
            border-color: white;
        }

        .toggle-btn:hover {
            background: rgba(255, 255, 255, 0.3);
            transform: translateY(-2px);
        }

        .footer {
            text-align: center;
            padding: 80px 20px;
            color: white;
        }

        .footer h2 {
            font-size: 32px;
            margin-bottom: 20px;
        }

        .footer p {
            font-size: 18px;
            opacity: 0.9;
        }

        @media (max-width: 1200px) {
            .phone-container {
                gap: 40px;
            }
            .phone-container-wrapper {
                gap: 40px;
            }
            .phone-with-controls {
                gap: 20px;
            }
            .phone {
                width: 280px;
                height: 570px;
            }
        }

        @media (max-width: 900px) {
            .phone-container {
                flex-direction: column;
                gap: 60px;
            }
            .phone-container-wrapper {
                flex-direction: column;
                gap: 60px;
                align-items: center;
            }
            .phone-with-controls {
                flex-direction: column;
                gap: 30px;
            }
            .solar-toggle-container {
                flex-direction: row !important;
            }
            .toggle-btn {
                width: auto !important;
            }
            .arrow {
                transform: rotate(90deg);
            }
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="system1-logo">SYSTEM1</div>
        <h1>MONETIZING CONTENT FOR CREATORS</h1>
    </div>

    <div class="tab-container">
        <button class="tab-button active" onclick="switchTab('linktree1')">Linktree 1</button>
        <button class="tab-button" onclick="switchTab('linktree2')">Linktree 2</button>
        <button class="tab-button" onclick="switchTab('linktree3')">Linktree 3</button>
        <button class="tab-button" onclick="switchTab('linktree4')">Linktree 4</button>
    </div>

    <div class="container">
        <!-- Linktree 1 - Position 4 -->
        <div class="flow-section active" id="linktree1">
            <div class="sticky-container">
                <div class="phone-container">
                    <div class="phone phone1">
                        <div class="stage-label">CREATOR'S LINKTREE</div>
                        <div class="phone-screen">
                            <div class="phone-notch"></div>
                            <div class="linktree">
                                <div class="profile-pic">KD</div>
                                <div class="username">Katy_Delma</div>
                                <div class="bio">💼💰 | Exploring the intersection of tech and finance | Sharing insights, guides, and tools ✨</div>
                                <div class="social-icons">
                                    <div class="social-icon">🎵</div>
                                    <div class="social-icon">▶️</div>
                                    <div class="social-icon">💻</div>
                                    <div class="social-icon">📷</div>
                                </div>
                                <div class="link-button">Instagram</div>
                                <div class="link-button">TikTok</div>
                                <div class="link-button">YouTube</div>
                                <div class="link-button highlight">How Google Pixel 10 Transforms Smartphone Tech</div>
                            </div>
                        </div>
                    </div>

                    <div class="arrow arrow1">→</div>

                    <div class="phone phone2">
                        <div class="stage-label">ARTICLE WITH RELATED SEARCHES</div>
                        <div class="phone-screen">
                            <div class="phone-notch"></div>
                            <div class="article phone-content">
                                <div class="article-header">
                                    <div class="article-avatar">KD</div>
                                    <div class="author-info">
                                        <h3>Katy Delma</h3>
                                        <div class="author-link">Linktree ✨</div>
                                    </div>
                                </div>
                                <div class="article-content-block">
                                    <h1 class="article-title">How Google Pixel 10 Transforms Smartphone Tech</h1>
                                    <div class="article-text">
                                        The Google Pixel 10 smartphone represents a leap forward in technology with its advanced AI capabilities and innovative features. Powered by the Google Tensor G5 chip, it enhances on-device AI tasks, revolutionizes photography, and provides seamless language translation.
                                    </div>
                                    <div class="article-text">
                                        This chip doesn't just enhance performance; it opens up new possibilities for on-device AI applications by providing power for features like the Gemini Nano model, enabling complex and generative AI tasks.
                                    </div>
                                </div>

                                <div class="related-searches">
                                    <div class="search-title">Related Searches</div>
                                    <div class="search-chip">Google Pixel Pro</div>
                                    <div class="search-chip">Google Tensor G5</div>
                                    <div class="search-chip">Gemini Nano AI</div>
                                </div>

                                <div class="article-content-block">
                                    <div class="article-text">
                                        One of the standout features is the Magic Cue, which seamlessly integrates with popular apps such as Gmail and Calendar to offer proactive suggestions and display relevant information at a glance. This feature not only enhances user convenience and efficiency but also upholds privacy.
                                    </div>
                                    <div class="article-text">
                                        Photography has been taken up a notch with a 5x telephoto lens and Super Res Zoom, boasting up to 20x zoom for capturing distant details. The Google Pixel 10 does not disappoint in the camera department, improving on past success with higher-quality photos achievable with faster autofocusing and advanced AI features.
                                    </div>
                                </div>

                                <div class="related-searches">
                                    <div class="search-title">More Related Searches</div>
                                    <div class="search-chip">Pixel 10 Camera</div>
                                    <div class="search-chip">5x Telephoto Lens</div>
                                    <div class="search-chip">Magic Cue Features</div>
                                </div>

                                <div class="article-content-block">
                                    <div class="article-text">
                                        The Pixel 10's unique AI-driven experiences do not stop at picture-taking. With the Pixel 10, AI takes on an even more comprehensive role, supporting real-time call translations through Voice Translate which allows conversations to flow naturally across different languages.
                                    </div>
                                    <div class="article-text">
                                        The visual and tactile appeal of the Pixel 10 cannot be understated. The series comes with a modern design incorporating a satin-finish metal frame and polished glass back, available in four distinct color options: Obsidian, Frost, Indigo, and Lemongrass.
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="arrow arrow2">→</div>

                    <div class="phone phone3">
                        <div class="stage-label">BRANDED SEARCH RESULTS PAGE</div>
                        <div class="phone-screen">
                            <div class="phone-notch"></div>
                            <div class="serp phone-content">
                                <div class="search-bar">🔍 Google Pixel Pro</div>
                                
                                <div class="serp-result">
                                    <div class="sponsored-badge">Sponsored</div>
                                    <div class="result-url">google.com</div>
                                    <div class="result-title">Get Google One Premium Storage</div>
                                    <div class="result-description">Shop Online - 2 TB of storage w/ VPN & Premium features on $9.99/mo plan w/AutoPay.</div>
                                    <button class="visit-button">Visit Website</button>
                                </div>

                                <div class="serp-result">
                                    <div class="sponsored-badge">Sponsored</div>
                                    <div class="result-url">t-mobile.com</div>
                                    <div class="result-title">Get Google Pixel 10 Pro On Us</div>
                                    <div class="result-description">Shop Online or In-Store - On us via 24 mo crdt w/ new line on $100+/mo plan w/AutoPay.</div>
                                    <button class="visit-button">Visit Website</button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Linktree 2 - Position 1 -->
        <div class="flow-section" id="linktree2">
            <div class="sticky-container">
                <div class="phone-container">
                    <div class="phone phone1">
                        <div class="stage-label">CREATOR'S LINKTREE</div>
                        <div class="phone-screen">
                            <div class="phone-notch"></div>
                            <div class="linktree blue">
                                <div class="profile-pic">KD</div>
                                <div class="username">Katy_Delma</div>
                                <div class="bio">💼💰 | Exploring the intersection of tech and finance | Sharing insights, guides, and tools ✨</div>
                                <div class="social-icons">
                                    <div class="social-icon">🎵</div>
                                    <div class="social-icon">▶️</div>
                                    <div class="social-icon">💻</div>
                                    <div class="social-icon">📷</div>
                                </div>
                                <div class="link-button highlight-alt1">How Google Pixel 10 Transforms Smartphone Tech</div>
                                <div class="link-button">YouTube</div>
                                <div class="link-button">Instagram</div>
                                <div class="link-button">TikTok</div>
                            </div>
                        </div>
                    </div>

                    <div class="arrow arrow1">→</div>

                    <div class="phone phone2">
                        <div class="stage-label">ARTICLE WITH RELATED SEARCHES</div>
                        <div class="phone-screen">
                            <div class="phone-notch"></div>
                            <div class="article blue phone-content">
                                <div class="article-header">
                                    <div class="article-avatar">KD</div>
                                    <div class="author-info">
                                        <h3>Katy Delma</h3>
                                        <div class="author-link">Linktree ✨</div>
                                    </div>
                                </div>
                                <div class="article-content-block">
                                    <h1 class="article-title">How Google Pixel 10 Transforms Smartphone Tech</h1>
                                    <div class="article-text">Revolutionary AI-powered photography meets stunning design. The Pixel 10 introduces breakthrough features that redefine mobile computing for 2025 with the powerful Tensor G5 chip.</div>
                                    <div class="article-text">This chip doesn't just enhance performance; it opens up new possibilities for on-device AI applications by providing power for features like the Gemini Nano model, enabling complex and generative AI tasks without cloud dependency.</div>
                                </div>

                                <div class="related-searches">
                                    <div class="search-title">Related Searches</div>
                                    <div class="search-chip alt1">Best Smartphone 2025</div>
                                    <div class="search-chip alt1">Pixel 10 Camera</div>
                                    <div class="search-chip alt1">On-Device AI</div>
                                </div>

                                <div class="article-content-block">
                                    <div class="article-text">Adding to these innovative features is Pixel Journal, providing a private space for user reflection and well-being with personalized writing prompts and pattern insights, enhanced with AI.</div>
                                    <div class="article-text">The AI enhancements also extend to the sound experience. The Pixel 10 Recorder can now transform vocal recordings into music tracks, allowing for a thriving environment for creative expression.</div>
                                </div>

                                <div class="related-searches">
                                    <div class="search-title">More Related Searches</div>
                                    <div class="search-chip alt1">Pixel Journal App</div>
                                    <div class="search-chip alt1">AI Music Creation</div>
                                    <div class="search-chip alt1">Gboard AI Tools</div>
                                </div>

                                <div class="article-content-block">
                                    <div class="article-text">Writing Tools in Gboard have been improved with style-specific rewrites and suggestions boosted by voice commands.</div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="arrow arrow2">→</div>

                    <div class="phone phone3">
                        <div class="stage-label">BRANDED SEARCH RESULTS PAGE</div>
                        <div class="phone-screen">
                            <div class="phone-notch"></div>
                            <div class="serp blue phone-content">
                                <div class="search-bar">🔍 Best Smartphone 2025</div>
                                
                                <div class="serp-result">
                                    <div class="sponsored-badge alt1">Sponsored</div>
                                    <div class="result-url">bestbuy.com</div>
                                    <div class="result-title">Google Pixel 10 - Save $200</div>
                                    <div class="result-description">Limited time offer on the latest Pixel with AI features. Free shipping + trade-in credit.</div>
                                    <button class="visit-button alt1">Visit Website</button>
                                </div>

                                <div class="serp-result">
                                    <div class="sponsored-badge alt1">Sponsored</div>
                                    <div class="result-url">verizon.com</div>
                                    <div class="result-title">Switch to Verizon - Get Pixel 10 Free</div>
                                    <div class="result-description">When you switch and trade in. Plus unlimited data for your whole family.</div>
                                    <button class="visit-button alt1">Visit Website</button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Linktree 3 - Position 2 -->
        <div class="flow-section" id="linktree3">
            <div class="sticky-container">
                <div class="phone-container">
                    <div class="phone phone1">
                        <div class="stage-label">CREATOR'S LINKTREE</div>
                        <div class="phone-screen">
                            <div class="phone-notch"></div>
                            <div class="linktree purple">
                                <div class="profile-pic">KD</div>
                                <div class="username">Katy_Delma</div>
                                <div class="bio">💼💰 | Exploring the intersection of tech and finance | Sharing insights, guides, and tools ✨</div>
                                <div class="social-icons">
                                    <div class="social-icon">🎵</div>
                                    <div class="social-icon">▶️</div>
                                    <div class="social-icon">💻</div>
                                    <div class="social-icon">📷</div>
                                </div>
                                <div class="link-button">TikTok</div>
                                <div class="link-button highlight-alt2">How Google Pixel 10 Transforms Smartphone Tech</div>
                                <div class="link-button">Instagram</div>
                                <div class="link-button">YouTube</div>
                            </div>
                        </div>
                    </div>

                    <div class="arrow arrow1">→</div>

                    <div class="phone phone2">
                        <div class="stage-label">ARTICLE WITH RELATED SEARCHES</div>
                        <div class="phone-screen">
                            <div class="phone-notch"></div>
                            <div class="article purple phone-content">
                                <div class="article-header">
                                    <div class="article-avatar">KD</div>
                                    <div class="author-info">
                                        <h3>Katy Delma</h3>
                                        <div class="author-link">Linktree ✨</div>
                                    </div>
                                </div>
                                <div class="article-content-block">
                                    <h1 class="article-title">How Google Pixel 10 Transforms Smartphone Tech</h1>
                                    <div class="article-text">Experience the future with Tensor G5 chip. Advanced machine learning brings unprecedented speed and intelligence to every interaction, from photography to real-time translation.</div>
                                    <div class="article-text">This chip doesn't just enhance performance; it opens up new possibilities for on-device AI applications by providing power for features like the Gemini Nano model.</div>
                                </div>

                                <div class="related-searches">
                                    <div class="search-title">Related Searches</div>
                                    <div class="search-chip alt2">Pixel 10 vs iPhone</div>
                                    <div class="search-chip alt2">Tensor G5 Chip</div>
                                    <div class="search-chip alt2">Real-Time Translation</div>
                                </div>

                                <div class="article-content-block">
                                    <div class="article-text">The Pixel 10's unique AI-driven experiences support real-time call translations through Voice Translate which allows conversations to flow naturally across different languages, including English, Spanish, and French.</div>
                                    <div class="article-text">In a move supporting long-term value, Google ensures that every Pixel 10 smartphone experience will be continually enhanced through software updates for seven years delivering sustained performance.</div>
                                </div>

                                <div class="related-searches">
                                    <div class="search-title">More Related Searches</div>
                                    <div class="search-chip alt2">Voice Translate</div>
                                    <div class="search-chip alt2">7 Years Updates</div>
                                    <div class="search-chip alt2">Android 15 Features</div>
                                </div>

                                <div class="article-content-block">
                                    <div class="article-text">This 'never-aging' promise is a significant leap toward longevity and sustainability in smartphone usage.</div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="arrow arrow2">→</div>

                    <div class="phone phone3">
                        <div class="stage-label">BRANDED SEARCH RESULTS PAGE</div>
                        <div class="phone-screen">
                            <div class="phone-notch"></div>
                            <div class="serp purple phone-content">
                                <div class="search-bar">🔍 Tensor G5 Chip</div>
                                
                                <div class="serp-result">
                                    <div class="sponsored-badge alt2">Sponsored</div>
                                    <div class="result-url">google.com</div>
                                    <div class="result-title">Tensor G5 - The Brain Behind Pixel 10</div>
                                    <div class="result-description">Discover how Google's custom chip revolutionizes mobile AI. Learn more about Pixel 10.</div>
                                    <button class="visit-button alt2">Visit Website</button>
                                </div>

                                <div class="serp-result">
                                    <div class="sponsored-badge alt2">Sponsored</div>
                                    <div class="result-url">amazon.com</div>
                                    <div class="result-title">Google Pixel 10 Unlocked</div>
                                    <div class="result-description">Prime members get exclusive pricing. Free returns and fast shipping available.</div>
                                    <button class="visit-button alt2">Visit Website</button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Linktree 4 - Position 3 -->
        <div class="flow-section" id="linktree4">
            <div class="sticky-container">
                <div class="phone-container">
                    <div class="phone phone1">
                        <div class="stage-label">CREATOR'S LINKTREE</div>
                        <div class="phone-screen">
                            <div class="phone-notch"></div>
                            <div class="linktree green">
                                <div class="profile-pic">KD</div>
                                <div class="username">Katy_Delma</div>
                                <div class="bio">💼💰 | Exploring the intersection of tech and finance | Sharing insights, guides, and tools ✨</div>
                                <div class="social-icons">
                                    <div class="social-icon">🎵</div>
                                    <div class="social-icon">▶️</div>
                                    <div class="social-icon">💻</div>
                                    <div class="social-icon">📷</div>
                                </div>
                                <div class="link-button">YouTube</div>
                                <div class="link-button">TikTok</div>
                                <div class="link-button highlight-alt3">How Google Pixel 10 Transforms Smartphone Tech</div>
                                <div class="link-button">Instagram</div>
                            </div>
                        </div>
                    </div>

                    <div class="arrow arrow1">→</div>

                    <div class="phone phone2">
                        <div class="stage-label">ARTICLE WITH RELATED SEARCHES</div>
                        <div class="phone-screen">
                            <div class="phone-notch"></div>
                            <div class="article green phone-content">
                                <div class="article-header">
                                    <div class="article-avatar">KD</div>
                                    <div class="author-info">
                                        <h3>Katy Delma</h3>
                                        <div class="author-link">Linktree ✨</div>
                                    </div>
                                </div>
                                <div class="article-content-block">
                                    <h1 class="article-title">How Google Pixel 10 Transforms Smartphone Tech</h1>
                                    <div class="article-text">Sustainability meets innovation. The Pixel 10 features recycled materials and energy-efficient design while delivering flagship performance powered by the revolutionary Tensor G5 chip.</div>
                                    <div class="article-text">This chip doesn't just enhance performance; it opens up new possibilities for on-device AI applications while maintaining exceptional battery efficiency.</div>
                                </div>

                                <div class="related-searches">
                                    <div class="search-title">Related Searches</div>
                                    <div class="search-chip alt3">Eco-Friendly Phone</div>
                                    <div class="search-chip alt3">Pixel 10 Battery Life</div>
                                    <div class="search-chip alt3">Sustainable Tech</div>
                                </div>

                                <div class="article-content-block">
                                    <div class="article-text">The visual and tactile appeal of the Pixel 10 cannot be understated. The series comes with a modern design incorporating a satin-finish metal frame and polished glass back, available in four distinct color options.</div>
                                    <div class="article-text">Furthermore, switching to Google Pixel has been streamlined, as it offers compatible experiences with popular devices, ensuring that users do not feel isolated from other ecosystems.</div>
                                </div>

                                <div class="related-searches">
                                    <div class="search-title">More Related Searches</div>
                                    <div class="search-chip alt3">Pixel Watch 3</div>
                                    <div class="search-chip alt3">Pixel Buds Pro 2</div>
                                    <div class="search-chip alt3">3000 Nits Display</div>
                                </div>

                                <div class="article-content-block">
                                    <div class="article-text">Additional seamless integrations are evident with accessories like the Pixel Watch and Pixel Buds with dynamic spatial audio.</div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="arrow arrow2">→</div>

                    <div class="phone phone3">
                        <div class="stage-label">BRANDED SEARCH RESULTS PAGE</div>
                        <div class="phone-screen">
                            <div class="phone-notch"></div>
                            <div class="serp green phone-content">
                                <div class="search-bar">🔍 Eco-Friendly Phone</div>
                                
                                <div class="serp-result">
                                    <div class="sponsored-badge alt3">Sponsored</div>
                                    <div class="result-url">google.com</div>
                                    <div class="result-title">Pixel 10 - Built with 70% Recycled Materials</div>
                                    <div class="result-description">Our most sustainable phone yet. Carbon neutral shipping and energy efficient design.</div>
                                    <button class="visit-button alt3">Visit Website</button>
                                </div>

                                <div class="serp-result">
                                    <div class="sponsored-badge alt3">Sponsored</div>
                                    <div class="result-url">att.com</div>
                                    <div class="result-title">AT&T - Trade In & Go Green</div>
                                    <div class="result-description">Recycle your old device and get the new Pixel 10. We'll plant a tree with every purchase.</div>
                                    <button class="visit-button alt3">Visit Website</button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
  <div class="footer">
        <h2>Multiple Paths to Monetization</h2>
        <p>System1 provides flexible content monetization solutions for every creator</p>
    </div>

    <script>
        function animatePhones(tabId) {
            const section = document.getElementById(tabId);
            if (!section) return;
            
            const phone1 = section.querySelector('.phone1');
            const phone2 = section.querySelector('.phone2');
            const phone3 = section.querySelector('.phone3');
            const arrow1 = section.querySelector('.arrow1');
            const arrow2 = section.querySelector('.arrow2');
            
            // Reset all animations
            [phone1, phone2, phone3, arrow1, arrow2].forEach(el => {
                if (el) el.classList.remove('visible');
            });
            
            // Animate in sequence
            setTimeout(() => phone1?.classList.add('visible'), 200);
            setTimeout(() => arrow1?.classList.add('visible'), 1000);
            setTimeout(() => phone2?.classList.add('visible'), 1000);
            setTimeout(() => arrow2?.classList.add('visible'), 1800);
            setTimeout(() => phone3?.classList.add('visible'), 1800);
        }

        function animateSolarPhones() {
            const solarPhone1 = document.querySelector('.phone1-solar');
            const solarPhone2 = document.querySelector('.phone2-solar');
            const solarPhone3 = document.querySelector('.phone3-solar');
            const solarArrow1 = document.querySelector('.solar-flow-section .arrow1');
            const solarArrow2 = document.querySelector('.solar-flow-section .arrow2');
            
            // Reset all animations
            [solarPhone1, solarPhone2, solarPhone3, solarArrow1, solarArrow2].forEach(el => {
                if (el) el.classList.remove('visible');
            });
            
            // Animate in sequence
            setTimeout(() => solarPhone1?.classList.add('visible'), 200);
            setTimeout(() => solarArrow1?.classList.add('visible'), 1000);
            setTimeout(() => solarPhone2?.classList.add('visible'), 1000);
            setTimeout(() => solarArrow2?.classList.add('visible'), 1800);
            setTimeout(() => solarPhone3?.classList.add('visible'), 1800);
        }

        function switchTab(tabId) {
            document.querySelectorAll('.flow-section').forEach(s => s.classList.remove('active'));
            document.querySelectorAll('.tab-button').forEach(b => b.classList.remove('active'));
            document.getElementById(tabId).classList.add('active');
            event.target.classList.add('active');
            window.scrollTo(0, 0);
            
            // Start animation for the new tab
            setTimeout(() => animatePhones(tabId), 100);
        }

        // Trigger animation on page load for active tab
        document.addEventListener('DOMContentLoaded', () => {
            animatePhones('linktree1');
        });

        // Trigger solar animation when scrolled into view
        let solarAnimated = false;
        window.addEventListener('scroll', () => {
            if (solarAnimated) return;
            
            const solarSection = document.querySelector('.solar-flow-section');
            if (solarSection) {
                const rect = solarSection.getBoundingClientRect();
                if (rect.top < window.innerHeight * 0.8) {
                    solarAnimated = true;
                    animateSolarPhones();
                }
            }
        });

        function showSolarSocial() {
            document.getElementById('solar-social').style.display = 'block';
            document.getElementById('solar-thankyou').style.display = 'none';
            document.getElementById('solar-disqualify').style.display = 'none';
            document.getElementById('solar-linktree').style.display = 'none';
            const buttons = document.querySelectorAll('.solar-toggle-container .toggle-btn');
            buttons.forEach(btn => btn.classList.remove('active'));
            buttons[0].classList.add('active');
        }

        function showSolarThankYou() {
            document.getElementById('solar-social').style.display = 'none';
            document.getElementById('solar-thankyou').style.display = 'block';
            document.getElementById('solar-disqualify').style.display = 'none';
            document.getElementById('solar-linktree').style.display = 'none';
            const buttons = document.querySelectorAll('.solar-toggle-container .toggle-btn');
            buttons.forEach(btn => btn.classList.remove('active'));
            buttons[1].classList.add('active');
        }

        function showSolarDisqualify() {
            document.getElementById('solar-social').style.display = 'none';
            document.getElementById('solar-thankyou').style.display = 'none';
            document.getElementById('solar-disqualify').style.display = 'flex';
            document.getElementById('solar-linktree').style.display = 'none';
            const buttons = document.querySelectorAll('.solar-toggle-container .toggle-btn');
            buttons.forEach(btn => btn.classList.remove('active'));
            buttons[2].classList.add('active');
        }

        function showSolarLinktree() {
            document.getElementById('solar-social').style.display = 'none';
            document.getElementById('solar-thankyou').style.display = 'none';
            document.getElementById('solar-disqualify').style.display = 'none';
            document.getElementById('solar-linktree').style.display = 'block';
            const buttons = document.querySelectorAll('.solar-toggle-container .toggle-btn');
            buttons.forEach(btn => btn.classList.remove('active'));
            buttons[3].classList.add('active');
        }
    </script>
</body>
</html>
