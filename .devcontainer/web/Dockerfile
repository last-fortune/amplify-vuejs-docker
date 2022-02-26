FROM node:16.14.0
# java for Amplify Mock
RUN apt update; apt install -y wget software-properties-common apt-transport-https
RUN wget -O- https://apt.corretto.aws/corretto.key | apt-key add - 
RUN add-apt-repository 'deb https://apt.corretto.aws stable main'
RUN apt update; apt-get install -y java-18-amazon-corretto-jdk
# git-flow
RUN apt install git-flow
# vue & amplify
RUN npm install -g npm@8.5.1
RUN npm install -g @aws-amplify/cli@7.6.22
RUN npm install -g @vue/cli@5.0.1
