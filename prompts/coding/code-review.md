# 코드 리뷰 요청 (Code Review Request)

## 설명 (Description)
코드의 품질, 버그, 개선 사항을 검토하기 위한 프롬프트입니다.

A prompt for reviewing code quality, bugs, and improvements.

## 카테고리 (Category)
- 분류: 코딩 (Coding)
- 난이도: 중급
- 용도: 코드 품질 향상 및 버그 탐지

## 프롬프트 내용 (Prompt Content)
```
다음 코드를 리뷰해주세요. 특히 다음 사항들을 중점적으로 확인해주세요:

1. 코드의 가독성과 유지보수성
2. 잠재적인 버그나 에러 처리
3. 성능 최적화 가능성
4. 보안 취약점
5. 모범 사례 준수 여부

[여기에 코드를 붙여넣으세요]

각 항목에 대해 구체적인 피드백과 개선 제안을 제공해주세요.
```

## 사용 예시 (Usage Example)
```python
# 예시 코드
def calculate_total(items):
    total = 0
    for item in items:
        total = total + item['price']
    return total
```

위 코드와 함께 프롬프트를 사용하여 리뷰를 요청할 수 있습니다.

## 기대 결과 (Expected Output)
- 코드의 강점과 약점 분석
- 구체적인 개선 제안
- 버그나 보안 취약점 지적
- 리팩토링된 코드 예시

## 활용 팁 (Tips)
- 코드의 컨텍스트를 함께 제공하면 더 정확한 리뷰를 받을 수 있습니다
- 특정 언어나 프레임워크를 명시하면 더 전문적인 피드백을 받을 수 있습니다
- 리뷰 우선순위를 지정하면 중요한 부분에 집중할 수 있습니다

## 태그 (Tags)
#코딩 #코드리뷰 #품질관리 #버그탐지 #리팩토링
