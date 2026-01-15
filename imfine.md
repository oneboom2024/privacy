<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Privacy Policy - ImFine</title>
    <style>
        body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif; line-height: 1.6; color: #333; max-width: 800px; margin: 0 auto; padding: 20px; background-color: #f9f9f9; }
        .container { background-color: #ffffff; padding: 40px; border-radius: 12px; box-shadow: 0 2px 10px rgba(0,0,0,0.05); }
        h1 { text-align: center; color: #1a1a1a; margin-bottom: 10px; }
        .date { text-align: center; color: #666; font-size: 0.9em; margin-bottom: 40px; border-bottom: 1px solid #eee; padding-bottom: 20px; }
        h2 { color: #2c3e50; margin-top: 30px; font-size: 1.4em; border-left: 4px solid #007AFF; padding-left: 12px; }
        ul { padding-left: 20px; }
        li { margin-bottom: 10px; }
        strong { color: #2c3e50; }
        a { color: #007AFF; text-decoration: none; }
        a:hover { text-decoration: underline; }
        @media (max-width: 600px) { .container { padding: 20px; } h1 { font-size: 1.8em; } }
    </style>
</head>
<body>
<div class="container">
    <h1>Privacy Policy</h1>
    <p class="date">Last Updated: January 15, 2026</p>

    ```

### 第二步：拼接正文
**紧接着上面代码的末尾**，粘贴下面这部分内容：

```html
    <h2>1. Information We Collect</h2>
    <p>We collect the following information to provide our safety check-in service:</p>
    <ul>
        <li><strong>Account Information:</strong> Email address (collected via Apple Sign In for authentication purposes).</li>
        <li><strong>Check-in Data:</strong> Daily check-in records, timestamps, and mood status selections.</li>
        <li><strong>Emergency Contact Information:</strong> The email address of the person you designate as your emergency contact.</li>
        <li><strong>Personal Messages:</strong> Your encrypted preset message ("Will Message") to be sent only in case of an emergency.</li>
        <li><strong>App Settings:</strong> Check-in interval preferences (e.g., 12h, 24h), notification settings, and local time zone.</li>
        <li><strong>Usage Data:</strong> Anonymous analytical data collected through Firebase Analytics and Facebook Analytics to help us improve app stability and functionality.</li>
        <li><strong>Device Information:</strong> Device identifiers (IDFV), device model, and app version information for analytics and debugging purposes.</li>
    </ul>

    <h2>2. How We Use Your Information</h2>
    <p>Your information is used exclusively for the following purposes:</p>
    <ul>
        <li><strong>Safety Services:</strong> To verify your safety status and track your check-in intervals.</li>
        <li><strong>Emergency Notifications:</strong> To automatically send an alert email to your designated emergency contact ONLY if you fail to check in within your specified timeframe.</li>
        <li><strong>Service Improvement:</strong> To analyze aggregate usage trends via Firebase and Facebook Analytics to enhance user experience.</li>
        <li><strong>Subscription Management:</strong> To process and manage your Pro subscription status via Apple's StoreKit.</li>
        <li><strong>Local Storage:</strong> To store your check-in history and mood diary locally on your device for offline access and privacy.</li>
    </ul>

    <h2>3. Data Storage and Security</h2>
    <ul>
        <li><strong>Cloud Storage:</strong> Your critical account data (User ID, Emergency Contact, Will Message) is stored securely in our cloud database hosted by <strong>Supabase</strong>.</li>
        <li><strong>Data Encryption:</strong> We employ industry-standard encryption protocols (SSL/TLS) for data in transit and encryption at rest to protect your sensitive personal information.</li>
        <li><strong>Local Storage:</strong> Your historical check-in logs and detailed mood data are primarily stored locally on your device to minimize data transmission.</li>
        <li><strong>Data Retention:</strong> We retain your account data only as long as your account is active. Upon account deletion, your personal data is removed from our active databases.</li>
    </ul>

    <h2>4. Third-Party Services</h2>
    <p>We utilize the following trusted third-party service providers:</p>
    <ul>
        <li><strong>Supabase:</strong> Secure cloud database and authentication services.</li>
        <li><strong>Firebase Analytics (Google):</strong> To monitor app stability and crash reporting.</li>
        <li><strong>Facebook SDK (Meta):</strong> For aggregate app performance tracking and analytics.</li>
        <li><strong>Apple StoreKit:</strong> To handle all payment processing and subscription management securely.</li>
    </ul>
    <p>These third-party providers have their own privacy policies, and we encourage you to review them.</p>

    <h2>5. Your Rights and Choices (Account Deletion)</h2>
    <p>You have full control over your data:</p>
    <ul>
        <li><strong>Access & Modification:</strong> You can view or update your check-in history, emergency contact, "Will Message," and settings directly within the app at any time.</li>
        <li><strong>Account Deletion:</strong> In accordance with Apple's guidelines, you can <strong>delete your account and all associated cloud data directly within the App Settings</strong>. This action is irreversible.</li>
        <li><strong>Subscription Management:</strong> Subscriptions are managed by Apple. You can cancel or manage your subscription via your iPhone's "Settings" &gt; "Apple ID" &gt; "Subscriptions".</li>
        <li><strong>Analytics Opt-out:</strong> You may limit ad tracking and analytics through your iOS device's privacy settings (Settings &gt; Privacy & Security &gt; Tracking).</li>
    </ul>

    <h2>6. Emergency Contact Responsibility</h2>
    <p><strong>Important:</strong> By providing an emergency contact's email address, you represent and warrant that you have obtained that person's express consent to share their contact information with us for the sole purpose of receiving emergency safety alerts. We will not use this email address for marketing purposes.</p>

    <h2>7. Emergency Alert Mechanism</h2>
    <p>This app functions as a "Dead Man's Switch."</p>
    <ul>
        <li>If you fail to check in within your set interval, our system will automatically email your designated contact.</li>
        <li>This email will contain your preset "Will Message" and the time of your last confirmed activity.</li>
        <li>You acknowledge that this service relies on internet connectivity and server availability.</li>
    </ul>

    <h2>8. Children's Privacy</h2>
    <p>Our service is not intended for children under the age of 13. We do not knowingly collect personal information from children under 13. If we become aware that we have inadvertently collected such data, we will take steps to delete it immediately.</p>

    <h2>9. Changes to This Policy</h2>
    <p>We may update this Privacy Policy periodically. We will notify you of significant changes by updating the "Last Updated" date at the top of this policy. Your continued use of the app after changes constitutes acceptance of the new policy.</p>

    <h2>10. Contact Us</h2>
    <p>If you have any questions about this Privacy Policy or your data rights, please contact us at:</p>
    <p><strong>Email:</strong> <a href="mailto:kuma@oneboom.vip">kuma@oneboom.vip</a></p>
</div>
</body>
</html>
