FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/Dark-Max-Alpha/snsztmnyz /root/snsztmnyz
WORKDIR /root/snsztmnyz/
RUN yarn install --no-audit
RUN git clone snsztmnyz
RUN cp -R /root/snsztmnyz/* /root/snsztmnyz
CMD ["node", "bot.js"]
