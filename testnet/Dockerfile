FROM hx2a/dogecoind:latest

EXPOSE 44555 44556

USER root
ADD dogecoin.conf /dogecoin/.dogecoin/dogecoin.conf
RUN chown -R dogecoin:dogecoin /dogecoin/.dogecoin
USER dogecoin

