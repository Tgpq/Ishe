FROM RepthonArabic/userbot_Whatsapp
RUN git clone https://github.com/RepthonArabic/userbot_Whatsapp /root/RepthonArabic
WORKDIR /root/RepthonArabic/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
