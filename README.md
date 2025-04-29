📧 Validador de E-mail - Projeto JavaScript

📚 Sobre o Projeto
Este projeto foi desenvolvido como parte da disciplina de Desenvolvimento em JavaScript do curso de Análise e Desenvolvimento de Sistemas da Anhanguera. Trata-se de uma aplicação web simples que valida endereços de e-mail utilizando expressões regulares em JavaScript.

🎯 Objetivo
O objetivo principal deste projeto é demonstrar a aplicação prática de conceitos fundamentais de JavaScript, incluindo:
- Manipulação do DOM
- Eventos em JavaScript
- Validação de formulários
- Uso de expressões regulares (RegEx)
- Feedback visual ao usuário

🛠️ Tecnologias Utilizadas
- HTML5
- CSS3
- JavaScript (Vanilla)

📋 Funcionalidades
- Interface de usuário intuitiva
- Validação em tempo real do formato de e-mail
- Feedback visual com mensagens de erro/sucesso
- Design responsivo para diferentes dispositivos

🖥️ Demonstração
A aplicação verifica se o e-mail inserido contém:
- Um nome de usuário válido
- O símbolo '@'
- Um domínio válido com extensão (como .com, .org, etc.)

📝 Como Utilizar
1. Clone este repositório
2. Abra o arquivo `index.html` em qualquer navegador
3. Digite um endereço de e-mail no campo de entrada
4. Clique no botão "Validar" para verificar se o e-mail é válido

📊 Aprendizados
Durante o desenvolvimento deste projeto, pude aplicar diversos conceitos importantes:
- Implementação de expressões regulares para validação de dados
- Manipulação de elementos HTML via JavaScript
- Tratamento de eventos de formulário
- Estilização e feedback visual para melhorar a experiência do usuário

🔍 Código-fonte
O projeto utiliza uma expressão regular simples para validar o formato básico de um e-mail:
```javascript
const regexEmail = /^[^@\s]+@[^@\s]+\.[^@\s]+$/;
