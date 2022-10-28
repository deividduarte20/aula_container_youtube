## Persiste na criação de um container no qual o mesmo traz o debian com vários pacotes instalados (Imagem criada com intuito de testes)

- ansible</br>
- wget</br>
- aws cli</br>
- terraform</br>
- helm</br>
- kubectl</br>
- curl</br>
- vim</br>

### Para buildar imagem
`docker build -t deividdua/debian-pacotes`

### Para rodar o container de forma que entre no mesmo e que seja excluído automaticamente ao sair
`docker run -ti --rm -v $PWD:/app deividdua/debian-pacotes`
