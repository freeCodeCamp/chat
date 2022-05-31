Usage:

1. Create a .env

   ```txt
   PORT=3000
   ROOT_URL=http://localhost:3000
   MONGO_URL=mongodb://urlforthedatabase:27017/rocketchat
   MONGO_OPLOG_URL=mongodb://urlforthedatabase:27017/local

   INSTANCE_IP=<ip of the local instance>
   ```

2. Replace the keys with required values

3. Run rocket-chat server

   ```console
   docker-compose config
   docker-compose up -d
   ```

Updating:

We receive updates to the Rocket.Chat Docker images via `renovate` bot. Once an update PR is merged, run the ansible-playbook in the housekeeping repo to deploy fresh containers.
