VECHOLA APK — CLOUD BUILD PACKAGE

Is ZIP mein Vechola app aur GitHub Actions workflow hai. Android Studio ki zaroorat nahi.
Lekin APK ko GitHub ke cloud computer par build karne ke liye GitHub account aur ek dafa upload/click karna hoga.

STEP 1
GitHub.com par free account banao ya login karo.

STEP 2
New repository banao. Naam: vechola-app
Repository ko Public rakhna easiest hai (private repo bhi kaam kar sakti hai).

STEP 3
Is ZIP ko extract karo. Iske andar ki tamam files/folders (including .github folder) GitHub repository mein upload karo.
GitHub website par Add file > Upload files use kar sakti ho. Hidden .github folder bhi upload hona chahiye.

STEP 4
Repository ke Actions tab mein jao.
"Build Vechola Android APK" workflow select karo.
"Run workflow" par click karo.

STEP 5
Build complete hone par workflow run ke neeche Artifacts mein "Vechola-debug-apk" download karo.
ZIP artifact extract karo. Andar app-debug.apk hogi. Use Android phone mein bhej kar install karo.
Phone par install prompt aaye to browser/files app ke liye "Install unknown apps" allow karna par sakta hai.

IMPORTANT
- Yeh debug APK hai, personal testing ke liye. Public Play Store release ke liye signed release build aur secure signing key chahiye.
- App ka profile data is waqt sirf usi device/browser ke local storage mein rehta hai. Doosre users ke phones par sync nahi hota.
- Demo profiles fictional hain. Real rishta service ke liye secure online backend, proper login, privacy controls, consent, moderation aur staff permissions banana zaroori hai.
- Is prototype mein sample profile search, filters, favourites, local profile creation/editing aur JSON backup shamil hain.
