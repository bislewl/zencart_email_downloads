===Zen Cart Email Downloads from Orders Screen v1.1.1===

Tested on Zen Cart 1.39H & 1.5.X and tested on PHP 5.5.18
License Commercial ==

This module is an advanced installation.

This module adds a "email download" with customized message to your admin
orders screen, if a download is purchased. Many times people fail to download
their order, then maybe can't login and many other troublesome issues happen
with downloads. Now, you can easily resend the download to their email,
as an attachment when troubles arise. Huge timesave from FTP to fetch the 
download, typing an all new email every time etc.

Need this installed for you? (https://zencart.codes/index.php?main_page=product_info&cPath=32&products_id=39)

Module release 10/03/2014 http://pro-webs.net/ 

Please provide bug fixes and issues to https://pro-webs-support.com/

===Database Changes===
None

===Core File Edits===
Yes

===Basic Installation===
1. !!!! Backup your database and affected files !!!!
   
2. Rename your admin to your own secret admin folder name in the CATALOG folder. Upload the files in 
   the module catalog folder to the matching file structure in your Zen Cart 
   directory. There are no ovewrites in this part.
 
3. See orders_download.txt in CORE_EDITS folder and merge the commented changes marked 
   with "Email Downloads from Orders Screen" in to your own 
   catalog/your_admin/modules/orders_download.php
   * There are 6 edits
   **This file is a 1.5.4 file, so merging other versions will require additional skill 
   
4. The default admin email download text can be edited in catalog/YOUR_ADMIN/includes/modules/orders_download.php
5. Test Module using a variety of possible cases
6. Please direct support questions here (https://pro-webs-support.com/)      
   
The default admin email down text can be edited in catalog/YOUR_ADMIN/includes/modules/orders_download.php

===EOF Basic Installation===        
       
===Change History===
Date       Version  Who             Why
===============================================================================
10/03/2014  1.0.0      PRO-Webs.net    Initial Release
01/13/2015  1.1.0      PRO-Webs.net    Zen Cart version 1.5.4 update 
04/30/2015  1.1.1      PRO-Webs.net    Modified Files to update from 1.5.4; reorganization; bug fixes