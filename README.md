# FB MarketPlace Messenger Cleanup

Version 1.0 — a Chrome extension for reviewing and selectively cleaning up Facebook Marketplace Selling conversations.

## Features

- Opens the Marketplace Inbox in the current Chrome tab and attempts to select Marketplace messages
- Scans conversations currently loaded in the interface
- Filters conversations by a user-selected minimum age
- Allows review and CSV export before deletion
- Requires confirmation before deleting conversations
- Stops processing if deletion cannot be verified

## Installation (Windows)

1. Download `FB_MarketPlace_Messenger_Cleanup_V1.0.zip` from this repository once the release archive has been uploaded.
2. Right-click the ZIP and choose **Extract All**. Do not run setup inside the compressed ZIP.
3. Open the extracted folder and double-click `Install.cmd`.
4. Select **Yes** when asked whether to install the extension.
5. Choose a parent folder. Setup creates **FB MarketPlace Messenger Cleanup** there.
6. Open Chrome at `chrome://extensions`.
7. Turn on **Developer mode**, click **Load unpacked**, and choose the newly created extension folder.
8. Open Facebook and use the extension from Chrome's toolbar.

Chrome requires the user to approve installation of an unpacked extension; the Windows installer cannot silently enable it.

## Using the extension

Open Facebook, launch the extension, select the minimum age in days, and scan. Review eligible conversations and export CSV if desired. Select conversations deliberately and confirm before deleting. Deletion is irreversible; test scanning and export before deleting anything.

## Limitations and safety

- Only conversations loaded in Facebook's interface can be inspected.
- Facebook can change its layout and break automatic navigation or message detection.
- Review every selection before deletion. Do not assume all matching conversations are safe to remove.
- This project is not affiliated with or endorsed by Meta or Facebook.

## License and attribution

No open-source license is granted at this time. Code provenance and third-party attribution are under review before reuse or redistribution terms are selected.
