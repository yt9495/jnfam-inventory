# JNFAM 재고 현황 시스템 (Inventory Status)

- 주소: https://yt9495.github.io/jnfam-inventory/
- 단일 파일 웹앱 (`index.html`) · Firebase(jnfam-ledger 프로젝트, 수불부와 공유) · Google 계정 로그인
- Firestore 컬렉션: `inv_products`, `inv_lots`, `inv_usage`, `inv_isos`, `inv_snapshots`
- 수불부 연동: `inbound` 컬렉션의 미착품/선적예정을 입고 예정으로 표시, 입고 등록 시 미착품→상품 전환
- DEMO 모드: `?demo=1` (저장 안 됨)
