# Squid

This option can be activated from menu option Status after Wireless option is active.

Squid

You will find 3 options in Squid module.
Squid

This option is used to Start or Stop Squid.
Inject

If this option is active, Squid will inject each javascript file passing throw the proxy.
By default you will find 2 scripts as an example: pasarela_get_submit and pasarela_xss

pasarela_xss is a simple script that inject an annoying alert with the message XSS.
pasarela_get_submit is a script that captures the submitted form content without being noticed by the user.
The captured content can be found in: /var/www/site/inject/data.txt

Note: To add new scripts, just copy your script in /FruityWifi/squid.inject/ with the extension “.js”.
Iptables

If this option is active all traffic that passes through the interface Wifi will be redirected to Squid. By default this option will be activated when you start Squid.
