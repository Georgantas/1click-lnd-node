
To start lnd, use command `docker-compose up`, and wait a minute. 

To access your lnd container use `docker exec -it lnd bash`. Use `lncli create` to create a new wallet, and `lncli unlock` to unlock it. With an unlocked wallet, you can use the Thunderhub GUI to interact with your node (visit `localhost:3000` in your web browser).
