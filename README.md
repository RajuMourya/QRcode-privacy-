<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Privacy Policy - Ai saathi hub</title>
    <meta name="description" content="Official Privacy Policy for Ai saathi hub Android Application and Bundle on Google Play Store.">
    <style>
        :root {
            --primary: #4F46E5;
            --primary-dark: #3730A3;
            --primary-light: #EEF2FF;
            --secondary: #059669;
            --accent: #EA580C;
            --bg: #F8FAFC;
            --surface: #FFFFFF;
            --text-main: #0F172A;
            --text-muted: #475569;
            --border: #E2E8F0;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
        }

        body {
            background-color: var(--bg);
            color: var(--text-main);
            line-height: 1.7;
            padding: 20px 15px;
        }

        .policy-container {
            max-width: 900px;
            margin: 20px auto;
            background: var(--surface);
            padding: 45px 35px;
            border-radius: 20px;
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.05), 0 8px 10px -6px rgba(0, 0, 0, 0.01);
            border: 1px solid var(--border);
        }

        .header {
            text-align: center;
            border-bottom: 2px solid var(--border);
            padding-bottom: 30px;
            margin-bottom: 30px;
        }

        .header h1 {
            color: var(--primary);
            font-size: 30px;
            font-weight: 800;
            margin-bottom: 12px;
            letter-spacing: -0.5px;
        }

        .header p {
            color: var(--text-muted);
            font-size: 15px;
        }

        .badge-bar {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: center;
            margin-top: 15px;
        }

        .badge {
            background: var(--primary-light);
            color: var(--primary);
            font-size: 12px;
            font-weight: 700;
            padding: 5px 14px;
            border-radius: 50px;
            display: inline-flex;
            align-items: center;
            gap: 5px;
            border: 1px solid #C7D2FE;
        }

        .badge.green {
            background: #ECFDF5;
            color: var(--secondary);
            border-color: #A7F3D0;
        }

        /* App Details Metadata Table */
        .meta-table-box {
            background: #F8FAFC;
            border: 1px solid var(--border);
            border-radius: 14px;
            overflow: hidden;
            margin: 25px 0 35px 0;
        }

        .meta-table-title {
            background: #EEF2FF;
            color: var(--primary-dark);
            padding: 12px 20px;
            font-size: 14px;
            font-weight: 700;
            border-bottom: 1px solid var(--border);
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .meta-table {
            width: 100%;
            border-collapse: collapse;
        }

        .meta-table tr {
            border-bottom: 1px solid #EDF2F7;
        }

        .meta-table tr:last-child {
            border-bottom: none;
        }

        .meta-table td {
            padding: 12px 20px;
            font-size: 14px;
        }

        .meta-table td.label {
            font-weight: 600;
            color: var(--text-muted);
            width: 38%;
            background: #FBFDFF;
        }

        .meta-table td.val {
            color: var(--text-main);
            font-weight: 500;
            font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
            word-break: break-all;
        }

        h2 {
            color: var(--primary-dark);
            font-size: 20px;
            font-weight: 700;
            margin-top: 32px;
            margin-bottom: 14px;
            display: flex;
            align-items: center;
            gap: 10px;
            border-left: 4px solid var(--primary);
            padding-left: 12px;
        }

        p, ul, ol {
            color: var(--text-muted);
            font-size: 15px;
            line-height: 1.75;
            margin-bottom: 16px;
        }

        ul, ol {
            padding-left: 24px;
        }

        li {
            margin-bottom: 10px;
        }

        .highlight-card {
            background: #F0FDF4;
            border-left: 4px solid var(--secondary);
            padding: 18px 22px;
            border-radius: 0 12px 12px 0;
            margin: 20px 0;
        }

        .highlight-card p {
            color: #166534;
            margin: 0;
            font-size: 14.5px;
            font-weight: 500;
        }

        .info-card {
            background: #EFF6FF;
            border-left: 4px solid var(--primary);
            padding: 18px 22px;
            border-radius: 0 12px 12px 0;
            margin: 20px 0;
        }

        .info-card p {
            color: #1E40AF;
            margin: 0;
            font-size: 14.5px;
        }

        .contact-box {
            background: #FAFAFA;
            border: 2px dashed #CBD5E1;
            padding: 25px;
            border-radius: 16px;
            margin-top: 35px;
        }

        .contact-box h3 {
            color: var(--primary-dark);
            font-size: 18px;
            margin-bottom: 12px;
        }

        .contact-box p {
            margin-bottom: 8px;
        }

        .contact-box a {
            color: var(--primary);
            text-decoration: none;
            font-weight: 700;
        }

        .contact-box a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid var(--border);
            color: #94A3B8;
            font-size: 13px;
        }

        @media (max-width: 600px) {
            .policy-container {
                padding: 25px 18px;
            }
            .header h1 {
                font-size: 24px;
            }
            .meta-table td {
                display: block;
                width: 100% !important;
                padding: 8px 15px;
            }
            .meta-table td.label {
                background: #F1F5F9;
                font-size: 12px;
            }
        }
    </style>
</head>
<body>

<div class="policy-container">
    
    <!-- Header -->
    <div class="header">
        <h1>Privacy Policy / गोपनीयता नीति</h1>
        <p>Official Google Play Store Developer & App Privacy Document</p>
        <div class="badge-bar">
            <span class="badge green">✓ Google Play Compliant</span>
            <span class="badge">✓ Google AdMob / AdSense Certified</span>
            <span class="badge">✓ COPPA & GDPR Ready</span>
        </div>
    </div>

    <!-- App & Package Details Table for Google Play Console -->
    <div class="meta-table-box">
        <div class="meta-table-title">📱 App Specification & Identification Details</div>
        <table class="meta-table">
            <tr>
                <td class="label">App Name (ऐप का नाम)</td>
                <td class="val"><strong>Ai saathi hub</strong></td>
            </tr>
            <tr>
                <td class="label">Package Name / Application ID</td>
                <td class="val"><strong>com.aistudio.aisaathihub.uqvzk</strong></td>
            </tr>
            <tr>
                <td class="label">App Bundle / Package Type</td>
                <td class="val">Android App Bundle (.aab) / APK</td>
            </tr>
            <tr>
                <td class="label">Official Website / Blog</td>
                <td class="val"><a href="https://aisaathihub.blogspot.com/" target="_blank" style="color: #EA580C; text-decoration: none; font-weight: bold;">https://aisaathihub.blogspot.com/</a></td>
            </tr>
            <tr>
                <td class="label">Developer / Publisher Email</td>
                <td class="val"><a href="mailto:rajumourya2019@gmail.com" style="color: #4F46E5; text-decoration: none;">rajumourya2019@gmail.com</a></td>
            </tr>
            <tr>
                <td class="label">Google AdMob / AdSense Pub ID</td>
                <td class="val">pub-6690245244769117</td>
            </tr>
            <tr>
                <td class="label">Google Ads Account</td>
                <td class="val">102-187-8996</td>
            </tr>
            <tr>
                <td class="label">Publication ID</td>
                <td class="val">CAow9NbHDA</td>
            </tr>
            <tr>
                <td class="label">Effective Date (लागू होने की तिथि)</td>
                <td class="val">September 01, 2026</td>
            </tr>
        </table>
    </div>

    <!-- Overview -->
    <div class="info-card">
        <p><strong>General Overview:</strong> <em>Ai saathi hub</em> (Application ID: <code>com.aistudio.aisaathihub.uqvzk</code>) is built as a free, multi-utility productivity and digital toolbox application (providing 100+ daily utility tools including Image Compressor, PDF Tools, Resume Builder, Financial & Health Calculators, Text & Code Converters, and more). This Privacy Policy explains our practices concerning the collection, use, and disclosure of user information.</p>
    </div>

    <!-- 1. Data Collection and Local Processing -->
    <h2>1. Data Collection & Processing / डेटा गोपनीयता</h2>
    <div class="highlight-card">
        <p>🔒 <strong>Zero Server Upload Policy:</strong> All your files, photos, images, and user-entered inputs are processed locally (on-device) inside your smartphone. We do not store or transmit your sensitive files to our personal servers.</p>
    </div>
    <p>Specifically, our privacy framework ensures:</p>
    <ul>
        <li><strong>No Mandatory Account Registration:</strong> Users are not required to create an account, log in, or submit personal details (e.g. phone numbers, passwords) to access the core offline utilities.</li>
        <li><strong>Image & Document Tools (On-Device Sandbox):</strong> When utilizing the Image Compressor, Image Resizer, or PDF/Resume tools, files are handled strictly within the Android app's local sandbox memory.</li>
        <li><strong>Device Technical Information:</strong> Standard, non-personal diagnostic metrics (such as device model, OS version, language preference, and crash reports) may be processed automatically by the Android OS to optimize stability.</li>
    </ul>

    <!-- 2. Advertising Partners -->
    <h2>2. Advertising & Monetization Partners / विज्ञापन सेवाएं</h2>
    <p>To provide 100+ tools completely free to users worldwide, the application integrates verified, industry-leading third-party ad networks:</p>
    <ul>
        <li>
            <strong>Google AdMob & Google AdSense:</strong>
            <br>Publisher ID: <code>pub-6690245244769117</code>
            <br>Google AdMob complies with Google Play Policy guidelines. Google may use advertising identifiers (AAID) and cookies to serve contextual or personalized advertisements according to its privacy policy.
            <br>Learn more: <a href="https://policies.google.com/privacy" target="_blank" style="color:var(--primary); font-weight:600;">Google Privacy & Terms</a>
        </li>
        <li>
            <strong>Adsterra Network:</strong>
            <br>Partner Publisher ID: <code>id3448655</code>
            <br>Used for supplementary display banners and monetization in compliance with international privacy protocols.
        </li>
    </ul>

    <!-- 3. App Permissions -->
    <h2>3. Android App Permissions / ऐप अनुमतियां</h2>
    <p>The application only requests permissions strictly essential for user-requested operations:</p>
    <ul>
        <li><code>android.permission.INTERNET</code>: Required to stream tool updates, access the official blog (<em>aisaathihub.blogspot.com</em>), and load third-party advertisements.</li>
        <li><code>android.permission.ACCESS_NETWORK_STATE</code>: Required to verify active internet connectivity before fetching online resources.</li>
        <li><strong>Android Photo Picker (Zero-Permission Media Access):</strong> For image tools, the app utilizes Android's native Photo Picker (<code>PickVisualMedia</code>), ensuring the app never has broad access to your photo gallery—only the specific file you pick is processed.</li>
    </ul>

    <!-- 4. Google Play Data Safety Declaration -->
    <h2>4. Google Play Data Safety Compliance / डेटा सुरक्षा</h2>
    <ul>
        <li><strong>Data in Transit:</strong> All external network communication (such as blog loading or ad requests) is encrypted over standard HTTPS/SSL protocols.</li>
        <li><strong>Data Sharing:</strong> We do not sell, rent, or trade your personal data to any external marketing broker.</li>
        <li><strong>Data Retention & Deletion:</strong> Since no user accounts or persistent database files are stored on cloud servers, uninstallation of the application instantly wipes all local tool caches from your device.</li>
    </ul>

    <!-- 5. Children's Privacy (COPPA Compliance) -->
    <h2>5. Children's Privacy (COPPA / GDPR-K Compliance)</h2>
    <p>Our app does not address or target anyone under the age of 13. We do not knowingly collect personally identifiable information from children under 13. If you are a parent or guardian and are aware that your child has provided us with personal data, please contact us so that we can take necessary corrective actions.</p>

    <!-- 6. Policy Updates -->
    <h2>6. Changes to This Privacy Policy</h2>
    <p>We may update our Privacy Policy from time to time to adapt to new features or regulatory updates. We advise you to review this page periodically for any changes. Any changes are effective immediately upon posting to this URL.</p>

    <!-- 7. Contact Us -->
    <div class="contact-box">
        <h3>7. Contact Us / संपर्क करें</h3>
        <p>If you have any questions, feedback, or concerns regarding this Privacy Policy or your experience with <strong>Ai saathi hub</strong>, please contact the developer directly:</p>
        <p>👤 <strong>Developer:</strong> Raju Mourya (Ai saathi hub Team)</p>
        <p>📧 <strong>Email:</strong> <a href="mailto:rajumourya2019@gmail.com">rajumourya2019@gmail.com</a></p>
        <p>🌐 <strong>Official Blog & Website:</strong> <a href="https://aisaathihub.blogspot.com/" target="_blank">https://aisaathihub.blogspot.com/</a></p>
        <p>📦 <strong>App Bundle ID:</strong> <code>com.aistudio.aisaathihub.uqvzk</code></p>
    </div>

    <!-- Footer -->
    <footer>
        <p>© 2026 Ai saathi hub (<code>com.aistudio.aisaathihub.uqvzk</code>). All rights reserved.</p>
        <p style="margin-top: 5px; font-size: 12px;">This document satisfies all requirements for Google Play Store Listing & Data Safety Form.</p>
    </footer>

</div>

</body>
</html>
