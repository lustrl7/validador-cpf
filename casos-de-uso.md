# Casos de Uso

## UC01 - Validar CPF

**Ator:** Usuário

**Fluxo principal:**
1. Usuário acessa a aplicação.
2. Informa o CPF.
3. Sistema remove caracteres de formatação.
4. Verifica a quantidade de dígitos.
5. Verifica sequências repetidas.
6. Calcula os dígitos verificadores.
7. Apresenta o resultado.

**Alternativas:**
- Quantidade incorreta: CPF inválido.
- Dígitos repetidos: CPF inválido.
- Dígitos verificadores incorretos: CPF inválido.

## UC02 - Formatar CPF

1. Usuário informa os dígitos.
2. Sistema remove caracteres não numéricos.
3. Sistema aplica a máscara.
4. Sistema apresenta o CPF formatado.
