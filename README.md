***动态伸缩、分布式、高可用、任意延时的海量定时任务中间件***

[![GitHub Action Build](https://github.com/shangtiancode/mtimer/actions/workflows/maven.yml/badge.svg?branch=master&event=push)](https://github.com/shangtiancode/mtimer/actions/workflows/maven.yml?query=branch%3Amaster+event%3Apush)

# start

```shell
nohup java -Dspring.config.location=application.yml -Xmx4g -Xms2g -XX:+UseG1GC -verbose:gc -Xloggc:/home/work/log/xtimer.gc.log -XX:+PrintGCDetails -XX:+PrintGCDateStamps -XX:+PrintPromotionFailure -XX:+PrintGCApplicationStoppedTime -XX:+PrintHeapAtGC -jar mtimer-broker-0.0.1.release.jar >/dev/null 2>&1 &
```
