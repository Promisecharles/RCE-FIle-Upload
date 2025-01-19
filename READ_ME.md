Online Railway Reservation System - File upload RCE (/admin/emp-profile-avatar.php)

Vendor Homepage:

https://codeastro.com/online-railway-reservation-system-in-php-with-source-code/

V1.0 Tested on:

PHP, Apache, MySQL Affected Page:

/admin/emp-profile-avatar.php
Steps To Reproduce

    Navigate to the following URL of the Online Railway Reservation System: Url : http://localhost/ORRS-PHP/admin/emp-profile-avatar.php

    Upload a malicious web shell (e.g., a .php file containing shell commands).

    Access the uploaded file through the URL: http://localhost/ORRS-PHP/admin/assets/img/profile/web.php

    Use the web shell to execute commands on the server. [For Example: dir ]

Proof of vulnerability
