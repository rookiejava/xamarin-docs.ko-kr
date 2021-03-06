---
title: Xcode 프로젝트를 사용 하 여 실제 예제
description: 이 문서에서는 Xcode 프로젝트 목표 Sharpie, C# Objective C 코드로 바인딩을 만드는 과정을 단순화 하는 직접 입력으로 사용 하는 방법을 설명 합니다.
ms.prod: xamarin
ms.assetid: 168AA64C-E181-4937-A1F2-AD095B9A36F2
author: asb3993
ms.author: amburns
ms.date: 01/15/2016
ms.openlocfilehash: 850c351f91c9a09a6654c876167e035f751e9504
ms.sourcegitcommit: ea1dc12a3c2d7322f234997daacbfdb6ad542507
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/05/2018
ms.locfileid: "34781119"
---
# <a name="real-world-example-using-an-xcode-project"></a>Xcode 프로젝트를 사용 하 여 실제 예제


**사용 하 여이 예제는 [Facebook에서 POP 라이브러리](https://github.com/facebook/pop)합니다.**

새로운 버전 3.0 이상에서는 목표 Sharpie 입력으로 Xcode 프로젝트 지원합니다. 이러한 프로젝트는 올바른 헤더 파일 및 기본 라이브러리를 컴파일하는 데 필요한 및 따라서 너무에 연결 하는 데 필요한 컴파일러 플래그를 지정 합니다. 목표 Sharpie는 첫 번째 선택 _대상_ 및 불가피 하도록 하는 경우 프로젝트의 기본 구성 합니다.

목표 Sharpie 프로젝트 및 헤더 파일을 구문 분석을 시도 먼저 빌드해야 것입니다. 프로젝트에 있으므로에 연결 하기 전에 전체 프로젝트를 빌드하려면 항상 좋습니다 외부 소비 및 통합, 헤더 파일을 올바르게 구성 합니다 빌드 단계가 있는 경우가 많습니다.

<pre>$ <b>git clone https://github.com/facebook/pop.git</b>
Cloning into 'pop'...
   <em>(more git clone output)</em>

$ <b>cd pop</b>
$ <b>sharpie bind pop.xcodeproj -sdk iphoneos9.0</b></pre>

