FROM liqiweidocker/maven

RUN wget http://mirrors.tuna.tsinghua.edu.cn/apache/tomcat/tomcat-8/v8.5.4/bin/apache-tomcat-8.5.4.tar.gz

RUN tar zxvf /apache-tomcat-8.5.4.tar.gz -C /project

EXPOSE 8080

CMD /project/apache-tomcat-8.5.4/bin/catalina.sh run
