# DataSet

  - /KBO
    - play_Schedule_RawData_json
      - 모든 계획된 정규리그 스케줄. 취소경기 포함
      - 2010 ~ 2021
    - play_BoxScore_RawData_json :     
      - play_Schedule > '게임센터'로부터 gameId 목록 추출.
      - gameId를 통해 요청/응답받은 BoxScore data.
    - play_ScoreBoard_RawData_json
      - play_Schedule > '게임센터'로부터 gameId 목록 추출.
      - gameId를 통해 요청/응답받은 ScoreBoard data.
      - BoxScore와는 별도로 요청해야 함.

  - /Weather
    - SURFACE_ASOS_RawData : years(2018 ~ 2021)
      - DAY : per day
      - HR : per hour
      - MIN : per minute
      - MNH : per month
