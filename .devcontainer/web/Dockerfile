FROM node:16.15.1
# java for Amplify Mock
RUN apt update; apt install -y wget software-properties-common apt-transport-https
RUN wget -O- https://apt.corretto.aws/corretto.key | apt-key add -
RUN add-apt-repository 'deb https://apt.corretto.aws stable main'
RUN apt update; apt-get install -y java-18-amazon-corretto-jdk
# git-flow
RUN apt install git-flow
# vue & amplify
RUN yarn global add @aws-amplify/cli@9.0.0
RUN yarn global add @vue/cli@5.0.6