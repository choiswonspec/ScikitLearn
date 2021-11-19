# ScikitLearn

- scikit-learn(“사이킷런”이라고 읽는다) 패키지는 머신러닝 교육을 위한 최고의 파이썬 패키지다.
- scikit-learn 패키지의 장점은 다양한 머신러닝 모형을 하나의 패키지에서 모두 제공하고 있다는 점이다.
- 다음은 scikit-learn 패키지에서 제공하는 머신러닝 모형의 목록의 일부다.
- 데이터셋
  - 회귀분석, 분류, 클러스터링용 가상 데이터셋 생성
  - 각종 벤치마크 데이터셋
- 전처리
  - 스케일링
  - 누락데이터 처리
  - 텍스트 토큰화
- 지도학습
  - 회귀분석
  - LDA/QDA
  - 서포트벡터머신
  - 퍼셉트론, SGD
  - KNN
  - 가우스프로세스
  - 나이브베이즈
  - 의사결정나무
  - 랜덤포레스트, 부스팅
- 비지도학습
  - 가우스 혼합모형
  - 클러스터링
  - PCA
- 성능 최적화
- 교차검증
- 특징선택
- 하이퍼파라미터 최적화

sklearn
│
├── 01 preprocessing (전처리)
│   │
│   ├── 스케일러
│   │   ├── MinMaxScaler
│   │   ├── RobustScaler
│   │   └── StandardScaler
│   │
│   └── 인코더
│       ├── LabelEncoder
│       └── OneHotEncoder
│
├── 02 model_selection (모델링 전처리)
│   │
│   ├── 데이터셋 분리
│   │   ├── KFold
│   │   ├── StratifiedKFold
│   │   └── train_test_split
│   │
│   └── 하이퍼파라미터 튜닝
│       └── GridSearchCV
│
├── 03 모델학습
│   │
│   ├── ensemble
│   │   ├── AdaBoostClassifier
│   │   ├── GradientBoostingClassifier
│   │   ├── RandomForestClassifier
│   │   └── RandomForestRegressor
│   │
│   ├── linear_model
│   │   ├── LogisticRegression
│   │   └── RidgeClassifier
│   │
│   ├── neighbors
│   │   └── KNeighborsClassifier
│   │
│   ├── svm
│   │   ├── SVC
│   │   └── SVR
│   │
│   └── tree
│       ├── DecisionTreeClassifier
│       ├── DecisionTreeRegressor
│       ├── ExtraTreeClassifier
│       └── ExtraTreeRegressor
│
├── 04 모델평가
│   │
│   ├── metrics
│   │   ├── accuracy_score
│   │   ├── classification_report
│   │   ├── confusion_matrix
│   │   ├── f1_score
│   │   ├── log_loss
│   │   ├── mean_absolute_error
│   │   ├── mean_squared_error
│   │   └── roc_auc_score
│   │
│   └── model (정의된 모델에서 추출)
│       ├── predict
│       └── predict_proba
│
└── 05 최종앙상블
│
└── ensemble
├── StackingClassifier
├── StackingRegressor
├── VotingClassifier
└── VotingRegressor
