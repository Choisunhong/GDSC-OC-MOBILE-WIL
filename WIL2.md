위젯- 만들고 싶은 것의 단위?

글자위젯 Text()
이미지위젯 Icon(Icons.star)
아이콘위젯 Image.asset('경로')
 - pubspec.yaml 파일에
   flutter: 
     asstes:
       - assets/ //이거하면 파일안 모든 파일읽어올수 있음
container() Container(width: 50,height: 50,color: Colors.blue,)이런식 
child 하고 위에 home 에 center(위치) 넣는다


MaterialApp 이거 넣어서 스타일 적용
 appBar: AppBar(),
        body: Container(),
        bottomNavigationBar: BottomAppBar( child: Text('aaa'),),
      ) 이렇게 나브바 푸터 적용하면됨

가로로 정렬하기
Row(childern:[])이렇게 짜면됨
세로로 정렬
Column(childern:[])이렇게 짜면됨

 home: Scaffold(
          appBar: AppBar(),
        body: Row(
          children:[
            Icon(Icons.star),
            Icon(Icons.star),
            Icon(Icons.star),
          ]

        ),
          bottomNavigationBar: BottomAppBar( child: Text('aaa'),),

      ) 이런느낌으로 짜면됨

 mainAxisAlignment- display 하는걸 정함
crossAxisAlignment-