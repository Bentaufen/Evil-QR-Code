# Evil-QR-Code
This is a simple attack where I take advantage of QR-Codes to execute javascript on the device that scanned the QR-Code.

<b>How this works:</b>
1. Generate QR-Code with an embedded link that points to a site with an XSS vulnerability.
2. The user's device navigates to the page after scanning the QR-Code.
3. The malicioius site executes javascript on the user's device.

<b>How is this any more dangerous than clicking on a link?</b><br>
Users are unable to know what they are scanning before they scan. This is even more dangerous if the scanner automatically loads the URL that is embedded into the QR-Code.
