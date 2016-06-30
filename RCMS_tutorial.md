# RCMS tutorial
![](http://i.imgur.com/uUUsDDt.jpg)

## Table of Contents ##
1. [RCMS 개요](#RCMS 개요)
2. [기본설정](#기본설정)
	1. [기본설정 프로세스](#기본설정 프로세스)
	2. [절차: RCMS 실행/보안시스템 설치](#절차-RCMS실행보안시스템설치)
	3. [절차: 회원가입](#절차-회원가입)
	4. [절차: 인증서 등록(산업기술지원 사이트에서)](#절차-인증서 등록(산업기술지원 사이트에서))
	5. [절차: 협약정보 확인](#절차-협약정보 확인)
	6. [절차: 펌뱅킹 서비스 이용 신청](#절차-펌뱅킹 서비스 이용 신청)
	7. [절차: 권한 부여](#절차-권한 부여)
	8. [절차: 이체 비밀번호 등록](#절차-이체 비밀번호 등록)
	9. [절차: 연구비 카드사 등록](#절차-연구비 카드사 등록)
	10. [절차: 연구비 카드 과제등록](#절차-연구비 카드 과제)
	11. [연구비 카드 과제등록](#절차-연구비 카드 과제등록)  
3. [연구비 관리](#연구비 관리)
	1. [연구비관리 프로세스](#연구비관리 프로세스)
	2. [연구비 사용관리](#연구비 사용관리)
	3. [사용등록](#사용등록)
		1. [사용등록-전자세금계산서](#사용등록-전자세금계산서)
			1. [사용등록-전자세금계산서-증빙서류 관리](#사용등록-전자세금계산서-증빙서류 관리)
			2. [사용등록-전자세금계산서-계좌이체](#사용등록-전자세금계산서-계좌이체)
			3. [사용등록-전자세금계산서-기자재 구입 예시](#사용등록-전자세금계산서-기자재 구입 예시)
		2. [사용등록-카드](#사용등록-카드)
			1. [사용등록-카드-증빙서류 관리](#사용등록-카드-증빙서류 관리)
			2. [사용등록-카드-연구활동비 사용 예시](#사용등록-카드-연구활동비 사용 예시)
		3. [사용등록-기타](#사용등록-기타)
			1. [사용등록-기타-인건비 사용 예시](#사용등록-기타-인건비 사용 예시)
	4. [사용실행](#사용실행)

<a name="RCMS 개요"/>
## RCMS 개요 ##
* 개념과 도입배경
* RCMS 특징/메뉴구조/구성

은행/카드사와 연계해 실시간으로 연구비를 지급합니다. 수행기관의 연구비 사용은 반드시 RCMS에서 처리해야 합니다.

### 주요기능 ###
기획 > 과제공고 및 선정 > ** 연구과제 관리(집행) ** > ** 사후정산 ** > 성과활용

### 구성 ###
* 연구비 집행 모듈
	* 연구비 전용 인터넷 뱅킹
	* 일반 법인카드를 통한 연구비 사용
* 연구비 정산 모듈
	* 국세청 전자증깁을 통한 지급처리
	* 온라인 정산보고 지원
* 연계모듈
	* 금융망 연계모듈
	* 과제관리 연계모듈

이전에는 일괄 지급 후 일괄 보고했습니다.

도입이후에는 전담기관이 연구비를 RCMS에 예치한 후 연구기관이 실시간 지급을 하게 됩니다. 실시간으로 정산하고 증빙합니다.

![](http://i.imgur.com/cZBrEYZ.png)

### 특징: 연구비 예치 ###
수행기관은 RCMS에 민간부담금을 입금(가상계좌)합니다. 협약이 완료된 후 전담기관이 정부출연금을 입금한 이후에 사용가능합니다.
![](http://i.imgur.com/rkOY1sm.jpg)

### 특징: 사업비 사용등록/이체실행 ###
수행기관이 사용등록을 하면 RCMS에서 수행기관 사업비 계좌를 거처 거래처 계좌로 실시간 이체(입금과 동시에 출금)

![](http://i.imgur.com/642PvAj.png)
![](http://i.imgur.com/G0vlPkB.png)
![](http://i.imgur.com/FhAAokb.png)
![](http://i.imgur.com/ORMRAIt.png)
![](http://i.imgur.com/Dx1WLhT.png)
![](http://i.imgur.com/FqgxIn4.jpg)

### 특징: 연구비 상시 점검 ###
협약종료 -> 실시간으로 확인/결과 보고서 3회/년
![](http://i.imgur.com/RnegtrE.jpg)

### 특징: 증빙서류 관리 간소화 ###
서류보관 -> 파일로 서버 전송(전자증빙 및 증빙파일 온라인 등록, 거래 발생시점 업로드 원칙 + 예외적으로 20일 이내 업로드)
![](http://i.imgur.com/QQPvkEy.jpg)

### 특징: 온라인 정산 가능 ###
증빙서류 시스템은 온라인 상 저장되어 있고 추가로 사업비 집행마감, 이월금 등록 추가정산 서류를 업로드한 후 보고서 제출 버튼을 클릭합니다. 

증빙서류를 검토한 후 정산담당자(전담기관/회계법인)가 최종 정산결과를 도출합니다.
 
![](http://i.imgur.com/9SYS2vv.jpg)

### 도입성과 ###

<a name="기본설정"/>
## 기본설정 ##
![](http://i.imgur.com/aGkal0U.jpg)

<a name="기본설정 프로세스"/>
### 기본설정 프로세스 ###
![](http://i.imgur.com/MubyJDL.jpg)

<a name="절차-RCMS실행보안시스템설치"/>
#### 절차: RCMS 실행/보안시스템 설치 ####
자동으로 설치되지만 혹시 설치되지 않으면 수동으로 설치할 수 있습니다.
![](http://i.imgur.com/LOveRHy.jpg)

필수
![](http://i.imgur.com/YkaB4Q9.jpg)

부가
![](http://i.imgur.com/eKcFSM6.jpg)

<a name="절차-회원가입"/>
### 절차: 회원가입 ###

![](http://i.imgur.com/A5opomZ.jpg)
![](http://i.imgur.com/XsuCBCD.jpg)
![](http://i.imgur.com/71c8mnX.jpg)

<a name="절차-인증서 등록(산업기술지원 사이트에서)"/>
### 절차: 인증서 등록(산업기술지원 사이트에서) ###
인증서 등록 링크는 RCMS 사이트 퀵메뉴에서

산업기술지원 사이트로 이동 후 동일한 아이디로 접속

![](http://i.imgur.com/lpgwcdU.jpg)

![](http://i.imgur.com/szSe5fn.jpg)

![](http://i.imgur.com/NS4Mj3T.jpg)

![](http://i.imgur.com/CEpqnPh.jpg)

<a name="절차-협약정보 확인"/>
### 절차: 협약정보 확인 ###
![](http://i.imgur.com/0zawYu0.jpg)
![](http://i.imgur.com/dlkM2wB.jpg)
![](http://i.imgur.com/lCW7kaM.jpg)
![](http://i.imgur.com/oYjXWsU.jpg)
![](http://i.imgur.com/YuGN7Nw.jpg)
![](http://i.imgur.com/vAnCAH9.jpg)

<a name="절차-펌뱅킹 서비스 이용 신청"/>
### 절차: 펌뱅킹 서비스 이용 신청 ###
RCMS에서 바로 신청가능

![](http://i.imgur.com/nT61hvg.jpg)

<a name="절차-권한 부여"/>
### 절차: 권한 부여 ###
참여연구원에게 이체 권한 부여
![](http://i.imgur.com/wzSGFHt.jpg)
![](http://i.imgur.com/drHVylJ.jpg)
![](http://i.imgur.com/EG0FiIq.jpg)
![](http://i.imgur.com/L58Zm8q.jpg)
![](http://i.imgur.com/4Y5wkWv.jpg)

주의
![](http://i.imgur.com/8fFHH71.jpg)


일반사용자에게 이체 권한 부여
![](http://i.imgur.com/vCqR2g8.jpg)

사용자이름이 등록된 경우
![](http://i.imgur.com/kATgK4m.jpg)
![](http://i.imgur.com/9i7OdPm.jpg)

사용자이름이 등록되어 있지 않은 경우
![](http://i.imgur.com/GqcfEqa.jpg)
![](http://i.imgur.com/kmWpoil.jpg)

<a name="절차-이체 비밀번호 등록"/>
### 절차: 이체 비밀번호 등록 ###
연구비 이체시 마지막 확인 작업

이체실행 담당자 별로 비밀번호 등록
![](http://i.imgur.com/nNwCXdq.jpg)

<a name="절차-연구비 카드사 등록"/>
### 절차-연구비 카드사 등록 ###
과제별로 카드사는 한 개만. 카드는 여러 개 등록가능합니다.
등록시 법인공용공인인증서가 필요합니다.

![](http://i.imgur.com/jOfcGDS.jpg)

카드사 등록 절차 
![](http://i.imgur.com/9mDst48.jpg)
![](http://i.imgur.com/ru2s9Q9.jpg)
![](http://i.imgur.com/5sIyy2b.jpg)
![](http://i.imgur.com/vu0bb6T.jpg)

<a name="절차-연구비 카드 과제등록"/>
### 절차-연구비 카드 과제등록 ###
![](http://i.imgur.com/o9VDW24.jpg)
![](http://i.imgur.com/uFGsSyb.jpg)
![](http://i.imgur.com/EgBMo8M.jpg)
![](http://i.imgur.com/QCG5iBn.jpg)

<a name="연구비 관리"/>
## 연구비 관리 ##
![](http://i.imgur.com/0p6B09f.jpg)

<a name="연구비관리 프로세스"/>
### 연구비관리 프로세스 ###
![](http://i.imgur.com/MJyDKPX.jpg)


<a name="연구비 현황조회"/>
### 연구비 현황조회 ###
![](http://i.imgur.com/ZCbQugL.jpg)

비목별 사용내역 조회
![](http://i.imgur.com/7vBX7n0.jpg)

주의: 정부출연금 지급완료 이후 연구비 사용이 가능합니다.

<a name="연구비 사용관리"/>
### 연구비 사용관리 ###
연구비 등록방법
![](http://i.imgur.com/EWM06Di.jpg)

증빙우선등록방식
![](http://i.imgur.com/ysvD40H.jpg)
![](http://i.imgur.com/pce4n87.jpg)

비목우선등록방식
![](http://i.imgur.com/RfbVvqY.jpg)
![](http://i.imgur.com/YyupTjE.jpg)

<a name="사용등록"/>
### 사용등록 ###
사용등록
![](http://i.imgur.com/2OhdRJt.jpg)

<a name="사용등록-전자세금계산서"/>
#### 사용등록-전자세금계산서 ####
![](http://i.imgur.com/W7bb6Wi.jpg)
![](http://i.imgur.com/DUE93uS.jpg)
![](http://i.imgur.com/dZEmyje.jpg)
![](http://i.imgur.com/B7kLhig.jpg)

인증 후 저장하면 비목등록화면으로 연결됩니다.

승인번호를 알 수 없는 경우-목록조회방법
전자세금계산서 내역 조회 페이지로 이동 후 목록
발생일자를 조회하고 전자세금계산서 접수확인목록을 확인하여 상세조회 -> 저장 후 사용등록화면으로 이동

![](http://i.imgur.com/jh3JTxl.jpg)
![](http://i.imgur.com/SPWgu1q.jpg)
![](http://i.imgur.com/moeUtLo.jpg)
![](http://i.imgur.com/IkzngBA.jpg)

<a name="사용등록-전자세금계산서-증빙서류 관리"/>
##### 사용등록-전자세금계산서-증빙서류 관리 #####
사용용도 선택 & 증빙서류 업로드

세목/세세목/품목 입력 후 증빙서류 미등록 항목 클릭 -> 추가 클릭

![](http://i.imgur.com/zF4DnWF.jpg)
![](http://i.imgur.com/oRYP2QZ.jpg)

업로드 후 저장하기 클릭
![](http://i.imgur.com/o2HVAvZ.jpg)

증빙서류 등록 결과
![](http://i.imgur.com/gmp6qSs.jpg)

<a name="사용등록-전자세금계산서-계좌이체"/>
##### 사용등록-전자세금계산서-계좌이체 ####
![](http://i.imgur.com/rbBAB26.jpg)

<a name="사용등록-전자세금계산서-기자재 구입 예시"/>
##### 사용등록-전자세금계산서-기자재 구입 예시 ####
![](http://i.imgur.com/hKSHbF1.jpg)

<a name="사용등록-카드"/>
#### 사용등록-카드 ####
![](http://i.imgur.com/gqOWfed.jpg)

카드결제일 전까지는 RCMS에 등록해야 합니다.
![](http://i.imgur.com/3SWR96m.jpg)
![](http://i.imgur.com/vzLZk1v.jpg)


증빙선택에서 카드 선택 후 증빙등록을 클릭합니다.

카드 선택
![](http://i.imgur.com/6uGio3d.jpg)

사용일자 조회
![](http://i.imgur.com/bZyEGnF.jpg)

사용내역 조회
![](http://i.imgur.com/EkEcgqd.jpg)
![](http://i.imgur.com/dgswqTN.jpg)

전자세금계산서보다 간단하지만 혹시 부가세와 공급가액이 분리되어 있지 않으면 조정을 해야 합니다.
![](http://i.imgur.com/Wg5Zpgt.jpg)

<a name="사용등록-카드-증빙서류 관리"/>
##### 사용등록-카드-증빙서류 관리 #####
![](http://i.imgur.com/tojKUjb.jpg)

증빙 가이드라인을 확인해 연구비에서 누락되지 않게 주의합시다.

<a name="사용등록-카드-연구활동비 사용 예시"/>
##### 사용등록-카드-연구활동비 사용 예시 #####
![](http://i.imgur.com/TWIbmlu.jpg)

<a name="사용등록-기타"/>
#### 사용등록-기타 ####
![](http://i.imgur.com/3X2Ie1r.jpg)
![](http://i.imgur.com/DYHTa3b.jpg)

![](http://i.imgur.com/oiQZDq5.jpg)

기타 증빙은 비목등록정보 화면으로 바로 연결됩니다.
![](http://i.imgur.com/qJ5lsMB.jpg)
![](http://i.imgur.com/c55AcVu.jpg)

<a name="사용등록-기타-인건비 사용 예시"/>
##### 사용등록-기타-인건비 사용 예시 #####
자계좌이체로 인건비를 처리하는데 주목해주세요.
![](http://i.imgur.com/E9NHpbo.jpg)

<a name="사용실행"/>
### 사용실행 ###
사용등록 후 사용실행을 거친 후에야 계좌이체가 실행됩니다.
![](http://i.imgur.com/fQRCEIk.jpg)

![](http://i.imgur.com/0aduLaN.jpg)

개인공인인증서를 이용해 로그인 -> 해당 과제를 선택하고 -> 지금까지 등록된 사용요청등록을 확인 ->

![](http://i.imgur.com/WFpnKho.jpg)
![](http://i.imgur.com/pW9Ubci.jpg)
![](http://i.imgur.com/Y6cpJCE.jpg)

이제 비밀번호를 입력한 후 이체 실행을 누르면 법인범용공인인증서 입력화면이 나옵니다.

혹시 연구비사용실행 버튼이 보이지 않는다면 아래의 사례에 해당하는지 확인하세요.
![](http://i.imgur.com/73V4XOM.jpg)

### 사용결과 조회 ###
사용일자: 전자세금계산서의 경우 작성일. 카드인 경우는 승인일자. 기타의 경우는 이체일자를 말합니다.

이체일자: RCMS 연구비 사용등록후 이체실행을 완료한 일자

![](http://i.imgur.com/Dpi2Mme.jpg)
![](http://i.imgur.com/ZPEmwRY.jpg)

이제확인증 출력
![](http://i.imgur.com/enpwZKS.jpg)

### 현물사용내역 등록 ###
현물사용 유의점
![](http://i.imgur.com/z3931tF.jpg)

현물사용내역 등록
![](http://i.imgur.com/8lwGTTk.jpg)
![](http://i.imgur.com/9Ti4244.jpg)
![](http://i.imgur.com/yy81u7m.jpg)
![](http://i.imgur.com/pav2RXk.jpg)



## 연구비 복원 ##
![](http://i.imgur.com/qW1Sn0f.jpg)

연구비 사용/관리 프로세스
![](http://i.imgur.com/Bv0wNME.jpg)

연구비 복원 이유
![](http://i.imgur.com/ymBRUVV.jpg)

### 연구비 이체 취소 ###
전자세금계산서 사용 실행이후 연구비 회수가 가능함

![](http://i.imgur.com/49QHVcs.jpg)
![](http://i.imgur.com/mZl3IIy.jpg)
![](http://i.imgur.com/bx6DRqy.jpg)
![](http://i.imgur.com/ThsVodo.jpg)
![](http://i.imgur.com/Cy1G5Az.jpg)

주의
![](http://i.imgur.com/2lAB3IE.jpg)

### 연구비 일부 취소 요청 ###
부분취소는 한 건씩만 가능합니다.
![](http://i.imgur.com/OwRkYjV.jpg)
![](http://i.imgur.com/BbsAM7T.jpg)

### 연구비 카드결제 취소 ###
![](http://i.imgur.com/QEh8KkR.jpg)
#### 연구비 카드결제 취소 - 가맹점 & RCMS 취소 ####
![](http://i.imgur.com/AsZSl3n.jpg)
#### 연구비 카드결제 취소 - RCMS 등록 취소 ####
![](http://i.imgur.com/uH85HiA.jpg)
![](http://i.imgur.com/CZNrqqE.jpg)
#### 연구비 부가세 복원 요청 ####

![](http://i.imgur.com/WUD3uCi.jpg)
![](http://i.imgur.com/joenSFb.jpg)
![](http://i.imgur.com/cNRNqEV.jpg)

## 연구비 정산 ##
![](http://i.imgur.com/qhl34Or.jpg)
![](http://i.imgur.com/r7YK0TT.jpg)
### 연구비 사용 실행 조회 ###
### 연구비 증빙 문서관리 ###
![](http://i.imgur.com/AgI2GFr.jpg)

증빙파일 일괄조회
![](http://i.imgur.com/d6tT0XS.jpg)
### 증빙문서관리 활용 ###
![](http://i.imgur.com/ZsUYUqw.jpg)
### 카드사용내역 조회 ###

### 정산서류작성 ###
#### 정산서류등록 ####
정산진행상태가 아닙니다
![](http://i.imgur.com/tdsb7mm.jpg)

연구비 집행마감 진행
![](http://i.imgur.com/NONEMvp.jpg)

정산서류등록
![](http://i.imgur.com/5JO5VW7.jpg)
![](http://i.imgur.com/GSM2YKZ.jpg)
![](http://i.imgur.com/pfo9nGq.jpg)

수익금/이월등록신청
![](http://i.imgur.com/yavyKef.jpg)
사용실적보고서 조회
사용실적보고서 제출 이후에는 수정 불가

정산진행현황 조회 -> 불인전내역과 검토의견 확인 가능

![](http://i.imgur.com/juGS2PV.jpg)

연구비상시점검
![](http://i.imgur.com/XqlL3U1.jpg)
![](http://i.imgur.com/8uI9iCI.jpg)

상시점검에 입력된 파일은 정산시 따로 입력하지 않아도 됩니다.

![](http://i.imgur.com/dnFqpLX.jpg)