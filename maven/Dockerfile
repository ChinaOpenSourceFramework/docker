###########################################
#
#   maven 3.3.9
#
###########################################

FROM liqiweidocker/java

ENV M2_HOME=/project/apache-maven-3.3.9
ENV PATH ${M2_HOME}/bin:$PATH

# install maven

RUN wget http://mirrors.tuna.tsinghua.edu.cn/apache/maven/maven-3/3.3.9/binaries/apache-maven-3.3.9-bin.tar.gz

RUN tar zxvf /apache-maven-3.3.9-bin.tar.gz -C /project

RUN rm -f /apache-maven-3.3.9-bin.tar.gz
