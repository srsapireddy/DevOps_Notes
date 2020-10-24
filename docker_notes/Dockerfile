From java:latest
MAINTAINER ramki info@techmine.com
LABEL env=production
ENV apparea /data/app
Run mkdir -p $apparea
ADD ./gitbucket.war $apparea
WORKDIR $apparea
CMD ["java","-jar","gitbucket.war"]