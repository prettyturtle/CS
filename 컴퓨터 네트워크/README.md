# 컴퓨터 네트워크

## 1. 네트워크와 인터넷

### 네트워크와 인터넷

#### 네트워크

- 종단 시스템(end system): pc나 스마트폰처럼 네트워크 송수신 주체
- 프로토콜(protocol): 두 이종 시스템을 연결하기 위한 규약
- 통신을 목적으로 실제 물리적으로 선으로 연결되어 있거나 무선으로 연결됨

#### 인터넷
- 네트워크간의 연결
- 회사 혹은 소규모의 네트워크에서 전세계 네트워크와 연결된 상태
- 다양한 애플리케이션 서비스가 제공되고 있다
- 종단 시스템은 보통 ISP(Internet Service Provider)에 의해 연결

#### OSI 7 Layer
- 네트워크 구성요소를 7개의 계층으로 역할을 나눈 표준 모델
- 각 계층별 역할을 통해 통신 규격(프로토콜)을 만족
- 일부 하위계층은 하드웨어에서 구현되며 상위계층은 소프트웨어로 구현

#### TCP/IP (Transmission Control Protocol / Internet Protocol)
- OSI 7 Layer가 나오기 전에 널리 사용되던 사실상 표준 역할
- 각 계층별 역할에 따라 역할이 나누어짐

### 용어

#### IP 주소(Address)
- 통신 자료를 최종적으로 전달하기 위해 필요한 송/수신 위치정보
- 보통 IPv4의 주소를 사용하며 주소 부족을 위해 IPv6가 개발됨

#### 패킷 교환(Packet Switching)
- 종단간에 전송되는 데이터를 패킷(Packet)이라는 단위로 전달함
- 패킷은 네트워크를 통해 일정한 순서없이 보내지며 어떤 경로를 통해 이동되는지는 네트워크의 상황에 따라 다르다

### 통신을 위한 기본 동작
- 요청(Request): 전송하는 종단 장치에서 상대방에 서비스를 요청한다
- 인지(Indicate): 수신하는 장치에서 작업 요청(이벤트)을 확인한다
- 응답(Response): 수신하는 장치에서 요청받은 작업에 대해 적절히 응답한다
- 확인(Confirm): 전송 측에서 응답 데이터를 최종적으로 확인한다

### 네트워크 유형
- LAN (Local Area Network)
	- 일정 그룹의 지역 네트워크 (집, 사무실, 학교 등)
	- 소규모로 묶이며 사설망 등을 구축해 연결
- WAN (Wide Area Network)
	- 원거리 통신망으로 넓은 범위 연결 (국가, 대륙 등)
- 크기 유형
	- LAN < WAN < Internet

### 네트워크 토폴로지
- 네트워크의 구성 형태
- Ring Topology
	- 장점: 기기와 기기간의 연결이므로 회선 설치가 수월
	- 단점: 중간에 불량이 생겼을 경우, 해당 장치에 통신하기 어려움
- Bus Topology
- Star Topology
- Mesh Topology

Ring Topology|Bus Topology|Star Topology|Mesh Topology
-|-|-|-
<img width="350px" height="250px" src="https://www.itrelease.com/wp-content/uploads/2019/06/Ring-topology-diagram.jpg">|<img width="350px" height="250px" src="https://thumbs.dreamstime.com/b/bus-topology-diagram-29007878.jpg">|<img width="350px" height="250px" src="https://cdn.comparitech.com/wp-content/uploads/2018/11/star-Topology.jpg">|<img width="350px" height="250px" src="https://www.itrelease.com/wp-content/uploads/2021/06/Full-Mesh-Topology-1024x640.jpg">
