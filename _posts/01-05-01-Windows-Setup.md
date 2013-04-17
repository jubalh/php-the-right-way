---
isChild: true
---

## Windows Setup {#windows_setup_title}

PHP ist auf verschiedene Arten für Windows verfügbar. Du kannst die [Binaries runterladen][php-downloads] und bis vor kurzem konntest du einen 'msi'Installer benutzen. Dieser Installer wird seit PHP 5.3.0 nicht mehr unterstützt.

Zum Lernen und Entwickeln auf deiner lokalen Maschine kannst du den mit PHP 5.4 eingebauten Webserver benutzen, und musst dich nicht um die Konfiguration kümmern. Wenn du lieber eine "All-In-One"-Lösung hättest, welche einen vollwertigen Webserver und MySQL enthält dann kommen folgende Tools für dich in Frage: [Web Platform Installer][wpi], [Zend Server CE][zsce], [XAMPP][xampp] und [WAMP][wamp]. Diese Tools werden dich schnell entwickeln lassen unterscheiden sich aber von Produktions-Umgebungen. Nimm dich also in Acht wenn du auf Windows entwickelst, später aber auf einem Linux System hostest.

Wenn dein Produktionssystem auf Windows läuft dann wird dir IIS7 am stabilsten sein und die beste Performance haben. Um die Konfiguration zu vereinfachen kannst du [phpmanager][phpmanager] (ein GUI Plugin für IIS7) verwenden. IIS7 kommt mit eingebautem FastCGI, du musst nur PHP als Handler konfigurieren. Um Unterstützung und weitere Informationen zu bekommen gibt es für PHP einen [speziellen Bereich auf iis.net][php-iis].

[php-downloads]: http://windows.php.net
[phpmanager]: http://phpmanager.codeplex.com/
[wpi]: http://www.microsoft.com/web/downloads/platform.aspx
[zsce]: http://www.zend.com/en/products/server-ce/
[xampp]: http://www.apachefriends.org/en/xampp.html
[wamp]: http://www.wampserver.com/
[php-iis]: http://php.iis.net/
