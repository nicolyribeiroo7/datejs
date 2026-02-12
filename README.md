

📅 Calculadora de Intervalo entre Datas
📌 Sobre o Projeto

Este projeto é uma calculadora de intervalo entre duas datas, desenvolvida com HTML, CSS e JavaScript puro.

Ela permite que o usuário selecione duas datas e visualize a diferença entre elas em:

✅ Dias

✅ Meses (aproximado)

✅ Anos (aproximado)

O projeto tem finalidade didática, ajudando na prática de:

Manipulação de datas em JavaScript

Captura de dados com getElementById

Validação de formulário

Manipulação do DOM

Cálculos com milissegundos

🖥️ Tecnologias Utilizadas

HTML5

CSS3

JavaScript

🎯 Funcionalidades
🔹 1. Inserção de Datas

O usuário pode selecionar:

Primeira data

Segunda data

Utilizando o input do tipo:

<input type="date">

🔹 2. Cálculo do Intervalo

Ao clicar no botão "Calcular Intervalo", o sistema:

Verifica se os dois campos foram preenchidos.

Converte as datas para objetos Date.

Calcula a diferença em milissegundos.

Converte o resultado para:

Dias

Meses (considerando 30 dias)

Anos (considerando 12 meses)

📌 Fórmula utilizada para dias:
1 dia = 1000 × 60 × 60 × 24 milissegundos


A diferença é calculada assim:

const diffEmMs = Math.abs(d2 - d1);
const diffEmDias = Math.floor(diffEmMs / (1000 * 60 * 60 * 24));

🔹 3. Validação

Caso alguma data não seja preenchida, o sistema exibe a seguinte mensagem:

Por favor, preencha as duas datas antes de calcular!


Isso impede que o cálculo seja feito com valores vazios.

🔹 4. Botão "Limpar Campos"

O botão:

Limpa as duas datas

Apaga o resultado exibido

Retorna o foco para o primeiro campo

🎨 Estilização

O projeto possui um design simples e organizado:

Fonte: Arial

Layout centralizado

Botões estilizados com bordas arredondadas

Área de resultado com sombra e fundo branco

Destaque visual para mensagens de erro

📚 Objetivo Educacional

Este projeto é ideal para quem está iniciando em JavaScript e deseja praticar:

Manipulação de eventos (onclick)

Estrutura condicional (if)

Funções

Conversão de tipos

Operações matemáticas

Template literals

Interação com o DOM

⚠️ Observação Importante

O cálculo de meses e anos é aproximado, pois considera:

30 dias por mês

12 meses por ano

Para aplicações reais que exigem precisão, seria necessário usar uma lógica mais avançada ou bibliotecas específicas.

🚀 Como Executar

Salve o arquivo como index.html

Abra o arquivo em qualquer navegador moderno

Selecione duas datas

Clique em Calcular Intervalo

👩‍💻 Autoria

Projeto desenvolvido para prática e aprendizado de JavaScript.
