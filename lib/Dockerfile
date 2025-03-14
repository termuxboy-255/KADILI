FROM quay.io/gurusensei/gurubhay:latest

RUN git clone https://github.com/termuxboy-255/KADILI/root/global

WORKDIR /root/global/

RUN npm install --platform=linuxmusl

EXPOSE 5000

CMD ["npm", "start"]
