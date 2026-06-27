# 솔티탭 90일 여정 공개 사이트

Quartz v4 + GitHub Pages로 공개할 솔티탭 90일 여정 사이트입니다.

## 내부/공개 분리 원칙

- 내부 ObsidianVault: 전체 회의록, KPI, 민감자료 보관
- 이 Quartz 사이트: 외부 공개 가능한 요약 기록만 게시

## 로컬 빌드

```bash
cd /root/saltea-90days-public-v4
npx quartz build
```

## GitHub Pages 공개

1. GitHub에 `saltea-90days` 저장소 생성
2. 이 폴더를 push
3. Settings → Pages → GitHub Actions로 공개
