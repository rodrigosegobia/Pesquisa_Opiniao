# Pesquisa de Opinião - TudoWeb

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-2ea44f)
![GitHub](https://img.shields.io/badge/GitHub-Projeto-181717?logo=github&logoColor=white)
![ETEC](https://img.shields.io/badge/ETEC-Desenvolvimento%20de%20Sistemas-b31b34)

Este projeto foi desenvolvido como atividade da Agenda de Desenvolvimento de Sistemas.

A proposta é realizar uma pesquisa de opinião para a empresa **TudoWeb**, registrando o nome, a idade e a avaliação de cada entrevistado sobre o atendimento recebido.

## Funcionamento

O programa está configurado para realizar a pesquisa com **50 entrevistados**.

Cada pessoa informa:

- nome;
- idade;
- opinião sobre o atendimento:
  - `1` - EXCELENTE
  - `2` - BOM
  - `3` - RUIM

Ao final, o programa exibe a quantidade de respostas **EXCELENTE** e **RUIM**.

Também foram adicionadas validações para impedir valores inválidos na idade e na avaliação. Caso seja digitada uma letra onde é esperado um número, o programa informa o erro e solicita o valor novamente.

## Estruturas utilizadas

Durante o desenvolvimento foram utilizadas estruturas de repetição e decisão, principalmente:

- `for`
- `while`
- `if`, `elif` e `else`
- `try` e `except`

## Teste de validação

Antes da versão final com 50 entrevistados, o funcionamento foi validado com **10 entrevistados**, conforme solicitado na atividade.

### Código utilizado no teste

![Código do teste](prints/codigo_teste.png)

### Execução do teste

![Execução - parte 1](prints/execucao_01.png)

![Execução - parte 2](prints/execucao_02.png)

![Resultado do teste](prints/execucao_resultado.png)

No teste realizado, o resultado final foi:

- **4 respostas EXCELENTE**
- **3 respostas RUIM**

## Arquivo principal

O arquivo `pesquisa_opiniao.py` contém a versão final do programa, preparada para os 50 entrevistados solicitados na atividade.

---

**Rodrigo Nunes Segobia**  
Técnico em Desenvolvimento de Sistemas - ETEC
