## 상황

이 애플리케이션의 이름은 "랜덤문장" 입니다.  
이 앱의 메인 화면에는 랜덤한 문장이 FlatList에서 랜더링 되고 있습니다.  
당신의 임무는 이 리스트에 텍스트 검색 기능을 넣는 것입니다.  

## 명세서

검색창에 검색어를 입력시 리스트에서 매칭되는 문자들을 찾습니다.  
검색이 완료되었다면, 첫번째로 매칭된 문장으로 자동 스크롤 하세요. (애니메이션으로 스무스한 이동)  
0/0은 {현재 순서}/{매칭된 갯수} 를 의미합니다.  
"다음" 버튼을 누르면 다음 위치로 이동해야합니다. (애니메이션으로 스무스한 이동)  
"이전" 버튼을 누르면 다음 위치로 이동해야합니다. (애니메이션으로 스무스한 이동)  

## 조건

1. FlatList를 제외한 프로젝트 내 모든 코드를 수정할 수 있습니다.
2. 라이브러리 사용이 가능합니다.
3. 아이템 컴포넌트 하나하나가 무겁다는 가정을 둡시다. FlatList의 아이템을 한번에 너무 많이 랜더링 하지 마세요.

## Situation

The name of this application is “Random Sentence”.  
On the main screen of this app, random sentences are rendered in FlatList.  
Your task is to add text search functionality to this list.  

## Specification

When you enter a search term in the search box, matching characters are found in the list.  
Once the search is complete, automatically scroll to the first matched sentence. (Smooth movement with animation)  
0/0 means {current order}/{number of matches}.  
When you press the “Next” button, you should move to the next location. (Smooth movement with animation)  
When you press the "Previous" button, you should go to the next location. (Smooth movement with animation)  

## Condition

1. All code in the project except FlatList can be modified.
2. The library can be used.
3. Let’s assume that each item component is heavy. Avoid rendering too many FlatList items at once.
