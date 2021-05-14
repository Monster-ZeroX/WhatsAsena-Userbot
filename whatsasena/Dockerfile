FROM fusuf/whatsasena:latest

RUN git clone https://github.com/kaviya-admin/WhatsAsena-Userbot /root/WhatsAsena-Userbot
WORKDIR /root/WhatsAsena-Userbot/
ENV TZ=Asia/Colombo
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
