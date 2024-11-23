https://github.com/datastacktv/data-engineer-roadmap  
위에 있는 roadmap을 영어에서 한국어로 번역해보았다.


# **1. CS 기본**

- **터미널 사용법**: CLI 명령어와 기본적인 셸 스크립팅을 익히세요.
- **데이터 구조 및 알고리즘**: 배열, 연결 리스트, 스택, 큐, 트리, 그래프, 그리고 정렬과 검색 알고리즘을 공부하세요.
- **API들**: RESTful API와 그 메소드들 (GET, POST, PUT, DELETE)을 이해하세요.
- **정형 데이터 vs 비정형 데이터**: 구조화된 데이터 (e.g., 관계형 데이터베이스)와 비구조화된 데이터 (e.g., 텍스트 파일, 이미지)의 차이를 배우세요.
- **Serialization(직렬화)**: 데이터를 파일에 쓰거나 네트워크로 전송할 수 있는 형식으로 변환하는 방법을 이해하세요.
- **Linux**:
    - **CLI**: CLI 명령어를 익히세요.
    - **Vim**: Vim 편집기를 사용하는 방법을 배우세요.
    - **Shell scripting**: 셸 스크립팅을 익히세요.
    - **Cronjobs**: 크론 잡을 사용하는 방법을 배우세요.
- **수학과 통계**: 확률론, 통계학, 선형대수를 복습하세요.

# **2. 컴퓨터와 인터넷의 작동 원리**

- How does the computer work?  : 컴퓨터가 어떻게 동작하는지 이해하세요.
- How does the Internet work?  : 인터넷이 어떻게 동작하는지 이해하세요.
- **Git-version control**: Git 버전 제어를 익히세요.

# **3. 프로그래밍 언어**

- **Python**: Python을 중점적으로 공부하세요. Pandas, NumPy, Matplotlib 라이브러리를 익히세요.
- **Java, Scala, Go**: 이 언어들에 대해 기본적인 이해를 가지세요.

# **4. Testing**

- **Unit testing**: 개별 컴포넌트의 테스트를 작성하는 방법을 배우세요.
- **Integration testing**: 컴포넌트 간의 상호작용을 테스트하는 방법을 이해하세요.
- **Functional testing**: 전체 애플리케이션의 기능을 테스트하는 방법을 공부하세요.

# **5. Database Fundamentals**

- **SQL**: SQL 기본, 쿼리, 인덱싱, 정규화를 마스터하세요.
- **ACID Transactions**: 원자성, 일관성, 격리성, 지속성의 원칙을 이해하세요.
- **CAP 정리**: 일관성, 가용성, 분할 내성 간의 트레이드오프를 배우세요.
- **OLTP vs OLAP**: 온라인 트랜잭션 처리와 온라인 분석 처리의 차이를 공부하세요.
- **Dimensional Modeling**: 데이터 웨어하우스에서 사용되는 데이터 모델링 기법을 이해하세요.

# **6. Relational Databases**

- **MySQL**: MySQL을 익히세요.
- **PostgreSQL**: PostgreSQL을 공부하세요.
- **MariaDB**: MariaDB를 익히세요.
- **Amazon Aurora**: Amazon Aurora를 공부하세요.

# **7. Non-Relational Databases**

### **Document**:

- **MongoDB**: MongoDB를 익히세요.
- **Elasticsearch**: Elasticsearch를 공부하세요.
- **Apache CouchDB**: Apache CouchDB를 익히세요.
- **Azure CosmosDB**: Azure CosmosDB를 공부하세요.

### **Wide Column**:

- **Apache Cassandra**: Apache Cassandra를 익히세요.
- **Apache HBase**: Apache HBase를 공부하세요.
- **Google Bigtable**: Google Bigtable을 익히세요.

### **Graph**:

- **Neo4j**: Neo4j를 공부하세요.
- **Amazon Neptune**: Amazon Neptune를 익히세요.

### **Key-Value**:

- **Redis**: Redis를 익히세요.
- **Memcached**: Memcached를 공부하세요.
- **Amazon DynamoDB**: Amazon DynamoDB를 익히세요.

# **8. Data Warehouses**

- **Snowflake**: 클라우드 기반 데이터 웨어하우스 서비스를 이해하세요.
- **Presto**: 빠른 대화식 쿼리를 위한 오픈 소스 분산 SQL 쿼리 엔진을 공부하세요.
- **Apache Hive**: 대규모 데이터 분석을 위한 내결함성 분산 데이터 웨어하우스 시스템을 익히세요.
- **Apache Impala**: 실시간 병렬 조회가 가능한 쿼리 엔진을 공부하세요.
- **Amazon Redshift**: 완전히 관리되는 페타바이트급 데이터 웨어하우스 서비스를 이해하세요.
- **Google BigQuery**: 구글에서 제공하는 클라우드 데이터 웨어하우스를 공부하세요.
- **Azure Synapse**: 엔터프라이즈 데이터 웨어하우징과 빅 데이터 분석을 함께 제공하는 무제한 분석 서비스를 익히세요.
- **ClickHouse**: OLAP을 위한 컬럼 지향형 SQL DBMS를 공부하세요.

# **9. Object Storage**

- **AWS S3**: S3를 사용한 객체 저장소를 이해하세요.
- **Azure Blob Storage**: Azure의 객체 저장소 솔루션을 익히세요.
- **Google Cloud Storage**: Google Cloud를 사용한 객체 저장소를 공부하세요.

# **10. Cluster Computing Fundamentals**

- **Apache Hadoop**: 분산 컴퓨팅을 위한 Hadoop을 익히세요.
- **HDFS**: Hadoop 분산 파일 시스템을 이해하세요.
- **MapReduce**: 대규모 데이터 처리를 위한 MapReduce를 공부하세요.
- **Lambda & Kappa Architectures**: 실시간 데이터 처리 아키텍처를 이해하세요.
- **Managed Hadoop**:
    - **Amazon EMR**: Amazon EMR를 익히세요.
    - **Google Dataproc**: Google Dataproc를 공부하세요.
    - **Azure Data Lake**: Azure Data Lake를 익히세요.

# **11. Data Processing**

### **Batch**:

- **Apache Pig**: Apache Pig를 익히세요.
- **Apache Arrow**: Apache Arrow를 공부하세요.
- **data build tool**: data build tool을 익히세요.

### **Hybrid**:

- **Apache Spark**: Apache Spark를 공부하세요.
- **Apache Beam**: Apache Beam을 익히세요.
- **Apache Flink**: Apache Flink를 공부하세요.
- **Apache NiFi**: Apache NiFi를 익히세요.

### **Streaming**:

- **Apache Kafka**: Apache Kafka를 공부하세요.
- **Apache Storm**: Apache Storm을 익히세요.
- **Apache Samza**: Apache Samza를 공부하세요.
- **Amazon Kinesis**: Amazon Kinesis를 익히세요.

# **12. Messaging**

- **Amazon SNS & SQS**: Amazon의 메시징 서비스를 이해하세요.
- **Google PubSub**: Google의 메시징 서비스를 익히세요.
- **Azure Service Bus**: Azure의 메시징 서비스를 공부하세요.
- **RabbitMQ**: RabbitMQ를 사용한 메시징을 이해하세요.
- **Apache ActiveMQ**: Apache ActiveMQ를 사용한 메시징을 공부하세요.

# **13. Workflow Scheduling**

- **Apache Airflow**: 워크플로우 스케줄링을 위한 Apache Airflow를 익히세요.
- **Google Commposer**: Google의 워크플로우 스케줄링 서비스를 이해하세요.
- **Apache Oozie**: Apache Oozie를 사용한 워크플로우 스케줄링을 공부하세요.
- **Luigi**: Luigi를 사용한 워크플로우 스케줄링을 익히세요.

# **14. Monitoring Data Pipelines**

- **Prometheus**: 데이터 파이프라인 모니터링을 위한 Prometheus를 공부하세요.
- **Datadog**: Datadog를 사용한 데이터 파이프라인 모니터링을 이해하세요.
- **Sentry**: Sentry를 사용한 데이터 파이프라인 모니터링을 공부하세요.
- **StatsD**: StatsD를 사용한 데이터 파이프라인 모니터링을 익히세요.

# **15. Networking**

- **Protocols**: 네트워크 프로토콜을 이해하세요.
- **Firewalls**: 방화벽을 공부하세요.
- **VPN**: VPN을 이해하세요.
- **VPC**: VPC를 공부하세요.
- **HTTP/HTTPS**: HTTP/HTTPS 프로토콜을 이해하세요.
- **TCP**: TCP 프로토콜을 공부하세요.
- **SSH**: SSH 프로토콜을 이해하세요.
- **IP**: IP 프로토콜을 공부하세요.
- **DNS**: DNS를 이해하세요.

# **16. Infrastructure as Code**

### **Containers**:

- **Docker**: Docker를 사용한 컨테이너화된 애플리케이션을 실행하는 플랫폼을 익히세요.
- **LXC**: LXC를 사용한 컨테이너 관리를 공부하세요.

### **Container Orchestration**:

- **Kubernetes**: Kubernetes를 사용한 컨테이너 오케스트레이션을 익히세요.
- **Docker Swarm**: Docker Swarm을 사용한 컨테이너 오케스트레이션을 공부하세요.
- **Apache Mesos**: Apache Mesos를 사용한 컨테이너 오케스트레이션을 익히세요.
- **GKE**: GKE를 사용한 컨테이너 오케스트레이션을 공부하세요.

### **Infrastructure Provisioning**:

- **Terraform**: Terraform을 사용한 인프라스트럭처 프로비저닝을 익히세요.
- **Pulumi**: Pulumi를 사용한 인프라스트럭처 프로비저닝을 공부하세요.
- **AWS CDK**: AWS CDK를 사용한 인프라스트럭처 프로비저닝을 익히세요.

# **17. CI/CD**

- **GitHub Actions**: GitHub Actions를 사용한 CI/CD를 익히세요.
- **Jenkins**: Jenkins를 사용한 CI/CD를 공부하세요.

# **18. Identity and Access Management**

- **Active Directory**: Active Directory를 사용한 사용자 인증 및 권한 관리를 이해하세요.
- **Azure Active Directory**: Azure Active Directory를 사용한 사용자 인증 및 권한 관리를 공부하세요.

# **19. Data Security & Privacy**

- **Legal Compliance**: 법적 요구 사항을 준수하는 방법을 이해하세요.
- **Encryption**: 데이터 암호화를 공부하세요.
- **Key Management**: 키 관리를 이해하세요.
- **Data Governance & Integrity**: 데이터 관리 및 무결성을 공부하세요.

# **20. Visualise Data**

- **Tableau**: Tableau를 사용한 데이터 시각화를 익히세요.
- **Looker**: Looker를 사용한 데이터 시각화를 공부하세요.
- **Grafana**: Grafana를 사용한 데이터 시각화를 이해하세요.
- **Jupyter Notebook**: Jupyter Notebook을 사용한 데이터 시각화를 공부하세요.
- **Microsoft Power BI**: Microsoft Power BI를 사용한 데이터 시각화를 익히세요.

# **21. Machine Learning Fundamentals**

- **Terminology**:
    - **Supervised vs Unsupervised Learning**: 감독학습과 비감독학습의 차이를 이해하세요.
    - **Classification vs Regression**: 분류와 회귀의 차이를 공부하세요.
    - **Evaluation Metrics**: 모델 평가 지표를 이해하세요.
- **sciKit-learn**: sciKit-learn을 사용한 머신러닝을 공부하세요.
- **Tensorflow**: Tensorflow를 사용한 머신러닝을 익히세요.
- **Keras**: Keras를 사용한 머신러닝을 공부하세요.
- **PyTorch**: PyTorch를 사용한 머신러닝을 익히세요.

# **22. Machine Learning Ops**

- **Tensorflow Extended**: Tensorflow Extended를 사용한 머신러닝 운영을 공부하세요.
- **Kubeflow**: Kubeflow를 사용한 머신러닝 운영을 익히세요.
- **MLflow**: MLflow를 사용한 머신러닝 운영을 공부하세요.
- **Amazon SageMaker**: Amazon SageMaker를 사용한 머신러닝 운영을 익히세요.
- **Google AI Platform**: Google AI Platform을 사용한 머신러닝 운영을 공부하세요.

## **추가적으로 공부해야할 내용**

- **Data Engineering Workflow**: 데이터 엔지니어링 워크플로우를 이해하고 설계하는 방법을 공부하세요.
- **Data Pipeline Monitoring**: 데이터 파이프라인 모니터링을 위한 다양한 도구와 기술을 익히세요.
- **CI/CD Best Practices**: CI/CD의 실무를 이해하고 적용하는 방법을 공부하세요.
- **Identity and Access Management Best Practices**: 사용자 인증 및 권한 관리의最佳 실무를 이해하고 적용하는 방법을 공부하세요.
- **Data Security Best Practices**: 데이터 보안의 실무를 이해하고 적용하는 방법을 공부하세요.
- **Machine Learning Best Practices**: 머신러닝의 실무를 이해하고 적용하는 방법을 공부하세요.
