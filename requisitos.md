# Requisitos

## Requisitos Funcionais

**RF01 - Informar CPF:** permitir que o usuário informe um CPF.

**RF02 - Formatar CPF:** apresentar o CPF no padrão `000.000.000-00`.

**RF03 - Validar CPF:** verificar os dígitos verificadores.

**RF04 - Informar resultado:** indicar claramente se o CPF é válido ou inválido.

**RF05 - Rejeitar entradas inválidas:** rejeitar valores com quantidade incorreta de dígitos
ou sequências repetidas.

## Requisitos Não Funcionais

**RNF01 - Usabilidade:** interface simples e objetiva.

**RNF02 - Desempenho:** validação realizada rapidamente no navegador.

**RNF03 - Privacidade:** o CPF não deve ser armazenado nem enviado para serviços externos.

**RNF04 - Compatibilidade:** funcionar em navegadores modernos.

**RNF05 - Manutenibilidade:** separar interface, regras de negócio e funções auxiliares.
