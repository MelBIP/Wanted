# Wanted 프리온보딩 챌린지 iOS 사전 과제

# 성적관리프로그램

## 프로젝트 이름

- MyCreditManager

## 사용언어 / 환경

- Swift
- Xcode 기본 템플릿 중 [MacOS - Command Line Tool]

## 프로그램의 메뉴

- 학생추가
- 학생삭제
- 성적추가(변경)
- 성적삭제
- 평점보기
- 종료

## 프로그램 동작조건

- 사용자가 종료 메뉴를 선택하기 전까지는 계속해서 사용자의 입력을 받습니다
- 메뉴선택을 포함한 모든 입력은 숫자 또는 영문으로 받습니다

## 성적별 점수

- A+ (4.5점) / A (4점)
- B+ (3.5점) / B (3점)
- C+ (2.5점) / C (2점)
- D+ (1.5점) / D (1점)
- F (0점)

## 평점

- 각 과목의 점수 총 합 / 과목 수
- 최대 소수점 2번째 자리까지 출력
    - 예)
        - 3.75
        - 4.1
        - 2

## 프로그램 동작모습

`예시 화면의 굵은 글씨는 콘솔 출력 내용이며, 얇은 글씨는 콘솔을 통한 입력 내용입니다.`

### 메뉴의 잘못된 입력 처리

![스크린샷 2023-04-25 오후 5.27.55.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5b3c4a7b-f208-42ce-ae5f-4b82f4301c77/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-04-25_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_5.27.55.png)

### 학생 추가

- 메뉴를 선택한 후에도 잘못 입력한 것이 있으면 처리해 주어야합니다
- 이미 존재하는 학생은 다시 추가하지 않습니다

![스크린샷 2023-04-25 오후 5.28.33.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6239420b-f77a-438e-92d7-0d8997982bfc/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-04-25_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_5.28.33.png)

### 학생삭제

- 메뉴를 선택한 후에도 잘못 입력한 것이 있으면 처리해 주어야합니다
- 없는 학생은 삭제하지 않습니다

![스크린샷 2023-04-25 오후 5.29.18.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fceef533-ff3e-4a51-b309-cbad68dff3fc/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-04-25_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_5.29.18.png)

### 성적추가

- 메뉴를 선택한 후에도 잘못 입력한 것이 있으면 처리해 주어야합니다
- 없는 학생의 성적은 추가하지 않습니다

![스크린샷 2023-04-25 오후 5.30.11.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7db00c2a-0b03-4871-8c78-a67a86e5825e/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-04-25_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_5.30.11.png)

![스크린샷 2023-04-25 오후 5.30.27.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/105559b7-134a-4c61-abe3-3c0df47d8098/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-04-25_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_5.30.27.png)

### 성적삭제

- 메뉴를 선택한 후에도 잘못 입력한 것이 있으면 처리해 주어야합니다
- 없는 학생의 성적은 삭제하지 않습니다

![스크린샷 2023-04-25 오후 5.31.22.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c1236261-5fc1-400d-b207-bab8d050eba8/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-04-25_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_5.31.22.png)

### 평점보기

- 메뉴를 선택한 후에도 잘못 입력한 것이 있으면 처리해 주어야합니다
- 해당 학생의 과목과 성적을 모두 출력한 후 마지막 줄에 평점을 출력합니다
- 없는 학생은 평점을 보여주지 않습니다

![스크린샷 2023-04-25 오후 5.42.41.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ef484364-01cd-4455-b5e0-c77bf114264e/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-04-25_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_5.42.41.png)

### 종료

- 프로그램을 종료합니다

![스크린샷 2023-04-25 오후 5.43.13.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4ec11900-ca4b-4e03-81e7-525c18ea2bde/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-04-25_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_5.43.13.png)

---

## Coding 💻

![옵셔널을 벗겨야지 제대로 된 값이 나옴](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fa304edd-eb0e-4d55-880a-a91ede9e3219/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-04-25_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_5.46.15.png)

옵셔널을 벗겨야지 제대로 된 값이 나옴

```swift
import Foundation

let answer = readLine()!

print("원하는 기능을 입력해주세요")
print("1: 학생추가, 2: 학생삭제, 3: 성적추가(변경), 4: 성적삭제, 5: 평점보기, X: 종료")

print(answer)
```

![이런 식으로](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c52766fa-48e6-41c1-bcb4-2c9e1a8de5f0/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-04-25_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_5.47.04.png)

이런 식으로

![옵셔널을 벗기지 않고 그대로 출력하게 되면](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/19897808-7512-4dcd-ac10-acd61a5ad8db/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-04-25_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_5.47.57.png)

옵셔널을 벗기지 않고 그대로 출력하게 되면

![경고가 뜸](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1f3352d2-8814-444d-b5bb-834582a9ca94/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-04-25_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_5.48.38.png)

경고가 뜸

### 사용자가 종료 메뉴를 선택하기 전까지는 계속해서 사용자의 입력을 받습니다

![while문을 사용하여 무한루프 돌려줌](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c00be44b-eb96-484a-a446-2b5361790448/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-04-25_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_5.55.37.png)

while문을 사용하여 무한루프 돌려줌

### 잘못된 입력처리

![스크린샷 2023-04-25 오후 6.05.21.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1df7118c-7c58-4945-a233-d9a1e60dbbe4/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-04-25_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_6.05.21.png)

switch-case문으로 하려 했는데 잘 안 되는 거 같기 때문에 그냥 if문으로 두겠음

### 학생추가
