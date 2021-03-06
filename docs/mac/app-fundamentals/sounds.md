---
title: Xamarin.Mac에 AVAudioPlayer와 소리 재생
description: 이 문서에서는 Xamarin.Mac 응용 프로그램에서 AVAudioPlayer 소리를 재생 하는 방법에 설명 합니다. AVAudioPlayer 높은 수준 및 보다 완전 하 게 설명 하는 다른 문서 링크에 설명 합니다.
ms.prod: xamarin
ms.assetid: 4A683A94-F75D-4EAF-8497-E9443653250B
ms.technology: xamarin-mac
author: bradumbaugh
ms.author: brumbaug
ms.date: 10/19/2016
ms.openlocfilehash: 9e5b9ec43189999f8a0aee29eb50221b494e2133
ms.sourcegitcommit: ea1dc12a3c2d7322f234997daacbfdb6ad542507
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/05/2018
ms.locfileid: "34791857"
---
# <a name="playing-sound-with-avaudioplayer-in-xamarinmac"></a>Xamarin.Mac에 AVAudioPlayer와 소리 재생

## <a name="about-the-avaudioplayer"></a>AVAudioPlayer에 대 한

`AVAudioPlayer` 클래스 메모리 또는 파일에서 재생 오디오 데이터를 사용 합니다. Apple이이 클래스를 사용 하 여 네트워크 스트리밍 수행 하는 하거나 오디오 I/O 대기 시간이 필요 하지 않는 앱에서 오디오를 재생 하는 것이 좋습니다.

사용할 수는 `AVAudioPlayer` 다음을 수행 하는 클래스:

- 선택적 반복 구조 있는 모든 기간의 소리를 재생 합니다.
- 선택적 동기화와 동시에 여러 소리를 재생 합니다.
- 볼륨, 재생 속도 및 각 소리 재생에 대 한 스테레오 배치를 제어 합니다.
- 빨리 감기 또는 되감기와 같은 기능을 지원 합니다.
- 재생 수준을 계량 데이터를 가져옵니다.

`AVAudioPlayer` iOS, tvOS.aif,.wav 또는.mp3 같은 macOS에서 제공 되는 모든 오디오 형식으로 소리를 지원 합니다.

## <a name="playing-sounds-in-macos"></a>MacOS에서 소리 재생

MacOS iOS 하므로 동일한 오디오 도구 상자 클래스를 지원 하므로 iOS를 참조 하십시오 [AVAudioPlayer와 소리 재생](https://developer.xamarin.com/recipes/ios/media/sound/avaudioplayer/) Xamarin.Mac 앱에서 오디오 재생의 전체 세부 정보에 대 한 설명서입니다.

## <a name="related-links"></a>관련 링크

- [AVAudioPlayer 참조](https://developer.apple.com/documentation/avfoundation/avaudioplayer)
