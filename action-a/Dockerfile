#!/bin/sh
FROM debian:9.5-slim

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["hello-github-actions/action-a/entrypoint.sh"]
