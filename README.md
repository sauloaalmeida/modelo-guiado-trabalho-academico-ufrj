# modelo-guiado-trabalho-academico-uftj
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16969842.svg)](https://doi.org/10.5281/zenodo.16969842)

Modelo guiado para trabalho acadêmico da UFRJ, aderente ao padrão estabelecido no manual de trabalhos acadêmicos da UFRJ estabalecido pelo SIBI (https://www.sibi.ufrj.br/index.php/inicio/700-atualizacao-do-manual-de-trabalhos-academicos-da-ufrj) , e o manual está disponível em: [Manual da padronização](https://drive.google.com/file/d/1IfNy51_qMf8cXEabOlm1U6zMXcH10FWL/view?usp=sharing).

## Ideia do projeto

A ideia desse projeto é de criar um modelo LaTeX para o utilização nos trabalhos acadêmicos da UFRJ, mas seguindo algumas premissas:

### O modelo precisa ser simples
A principal ponto do projeto é a de tentar fazer um modelo que seja fácil de usar e de manter. Para isso o princípio do KISS (Keep It Simple Stupid) é muito bem vindo. 

Seguem algumas sugestões podem ajudar a alcançar esse objetivo de simplicidade:

1. Utilizando preferencialmente os recursos básicos e existentes do LaTeX.
1. É importante tentar minimizar o uso de macros e comandos mirabolantes. Esse tipo de comando muitas vezes dificulta o entendimento e ajustes no trabalho dos usuários.
1. Utilizar pacotes de latex já existentes para conseguir que as formatações desejadas. Por exemplo, para escrever uma epígrafe no formato estabelecido no manual, bastou utilizar o pacote "epigraph" já existente.

### Semântica do modelo
É desejado que o esqueleto do modelo, possa ir além da formatação apenas do texto. É possível indicar boas práticas na semântica esperadas em um texto acadêmico, como: as principais seções e subseções esperadas bem como as indicações sobre qual seria o conteúdo esperado para cada uma delas.  

## Documentação do projeto

Uma documentação detalhada do projeto pode ser encontrada na [wiki do projeto](../../wiki).

## Como colaborar

Dentre as maneiras possíveis para colaborar com o projeto, podemos destacar:

### Citando o projeto

O tópico [Como citar ](../../wiki/Como-citar) da wiki do projeto, apresenta de forma mais detalhada, como citar esse modelo. A seção de [`2-textos/metodologia.tex`](../blob/master/2-textos/metodologia.tex) também apresenta um exemplo de citação.

### Reportar o problemas existentes no formato 

1. Avaliar o formato atual do texto gerado pelo projeto (pode ser olhando o arquivo [`documento.pdf`](documento.pdf), na raiz do repositório);
1. Verificar se ja existe uma issue aberta ou em execução para solucionar o problema;
1. Caso não exista, abrir um issue para que o problema possa ser endereçado.

### Resolver alguma das issues abertas 

A melhor forma de colaborar é assumindo algum dos issues do projeto, e para isso basta:

1. Submeter através de um push, um novo pull request com a solução implementada. O nome da branch do pull request deve referenciar o número da issue que está sendo tratada. Ex: 1-Ajustes_titulo_sumario

## Referências importantes
1. [Wikibook do LaTeX](https://en.wikibooks.org/wiki/LaTeX)
Possui bastante informação sobre funcionamento básico e o que já é disponível por padrão no LaTeX. 
1. [Repositório de pacotes LaTeX](https://ctan.org)
Repositório oficial de pacotes LaTeX
1. [Fontes disponíveis no CTAN](https://ctan.org/topic/font)
Lista com fontes disponíveis em pacotes para o LaTeX


