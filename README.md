# seguranca-defensiva-com-python-e-ia
Caderno temático sobre segurança defensiva, Python e Inteligência Artificial, desenvolvido para o desafio da DIO.
## Contexto

Este projeto foi desenvolvido como parte de um desafio da DIO sobre aprendizagem ativa com Inteligência Artificial. O tema escolhido foi Segurança Defensiva com Python e Inteligência Artificial.

A escolha do tema surgiu do meu interesse em aprender segurança da informação e desenvolver conhecimentos em Python. O NotebookLM foi utilizado para organizar fontes, elaborar perguntas, revisar conceitos e consolidar o aprendizado.

## Objetivos

- Compreender os fundamentos da segurança da informação;
- Diferenciar ameaça, vulnerabilidade, risco e controle;
- Conhecer ataques comuns, como phishing e engenharia social;
- Aprender como Python pode ser utilizado em tarefas defensivas;
- Entender como a Inteligência Artificial auxilia profissionais de segurança;
- Criar um material de revisão com resumos, glossário e prompts;
- Praticar o uso responsável e ético de ferramentas de segurança.

 ## Engenharia de Prompts e Cicatrizes

### Teste 1 — Prompt simples

**Prompt utilizado:**

> Explique phishing.

**Resultado obtido:**

O NotebookLM explicou que phishing é uma fraude virtual utilizada para obter dados pessoais e financeiros. A resposta apresentou o funcionamento do golpe, o uso de engenharia social, a criação de urgência, páginas clonadas, sinais de alerta e formas de prevenção.

**Fontes indicadas pelo NotebookLM:**

- Livro “Cartilha de Segurança para Internet — Versão 4.0”, do CERT.br;
- Fascículos da “Cartilha de Segurança para Internet”, do CERT.br/NIC.br.

**Dificuldade observada:**

Apesar de a resposta conter bastante informação, o prompt era muito aberto. Eu não havia informado o público, a estrutura esperada nem solicitado explicitamente um exemplo fictício. O NotebookLM escolheu sozinho como organizar a resposta.

### Teste 2 — Prompt melhorado

**Prompt utilizado:**

> Utilizando somente as fontes deste caderno, explique phishing para uma pessoa iniciante. Organize a resposta em definição, funcionamento, sinais de alerta, exemplo fictício e formas de prevenção. Cite as fontes utilizadas.

**Resultado obtido:**

A resposta foi organizada nas seções solicitadas:

1. Definição;
2. Funcionamento;
3. Sinais de alerta;
4. Exemplo fictício;
5. Formas de prevenção;
6. Fontes utilizadas.

O NotebookLM explicou que os criminosos podem imitar instituições conhecidas, criar mensagens alarmistas e direcionar a vítima para páginas clonadas. Também apresentou um exemplo fictício de uma mensagem bancária falsa e recomendou conferir o endereço do site, desconfiar do remetente e evitar links recebidos em mensagens.

**Fontes indicadas pelo NotebookLM:**

- Livro “Cartilha de Segurança para Internet — Versão 4.0”, do CERT.br;
- Fascículos “Golpes: Não se Deixe Enganar”, “Códigos Maliciosos” e “Banco via Internet”, do CERT.br/NIC.br.

### Comparação dos resultados

A segunda resposta ficou mais fácil de estudar e consultar porque o prompt definiu:

- o público iniciante;
- a utilização somente das fontes do caderno;
- as seções que deveriam aparecer;
- a inclusão de um exemplo fictício;
- a necessidade de indicar as fontes.

A primeira resposta não estava errada, mas sua organização dependia das escolhas da Inteligência Artificial. A segunda tentativa demonstrou que um prompt específico oferece maior controle sobre o formato do resultado.

### Cicatriz — Cuidado com respostas aparentemente corretas

Durante a revisão, observei que a resposta relacionou a presença de HTTPS e do cadeado fechado à segurança do site. Essa informação precisa ser interpretada com cuidado: HTTPS indica que a conexão está criptografada, mas não garante que o site pertença à instituição verdadeira. Uma página de phishing também pode possuir HTTPS.

Por isso, além de verificar o cadeado, é necessário conferir cuidadosamente o endereço completo do site e, em caso de dúvida, acessar a instituição pelo aplicativo oficial ou digitando o endereço conhecido no navegador.

### Aprendizado

Aprendi que não devo aceitar automaticamente todas as afirmações produzidas pela IA. Mesmo quando a resposta apresenta referências, ainda é necessário comparar o conteúdo com as fontes e verificar possíveis simplificações ou informações incompletas.
