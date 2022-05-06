# computer-ability
## 컴퓨터 일반
1. 최신 Windows의 특징
·그래픽 사용자 인터페이스(GUI) 사용: 키보드로 명령어를 직접 입력하지 않고, 
아이콘이나 메뉴를 마우스로 선택하여 모든 작업을 수행하는 사용자 작업 환경

·선점형 멀티태스킹(Preemptive Multi-tasking): 운영체제가 각 작업의 CPU이용 시간을 제어하는 응용 프로그램 실행중 문제가 발생하면 해당 프로그램을 강제 종료시키,
모든 시스템 자원을 반환하는 멀티테스킹 운영 방식
CPU: 컴퓨터의 정중앙에서 모든 데이터를 처리하는 장치
입력 받은 명령어를 해석해 연산한 후 그 결과를 출력하는 역할을 하게 된다.

·플러그 앤 플레이(PnP; Plug & Play): 컴퓨터 시스템에 하드웨어를 설치했을 때,
해당 하드웨어를 사용하는 데 필요한 시스템 환경을 운영체제가 자동으로 구성해주는 것

·OLE(Object Linking and Embedding): 다른 여러 응용 프로그램에서 작성된 문자나 그림 등의 개체(Object)를 현재 작성중인 문서에 자유롭게 
연결(Linking)하거나 삽입(Embedding)하여 편집할 수 있게 하는 기능

·255자의 긴 파일 이름: 최대 255자의 긴 파일 이름을 지정할 수 있고, NTFS에서 유니코드 문자를 지원하여 세계 여러 문자를 파일 이름에 사용할 수 있으며, 파일 이름으로는 
```
￦/:*?"<>|
```
를 제외한 모든 문자 및 공백을 사용할 수 있음

2. 파일 시스템
보조기억장치에 저장되는 파일에 대해 수정, 삭제, 추가, 검색 등의 작업을 체계적으로 할 수 있도록 지원하는 관리 시스템으로
종류에는 FAT(16), FAT32, NTFS가 있다.
```
         | ·MS-DOS 및 기타 Windows 기반의 운영체제에서 파일을 구성하고 관리하는데 사용되는 파일 시스템
FAT(16)  | ·MS-DOS를 포함한 Windows 98, 2000, XP 등에서 사용할 수 있음
*********************************************************************************************
         | ·FAT 파일 시스템에서 파생된 것으로 FAT보다 큰 드라이브를 사용할 수 있고, FAT에 비해 클러스터 크기가 작으므로 하드디스크의 공간낭비를 줄일 수 있음
FAT32    | ·Windows 98, 2000, XP 등에서 사용할 수 있음
*********************************************************************************************
         | ·성능 및 공간 활용, 보안, 안정성 면에서 FAT 파일 시스템에 비해 뛰어난 고급 기능을 제공함
NTFS     | ·Windows NT, 2000, XP, Vista, 7 등에서 사용할 수 있음
```

3. 한글 Windows 7의 새로운 기능
```
라이브러리   | 컴퓨터의 여기저기에 흩어져 있는 자료를 한 곳에서 확인하고 정리할 수 있게 하는 기능
***************************************************************************************************
홈 그룹      | 한글 Windows 7이 설치된 두 대 이상의 컴퓨터를 네트워크로 연셜해 파일 및 프린터를 쉽게 공유할 수 있도록 하는 기능
***************************************************************************************************
64비트       | 완전한 64비트로 데이터를 처리하므로 더 많은 양의 데이터를 빠르게 처리할 수 있으며,
데이터 처리  | 사용자에게 좀더 빠르고 간편하게 시스템을 구축할 수 있게 함
***************************************************************************************************
점프 목록    | 파일, 폴더, 웹 사이트 등 최근에 사용했던 문서나 작업을 더 빠르고 간편하게 이용할 수 있도록 프로그램별로 구성한 목록
***************************************************************************************************
프로그램 단추| 자주 사용하는 프로그램을 쉽게 실행할 수 있도록 
고정         | 작업 표시줄에 고정하는 기능
***************************************************************************************************
에어로 전환  | 작업 표시줄을 클릭하지 않고도 열려 있는 모든 창의 
3D           | 내용을 미리 볼 수 있음
***************************************************************************************************
에어로 스냅  | 열려 있는 창을 화면 가장자리로 드래그하여 창의
(Aero Snap)  | 크기를 조절할 수 있음
***************************************************************************************************
에어로 세이크| 창을 흔들어 다른 모든 열려 있는 창을 최소화할 수
(Aero Shake) | 있음
***************************************************************************************************
에어로 피크  | 현재 실행중인 프로그램을 통해 열린 모든 창들의 축소판 미리 보기가 가능하며,
(Aero Peek)  | 열려 있는 모든 창을 최소화하지 않고 바탕 화면을 볼 수 있음 
***************************************************************************************************
자려 보호    | 시간, 프로그램, 게임 등급 등에서 특정 사용자를 대상으로 컴퓨터 사용에 제한을 가할 수 있음
***************************************************************************************************
사용자 계정  | 유해한 프로그램이나 불법 사용자가 컴퓨터 설정을 
컨트롤       | 임의로 변경하지 못하도록 제어하는 기능
***************************************************************************************************
             | 시간이나 일정, 뉴스 등 컴퓨터를 사용하면서 자주 확인하는 정보를 손쉽게
가젯         | 볼 수 있도록 바탕화면에 표시할 수 있는 작은 프로그램
***************************************************************************************************
캡쳐 도구    | 화면의 특정 부분 또는 전제를 캡쳐하여 HTML, PNG, GIF, JPG 등의 파일로 저장할 수 있음
***************************************************************************************************
스티커 메모  | 종이에 메모 하듯이 일정이나 전화번호 등을 적을 떄 사용함
***************************************************************************************************
Windows      | 한글 Windows 7의 다양한 멀티미디어 파일을
Media Center | 한 곳에서 모두 재생할 수 있음
***************************************************************************************************
Windows DVD  | 사진이나 동영상 파일을 일반 DVD 플레이어에서 
Maker        | 재생할 수 있는 DVD로 만들 때 사용함
***************************************************************************************************
Windows      | 스파이웨어를 포함한 원치 않는 소프트웨어로부터
Defender     | 컴퓨터를 보호함
***************************************************************************************************
원격 미디어  | 홈 미디어에 인터넷을 연결하면 음악, 비디오, 사진을 장소에
스트리밍     | 관계없이어디서나 스트리밍할 수 있음
***************************************************************************************************
시동 복구    | Windows가 시작되지 않는 문제를 
(컴퓨터 복구)| 진단하지 않고 복구하는 기능
***************************************************************************************************
Windows      | 컴퓨터의 하드웨어 및 소프트웨어 구성 기능을
체험 지수    | 측정하고 측정값을 숫자(1.0~7.9)로 표시함
***************************************************************************************************
Windows      | 터치 스크린이 설치된 컴퓨터인 경우 손가락을
Touch        | 사용하여 마우스나 키보드의 작업을 대신할 수 있음
***************************************************************************************************
ReadyBoost   | USB 플래시 드라이브나 플래시 메모리 카드를 사용하여 컴퓨터 속도를 향상시키는 기능
```

4. 주요 부팅 메뉴(부팅 메뉴 표시: F8)

·컴퓨터 복구: 부팅에 문제가 있거나 시스템이 정상적으로 동작하지 않을 때 시스템을 초기 상태 또는 최적의 상태로 복원시키기 위한 메뉴로,
시스템 복구 작업은 '시스템 복구 옵션' 대화상자를 통해 이루어짐

·안전 모드: 컴퓨터가 비정상적으로 작동될 때 컴퓨터에 발생한 문제를 해결하기 위해 사용하는 방식으로, 
컴퓨터 작동에 필요한 최소한의 장치만을 설정하여 부팅하므로 네트워크 관력 작업이나 사운드 카드, 모뎀 등은 사용할 수 없음(해상도: 800*600)

·안전 모드(네트워킹 사용): 네트워크가 지원되는 안전 모드로 부틸하는 방식

·안전 모드(명령 프롬프트 사용): 안전 모드로 부팅하되, GUI 환경이 아닌 DOS 모드로 부팅함

·부팅 로깅 사용: 부팅 과정을 Ntbtlog.txt파일에 기록하며 부팅하는 방식으로, 문제가 있을 때 이 방법을 사용하여 부팅한 후
Ntbtlog.txt파일을 열러 문제가 발생한 부분을 확인할 수 있음

·저해상도 비디오 사용(640*480): 화면 모드를 640*480해상도로 설정하여 부팅하는 방식으로, 그래픽 카드 드라이버를 새로
설치한 후 한글 Windows 7이 제대로 실행되지 않을 때 유용함

·마지막으로 성공한 구성(고급): 마지막으로 시스템이 문제없이 실행되고 종료되었을 때의 레지스트리 정보와 드라이버를 사용하여 부팅하는 방식

·디렉터리 서비스 복원 모드: 디렉터리 컨트롤에서만 사용 가능한 방식으로, 
디렉터리 서비스를 복원할 수 있도록 Active Directory를 실행하는 Windows 도메인 컨트롤러를 시작함

·디버깅 모드: 네트워크로 연결된 경우 컴퓨터 관리자에게 해당 컴퓨터의 디버그 정보를 보내면서 컴퓨터를 시작함

·시스템 오류 시 자동 다시 시작 사용 안함: 시스템에 오류가 발생한 경우 시스템이 자동으로 다시 시작되지 않도록 지정함

·드라이버 서명 적용 사용 안함: 부적절한 서명이 포함된 드라이버를 설치할 수 있도록 함

·표준 모드로 Windows 시작: 한글 Windows 7의 기본 부팅 방식

5. 바로 가기 키(단축키)

<img width="" height="" src="./pic/단축키.png"></img>
