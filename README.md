# Extração de dados do Bike Sampa 🚲

Esse repositório contém um notebook para extrair os dados de notificação dos
e-mails enviados pelo [Bike Sampa](https://bikeitau.com.br/bikesampa/) no formato compatível com o [meu notebook do
ObservableHQ]() para explorar essas informações.

## Como utilizar?

Para utilizar esse notebook é necessário que você exporte os seus e-mails no
mesmo formato que o Google Takeout exporta os e-mails do Gmail, que foi a
ferramenta que eu utilizei. Usando o Google Takeout os passos são os seguintes:

1. Agrupar todos os e-mails do Bike Sampa numa mesma tag.
2. Ir até Google Takeout e solicitar somente os e-mails dessa tag.
3. Baixar extrair os e-mails exportados que foram enviados para o seu e-mail.
4. Executar o notebook com caminho principal apontando para o arquivo \*.mbox

Ao final do notebook deve existir um arquivo bikesampa.csv que pode ser 
anexado ao notebook do ObservableHQ para serem explorados.
