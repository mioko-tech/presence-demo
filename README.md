
You can run this demo on localhost on Mac by:
- update docker-compose.yml to set [your Mac name].local. This can be found in your Mac System Preferences > Sharing.
- cd into root directory
- run docker-compose up
- Once you see the below two lines, it's running and ready to use:
  - https-portal_1  | [services.d] starting services
  - https-portal_1  | [services.d] done.
- The site is now available on your Mac at https://0.0.0.0:8181/
- The site is also available on iOS at https://[your Mac name]:8181 (ensure you have enabled Mac Preferences > Sharing > File Sharing and your iPhone is on the same wi-fi network as your Mac)
- If the site does not load try killing the Safari iOS app and re-launch it
- On Android, you should connect via USB and enable port forwarding for port 8181 in Chrome. Then open https://localhost:8181/ on your Android device.