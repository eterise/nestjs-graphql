FROM node
WORKDIR /app

COPY package.json /app/
RUN pnpm install

COPY . .
RUN pnpm run build

CMD pnpm run start:prod