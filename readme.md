# 정지후 202630232
## 10월 08일 
노드 삽입: 즁건에 데이터 삽입
1.새 노드 생성후 데이터에 a 입력
2.새노드(a)의 링크에 b 노드를 복사하면 a노드와 b노드 모두 c노드를 가리킴
3.b노드에 a노드 지정

노드 삭제: 데이터 삭제
1.삭제할 a노드의 링크를 바로앞 b노드의 링크로 복사시 b노드는 c노드를 가리킴
2.a노드 삭제

단순 얀걀 리스트의 일반 형태
해드(head): 첫번째 노드
현재(current): 지금 처리중인 노드
이전(pre) : 지금 처리중인 노드의 바로 앞 노드

배열에 저장된 데이터 입력 과정 
1.빈노드 생성 head = Node()
2.데이터 입력 data Array[0]
3.첫 번째 노드를 해드(head)로 지정 node
4.노드를 메모리에 삽입 memory.append(node)

1.기존 노드를 임시 저장 pre = node
2.빈 노드 생성 Node()
3.데이터 입력 node.data = data
4.이전(pre)의 링크 새노드에 대입 preNode.link = node
5.새노드를 메모리에 삽입 memory.append(node)

노드 검색
1.현재 노드(current)를 첫번째 노드인 해드(head)를 동일 하게 한뒤 혀재 노드가 검색할 데이터인지 비교후 동일시 현재 노드 반환
2.현재 노드를 다음 노드로 전이후 검색할 데이터와 동일시 현재 노드 반환

원형 연결 리스트 
 시작 위치와 다음유ㅣ치가 계속 이어진 후 마지막에 다시 시작으로 돌아오는 형태.

-단순 연결 리스트와 구조가 같으나 처음 데이터를 마지막데이터가 링크를 가지고 있다는 차이점이 있음

노드 삽입: 중간에 노드 삽입
1.새노드 생성 
2.링크 수정




## 9월10일(1주차)
강의 내용 정리


# html의 h1부터 h6의 크기
# h1 크기
## h2 크기
### h3 크기
#### h6 크기
*이텔릭체*

**볼드체**

***볼드+이텔릭체***

~~취소선~~

---

1. 사과
2. 배
3. 감

* 사과 
    * 작은 사과
    * 맛있는 사과 
        * 사과
* 배
* 감

## 코드 불럭
```python
fruits = ["apple", "banana", "cherry"]

for f in fruits:
    print(f)



```java
public class HelloWorld {
    public static void main(String[] args) {
        // 화면에 문장을 출력합니다
        System.out.println("Hello, Java!");
        
        int age = 20;
        String name = "홍길동";
        
        System.out.println(name + "의 나이는 " + age + "살입니다.");
    }
}

```
문장 중에 `ctrl` 키가 나오면,,

## 링크
[구글 바로가기](https://google.com "alt 옵션")
[내부 링크](#정지후-202630232)

## 이미지 삽입 
![구글 로고](images.png "images.png")

# datastructuregit
