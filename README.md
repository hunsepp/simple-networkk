# simple-networkk

20200731

실전 패브릭네트워크 구성하기
교재12차 38~99(86~99 집중)
네트워크구성 확장
3개의 organization(v)
ca구성(v)
각 organization에 앵커피어 구성(v)
TLS 암호화 통신구현(?)
3개의 COUCHDB(v)
<네트워크준비>
crypto-config.yaml 수정 (노트랑 ca개수)
configtx.yaml 수정 (channel과 genesis block 생성 설정, anchor 피어 설정, orderer 설정, organization 3개 생성 and etc...)
generate.sh 수정 및 실행
docker-compose.yml 수정(ca컨테이너와 peer 컨테이너정의, ca 관리자, cli 컨테이너 구성, couchDB 추가및 수정)
start.sh 수정(organization 실행 명령어, 경로 등등)

할것, 앵커피어 늘려서 네트워크구축)
