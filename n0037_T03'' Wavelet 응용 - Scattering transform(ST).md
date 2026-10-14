---
tags:
---
### 커버페이지
==노트요약== scattering transform(ST) 이용한 자동 분류 예제 코드 및 이론, 연구 내용
- 자동분류 예제 코드 - 매트랩, 파이썬 : [C01], [C02] `C for code`
- <span style="color:rgb(255, 255, 0)">이론</span> 및 <span style="color:rgb(255, 255, 0)">참고문헌</span> 정리 : [R00] `R for reference`
- 연구 내용 정리 : [S00]

==상위노트== [[n0037'' Data Science, Pattern Recognition 딥러닝]]  
==형제노트== 
- [[n0478'' wavelets]] - 웨이블렛 관련 내용 모음
- [[n0037_T12'' JTFS]] - joint time - frequency scattering 에 대한 모음

==서브노트==
- [[n0037_T03_C01'' scattering - using matlab]] : <span style="color:rgb(255, 255, 0)">매트랩 scattering 코드</span>에 대한 예제 코드 분석
- [[n0037_T03_C02'' python scattering]] : <span style="color:rgb(255, 255, 0)">파이썬 scattering 연습</span> 서브노트


참고자료 정리
- [[n0037_T03_R01'' REF paper]] : <span style="color:rgb(255, 255, 0)">이론 및 참고논문 요약 정리</span>

리서치 전체 흐름 정리 노트
- [[n0037_T03_r00'' GUIDE Scattering journal paper]] : 리서치 전체 흐름 정리 노트
	- [[n0037_T03_S01'' SCIE sct]]
	- [[n0037_T03_S02'' ST 한국음향학회]]

==참고노트==  
- [[2024-11-10]] 유튜브 + 매트랩 튜토리얼 영상

# 핵심 이론의 정리 - R01 내용 재정리
이론(논리)의 발전 단계: wavelet (CWT) --> scattering --> JTFS
**Notation**
$$W x=x \star \psi ; \quad U x=|W x| ; \quad S x=U x \star \phi$$
$W$ for wavelet transform - 웨이블렛변환
$U$ for unaveraged coefficients (after modulus) - 절대값
$S$ for scattering (averaged coefficients) - scattering coefficient

# 코드 - Kymatio 튜토리얼
==참고노트== [[n0037_T03_C02'' python scattering#Kymatio 튜토리얼]] 에서 정리함


