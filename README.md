# htaccess-firewall
The orginal .htaccess webapplication firewall

Released, somewhere in 2007 (updated to 2025), my orginal .htaccess webpplication firewall. A quick and practical way to stop webapplication attacks without having to shut your server down. It runs before PHP, at the apache level. So any attacks are quickly mitigated before they even reach PHP. It is also possible to log these requests, for more information on that see the apache mod_rewrite specifications. It uses blacklisting as WAF technique.

Used by Joomla when they got attacked.
