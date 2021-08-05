FROM fusuf/whatsasena:latest

RUN git clon https://github.com/BossAfthab/BossAfthab/tree/main/root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
