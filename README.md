# testtt
測試咖啡廳開店
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://orange1030.github.io/testtt/index.html$1 [R,L]
