easy-rule-demo
规则引擎之EasyRules 什么是EasyRules 首先EasyRule是一个规则引擎
1 pom.xml
      <dependency>
          <groupId>org.jeasy</groupId>
          <artifactId>easy-rules-core</artifactId>
          <version>3.0.0</version>
      </dependency>
2 规则是一个interface接口，里面有俩函数：一个用来判断条件是否达成，返回true/false，另一个是如果返回是true，则执行一些动作修改某些值