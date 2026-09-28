# Web to APK Builder



Android WebView worker for Forgekit. GitHub Actions builds an installable debug APK from a website URL and app metadata.



## Build from GitHub Actions



Open **Actions → Build Android APK → Run workflow**, then provide:



- Website URL
- 
- App name
- 
- Package name
- 
- Version name and numeric version code
- 
- Icon preset (`nova`, `orbit`, `pulse`, or `arc`)
- 


The generated APK is uploaded as a workflow artifact. The APK is a debug-signed WebView app; it is installable for testing. For Play Store release, add a signing keystore and release signing secrets.






