# WEEK 10 & 11

---

1. Setup 2 VM- MHN-admin,mhn-honeypot
2. Set Firewall Rules
3. Install MHN application in mhn-admin
4. Access MHN through External IP
5. Deploy Honeypot-1 in another VM
6. Attack the honeypot
7. Deploy other honeypot [BONUS]


---
Google Cloud Setup

![](https://i.imgur.com/q6Efb2D.png)


---
Firewall Settings

![](https://i.imgur.com/Jmms0Qd.png)


---

HONEYPOTS DEPLOYED
![](https://i.imgur.com/1QTL7Ir.png)


---
## ISSUES
* Install MHN application error
* Honeypot deploy script kept failing
    Flask-Login module has to be downgraded to overcome this     error. 
    *     pip uninstall Flask-Login==0.3.0 
    *     pip install Flask-Login==0.2.11
    https://github.com/threatstream/mhn/issues/650
* No attacks was recorded

