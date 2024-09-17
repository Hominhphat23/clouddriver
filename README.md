var gitalkConfig = {
    clientID: "a2bdae5457402030fb6b",
    clientSecret: "c1c9ce6f3334a85f5456b602ca138dee038fd414",
    repo: "robotdemo.github.io",
    owner: "zeroone001",
    admin: ["zeroone001"],
    perPage: 20,
    language: "zh-CN",
    // labels: ['Open'],
    pagerDirection: "last",
    distractionFreeMode: false,
    proxy: 'http://192.168.31.16:8011'
};
const gitalk = new Gitalk({
    clientID: 'GitHub Application Client ID',
    clientSecret: 'GitHub Application Client Secret',
    repo: 'https://github.com/zeroone001/robotdemo.github.io/tree/master',      // The repository of store comments,
    owner: 'zeroone001',
    admin: ['zeroone001'],
    id: location.pathname,      // Ensure uniqueness and length less than 50
    distractionFreeMode: false  // Facebook-like distraction free mode
})

gitalk.render('gitalk-container');Spinnaker Cloud Provider Service
------------------------------------
[![Build Status](https://github.com/spinnaker/clouddriver/workflows/Branch%20Build/badge.svg)](https://github.com/spinnaker/clouddriver/actions)

This service is the main integration point for Spinnaker cloud providers like AWS, GCE, CloudFoundry, Azure etc.

### Developing with Intellij

To configure this repo as an Intellij project, run `./gradlew idea` in the root directory.

Some of the modules make use of [Lombok](https://projectlombok.org/), which will compile correctly on its own. However, for Intellij to make sense of the Lombok annotations, you'll need to install the [Lombok plugin](https://plugins.jetbrains.com/plugin/6317-lombok-plugin) as well as [check 'enable' under annotation processing](https://www.jetbrains.com/help/idea/configuring-annotation-processing.html#3).

### Debugging

To start the JVM in debug mode, set the Java system property `DEBUG=true`:
```
./gradlew -DDEBUG=true
```

The JVM will then listen for a debugger to be attached on port 7102.  The JVM will _not_ wait for
the debugger to be attached before starting Clouddriver; the relevant JVM arguments can be seen and
modified as needed in `build.gradle`.
## docsify

基于 docsify

https://docsify.js.org/#/zh-cn/cover

## 启动服务

docsify serve ./docs

https://zeroone001.github.io/robotdemo.github.io/#/


## 仓库地址

https://github.com/BerserkerRider/robot.github.io

## gittalk

展示GitHub issues 内容的插件

https://github.com/gitalk/gitalk

### 安装

https://github.com/gitalk/gitalk#install

```js
var gitalkConfig = {
    clientID: "a2bdae5457402030fb6b",
    clientSecret: "c1c9ce6f3334a85f5456b602ca138dee038fd414",
    repo: "robotdemo.github.io",
    owner: "zeroone001",
    admin: ["zeroone001"],
    perPage: 20,
    language: "zh-CN",
    // labels: ['Open'],
    pagerDirection: "last",
    distractionFreeMode: false,
    proxy: 'http://192.168.31.16:8011'
};
const gitalk = new Gitalk({
    clientID: 'GitHub Application Client ID',
    clientSecret: 'GitHub Application Client Secret',
    repo: 'https://github.com/zeroone001/robotdemo.github.io/tree/master',      // The repository of store comments,
    owner: 'zeroone001',
    admin: ['zeroone001'],
    id: location.pathname,      // Ensure uniqueness and length less than 50
    distractionFreeMode: false  // Facebook-like distraction free mode
})

gitalk.render('gitalk-container');
```

## 第三方登录

https://www.ruanyifeng.com/blog/2019/04/github-oauth.html

## 开源
https://github.com/BerserkerRider/robot.github.iohttps://zeroone001.github.io/robotdemo.github.io/#/https://github.com/gitalk/gitalk#install
基于 docsify

https://docsify.js.org/#/zh-cn/cover

## 启动服务

docsify serve ./docs

https://zeroone001.github.io/robotdemo.github.io/#/


## 仓库地址

https://github.com/BerserkerRider/robot.github.io

## gittalk

展示GitHub issues 内容的插件

https://github.com/gitalk/gitalk

### 安装

https://github.com/gitalk/gitalk#install

```js
var gitalkConfig = {
    clientID: "a2bdae5457402030fb6b",
    clientSecret: "c1c9ce6f3334a85f5456b602ca138dee038fd414",
    repo: "robotdemo.github.io",
    owner: "zeroone001",
    admin: ["zeroone001"],
    perPage: 20,
    language: "zh-CN",
    // labels: ['Open'],
    pagerDirection: "last",
    distractionFreeMode: false,
    proxy: 'http://192.168.31.16:8011'
};
const gitalk = new Gitalk({
    clientID: 'GitHub Application Client ID',
    clientSecret: 'GitHub Application Client Secret',
    repo: 'https://github.com/zeroone001/robotdemo.github.io/tree/master',      // The repository of store comments,
    owner: 'zeroone001',
    admin: ['zeroone001'],
    id: location.pathname,      // Ensure uniqueness and length less than 50
    distractionFreeMode: false  // Facebook-like distraction free mode
})

gitalk.render('gitalk-container');
```

## 第三方登录

https://www.ruanyifeng.com/blog/2019/04/github-oauth.html

## 开源
**Files with changes (up to 15)**

| Original Link | Updated Link |
| --- | --- |
| [https://developers.cloudflare.com/r2/buckets/event-notifications/](https://developers.cloudflare.com/r2/buckets/event-notifications/) | [https://pjones-r2-event-notification.cloudflare-docs-7ou.pages.dev/r2/buckets/event-notifications/](https://pjones-r2-event-notification.cloudflare-docs-7ou.pages.dev/r2/buckets/event-notifications/) |
| [https://developers.cloudflare.com/r2/examples/upload-logs-event-notifications/](https://developers.cloudflare.com/r2/examples/upload-logs-event-notifications/) | [https://pjones-r2-event-notification.cloudflare-docs-7ou.pages.dev/r2/examples/upload-logs-event-notifications/](https://pjones-r2-event-notification.cloudflare-docs-7ou.pages.dev/r2/examples/upload-logs-event-notifications/) |
| [https://developers.cloudflare.com/workers/wrangler/commands/](https://developers.cloudflare.com/workers/wrangler/commands/) | [https://pjones-r2-event-notification.cloudflare-docs-7ou.pages.dev/workers/wrangler/commands/](https://pjones-r2-event-notification.cloudflare-docs-7ou.pages.dev/workers/wrangler/commands/) |
| [https://developers.cloudflare.com/queues/tutorials/upload-logs-event-notifications/](https://developers.cloudflare.com/queues/tutorials/upload-logs-event-notifications/) | [https://pjones-r2-event-notification.cloudflare-docs-7ou.pages.dev/queues/tutorials/upload-logs-event-notifications/](https://pjones-r2-event-notification.cloudflare-docs-7ou.pages.dev/queues/tutorials/upload-logs-event-notifications/) |

_Originally posted by @github-actions in https://github.com/cloudflare/cloudflare-docs/pull/13730#issuecomment-2030991425_name = "event-notification-writer"
main = "src/index.ts"
compatibility_date = "2024-03-29"
compatibility_flags = ["nodejs_compat"]

[[queues.consumers]]
queue = "example-event-notification-queue"
max_batch_size = 100
max_batch_timeout = 5

[[r2_buckets]]
binding = "LOG_SINK"
bucket_name = "example-log-sink-bucket
const result = await axios({
  method: 'get',
  url: `https://api.github.com/user`,
  headers: {
    accept: 'application/json',
    Authorization: `token ${accessToken}`
  }
const tokenResponse = await axios({
  method: 'post',
  url: 'https://github.com/login/oauth/access_token?' +
    `client_id=${clientID}&` +
    `client_secret=${clientSecret}&` +
    `code=${requestToken}`,
  headers: {
    accept: 'application/json'
Selector	Description	WARP mode required
User email	Email address of a user
user-name@company.com	Gateway with WARP
User group emails	Email address of an IdP group
contractors@company.com	Gateway with WARP
User group IDs	ID of an IdP group
12jf495bhjd7893ml09o	Gateway with WARP
User group names	Name of an IdP group
developers	Gateway with WARP
Operating system	Operating system of the device
macOS	Any mode
Operating system version	OS version specified in Semver format
1.2.0	Any mode
Managed network	Network location of the device	Any mode
SAML Attributes	Attribute name and value from a SAML IdP	Gateway with WARP
Comparison operators
user-name@company.com
$ openssl req -x509 -newkey rsa:4096 -sha256 -days 3650 -nodes -keyout example.key -out example.pem -subj "/CN=example.com" -addext "subjectAltName=DNS:example.com"
_eventsCount: 2,
[Symbol(shapeMode)]: true,
[Symbol(kCapture)]: false,
[Symbol(kHeaders)]: {
'content-type': 'application/json; charset=utf8',
'content-length': '0',
connection: 'keep-alive',
date: 'Sat, 17 Aug 2024 05:19:33 GMT',
'cache-control': 'no-cache, no-store, must-revalidate, max-age=0, s-maxage=0',
'apigw-requestid': 'cozj2hdwSK4EJsg=',
'x-cache': 'Error from cloudfront',
via: '1.1 748bf2e250893e1ba5433de84d1e52d4.cloudfront.net (CloudFront)',
'x-amz-cf-pop': 'ORD58-P4',
'x-amz-cf-id': '5fmG-hz2OdyHIZPhC8ab4x_6HZ70qRzY9JLmOgnY6Yh4p_xhZfXRjQ=='
},
[Symbol(kHeadersCount)]: 20,
[Symbol(kTrailers)]: null,
[Symbol(kTrailersCount)]: 0
https://ranbel-tunnel-changelog.cloudflare-docs-7ou.pages.dev/cloudflare-one/changelog/browser-isolation/
https://ranbel-tunnel-changelog.cloudflare-docs-7ou.pages.dev/cloudflare-one/changelog/dex/https://ranbel-tunnel-changelog.cloudflare-docs-7ou.pages.dev/cloudflare-one/changelog/casb/https://ranbel-tunnel-changelog.cloudflare-docs-7ou.pages.dev/cloudflare-one/changelog/warp/
  id 'com.adarshr.test-logger' version '2.1.0' 
 } 
  
 sourceSets { 
   integration { 
     java.srcDirs = ["src/integration/java"] 
     resources.srcDirs = ["src/integration/resources"] 
     compileClasspath += main.output + test.output 
   } 
 } 
  
 configurations { 
   integrationImplementation.extendsFrom testImplementation 
   integrationRuntime.extendsFrom testRuntime 
 } 
  
 dependencies { 
   implementation project(":cats:cats-core") 
   implementation project(":clouddriver-api") 
   implementation project(":clouddriver-configserver") 
   implementation project(":clouddriver-core") 
   implementation project(":clouddriver-eureka") 
   implementation project(":clouddriver-security") 
   implementation project(":clouddriver-saga") 
  
   implementation "javax.inject:javax.inject:1" 
   implementation "com.amazonaws:aws-java-sdk" 
   implementation "com.github.ben-manes.caffeine:guava" 
   implementation "com.netflix.awsobjectmapper:awsobjectmapper" 
   implementation "com.netflix.frigga:frigga" 
   implementation "io.spinnaker.fiat:fiat-api:$fiatVersion" 
   implementation "io.spinnaker.fiat:fiat-core:$fiatVersion" 
   implementation "io.spinnaker.kork:kork-cloud-config-server" 
   implementation "io.spinnaker.kork:kork-core" 
   implementation "io.spinnaker.kork:kork-aws" 
   implementation "io.spinnaker.kork:kork-exceptions" 
   implementation "io.spinnaker.kork:kork-secrets" 
   implementation "io.spinnaker.kork:kork-security" 
   implementation "io.spinnaker.kork:kork-credentials" 
   implementation "io.spinnaker.kork:kork-moniker" 
   implementation "io.spinnaker.kork:kork-retrofit" 
   implementation "com.squareup.okhttp:okhttp" 
   implementation "com.squareup.okhttp:okhttp-apache" 
   implementation "com.squareup.okhttp:okhttp-urlconnection" 
   implementation "com.squareup.retrofit:converter-jackson" 
   implementation "com.squareup.retrofit:retrofit" 
   implementation "io.reactivex:rxjava" 
   implementation "org.apache.httpcomponents:httpclient" 
   implementation "org.apache.httpcomponents:httpcore" 
   implementation "org.codehaus.groovy:groovy" 
   implementation "org.springframework.boot:spring-boot-actuator" 
   implementation "org.springframework.boot:spring-boot-starter-web" 
   implementation 'com.aestasit.infrastructure.sshoogr:sshoogr:0.9.25' 
   implementation 'com.jcraft:jsch.agentproxy.connector-factory:0.0.9' 
   implementation 'com.jcraft:jsch.agentproxy.jsch:0.0.9' 
   implementation "com.github.wnameless.json:json-flattener:0.11.1" 
  
   testImplementation "io.spinnaker.kork:kork-exceptions" 
   testImplementation "cglib:cglib-nodep" 
   testImplementation "com.natpryce:hamkrest" 
   testImplementation "com.google.guava:guava" 
   testImplementation "org.junit.jupiter:junit-jupiter-api" 
   testImplementation "org.objenesis:objenesis" 
   testImplementation "org.spockframework:spock-core" 
   testImplementation "org.spockframework:spock-spring" 
   testImplementation "org.springframework.boot:spring-boot-starter-test" 
   testImplementation "org.springframework:spring-test" 
  
   integrationImplementation project(":clouddriver-web") 
   integrationImplementation "org.springframework:spring-test" 
   integrationImplementation sourceSets.test.output 
   integrationImplementation sourceSets.main.output 
   integrationImplementation ("io.rest-assured:rest-assured:4.0.0") { 
     exclude group: "org.codehaus.groovy", module: "groovy" // use kork's version 
   } 
 } 
  
 task integrationTest(type: Test) { 
   description = "Runs AWS EC2 provider integration tests." 
   group = 'verification' 
  
   environment "PROJECT_ROOT", project.rootDir.toString() 
   useJUnitPlatform() 
  
   testClassesDirs = sourceSets.integration.output.classesDirs 
   classpath = sourceSets.integration.runtimeClasspath 
   shouldRunAfter test 
   maxParallelForks = 4 
  
   minHeapSize = "512m" 
   maxHeapSize = "${testJvmMaxMemory}" 
  
   testlogger { 
     theme 'mocha' 
     showFailedStandardStreams true 
   } 
 }

@targos pushed 12 commits.

b4cd81b deps: update V8 to 12.9.202.18
013f7d8 build: reset embedder string to "-node.0"
40113d1 src: update NODE_MODULE_VERSION to 131
affda4e deps: always define V8_EXPORT_PRIVATE as no-op
ddf2ae4 deps: disable V8 concurrent sparkplug compilation
d9b1876 deps: patch V8 to avoid duplicated zlib symbol
763a6b9 deps: patch V8 to support compilation with MSVC
4d662bb deps: fix FP16 bitcasts.h
4e012d4 deps: always define V8_NODISCARD as no-op
f00716f deps: patch V8 to support older Clang versions
d2250da deps: V8: cherry-pick 01a47f3ffff2
d174634 deps: V8: cherry-pick 97199f686e2f