FROM couchdb
RUN apt-get update; apt-get install -y --no-install-recommends python3-pip
RUN pip install couchdb

ENV COUCHDB_QUERY_SERVER_PYTHON "/usr/local/bin/couchpy"
