# K8S Master 클러스터의 LBNode 설치 가이드(HAProxy + Keepalived)
* 본 가이드는 A, B로 구성.
* [A는 별도의 LBNode를 갖는 K8S 다중화 클러스터 구축을 위해 작성](#A_LBNode/README.md)되었음.
	* 구축하려는 LBNode에 해당 파일들이 같은 디렉터리 내에 존재해야 함.
	* LBNode 각각에서 아래의 작업들을 동일하게 수행해야 함.
* [B는 별도의 LBNode 없이, K8S 다중화 클러스터 내에서 HAProxy가 동작하도록 작성](#B_NoLBNode/README.md)되었음.
	* 구축하려는 MasterNode에 해당 파일들이 같은 디렉터리 내에 존재해야 함.
	* MasterNode 각각에서 아래의 작업들을 동일하게 수행해야 함.
