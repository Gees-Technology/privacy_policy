# Privacy Policy for Madheedh Exchange (Al Fatxi Exchange)

**Effective Date:** January 12, 2026

This Privacy Policy describes how Madheedh Exchange (also referred to as "Al Fatxi Exchange", "we", "us", or "our") collects, uses, and shares information when you download, install, or use our mobile application (the "App"). By using the App you agree to the collection and use of information described in this policy.

**App and Service Overview**

- App name: Madheedh Exchange (displayed in the app as "Madheedh Exchange").
- Platforms: Android and iOS (mobile devices).
- Core functionality: currency exchange rates, transaction creation and tracking, user authentication, and sharing app content.
- Backend services: Firebase (Authentication, Cloud Firestore, and Firebase Storage) and third-party packages as described in our app manifest.

## 1. Information We Collect

### 1.1 Information You Provide

- **Account Information:** When you register or sign in using the App we collect your email and any profile information you provide (for example, display name). Authentication is handled by Firebase Authentication.  
- **Transaction Data:** When you create an exchange or transaction, we collect details necessary to process and record that transaction (amounts, currency codes, timestamps, metadata you enter). This data is stored in Cloud Firestore.  
- **User Content:** Any messages, notes, or files you explicitly upload or attach to your account or transactions. Uploaded files may be stored in Firebase Storage.  
- **Communications:** Feedback, support requests, or other messages you send to us.

### 1.2 Information Collected Automatically

- **Device & Usage Information:** Technical information collected automatically when you use the App, such as device model, operating system version, unique device identifiers, app version, network information, and usage statistics (which screens you visit and how you use features).  
- **Log Data:** Standard server and analytics logs, including IP address, timestamps, and error reports.  
- **Connectivity Status:** The App may check network connectivity (via the connectivity_plus package) to provide offline/online behavior and to detect changes in connectivity.

### 1.3 Information From Third Parties

- **Third-party services:** If you choose to connect or share via third-party services (for example, share links using native share dialogs), we may receive information returned by those services according to their own privacy policies.  
- **Device permissions:** If you grant permission (see Section 7), the App may access features such as storage access or device location. Permissioned data will only be used for the purposes described when requesting the permission.

## 2. How We Use Your Information

- **Provide and maintain the App:** To enable authentication, store and retrieve your transactions and exchange-rate data, and provide the App features.  
- **Personalize experience:** To present content and settings specific to you.  
- **Communications:** To send technical notices, security alerts, and responses to support requests.  
- **Analytics & Improvements:** To analyze usage patterns, fix bugs, and improve the App.  
- **Fraud prevention & security:** To detect and prevent abuse and fraudulent activity.  
- **Sharing features:** To allow you to share rates or content using device-native share mechanisms.

## 3. How We Store & Where We Keep Data

- **Firebase Cloud Firestore:** Transaction records, app-specific user data, and configuration (exchange rates fetched and cached) are stored in Cloud Firestore.  
- **Firebase Storage:** Files and user-uploaded content (if any) are stored in Firebase Storage.  
- **Firebase Authentication:** Authentication credentials are handled by Firebase Auth; we do not store raw passwords on our servers.  
- **Local Storage:** The App may use secure local storage (via flutter_secure_storage) for tokens, session identifiers, or other small pieces of sensitive data required for operation.  
- **Retention:** We retain user data as long as necessary to provide services, comply with legal obligations, resolve disputes, and enforce our agreements. Specific retention periods may vary by data type.

## 4. How We Share Information

- **Service providers:** We may share data with third-party service providers who help operate the App (e.g., Firebase services, analytics, crash reporting, email delivery).  
- **With your consent:** When you explicitly permit sharing (for example, when you share a rate or transaction via social sharing).  
- **Legal & safety:** When required by law or to protect rights, safety, or property.  
- **Business transfers:** In connection with a merger, acquisition, or sale of assets—users will be notified and any transfer will be subject to this policy or a successor policy.

We do not sell personal information to third parties.

## 5. Third-Party Libraries and Services

The App uses open-source and third-party packages included in our `pubspec.yaml`, including but not limited to: Firebase services (`firebase_core`, `firebase_auth`, `cloud_firestore`), `flutter_secure_storage`, `connectivity_plus`, `permission_handler`, `url_launcher`, `share_plus`, and analytics/crash reporting libraries if enabled. These providers may collect or process information according to their own policies.

## 6. Security

We implement reasonable technical and organizational measures (encryption in transit, Firebase security rules where applicable, secure local storage for sensitive tokens) to protect user data. However, no method of transmission over the internet or electronic storage is completely secure. If you suspect an account breach, contact us immediately.

## 7. Permissions

The App may request the following permissions depending on device and platform:  

- **Storage / Files access:** To allow you to pick or save attachments or files (used only when you explicitly upload or download content).  
- **Location:** The App may request location only if you choose to enable location-based features.  
- **Network state:** To monitor connectivity for online/offline behavior.  

Permissions are requested at runtime and you can revoke them at any time via your device settings.

## 8. Children

The App is not intended for children under 13 (or the minimum age in your jurisdiction). We do not knowingly collect personal information from children. If we learn that we collected personal information from a child without parental consent, we will delete it.

## 9. Your Rights and Choices

- **Access & correction:** You can request a copy of the personal information we hold about you and ask that we correct inaccuracies.  
- **Deletion:** You may request deletion of your personal data; certain data may be retained for legal or operational reasons (for example, to resolve disputes).  
- **Opt-out of marketing:** You can opt-out of promotional communications by following the unsubscribe instructions in those messages or contacting us.  

To exercise rights or make requests, contact us at the email below. We may ask you to verify your identity before complying with certain requests.

## 10. International Transfers

Data may be stored and processed in servers located in countries other than your own (Firebase-managed servers). We take steps to ensure appropriate safeguards for transfers.

## 11. Changes to This Policy

We may update this Privacy Policy. When we do, we will update the "Effective Date" and notify users within the App or by other reasonable means. Continued use after changes constitutes acceptance.

## 12. Contact Us

If you have questions, requests, or concerns about this Privacy Policy or how your data is handled, contact us at:  

- **Email:** <monkedlufffy@gmail.com>  
- **Project / Firebase project ID:** madheed  

--

This document is provided for informational purposes and does not constitute legal advice. Consider consulting a legal professional to ensure compliance with applicable laws and regulations for your app and target markets.
