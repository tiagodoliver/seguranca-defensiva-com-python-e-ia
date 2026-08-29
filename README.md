# Segurança Defensiva com Python e Inteligência Artificial

Caderno temático sobre segurança defensiva, Python e Inteligência Artificial, desenvolvido para o desafio da DIO.

## Contexto

Este projeto foi desenvolvido como parte de um desafio da DIO sobre aprendizagem ativa com Inteligência Artificial. O tema escolhido foi **Segurança Defensiva com Python e Inteligência Artificial**.

A escolha surgiu do meu interesse em aprender segurança da informação e desenvolver conhecimentos em Python. O NotebookLM foi utilizado para organizar fontes, elaborar perguntas, revisar conceitos e consolidar o aprendizado.

## Objetivos

- Compreender os fundamentos da segurança da informação;
- Diferenciar ameaça, vulnerabilidade, risco e controle;
- Conhecer golpes como phishing e técnicas de engenharia social;
- Aprender como Python pode ser utilizado em tarefas defensivas;
- Entender benefícios, riscos e limitações da Inteligência Artificial;
- Criar um material de revisão com resumos, glossário e prompts;
- Praticar o uso responsável e ético de ferramentas de segurança.

## Curadoria de Fontes

### 1. Cartilha de Segurança para Internet

- **Instituição:** CERT.br / NIC.br
- **Link:** https://cartilha.cert.br/livro/cartilha-seguranca-internet.pdf
- **Assunto:** Golpes, senhas, códigos maliciosos, privacidade e proteção.
- **Motivo da escolha:** É um material brasileiro e confiável sobre segurança na Internet.

### 2. Fascículos de Segurança para Internet

- **Instituição:** CERT.br / NIC.br
- **Link:** https://cartilha.cert.br/fasciculos/
- **Assunto:** Autenticação, backup, golpes e proteção de dados.
- **Motivo da escolha:** Apresenta explicações curtas e apropriadas para iniciantes.

### 3. Guia de IA Generativa

- **Instituições:** Secretaria de Governo Digital e SERPRO
- **Link:** https://www.gov.br/governodigital/pt-br/infraestrutura-nacional-de-dados/inteligencia-artificial-1/publicacoes/guia-ia-generativa
- **Assunto:** Uso responsável da IA generativa, riscos, proteção de dados, ataques cibernéticos e boas práticas.
- **Motivo da escolha:** Apresenta conteúdo aberto e acessível sobre benefícios, riscos e cuidados relacionados ao uso da IA.

### 4. Tutorial Oficial do Python

- **Instituição:** Python Software Foundation
- **Link:** https://docs.python.org/pt-br/3/tutorial/
- **Assunto:** Fundamentos da linguagem Python.
- **Motivo da escolha:** É a documentação oficial da linguagem e está disponível em português.

## Metodologia

As fontes foram adicionadas ao NotebookLM e analisadas por meio de prompts progressivos. Primeiro, foram feitas perguntas abertas para identificar conceitos fundamentais. Depois, os prompts foram refinados para definir o público, limitar as respostas às fontes, solicitar uma estrutura e exigir referências.

As respostas não foram aceitas automaticamente. O conteúdo foi comparado com as fontes, revisado e corrigido antes de ser incorporado ao projeto.

## Engenharia de Prompts e Cicatrizes

### Teste 1 — Prompt simples

**Prompt utilizado:**

> Explique phishing.

**Resultado obtido:**

O NotebookLM explicou o conceito, o funcionamento do golpe e algumas formas de prevenção. Entretanto, como o prompt era muito aberto, a organização da resposta ficou totalmente a cargo da IA.

**Dificuldade observada:**

O prompt não informou o público, o formato esperado nem solicitou explicitamente exemplos e referências.

### Teste 2 — Prompt melhorado

**Prompt utilizado:**

> Utilizando somente as fontes deste caderno, explique phishing para uma pessoa iniciante. Organize a resposta em definição, funcionamento, sinais de alerta, exemplo fictício e formas de prevenção. Cite as fontes utilizadas.

**Resultado obtido:**

A resposta foi organizada nas seções solicitadas e ficou mais fácil de estudar. O NotebookLM apresentou definição, funcionamento, sinais de alerta, exemplo fictício, prevenção e fontes utilizadas.

**Aprendizado:**

Um prompt específico oferece maior controle sobre a estrutura e facilita a conferência da resposta nas fontes.

### Cicatriz 1 — HTTPS não garante legitimidade

Em uma das respostas, a presença de HTTPS e do cadeado foi associada à segurança do site. Essa afirmação precisa de contexto: HTTPS indica que a conexão está criptografada, mas não comprova que o site pertença à instituição verdadeira. Uma página de phishing também pode possuir HTTPS.

O aprendizado foi que respostas aparentemente corretas ainda precisam de revisão crítica.

### Cicatriz 2 — Fonte bloqueada

A primeira fonte escolhida sobre IA era um PDF governamental. Ao tentar importá-lo, o conteúdo estava restrito e o NotebookLM analisou elementos da página, como informações sobre cookies, em vez do documento.

Para solucionar o problema, a fonte foi substituída pelo **Guia de IA Generativa**, da Secretaria de Governo Digital e do SERPRO. Depois da substituição, o NotebookLM conseguiu responder com base no conteúdo correto.

## Miniguia de Estudo

### 1. O que é Segurança da Informação

Segurança da informação é o conjunto de práticas adotadas para proteger dados, dispositivos e sistemas contra acesso indevido, alterações, perdas e indisponibilidade. Essa proteção depende tanto de ferramentas técnicas quanto do comportamento consciente das pessoas.

Não basta instalar um antivírus: também é necessário atualizar programas, proteger senhas, desconfiar de mensagens suspeitas e manter cópias de segurança.

### 2. Confidencialidade, Integridade e Disponibilidade

Os três princípios básicos da segurança da informação são:

- **Confidencialidade:** somente pessoas autorizadas podem acessar a informação;
- **Integridade:** a informação deve permanecer correta e protegida contra alterações não autorizadas;
- **Disponibilidade:** sistemas e informações devem estar acessíveis quando forem necessários.

Um arquivo confidencial exposto publicamente perde sua confidencialidade. Se o conteúdo for alterado sem autorização, sua integridade foi comprometida. Se ninguém conseguir acessá-lo quando necessário, ocorreu um problema de disponibilidade.

### 3. Ameaças, Vulnerabilidades, Riscos e Controles

- **Ameaça:** algo com potencial para causar dano, como um golpista ou programa malicioso;
- **Vulnerabilidade:** fraqueza que pode ser explorada, como um sistema desatualizado;
- **Risco:** possibilidade de uma ameaça explorar uma vulnerabilidade e provocar impacto;
- **Controle de segurança:** medida utilizada para reduzir o risco, como atualização, backup, autenticação ou firewall.

Uma comparação simples é pensar em uma janela sem trinco. A janela representa a vulnerabilidade, um possível invasor representa a ameaça, a possibilidade de furto representa o risco e a instalação de um trinco representa o controle.

### 4. Phishing, Engenharia Social e Códigos Maliciosos

**Engenharia social** é a manipulação de pessoas para que realizem ações prejudiciais, como revelar uma senha ou abrir um arquivo perigoso. Golpistas exploram sentimentos como medo, urgência, curiosidade e confiança.

**Phishing** é um golpe no qual uma mensagem tenta se passar por uma comunicação legítima. A vítima é induzida a clicar em um link, fornecer dados ou instalar um arquivo.

**Códigos maliciosos**, também chamados de malware, são programas criados para executar ações prejudiciais. Vírus, worms, spywares e cavalos de Troia são alguns exemplos.

Uma mensagem dizendo que uma conta bancária será bloqueada imediatamente pode ser uma tentativa de phishing. O usuário deve evitar o link e acessar o serviço pelo aplicativo ou endereço oficial conhecido.

### 5. Boas Práticas de Proteção

- Manter o sistema operacional e os aplicativos atualizados;
- Utilizar senhas longas e diferentes em cada serviço;
- Ativar uma segunda etapa de autenticação;
- Fazer backups periódicos dos arquivos importantes;
- Manter ferramentas de proteção atualizadas;
- Evitar anexos e links inesperados;
- Conferir cuidadosamente o endereço dos sites;
- Não compartilhar senhas ou informações confidenciais;
- Utilizar somente sistemas próprios ou autorizados para atividades práticas.

### 6. Como Python Pode Ajudar na Segurança Defensiva

Python possui uma sintaxe acessível e uma biblioteca padrão ampla. Na segurança defensiva, pode ajudar a automatizar tarefas repetitivas, como:

- Ler e organizar arquivos de log;
- Contar tentativas de autenticação malsucedidas;
- Calcular hashes para verificar a integridade de arquivos;
- Organizar indicadores encontrados em dados fictícios;
- Automatizar cópias de segurança;
- Gerar relatórios simples.

Um script defensivo deve ser testado apenas com arquivos próprios, dados fictícios ou ambientes expressamente autorizados.

Exemplo didático com registros fictícios:

```python
logs = [
    "Login realizado com sucesso",
    "Acesso negado",
    "Acesso negado",
]

tentativas_negadas = 0

for evento in logs:
    if evento == "Acesso negado":
        tentativas_negadas += 1

print(f"Tentativas negadas: {tentativas_negadas}")
```

Esse exemplo apenas conta eventos presentes em uma lista. Ele não invade, acessa ou modifica nenhum sistema.

### 7. Como a Inteligência Artificial Pode Ajudar

A IA analítica pode processar dados para produzir classificações, recomendações e previsões. A IA generativa pode auxiliar na criação de resumos, textos, códigos e materiais de estudo.

Entre as aplicações possíveis estão:

- Automatizar tarefas repetitivas;
- Resumir grandes volumes de informação;
- Auxiliar na identificação de inconsistências;
- Apoiar a criação inicial de scripts;
- Ajudar na organização e revisão do conhecimento.

Técnicas como RAG permitem que um sistema consulte bases de conhecimento selecionadas antes de responder. Isso pode reduzir respostas sem fundamento, mas não elimina erros. Toda saída relevante ainda precisa de revisão humana.

A IA deve ser tratada como ferramenta de apoio, e não como substituta do julgamento humano. A responsabilidade pelo uso do resultado continua sendo da pessoa.

### 8. Riscos e Limitações da Inteligência Artificial

- **Alucinação:** resposta incorreta ou inventada apresentada de maneira convincente;
- **Vazamento de dados:** exposição causada pelo envio ou tratamento inadequado de informações pessoais ou confidenciais;
- **Phishing auxiliado por IA:** produção de mensagens fraudulentas mais naturais e convincentes;
- **Deepfake:** conteúdo sintético que imita a aparência ou a voz de uma pessoa;
- **Envenenamento de dados:** inclusão de dados manipulados para comprometer o comportamento de um sistema;
- **Viés algorítmico:** distorção que pode reproduzir ou ampliar preconceitos presentes nos dados ou no projeto do sistema;
- **Acesso não autorizado:** exposição de informações a pessoas, sistemas ou fornecedores sem a devida permissão.

Para utilizar IA com mais segurança:

- Não inserir senhas ou informações sigilosas;
- Evitar o envio de dados pessoais desnecessários;
- Anonimizar dados quando for apropriado;
- Verificar a política de privacidade da ferramenta;
- Utilizar soluções aprovadas pela instituição;
- Conferir fatos, referências e códigos produzidos;
- Manter supervisão humana sobre decisões importantes.

### 9. Ética e Uso Responsável

Conhecimentos de segurança e programação devem ser utilizados para proteção, aprendizagem e melhoria dos sistemas. Testes devem ocorrer apenas em equipamentos próprios ou ambientes autorizados.

Também é necessário respeitar a privacidade, a legislação, os direitos autorais e as regras de uso dos sistemas. Encontrar uma informação acessível não significa possuir autorização para coletá-la, divulgá-la ou utilizá-la.

## Glossário

- **Ameaça:** situação, agente ou ação com potencial para causar dano a informações ou sistemas.
- **Autenticação:** processo utilizado para comprovar a identidade de uma pessoa ou sistema.
- **Backup:** cópia de segurança utilizada para recuperar arquivos em caso de perda, falha ou ataque.
- **Código malicioso:** programa desenvolvido para executar ações prejudiciais em um dispositivo.
- **Confidencialidade:** proteção da informação contra acesso não autorizado.
- **Controle de segurança:** medida técnica, administrativa ou comportamental utilizada para reduzir riscos.
- **Deepfake:** áudio, imagem ou vídeo sintético que imita uma pessoa de forma realista e potencialmente enganosa.
- **Disponibilidade:** garantia de que sistemas e informações estejam acessíveis quando necessários.
- **Engenharia social:** manipulação psicológica utilizada para induzir alguém a realizar uma ação prejudicial.
- **Firewall:** mecanismo que controla comunicações de rede de acordo com regras de segurança.
- **Hash:** resultado de tamanho fixo produzido por uma função, utilizado, entre outras aplicações, na verificação da integridade de dados.
- **Inteligência Artificial Generativa:** tipo de IA capaz de produzir conteúdos como textos, imagens, áudios e códigos a partir de padrões aprendidos.
- **Integridade:** proteção da informação contra alteração não autorizada.
- **Phishing:** golpe que utiliza mensagens ou páginas falsas para obter dados ou induzir ações perigosas.
- **Risco:** possibilidade de uma ameaça explorar uma vulnerabilidade e produzir impacto.
- **Viés algorítmico:** distorção nos resultados de um sistema causada pelos dados, pelas escolhas de projeto ou pelo contexto de utilização.
- **Vulnerabilidade:** fraqueza que pode ser explorada e comprometer a segurança.

## Prompts Reutilizáveis

### Explicação para iniciantes

> Utilizando somente as fontes deste caderno, explique [CONCEITO] para uma pessoa iniciante. Apresente definição, exemplo fictício, riscos, prevenção e referências utilizadas.

### Comparação de conceitos

> Compare [CONCEITO 1] e [CONCEITO 2]. Apresente diferenças, semelhanças, exemplos e erros comuns de interpretação. Utilize somente as fontes selecionadas.

### Questionário de revisão

> Crie dez perguntas sobre [TEMA], divididas em nível básico, intermediário e avançado. Espere minhas respostas antes de apresentar o gabarito.

### Resumo estruturado

> Faça um resumo sobre [TEMA]. Organize a resposta em conceitos, exemplos, riscos e boas práticas. Utilize somente as fontes selecionadas e indique as referências.

### Verificação crítica

> Analise a resposta anterior e identifique afirmações que não estejam claramente fundamentadas nas fontes. Explique os problemas e apresente uma versão corrigida.

### Plano de estudos

> Crie um plano de estudos de quatro semanas sobre [TEMA] para uma pessoa iniciante. Para cada semana, defina conceitos, atividades práticas defensivas e perguntas de revisão.

## Conclusão

Este projeto permitiu estudar fundamentos da segurança da informação e conhecer aplicações defensivas de Python e Inteligência Artificial. O processo mostrou que prompts mais específicos produzem respostas mais organizadas, mas não eliminam a necessidade de conferir fontes e revisar criticamente o conteúdo.

A dificuldade de acesso a uma das fontes também demonstrou a importância de testar formatos, substituir materiais bloqueados e documentar as decisões tomadas durante a pesquisa.

## Aviso Ético

Todo o conteúdo deste projeto possui finalidade exclusivamente educacional e defensiva. As práticas de segurança devem ser realizadas somente em sistemas próprios ou ambientes nos quais exista autorização.

