# Le_Mars

Este é um programa em C que lê os dumps da memória de texto e de dados do simulador MARS MIPS
*    e gera um arquivo VHDL (memory.vhd) contendo 2 ou mais
*    declarações de pares de entidade/arquitetura, que definem um módulo de memória de instruções
*   ou mais blocos de memória de dados
*    Observações:
*        1) Presume-se que os dumps contenham exclusivamente valores hexadecimais
*        para endereços, código-objeto e dados. Parametrize o MARS para gerar
*        dumps adequados para entrada neste programa
*        2) O tamanho dos módulos de memória é fixo: 1 bloco de 16 Kbits para a
*           memória de instruções e 4 blocos de 16 Kbits (64 Kbits) para cada módulo de
*           memória de dados.

Traduzido com a versão gratuita do tradutor - DeepL.com
