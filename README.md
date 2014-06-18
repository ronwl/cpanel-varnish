## cpanel-varnish

Install Varnish on cPanel server to serve static files.

**Note:** Make sure you review the code before executing it.

---

#### Installation

````bash
wget https://raw.githubusercontent.com/ronwl/cpanel-varnish/master/install.sh
````

````bash
chmod +x install.sh
````

````bash
./install.sh
````

You can play around with Varnish setting to get best result based on your preferences
````bash
/etc/varnish/default.vcl
````

---

#### Uninstall

In case you want to reverse the setting

````bash
wget https://raw.githubusercontent.com/ronwl/cpanel-varnish/master/uninstall.sh
````

````bash
chmod +x uninstall.sh
````

````bash
./uninstall.sh
