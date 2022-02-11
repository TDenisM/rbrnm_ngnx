!!!https://github.com/traefik/whoami!!!

FROM alpine AS src
ADD https://rebrainme-workshop-apps.s3.amazonaws.com/nginx/whoami /whoami
RUN chmod +x /whoami
CMD ["/whoami", "-port", "8080"]

#FROM scratch
#COPY --from=src /whoami /whoami
#CMD ["/whoami", "-port", "8080"]
