FROM tmvdl/android:app

WORKDIR /app

RUN cordova create busy com.brtmvdl.busy busy

WORKDIR /app/busy

COPY www/html www

RUN cordova platform add android

RUN cordova build android
