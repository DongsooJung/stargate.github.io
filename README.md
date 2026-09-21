# stargate.github.io — 통합됨 (Consolidated)

> ⚠️ **이 저장소는 통합 허브로 이전되었습니다.**
> 포털/프로젝트 콘텐츠는 **[dongsoojung.github.io](https://dongsoojung.github.io/)** 로 통합되었습니다.

## 현재 상태

| 경로 | 상태 |
|---|---|
| `/` (index.html) | 통합 허브로 리다이렉트 ✅ |
| `/decision.html` | 허브 `/decision/`로 이관 완료, 리다이렉트 ✅ |
| `/refund/` | 환불규정 — 법적 문서 단일 진본은 `stargate-main` 참고 (정리 예정) |

## 통합 계획

1. ~~index 리다이렉트~~ ✅ (2026-09-21)
2. ~~`decision.html` → 허브 이관 후 리다이렉트~~ ✅ (2026-09-21)
3. `refund/` → `stargate-main` 단일 진본으로 링크 교체
4. 완료 후 이 저장소 **아카이브** 예정

## 참고 — DECISION OS 이관 시 발견된 이슈

- AI SWOT 생성 기능이 브라우저에서 Anthropic API를 직접 호출하나 `x-api-key` 헤더가 없어 401 오류 발생. 서버 프록시(Supabase Edge Function 등)로 교체 필요. 이관본(허브 `/decision/index.html`) 주석에 기록됨.
