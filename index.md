# Privacy Policy – Kitoko Voice for Salesforce

Last updated: 06 March 2026

## 1. Overview
Kitoko Voice for Salesforce is a Chrome extension that helps users capture voice, convert speech to text, and save results into Salesforce records.

This extension is intended for business use on Salesforce pages.

## 2. Data We Process
Depending on usage, the extension may process:
- Microphone audio (only when user starts recording)
- Speech-to-text output (transcript)
- Salesforce record context (record ID from current page URL)
- Salesforce session/auth context required to perform authorized API calls

## 3. How Data Is Used
Data is used only to provide extension functionality:
- Real-time speech recognition in browser context
- Final transcription processing via configured transcription service
- Uploading audio file to the relevant Salesforce record (Files, fallback: Notes & Attachments)

## 4. Third-Party Services
The extension may communicate with these services:
- Salesforce APIs (`*.salesforce.com`, `*.force.com`) for record/file operations
- Speech/transcription providers used by the extension flow (e.g., browser speech services and configured transcription endpoint)

Your use of third-party services is subject to each provider’s own terms and privacy policies.

## 5. Storage and Retention
- The extension itself does not provide a separate long-term storage service for user recordings.
- Final saved files/transcripts are retained in your Salesforce organization according to your Salesforce retention settings.
- Temporary processing by third-party services may occur as part of transcription.

## 6. Permissions Explained
The extension requests permissions such as:
- `tabs`: detect and interact with the active Salesforce tab
- `contextMenus`: provide right-click start actions
- `cookies`: read Salesforce session context required for authenticated API actions

## 7. Data Sharing
We do not sell personal data.
Data is shared only as technically necessary to deliver the feature flow (transcription + Salesforce save operations).

## 8. Security
Reasonable technical measures are used to reduce unauthorized access risk. However, no method of transmission or storage is 100% secure.

## 9. User Controls
Users can:
- Start/stop recording at any time
- Remove the extension at any time
- Delete created files/records from Salesforce according to org permissions

## 10. Children’s Privacy
This extension is not directed to children under 13.

## 11. Changes to This Policy
We may update this policy periodically. Updates are published on this same page with a revised date.

## 12. Contact
For privacy questions or requests:
- Email: kemalettin.taylan@kitokogroup.com
