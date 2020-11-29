FROM minio/minio:RELEASE.2020-11-25T22-36-25Z
ENV MINIO_DIR=""
ENTRYPOINT minio gateway nas ${MINIO_DIR:-/minio}