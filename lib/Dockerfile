FROM quay.io/lyfe00011/md:beta
RUN git clone https://github.com/dark-vro/WhatsAsena-MD.git /xasena
WORKDIR /xasena
RUN yarn install --network-concurrency 1
CMD ["node", "index.js"]
