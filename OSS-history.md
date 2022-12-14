<h1>OSS 역사와 개요</h1>

## 📚 OSS(Open Source Software)
📌 라이선스에 따라 소스 코드가 공개되어 누구나 자유롭게 사용하고 수정하거나 재배포할 수 있는 소프트웨어입니다.  

## 📚 OSD 10대 기준
📌 공개 소프트웨어를 상호 관리 감독하며 지속적으로 발전할 수 있도록 참여자들이 지켜야 하는 기준입니다. 아래에 그 내용이 있습니다.

* 자유 재배포(Free Redistribution)
* 소스 코드(Source Code) 공개
* 2차적 저작물(Derived Works) 배포 허용
* 원저작자 소스 코드 수정 제한(Integrity of The Author’s Source Code)
* 사용 대상 차별 금지(No Discrimination Against Persons or Groups)
* 사용 분야 제한 금지(No Discrimination Against Fields of Endeavor)
* 라이선스 배포(Distribution of License)
* 특정 제품 의존성 금지(License Must Not Be Specific to a Product)
* 다른 라이선스 포괄적 수용(License Must Not Contaminate Other Software)
* 라이선스 기술 중립성(License Must be Technology-Neutral)

## 📖 OSS history

### 1970s

* 소프트웨어 개발이 일부 해커들의 전유물이던 시절에는 소프트웨어를 서로 댓가 없이 복사해서 사용했습니다. 기업도 마찬가지로 소프트웨어를 무료로 배포하였고, 사용자들이 수정하고 복사하도록 허용했습니다.

### 1980s

> 1970년대 이후 소프트웨어 산업의 상업화로 인해 자유 소프트웨어 인식이 점차 사라질 위기에 처하기 시작했습니다. 프로그래머였던 Richard Matthew Stallman(리차드 스톨만)은 소프트웨어를 공공영역으로 인식했습니다. 그리고 소스코드는 컴퓨터 과학을 발전시키는 데 기본이며, 변화가 계속되고, 발전하기 위해서는 소스코드를 자유롭게 사용할 수 있어야 한다고 생각했습니다. 이러한 계기로 ***GNU Project***가 시작되었고, 밑에서 자세하게 설명 할 것입니다.

<img src="https://user-images.githubusercontent.com/65354879/193526751-90d71631-bc3a-47b3-a666-ea9beeb00e67.png" width="100" height="100"/>

> GNU Project의 마스코트 🐃 [^1] 

[^1]: Gnu가 소과 포유류의 총칭.

* 1983 : Richard Matthew Stallman에 의해 ***GNU Project***가 시작되었습니다. Richard Matthew Stallman은 첫 선언문에 이은 "GNU 선언문"을 비롯한 여러 글들을 통해서, "초기 전산 공동체에 지배적이었던, 협동 정신을 되돌리자"라고 주장했습니다.

* 1985 : Richard Matthew Stallman은 GNU 프로젝트를 철학적, 법률적, 금융적으로 지원하기 위해 자선단체인 자유 소프트웨어 재단(FSF, Free Software Foundation)을 설립하였습니다. 프로젝트의 대부분은 자원 봉사자들이 개발했습니다. GNU가 이목을 끌어, 이를 주목한 회사들은 GNU 소프트웨어의 개발이나 판매 및 기술 지원을 돕기 시작했습니다.

### 1990s

> Linus Torvalds(리누스 토발즈)는 당시 자신이 보유하고 있던 인텔 80386 기반의 IBM 호환 PC에서도 Minix[^2]가 구동되기를 원했습니다. 이를 계기로 그는  Minix를 참고한 새로운 오픈소스 운영체제를 개발하였고, 그 운영체제를 밑에서 자세하게 설명 할 것입니다.
[^2]: Unix 계열 운영 체제 중의 하나로, 명칭은 미니멀(minimal)과 유닉스(Unix)로부터 비롯됨.

<img src="https://user-images.githubusercontent.com/65354879/193561563-e8e1dadb-d634-41ad-8486-a29ff7e61980.png" width="100" height="100">

> Linux Kernel 마스코트인 Tux(펭귄) 🐧

* 1991 : Linus Torvalds에 의해 Minix를 참고하여 개발한 오픈소스 운영체제인 ***Linux***가 개발되었습니다. 이를 1991년 8월에 자신이 활동하던 유즈넷의 뉴스 그룹 네트워크에 처음 공개했습니다. Linus Torvalds가 최초 공개한 ***Linux Kernel***[^3]의 첫 번째 버전(0.01)은 약 1만줄 정도의 코드로 이루어져 있었습니다. 하지만 이를 보고 흥미를 느낀 개발자들이 프로젝트에 참가하여 힘을 보태었고, 불과 1년 후에는 4만줄 정도로 규모가 커졌습니다.

[^3]: Kernel 이란 컴퓨터 운영 체제의 핵심이 되는 컴퓨터 프로그램으로, 시스템의 모든 것을 완전히 통제함.

* 1994 : ***GNU Project***에서 ***Linux Kernel***을 채택하고, ***GNU/Linux***로 명명되었습니다. ***Linux Kernel*** 그 자체만으로는 시스템을 구성 할 수 없기 때문에, ***GNU/Linux*** 에서 기타 프로그램 제작에 큰 기여를 하였습니다. 그리고 이것이 전세계 개발자들이 자유롭게 Linux 개발에 참여할 수 있는 토대가 마련되어, 마침내 1994년 3월에 첫 번째 완성 버전인 Linux Kernel 1.0.0이 공개되었습니다. 그 이후 RedHat, Debian 등 다양한 배포판이 등장하였습니다. 그로 인해 리눅스의 보급으로 자유소프트웨어 운동이 확산됐습니다.

* 1997 : 1997년 봄에 자유 소프트웨어 공동체 리더 모임이 캘리포니아에서 있었습니다. 이 모임에서 Tim O'Reilly(팀 오라일), Larry Augustine(래리 어거스틴), Eric Steven Raymond(에릭 스티븐 레이몬드)가 오픈소스 소프트웨어 대해 논의하였습니다. 그 후 Bruce Perens(브루스 페런스)는 [OSD(Open Source Definition)](#OSD-10대-기준)을 만들었습니다. ***그쯤에 자유소프트웨어라는 용어에서 오픈소스 소프트웨어로 용어가 변경되었습니다.***


## 📌 OSS 현황


* 2020년 오픈소스 SW(OSS) 시장 동향 조사보고서에 따르면 국내에서 오픈소스 기술 기반 사업을 운영하는 기업들의 매출의 총 규모는 2,843억원이었습니다.  
* 1천여개 기업에게 설문 조사한 결과 국내기업의 OSS 활용률은 58.8%로 2018년부터 꾸준히 증가 중입니다. 대부분 인프라를 구축할 때 오픈소스 기술을 활용하고 있다고 응답했습니다.  

* 하지만 오픈소스 기술을 이용한다고 소스코드를 공개에 적극적인 것은 아닙니다. 설문조사에 참여한 기업 중 소프트웨어 직접 개발하고 있는 곳은 417개였는데 이중 소스코드를 오픈소스 형태로 공개한 곳은 84개였습니다. 소스코드를 공개하더라도 응답자 58%는 고객사에게만, 41%는 기업 내부에만 공개했고, 커뮤니티에 공개하는 비율은 38%였습니다.

* 공개한 이유는
'외부 개발자의 집단지성을 SW 개발에 활용하기 위해서'와 ‘자사 SW를 판매하기 위한 전략적 목적에서’라는 응답이 가장 많이 나왔습니다.

* 공개 안 한 이유는
‘보안, 기밀 등의 문제 때문’과 ‘소스코드 공개에 소비되는 시간과 노력이 부담되기 때문’이 가장 높았습니다.

* 개인 개발자 측면에서 살펴보면 2020년 기준 깃허브 내 한국 개발자 계정 수는 2만2400여개로 전 세계 깃허브 계정 중 0.06%에 해당하는 수치입니다.

<img src="https://user-images.githubusercontent.com/110793635/193616789-e27f0efd-aae4-4d7c-9a08-b923d9747f26.png" alt="2020년 개발자 소속 현황"  width="300" height="300">

* 마지막으로 기술적으로 분석했을 때 한국 개발자들이 많이 사용하고 있는 오픈소스 프레임워크/라이브러리는 스프링과 노드JS이며, 향후 배우고 싶은 리액트JS, 노드JS, 텐서플로우가 뽑혔습니다. 이런 동향은 해외에도 비슷해서 위에서 언급한 보고서나 자료에 따르면 해외에서 최근 인기 있는 오픈소스 기술들은 주로 인공지능, 클라우드, 자바스크립트, 프로그래밍 언어(파이썬, 러스트) 등이 포함됐습니다.

* 위의 결과들을 종합해봤을 때 한국 내 오픈소스 시장은 관련 참여자가 다양해지고 성장하고 있지만 한편으로 발전해야 할 부분도 존재합니다. 특히 오픈소스 기반 스타트업이나 관련 투자 생태계가 다른 국가보다 부족합니다. 오픈소스 기술 도입으로 얻는 효과에 대해서도 비용 절감이나 신기술 도입 창구로 좁게 인식하는 점도 아쉽습니다. 해외 기업들은 그 외에도 실력 있는 개발자들을 스카웃하거나 개발자들의 직업 만족도를 높이려는 도구로 오픈소스를 활용하거나 내부 기술력을 높이거나 기술 교육 용도로 오픈소스 기술을 바라보고 있습니다.  


* ### 현재로서는 Git과 Github :octocat: 를 통하여 서로 소스코드를 공개하고 협업하여 오픈소스 소프트웨어의 발전을 돋구고 있습니다.

## 📌 대표적인 OSS 

### 🐧 Linux

---
* OSS history 에서도 주력으로 다루어 얘기하였던 리눅스입니다. 사실상 "***오픈소스***"의 시초가 되는 격이라고도 볼 수 있습니다. 

* 다음 사진은 리눅스의 배포판의 종류들입니다. 매우 많은 것을 확인할 수 있고, 해당 사진이 리눅스 배포판의 전부는 아닙니다. 훨씬 더 많습니다.

<img src=https://user-images.githubusercontent.com/65354879/202909207-3d439994-b43e-4814-9531-e8134ff82ea5.png height=350 weight=350>

* 특히 리눅스는 서버(server) 영역과 임베디드(embedded) 시스템 영역에서 막강한 영향력을 가지며 모바일 운영체제와 최근에는 데스크탑 운영체제로도 주목을 받고 있습니다. 개인 PC용으로는 우분투(ubuntu)와 민트(Mint)가 널리 알려져 있으며, 소형 임베디드 시스템에서 상대적으로 가벼운 데비안(Debian)이 많이 사용됩니다. 

* github에 리눅스 커널에 대한 소스코드가 오픈되어 있습니다[^4]. ~~리눅스 커널의 아름다운~~ 소스코드를 확인하여 보세요.

[^4]: https://github.com/torvalds/linux 

### 🆚code
---
<img src=https://user-images.githubusercontent.com/65354879/203024906-d75451e1-5be2-441a-97f4-47a5d7050451.png height=200 weight=200>    

> vscode의 공식 로고

* vscode는 Visual Studio Code의 줄임말이며, 마이크로소프트에서 개발하여 2016년에 출시한 ~~고급 메모장~~ IDE입니다. vscode는 기본적으로 JavaScript, TypeScript, Node.js를 지원하며, 다양한 확장(extension)을 통해 다른 언어(C, C++, C#, Java, Python, PHP, Go 등)나 런타임(.NET, Unity 등)을 지원하도록 설정할 수 있습니다. 

* vscode는 오픈소스 소프트웨어로, github에 공식적으로 소스 코드가 공개되어 있습니다[^5].

[^5]: https://github.com/microsoft/vscode

### 📌 react
---
<img src=https://user-images.githubusercontent.com/65354879/203027044-1d3b3636-f39c-4421-b283-7dcf26089ddf.png weight=170 height=170>

> react의 공식 로고

* react는 페이스북에서 개발한 View단을 컨트롤하는 라이브러리 입니다. 쉽게 말하자면 UI 개발을 위한 javascript 라이브러리이며, 자세한 내용은 공식 홈페이지를 통해 확인하실 수 있습니다[^6].

*  react는 2011년도에 라이브러리 개발을 하였고, 2012년에 instagram에 반영하였습니다. 그리고 2013년 5월 열린 JSConf US에서 오픈소스화 되었습니다. vscode와 마찬가지로 github에 코드가 공개되어 있습니다[^7].

> 라이브러리 : 단순하게 활용 가능한 도구들의 집합입니다. 개발 주도권을 사용자가 가지고 있어, 사용자가 전체적인 흐름을 만들며 라이브러리를 가져다 쓸 수 있습니다.

[^6]: https://ko.reactjs.org/
[^7]: https://github.com/facebook/react

### 🤖 tensorflow

<img src=https://user-images.githubusercontent.com/65354879/203085483-14f7ebf2-3b6a-4bd4-afa5-72022f2fe931.png height=150 weight=150>

> tensorflow의 공식 로고

* tensorflow는 구글에서 만든 머신러닝을 위한 오픈소스 소프트웨어 파이썬 라이브러리입니다. 

* Define and Run 방식이며, 그래프를 먼저 정의하는 방식을 채택하고 있습니다.

* tensorflow는 github 계정을 통해 소스코드를 공개해놨습니다[^8].

[^8]: https://github.com/tensorflow/tensorflow

### 🔥 pytorch

![image](https://user-images.githubusercontent.com/65354879/203093309-334f3dca-0776-4a4d-9416-f933e412fc5a.png)

> pytorch의 공식 로고

* pytorch는 FAIR(Facebook AI Research)에서 만든 오픈 소스 머신러닝 라이브러리입니다.

* Define by Run 방식이며, 실행하면서 그래프를 그리는 방식을 채택하고 있습니다. tensorflow와 목적은 비슷하지만 다른 작동 체계를 가집니다.

* pytorch는 github 계정을 통해 소스코드를 공개해놨습니다[^9].

<br>
<br>

[^9]: https://github.com/pytorch/pytorch

출처
>https://www.oss.kr/oss_guide/show/f74f64ae-767b-4667-96bf-8a0dc8ab0082

>https://www.nipa.kr/main/selectBbsNttView.do?key=112&bbsNo=8&nttNo=7835&bbsTy=bbs

>https://it.donga.com/19504/

>https://www.nepla.net/post/%EC%98%A4%ED%94%88%EC%86%8C%EC%8A%A4-%EC%86%8C%ED%94%84%ED%8A%B8%EC%9B%A8%EC%96%B4%EC%9D%98-%EC%97%AD%EC%82%AC

>http://terms.tta.or.kr/dictionary/dictionaryView.do?word_seq=051008-7



