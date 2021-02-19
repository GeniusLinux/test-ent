#FROM geniuslinux/test-ent:base
FROM docker.pkg.github.com/geniuslinux/test-ent/test.base:latest

RUN mkdir -p /root/ci-platform
COPY --from=geniuslinux/test-ent:toolchain /root/toolchain/toto /root/ci-platform/
