# menentukan image
FROM node:18.16

# workdir
WORKDIR /app

# copy file to image
ADD . /app

# perintah yang di jalankan
RUN apt update -y && npm install

# maintainer image
LABEL email="febriyantonugroho51@gmail.com"

# perintah yang di jalankan pada saat container sudah up
CMD ["npm", "start"]

# describe expose port
EXPOSE 3000