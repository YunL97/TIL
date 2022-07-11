# 20220711

- PrimarySwatch
  - App을 생성할 때 ThemeData를 통해서 전체적인 Theme을 설정할 수 있다.
  - ThemeData를 통해서 세세한 색상값을 일일이 설정 할 수 있는데 번거로운 작업임
  - PrimarySwatch 속성값을 통해 전체적인 Theme을 설정 가능, 미리 제공되는 견본색상을 뜻함

```
//material 에서사용
theme: ThemeData(
    primartSwatch: Colors.red
)
```
- 탭바에서 drawer:Drawer()
   - 탭바에서 drawer사용하면 자동으로 목록이 생성되게 해줌

- BuildContext
   - widget tree 에서 현재 widget의 위치를 알 수 있는 정보
   - 이 buildcontext는 stateless 위젯이나 state 빌드 메서드에 의해서 리턴 된 위젯의 부모가 된다.
   - 


