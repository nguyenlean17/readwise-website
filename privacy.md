# Privacy Policy for ReadWise 

**Last Updated:** April 7, 2026


Thank you for choosing ReadWise. This extension was built as a student-led educational project, and our sole priority is helping people learn English—not profiting off your data. We are not a corporation, we do not run ads, and we strictly do not sell any user data to third parties. We are committed to protecting your privacy and being fully transparent. This Privacy Policy explains what limited information our extension interacts with, how it is used, and how it is protected.

This policy is designed to fully comply with the Google Chrome Web Store User Data Privacy policies.

## 1. Information We Collect and How We Use It

To provide our core features—inline translation, vocabulary tracking, and AI-powered reading comprehension—the Extension requires access to certain data. **We only collect data strictly necessary for the Extension to function.**

### A. Website Content (Page Text)
- **What is collected:** When you use the "Take Quiz" or "Evaluate Difficulty" features, the Extension reads the text content of the article currently open in your active tab (up to a maximum of 15,000 characters).
- **How it is used:** This text is securely transmitted directly to the **Google Gemini API** (`generativelanguage.googleapis.com`) solely for the purpose of generating reading comprehension questions and determining the reading difficulty level.
- **Data Retention:** We do not store this website content on any external servers or backend databases. It is processed transiently by Google Gemini and immediately discarded once your quiz or difficulty rating is generated.

### B. Selected Words for Translation
- **What is collected:** When you click or highlight a word on a supported website format to translate it, the Extension captures the specific word or short phrase.
- **How it is used:** This word is sent to a custom Google Apps Script endpoint and the Free Dictionary API to retrieve the Vietnamese translation, phonetics, and definitions.

### C. Local Storage (Saved Articles & Vocabulary)
- **What is collected:** URLs and titles of articles you explicitly click "Save Article" on, as well as the words you save to your "Vocab Bank", and your genre/difficulty preferences.
- **How it is used:** This information is saved **locally on your device** utilizing Chrome's Local Storage API. We do not sync, exfiltrate, or transmit your saved vocabulary or reading history to our own external servers.

## 2. Third-Party Services

To provide AI and translation capabilities, the Extension interacts with the following third-party services:
- **Google Gemini API:** Receives website article text to generate AI reading quizzes and difficulty evaluations. Please refer to Google's Privacy Policy regarding data processed by their Generative AI APIs.
- **Google Apps Script:** Receives individual translated words.
- **Free Dictionary API:** Receives individual words to fetch English definitions and phonetic data.

## 3. What We Do NOT Do

To be absolutely clear on our data practices:
- **We DO NOT sell** your data to third parties.
- **We DO NOT use** your data for targeted advertising, analytics tracking, or marketing purposes.
- **We DO NOT collect** or monitor your general web browsing history (only pages you actively interact with using our AI features or save to your list are processed).
- **We DO NOT store** your webpage content, translations, or history on our servers. Everything resides locally in your browser.

## 4. Your Control

Because your data (Vocab Bank, Saved Articles, and Settings) is stored entirely in your local Chrome storage, you have full control over it. You can delete your data at any time by:
1. Using the reset/clear functions within the Extension's UI (if available).
2. Uninstalling the Extension, which automatically clears the associated local storage data.

## 5. Changes to This Privacy Policy

We may update this Privacy Policy from time to time as we add new features. If we make significant changes to how we handle user data, we will update the "Last Updated" date at the top of this policy and notify you within the Extension.

## 6. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us at:

**Email:** 
nguyenlean17@gmail.com
