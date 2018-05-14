#Ambiente Dev Linux - 4 máquinas

-------------------------------------------------------------------------------------


# dev-site-a
_RHEL 5 - host masters e alguns slaves_

- **jboss-eap-6-domaincontroller (19990)**
  - cotacao-server-group
  - bbr-server-group
  - bbl-server-group
  - onshore-server-group
  - onshore2-server-group
- **jboss-eap-7-domaincontroller (29990)**
  - dpb-server-group
- **jboss-eap-7-pre-uat-domaincontroller _host-master_ (39990)**
  - cotacao-server-group
    - **cotacao13**
  - dpb-server-group
    - **dpb-backend-03**
- **jboss-4-site**

-------------------------------------------------------------------------------------

# dev-site-b
_RHEL 5 - hosts slaves e alguns standalones_

- jboss-eap-6-host-cotacao11 (19990)
  - **cotacao11**
- jboss-eap-6-host03 (19990)
  - **bbr-backend-01**
  - **bbl-backend-01**
  - **onshore-backend-01**
  - **onshore2-backend-01**
- jboss-eap-7-delta01 (29990)
  - **dpb-backend-01**
- **jboss-eap-7-web-sso2**
- **jboss-4-dmz**





-------------------------------------------------------------------------------------

# dev-site-c
_RHEL 5 - dmz - standalones_

-  **jboss-eap-6-bbr1**
-  **jboss-eap-6-bbl1**
-  **jboss-eap-6-onshore1**
-  **jboss-eap-6-onshore3**
-  **jboss-eap-7-dpb1**
-  **jboss-eap-7-sso1**

-------------------------------------------------------------------------------------

# dev-site-d
RHEL 6 - dmz - standalones - SIT_
-  **jboss-eap-7-dpb3**
-  **jboss-eap-7-sso3**

-------------------------------------------------------------------------------------

```






























end empty space for better scroll
```