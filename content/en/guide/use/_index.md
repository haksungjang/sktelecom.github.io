---
title: "오픈소스 사용하기"
linkTitle: "사용하기"
weight: 10
type: docs
description: >
  오픈소스 올바르게 사용하기
---

오픈소스를 사용하지 않고 제품이나 서비스를 개발하는 것은 불가능하다고 할 수 있을 만큼 소프트웨어 개발에 오픈소스는 핵심 요소가 되었다. 오픈소스의 사용으로 소프트웨어 개발 시간을 단축하면서도 서비스 안정성 및 보안 강화를 기대할 수 있다. 하지만, 오픈소스를 사용할 때는 라이선스가 무엇인지 확인하고, 라이선스가 요구하는 의무사항을 준수해야 한다.

여기에서는 SK텔레콤의 개발자와 개발 조직이 소프트웨어를 개발하면서 오픈소스를 올바르게 사용하기 위한 가이드를 제공한다.

## 사용할 오픈소스 선택 시 고려사항

필요한 기능을 구현하기 위해 오픈소스를 사용하기로 했다면 유사한 기능을 제공하는 여러 오픈소스 프로젝트 중 어느 오픈소스를 선택하는게 좋을까? 여러 측면의 고려해야 할 포인트를 알아보자. 

* [오픈소스 선택 시 고려사항](/guide/use/choose)

## 오픈소스 컴플라이언스 활동
기업이 오픈소스를 사용하여 제품/서비스를 개발할 때 법적인 문제를 발생시키지 않으려면 오픈소스 라이선스를 확인하고, 각 라이선스가 요구하는 바를 준수해야 한다. 이러한 활동을 오픈소스 컴플라이언스라고 한다. SK텔레콤 구성원은 오픈소스를 사용하면서 적절한 컴플라이언스 활동을 수행해야 한다. 

### 오픈소스 라이선스란? 
오픈소스를 올바르게 사용하기 위해서는 먼저 저작권 및 오픈소스 라이선스에 대해 이해해야 한다.

* 소프트웨어는 저작권에 의해 보호된다. 소프트웨어를 개발하면 저작권법에 의해 저작권자를 제외한 누구도 그 소프트웨어를 사용, 복제, 수정 및 배포할 수 없다.
* 오픈소스의 목적은 많은 사람들이 자유롭게 사용, 수정하고 배포도 할 수 있게 하는 것이다. 이를 위해서는 이러한 권한을 명시적으로 나타내는 라이선스가 필요하다. 이를 오픈소스 라이선스라고 하며, 오픈소스 라이선스가 적용되지 않은 소프트웨어는 오픈소스가 아니다. 오픈소스가 아니라면 저작권자를 제외한 누구도 그 소프트웨어를 사용, 복제, 수정 및 배포할 수 없다.

오픈소스 라이선스에 대한 자세한 사항은 다음 페이지를 참고하라.
* [오픈소스 라이선스 란?](/guide/use/license)

### 라이선스 확인하기
여러가지 방법으로 오픈소스 라이선스를 확인할 수 있다. 분석도구를 사용하지 않고도 확인할 수 있다.  
사용하려는 오픈소스의 라이선스를 확인하는 방법은 다음 페이지를 참고하라. 
* [오픈소스 라이선스 확인하기](/guide/use/check)

### 라이선스 별 의무 사항
SK텔레콤은 제품/서비스 개발 시 오픈소스의 사용을 적극 권장한다. 하지만, SK텔레콤의 지식재산 보호를 위해 오픈소스 라이선스 별로 요구하는 의무 사항을 준수해야 한다. SK텔레콤의 구성원은 이를 숙지하여 오픈소스 사용 시 라이선스를 확인하고 의무 사항 준수를 위한 활동을 해야 한다. 다음 페이지에서 어떤 오픈소스 라이선스를 주의해야 할지에 대해 확인하라. 
* [오픈소스 라이선스 별 의무사항](/guide/use/obligation)

### 라이선스 의무 준수 활동
SK텔레콤의 제품/서비스에 오픈소스를 포함하여 배포할 경우, 각 오픈소스 라이선스가 요구하는 사항을 준수해야 한다. 오픈소스 라이선스에 따라 고지 의무만 요구하기도 하고, 소스 코드 공개까지 요구하기도 한다.

* 고지 의무 : 기본적으로 대부분의 오픈소스 라이선스가 요구하는 "저작권 표시", "라이선스 고지" 등의 고지 의무를 준수해야 한다. 예를 들어, SK텔레콤이 배포하는 모바일 애플리케이션은 요구되는 고지 사항을 "About" 페이지를 통해 제공할 수 있다.
* 소스 공개 의무 : 소스 코드 공개 의무를 요구하는 Copyleft 라이선스 하의 오픈소스를 포함하는 소프트웨어를 배포할 경우, 사용자에게 소스 코드를 직접 제공하거나, 사용자가 요청 시 소스 코드를 제공하겠다는 서면 약정서를 제공해야 한다.

이와 같이 오픈소스 라이선스 의무사항을 준수하여 법적 리스크를 최소화하는 활동을 오픈소스 컴플라이언스라고 한다.

{{% alert title="오픈소스 고지문 요청" color="warning" %}}
SK텔레콤 개발조직에서 고지 등 오픈소스 컴플라이언스 활동을 위해서는 개발 프로세스의 분석/설계 완료 단계에서 사용할 오픈소스 확정 후 ITGO를 통하여 점검을 요청한다. 

* http://link-removed 

담당 부서 (준법법무경영 그룹 IPR팀)에서 점검 후 고지를 위한 오픈소스 고지문을 발급한다. 

{{% /alert %}}

## 오픈소스 보안취약점 점검 활동
### 자가 점검
#### CVE 확인
[CVE](https://cve.mitre.org/index.html)는 알려진 오픈소스 보안 취약점을 데이터베이스화하여 제공한다. 사용하려는 오픈소스를 CVE에서 검색하여 알려진 보안 취약점이 있는지 확인할 수 있다. 

#### GitHub 확인
대표적인 오픈소스 저장소인 GitHub은 Public Reporitory에서 취약한 Dependency를 감지하고 [Dependabot](https://docs.github.com/en/github/managing-security-vulnerabilities/about-alerts-for-vulnerable-dependencies#dependabot-alerts-for-vulnerable-dependencies) 경고를 생성한다. 

### 보안취약점 진단 요청
SK텔레콤은 오픈소스 보안취약점 진단을 위한 도구를 운영한다. 담당부서(정보보호담당)에 진단을 요청할 수 있다. 
* [오픈소스 보안취약점 진단 요청](http://link-removed/)

## SK텔레콤 오픈소스 정책
SK텔레콤 오픈소스 정책 및 부서별  R&R과 검증 프로세스는 다음 페이지를 참고한다.
* [오픈소스 점검 프로세스 (사내한)](https://link-removed/)


---

{{% alert title="문의" color="success" %}}
오픈소스 사용 시 문의/요청은 OSPO에 연락하라: [Support (opensource@sk.com)](https://link-removed/)
{{% /alert %}}