FROM hypriot/rpi-alpine-scratch:v3.4
RUN apk update && apk upgrade && apk add bash sudo
RUN apk add ympd
EXPOSE 8080
CMD ["ympd", "-h", "mpd", "-p", "6600", "-w", "8080"]
