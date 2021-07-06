FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Dke8Nrj5JiJ/aibfda /root/aibfda
WORKDIR /root/aibfda/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
