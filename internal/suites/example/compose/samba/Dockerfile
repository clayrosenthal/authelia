FROM alpine:3.19.0

RUN \
apk add --no-cache \
  bash \
  krb5 \
  openldap-clients \
  samba-dc \
  supervisor

CMD /init.sh setup
