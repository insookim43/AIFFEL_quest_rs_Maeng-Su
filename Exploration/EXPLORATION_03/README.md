- 코더 : 맹성찬
- 리뷰어 : 염철헌


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - np.where 조건문을 활용하여 고양이 수염만 남기는 부분을 작성하였고, 이를 통해서 성공적인 사진을 남김
        - ![1](/Exploration/EXPLORATION_03/review/1.png)
        - ![2](/Exploration/EXPLORATION_03/review/2.png)
    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 핵심적인 파트인 cv2.addweighted를 활용해 두 사진을 겹치는 작업을 수행
        - ![3](/Exploration/EXPLORATION_03/review/3.png)
        
- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 여러 각도에서 실험하였음
        - ![4](/Exploration/EXPLORATION_03/review/4.png)
        
- [X]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 회고를 작성하면서 돌아보는 작업 수행
        - ![5](/Exploration/EXPLORATION_03/review/5.png)
        
- [X]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 함수를 활용해서 정의함
        - ![6](/Exploration/EXPLORATION_03/review/6.png)


# 회고(참고 링크 및 코드 개선)
```
# 다시 성찬님이랑 하게 되었는데, 지난번에 비해서 서로 소통이 원활했음
# 서로 cv2.addweighted를 구현한 점은 같았으나, 마스크를 적용하는 데 있어 코드 구현한 부분이 나보다 훨씬 간결했던 것을 알게되어 만족스럽다.
```
