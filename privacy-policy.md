# Privacy Policy for Quran by Helal

**Effective Date:** October 17, 2025
**Last Updated:** October 29, 2025

## Introduction

Helal ("we," "our," or "us") operates the Quran by Helal mobile application (the "App"). This page informs you of our policies regarding the collection, use, and disclosure of personal data when you use our App.

## Information We Collect

### Personal Information
We do not collect personally identifiable information such as names, email addresses, or phone numbers.

### Location Data
We collect your device's precise location (GPS coordinates) for the following purposes:
- Calculating accurate prayer times based on your location
- Determining the Qibla direction for prayer
- Providing location-specific Islamic content

**What location data we collect:**
- Precise GPS coordinates (latitude and longitude) when you use auto-detect
- City name and country information
- Country code

**How we use location data:**
- Prayer times calculation is performed locally on your device
- Location coordinates are stored locally on your device only
- City name and country code are sent to Firebase Analytics for app improvement
- GPS coordinates are NEVER sent to our servers or third parties

**Your control:**
- You can manually select your city instead of using GPS auto-detect
- Location data is only collected when you actively use prayer times or Qibla features
- You can revoke location permissions at any time through device settings

### Usage Data
We may collect information about how the App is accessed and used ("Usage Data"). This Usage Data may include:
- Device information (device type, operating system)
- App usage patterns and features used
- Crash reports and performance data
- Location information (city name and country code only, sent to analytics)

### User Feedback and Suggestions
We collect feedback and suggestions that you voluntarily submit through our in-app feedback feature:
- Your feedback message or suggestion text (text only)
- App version and device information (automatically included for troubleshooting)
- Submission timestamp

**Content Moderation:**
To maintain a respectful environment, all feedback submissions are automatically screened before being stored:
- **Spam Detection**: Identifies promotional content and repetitive submissions
- **Profanity Filter**: Blocks inappropriate language in Arabic and English
- **Malicious Content Detection**: Identifies and blocks suspicious URLs and harmful content
- **Automated Filtering**: Content is validated in real-time before submission
- **User Feedback**: You receive immediate notification if content is rejected, with a clear explanation
- **Privacy**: All moderation is automated - no human review unless necessary for app improvement

Inappropriate content is rejected immediately and is not stored. Only content that passes our automated screening is saved to Firebase Firestore.

**Important Notes:**
- All feedback submission is completely voluntary
- We do NOT collect any personal identifiers (name, email, phone number) with feedback
- Feedback is stored securely on Firebase Firestore servers
- You control what information you share with us
- Rejected content is not stored or retained

### Advertising
We use Google AdMob to display optional rewarded ads that help support app development:

**When ads are shown:**
- ONLY when you explicitly tap "Support the Developer" button
- You can always cancel before watching
- Ads are completely voluntary - never forced

**What data Google AdMob may collect:**
- Device information (device type, OS version)
- Ad interaction data (views, clicks)
- IP address (for ad targeting and fraud prevention)
- Advertising ID (can be reset in device settings)

**What we do NOT share with AdMob:**
- Your location data
- Your reading history
- Bookmarks or personal preferences
- Any personally identifiable information

**Your control:**
- You choose when to watch ads (by tapping Support button)
- You can opt out of personalized ads in device settings
- You can reset your advertising ID at any time

For more information about Google's use of data, see: [Google Privacy Policy](https://policies.google.com/privacy)

### Local Storage
The App may store data locally on your device including:
- Your reading preferences and settings
- Bookmarks and favorite verses
- Audio playback history
- Downloaded content for offline use

## How We Use Your Information

We use the collected data for:
- Providing and maintaining our App
- Improving user experience and App functionality
- Analyzing usage patterns to enhance features
- Detecting and preventing technical issues
- Reviewing user feedback and suggestions to improve the App
- Understanding user needs and priorities for future updates

## Data Sharing

We do not sell, trade, or rent your personal information to third parties.

### What We Share with Third Parties

**Firebase (Google):**
- **Firebase Analytics**: App usage patterns (features used, screen views, session duration), device information, city name and country code, app performance data
- **Firebase Firestore**: User feedback and suggestions (text messages only, app version, device info, timestamps)
- NO GPS coordinates, NO personal identifiers, NO reading content, NO screenshots

**Google AdMob:**
- **Rewarded Ads** (voluntary only): Device information, advertising ID, ad interaction data
- Only shown when you tap "Support the Developer" button
- You can cancel before watching
- See "Advertising" section above for full details

**Audio Streaming Services:**
- Quran recitation audio is streamed from public Islamic content providers (everyayah.com, quran.com)
- Only audio file requests are sent, no personal data

**Cloudflare Workers:**
- **Purpose**: Secure HTTPS proxy service for Quran tafsir (interpretation) content
- **What we share**: Anonymous requests about which Quranic verses you're viewing (surah and ayah numbers only)
- **What we DON'T share**: No personal information, no user identifiers, no location data, no reading history
- **Security**: All data is encrypted in transit using HTTPS/SSL
- **Caching**: Cloudflare may temporarily cache tafsir responses to improve loading speed
- **Privacy**: Cloudflare's edge network processes requests anonymously
- **Learn more**: [Cloudflare Privacy Policy](https://www.cloudflare.com/privacypolicy/)

This service helps us provide secure, fast access to Islamic scholarly interpretations while protecting your privacy.

**What We NEVER Share:**
- Your precise GPS coordinates
- Your reading history or bookmarks
- Personal information
- Any data that can identify you individually

### Third-Party Privacy Policies

Our App uses third-party services that have their own privacy policies:
- **Firebase Analytics**: [Google Privacy Policy](https://policies.google.com/privacy)
- **Google AdMob**: [Google Privacy Policy](https://policies.google.com/privacy) | [AdMob Policy](https://support.google.com/admob/answer/6128543)
- **Cloudflare Workers**: [Cloudflare Privacy Policy](https://www.cloudflare.com/privacypolicy/)
- **Quran Audio Providers**: Public Islamic content services

## Permissions We Request

Our App requests the following permissions to provide its features:

**Location Permissions:**
- **ACCESS_FINE_LOCATION**: To get your precise GPS coordinates for accurate prayer times calculation and Qibla direction
- **ACCESS_COARSE_LOCATION**: As a fallback if fine location is unavailable

**Other Permissions:**
- **INTERNET**: To stream Quran audio and access online content
- **ACCESS_NETWORK_STATE**: To check internet connectivity before streaming
- **POST_NOTIFICATIONS**: To send you prayer time reminders (only if enabled by you)
- **SCHEDULE_EXACT_ALARM**: To schedule precise prayer time alarms
- **FOREGROUND_SERVICE**: To play audio in the background
- **WAKE_LOCK**: To keep screen on while you're reading
- **VIBRATE**: For haptic feedback during interactions
- **RECEIVE_BOOT_COMPLETED**: To reschedule prayer alarms after device restart

All permissions are used solely for their stated purposes and are essential for app functionality.

## Data Security

We implement appropriate security measures to protect your data against unauthorized access, alteration, disclosure, or destruction:

- **HTTPS Encryption**: All network communications use HTTPS/SSL encryption to protect data in transit
- **Secure APIs**: All external API requests are made through encrypted connections
- **Input Validation**: User inputs are sanitized to prevent malicious content
- **Content Filtering**: Automated moderation protects against inappropriate submissions
- **Firebase Security**: User data stored in Firebase is protected by Google's enterprise-grade security
- **Local Storage**: Sensitive data (like your reading history and bookmarks) is stored only on your device

However, no method of transmission over the internet is 100% secure, and we cannot guarantee absolute security.

## Data Retention

- Usage data sent to Firebase Analytics is retained according to Google's data retention policies
- Local app data remains on your device until you uninstall the app
- You can clear local data through your device's app settings
- Location data is stored only on your device and can be removed by uninstalling the app

## Your Rights

You have the right to:
- Access the data we have about you
- Request correction of inaccurate data
- Request deletion of your data
- Object to our processing of your data

## Children's Privacy

Our App does not knowingly collect personal information from children under 13. If we discover that a child under 13 has provided us with personal information, we will delete it immediately.

## Changes to This Privacy Policy

We may update our Privacy Policy from time to time. We will notify users of any changes by posting the new Privacy Policy on this page and updating the "Effective Date."

## Contact Us

If you have any questions about this Privacy Policy, please contact us at:

**Email:** helal.tech.studio@gmail.com
**App:** Quran by Helal
**Developer:** Helal

---

## Summary of Changes

### October 29, 2025 Update
- **NEW**: Cloudflare Workers service disclosure for secure HTTPS proxy
- **NEW**: Content moderation system for user feedback (spam, profanity, malicious content filtering)
- **UPDATED**: Enhanced data security section with HTTPS encryption details
- **UPDATED**: Expanded third-party services list to include Cloudflare

### October 17, 2025 Update
This privacy policy was created to provide detailed and accurate information about:
- Precise location data collection (GPS coordinates) for prayer times and Qibla features
- Specific details about what data is shared with Firebase Analytics
- Complete list of app permissions and their purposes
- Clearer explanation of data retention practices
- User feedback and suggestions collection feature (text only)
- Firebase Firestore usage for feedback management
- Google AdMob rewarded ads for voluntary developer support
- Detailed disclosure of ad data collection and user control options

---

*This privacy policy was last updated on October 29, 2025.*
