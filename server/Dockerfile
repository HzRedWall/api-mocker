FROM registry.cn-hangzhou.aliyuncs.com/wtx/node-nginx:latest
COPY . /app/
RUN npm config set sass-binary-site http://npm.taobao.org/mirrors/node-sass
RUN npm install && npm start
CMD ["nginx","-g","daemon off;"]
