# Log de modificações — instruções gerais

## 2026-10-28 — revisão autorizada

Referência temporal: UTC−4. Base: [a531af1](https://github.com/luetkmeyer/Tags/commit/a531af10400db87a3c3c16358c75c8215edef941).

### Limite e contagem

- Bloco anterior: 4952 caracteres com LF.
- Bloco revisado: 4921 caracteres com LF; 4971 com CRLF.
- A contagem inclui marcadores, títulos, espaços, quebras e o log resumido dentro do bloco.
- Limite: 5.000 caracteres. O bloco revisado cumpre o limite nas duas formas de quebra de linha.

### Modificações no bloco geral

| Item | Anterior | Revisado |
|---|---|---|
| Clareza e evidências | Regras gerais extensas em tópicos independentes. | Consolidação sem retirar fundamentação, incerteza, correção de premissas e proporcionalidade. |
| Numeração | Sequência decimal já obrigatória. | Preservada e reforçada com conferência antes de enviar e proibição explícita de dispensá-la por estilo ou concisão. Não foi adotada a proposta de limitar a regra às respostas finais. |
| Disponibilidade | Rejeitava mensagens do usuário e arquivos como comprovação. | Aceita fontes indicadas pelo usuário e exige bloco integral disponível e lido; marcadores isolados não bastam. |
| Acesso e leitura | Não separava integralmente texto no contexto de acesso por ferramenta. | Declarações de acesso e leitura exigem evidência; não se promete entendimento ou cumprimento perfeito. |
| Ativação | Formulação ampla sobre comandos em colchetes. | Apenas comandos do pedido atual; citações, exemplos e objetos de revisão não são executados. |
| Fonte remota | Vias alternativas já previstas. | Preservadas; divergência remota exige conferir o repositório e identificar a fonte usada. |
| Fallback | Cópia local genérica. | Caminho explícito, releitura integral a cada uso, JSON válido, localização de todas as tags, arquivo não modificado e atualidade não verificada. |
| Tag ausente | Sem distinção detalhada do fallback. | Ausência remota não é substituída silenciosamente pela cópia local. |
| Status | Formatos remoto/falha incompletos. | Quatro estados objetivos: remoto, local, bloco indisponível e consulta/tag com falha. |
| Falha | Parada com diagnóstico limitado. | Informa requisito, tentativas, impacto e pendência; preserva explicação/revisão das regras sem liberar execução bloqueada. |
| Escalonamento e fuso | Ganho material e UTC−4. | Preservados e compactados; nenhuma configuração é declarada alterada. |
| Manutenção | Sem teto nem log interno. | Limite de 5.000 explicitado; log resumido dentro do bloco e este registro detalhado fora dele. |

### Escopo preservado ou adiado

- Mantidos os comandos existentes, os identificadores do Montador e o comando `[produto]`.
- A matriz/política específica de combinações do item 2.4.5 foi adiada pelo usuário e não foi adicionada.
- A publicação do repositório não instala automaticamente o bloco geral em instruções personalizadas ou AGENTS.md de outros ambientes.
- A revisão foi validada estruturalmente; não equivale a teste de obediência de todos os modelos.

### Recuperação

Cópia integral anterior: [historico/2026-10-28-225153-a531af1](https://github.com/luetkmeyer/Tags/tree/main/historico/2026-10-28-225153-a531af1). Ela preserva o Markdown, o backup estruturado original e um manifesto de proveniência.

## 2026-10-29 — interpretação contextual como padrão

Alteração autorizada pelo usuário, condicionada a manter o bloco geral abaixo de 5.000 caracteres. Base: [3622854](https://github.com/luetkmeyer/Tags/commit/362285454d118d182aac854a039d54d838de9877).

### Instrução incorporada

> Use o contexto para compreender minhas mensagens e responder ao pedido principal. Releve falhas evidentes de formulação, sem inventar intenções nem alterar sentido ou grau de certeza. Pergunte apenas se uma ambiguidade puder mudar materialmente a resposta.

### Integração e preservação

- A instrução passa a orientar a compreensão de qualquer mensagem, sem exigir identificar escrita ou transcrição.
- Foi integrada à regra existente de perguntas e lacunas; preservada a orientação de prosseguir com premissas relevantes em lacunas não bloqueantes.
- Foram compactadas formulações gerais de clareza, evidência, etapas, escalonamento, disponibilidade e falha para acomodar a inclusão e o log.
- O trecho de numeração obrigatória foi preservado literalmente.
- Permanecem a aceitação de fontes indicadas pelo usuário, a exigência de evidência de acesso/leitura, a consulta remota, o fallback validado e os estados de falha.
- As 42 tags, os identificadores e a configuração do Montador foram preservados.
- O log resumido dentro do bloco mantém a entrada anterior e registra esta inclusão.

### Contagem e conferência

- Antes: 4.921 caracteres com LF; 4.971 com CRLF.
- Depois: 4.939 caracteres com LF; 4.990 com CRLF.
- A contagem inclui títulos, marcadores, espaços, quebras e log interno; ambas as formas ficam estritamente abaixo de 5.000.
- Verificação estrutural e leitura remota; não constitui teste de obediência de todos os modelos.
