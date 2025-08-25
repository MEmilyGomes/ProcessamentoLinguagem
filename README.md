<img src="https://pages.cnpem.br/workshopbioimagens/wp-content/uploads/sites/166/2023/06/logo-ilum-2048x382.png" alt="Descrição da imagem" style="width: 1000px; height: auto; ">

<h1 align="center">Identificação da Temperatura Crítica ☝️:</h1>
<h3 align="center">Processamento de Linguagem Natural</h3>

<p align="center"><strong>Autores:</strong> Maria Emily Nayla Gomes da Silva e Júlia Guedes Almeida dos Santos</p>
<p align="center"><strong>Orientador:</strong> Prof. Dr. James Moraes de Almeida</p>

<p align="center">
<img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>


## 📝 Descrição
<p align="justify">
Neste projeto, desenvolveram-se duas abordagens de processamento de linguagem natural aplicadas à identificação da temperatura crítica em supercondutores metálicos: o uso de expressões regulares (<i>regex</i>) para encontrar a composição dos materiais metálicos, bem como a utilização de modelos pré-treinados de <i>natural language processing</i>. O objetivo é identificar as temperaturas mínimas necessárias para que um material metálico apresente as características associadas a supercondutores. Além disso, são disponibilizados dois notebooks que demonstram como foi possível extrair informações de um banco de dados contendo 3.846 <i>abstracts</i> sobre o tema, obtidos no site <i>Web of Science</i>.
</p>

## 📔 Notebooks e arquivos do projeto
 <!-- 
* `Imagens`: Pasta contento figuras utilizadas no README e o código para gerar a imagem de visualização do *dataset*.
  - `24Imagens_MNIST.png`: imagem de visualização do *dataset*.
  - `Construcao-Figura-24Imagens_MNIST.ipynb`: código para gerar a imagem de visualização do *dataset*.
  - `Matriz de Confusão - MNIST.png`: previsão obtida pela rede treinada.
  - `logos_ilum_cnpem_mcti_mec.jpg`: logotipos da institução na qual tal projeto foi realizado e seus vínculos.
* `CNN.ipynb`: caderno principal do projeto, com o *download* do *dataset* MNIST, além de construção, treinamento, teste e resultados obtidos com a CNN.
--->

* `superconductors_aulas_1_e_2.ipynb`: Introdução ao processamento de linguagem natural; e Vetorização e Análise de Vetores.
* `superconductors_aulas_3_e_4.ipynb`: Vetorização de Palavras e Regex.
* `README.md`: descrição geral do projeto.
  
## 🗂️ Banco de dados
<p align="justify">
Ao pesquisar em todos os bancos de dados disponíveis no <i>Web of Science</i> com a busca <code>superconductor* AND ("critical temperature" OR "Tc") AND "metallic"</code>, obteve-se um total de 4.820 artigos associados. Além disso, ao desconsiderar aqueles que não possuíam <i>abstract</i>, os dados foram reduzidos a 3.846 artigos.
</p>

<!-- 
## 🏋️‍♀️ Encontrando a temperatura crítica

### Regex

### NLP



## 🔢 Resultados Obtidos
<p align="justify">Os resultados obtidos foram excelentes. A baixa variabilidade dos dados, aliada ao grande número de exemplos e ao uso de uma ferramenta otimizada, a biblioteca Lightning, justifica a matriz de confusão apresentada a seguir, bem como a acurácia superior a 98% alcançada com apenas duas épocas. A concentração da densidade de predições na diagonal principal revela a qualidade do modelo, indicando que ele não está sobreajustado, mas sim realizando uma grande quantidade de previsões corretas.</p>
<p> </p>
<div align="center">
  <img src="Imagens/Matriz de Confusão - MNIST.png" alt="Descrição da imagem" width="500"/>
</div>


## 😁 Conclusão
<p align="justify">A biblioteca Lightning mostrou-se bastante eficiente para lidar com os dados disponíveis. Especificamente, trabalhamos com um grande volume de dados e com baixa variabilidade entre os exemplos. Ainda assim, apenas duas épocas de treinamento com três filtros foram suficientes para alcançar uma acurácia superior a 98%. Dessa forma, consideramos essa ferramenta bastante poderosa.</p>
 -->

## 🖇️ Informações técnicas
* Linguagem de programação: `Python 3.9`
* Software:  `Jupyter Notebook`
* Bibliotecas e Módulos: `regex`
<br>

 <!--
## 👩‍🦳 Referências
$1.$ [**Nicola, Nicholas Di. “nicholas-dinicola/Lightning-Series"**](https://github.com/nicholas-dinicola/Lightning-Series)  
Acesso em 12 de abril de 2025. 

$2.$ [**GeeksforGeeks. “MNIST Dataset : Practical Applications Using Keras and PyTorch"**](https://www.geeksforgeeks.org/mnist-dataset/)  
Acesso em 12 de abril de 2025.

$3.$ **JAMES, Gareth; et al. An Introduction to Statistical Learning with Applications in Python.** 1. ed. Cham: Springer, 2023. p. 399–411.
 -->


## 🧠 Contribuições dos Colaboradores
| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/172424779?v=4" width=115><br><sub>Julia Guedes A. Santos</sub>](https://github.com/JuliaGuedesASantos)<br> [<sub>Ilum - CNPEM</sub>](https://ilum.cnpem.br/)<br> [<sub>Currículo Lattes</sub>](https://lattes.cnpq.br/9504021537643847)<br> [<sub>Linkedin</sub>](https://www.linkedin.com/in/j%C3%BAlia-guedes-546542283/) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/172424897?v=4" width=115><br><sub> Maria Emily Nayla</sub>](https://github.com/MEmilyGomes)<br> [<sub>Ilum - CNPEM</sub>](https://ilum.cnpem.br/)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/9482558334105708)<br> |
| :---: | :---: | 

<!--
#### Para o Projeto:
* Emily Gomes: Atualizações na construção, treinamento e análise da previsão de uma CNN utilizando o Lightning.
* Yasmin Shimizu: Atualizações na construção, treinamento e análise da previsão de uma CNN utilizando o Lightning.

#### Para o Repositório GitHub:
* Emily Gomes: README e upload do notebook Jupyter referente a construção, treinamento e previsão da CNN.
* Yasmin Shimizu: README, upload de imagens e upload do notebook Jupyter referente à figura "24Imagens_MNIST.png".
 -->
