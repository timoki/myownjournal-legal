# 나만의 일기장 — 약관 및 정책

앱에서 보여 주는 개인정보 처리방침과 서비스 이용약관을 그대로 웹에 올린 것입니다.

- 개인정보 처리방침 — https://timoki.github.io/myownjournal-legal/privacy.html
- 서비스 이용약관 — https://timoki.github.io/myownjournal-legal/terms.html

## ⚠️ 이 저장소의 HTML 을 손으로 고치지 마세요

원본은 앱 저장소의 `lib/features/settings/presentation/legal/legal_texts.dart` 하나입니다.
여기 파일은 거기서 **생성**된 것이고, 손으로 고치면 앱 안 문서와 어긋납니다.
실제로 그렇게 어긋난 적이 있어서 이렇게 바꿨습니다.

고칠 때는 앱 저장소에서:

```bash
bash tool/publish_legal_docs.sh
```

앱 저장소의 `test/legal_docs_html_test.dart` 가 두 쪽이 어긋나면 실패시킵니다.
