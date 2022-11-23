# OSS-저작권

## 공개 SW[^1] 와 라이선스
### 공개 SW는 소스가 공개되어 사용, 복제 , 배포 , 수정 할 수 있지만, 원 저작자의 라이선스 규칙을 따라야 합니다.
> 공개 SW 라이선스란 OSS 개발자와 이용자 간의 사용 방법 및 조건의 범위를 명시한 계약을 말합니다.  
> 따라서 공개 SW를 이용하려면 공개SW 개발자가 만들어놓은 조건의 범위에 따라 해당 소프트웨어를 사용해야 합니다.  
> 이를 위반할 경우에는 라이선스 위반 및 저작권 침해로 이에 대한 법적 책임을 져야 합니다.

## SW 라이선스 분류
![image](https://user-images.githubusercontent.com/110793635/202849234-05d79696-15f9-4106-8cda-35931d0988c6.png)

## 소스코드 공개 여부에 따른 라이선스 비교
|구분|무료 라이선스|유료 라이선스|
|------|---|---|
|공개|대부분 OSS(Apache, Tomcat, JBoss|일부 배포판 OSS (Red Hat, MySQL)|
|비공개|Freeware(Winzip, RealAudio)<br>Shareware(초기에만 무료)<br>Adware(JetAudio)|상용 비공개 소프트웨어<br>(MS Office, Oracle, Shareware)|

## 주요 공개 SW 라이선스
### GPL
![image](https://user-images.githubusercontent.com/110793635/202886481-0fea547d-c01b-467b-aad2-1d0af07afa39.png)

> GPL(General Public License)은 소스코드 공개에 대한 해석이 까다로운 라이선스 중 하나입니다.  
> GPL의 소스코드 전체 혹은 일부를 사용했거나, 소스코드가 아닌 형태를 결합/연결했다면  
> 어디부터 어디까지 소스코드를 공개를 해야 하는지 의문이 발생합니다.  
> 우선 소스코드 공개 의무가 발생하려면 물리적인 프로그램의 이동인 '배포'가 발생해야 합니다.  
> 단순히 GPL 프로그램을 내부적으로 사용할 경우에는 소스코드 공개 의무가 발생하지 않습니다.  
> 또한 GPL 프로그램을 서버에 저장하고 네트워크 통신 형식으로 서비스만 제공한다면  
> GPL에 따른 소스코드 공개 의무는 발생하지 않습니다.  
> > 결론적으로 GPL 프로그램의 결과물이 GPL의 코드 일부 혹은 전체를 포함하는 프로그램이거나  
> > GPL 프로그램의 일부로 구성되는 경우에는  그 결과물에 GPL 라이선스가 적용될 수도 있지만  
> > 이러한 경우는 드물게 발생하는 만큼 프로그램이 생성하는 결과물에 GPL 라이선스가 적용되지 않는 것으로 이해하면 됩니다.

### LGPL
![image](https://user-images.githubusercontent.com/110793635/202886543-e49f32c1-9965-4f4e-acf6-beef7b22ba94.png)

> LGPL(Lesser General Public License)은 GPL보다는 훨신 완화된 조건의 공개 소프트웨어 라이센스입니다.  
> 가장 큰 차이점은 LGPL 코드를 정적(static) 또는 동적(dynamic) 라이브러리로 사용한 프로그램을 개발하여  
> 판매/배포할 경우에 프로그램의 소스코드를 공개하지 않아도 된다는 점입니다.  
> LGPL 코드를 사용했음을 명시만 하면 됩니다.  
> > 단, LGPL 코드를 단순히 이용하는 것이 아니라 이를 수정하거나  
> > 이로부터 파생된 라이브러리를 개발하여 배포하는 경우에는 전체 코드를 공개해야 합니다.
### MPL
![image](https://user-images.githubusercontent.com/110793635/202886655-9d8c37f3-c9d4-4c7b-a2c7-14215203b22d.png)

> MPL(Mozilla Public License)는 BSD License와 GPL의 혼합적 성격을 띠고 있습니다.  
> MPL의 소스코드 공개의무는 파일 단위로 적용됩니다.  
> 만약 MPL의 소스코드 수정 시 수정한 파일 단위의 소스코드 공개 및 수정 내용, 날짜 등에 대한 고지를 해야 합니다.  
> 따라서 MPL의 라이브러리를 수정했다면 수정한 파일 단위의 소스코드 공개 및 수정 내용, 날짜 등에 대한 고지를 진행해야 합니다.  
> 즉 MPL의 파일의 수정이 아니라면 MPL은 적용되지 않습니다.

### BSD
![image](https://user-images.githubusercontent.com/110793635/202886767-cf64d525-855b-4fc7-b013-b7d04c46dfab.png)

> BSD(Berkeley Software Distribution) license는 SW license라고도 할 수 없을 만큼 미약합니다.  
> 해당 SW는 아무나 개작할 수 있고, 수정한 것을 제한 없이 배포할 수 있습니다.  
> 다만 수정본의 재배포는 의무적인 사항이 아니므로 BSD license를 갖는 프로그램은 상용 SW에서도 사용할 수 있습니다.  
> 이것이 GPL과의 가장 큰 차이점인데, GPL은 파생물의 경우에도 소스 코드가 반드시 배포되도록 합니다.

### Apache
![image](https://user-images.githubusercontent.com/110793635/202886894-81373d2d-33fb-4e08-af1d-d1c6f8354b3f.png)

> Apache License는 누구나 파생된 프로그램을 제작할 수 있으며 저작권을 양도, 전송할 수 있는 규정을 의미합니다.  
> 누구든 자유롭개 Apache SW를 다운 받아 부분 혹은 전체를 개인적 혹은 상업적 목적으로 이용할 수 있으며  
> 재배포시에는 원본 소스 코드 또는 소스 코드를 반드시 포함시켜야 하는 것은 아닙니다.  
> 단 Apache License 버전 및 표기는 반드시 포함하도록 함으로써 Apache License로 개발된 것을 명확하게 밝혀야 합니다.

## 주요 공개 SW 라이선스 비교

|구분|무료 이용가능|배포<br>허용가능|소스코드<br>취득가능|소스코드<br>수정가능|2차적 저작물<br>재공개 의무|독점SW와<br>결합가능|
|:----|:------------:|:-----------:|:----------------:|:----------------:|:---------------------:|:----------------:|
|GPL|●|●|●|●|●|X|
|LGPL|●|●|●|●|●|●|
|MPL|●|●|●|●|●|●|
|BSD license|●|●|●|●|X|●|
|Apache license|●|●|●|●|X|●|

## OSS license top 20

|Rank|License|Usage|Risk|
|:---|:------|:----|:---|
|1|MIT License|32%|Low|
|2|GNU General Public License (GPL) 2.0|18%|High|
|3|Apache License 2.0|14%|Low|
|4|GNU General Public License (GPL) 3.0|7%|High|
|5|BSD License 2.0 (3-clause, New or Revised)|6%|Low|
|6|ISC License|5%|Low|
|7|Artistic License (Perl)|4%|Medium|
|8|GNU Lesser General Public License (LGPL) 2.1|4%|High|
|9|GNU Lesser General Public License (LGPL) 3.0|2%|High|
|10|Eclipse Public License (EPL)|1%|Medium|
|11|Microsoft Public License|1%|Medium|
|12|Simplified BSD License (BSD)|1%|Low|
|13|Code Project Open License 1.02|1%|Low|
|14|Mozilla Public License (MPL) 1.1|<1%|Medium|
|15|GNU Affero General Public License 3.0 or later|<1%|High|
|16|Common Development and Distribution License|<1%|Medium|
|17|Do What the Fuck You Want To Public License|<1%|Low|
|18|Microsoft Reciprocal License|<1%|High|
|19|Sun GPL with Classpath Exception 2.0|<1%|High|
|20|zlib/libpng License|<1%|Low|

[^1]: Open Source Software
