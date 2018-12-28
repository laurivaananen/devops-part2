# FROM node
# WORKDIR /workdir
# COPY . .
# RUN npm install
# EXPOSE 5000

# RUN npm run build
# RUN npm install -g serve

# CMD ["serve", "-s", "-l", "5000", "build"]



FROM node
WORKDIR /workdir
COPY . .
RUN npm install
EXPOSE 5000
# ENV API_URL=http://localhost:8000
CMD ["npm", "start"]

