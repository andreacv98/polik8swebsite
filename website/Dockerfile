# syntax=docker/dockerfile:1
FROM klakegg/hugo:0.91.0-onbuild AS hugo

FROM nginx
COPY --from=hugo /target /usr/share/nginx/html
