#설정 방법 및 설명

※ Defender for Cloud 의 경우 30일 무료 평가판 사용 가능

※ 적용된 각 리소스 수에 따라 과금 측정

Defender for Cloud

♠ Azure resource들에 대해 클라우드 상태 및 보안을 적용, 대시보드 형태로 확인 가능

♠ Defender for Cloud의 경우 구독 단위로 보호

♠ Log Analytics 및 EvnetHub를 통해 Microsoft Sentinel 또는 Splunk로 연동 가능

![image](https://github.com/user-attachments/assets/6d009c76-66f5-4463-8d94-17ef968d542f)


1. Portal.azure.com 메인화면

![image](https://github.com/user-attachments/assets/1b80cf7e-1b46-4ebc-9233-4b727c088335)

2. 상단 검색에 Defender for Cloud 검색

![image](https://github.com/user-attachments/assets/df5cf9b6-28e1-4c70-a5ed-152a5f88ad08)

3. Defender for Cloud Main 화면

![image](https://github.com/user-attachments/assets/d9510484-17b7-4166-a87c-fdb796b1ba14)

4. 환경설정 탭에서 구독 확인

![image](https://github.com/user-attachments/assets/529f4b9b-22de-41fb-83ea-f9df9ff3e0ae)

* 아래와 같이 평가판 사용 가능 여부 확인
![image](https://github.com/user-attachments/assets/a6bd5b32-b225-4d4b-99a4-1f6f78188fd8)


5. Defender for Cloud를 적용할 구독 선택

![image](https://github.com/user-attachments/assets/38e0ad64-8739-4500-84ac-e2e65536118d)


* 구독 선택 시 아래와 같은 화면 확인 가능
* 구독 단위로 리소스 보호 
![image](https://github.com/user-attachments/assets/7677c83b-827c-4c58-958e-c88a2a77f217)


* 처음 Defender for Cloud 사용하는 구독의 경우 아래와 같이 표시 됨 [리소스 수의 경우 기존에 있으면 표시 됨]
![image](https://github.com/user-attachments/assets/3ae43885-7a61-4dbe-94d0-dc4ade5c0a2c)


Defender for Cloud CSPM (Cloud Security Posture Management)

![image](https://github.com/user-attachments/assets/4ccafe7d-9fc0-487c-b75b-49d070c35a35)

Microsoft Defender CSPM은 에이전트 없는 취약성 검사, 데이터 인식 보안 태세, 클라우드 보안 그래프, 고급 위협 헌팅을 비롯한 고급 보안 상태 기능을 제공
가격 책정은 구독 크기를 기준으로 하며, 서버, 데이터베이스, 스토리지 리소스에 대해서만 청구 가능한 리소스당 매월 $5의 요금이 적용
기본 CSPM에는 자산 검색, 태세 강화를 위한 지속적인 평가 및 보안 권장 사항, 조직의 현재 태세 상태를 측정하는 보안 점수가 포함

기본 CSPM (Cloud Security Posture Management)

![image](https://github.com/user-attachments/assets/a300e33a-ede2-46a6-9df5-b44c85da655c)

Defender CSPM (Cloud Security Posture Management)

![image](https://github.com/user-attachments/assets/ba59776b-a904-446a-a43d-9bcaa31814c6)


CWP or CWPP (Cloud workflow protection platform)

클라우드 워크로드 보호 플랫폼은 물리적 서버, 서버리스 기능, 가상 머신 및 컨테이너에 연결된 조직의 클라우드 환경 전반에 걸쳐 일련의 보호 기능을 제공하는 포괄적인 사이버 보안 솔루션
CWPP는 클라우드 환경에 배포된 모든 워크로드를 감지하고 자동으로 평가를 수행하고, 네트워크를 모니터링하고, 문제를 감지하고, 조직의 정책에 따라 보안 표준을 적용

CWP 기능
1. 취약점 관리 :  CWPP는 클라우드 환경에서 실행되는 애플리케이션과 소프트웨어를 평가하여 워크로드가 공개되기 전에 잘못된 구성과 같은 잠재적인 보안 문제 탐지

2. 네트워크 분할 : CWPP는 네트워크를 분할하여 여러 환경의 보안 관리 문제를 완화하는 데 도움, 이를 통해 공격자가 하나의 진입점을 통해 전체 네트워크에 접근하는 것을 더욱 어렵게 만들고, 팀원들에게 위협이 어디에서 나타나는지 더 빠르게 파악

3. 불변성 : CWPP는 배포 후 서버를 변경할 수 없는 불변 인프라를 지원하여 악성 구성 요소가 환경에 침투하는 것을 방지, 승인된 동작 범위를 벗어나는 모든 동작은 자동으로 우려를 불러일으키고 환경에 피해가 발생하기 전에 해결

4. 무결성 보호 : 클라우드 워크로드 보호 플랫폼은 클라우드 환경에서 모든 것이 제대로 실행되도록 끊임없이 작동, 이를 통해 보안 팀은 안심하고 더 중요한 작업에 집중할 시간을 확보

5. 메모리 보호 : CWPP는 지속적으로 작동하기 때문에 애플리케이션이 실행될 때마다 나타나는 취약점을 식별

6. 허용 목록 : 모든 조직에서 흔히 발생하는 위험 중 하나는 승인되지 않은 소프트웨어의 설치 및 사용 문제, 이는 보안 모범 사례를 추적하고 적용하기 어렵게 만들 뿐만 아니라, 네트워크로의 잠재적인 진입로를 확보하여 간과
CWPP를 사용하면 클라우드 인프라 내에서 애플리케이션을 허용 및 차단하는 목록을 자동으로 적용하여 이러한 위험을 줄임

7. 침입 방지 : CWPP는 의심스러운 활동이나 악성 소프트웨어가 있는지 네트워크를 지속적으로 모니터링, 이상 징후나 정책 위반 사항이 감지되는 즉시 CWPP가 조치를 취하여 문제를 예방

8. 엔드포인트 탐지 및 대응 : 여러 사용자가 여러 환경에서 작업하는 상황에서 CWPP는 네트워크에 연결된 장치를 모니터링하여 위협과 의심스러운 행동을 감지하고 이러한 문제를 신속하게 해결하는 데 중요한 역할

9. 맬웨어 방지 검사 : 자동 검사는 보안팀이 조직 전체의 클라우드 워크로드를 모니터링하는 부담 감소 CWPP는 워크로드에서 맬웨어를 감지하고 인프라에 침투하기 전에 문제를 해결

Defender for Cloud - Servers

![image](https://github.com/user-attachments/assets/9d0e432c-1ed6-4b9e-beb5-13dea994579e)

Defender for Cloud - App Service

![image](https://github.com/user-attachments/assets/d8725bd5-5483-41a2-9676-efcb5e837dc4)

Defender for Cloud - Databases

![image](https://github.com/user-attachments/assets/ea60abb0-b176-4148-9eca-ae85860812ee)

Defender for Cloud - Storage 

![image](https://github.com/user-attachments/assets/48a31a60-002d-4b3d-9157-fa9cfbfe7bc5)

Defender for Cloud - Containers

![image](https://github.com/user-attachments/assets/86d92ef6-f683-4d4f-870d-63b51b66efc8)

Defender for Cloud - AI Services

![image](https://github.com/user-attachments/assets/37f9c0e3-cd9b-4b92-8da6-d1e4cebd4918)

Defender for Cloud - Key Vault

![image](https://github.com/user-attachments/assets/0c606012-0e05-4730-873f-904048980934)

Defender for Cloud - Resource Manager

![image](https://github.com/user-attachments/assets/73a615bb-6b41-4582-b479-fcbdf16f43ae)

Defender for Cloud - APIs

![image](https://github.com/user-attachments/assets/15eac650-c705-4b9e-bdd2-8fd9e14c57b1)


