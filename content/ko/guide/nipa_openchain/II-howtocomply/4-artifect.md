---
title: "4. 컴플라이언스 산출물 생성 및 제공"
weight: 4
type: docs
---

## 4.1 컴플라이어스 산출물

OpenChain 규격 버전 2.1의 3.4.1항에서는 다음과 같이 컴플라이언스 산출물에 대한 요구사항과 입증 자료를 정의하고 있다.

{{% pageinfo %}}

### OpenChain 규격 버전 2.1
-----------

### 3.4.1 컴플라이언스 산출물

 배포 대상 소프트웨어에 대한 컴플라이언스 산출물을 생성하는 프로세스가 있어야 한다. 

#### 입증 자료:

 3.4.1.1 식별된 라이선스가 요구하는 대로 컴플라이언스 산출물 준비하고 이를 배포 대상 소프트웨어와 함께 배포하기 위한 프로세스를 설명하는 문서화된 절차  
 3.4.1.2 배포 대상 소프트웨어의 컴플라이언스 산출물 사본을 보관하기 위한 문서화된 절차 
  - 산출물 사본은 배포 대상 소프트웨어의 마지막 배포 이후 합리적인 기간 동안 혹은 식별된 라이센스가 요구하는 기간 동안 보관해야 한다(둘 중 더 긴 쪽을 따름). 
  - 이러한 절차가 올바르게 지켜졌음을 입증하는 기록을 남겨야 한다.

----------------

### 3.4.1 Compliance Artifacts

A process exists for creating the set of Compliance Artifacts for the Supplied Software.

#### Verification Materials(s):

 3.4.1.1 A documented procedure that describes the process under which the Compliance Artifacts are prepared and distributed with the Supplied Software as required by the Identified Licenses.   
 3.4.1.2 A documented procedure for archiving copies of the Compliance Artifacts of the Supplied Software - where the archive is planned to exist for a reasonable period of time since the last offer of the Supplied Software; or as required by the Identified Licenses (whichever is longer). Records exist that demonstrate the procedure has been properly followed.

{{% /pageinfo %}}

앞 장에서 오픈소스 컴플라이언스 활동의 가장 기본은 배포 대상 소프트웨어에 포함된 오픈소스 현황을 파악하는 것이라고 하였다. 이는 바로 오픈소스 컴플라이언스의 핵심인 오픈소스 라이선스 요구사항을 올바르게 충족하기 위해서이다. 즉, 배포 대상 소프트웨어에 포함된 오픈소스에 대한 컴플라이언스 산출물 세트를 생성하는 프로세스가 구축되어야 한다.

컴플라이언스 산출물은 크게 두 가지로 구분된다.

1. 오픈소스 고지문 : 오픈소스 라이선스 전문과 저작권 정보 제공을 위한 문서
2. 공개할 소스코드 패키지 : GPL, LGPL 등 소스 코드 공개를 요구하는 오픈소스 라이선스 의무 이행을 위해 공개할 소스코드를 취합한 패키지

컴플라이언스 산출물은 배포 대상 소프트웨어를 배포할 때 함께 제공해야 한다. “[[부록 02] 샘플 오픈소스 컴플라이언스 프로세스](../../appendix/2-process-template/)”의 고지, 확인, 배포 단계를 통해 컴플라이언스 산출물을 생성하여 배포한다.

배포 대상 소프트웨어를 배포 시, 공개할 소스코드 패키지를 동봉하는 것이 곤란할 경우, 최소 3년간 소스코드를 제공하겠다는 서면 약정서(Written Offer)를 제공하는 것으로 대신할 수 있다. 일반적으로 서면 약정서는 제품의 사용자 매뉴얼을 통해 제공하며, 예시는 다음과 같다.

> The software included in this product contains copyrighted software that is licensed under the GPL. A copy of that license is included in this document on page X. You may obtain the complete Corresponding Source code from us for a period of three years after our last shipment of this product, which will be no earlier than 2011-08- 01, by sending a money order or check for $5 to:
>
> GPL Compliance Division  
> Our Company  
> Any Town, US 99999  
>   
> Please write“source for product Y” in the memo line of your payment.  
> You may also find a copy of the source at http://www.example.com/sources/Y/.  
> This offer is valid to anyone in receipt of this information.

_<center>< [https://www.softwarefreedom.org/resources/2014/SFLC-Guide_to_GPL_Compliance_2d_ed.html](https://www.softwarefreedom.org/resources/2014/SFLC-Guide_to_GPL_Compliance_2d_ed.html#appendix-1-offer-of-source-code) ></center>_

따라서, 컴플라이언스 산출물은 3년 이상 보관해야 하며 이를 위한 프로세스가 구축되어야 한다. 일부 기업은 자체적인 웹사이트(예: http://opensource.lge.com/) 구축하여 외부 고객들이 배포 대상 소프트웨어에 대한 오픈소스 고지문과 공개할 소스코드 패키지를 언제든지 다운받을 수 있도록 편의를 제공한다.

