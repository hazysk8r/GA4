# GA4 Key Events 

## 📋 Key Events란?

**Key Events(핵심 이벤트)**는 GA4에서 비즈니스에 중요한 사용자 행동을 표시하는 이벤트로, 전환(Conversion)을 추적하고 측정하는 도구. 
- 사업체에 중요한 것들만 선택해서 측정하고, 이를 활용해서 더 효율적인 비즈니스 결정을 내릴 수 있게 도와줌.

## 🎯 주요 특징

### 자동 수집 vs 수동 설정
```markdown
🔄 자동 Key Events:
- first_open 
- purchase 
- in_app_purchase 
- app_store_subscription_convert 

⚙️ 수동 Key Events:
- form_submit 
- video_complete 
- download 
- newsletter_signup 
```

### Key Events의 장점
- **의사결정 정확도 향상**: 데이터 기반으로 정확한 판단이 가능
- **마케팅 ROI 최적화**: 가장 가치 있는 channel에 예산 집중
- **비즈니스 Process 개선**: 구체적 병목 지점 발견 및 해결
---

### 주된 활용점
- **사업체 성공에 중요한 action을 어떻게 측정할 수 있을지?**: 예시로 무료체험 → 유료 전환율 측정.
- **구매 event로 이어지는 action들은 무엇인지?**: Form 제출 혹은 pdf 다운로드가 구매 혹은 가입에 어떤 영향을 주는가.
- **소셜 포스트가 핵심 이벤트 유도에 효과적인가?**: Instagram 광고가 Facebook 광고보다 가입 전환율이 더 높다면 Instagram에 집중.

## 🛠️ 설정 방법

### 1. 기존 이벤트를 Key Event로 전환

#### 설정 경로
```markdown
📍 GA4 설정 경로:
관리(Admin) → 구성(Configure) → 이벤트(Events) → "핵심 이벤트로 표시" 토글 ON
```

#### 설정 조건
```markdown
✅ Key Event 전환 조건:
- 지난 30일간 최소 1회 발생한 이벤트
- 최대 30개
