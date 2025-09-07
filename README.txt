iOS OTA Installer Package

Usage:
1. Replace manifest.plist values:
   - bundle-identifier (com.example.myapp)
   - bundle-version (1.0.0)
   - title (My App)
   - URLs (point them to your HTTPS server path for .ipa and icon)

2. Put your signed .ipa file in the same folder as manifest.plist.

3. Upload everything (index.html, manifest.plist, .ipa, icon) to your HTTPS server.

4. Open index.html in Safari on your device, tap Install.
