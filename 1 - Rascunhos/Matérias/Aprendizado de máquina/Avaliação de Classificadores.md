## O que é avaliação de classificadores?
- Avaliar o quão bom o classificador é na generalização
- O que medir?
	- Taxa erro
	- Taxa Acerto(acurácia)
## Procedimento básico
- Separar Base de dados em base de treinamento e base de testes
- Acurácia nº acertos/base de dados

## Técnicas para avaliação de classificadores
### Hold out
- Seleciona uma fração da base para ser os testes e outra para ser o treino
- Pesquisar amostragem estratificada
- Problemas
	- Proporção
		- Se a classe tem uma proporção muito distintas entre as classes
	- Quando os casos de treino não refletem os dados de teste
		- Solução: Refazer o treinamento com uma nova divisão da base de dados
### Random Subsampling
- Hold out executado k vezes
	- Acurácia do classificador é a média das acurácias obtidas nas k execuções 
- Problemas
	- Custoso
### k-Fold Cross Validation
- Particionar a base em k partes (de aproximadamente o mesmo tamanho)
- Treinamento e teste são executados k vezes
- Em cada execução:
	- 
### Stratified Cross-Validation
- Cada partição utilizada na técnica k-fold cross validation deve possuir a mesmo distribuição de classes da base original
### Leave-one-Out
- Mesmo que k-fold cross validation quando k é o número de instância da base de dados

# Medidas de Desempenho
### Acurácia
$\frac{A}{N}$
### Taxa de Erro
$\frac{E}{N}$
### Precisão(Precision)
$\frac{TA_{d}}{TC_{d}}$
### Cobertura(Recall)
$\frac{CA_{d}}{CT_{d}}$
### Sensibilidade
### Especificidade
### ROC e AUC
### F-score
### Kappa
