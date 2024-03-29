# SimuladorRoboTerminalCoppelliaSim

## Parte 2 do projeto da disciplina de Visão Computacional Aplicada a Testes da residência em Robótica e Inteligência Artificial aplicadas a testes de software da Softex/CIn-UFPE. Neste projeto é usado um código de reconhecimento facial feito em python com o auxílio da biblioteca de visão computacional open source chamada OpenCV para reconhecer os rostos e treinar o software a indentificar os mesmos através de aprendizagem de máquina (machine learning). É utilizado também um simulador de braços robóticos com terminal de mesário e urna eletrônica (todos virtuais) que se encontra neste perfil do GitHub no repositório VerificacaoFacialRoboTerminalCoppellia. Ao seguir os passos abaixo pode-se usar o código de reconhecimento facial, outro código para treinar o software a reconhecer os rostos e por fim um último código para associá-los aos seus respectivos títulos de eleitores e se conectar ao simulador CoppelliaSim para então o braço robótico digitar esses títulos no terminal e urna virtuais.

## Para o funcionamento total do projeto, faz-se necessário seguir os seguintes passos:

1 - Clonar este repositório e abrir seu diretório local.

2 - Clonar o repositório VerificacaoFacialRoboTerminalCoppellia que se encontra neste perfil do GitHub e abrir seu diretório local.

3 - Copiar todos os arquivos contidos no repositório local SimuladorRoboTerminalCoppelliaSim e colar no repositório local VerificacaoFacialRoboTerminalCoppellia.

4 - Fazer o download do simulador CoppelliaSim.

5 - Dentro do repositório local VerificacaoFacialRoboTerminalCoppellia procurar o arquivo/cena MontagemUrnaeNiryo.ttt e abrir no simulador CoppelliaSim.

6 - No simulador CoppelliaSim clicar no botão play/run.

7 - Abrir o diretório do repositório local VerificacaoFacialRoboTerminalCoppellia em uma IDE de sua preferência.

8 - Na IDE abrir o arquivo faceRecog.py, fazer os importes necessários das linhas 1, 2 e 3, mudar o nome da pessoa a qual será feito o reconhecimento facial na linha 5, mudar a rota da pasta Data para o local onde ela se encontra em seu computador na linha 6, apertar o botão run, abrirá uma janela com a sua câmera ligada para fazer o reconhecimento facial, mover lentamente o rosto da pessoa para cima, para baixo, para a esquerda e para a direita.

9 - Ainda na IDE, dentro do repositório VerificacaoFacialRoboTerminalCoppellia, abrir o arquivo treinando.py, fazer os importes necessários das linhas 1, 2 e 3, mudar a rota da pasta Data para o local onde ela se encontra em seu computador na linha 5 e um arquivo .xml será criado no repositório local treinando assim a sua máquina e realizando machine learning.

10 - Ainda na IDE, dentro do repositório VerificacaoFacialRoboTerminalCoppellia, abrir o arquivo reconhecimentoFacial.py, fazer os importes necessários das linhas 1, 2, 3 e 5 e mudar a rota da pasta Data para o local onde ela se encontra em seu computador na linha 7, apertar o botão run, abrirá uma janela com a sua câmera ligada para fazer o reconhecimento facial.

11 - No simulador CoppelliaSim os braços robóticos irão digitar o título de eleitor do rosto identificado no terminal virtual do mesário e na urna eletrônica virtual.
