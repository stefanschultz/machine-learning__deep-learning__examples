# **Demo examples for ml5.js and p5.js:**
- Bird Image Classification with MobileNet and ml5.js: [./BirdImageClassification/](./BirdImageClassification/)

# Configuration:
- Go into loacated folder and run "npm install" to install all neccessary modules.
- Start local HTTP server by typing in your terminal "npm run start-server" and navigate to [http://127.0.0.1:5700/](http://127.0.0.1:5700/)
- Check in your browser if your hardware acceleration is activated. E.g. check in Chrome browser also your flags and see in your browser console for this error **"Error: WebGL is not supported on this device"**.

**First:**
1. Go to the **Settings** and scroll to **Advanced**.
2. Under **System** enable **use hardware acceleration when available** option.

**Second:**
1. Enter the URL **chrome://flags** in the address bar from the browser.
2. Locate the section on that page called Override software rendering list.
3. Change the **Disabled** option to **Enabled**.
4. Relaunch your browser.
5. Return to the **chrome://gpu** page and check whether acceleration is enabled.