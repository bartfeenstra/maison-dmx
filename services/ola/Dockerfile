FROM bartfeenstra/ola:0.2.0

USER root

COPY ./conf /usr/lib/olad/.ola/
RUN chown -R olad /usr/lib/olad/.ola/

USER olad
