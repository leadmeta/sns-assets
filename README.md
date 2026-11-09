# LEADMETA SNS Assets

SNS 카드 이미지 공개 호스팅용 저장소입니다. Pinterest·Instagram API는 파일 업로드를 받지 않고 **공개 이미지 URL**만 받기 때문에 사용합니다.

- `cards/<날짜>/` — 계정별 카드 PNG (1000x1500 또는 1080x1350)
- 생성: `node pipeline/make_pin_card.mjs --spec content/pins_<날짜>.json --out assets-repo/cards/<날짜>`
- 이미지에 포함된 텍스트는 리드메타 콘텐츠이며, 재사용을 허용하지 않습니다.
