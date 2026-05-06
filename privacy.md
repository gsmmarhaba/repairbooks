# Privacy Policy for RepairBooks

**Effective Date:** May 6, 2026

Thank you for choosing to be part of our community at RepairBooks ("we", "us", "our"). We are committed to protecting your personal information and your right to privacy. This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our mobile application, RepairBooks (the "App").

Please read this privacy policy carefully as it will help you make informed decisions about sharing your personal information with us.

## 1. Core Philosophy: Offline-First
RepairBooks is designed as an "offline-first" application. This means that, by default, the core data you generate while using the App (including your inventory, customer details, jobs, and financial ledgers) is stored **locally on your device** using an internal SQLite database. We do not automatically upload, sync, or view your daily shop data on our servers.

## 2. Information We Collect and How We Use It

### A. Authentication Data (Firebase)
To securely identify you and ensure that only you can access your shop's profile, we use Firebase Authentication (provided by Google). 
*   **What we collect:** Your phone number.
*   **How we use it:** To send you an SMS OTP (One-Time Password) for account creation and login. 

### B. Shop Profile Information
During onboarding, you provide basic shop details (Shop Name, Currency, Terms & Conditions). 
*   **What we collect:** Basic shop profile settings.
*   **How we use it:** This information is saved locally and a basic identifier may be securely registered via Firebase Cloud Firestore to allow for optional features like sharing PDF invoices or ledgers with your customers.

### C. Google Drive Backup Data (User-Initiated)
To prevent data loss if you lose or break your phone, RepairBooks offers a secure Google Drive Backup feature. If you explicitly choose to link your Google account, the App will request access to a specific, hidden folder in your Google Drive (the `drive.appdata` scope).

*   **What we collect/transfer:** The App securely uploads an encrypted copy of your local SQLite database directly to your personal Google Drive.
*   **How we use it:** This data is used **exclusively** to allow you to restore your shop's data to a new device or recover from a data loss event. 
*   **What we DO NOT do:** We do not have access to your backup files. The backup is stored in your personal Google Drive account. We do not view, read, modify, or download your personal Google Drive files outside of the specific RepairBooks backup file.

## 3. Google API Services User Data Policy (Limited Use Disclosure)
RepairBooks's use and transfer to any other app of information received from Google APIs will adhere to the **[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy)**, including the Limited Use requirements.

Specifically regarding the Google Drive API (`drive.appdata` scope):
*   We only use this access to read, write, and manage the specific database backup file created by RepairBooks.
*   We do not use this data to serve advertisements.
*   We do not allow humans to read this data (unless we have your affirmative agreement for specific support cases).
*   We do not sell or transfer this data to third parties.

## 4. Third-Party Services
The App uses third-party services that may collect information used to identify you.
Links to privacy policies of third-party service providers used by the App:
*   [Google Play Services](https://policies.google.com/privacy)
*   [Google Analytics for Firebase](https://firebase.google.com/policies/analytics)
*   [Firebase Crashlytics](https://firebase.google.com/support/privacy/)

## 5. Security of Your Information
We use administrative, technical, and physical security measures to help protect your personal information. Your local data remains on your device. Your Google Drive backups are secured by Google's infrastructure and are tied directly to your Google Account credentials.

## 6. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Effective Date" at the top. You are advised to review this Privacy Policy periodically for any changes.

## 7. Contact Us
If you have questions or comments about this policy, you may email us at:
**youfixers@gmail.com**
