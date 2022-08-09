# Acessibilidade-WEB-Front-End---apeperia
Projeto de estudos de acessibilidade WEB com a página da apeperia.

Para verificar a acessibilidade, pode ser utilizado o leitor de tela NVDA, ou equivalente.

Aula 1: Há multiplas tags h1 no HTML da página. As tags h1 foram trocadas por tags h2, h3, h4 mantendo uma semântica e melhorando muito a acessibilidade para pessoas com deficiência de visão.

Aula 2: Foi alterada a tag "lang" de "en" para "pt-br", a fim de a corrigir o sotaque na leitura da tela. 

Foram adicionadas descrições "alt" nas imagens e foram feitas mudanças no logotipo da página, tendo em vista melhorar a compreensibilidade na navegação em modo acessibilidade.

Aula 3: Alterações no CSS para tirar estilização de bullets nas tags "li". O gênero neutro em "todxs" não é amigável a acessibilidade, por isso reformular a frase foi a saída encontrada para melhorar esse ponto. 

O checkbox não é identificado pelo leitor de tela se estiver com as propriedades "display none", ou "visibility hidden", então foi preciso utilizar a propriedade "position absolute" e jogar o checkbox original para o canto (valor 9999px).

Aula 4: Foi criado um link âncora para pular para o conteúdo principal da página. Atribuição de "role" à tag "main", para alguns leitores que já tem o artifício de pular a navegação. 

Utilização da tag "figure" e "figcaption" no lugar das "div" e "p", melhorando a semântica do HTML. Utilização da propriedade "aria-labelledby" para remover redundância de informação nas tags "figure".

Aula 5: Melhorias nas tags label e inputs, colocando placeholders significativos, propriedade "for" e "id" nas labels e inputs. 

Implementação da propriedade readonly nos campos desabilitados, a fim de tornar possível acesso pelos leitores de tela às informações contidas ali, ainda que desabilitadas para edição. 

Retirada da tag meta as propriedades que bloqueavam o zoom por parte do usuário. Implementação de controles e legendas no vídeo da seção institucional.