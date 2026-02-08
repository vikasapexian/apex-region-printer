# APEX Region Printer

APEX Region Printer is a Dynamic Action plugin for Oracle APEX that allows you to print a specific page region or HTML container instead of the entire page.

It is designed for enterprise use cases such as invoices, reports, salary slips, and certificates, with support for images, colors, and multi-page content.

![Preview]([https://raw.githubusercontent.com/www-smithchain-com/Apex-Font-Toggler/main/preview.gif](https://github.com/vikasapexian/apex-region-printer/blob/main/myFile08-02-2026_130937.gif))
## Features

- Print any Oracle APEX region or HTML container
- Supports images and logos
- Handles multi-page content
- Color and border-friendly print output
- Hides screen-only elements using `.no-print`
- Lightweight, client-side execution
- No server-side processing required

---

## Requirements

- Oracle APEX 19.1 or above
- Universal Theme (recommended)
- Modern browser (Chrome, Edge, Firefox)

---

## Installation

1. Download the plugin from this repository.
2. In Oracle APEX, go to **Shared Components → Plug-ins**.
3. Click **Import** and upload the plugin file.
4. Install the plugin into your application.

---

## How to Use

1. Create a page region (Static Content, Report, Interactive Grid, etc.).
2. Set a **Static ID** for the region you want to print.
3. Create a button on the page (e.g. **Print**).
4. Create a **Dynamic Action** on button click.
5. Add a **True Action** and select **APEX Region Printer**.
6. Enter the **Region Static ID** in the plugin attribute.
7. Save and run the page.

Click the button to print only the selected region.

---


### About

Author: Vikas Pandey   
Twitter: @Smith121266   
LinkedIn: linkedin.com/in/vikas-pandey-aba223120/  
