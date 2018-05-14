#Ambiente Dev Linux - 3 máquinas

-------------------------------------------------------------------------------------
## **dev-site-a**

- **jboss-eap-6-domaincontroller (19990)**
  - cotacao-server-group
  - bbr-server-group
  - bbl-server-group
  - onshore-server-group
  - onshore2-server-group
- **jboss-eap-7-domaincontroller (29990)**
  - dpb-server-group
- **jboss-4-site**

-------------------------------------------------------------------------------------

## **dev-site-b**

- jboss-eap-6-host-cotacao11 (dc = dev-site-a : 19990)
  - **cotacao11**
- jboss-eap-6-host03 (dc = dev-site-a : 19990)
  - **bbr-backend-01**
  - **bbl-backend-01**
  - **onshore-backend-01**
  - **onshore2-backend-01**
- jboss-eap-7-delta01 (dc = dev-site-a : 29990)
  - **dpb-backend-01**
- **DMZ-jboss-eap-7-web-sso2**
- **DMZ-jboss-4-dmz**

-------------------------------------------------------------------------------------

## **dev-site-c**

-  **DMZ-jboss-eap-6-bbr1**
-  **DMZ-jboss-eap-6-bbl1**
-  **DMZ-jboss-eap-6-onshore1**
-  **DMZ-jboss-eap-6-onshore3**
-  **DMZ-jboss-eap-7-dpb1**

-------------------------------------------------------------------------------------

## **dev-site-d**

- N/A

-------------------------------------------------------------------------------------