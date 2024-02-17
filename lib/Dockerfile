FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/darknim999/DARK-NIM-MD /root/darknim999
WORKDIR /root/darknim999/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
