FROM docker:17.03-dind
RUN apk add --update util-linux shadow && rm -rf /var/cache/apk/*
ADD entry.sh /entry.sh
RUN chmod a+x /entry.sh
CMD /entry.sh
