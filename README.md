# Download-Costco-Receipts
Download all of your Costco In-Warehouse Receipts between two dates, in JSON format.

 * You can set your own Start/End dates or accept the defaults.
 * First run will set the default Start and End dates to 3 years (Costco Maximum)
 * Subsequent runs, the default Start date will be set to the last Costco Receipt date received (temporarily stored in localStorage from the previous run).

 # Usage:
 1) Go to **https://www.costco.com/OrderStatusCmd** in your browser.
 2) Log into your Costco Account.
 3) Open **DevTools** -> **Console** (tab);
    * Access the developer tools in **Chrome**, **Firefox**, and **Brave** using a keyboard shortcut or by **right-clicking on a webpage**.
    * **Windows / Linux**  - Ctrl + Shift + I
    * **macOS**            - Cmd + Option + I
    * **Browser**          - Right-Click in the webpage, then select Inspect from the context menu that appears.
 4) **Paste** the whole snippet below and press **Enter**. (or CTRL+Enter)
 5) Enter the desired Start and End dates when prompted (format YYYY-MM-DD). 
    * Press Enter at each date prompt if you prefer to accept the default values.
    * **NOTE:** You can press Cancel to abort.
 6) Once complete, you will be presented with a dialog window to save a JSON file named **costco-receipts-<ISO_TIMESTAMP>.json** containing all your Costco receipts in an array format (_sorted oldest -> newest_)
 
# IMPORTANT: 
  * **The downloaded JSON contains sensitive data. Treat it accordingly.**
