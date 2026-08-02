# PICKAI 정책 페이지 연결 방법

1. 모든 HTML에서 아래 두 문구를 실제 정보로 변경
- YOUR_SUPPORT_EMAIL@example.com
- 운영자명 또는 사업자명 입력

2. GitHub 저장소 `moa-privacy`의 루트에 파일 업로드

3. GitHub → Settings → Pages
- Source: Deploy from a branch
- Branch: main
- Folder: /(root)
- Save

4. 공개 주소
- https://uyh11225.github.io/moa-privacy/privacy-policy.html
- https://uyh11225.github.io/moa-privacy/terms.html
- https://uyh11225.github.io/moa-privacy/account-deletion.html
- https://uyh11225.github.io/moa-privacy/contact.html

5. 앱 연결용 Cursor AI 요청문

PICKAI의 MY 또는 설정 화면에서 아래 공개 페이지를 연결해줘.
개인정보처리방침: https://uyh11225.github.io/moa-privacy/privacy-policy.html
이용약관: https://uyh11225.github.io/moa-privacy/terms.html
계정 삭제 안내: https://uyh11225.github.io/moa-privacy/account-deletion.html
문의하기: https://uyh11225.github.io/moa-privacy/contact.html

expo-web-browser의 WebBrowser.openBrowserAsync 또는 Linking.openURL을 사용하고,
열기 실패 시 알림을 표시해.
기존 디자인과 다른 기능은 변경하지 말고 Git diff를 보여준 뒤 멈춰.

6. Play Console
- 개인정보처리방침 URL: privacy-policy.html
- 계정 삭제 URL: account-deletion.html
