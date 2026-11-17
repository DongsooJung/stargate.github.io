# stargate.github.io — 통합 완료 (아카이브 대기)

> ⚠️ **이 저장소의 모든 콘텐츠가 통합 허브로 이전되었습니다.**
> 포털/프로젝트 콘텐츠는 **[dongsoojung.github.io](https://dongsoojung.github.io/)** (운영 도메인: stargateedu.co.kr)가 단일 진본입니다.

## 최종 상태

| 경로 | 상태 |
|---|---|
| `/` (index.html) | 통합 허브로 리다이렉트 ✅ |
| `/decision.html` | 허브 `/decision/`로 이관 완료, 리다이렉트 ✅ |
| `/refund/` | 허브 `/refund/`로 이관 완료, 리다이렉트 ✅ (2026-11-17) |
| `/refund/tutoring.html` | 허브 `/refund/tutoring.html`로 이관 완료, 리다이렉트 ✅ (2026-11-17) |

## 통합 계획 진행

1. ~~index 리다이렉트~~ ✅ (2026-09-21)
2. ~~`decision.html` → 허브 이관 후 리다이렉트~~ ✅ (2026-09-21)
3. ~~`refund/` → 허브 이관 후 리다이렉트~~ ✅ (2026-11-17, 과외 환불규정 원본 포함)
4. **이 저장소 아카이브 가능** — 레포 정리 프로젝트 트래킹: DongsooJung/dongsoojung.github.io#293

## 참고 — DECISION OS 이관 시 발견된 이슈

- AI SWOT 생성 기능이 브라우저에서 Anthropic API를 직접 호출하나 `x-api-key` 헤더가 없어 401 오류 발생. 서버 프록시(Supabase Edge Function 등)로 교체 필요. 이관본(허브 `/decision/index.html`) 주석에 기록됨.
