# Posso Ler?
É um projeto open source criado com o intuito de democratizar o acesso à informação, pois nesse momento, em meio a tantas _fake news_, é mais que fundamental ter acesso a notícias e conteúdos de fontes confiáveis. Com a extensão __Posso Ler?__ você é capaz de visualizar notícias e conteúdos exclusivos de alguns jornais e sites. [Ir para site](https://possoler.tech)
<br>
<br>
## Sites Suportados

* [Folha de São Paulo](https://www.folha.uol.com.br/)
* [Estadão](https://www.estadao.com.br/)
* [Gazeta do Povo](https://www.gazetadopovo.com.br/)
* [O Globo](https://oglobo.globo.com/)
* [Super Interessante](https://super.abril.com.br/)
* [Quatro Rodas](https://quatrorodas.abril.com.br/)
* [Veja](https://veja.abril.com.br/)
* [Responde Ai](https://www.respondeai.com.br/)
* [Exame](https://exame.com/)
* [Guia do Estudante](https://guiadoestudante.abril.com.br/)
* [Revista Época](https://epoca.globo.com/)
* [Revista Época Negocios](https://epocanegocios.globo.com/)
* [Revista Galileu](https://revistagalileu.globo.com/)
* [Revista Marie Claire](https://revistamarieclaire.globo.com/)
* [Revista Globo Rural](https://revistagloborural.globo.com/)
* [Pequenas Empresas Grandes Negócios](https://revistapegn.globo.com/)
* [JOTA](https://www.jota.info/)
* [NSC Total](https://www.nsctotal.com.br/home)
* [New York Times](https://www.nytimes.com/)
* [El País](http://elpais.com/)
* [Jornal VS](https://www.jornalvs.com.br/)
* [Valor Econômico](https://valor.globo.com/) - Ler sobre <i>**Cache Mock**</i> na seção de <i>Perguntas Frequentes</i>
* [GaúchaZH](https://gauchazh.clicrbs.com.br/)
* [Jornal do Comércio](https://www.jornaldocomercio.com/)
* [The Economist](https://www.economist.com/)
* [Brainly](https://brainly.com.br/)

## Perguntas Frequentes

### Como o "Posso Ler?" remove os bloqueios?
Logo após todo o conteúdo da página ser carregado e renderizado, o script realiza manipulação da DOM para mudar as propriedades dos elementos da página e excluir todos os bloqueios exibidos para o usuário não assinante. Dentre essas alterações, estão remoções de scripts dentro da página que são responsáveis por esses bloqueios.
<br>
<br>
### Mas isso não é ilegal ou imoral?
Como dito anteriormente, todas as modificações feitas pela extensão ocorrem na DOM (somente na exibição de cada site no respectivo aparelho em que está sendo acessado). Desta forma, a ferramenta não utiliza nenhum método de roubo ou violação de dados, como por exemplo, invadir um banco de dados protegido para ter acesso a tal informação para disponibilizá-la. O que ela faz, é somente mudar o modo de exibição da informação já fornecida pelos sites de forma que os usuários consigam vê-las sem nenhum bloqueio de exibição.
As empresas responsáveis pelos sites poderiam adotar outras formas mais eficazes para o bloqueio da exibição da informação, como por exemplo, verificar primeiro se o usuário está logado com sua conta de assinante, e caso positivo, disponibilizar o conteúdo. Contudo, há um grande problema em fazer isso, pois, adotando esse método, as empresas teriam que abrir mão do SEO (conjunto de técnicas que têm como objetivo posicionar uma ou mais páginas de destino entre os melhores resultados dos motores de pesquisa.)

**LEMBRE-SE**: Os jornais precisam pagar seus funcionários e as assinaturas são uma fonte de renda para isso. Ao usar o "Posso Ler?" NÃO USE Ad blockers, pois os jornais também necessitam de uma fonte de renda para manter seu funcionamento.
<br>
<br>
### Como faço para reportar um bug ou dar uma sugestão/feedback?
Caso tenha encontrado um bug ou queira dar uma sugestão/feedback, escreva um email para **thomazf.dev@gmail.com**. Tentarei responder o mais rápido possível, pois estarei ocupado me dedicando à faculdade e ao meu serviço.
<br>
<br>
### O que é Cache Mock?
Cache Mock (Simulação por Cache) é uma técnica que desenvolvi para conseguir burlar de forma legal alguns sites que utilizam hard paywall. Essa técnica se define em utilizar o cache da própria página gerado pelo Google e, partir dela, pegar todo o conteúdo e renderizá-lo para o usuário. Como o cache é uma "cópia" do conteúdo estático de uma página, geralmente estas não possuem nenhum tipo de bloqueio de conteúdo, possibilitando o acesso a eles.
<br>
<br>
### Observações sobre o Cache Mock
Alguns sites utilizam proteção de hard paywall em seus conteúdos. Geralmente, conteúdos com esse nível de proteção ficam armazenados no servidor e só são renderizados na tela do usuário (cliente) quando o sistema tem a certeza de que o mesmo se encontra logado em sua conta de assinante. A solução encontrada para contornar este caso, foi utilizar o cache da página gerado pelo Google, como foi explicado no tópico acima. Contudo, caso a notícia seja muito recente, é capaz do cache da página em questão não ter sido gerado ainda, e caso esse seja o ocorrido, ao tentar desbloquear a notícia, a extensão informará a você por um pop-up que não foi possível desbloquear o conteúdo no momento e que você poderá tentar mais tarde. Ou seja, nem sempre será possível desbloquear todos os conteúdos. Pode ocorrer também da API que faz a conexão entre a extensão e o cache ficar indisponível devido ao excesso de requisições feitas a partir de um mesmo endereço de IP (Isso é uma medida de segurança a fim de evitar ataques DDoS). Caso isso ocorra, um pop-up aparecerá em sua tela informando que o serviço está temporariamente indisponível. Nesse caso, não há muito o que fazer além de esperar seu endereço de IP ser liberado novamente para fazer requisições para a API.
<br>
<br>
**Ponto de atenção:** Por se tratar de dados obtidos à partir do cache, o conteúdo apresentado pode estar desatualizado em relação a página original caso a mesma tenha tido alguma alteração após a última geração de cache feita pelo Google.
<br>
<br>
<br>
<br>

 >"O direito à informação é considerado um direito fundamental numa sociedade democrática"
 
Made with ❤️ by Thomaz Ferreira
