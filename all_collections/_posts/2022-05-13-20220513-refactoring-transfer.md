---
layout: post
title: 송금 기능 리팩토링 및 테스트 코드 작성
date: 2022-04-26 01:01:01
categories: [리팩토링, 테스트코드]
project: STEPS
---

STEPS 4.0 송금 기능 한도 체크 쪽 이슈가 생겼다.

STEPS 4.0 오픈 전 송금 기능 QA 이슈들 수정하면서 코드가 꽤 어지러운 상황이였는데,  
이번 이슈를 수정하면서 리팩토링하였고, 한도 체크, 인증 로직 부분이 꽤 많이 변경되었다.  
이 부분은 송금액과 보안매체 여부 등등에 따라 굉장히 복잡하게 여러가지 케이스로 분기되어서  
원래 없었던 테스트 코드도 이참에 작성하여 테스트했다. 그리고 정상 이행했다.

테스트 코드 작성 생활화하자.
