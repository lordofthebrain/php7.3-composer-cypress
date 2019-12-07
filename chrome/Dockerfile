FROM lordofthebrain/php7.3-composer-cypress:buster
RUN echo "deb http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list \
    && curl -s https://dl-ssl.google.com/linux/linux_signing_key.pub --output linux_signing_key.pub \
    && apt-key add linux_signing_key.pub \
    && apt-get update \
    && apt-get install -y google-chrome-stable \
    && apt-get clean
