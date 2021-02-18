FROM node:10.16.3
RUN apt update && apt install net-tools -y && apt install vim -y
USER node
RUN mkdir -p /home/node/material-ui/project1
RUN chmod -R 777 /home/node/material-ui
WORKDIR /home/node/material-ui
CMD ["/bin/bash"]