# K-Fold-Cross-Validation-em-R
Aplicação do modelo Naive Bayes utilizando a técnica K-Fold Cross Validation para validar a acurácia do modelo. Nessa aplicação foi utilizada a base SPAM E-mail Database (UCI Machine Learning Repository)


## Método k-fold ##
O método de validação cruzada denominado k-fold consiste em dividir o conjunto total de dados em k subconjuntos mutuamente exclusivos do mesmo tamanho e, a partir disto, um subconjunto é utilizado para teste e os k-1 restantes são utilizados para estimação dos parâmetros e calcula-se a acurácia do modelo. Este processo é realizado k vezes alternando de forma circular o subconjunto de teste. A figura abaixo mostra o esquema realizado pelo k-fold.
Exemplo do esquema de particionamento e execução do método k-fold com k = 3.
Ao final das k iterações calcula-se a acurácia sobre os erros encontrados, através da equação descrita anteriormente, obtendo assim uma medida mais confiável sobre a capacidade do modelo de representar o processo gerador dos dados.

## Massa de treinamento (SPAM E-mail Database) ##
1. Title:  SPAM E-mail Database

2. Sources:
   (a) Creators: Mark Hopkins, Erik Reeber, George Forman, Jaap Suermondt
        Hewlett-Packard Labs, 1501 Page Mill Rd., Palo Alto, CA 94304
   (b) Donor: George Forman (gforman at nospam hpl.hp.com)  650-857-7835
   (c) Generated: June-July 1999
      
3. This file: 'spambase.DOCUMENTATION' at the UCI Machine Learning Repository
    http://www.ics.uci.edu/~mlearn/MLRepository.html
