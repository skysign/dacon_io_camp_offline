# dacon_io_camp_offline

'SK Data Analyst 와 함께하는 데이터 사이언스 입문 교육 & 프로젝트' 에서 진행한 프로젝트입니다.
교육에 대한, 자세한 내용은 링크 참고하세요, https://festa.io/events/443

## 프로젝트 목적
과거의 로그인한 데이터 제공하고, 그를 기반으로 하여, 앞으로 일주일 동안 로그인 확률을 예측하기

### 과거 로그인한 데이터
train_final.csv 에는 과거의 1월 부터 5월 8일까지 로그인한 기록이 아래와 같이 남아 있다.
- person_id: 유저별 고유 아이디
- Sex: 성별
- past_login_total: 과거에 로그인한 총 횟수
- past_1_month_login: 과거1달간 로그인한 총 횟수, 4월8일부터 5월8일까지 로그인 회수
- past_1_week_login: 과거 1주간 로그인한 총 횟수, 5월1일부터 5월8일까지 로그인 회수
- sub_size: 과거에 데이콘 대회에서의 총 제출 수
- email_type: 가입한 이메일 종류
- phone_rat: 폰으로 접속한 비율
- apple_rat: 애플 기기(아이폰과 맥북)으로 접속한 비율
- login : 로그인 여부

## 프로젝트 내용
- 여러가지 classifer를 사용할 예정이고, 각 classifer에서 모두 성능이 향상되는, feature engineering 하는 것을 목표로 한다.
- 5가지 classifer에서 모두 auc 값이 오르는 2가지 feature engineering을 진행 함


# 자세한 내용은 project.ipynb 참고하세요.
