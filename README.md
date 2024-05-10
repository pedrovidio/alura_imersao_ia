# VAR AI - Detecção de Impedimento em Futebol

Este projeto utiliza inteligência artificial para auxiliar na análise de impedimentos em partidas de futebol, simulando a função do VAR (Árbitro Assistente de Vídeo). 

## Descrição

O projeto consiste em um modelo de IA que analisa imagens de lances de futebol e identifica se há jogadores em posição de impedimento no momento exato do passe. 

## Funcionamento

1. **Envio da imagem:** O usuário envia uma imagem do lance em questão.
2. **Análise da imagem:** A IA processa a imagem, identificando os jogadores, a bola e a linha de impedimento.
3. **Detecção de impedimento:** O modelo determina se algum jogador está em posição de impedimento no momento do passe, considerando a posição de seus pés, cabeça e tronco em relação à linha de impedimento e ao penúltimo defensor.
4. **Intervenção do VAR:** O usuário pode interagir com o sistema, solicitando informações adicionais sobre o lance, como o número da camisa do jogador em possível impedimento e quais partes do seu corpo estão à frente da linha. Com base nessas informações, o usuário decide se o VAR deve intervir ou não.


## Próximos passos

* Melhorar a precisão do modelo de IA.
* Implementar a detecção automática da linha de impedimento.
* Permitir a análise de vídeos, em vez de apenas imagens estáticas.
* Criar uma interface gráfica para facilitar a interação com o sistema.
