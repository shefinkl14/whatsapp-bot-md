FROM quay.io/shefin/alexa:md
RUN git clone https://github.com/shefinkl14/whatsapp-bot-md.git /root/Alexa/
WORKDIR /root/Alexa/
RUN yarn install --network-concurrency 1
CMD ["node", "index.js"]
