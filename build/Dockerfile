FROM alpine:3.8

RUN apk upgrade --update --no-cache

USER nobody

ADD build/_output/bin/kubevirt-management-operator /usr/local/bin/kubevirt-management-operator
