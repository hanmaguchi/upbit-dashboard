# upbit-tools 대시보드 리뉴얼 시안

Claude Design 캔버스에서 내보낸 원본 (데이터 2026-11-19 01:45 KST 스냅샷).

- `canvas.json` — 아트보드 배치·제목 인덱스
- `Main.dc.html` — A안 · 브리핑
- `Console.dc.html` — 확정안 · 지금 시장 (데스크톱)
- `Mobile.dc.html` — 확정안 · 모바일 지금 시장 (390px)
- `Positions` / `Sprout` / `Signals` / `Research` / `Futures` / `Calculator` — 확정안 나머지 탭

`.dc.html`은 Design 런타임(`support.js`)에서 렌더링되는 소스라 브라우저에서 단독으로 열리지 않음. 구현 참고용.
