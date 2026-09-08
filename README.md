# Spring Getting Started Guides

[Spring Guides](https://spring.io/guides/) に掲載されている全68件を、推奨学習順に並べたロードマップ。

> [!note]
> この順序はSpring公式が定めた全ガイド共通の履修順ではない。公式の[Spring Quickstart](https://spring.io/quickstart/)が案内する「Spring Boot → RESTサービス → RESTクライアント → JPA」を出発点に、前提知識、難易度、技術の依存関係を考慮して構成している。

> [!tip]
> 最初から全68件を完走する必要はない。まずステージ1〜3を学び、その後は作りたいものに関係するステージへ進む。ステージ0のIDEガイドは、自分が使うものを1件だけ選べばよい。

## ステージ0：開発環境（3件・1件選択）

- [ ] 1. [Working a Getting Started guide with IntelliJ IDEA](https://spring.io/guides/gs/intellij-idea/) — IntelliJ IDEAでガイドを利用する
- [ ] 2. [Building a Guide with VS Code](https://spring.io/guides/gs/guides-with-vscode/) — VS Codeでガイドを利用する
- [ ] 3. [Working a Getting Started guide with STS](https://spring.io/guides/gs/sts/) — Spring Tool Suiteでガイドを利用する

## ステージ1：Spring BootとWebの基礎（12件・必修）

- [ ] 4. [Building an Application with Spring Boot](https://spring.io/guides/gs/spring-boot/) — Spring Bootの自動構成、起動方法、テスト、Actuatorの概要を学ぶ
- [ ] 5. [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/) — コントローラーとHTTP APIの基本を学ぶ
- [ ] 6. [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/) — Spring MVCとThymeleafで画面を作る
- [ ] 7. [Handling Form Submission](https://spring.io/guides/gs/handling-form-submission/) — Webフォームの表示と送信を扱う
- [ ] 8. [Validating Form Input](https://spring.io/guides/gs/validating-form-input/) — 入力値のバリデーションを追加する
- [ ] 9. [Uploading Files](https://spring.io/guides/gs/uploading-files/) — マルチパート形式のファイルを受け付ける
- [ ] 10. [Consuming a RESTful Web Service](https://spring.io/guides/gs/consuming-rest/) — Springから外部REST APIを利用する
- [ ] 11. [Scheduling Tasks](https://spring.io/guides/gs/scheduling-tasks/) — 定期実行するタスクを作る
- [ ] 12. [Creating Asynchronous Methods](https://spring.io/guides/gs/async-method/) — 非同期サービスメソッドを作る
- [ ] 13. [Testing the Web Layer](https://spring.io/guides/gs/testing-web/) — Spring BootとMVCコントローラーをテストする
- [ ] 14. [Building a RESTful Web Service with Spring Boot Actuator](https://spring.io/guides/gs/actuator-service/) — ヘルスチェックなどの運用エンドポイントを追加する
- [ ] 15. [Caching Data with Spring](https://spring.io/guides/gs/caching/) — メソッドの結果をキャッシュする

## ステージ2：データベースとREST API（8件・必修）

- [ ] 16. [Accessing Relational Data using JDBC with Spring](https://spring.io/guides/gs/relational-data-access/) — JDBCによるリレーショナルデータアクセスを学ぶ
- [ ] 17. [Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/) — Spring Data JPAでエンティティを永続化する
- [ ] 18. [Managing Transactions](https://spring.io/guides/gs/managing-transactions/) — 複数の処理をトランザクションとして扱う
- [ ] 19. [Accessing data with MySQL](https://spring.io/guides/gs/accessing-data-mysql/) — 実際のRDBMSへ接続する
- [ ] 20. [Accessing JPA Data with REST](https://spring.io/guides/gs/accessing-data-rest/) — JPAリポジトリをREST APIとして公開する
- [ ] 21. [Building REST services with Spring](https://spring.io/guides/tutorials/rest/) — REST API構築をまとまった題材で復習・発展させる
- [ ] 22. [Building a Hypermedia-Driven RESTful Web Service](https://spring.io/guides/gs/rest-hateoas/) — HATEOASを使ったREST APIを学ぶ
- [ ] 23. [Enabling Cross Origin Requests for a RESTful Web Service](https://spring.io/guides/gs/rest-service-cors/) — REST APIでCORSを設定する

## ステージ3：APIの品質と発展的なWeb（5件・準必修）

- [ ] 24. [Creating API Documentation with Restdocs](https://spring.io/guides/gs/testing-restdocs/) — テストからHTTP APIドキュメントを生成する
- [ ] 25. [Consumer Driven Contracts](https://spring.io/guides/gs/contract-rest/) — Consumer-Driven Contractテストを学ぶ
- [ ] 26. [Building a GraphQL service](https://spring.io/guides/gs/graphql-server/) — Spring for GraphQLでGraphQL APIを作る
- [ ] 27. [Observing GraphQL in action](https://spring.io/guides/topicals/observing-graphql-in-action/) — GraphQLのオブザーバビリティを学ぶ
- [ ] 28. [Using WebSocket to build an interactive web application](https://spring.io/guides/gs/messaging-stomp-websocket/) — WebSocketとSTOMPで双方向通信を行う

## ステージ4：セキュリティとシークレット管理（6件）

- [ ] 29. [Securing a Web Application](https://spring.io/guides/gs/securing-web/) — Spring Securityによるログインとアクセス制御の基本を学ぶ
- [ ] 30. [Authenticating a User with LDAP](https://spring.io/guides/gs/authenticating-ldap/) — LDAP認証を実装する
- [ ] 31. [Spring Boot and OAuth2](https://spring.io/guides/tutorials/spring-boot-oauth2/) — OAuth 2.0によるソーシャルログインとSSOを学ぶ
- [ ] 32. [Spring Security and Angular](https://spring.io/guides/tutorials/spring-security-and-angular-js/) — SPAとバックエンドを含む認証構成を学ぶ
- [ ] 33. [Accessing Vault](https://spring.io/guides/gs/accessing-vault/) — Spring VaultでHashiCorp Vaultのシークレットを読み込む
- [ ] 34. [Vault Configuration](https://spring.io/guides/gs/vault-config/) — Vaultからアプリケーション設定を取得する

## ステージ5：メッセージングとシステム連携（8件）

- [ ] 35. [Messaging with RabbitMQ](https://spring.io/guides/gs/messaging-rabbitmq/) — RabbitMQでメッセージを送受信する
- [ ] 36. [Messaging with JMS](https://spring.io/guides/gs/messaging-jms/) — JMSブローカーでメッセージを送受信する
- [ ] 37. [Messaging with Redis](https://spring.io/guides/gs/messaging-redis/) — Redisをメッセージブローカーとして利用する
- [ ] 38. [Integrating Data](https://spring.io/guides/gs/integration/) — Spring Integrationでデータ処理フローを作る
- [ ] 39. [Messaging with Google Cloud Pub/Sub](https://spring.io/guides/gs/messaging-gcp-pubsub/) — Google Cloud Pub/Subと連携する
- [ ] 40. [Spring Cloud Stream](https://spring.io/guides/gs/spring-cloud-stream/) — RabbitMQやKafkaを抽象化して利用する
- [ ] 41. [Producing a SOAP web service](https://spring.io/guides/gs/producing-web-service/) — SOAP Webサービスを提供する
- [ ] 42. [Consuming a SOAP web service](https://spring.io/guides/gs/consuming-web-service/) — WSDLベースのSOAPサービスを利用する

## ステージ6：NoSQLとリアクティブ処理（9件）

- [ ] 43. [Accessing Data with MongoDB](https://spring.io/guides/gs/accessing-data-mongodb/) — MongoDBへデータを永続化する
- [ ] 44. [Accessing MongoDB Data with REST](https://spring.io/guides/gs/accessing-mongodb-data-rest/) — MongoDBデータをREST APIとして公開する
- [ ] 45. [Accessing Data with Neo4j](https://spring.io/guides/gs/accessing-data-neo4j/) — Neo4jへオブジェクトと関係を永続化する
- [ ] 46. [Accessing Neo4j Data with REST](https://spring.io/guides/gs/accessing-neo4j-data-rest/) — Neo4jデータをREST APIとして公開する
- [ ] 47. [Accessing Data with Cassandra](https://spring.io/guides/gs/accessing-data-cassandra/) — Cassandraへデータを永続化する
- [ ] 48. [Accessing Data in Pivotal GemFire with REST](https://spring.io/guides/gs/accessing-gemfire-data-rest/) — GemFireデータをREST APIとして公開する
- [ ] 49. [Accessing Data Reactively with Redis](https://spring.io/guides/gs/spring-data-reactive-redis/) — Redisへリアクティブにアクセスする
- [ ] 50. [Accessing data with R2DBC](https://spring.io/guides/gs/accessing-data-r2dbc/) — RDBへリアクティブにアクセスする
- [ ] 51. [Building a Reactive RESTful Web Service](https://spring.io/guides/gs/reactive-rest-service/) — WebFluxとWebClientでリアクティブなRESTサービスを作る

## ステージ7：マイクロサービス（5件）

- [ ] 52. [Service Registration and Discovery](https://spring.io/guides/gs/service-registration-and-discovery/) — Eurekaでサービスを登録・検索する
- [ ] 53. [Centralized Configuration](https://spring.io/guides/gs/centralized-configuration/) — 複数サービスの設定を一元管理する
- [ ] 54. [Client-Side Load-Balancing with Spring Cloud LoadBalancer](https://spring.io/guides/gs/spring-cloud-loadbalancer/) — クライアント側ロードバランシングを行う
- [ ] 55. [Building a Gateway](https://spring.io/guides/gs/gateway/) — Spring Cloud GatewayでAPIゲートウェイを作る
- [ ] 56. [Spring Cloud Circuit Breaker Guide](https://spring.io/guides/gs/cloud-circuit-breaker/) — 障害を連鎖させないCircuit Breakerを導入する

## ステージ8：ビルド、デプロイ、運用（6件）

- [ ] 57. [Creating a Multi Module Project](https://spring.io/guides/gs/multi-module/) — ライブラリとアプリケーションを分割した構成を学ぶ
- [ ] 58. [Spring Boot with Docker](https://spring.io/guides/gs/spring-boot-docker/) — Spring Bootアプリケーションをコンテナ化する
- [ ] 59. [Spring Boot Kubernetes](https://spring.io/guides/gs/spring-boot-kubernetes/) — Spring BootアプリケーションをKubernetesへデプロイする
- [ ] 60. [Spring on Kubernetes](https://spring.io/guides/topicals/spring-on-kubernetes/) — SpringとKubernetesを体系的に学ぶ
- [ ] 61. [Deploying a Spring Boot app to Azure](https://spring.io/guides/gs/spring-boot-for-azure/) — Spring BootアプリケーションをAzureへデプロイする
- [ ] 62. [Observability with Spring](https://spring.io/guides/gs/tanzu-observability/) — アプリケーションのメトリクスを監視基盤へ送信する

## ステージ9：バッチとデータパイプライン（3件）

- [ ] 63. [Creating a Batch Service](https://spring.io/guides/gs/batch-processing/) — Spring Batchによる基本的なバッチ処理を作る
- [ ] 64. [Spring Cloud Task](https://spring.io/guides/gs/spring-cloud-task/) — 短時間で終了するタスクアプリケーションを作る
- [ ] 65. [Spring Cloud Data Flow](https://spring.io/guides/gs/spring-cloud-dataflow/) — ストリーミングとバッチのデータパイプラインを構築する

## ステージ10：目的に応じて学ぶ追加技術（3件）

- [ ] 66. [Creating CRUD UI with Vaadin](https://spring.io/guides/gs/crud-with-vaadin/) — VaadinとSpring Data JPAでCRUD画面を作る
- [ ] 67. [Building web applications with Spring Boot and Kotlin](https://spring.io/guides/tutorials/spring-boot-kotlin/) — KotlinでSpring Boot Webアプリケーションを作る
- [ ] 68. [Spring Boot with Kotlin Coroutines and RSocket](https://spring.io/guides/tutorials/spring-webflux-kotlin-rsocket/) — Kotlin Coroutines、WebFlux、RSocketでリアクティブなチャットアプリを作る
