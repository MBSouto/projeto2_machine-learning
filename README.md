# Projeto II - Futuro dos Dados e Aplicação de Big Data  

## TEMA
Abalones - Agrupamento de Abalones baseado em características físicas.

## Descrição do tema

Abalones são moluscos marinhos notáveis, conhecidos por suas conchas multicoloridas e saborosa carne. Encontrados em diversas regiões do mundo, esses gastrópodes desempenham um papel vital nos ecossistemas marinhos, auxiliando na saúde dos recifes de algas. Na joalheria, as conchas de abalone são altamente valorizadas pela sua beleza única. Apresentam uma lenta taxa de crescimento e graças à ação do tempo, as conchas mais antigas tendem a ser mais raras e valiosas, exibindo iridescência mais complexa e cores vibrantes, tornando-as peças cobiçadas para criações de joias exclusivas.

A idade do abalone é determinada cortando a concha através do cone, tingindo-a e contando o número de anéis através de um microscópio - uma tarefa tediosa e demorada.Assim, outras medidas, mais fáceis de obter, são usadas para prever a idade. Mais informações, como padrões climáticos e localização (e, portanto, disponibilidade de alimentos) podem ser necessárias para resolver o problema.

Técnicas de mineração de dados, como clustering, são essenciais para transformar grandes volumes de dados em insights. É amplamnte utilizada com o objetivo de agrupar objetos similares em clusters ou grupos para identificar padrões e segmentos em conjuntos de dados complexos.Assim, criaremos um modelo que seja capaz de agrupar os abalones baseado em pesos, medidas e sexo, entre outras características a fim de visualizar padrões nas conchas utilizadas na fabricação de jóias.



## Objetivo

Criar um modelo que seja capaz de agrupar os abalones baseado em pesos, medidas e sexo, entre outras características a fim de visualizar padrões nas conchas utilizadas na fabricação de jóias.
Determinar faixa etária de abalones, bem como similaridades das conchas a partir de medidas físicas utilizando técnicas de agrupamento.

##Especificação Técnica:
Abalone Data:

Fonte: UCI Machine Learning Repository

Descrição: O conjunto de dados contém características físicas dos abalones, uma éspecie de gastrópode que possui carne saborosa utilizada pela alta gastronomia e uma valiosa concha muito cobiçada pela indústria de jóias.

Campos da Base de Dados:

* Sexo: M (masulino), F (feminino) e I (infantil)
        Tipo: Nominal
* Comprimento: Medida mais longa da concha em mm
        Tipo: Contínuo
* Diâmetro: Medida perpendicular ao comprimento em mm
        Tipo: Contínuo
* Altura: Medida com carne na concha em mm
        Tipo: Contínuo
* Peso total: Abalone inteiro bem gramas
        Tipo: Contínuo
* Peso limpo: Peso da carne em gramas
        Tipo: Contínuo
* Peso das vísceras: Peso das vísceras em gramas (após o sangramento)
        Tipo: Contínuo
* Peso da casca: Após ser seco em gramas
        Tipo: Contínuo
* Anéis: somado a  +1,5 dá a idade em anos
        Tipo: Inteiro

**Métodos de Machine Learning Utilizados**

Pré-processamento dos Dados:

*  Normalização ou padronização dos dados para garantir que todas as variáveis estejam na mesma escala.
*  Tratamento de valores ausentes e inconsistências nos dados.

Algoritmos de Clustering:
*  K-Means: Algoritmo de clustering particional que divide os dados em K clusters baseados na minimização da distância intra-cluster.
