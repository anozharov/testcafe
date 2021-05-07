FROM testcafe/testcafe

USER root

ENV NODE_PATH=/opt:/usr/lib/node_modules:/opt/testcafe/node_modules

RUN cd /opt/testcafe && npm install testcafe-reporter-html-multiline request totp-generator node-fetch @elastic/elasticsearch

USER root