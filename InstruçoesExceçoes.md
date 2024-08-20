
A instrução TRY permite que você defina um bloco de codigo para ser testado quanto a erros enquanto esta sendo executado.
A instrução CATCH permite definir um bloco de codigo a ser executado caso ocorra um erro no bloco try.
A instrução FINALLY permite definir um bloco de codigo a ser executado idenpendente de ocorrer um erro ou não. As palavras-chave try e catch vêm em pares:

Estrutura de um bloco com try e catch:

try {
    // bloco de codifo conforme esperado

}
catch(Exception e) {// presisamos saber qual exceção
    //bloco de codifo que captura as exceçoes que podem acontecer
    // em caso de um fluxo não previsto
}