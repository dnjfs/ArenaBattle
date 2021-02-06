# ArenaBattle
이득우의 언리얼 C++ 게임 개발의 정석


언리얼 엔진을 독학하기 위하여 책을 보며 따라 진행한 프로젝트입니다.

언리얼 엔진 4.25.4 버전에서 개발하였습니다.
책은 4.19 버전을 기준으로 코드가 작성되어있어 함수 이름이 다르거나,
멤버 변수의 접근 제한자가 private로 바껴 직접 접근하지 못하는 변수들이 있어 수정하였습니다.

애셋이 모두 포함된 프로젝트입니다.

프로젝트를 다운받아 ArenaBattle.uproject 파일을 오른쪽 클릭하고
Generate Visual Studio project file을 선택하여 비주얼 스튜디오의 솔루션 파일을 만들 수 있습니다.

uproject으로 직접 언리얼 엔진을 실행시킬 수도 있지만, 디버그를 위해 솔루션 파일으로 비주얼 스튜디오를 실행시킨 후,
구성 관리자를 DebugGame Editor로 선택 후 F5로 디버깅을 시작하면 코드 중간에 중단점을 걸어 디버깅을 할 수 있습니다.

Source\ArenaBattle\Private\ABGameMode.cpp 코드 16번째 줄의 ScoreToClear 값을 조정하여 난이도 조절을 할 수 있습니다.

WASD로 이동하고 SpaceBar로 점프, 마우스 왼쪽클릭으로 공격, Shift+V로 시점변경 후 마우스를 움직여 카메라를 이동시킬 수 있습니다.
