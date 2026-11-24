# banttas-digital-runtime

banttas-digital AI 받아쓰기의 **런타임 팩**(임베디드 Python + torch, cuda/cpu 판)을 Releases 로 배포한다.

- 태그 = `packVersion`. 조각(`runtime-<variant>-<packVersion>.zip.NNN`)을 이어 붙이면 ZIP 하나다.
- 만드는 곳: `whlee21/banttas-digital` 의 `.github/workflows/runtime-pack.yml` (`sidecar/asr/pack/build.ps1`).
- 앱은 자기 `manifest.json` 에 적힌 크기·sha256 으로만 받는다.
- 구성요소의 라이선스 전문과 소스 위치는 팩 안의 `licenses/` 에 있다.
