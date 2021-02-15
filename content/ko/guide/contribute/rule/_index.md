---
title: "SK텔레콤 오픈소스 기여 Rule"
linkTitle: "기여 Rule"
weight: 11
type: docs
description: >
  SK텔레콤의 오픈소스 기여 Rule을 설명한다. 
---
SK텔레콤은 오픈소스 커뮤니티와의 협업의 가치를 존중하고, 이를 위해 구성원의 외부 오픈소스 프로젝트로의 기여를 장려한다. 하지만, SK텔레콤의 지식재산 보호와 의도치 않은 저작권 침해를 방지하기 위해 준수해야 할 몇가지 규칙이 있다. 

어느 것이라도 무언가 바람직하지 않아 보이는 상황이 있다면 주저하지 말고 OSPO에 문의하라. :[Support (opensource@sk.com)](https://tde.sktelecom.com/wiki/pages/viewpage.action?pageId=305680229)

## 승인을 받아라
오픈소스 기여는 저작권 관점에서 저작자가 저작물을 수정/사용/배포할 수 있는 권한을 오픈소스 프로젝트에 부여하는 것이다. 때에 따라서는 오픈소스 프로젝트에 여러분의 저작권을 양도해야 하기도 한다. 그런데 일반적으로 고용 기간에 만든 저작물의 저작권은 고용주가 소유한다. 즉, SK텔레콤 구성원이 만든 저작물은 SK텔레콤이 소유한다. 구성원이 임의로 저작물을 오픈소스에 기여하는 행위는 불필요한 저작권 침해 이슈를 유발시킬 수 있다. 

따라서, 기여하고자 하는 오픈소스 프로젝트가 있다면 SK텔레콤 오픈소스 기여 정책에 따라 최초 기여하기 전에 리뷰 요청 및 승인 절차를 따른다.

* [오픈소스 기여 절차](#오픈소스-기여-절차)

## 기여할 권리가 있는 코드만 기여하라
기여할 권리가 있는 코드만 기여하라. 즉, 직접 작성한 코드를 기여하라. 3rd party의 코드를 여러분이 임의로 기여해서는 안된다. 

## 지식 재산 노출에 주의하라
민감한 정보, 특허 등 기업의 지식재산 노출이 우려되는 코드, 문서 기여하지 마라. 

기여하려는 코드에 회사의 특허가 포함되어 있다면, 이 특허를 오픈소스 라이선스로 프로젝트에 기여해도 되는지 확인하라. 모호한 부분이 있다면 OSPO에 문의하라. 

## 수준 이하의 코드는 기여하지 마라
수준 이하의 코드는 기여하지 마라. 이는 기업의 평판에도 영향을 미칠 수 있다.

## CLA 서명에 주의하라
어떤 오픈소스 프로젝트는 모든 기여자에게 CLA (Contributor License Agreement)에 서명할 것을 요구한다. 이는 프로젝트가 여러 기여자의 저작물을 관리하면서 발생할 수 있는 저작권 분쟁을 줄이기 위해 기여자들에게 동의를 구하는 약정서이다. 보통 대기업이 주도하는 프로젝트에서 CLA에 서명할 것을 요구한다.

CLA는 프로젝트마다 다르지만 주로 다음 사항을 동의한다는 내용을 담고 있다.

~~~
- 나(또는 소속 기업)는 내가 기여하려고 하는 기여물을 프로젝트에 기여할 권리가 있다. (즉, 이 기여물의 저작자이다.)
- 나(또는 소속 기업)는 나의 기여물을 프로젝트가 수정, 배포, 관리할 수 있는 권한을 프로젝트에 부여한다.
- 나(또는 소속 기업)는 부여한 권한을 철회하지 않는다.
- 나(또는 소속 기업)는 프로젝트가 향후 필요에 따라 라이선스를 변경할 수 있는 권한을 프로젝트에 부여한다.
~~~

또한, 드문 경우지만, 어떤 CLA는 다음과 같은 조건에 대해서도 동의를 요구한다.

~~~
- 나(또는 소속 기업)는 나의 기여물을 기여함과 동시에 나의 저작권을 프로젝트 또는 프로젝트 관리 조직으로 양도한다.
~~~

SK텔레콤은 자사의 지식재산 보호를 위해 저작권 양도를 요구하는 오픈소스 프로젝트로의 기여는 허용하지 않는다. 이러한 판단을 위해 SK텔레콤의 구성원은 기여하려는 오픈소스 프로젝트에서 CLA 서명을 요구할 경우, 서명하기 전에 반드시 OSPO에 리뷰 요청을 하라. : 오픈소스 기여 절차

대부분의 CLA는 서명해도 문제가 되지 않기 때문에 승인 절차가 오래 걸리지 않다. 

## 저작권을 표시하라
구성원이 재직 기간에 생성한 저작물의 지식재산은 기본적으로 기업이 소유한다. 따라서, 구성원은 외부 오픈소스 프로젝트에 코드를 기여할 때 SK텔레콤의 저작권을 표기해야 한다.

하나 이상의 파일을 기여할 때, 다음과 같이 파일 상단에 저작권과 라이선스를 표기하라. 

~~~
Copyright 2021 SK TELECOM CO., LTD.
SPDX-License-Identifier: {$SPDX_license_name}
~~~

* 여기서 $SPDX_license_name은 해당 오픈소스 프로젝트의 라이선스 정책에 따라 작성한다.
* 단, 버그 수정 등의 목적으로 기존 코드를 수정하는 정도라면 해당 코드 수정에 대해 저작권을 표기할 필요는 없다. 
* 자세한 저작권 및 라이선스 표기 규칙은 다음 페이지를 참고하라. : [파일 내 저작권 및 라이선스 표시](/guide/release/process/copyright)

## 회사 이메일을 사용하라
오픈소스 프로젝트에 기여 시 개인 이메일을 사용하지 말고, SK텔레콤 이메일을 사용하라. 이를 통해 (1) 구성원은 회사를 대표하여 커뮤니티와 커뮤니케이션한다는 책임감을 갖게 되고, (2) SK텔레콤이 오픈소스 커뮤니티에 기여 활동을 활발히 하는 기업으로 인지도를 개선할 수 있다.

* GitHub에서 이메일 설정하는 방법은 다음 [Link](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/setting-your-commit-email-address)를 참고한다.