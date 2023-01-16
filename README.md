# Teste prático para programador Front-end

O objetivo é conhecer sua habilidades usando CSS para desenvolver as características da página e JS para formatar datas, mascaras e manipular inputs. Use somente HTML, CSS e JS. Não pode usar outras linguagens como PHP, ASP.net... Você está livre para usar, pacotes de terceiros (WEBPACK) e frameworks!

### Desafio

O objetivo é seguir o layout que vamos apresentar. Ele é uma pequena aplicação com duas páginas. Cadastro e Exibição de conteúdo.



##### Regras do layout:

1. As caixas de inputs deveram ter a altura de 45px, 
2. A caixa do corpo de conteúdo e cadastro deve ter uma largura de 440px. 
3. A caixa do corpo de conteúdo e cadastro deve está centralizada no meio da página.
4. O Layout deve ser responsivo, portanto os inputs devem ficar com a largura de 100% quando atingir o padrão de dispositivo mobile.
5. Nos inputs você deve usar máscaras para o CPF (EX: 000.000.000-00) e telefone (EX: (00) 00000-0000, (00) 0000-0000). 
6. Consuma a api de CEPs para buscar a validação do endereço. API para busca de CEP: https://viacep.com.br/ws/{{CEP}}/json/ Você deve criar um metodo para quando receber os dados da API "autopreencher" os campos de cidade, bairro e logradouro.
7. Use caixinhas em vermelho (Modal ou snackbar) para printar os erros para o usuário.
8. Ao Cadastrar usar uma caixa (Modal) para exibir o sucesso do cadastro e ao clicar em "ok" a pessoa será redirecionada para a página de exibição.
9. Você deve validar os inputs obrigatórios e também validar a sequência do CPF. 
10. Os inputs (CPF, CEP e Número) devem aceitar somente números, não poderá aceirar letras.





![](https://github.com/aurenilson/front-end/blob/master/src/iPad–1.png)

##### Cadastro:

- Nome completo

- Cpf

- Telefone

- Email

- CEP

- Cidade

- Bairro

- Logradouro

- Número



##### Exibição:

Use o json "https://api.coindesk.com/v1/bpi/currentprice.json" para retornar os dados e serem exibidos para o usuário.

Imagem: https://b2329743.smushcdn.com/2329743/wp-content/uploads/2020/10/rompeu-bitcoin-supera-sua-maxima-historica-reais.jpg

link para imagem do SAC: https://assets.izap.com.br/clarearacessorios.com.br/uploads/img5b9aaaebbf94f.png

Os textos podem ser COPIADOS por aqui da imagem abaixo:

![](https://github.com/aurenilson/front-end/blob/master/src/iPad–2.png)



OBS: fique atento as cores, fontes e gramática. Seu layout será testado em diferentes dispositivos. Boa sorte!
