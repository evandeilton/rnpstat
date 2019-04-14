# Introdução

R é uma das linguagens que mais cresce atualmente no mundo da programação científica. 
Esta linguagem tem sido uma das mais requisitadas por empresas, centros de pesquisa e por 
recrutadores das áreas de analytics e data science. Isso graças ao poder de processamento, 
aos recursos e à sua capacidade de expansão. R é uma linguagem científica, cross-plataforma, 
orientada a objetos, free e open source com uma comunidade de desenvolvedores e colaboradores 
global extremamente ativa.

# Estatística Descomplicada com R

Bem vindo ao primeiro módulo de **Estatística descomplicada com o R** que é uma produção exclusiva para do 
projeto R NA PRÁTICA. Esta série será composta por quatro módulos e neste primeiro, abordaremos os principais 
conceitos estatísticos e análise descritiva. O objetivo maior desta parte é revisar os conceitos mais 
importantes do inicio dos estudos estatísticos. Abordaremos a parte conceitual com algumas definições 
e termos estatísticos, tabelas de frequências, bem como as principais medidas descritivas (média, mediana e outras).
Veremos por fim, os principais gráficos estatísticos mais utilizados. Para reforçar os conhecimentos, 
faremos exercícios práticos com apoio do R com foco em bases de dados reais do INEP - Instituto Nacional
de Estudos e Pesquisas Educacionais Anísio Teixeira do ano de 2017.

No final deste módulo você será capaz de:

  * Definir estatística;
  * Compreender os principais tipos de variáveis e entender as melhores técnicas paracada tipo de variável;
  * Entender o que é e como utilizar tabelas de frequências;
  * Trabalhar com as principais medidas estatísticas (media, mediana, desvio padrão, etc.);
  * Entender correlação e covariância;
  * Construir gráficos estatísticos para os tipos corretos de dados com o pacote ggplot2.

-------------------------------

## R NA PRÁTICA

O **R NA PRÁTICA** foi originalmente uma ideia que surgiu com o desejo de ajudar a disseminar a linguagem R como uma ferramenta de apoio para o estudo de ciência de dados para pessoas de todos os níveis. A ideia do **R NA PRATICA** cresceu e tornou-se um projeto de maior abrangência envolvendo os temas como a propría programação em R, Estatística e probabilidade e _Data Science_.

## Programa integrado

O R NA PRATICA engloba cinco módulos. O primeiro já está completo e disponível. Os demais estão em fase de desenvolvimento:
 
  * Módulo - I   (Data Wrangling com R para Ciência de Dados)
  * Módulo - II  (Estatística descomplicada com R)
  * Módulo - III (Introdução à probabilidade com R)
  * Módulo - VI  (Testes de hipóteses com R)
  * Módulo - V   (Modelagem estatística com R)

### Módulo - I (Data Wrangling com R para Ciência de Dados)

Neste módulo exploramos o conceito Data Wrangling que é um tanto genérico em nosso português brasileiro, mas poderia ser traduzido como disputa/briga/luta de dados. Esta disputa está intimamente ligada ao processo de transformação de dados para obter conhecimento e isso inclui: obtenção, transformação, limpeza, agregação, visualização e criação de bases limpas para fins de Analytics na Ciência de Dados.

Neste módulo o aluno aprenderá:
<https://www.udemy.com/r-na-pratica-ciencia-de-dados/>

  * Operadores, sequências, funções, loops, família apply e gráficos dos sistemas base, lattice e ggplot2;   
  * Agregação, transformação, estatística descritiva de dados e tabelas de frequências;   
  * Dominará a criação de códigos otimizados em R com o moderno operador pipe "%>%" e os pacotes do tidyverse;   
  * Terá domínio sobre o processo de obtenção de conhecimento a partir de dados passando pelo ciclo de análise de situação problema, obtenção de dados, preparação, análise, visualização e comunicação de resultados com R Markdown;   
  * Será capaz de resolver cases de estudo e problemas com dados e situações reais.
  * Terá um vasto material de consulta com amostras de códigos e bases de dados de exemplos de todas as video aulas para reforçar seus conhecimentos e aplicações no dia-a-dia.

### Módulo - II (Estatística descomplicada com R )
Este livro é parte do segundo módulo do R NA PRÁTICA e está em constante atualização.

Em desenvolvimento (0%================80%=======100%)

### Módulo - III (Introdução à probabilidade com R)

Em desenvolvimento (0%====10%===================100%)

### Módulo - VI  (Testes de hipóteses com R)

Em desenvolvimento (0%==5%======================100%)

### Módulo - V   (Modelagem estatística com R)

Em desenvolvimento (0%=1%=======================100%)

# O pacote `rnp`

Muitas funções estão sendo criadas à medida em que o projeto ganha volume e os novos módulos vão sendo escritos. Para condensar tudo em um local apropriado e de fácil consulta, surgiu a ideia de empacotar estes recursos e disponibilizá-los aqui no github. Este é o pacote `rnp`.

Materiais como funções, algumas bases de dados e documentos disponibilizados aqui são para ajudar a todos que desejam aprender, melhorar, atualizar seus conhecimentos em R, Estatística e Ciência de dados e assim se destacar na descoberta de conhecimentos através de dados. 

## Bugs

Caso encontre algum bug ou tenha interesse em solicitar alguma inclusão de função, favor postar nas _issues_ do pacote [aqui](https://github.com/evandeilton/rnp/issues) para que possamos atender nas próximas atualizações do pacote.

### Instalação do pacote

```{r, eval=FALSE, echo=TRUE}
  # Se não tiver o devtools, instalar.
  if(!require(devtools)){
    install.packages("devtools")
  }
  # Instalar o rnp
  devtools::install_github("evandeilton/rnp")
  
  # Carregar o pacote
  require("rnp")
  ?rnp::rnp_freq
  
  # Vinheta
  # Se não tiver o prettydoc, a vinheta não roda
  if(!require(prettydoc)){
    install.packages("prettydoc")
  }
  vignette("rnp")
```
