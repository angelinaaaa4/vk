npm install @vkontakte/vk-tunnel –g
npx @vkontakte/create-vk-mini-app <zoomagasin>
cd <zoomagasin>
npm start
env NODE_TLS_REJECT_UNAUTHORIZED=0 \
PROXY_HTTP_PROTO=https \
PROXY_WS_PROTO=wss \
PROXY_HOST=localhost \
PROXY_PORT=10888 \
vk-tunnel
