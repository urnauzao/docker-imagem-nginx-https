# Ambiente de Desenvolvimento 

## Realizar o build da imagem docker
```sh
docker compose build
```

## Realizar o up da imagem docker
```sh
docker compose up
```

# Ambiente de Produção
- Ter configurado o server_name corretamente no arquivo `./nginx/sites-available/app.conf`
- Execute o comando `sh sh-up.sh` para realizar todos os processos necessários para rodar a imagem no ambiente.
## Criando certificado
- Acesse o container docker do nginx, e então execute o seguinte comando:
```sh
certbot --nginx
```
- Feito isso basta seguir informações e configurando as configurações que forem solicitadas.

## Renovar certificado
- Repita o mesmo passo da criação de certificado

