FROM alpine:latest

RUN apk add --no-cache sqlite
WORKDIR /data

CMD [\
sqlite3\, \/data/database.db\, \.databases\]
