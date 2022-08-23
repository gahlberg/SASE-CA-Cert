## CA Certificate for SASE endpoints 
    
## For utilizing SSL Inspection on SASE Account 361633
   * **Download this repo locally to your SASE Endpoint:**
      - Click code button and Download ZIP
      
   
   ### 1. Directions for Chrome:
      * #### Go to Settings
      * #### Go to Privacy and security
      * **Go to Security**
      * **Scroll down to Manage certificates**
      * **(if using Certificate stores on Windows) click the Import Button**
      * **Browse to the extracted .crt file and select saseCA**
      * **click Next**
      * **and place in the Trusted Root Certificate Authorities (store)**
   
   ### 2. Directions for Firefox:

      * **Go to Settings**
      * **Go to Privacy & security**
      * **Scroll down to Certificates**
      * **Click the View Certificates Button**
      * **Under Authorites Tab, click the Import Button**
      * **Browse to the extracted .crt file and select saseCA**
      * **click checkbox Trust this CA to identify websites**
      * **click ok and ok again**
      * **be sure to reference websites via https://<websiteURL>** 