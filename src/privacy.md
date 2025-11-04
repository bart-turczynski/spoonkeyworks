# Privacy Policy

Last updated: May 28, 2024

Reddit Answers Saver (the “Extension”) is a browser add-on that helps you capture the structured content shown on Reddit’s `/answers/` pages and save it to a JSON file on your device. This Privacy Policy explains what information the Extension accesses, how that information is used, and the choices you have.

## Information We Access

- **Reddit Answers page content.** When you activate the Extension on a Reddit Answers page, it reads the content already loaded in your browser tab, including question text, headings, conversation IDs, answer text and HTML, related questions, source posts, and outbound links.
- **Browser tab context.** The Extension uses Chrome’s `tabs` permission only to confirm the active tab and initiate downloads.

The Extension does **not** collect browsing history, cookies, login information, or any data from sites other than Reddit Answers pages (`*://*.reddit.com/answers/*`).

## How Information Is Used

- All processing happens locally in your browser. The Extension structures the Reddit Answers content into JSON and immediately triggers a download via Chrome’s `downloads` permission.
- No information is transmitted to the Extension publisher, stored on external servers, or shared with third parties.
- The downloaded JSON file is saved to your device under a filename such as `reddit-answers/<timestamp>-<question>.json`.

## Data Retention & Control

- The Extension does not retain any information after the download finishes.
- You control the JSON files saved to your device and may delete them at any time.
- You can remove the Extension at any time by uninstalling it from your browser’s extensions page.

## Permissions Explained

- `tabs`: Required to determine the active tab when the omnibox keyword is used or when initiating an export.
- `downloads`: Required to save the JSON file that you explicitly request.
- `*://*.reddit.com/*`: Needed so the content script can read the data already displayed on Reddit Answers pages.

The Extension does not request or use any additional permissions.

## Children’s Privacy

The Extension is intended for general audiences and does not knowingly collect any personal information from children.

## Changes to This Policy

We may update this Privacy Policy to reflect changes to the Extension or applicable laws. Material updates will be noted in the project repository and the “Last updated” date will change. Continued use of the Extension after an update constitutes acceptance of the revised policy.

## Contact

If you have questions about privacy or need support, please open an issue on the project repository or reach out via the support channel listed in the Chrome Web Store listing.
