---
title: iOS Backgrounding 기술
description: '이 문서에서 iOS backgrounding 다양 한 기술을 설명 하는 지침에 연결: 백그라운드 작업, 백그라운드 전송 서비스, 백그라운드 가져오기 및 원격 알림입니다.'
ms.prod: xamarin
ms.assetid: 011A8D48-1CDC-486A-A2B0-C4946118E7A9
ms.technology: xamarin-ios
author: bradumbaugh
ms.author: brumbaug
ms.openlocfilehash: ebf3c07a319a79994093f89f8e54f4cba7402533
ms.sourcegitcommit: ea1dc12a3c2d7322f234997daacbfdb6ad542507
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/05/2018
ms.locfileid: "34783757"
---
# <a name="ios-backgrounding-techniques"></a>iOS Backgrounding 기술

다음 섹션에서 기존 backgrounding 옵션와 함께 다음 iOS 기능 설명 합니다.

-  [편의적 백그라운드 작업](~/ios/app-fundamentals/backgrounding/ios-backgrounding-techniques/ios-backgrounding-with-tasks.md#background_tasks_in_iOS_7) -장치가 다른 프로세스에 대 한 절전 모드 해제 상태에 있을 때 편의적 청크에서 백그라운드 작업을 실행 하 여 배터리 수명을 보존할 합니다.
-  [백그라운드 전송 서비스](~/ios/app-fundamentals/backgrounding/ios-backgrounding-techniques/ios-backgrounding-with-tasks.md#background-transfers) -안정적으로 업로드 및 네트워크 상태 또는 파일 크기에 관계 없이 파일을 다운로드 합니다.
-  [Fetch 백그라운드](~/ios/app-fundamentals/backgrounding/ios-backgrounding-techniques/updating-an-application-in-the-background.md#background_fetch) -시스템에 의해 결정 된 간격으로 백그라운드에서 응용 프로그램을 새로 고칩니다.
-  [원격 알림](~/ios/app-fundamentals/backgrounding/ios-backgrounding-techniques/updating-an-application-in-the-background.md#remote_notifications) -사용자가 응용 프로그램을 사용자에 게 또는 자동으로 업데이트 하는 옵션을 사용 하기 전에 백그라운드에서 콘텐츠 업데이트를 트리거할 푸시 알림을 사용 합니다.
-  **UI 업데이트를 백그라운드** -사용자에 대 한 응용 프로그램 UI를 준비 하 고 응용 프로그램의 스냅숏 백그라운드에서 모두 업데이트 합니다.
