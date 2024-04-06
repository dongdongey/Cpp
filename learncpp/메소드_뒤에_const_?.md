# 메소드 뒤에 const ?

```cpp
class someClass{
		int a,b;
		
		int sum(){
				return a+b;
		}
		int csum() const{
				return a+b;
		}
}
```

이렇게 메소드 뒤에 const가 써있어서 반환값이 const라는 것도 아니고 대체 무슨 뜻 일까?

메소드 뒤에 붙는 cosnt는 현재 객체를 수정하지 않는다느 뜻이란다.

그러므로, 당연히 메소드가 아닌 일반 함수는 뒤에 const가 붙지 않는다.