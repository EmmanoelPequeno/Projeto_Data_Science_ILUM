## <b>PROJETO: JOGO DA FORCA - "Adivinhando Elementos Químicos" </b>

Grupo: Davi José, Iasodara do Carmo, Mayllon Emmanoel Pequeno e Natália Alcantara

O arquivo "_Forca_Definitivo_" é um código que implementa um jogo da forca reverso baseado em um banco de palavras dos elementos químicos da tabela peródica, no qual a máquina tenta adivinhar a palavra que você está pensando com o menor número possível de erros. 

<b>MOTIVAÇÃO:</b>
Em um jogo da forca tradicional o usuário recebe uma palavra misteriosa e chuta letras com um número de chances limitado, até que ele acerte a palavra. Já neste projeto, o usuário informa o número de letras da palavra para a máquina adivinhar.

<b>INSTRUÇÕES PARA JOGAR:</b>
1. Informe o tamanho da palavra que você está pensando.
2. Quando solicitado se a X letra aparece na palavra, responda "sim" ou "não"
3.  Informe a posição (ou posições) da letra
4. Ao final o código chuta a palavra e pergunta se ela está correta com "sim" ou "não"

_Observações:_
- A máquina continuará fazendo tentativas até adivinhar a palavra correta ou até esgotar todas as possibilidades.
- Ao final do jogo, você receberá a palavra adivinhada pela máquina.
<b>PASSOS</b>
 
 _Para analisar as letras mais comuns por tamanho de palavra:_
  
1. Dividir as palavras por tamanho e agrupa as de mesmo tamanho
2. Para cada grupo de palavras, dividir as palavras em letras
3. Para cada grupo de palavras, contar quantas vezes cada letra aparece na lista 
4. criar um dicionário que associa cada letra ao número de vezes que ela aparece
5. ordenar esse dicionário em ordem decrescente de letra mais comum
6. Criar uma lista de letras mais comuns para cada tamanho de palavra a partir do dicionário ordenado
  
_Para adivinhar a palavra no jogo da forca:_

1. Um input que recebe o número x de letras da palavra

2. Criar uma lista com x elementos zero, que irá armazenar as letras em ordem

3. Para cada tamanho de palavra x, o código chama a lista correspondente de letras mais comuns

4. Para cada item da lista de letras mais comuns, o código pergunta se aquela letra está presente na palavra

<b>METAS:</b> 
1. Fazer o código chutar a palavra quando algumas letras já tiverem organizadas. Exemplo: você é capaz de associar B_L_ às palavras BALA ou BELO por exemplo, sem chutar todas as letras do alfabeto;

2. fazer com que o código chute a palavra e pare de rodar assim que a mesma é adivinhada.  

3. fazer com que, ao usuário informar que não existe uma letra na palavra, o codigo refaça uma análise das letras mais comuns em palavras de x número de letras que NÃO TENHAM aquela letra. (com o objetivo de que ele acerte com um menor numero de erros)


