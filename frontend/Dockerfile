# Step 1: Build
FROM node:16-alpine
WORKDIR '/app'
COPY package.json .
RUN npm install
COPY . .
RUN npm run build

# Step 2: Take build and create nginx container
FROM nginx
EXPOSE 80
COPY --from=0 /app/build /usr/share/nginx/html