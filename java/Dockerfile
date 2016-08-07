##########################################
###
###   jak 8
###
##########################################

FROM liqiweidocker/base 

ENV JAVA_HOME /project/jdk1.8.0_101
ENV JRE_HOME ${JAVA_HOME}/jre
ENV CLASSPATH .:${JAVA_HOME}/lib:${JRE_HOME}/lib
ENV PATH ${JAVA_HOME}/bin:$PATH

ADD . /root

RUN wget --no-check-certificate --no-cookies --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u101-b13/server-jre-8u101-linux-x64.tar.gz

RUN tar zxvf server-jre-8u101-linux-x64.tar.gz -C /project/

RUN rm -rf server-jre-8u101-linux-x64.tar.gz
