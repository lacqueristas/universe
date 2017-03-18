FROM vault:0.6.5

ENV APPLICATION='/vault'

WORKDIR $APPLICATION

RUN apk add --no-cache bash

COPY bin/ $APPLICATION/bin/

CMD bin/serve
