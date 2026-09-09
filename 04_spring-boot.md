# Building an Application with Spring Boot

https://spring.io/guides/gs/spring-boot/

https://github.com/spring-guides/gs-spring-boot


# 学習メモ
- Gradle はクラスパスに追加された依存先ライブラリを自動でダウンロードしてくれる
- Spring Boot はクラスパスのライブラリを確認し、必要な設定を自動で追加してくれる。
- @RestController は、実質的に @Controller と @ResponseBody を組み合わせたアノテーション
- SpringApplication.run() を実行すると、Spring の ApplicationContext が構築され、必要な Bean や Web サーバーが準備されてアプリが起動する
- @SpringBootApplication は、@Configuration、@EnableAutoConfiguration、@ComponentScan を組み合わせたアノテーション
- CommandLineRunner を Bean として定義し、起動時に ApplicationContext 内の Bean を一覧表示できるようにした。これは Spring Boot 内に CommandLineRunner という型が存在し、内部でフック的に呼び出す処理がなされているためで、実際の呼び出し箇所はアプリケーションコード内には見当たらなかった。
- @SpringBootTest はアプリ全体のコンテキストを構築してしまうので、テストとしてはオーバースペックである。Web 層だけをテストしたい場合は @WebMvcTest を利用して、模擬的な HTTP リクエストの送信結果を検証する。MockMvc を使うと、実際の Web サーバーを起動せずに Controller の動作を確認することができる
- Actuator はアプリの運用・監視用のエンドポイントを提供するもの。ヘルスチェック、Bean 情報、メトリクスなどを取得できる
- Spring Boot は、組み込み Web サーバーを含んだ実行可能 JAR を作成できる。外部の Tomcat へ WAR ファイルを配置しなくても、java コマンドだけで Web アプリを起動できる。

