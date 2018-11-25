FROM mhart/alpine-node:10
RUN npm install -g textlint
RUN npm install -g \
  textlint-rule-no-dead-link \
  textlint-rule-no-todo
ENTRYPOINT ["textlint"]
