## <b>PROJETO: JOGO DA FORCA REVERSO- "Adivinhando Palavras"</b>

Este é um código que implementa um jogo da forca reverso, em que a máquina tenta adivinhar a palavra que você está pensando com o menor número possível de erros. O jogo é baseado em um código (falar resumidamente do código). 

<b>MOTIVAÇÃO:</b>
Em um jogo da forca tradicional o usuário recebe uma palavra misteriosa e chuta letras com um número de chances limitado, até que ele acerte a palavra. Já neste projeto, o usuário informa o número de letras de uma palavra arbitrária para a máquina adivinhar.

<b>INSTRUÇÕES PARA JOGAR:</b>
1. Informe o número de letras da palavra que você está pensando.
2. Quando solicitado o se X letra aparece na palavra, responda "sim" ou "não" 
3. Informe se a palavra está correta, respodendo "sim" ou "não"

A máquina continuará fazendo tentativas até adivinhar a palavra correta ou até esgotar todas as possibilidades.

Ao final do jogo, você receberá a palavra adivinhada pela máquina e o número de tentativas realizadas.

Aqui anexaremos os passos realizados para o programa

<b>METAS:</b>
1. Separar as palavras em listas de palavras com mesmo número de letras;
2. Ordenar as letras por ordem decrescente de frequência nas palavras com x letras;
3. Incorporar um banco de dados grande com a maioria das palavras existentes na língua portuguesa;
4. 
5. Fazer o código chutar a palavra quando algumas letras já tiverem organizadas. Exemplo: você é capaz de associar B_L_ às palavras BALA ou BELO por exemplo, sem chutar todas as letras do alfabeto;

<b>PASSOS</b>
 
 _Para analisar as letras mais comuns por tamanho de palavra:_
  
1. Dividir as palavras por tamanho e agrupar palavras de mesmo tamanho
2. Para cada grupo de palavras, dividir as palavras em letras
3. Para cada grupo de palavras, contar quantas vezes cada letra aparece na lista
4.. criar um dicionário que associa cada letra ao número de vezes que ela aparece
5.. ordenar esse dicionário em ordem decrescente de letra mais comum
6.. Criar uma lista de letras mais comuns para cada tamanho de palavra a partir do dicionário ordenado
  
_Para adivinhar a palavra no jogo da forca:_

1. Um input que recebe o número x de letras da palavra

2. Criar uma lista com x elementos zero, que irá armazenar as letras em ordem

3. Para cada tamanho de palavra x, o código chama a lista correspondente de letras mais comuns

4. Enquanto ganhou = False:

5. Para cada item da lista de letras mais comuns, o código pergunta se aquela letra está presente na palavra
