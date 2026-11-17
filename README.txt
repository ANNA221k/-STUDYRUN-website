STUDYRUN website — GitHub Pages ready

Files:
index.html — landing page
style.css — responsive design
script.js — JA/EN/PT translations and App Store URL
support.html — support page (complete contact information before publishing)
privacy.html — DRAFT CHECKLIST ONLY (replace with accurate, complete privacy policy before publishing)
assets/ — app screenshots

Before publishing:
1. In script.js, replace const APP_STORE_URL='' with your actual https://apps.apple.com/app/id... URL.
2. In support.html, add a working support contact method.
3. Replace privacy.html checklist with an accurate policy describing actual data collection, Firebase, ads, account data, retention, deletion, etc. and translate it into all three languages.
4. Replace illustrative budget panel with a real app screenshot if available.
5. Verify all claims match the shipped app, and check privacy/security and user consent.

GitHub Pages:
1. Create a PUBLIC GitHub repository, e.g. studyrun-site.
2. Upload the CONTENTS of this folder (index.html at repository root), commit.
3. Open Settings > Pages > Build and deployment > Deploy from a branch.
4. Select main branch, /(root), Save.
5. Wait for deployment; URL usually https://YOUR_USERNAME.github.io/studyrun-site/
6. Support: .../support.html; Privacy: .../privacy.html

更新：support.html と privacy.html は既存公開サイトの内容を基に再構成し、legal.js と legal-translations.js で3言語表示します。公開前に現在の実装との整合性を確認してください。特に広告（AdMob）の使用有無、Firebase/Agoraの取扱い、削除手順などを要確認。
