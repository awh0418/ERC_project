# ERC_project

## Data 
MELD: A Multimodal Multi-Party Dataset for Emotion Recognition in Conversations, ACL 2019
- 대화속 감정인식에서 상당히 많이 쓰이는 데이터 셋
- 기존에 EmotionLines 라는 ERC 데이터 셋이 있는데 이를 잘못된 부분을 필터링 하고 멀티모달로 확장
- Friends 티비 프로그램에서 수집한 데이터 셋
- 감정 클래스는 Ekman+neutral, 감성 클래스는 sentiment을 제공
- Ekman 이란? 폴 박사가 인간의 기본 감정을 분류한 것
  (분노, 혐오, 두려움, 기쁨, 슬픔, 놀라움)

  ->  다른 감정들은 이들의 복잡한 조합으로 될 수 있다.

  ex) 창피함 = 두려움 + 분노

  즉 Ekman 6개 감정 + 중립, 해서 7개의 감정 클래스로 데이터 태깅
