-Row 라는 위젯으로 하이트를 지정하기위해서 Container 로 감싸준다.
-Container 는 약간 무거운 느낌이고 Sizedbox는 약간 가벼운느낌
 

bottomNavigationBar: BottomAppBar(
            child: Container(
              height: 70,
              child: Row(

                mainAxisAlignment: MainAxisAlignment.spaceEvenly,
                children:[
                  Icon(Icons.phone),
                  Icon(Icons.message),
                  Icon(Icons.contact_page),
              ],
              ),
            )
              ), 
위와 같은 코드로 푸터를 코딩할 수 있다. 나중에 이 아이콘 보다 내가 쓰고싶은 이미지가 있으면 이미지로 넣을예정

width:50 이러한 느낌은 css px 단위로 고정된 값이다 이를 나중에 반응형으로 만들어야 UI적으로 모든 기기에 잘보일것같다

-안쪽여백 밑 패딩은 css랑 동일하게 모든 위아래가로세로 다 각각 지정가능
padding EdgeInset.all(20)이런식으로
fromLTRB-이걸로 개별적

-decoration:BoxDecoration 여기안에 스타일 다 지정한다 
 border 관련 css 코드 넣으면 됨

-Alignment 로 왠만한 위치 자 지정가능 

-width:double.infinty 이걸로 꽉차는 거 만들수 있다.



2강 
-flutter 객체 지향
-name 파라미터 를 생각



