# Critérios de Aceitação

## CA01 - CPF válido
Dado um CPF com 11 dígitos e verificadores corretos, quando o usuário validar, então o sistema informa que é válido.

## CA02 - CPF inválido
Dado um CPF com verificadores incorretos, quando o usuário validar, então o sistema informa que é inválido.

## CA03 - Quantidade incorreta
Dado um valor diferente de 11 dígitos, quando o usuário validar, então o sistema informa que é inválido.

## CA04 - Sequência repetida
Dado `11111111111`, quando o usuário validar, então o sistema informa que é inválido.

## CA05 - Formatação
Dado um CPF sem pontuação, quando o sistema processar a entrada, então ele pode apresentá-lo como `000.000.000-00`.

## CA06 - Processamento local
Dado um CPF informado, quando ocorrer a validação, então o processamento deve ocorrer no navegador sem API externa.
