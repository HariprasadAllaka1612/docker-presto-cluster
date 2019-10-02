ARG VERSION

FROM HariprasadAllaka1612/presto-base:${VERSION}
MAINTAINER HariprasadAllaka1612

COPY etc /usr/local/presto/etc
EXPOSE 8081

WORKDIR /usr/local/presto
ENTRYPOINT [ "./scripts/presto.sh" ]
