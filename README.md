# omeka 소개
오메카는 로이 로젠웨이그 센터(Roy Rosenzweig Center)에서 개발하여 2008년 2월 21일 출시되었다. 이 소프트웨어는 온라인 디지털 컬렉션을 위해 무료로 제공되는 오픈소스 콘텐츠 관리 시스템이다. 웹 어플리케이션으로서 역사 문화 컬렉션 출간 및 전시를 기본 목적으로 하며, 이용자가 기능성을 확장할 수도 있다. 오픈소스 소프트웨어인 디스페이스(Dspace)와 페도라(Fedora)는 학위논문이나 출판 전 논문, 회색문헌 등 도서에 초점이 맞추어져 있으므로 기록에 대해 충분히 기술할 수 없다. 이에 비해 오메카는 전시 기능에 초점을 맞추고 있으며, 더블린코어를 이용하여(이보람 등, 2014, pp. 202-203) 기록에 대해 충분히 기술할 수 있는 장점이 있다. 

오메카와 비슷한 오픈소스 소프트웨어로는 전통적으로 이용되어온 디스페이스와 페도라가 있다. 디스페이스는 MIT(Massachusetts Institue of Technology)에서 개발된 오픈소스 소프트웨어로 이미 대중성이 높고 미국 내 기관 레포지토리를 운영하는 대학들 간에 가장 많이 사용되는 시스템이다(Markey et al., 2007; 김지현, 2010에 서 재인용). 디지털 형태로 작성된 저널 논문, 학회 논문, 책, 기술 보고서 등을 등록할 수 있다. 디스페이스는 3단계의 수직적인 계층구조를 제공한다. 접근에 대한 제어에 있어서는 사용자들을 특정 그룹에 소속시키고, 컬렉션과 아이템에 대해 그룹의 접근제한 여부를 설정할 수 있는 구조를 가지고 있다. 페도라는 1997년에 코넬 대학교에서 개발되었으며, 현재 비영리 목적의 듀라스페이스의 후원을 받고 있는 오픈 소스 소프트웨어이다. 디지털 객체 리포지터리로 설계되었으며, 디지털 텍스트, 출판, 사진, 비디오 등을 등록할 수 있다. 확장성이 강하고 유연한 기능을 가지고 있다. 하지만 인터페이스가 불편하여, 다른 프로그램에 비해 상대적으로 복잡하다. 계층구조에 있어서 수직적인 계층구조가 아니라 개체 간 관계를 설정할 수 있도록 제공한다. 또한 사용자 인터페이스를 구축하는데 있어서는 다른 소프트웨어에 비해 높은 수준의 커스터마이징이 요구되어, 관리자가 웹 프로그래밍에 대한 전문 지식이 필요하다.

오메카는 상대적으로 간단하게 설치하고 사용할 수 있다는 장점을 가진다. 또한 게시된 디지털 객체는 접근 제어없이 누구나 접근할 수 있다. 인터페이스를 사용하는데 있어서도 관리자 페이지를 제공하며 해당 페이지에서 아이템, 컬렉션, 사용자 그룹 관리 등의 기능을 수행할 수 있다(이종덕 외, 2013). 즉, 오메카는 디스페이스나 페도라에 비해 같은 오픈소스 소프트웨어라도 관리가 쉽고 직관적인 인터페이스를 제공하기 때문에 이용자에게 별다른 설명 없이도 아카이브를 이용하는 데 큰 어려움이 없다. 

출처:  오픈소스를 이용한  부산항 사진  아카이브의 구축 방안 , 132-133.

[Omeka.org의 문제점] 

 1. Exhibit builder 플러그인 에러 (가장 심각)

- v3.0 활성화시 전시 생성 메뉴가 없음
- v2.2 활성화시 사이트 다운됨 (다른 플러그인을 ‘0’으로 설정하여 꺼놓으면 해결됨)
- v2.2 활성화되더라도 Add Exhibit > Add Page 실행시 에러 발생 (Mysqli prepare error: Unknown ‘layout’ in ‘field list’) 
- v2.2에서 ‘section’생성이 안됨. (Exhibit > Section > Page 개념대로 전시를 만들 수 없음 

2. 각종 플러그인 에러 

- CSV importer, EAD importer, OAI-PMH 등 각종 플러그인들이 2.0 compatible이라고 명시되어 있음에도 에러 발생함 
- 에러 해결을 위해 서버 세팅에 시간이 많이 소요됨 

3. 플러그인 부족 

- Omeka 2.0 이상 버전을 지원하는 플러그인의 수가 많지 않음 

4. 테마 부족

- Omeka 2.0 이상 버전을 지원하는 테마 수가 제한적임 

5. 커스터마이징 필요 

- 테마 부족으로 완성도 있는 전시를 만들려면 디자인 커스터마이징 필요함 
- 플러그인 부족으로 특정 기능 구현을 위한 기능 커스터마이징이 필요함 

[Omeka.net의 문제점]

1. 섹션명(영문)을 변경할 수 없음 (Browse item, Browse collection, Browse Exhibits 영문명을 사용해야 함) 

2. 테마 제한적 (5만원/1년 플랜 가입시 테마 추가됨, 더 비싼 플랜도 있으나 제공테마는 동일함) 

3. 커스터마이징 제한적 (omeka 서버를 사용하므로)

출처: 기록관리공개소프트웨어포럼 http://osasf.net/
