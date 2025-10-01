# WhiteList

# Ativar/desativar whitelist
docker exec -it minecraft-server rcon-cli whitelist on
docker exec -it minecraft-server rcon-cli whitelist off

# Adicionar/remover jogadores
docker exec -it minecraft-server rcon-cli whitelist add NomeJogador
docker exec -it minecraft-server rcon-cli whitelist remove NomeJogador

# Listar whitelist
docker exec -it minecraft-server rcon-cli whitelist list

# Recarregar whitelist
docker exec -it minecraft-server rcon-cli whitelist reload
