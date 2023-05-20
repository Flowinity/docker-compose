![TroploPrivateUploader Banner](https://i.troplo.com/i/9ea16d8ab178.png)
# TPU Docker Repository
1. Git clone this repository
2. Run `DB_DATABASE=tpu DB_USER=tpu DB_PASSWORD=REPLACE_ME DB_ROOT_PASSWORD=REPLACE_ME docker-compose up -d`
3. Go through the TPU Setup Wizard on http://localhost:34582
4. You must change the MariaDB server hostname to `mariadb` and the redis hostname to `redis` in the setup wizard. (seen below):
![Setup Wizard](https://i.troplo.com/i/87987421cfa1.png)
![Setup Wizard](https://i.troplo.com/i/582d2fd8d1a7.png)
5. Setup NGINX using the example `nginx.conf`. There's more detailed instructions about the TPU/NGINX setup on the [main repository](https://github.com/Troplo/PrivateUploader).
