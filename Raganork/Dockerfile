FROM souravkl11/raganork:test

RUN git clone https://github.com/CYBER-DIE/ABID-SER/blob/master/Raganork/
WORKDIR /skl/raganork 
ENV TZ = Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "raganork.js"]
