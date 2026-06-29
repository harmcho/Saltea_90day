---
title: 실사형 이미지 제작 환경
---

# 실사형 이미지 제작 환경

솔티탭 인스타그램 콘텐츠 품질을 높이기 위해, 단순 배경색/선그림 방식이 아니라 **실사형 라이프스타일 이미지 + 한글 텍스트 후합성** 방식으로 전환합니다.

## 목표

```text
AI 실사 배경 생성
↓
개똥이 한글 문구 합성
↓
카드뉴스 1080x1350 제작
↓
컨펌
↓
인스타그램 업로드
```

## 왜 필요한가

기존 단순 카드 방식은 다음 한계가 있었습니다.

- 배경이 단순함
- 러너 상황이 약함
- 사람 표현이 아이콘처럼 보임
- 브랜드 콘텐츠보다 테스트 이미지처럼 보임

따라서 앞으로는 다음 기준으로 제작합니다.

| 기준 | 방향 |
|---|---|
| 배경 | 새벽 러닝/퇴근 후 러닝 등 실제 장면 느낌 |
| 사람 | 얼굴 없는 실루엣/부분 컷 |
| 제품 없음 | 라이프스타일 상황으로 공감 유도 |
| 문구 | AI 이미지에 직접 넣지 않고 후합성 |
| 크기 | 1080x1350 |

## 필요한 환경

Hermes의 이미지 생성 도구는 FAL.ai 기반으로 사용할 수 있습니다.

필요값:

```text
FAL_KEY
```

보안상 공개 사이트에는 API 키를 기록하지 않습니다.

## 실사형 러너 배경 프롬프트 예시

```text
Photorealistic lifestyle photo of a Korean office worker runner jogging along the Seoul Han River at blue hour before sunrise, city skyline in the distance, cool navy and mint color mood, face not visible, premium wellness brand atmosphere, vertical 4:5 composition, large clean negative space for Korean headline, no text, no logo, no product, realistic lighting, high-end editorial photography
```

## 제작 원칙

- AI 생성 이미지는 텍스트 없는 배경만 생성
- 한글 문구는 개똥이가 별도 합성
- 의료적 효능 표현 금지
- “전해질 보충 보장” 같은 단정 표현 금지
- A타겟은 “땀을 많이 흘리는 날, 물과 함께 챙기는 루틴” 중심
- B타겟은 “아침 물 한 잔 옆 10초 소금차 루틴” 중심
