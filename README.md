# Criticas quando ao plugin web do HandTalk.me
As informações aqui contidas se aplicam ao software http://www.handtalk.me/, e
expressam minha opinião pessoal, que é válida para o dia 24 de outubro de 2016.
Tais afirmações poderão não ser válidas no futuro, e a pessoa leitora é
convidada a avaliar a pertinência, ou mesmo precisão, das afirmações aqui.

Este repositório surgiu da discussão iniciada em https://github.com/frontendbr/forum/issues/210,
onde um fundador do projeto respondeu. Ele se **refere a inclusão em sites, não
ao aplicativo para celulares**, e também **não questiona a qualidade do serviço**.

**TL;DR:**:

- **Você NÃO fere lei por não incluir este script proprietário**, ao contrário
do que o site poderia deixar subentendido
- **Deixa o site mais lento**: 208KB de arquivos para uma uma funcionalidade que
raramente vai ser usada. Note: não tenho críticas a 19MB necessário quando a solução
é usada
- **Requer JavaScript e extrema confiança nos sites que os usam**: ao requerer
JavaScript na mesma janela (não iframes) por padrão, isso dá completo poder sobre
o que ocorre, não apenas o leitor de tela
- **Os termos de uso abrem margem para uso para fins comerciais se a empresa for
comprada**, o combo muitos sites usando


## Do que esse feedback não trata
Esse feedback não aborda qualquer ponto quanto a qualidade do serviço final
propriamente dito. Não tenho experiência na área para comentários positivos
ou de pontos de melhoria sobre o serviço em si.

## Dos pontos de melhoria

_Nota: boa parte desses pontos não tem como serem resolvidos porque dependem
disso para a aplicação web funcionar. O ideal seria, no mínimo, que pessoas
tenham opção de só carregar JavaScript e dar poder ao Hand Talk se algum
link for clicado, ou mesmo que o Hand Talk seja uma extensão para navegador,
não algo a ser adicionado por padrão em todos os sites.

### Apelo à autoridade

De http://www.handtalk.me/sobre#lbi:

> "Art. 63. É obrigatória a acessibilidade nos sítios da internet  mantidos por empresas com sede ou representação comercial no País ou por órgãos de governo, para uso da pessoa com deficiência, garantindo-lhe acesso às informações disponíveis, conforme as melhores práticas e diretrizes de acessibilidade adotadas internacionalmente."

Dos principais motivos que me levaram a escrever isso, ao contrário de boas
práticas, como uso das WCAG, a inclusão de scripts proprietários NÃO é um
requerimento para cumprir legislação brasileira.

Assim como críticas que faço na [Carta aberta ao Prêmio Nacional de Acessibilidade na Web](https://github.com/fititnt/carta-aberta-premio-nacional-acessibilidade-na-web),

### Obrigatoriedade de Uso de JavaScript: muito poder por padrão
Ao incluir JavaScript na _mesma janela_ e nao em um `iframe`, isso dá completo
poder. Isso é equivalente a [Cross-site scripting](https://pt.wikipedia.org/wiki/Cross-site_scripting)
e a garantia de não ocorrer é de que o servidor original não seja comprometido
(por exemplo, ocorra uma invasão) e também por questões políticas.



## Direitos de cópia - DMCA Fair Use

Eu não possuo qualquer relação com HandTalk.me, ou qualquer marca envolvida. As
informações aqui são comentários de carater educacional e de críticas, sem
interesse comercial. Sabia mais em https://www.dmca.com/FAQ/Fair-Use.