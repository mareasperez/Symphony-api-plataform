FROM nginx:1.19

ARG UID
EXPOSE ${UID}
RUN echo ${UID}
RUN adduser -u ${UID} --disabled-login --gecos "" appuser

COPY default.conf /etc/nginx/default.conf