ANANDA ANDROID APP — SHORTEST ROUTE

This is the fastest version: the ANANDA website runs locally inside an Android WebView.
No server or AI service is required.

FEATURES
- ANANDA natural green/cream/gold branding
- Mobile-friendly website
- Herbal Shop section
- Consultation button opens WhatsApp
- Call button opens phone dialer
- Mobile bottom navigation
- ANANDA app icon
- Works offline for the website content

BUILD
1. Extract this ZIP.
2. Open the ANANDA_Android_App folder in Android Studio.
3. Wait for Gradle Sync.
4. Press Run to install on the phone.
5. To create an APK: Build > Build APK(s).

IMPORTANT
The WhatsApp/call number is currently +254 700 123 456, taken from the website mock-up.
Change it in index.html and MainActivity only if you want a different business number.


GITHUB ACTIONS APK BUILD — SHORTEST ROUTE

This project already includes:
.github/workflows/build-apk.yml

HOW TO BUILD THE APK ON GITHUB:
1. Extract this ZIP.
2. Create a new repository on GitHub.
3. Upload ALL the files and folders inside this project folder.
   Important: .github must be uploaded too.
4. Open your repository and tap Actions.
5. Select "Build ANANDA APK".
6. Tap "Run workflow".
7. Wait for the build to finish.
8. Open the completed workflow run.
9. Download the artifact called "ANANDA-APK".
10. Inside it is app-debug.apk.

The first build may take several minutes.
