# IOS-Summary-Book

안녕하세요. 노력하는 IOS 개발자 손태일 입니다. :)

Notion : https://www.notion.so/Son-TaeIl-370a8c79f1874074b94e9821e590a9a0 

포트폴리오 : https://drive.google.com/file/d/13OWAXnMPQNXrfBMzAb07v-4uTTAc7dSQ/view

// -----------------------------------------------------------------------------			      
   
   			 

#  지식 한입    

기본 알아둬야할 상식

### 1. Bounds 와 Frame 의 차이점은?
> Frame은 SuperView 기준의 자표, Bounds는 자신을 중점으로한 좌표   


### 2. 실제 디바이스가 없을 경우 개발 환경에서 할 수 있는 것과 없는 것은?
> 가속도, GPS 등의 센서 기능 이용, 카메라, 마이크, 푸쉬, CPU 메모리 테스트 등


### 3. 앱의 콘텐츠나 데이터 자체를 저장/보관하는 특별한 객체를 무엇이라 할까?
> Core Data - 데이터를 유지 또는 캐시하고 실행 취소를 지원하는 프레임워크, 영구 데이터 저장, 
즉 데이터 베이스 기능은 Core Data 기능의 일부분으로 데이터 베이스 기능을 포괄하는 프레임워크이다.


### 4. App thinning이란? 
> 애플리케이션이 디바이스에 설치될 때, 앱 스토어와 운영체제가 디바이스의 특성에 맞게 설치되도록 하는 설치 최적화 기술을 말함,       			  
https://ttuk-ttak.tistory.com/42


### 5. NSOperationQueue 와 GCD Queue 의 차이점은?
> 확인 : https://www.zehye.kr/ios/2020/04/23/11iOS_GCD_NSOperation_queue/


### 6. Foundation Kit은 무엇이고 포함되어 있는 클래스들은 어떤 것이 있을까요?
> Foundation Kit은 Cocoa Touch framework에 포함되어 있는 프레임워크 중 하나입니다. String, Int 등의 원시 데이터 타입과 컬렉션 타입 및 운영체제 서비스를 사용해 앱의 기본적인 기능을 관리하는 프레임워크이다.


### 7. Delegate란 무언인가 설명하고, retain 되는지 안되는지 그 이유는?
> 객체가 모든 일을 처리하는 것이 아니라 처리해야 할 일 중 일부를 다른 객체에 넘기는 것 (위임), 순환참조(두 객체가 서로 잡고있어 하나가 사라지려고 할 때 다른 한 쪽이 잡고 있으면 사라지지 않는 현상)에 의한 메모리 누수가 발생할 수 있다. (Retain Cycle)


### 8. 뷰의 위치나 크기를 재조정하려면 어떻게 해야할까?
> viewWillLayoutSubviews() : 뷰의 bounds가 변경되면, 뷰는 하위뷰의 레이아웃을 변경해야 하는데 그 작업을 하기전에 호출됨.     
> layoutSubViews() : 여기서 서브 뷰의 레이아웃을 조정      
> viewDidLayoutSubviews() : 뷰의 bounds가 변경시 서브뷰들의 위치를 조정하고 나서 그 때 시스템이 이 메서드를 호출, 그러나 일반적으로 서브 뷰의 개별 레이아웃이 조정되기만 했을 때는 호출 안됨


### 9. UIWindow 객체의 역할?
> 뷰들을 담는 컨테이너 역할.
![image](https://user-images.githubusercontent.com/47170564/133933273-d00b2203-0e1b-4576-8157-e9135a8ad844.png)


### 10. setNeedsLayout와 setNeedsDisplay의 차이는? 
> setNeedsLayout()메소드는 모든 핸들러가 종료되고 권한이 main run loop로 돌아오는 시점에 view의 position이나 layout에 관한 변화를 적용시키고 setNeedsDisplay()메소드는 다음 드로잉 사이클이 오면 그 때 쌓여있는 그려야할 컨텐츠들을 동시에 적용시킨다.
 
	
### 11. 다크모드를 지원하는 방법은?
> System Color를 쓴다 / Custom Color Set을 직접 만든다


### 12. NSCache와 딕셔너리로 캐시를 구성했을때의 차이는?
> 정리중


### 13. URLSession에 대해 설명하라
> 정리중



