ARG VERSION

FROM HariprasadAllaka1612/presto-base:${VERSION}
MAINTAINER HariprasadAllaka1612

ADD etc /usr/local/presto/etc

EXPOSE 8080

WORKDIR /usr/local/presto
ENTRYPOINT ["./scripts/presto.sh"]
