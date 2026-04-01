# a2meter

WinDivert로 TCP 패킷을 캡처해 미터기 DLL에 투입하고, 콜백으로 실시간 DPS를 집계합니다.

관리자 권한을 필요로 합니다.

### [다운로드 AionMeter](https://github.com/tmopcode/Aion2-Dps-Meter-Packet-Process/raw/refs/heads/main/update/AionMeter0.7.zip)

---

## 메인 화면

### 패킷 캡처 준비 화면

캐릭터 선택 또는 캐릭터 이동 시 패킷 캡처가 시작됩니다.

<p align="left">
<img alt="패킷 캡처 준비" src="https://github.com/tmopcode/Aion2-Dps-Meter-Packet-Process/blob/main/image/%EB%A9%94%EC%9D%B8/1.png?raw=true" />
</p>

하단 메뉴를 통해 그래프, 설정, 초기화, 종료 기능에 접근할 수 있습니다.

<p align="left">
<img alt="패킷 캡처 준비 - 하단 메뉴" src="https://github.com/tmopcode/Aion2-Dps-Meter-Packet-Process/blob/main/image/%EB%A9%94%EC%9D%B8/2.png?raw=true" />
</p>

---

### 패킷 감지 초기 화면

전투 진입 전 초기 상태로, 전투 시간 / 데미지 / HP를 표시합니다.

<p align="left">
<img alt="패킷 감지 초기" src="https://github.com/tmopcode/Aion2-Dps-Meter-Packet-Process/blob/main/image/%EB%A9%94%EC%9D%B8/3.png?raw=true" />
</p>

<p align="left">
<img alt="패킷 감지 초기 - 하단 메뉴" src="https://github.com/tmopcode/Aion2-Dps-Meter-Packet-Process/blob/main/image/%EB%A9%94%EC%9D%B8/4.png?raw=true" />
</p>

---

### 데미지 패킷 감지 플레이어 목록

전투 중 플레이어별 DPS 순위 및 누적 피해량을 표시합니다.

<p align="left">
<img alt="플레이어 목록" src="https://github.com/tmopcode/Aion2-Dps-Meter-Packet-Process/blob/main/image/%EB%A9%94%EC%9D%B8/5.png?raw=true" />
</p>

실시간 그래프를 함께 표시할 수 있습니다.

<p align="left">
<img alt="플레이어 목록 + 실시간 그래프" src="https://github.com/tmopcode/Aion2-Dps-Meter-Packet-Process/blob/main/image/%EB%A9%94%EC%9D%B8/6.png?raw=true" />
</p>

---

### 몬스터(NPC) 리스트

현재 전투 중인 몬스터 목록을 드롭다운으로 확인하고 전환할 수 있습니다.

<p align="left">
<img alt="몬스터 리스트" src="https://github.com/tmopcode/Aion2-Dps-Meter-Packet-Process/blob/main/image/%EB%A9%94%EC%9D%B8/7.png?raw=true" />
</p>

---

## 설정

### 표시

보스 판정, 비율 표시 방식, 본인 표시, 플레이어 정보, 닉네임 마스킹 등을 설정합니다.

<p align="left">
<img alt="설정 - 표시" src="https://github.com/tmopcode/Aion2-Dps-Meter-Packet-Process/blob/main/image/%EC%84%A4%EC%A0%95/1.png?raw=true" />
</p>

---

### 그래프

실시간 DPS 그래프 표시 여부, 표시 대상, 그래프 모드(CMA / DPS), 변동 시간, 표시 간격, 애니메이션 등을 설정합니다.

<p align="left">
<img alt="설정 - 그래프" src="https://github.com/tmopcode/Aion2-Dps-Meter-Packet-Process/blob/main/image/%EC%84%A4%EC%A0%95/2.png?raw=true" />
</p>

---

### 색상

직업별 색상 및 본인 색상, 종족별 색상, 전투력 색상을 설정합니다.

<p align="left">
<img alt="설정 - 색상" src="https://github.com/tmopcode/Aion2-Dps-Meter-Packet-Process/blob/main/image/%EC%84%A4%EC%A0%95/3.png?raw=true" />
</p>

---

### 단축키

기능별 단축키를 설정합니다. 키를 클릭한 뒤 원하는 키를 누르면 변경되며, ESC로 취소합니다.

<p align="left">
<img alt="설정 - 단축키" src="https://github.com/tmopcode/Aion2-Dps-Meter-Packet-Process/blob/main/image/%EC%84%A4%EC%A0%95/4.png?raw=true" />
</p>

| 기능           | 기본 단축키 |
| -------------- | ----------- |
| 창 표시 / 숨김 | `Insert`    |
| 데이터 초기화  | `Delete`    |
| 클릭 금지 토글 | `End`       |

---

### 시스템

패킷 캡처 방식(WinDivert / Npcap), 틱레이트, 창 설정(항상 위, 클릭 금지, 투명도, 창 크기)을 설정합니다.

<p align="left">
<img alt="설정 - 시스템" src="https://github.com/tmopcode/Aion2-Dps-Meter-Packet-Process/blob/main/image/%EC%84%A4%EC%A0%95/5.png?raw=true" />
</p>

---

## 스킬 / 버프 / 디버프

### 스킬 목록

플레이어 클릭 시 스킬별 세부 통계(적중, 치명타, 강타, 완벽, 다단, 막기, 초당/평균/최소/최대/누적 피해)를 확인할 수 있습니다.

<p align="left">
<img alt="스킬 목록" src="https://github.com/tmopcode/Aion2-Dps-Meter-Packet-Process/blob/main/image/%EC%8A%A4%ED%82%AC/1.png?raw=true" />
</p>

스킬 그룹을 펼쳐 세부 스킬별 통계를 확인할 수 있습니다.

<p align="left">
<img alt="스킬 목록 - 그룹 펼침" src="https://github.com/tmopcode/Aion2-Dps-Meter-Packet-Process/blob/main/image/%EC%8A%A4%ED%82%AC/2.png?raw=true" />
</p>

---

### 버프 목록

버프 / 디버프 탭에서 사용 횟수 및 지속시간 유지율을 확인할 수 있습니다.

<p align="left">
<img alt="버프 목록" src="https://github.com/tmopcode/Aion2-Dps-Meter-Packet-Process/blob/main/image/%EC%8A%A4%ED%82%AC/3.png?raw=true" />
</p>

---

### 디버프 목록 (보스)

보스에 적용된 디버프 및 지속시간 유지율을 확인할 수 있습니다.

<p align="left">
<img alt="디버프 목록 - 보스" src="https://github.com/tmopcode/Aion2-Dps-Meter-Packet-Process/blob/main/image/%EC%8A%A4%ED%82%AC/4.png?raw=true" />
</p>

---

## 업데이트 알림

새로운 버전이 출시되면 실행 시 업데이트 알림 창이 표시됩니다.
**지금 업데이트** 버튼으로 즉시 업데이트하거나, **건너뛰기**로 현재 버전을 유지할 수 있습니다.

<p align="left">
<img alt="업데이트 알림" src="https://github.com/tmopcode/Aion2-Dps-Meter-Packet-Process/blob/main/image/%EC%97%85%EB%8D%B0%EC%9D%B4%ED%8A%B8/1.png?raw=true" />
</p>
