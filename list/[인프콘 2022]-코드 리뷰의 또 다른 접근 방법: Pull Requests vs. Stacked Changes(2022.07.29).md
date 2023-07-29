# [인프콘 2022]-코드 리뷰의 또 다른 접근 방법: Pull Requests vs Stacked Changes

## 좋은 코드 리뷰란?

- 적당한 크기의 코드 변경
- 작업의 명확성
- 빠른 리뷰 속도

---

<br/>

## PR 관점에서의 코드 리뷰

- 작업 과정 속에서 많은 고민들과 커밋이 존재

- 결론적으로는, 리뷰어 입장에서 `File changes` 에만 집중

- `File changes` 가 커짐으로써 리뷰 부담감 증대, 코드 리뷰 속도 저하, conflict 가능성 증대 => 의욕 저하

---

<br/>

## Stack Changes 관점에서의 코드 리뷰

- 커밋 기준, 작은 단위로 적은 코드 변경 내역을 stack을 쌓아 올라가면서 확인 (Stack diff)

- 좋은 코드 리뷰에 해당하는 조건들이 충족

---

<br/>

## Graphite를 통한 Stack changes 확인 및 리뷰

<div align="center">
  <img width="600" alt="image" src="https://github.com/J-Ymini/J-Ymini/assets/75535651/106c5c48-1a77-4365-a951-510caf746e54"></div>

- Stack Diff를 통해 단순 작업자의 결과 공유를 넘어서 작업자의 고민 및 의식의 흐름까지 공유

---

<br/>

## 결론

- 팀 단위에서 어떤 점을 좀더 중요시 하느냐에 따라 PR or Stack Changes 선택

- 가장 중요한 것은 함께, 공감하며 협업하는 것

---
