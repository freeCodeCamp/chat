Usage:

1. Create a .env

   ```txt
   ROCKETCHAT_VERSION=latest
   PORT=3000
   ROOT_URL=http://localhost:3000
   MONGO_URL=mongodb://urlforthedatabase:27017/rocketchat
   MONGO_OPLOG_URL=mongodb://urlforthedatabase:27017/local

   INSTANCE_IP=<ip of the local instance>

   INSTANCE_IP_ALPHA=<ip of the first instance>
   INSTANCE_IP_BRAVO=<ip of the other instance>
   ```

2. Replace the keys with required values

3. Run rocket-chat server

   ```console
   docker-compose config
   docker-compose up -d
   ```
