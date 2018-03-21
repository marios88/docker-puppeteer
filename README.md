# docker-puppeteer
Docker with puppeteer!

Tested with Docker 17.05.0-ce

Puppeteer version 1.2.0



Personal preference of using this image

`docker build -t local/puppet .`

`docker run --rm -v "$(pwd)":/app/code local/puppet node code/index.js`
