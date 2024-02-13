This is a translation of c standard draft 
<a href="https://www.open-std.org/jtc1/sc22/wg14/www/docs/n3096.pdf">
N3096</a>, accessed from
<a href="https://www.iso-9899.info/wiki/Main_Page">
#C on Freenode and Libera</a>, in korean.

## 프로그래밍 언어 - C
<p align=center>
  답장: <i>JeanHeyd Meneide  <&hairsp;wg14@soasis.org&hairsp;></i>
</p>
<p align=center>
  <i>Freek Wiedijk <&hairsp;freek@cs.ru.nl&hairsp;></i>
</p>    
<p align=center>
  <b>초록</b>
</p>
<p align=center>
  (본 표지는 국제표준협회에 의해 교체될 것임.)
</p>
본 문서는 C 프로그래밍 언어로 작성된 프로그램의 형태를 규정하고 어떻게 번역할 것인지를 확립하고 있음. 본 문서의 목적은 C 언어 프로그램의 이식성, 신뢰성, 유지보수성, 효율적인 실행을 다양한 컴퓨터 시스템에서 촉진시키는 것임. 

항목들에서 C 언어 자체와 C 언어를 실행할때 쓰이는 라이브러리의 세부적인 내용이 설명되어 있음. 부속서에서는 C언어와 라이브러리의 관점에서의 요약문과 C 프로그램의 이식성에 영향을 주는 요인들을 나열. 

본 문서가 C 언어를 잘아는 프로그래머와 C 언어 번역 시스템을 구현하는 프로그래머를 안내하기위한 의도로 작성되기는 했지만, 본 문서는 튜토리얼로 쓰이기 위해 설계되지는 않았음. 

본 초안의 수신자 모두는 관련된 특허 권리를 알고 있으면 증빙 서류와 이에 대한 의견을 제출할 것으로 초대됨. 

다음 문서들은 2019년 10월 미팅에서 또는 그 이전까지 본 초안에 적용된 문서들임:
DR 476     좌측값에서 volatile의 의미
