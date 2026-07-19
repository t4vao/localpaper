# Localpaper

> Documento fundador iniciado pela investigação visual do arquivo Figma `localpaper` e consolidado por uma entrevista de definição do primeiro MVP. Fatos do design, inferências e decisões confirmadas permanecem identificados separadamente.

O Localpaper é uma proposta de produto para enviar documentos, acompanhar como eles são consumidos e usar sinais de interesse para decidir quando e como fazer follow-up. O Figma mostra uma experiência que reúne documentos, métricas de abertura e leitura, analytics, alertas e assistência por IA. **Confirmado pelo responsável pelo produto:** **BaseDoc** e **OjoDoc** são nomes anteriores do Localpaper. As ocorrências dessas marcas no Figma são, portanto, evidências históricas que ainda precisam ser migradas para a identidade Localpaper; elas não representam produtos distintos. O escopo comercial mostrado nesses materiais antigos continua sujeito a confirmação.

## Como ler as evidências

- **Confirmado:** explicitamente demonstrado no Figma.
- **Inferido:** interpretação provável, ainda não confirmada.
- **Pendente:** decisão que o Figma não permite determinar.
- **Conflitante:** existem versões ou evidências incompatíveis.

Os nomes entre crases são páginas, frames, grupos ou textos do Figma.

## Visão

- **Confirmado:** dar visibilidade sobre abertura, leitura, tempo por página, retornos e outros sinais de documentos compartilhados (`Onboarding-Login / Page Create account`, `Interface / Analytics`, `e-mail / D2`).
- **Proposta — Inferido:** transformar documentos enviados em sinais acionáveis, reduzindo follow-ups feitos no escuro e ajudando o usuário a agir no momento de maior interesse.
- **Confirmado:** a transformação desejada aparece literalmente como “transformar documentos em decisões” e “faça follow-up no momento perfeito” (`Onboarding-Login / Page Create account`).
- **Inferido:** o Localpaper existe para aproximar envio, acompanhamento e decisão comercial em uma única experiência.

## Problema

### Dor identificada

- **Confirmado:** pessoas enviam documentos e não sabem se foram abertos, quanto tempo foi gasto, quais páginas receberam atenção ou se o destinatário voltou a uma seção (`e-mail / D2 — Prova de valor (insight)`).
- **Confirmado:** o produto associa essa falta de sinal à dificuldade de saber quando vale a pena fazer follow-up (`e-mail / D3 — Social proof leve (identificação)`).
- **Confirmado:** os designs valorizam “interesse real”, alertas de mudança e indicação de quando agir (`Onboarding-Login / Page Create account`).
- **Inferido:** hoje o acompanhamento acontece de forma manual, tardia ou baseada em intuição.

### Relevância e resultado buscado

- **Confirmado:** os exemplos conectam documentos a abertura, engajamento, conversão e fechamento de negócios (`Interface / Painel`, `Interface / Analytics`).
- **Confirmado:** o usuário busca compartilhar um documento rastreável, entender o comportamento do leitor e realizar follow-up efetivo.
- **Pendente:** não há pesquisa, métrica de mercado ou validação quantitativa da dor no Figma.

## Público

| Perfil aparente | Necessidade observada | Certeza | Evidência |
|---|---|---|---|
| Equipes de vendas | Identificar interesse, propostas quentes e momento de follow-up | **Confirmado** | `Onboarding-Login / Page Create account`; “Aprovado por equipe de vendas e times internos”; `Interface / Analytics` |
| Freelancers e consultores | Saber se documentos enviados geraram interesse | **Confirmado** | `e-mail / D3` |
| Designers e criativos | Acompanhar documentos compartilhados | **Confirmado** | `e-mail / D3` |
| Agências pequenas | Obter visibilidade sem um processo pesado | **Confirmado** | `e-mail / D3` |
| Times internos | Acompanhar materiais enviados dentro da organização | **Confirmado** | opção “Time interno” em `Onboarding-Login / 1` |
| Pessoas que enviam para leads, clientes ou investidores | Entender consumo e interesse por destinatário | **Confirmado** | opções “Leads”, “Clientes”, “Investidores” em `Onboarding-Login / 1` |
| Marketing, CS ou RH | Uso possível a partir dos exemplos de documentos | **Inferido** | nomes como “Onboarding Plane”, “Políticas LGPD” e “Plano de carreira” em `Interface / Analytics` |

## Proposta de valor

**Confirmado:** compartilhar documentos com rastreamento e mostrar sinais de consumo — aberturas, leitores, tempo, páginas, retornos e variação de engajamento — para apoiar follow-ups e decisões.

**Inferido:** o diferencial aparente é converter telemetria de documentos em uma leitura priorizada do interesse, incluindo score, documentos quentes, alertas e assistência por IA. A forma de cálculo e a confiabilidade desses sinais estão pendentes.

## Direção comercial inicial

> **Decisão confirmada pelo responsável pelo produto:** esta é a direção escolhida para validação antes da definição do frontend. Ela orienta o recorte inicial, mas não constitui prova de demanda, retenção ou disposição a pagar.

### ICP recomendado

O primeiro ICP será:

- agências e consultorias B2B;
- aproximadamente 2–20 pessoas;
- vendas conduzidas pelo fundador ou por um pequeno time comercial;
- envio recorrente de propostas em PDF;
- ticket por negócio alto o bastante para tornar um follow-up perdido financeiramente relevante;
- uso atual provável de e-mail, WhatsApp, anexos ou links de armazenamento;
- operação comercial ainda sem acompanhamento sofisticado de documentos.

**Hipótese crítica:** esse público envia propostas com frequência suficiente, sente a perda de timing como uma dor relevante e aceita pagar para reduzi-la. A escolha do ICP está confirmada como direção; sua atratividade comercial ainda precisa ser validada.

### Dor prioritária

> Depois de enviar uma proposta importante, o vendedor não sabe se ela continua sendo considerada nem quando vale a pena retomar a conversa.

O problema prioritário não é “falta de analytics”. Analytics é apenas um possível mecanismo. O resultado buscado é reduzir follow-ups feitos no escuro e ajudar o remetente a priorizar o próximo contato.

### Proposta de valor inicial

> **Saiba quando uma proposta voltou a receber atenção e priorize seu próximo follow-up.**

Esta formulação é uma decisão inicial de posicionamento. Ela evita prometer que uma abertura comprova intenção de compra. Expressões como “interesse real”, “momento perfeito”, “sinal de conversão” e “proposta quente” continuam sendo hipóteses até existir correlação demonstrada com resposta, avanço ou fechamento.

### Caso de uso principal

Acompanhar uma proposta comercial em PDF enviada a um potencial cliente.

Outros documentos, públicos e usos permanecem possíveis, mas não devem ampliar o primeiro escopo antes da validação desse caso central.

### Momento de ativação

O upload do arquivo e a criação do link são etapas de configuração, não o valor final.

O momento de ativação será considerado:

> O remetente recebe o primeiro sinal de uma proposta real e considera esse sinal útil para decidir seu próximo follow-up.

O primeiro acesso detectado é um microvalor. A ativação real exige utilidade percebida. Como o evento depende do destinatário, tempo até compartilhar, tempo até o primeiro sinal e retorno ao produto após o alerta devem ser medidos separadamente.

### Menor fluxo capaz de entregar valor

1. Criar acesso com fricção mínima.
2. Declarar a intenção: acompanhar uma proposta.
3. Enviar um PDF.
4. Gerar um link rastreável.
5. Copiar e compartilhar o link fora do Localpaper.
6. Aguardar uma interação real, com estado claro no produto.
7. Receber um alerta sobre a interação.
8. Consultar uma timeline simples do documento.
9. Informar se o sinal ajudou a decidir o follow-up.

A pergunta de onboarding sobre destinatários só deve permanecer se alterar de forma útil o fluxo. Caso contrário, deve ser tratada como fricção administrativa.

### Escopo recomendado do MVP

O MVP deve conter apenas o necessário para validar o ciclo proposta → sinal → decisão:

1. Envio de PDF.
2. Geração de link rastreável.
3. Experiência básica de visualização para o destinatário.
4. Registro de primeira abertura, novas aberturas, última visita, tempo aproximado, páginas visualizadas e retorno posterior, desde que esses eventos possam ser apresentados com confiabilidade.
5. Lista simples de propostas/documentos.
6. Timeline por documento.
7. Alerta por e-mail de primeira abertura e de abertura novamente.
8. Comunicação transparente sobre as limitações dos dados.
9. Registro manual de realização de follow-up e utilidade do sinal.
10. Estados aplicáveis de vazio, processamento, erro, sucesso, link inválido e documento indisponível.

### Fora do MVP

Os itens abaixo permanecem documentados como ideias ou evidências históricas, mas não devem compor o MVP:

- Assistente Ojo e demais capacidades de IA;
- score de interesse e score de engajamento;
- classificação automática de documentos quentes;
- analytics agregado sofisticado;
- taxa de conversão calculada;
- comparação entre documentos;
- exportação PDF/Excel e relatórios configuráveis;
- Cofre;
- Branding e domínio personalizado;
- busca global;
- tags, pastas e organização avançada;
- múltiplos canais de alerta;
- colaboração, times e permissões complexas;
- onboarding para múltiplos públicos;
- planos e paywall implementados antes da validação de cobrança;
- automações comerciais;
- plataforma genérica de links, QR codes personalizados ou recursos inspirados na Dub.

A Dub permanece apenas como referência em espera. Nenhuma funcionalidade de seu produto foi incorporada ao escopo atual.

### Sinais iniciais de retenção

Estes são candidatos a sinais de retenção e precisam ser validados com comportamento real:

- envio de um segundo documento rastreável em até 14 dias;
- documentos rastreados por remetente por semana;
- retorno ao produto após um alerta;
- recebimento de dois ou mais sinais considerados úteis em 30 dias;
- repetição do ciclo compartilhar → receber sinal → fazer follow-up;
- crescimento do histórico de propostas;
- futura adoção por um segundo remetente da mesma empresa.

O principal candidato inicial a comportamento de retenção é o envio de uma segunda proposta rastreável em até 14 dias.

### Hipóteses de monetização

- Cobrança por workspace ou remetente ativo é a hipótese inicial mais coerente; o eixo definitivo de preço ainda não foi confirmado.
- Cobrança por visualização deve ser evitada inicialmente por tornar o custo imprevisível no momento de maior uso.
- Freemium não deve ser adotado antes de validar custo de atendimento, ativação curta e aquisição orgânica.
- Os primeiros pilotos devem testar pagamento real, mesmo que com acompanhamento manual.
- Faixas de preço, período de teste, cobrança e planos continuam pendentes e não devem ser implementados a partir deste documento.
- A disposição a pagar deve ser comparada ao valor de uma oportunidade recuperada, não ao custo de armazenamento de arquivos.

### Hipóteses críticas a validar

1. A informação muda decisões de follow-up, em vez de apenas satisfazer curiosidade.
2. O ICP envia propostas com frequência suficiente para criar recorrência.
3. Destinatários aceitam abrir um link rastreável.
4. Os eventos podem ser medidos e explicados com confiança suficiente.
5. O usuário aceita substituir anexo ou link de armazenamento pelo fluxo do Localpaper.
6. Uma oportunidade recuperada justifica o preço.
7. O histórico acumulado cria valor crescente e retenção.
8. Privacidade, segurança e políticas dos destinatários não bloqueiam a adoção.
9. Pequenas equipes aceitam pagar antes de exigir integrações e colaboração.
10. O produto consegue distinguir interação humana de prévias automáticas, scanners de segurança e bots; falsos alertas destruiriam a confiança na promessa central.

### Validação antes da construção ampla

1. Realizar 12–15 entrevistas baseadas na última proposta real enviada pelo participante.
2. Buscar 5–10 pilotos pagos antes de desenvolver o produto completo.
3. Executar um piloto concierge, entregando acompanhamento e alertas de forma manual ou assistida sempre que possível.
4. Testar mensagens centradas em follow-up, retorno à proposta e perda de timing.
5. Observar um protótipo com usuários, sem explicar previamente o fluxo.
6. Pedir compromisso concreto: pagamento, depósito, carta de intenção ou acesso a um piloto real.
7. Testar preço contra frequência e valor médio das propostas.
8. Perguntar após cada sinal: “Isso mudou o que você faria agora?”.
9. Comparar usuários que receberam sinais úteis com os que não receberam.
10. Preferir entrevistas e comportamento real a testes A/B sem volume suficiente.

### Métricas iniciais

**Ativação:**

- percentual que envia o primeiro PDF;
- percentual que gera e compartilha o primeiro link;
- percentual cujo link recebe uma interação humana válida;
- percentual que visualiza o primeiro alerta;
- percentual que declara que o alerta ajudou;
- tempo até link compartilhado;
- tempo até primeiro sinal útil.

**North star inicial proposta:** propostas rastreadas que geraram um sinal considerado útil pelo remetente.

**Retenção:**

- segundo documento em 14 dias;
- documentos rastreados por semana;
- retorno após alertas;
- dois ou mais sinais úteis em 30 dias;
- retenção por ciclo de envio, D7 e D30.

**Conversão comercial:**

- entrevista → piloto pago;
- piloto → continuidade paga;
- usuário ativado → pagante;
- preço aceito por perfil;
- cancelamento antes e depois do primeiro sinal útil.

As metas numéricas ainda precisam de uma linha de base. Cadastros, tempo de sessão e tamanho de lista não devem ser tratados como prova de valor.

## Princípios do produto

### Observados no design

1. **Sinal antes da ação — Confirmado:** métricas e mudanças aparecem junto de indicações de follow-up (`Painel`, `Analytics`).
2. **Resumo primeiro, detalhe depois — Confirmado:** cards de KPI antecedem gráficos, rankings e tabelas.
3. **Ações orientadas por linguagem — Confirmado:** textos explicam o resultado (“Criar meu primeiro documento”, “Exportar Relatório”) em vez de expor termos técnicos.
4. **Consistência de navegação — Confirmado:** barra lateral recorrente com Home, Assistente, Documentos, Analytics, Cofre, Branding e Configurações.
5. **Progressão guiada — Confirmado:** cadastro, pergunta de onboarding, primeiro documento e sequência de ativação por e-mail.

### Recomendações iniciais

1. **Tratar confiança como parte do produto — Recomendação:** explicar origem e significado de scores e “sinais quentes”.
2. **Priorizar o ciclo mínimo — Recomendação:** enviar, compartilhar, observar e decidir antes de expandir módulos incompletos.
3. **Consolidar a marca atual — Recomendação:** substituir referências legadas a BaseDoc e OjoDoc por Localpaper após decidir quais telas e comunicações antigas continuam válidas.
4. **Projetar estados, não só telas ideais — Recomendação:** completar vazio, carregamento, erro, permissão, cancelamento e retorno.
5. **Preservar foco — Recomendação:** distinguir capacidades confirmadas de ideias ainda apresentadas apenas em cards do Assistente.

## Funcionalidades observadas

| Funcionalidade | Finalidade | Usuário | Resultado esperado | Evidência visual | Certeza | Lacunas |
|---|---|---|---|---|---|---|
| Cadastro por e-mail ou Google | Criar conta e iniciar uso | Novo usuário | Conta criada | `Onboarding-Login / Page Create account` | **Confirmado** | Senha, verificação, consentimento e falhas não estão definidos; o campo exibido contém apenas e-mail |
| Login por e-mail/senha ou Google | Retornar ao produto | Usuário cadastrado | Sessão iniciada | `Onboarding-Login / Page Login` | **Confirmado** | Recuperação e erros não estão desenhados |
| Onboarding de perfil | Identificar destinatários frequentes | Novo usuário | Perfil inicial informado ou etapa pulada | `Onboarding-Login / 1` | **Confirmado** | Só uma pergunta está legível; efeito da resposta é desconhecido |
| Adicionar/enviar documento | Colocar o primeiro ou novo documento no produto | Remetente | Documento disponível para compartilhar | `Interface / Add Doc`, `Upload Doc`, `Pop up - juntar doc...`; `e-mail / D0–D2` | **Confirmado** | Formatos, limites, processamento e falhas pendentes |
| Gerar link rastreável | Distribuir documento com acompanhamento | Remetente | Link compartilhável | `e-mail / D0–D2`; coluna “Link” em `Interface / Painel` | **Confirmado** | Permissões, expiração, domínio e segurança não definidos |
| Lista de documentos | Consultar documentos e sinais recentes | Remetente | Acesso a data, tempo, última visita e ações | `Interface / Painel`; `Documentos` | **Confirmado** | A tela `Documentos` também existe vazia; ações por linha não são legíveis |
| Painel de acompanhamento | Resumir desempenho recente | Remetente/equipe | Visão de abertura, leitores e conversão | `Interface / Painel` | **Confirmado** | Período e fórmulas dos KPIs não estão totalmente definidos |
| Analytics | Analisar engajamento e conversão | Remetente/equipe | Gráficos, ranking e comparação | `Interface / Analytics` populado | **Confirmado** | Há variantes vazias; cálculo de score/conversão pendente |
| Filtro de período | Recortar métricas por tempo | Usuário de analytics | Dados de hoje, 7/30 dias, mês ou período customizado | `Frame 244`, `Frame 246` | **Confirmado** | Aplicação do filtro e calendário customizado não mostrados |
| Exportação de relatório | Levar dados para fora do produto | Usuário de analytics | Relatório com métricas selecionadas | `Analytics / Exportar Relatório`; `Frame 245` | **Confirmado** | PDF/Excel aparecem no Assistente, mas formatos e conteúdo final não estão confirmados no fluxo de exportação |
| Alertas | Avisar sobre mudança ou interesse | Remetente | Notificação no momento relevante | `Page Create account`; `Assistente` (“Alertas personalizados”) | **Confirmado** | Canal, gatilhos, frequência e preferências pendentes |
| Assistente de documentos | Consultar documentos e pedir análises | Usuário da conta | Respostas, insights e localização de conteúdo | `Interface / Assistente`; `Widget-IA` | **Confirmado** | Capacidades aparecem como sugestões; qualidade, limites e ações reais não demonstrados |
| Score de interesse/documentos quentes | Priorizar oportunidades | Vendas/remetente | Score de 0–100 e destaque de propostas com 70+ | cards em `Interface / Assistente` | **Confirmado como conceito de interface** | Fórmula, dados mínimos e validação não definidos |
| Comparação de performance | Comparar duas ou mais propostas | Remetente/equipe | Diferenças de métricas | card em `Interface / Assistente` | **Confirmado como ação oferecida** | Nenhuma tela de resultado encontrada |
| Timeline de atividades | Ver cronologia de visualizações | Remetente | Sequência de eventos do documento | card em `Interface / Assistente` | **Confirmado como ação oferecida** | Tela e granularidade ausentes |
| Cofre | Área navegável chamada Cofre | Usuário da conta | **Pendente** | `Interface / Cofre` | **Confirmado apenas como módulo** | Frame principal vazio; propósito e conteúdo não determinados |
| Branding | Área navegável de personalização | Usuário da conta | **Pendente** | `Interface / Branding` | **Confirmado apenas como módulo** | Frame principal vazio; domínio customizado e controles aparecem isolados, sem fluxo completo |
| Domínio personalizado | Configurar um domínio | Usuário da conta | Link com domínio próprio | componentes `Domínio`, `ojodoc.com`, toggles e “Link text - config” | **Inferido** | `ojodoc.com` é referência legada confirmada; não há tela completa nem relação confirmada com Branding |
| Busca global | Encontrar conteúdo/ações | Usuário da conta | Resultado de “Pesquisa qualquer coisa” | topo de `Painel` e `Assistente` | **Confirmado como controle** | Resultados, escopo e estados ausentes |
| E-mails de ciclo de vida | Ativar uso e comunicar teste/assinatura | Conta do produto na fase BaseDoc | Primeiro documento, trial, planos e confirmação | `e-mail / D0–D7` | **Confirmado como material legado** | BaseDoc é nome anterior confirmado; ainda não está confirmado se trial, planos, assinatura e textos continuam válidos para o Localpaper atual |

## Mapa de páginas

| Página ou tela | Finalidade aparente | Ação principal | Origem no Figma | Confiança | Observações/conflitos |
|---|---|---|---|---|---|
| Logo — ícone | Marca compacta | N/A | `logotipo / Logo-icon` | **Confirmado** | Símbolo circular composto por marcas arredondadas |
| Logo — completa | Símbolo + nome | N/A | `logotipo / Logo-completa` | **Confirmado** | Uso não especificado |
| Logo — texto | Wordmark Localpaper | N/A | `logotipo / Logo-texto` | **Confirmado** | Inter Bold, 65 px, tracking -6% no elemento inspecionado; não é token oficial |
| Login | Acesso de usuário existente | “Entrar” | `Onboarding-Login / Page Login` | **Confirmado** | Google, e-mail, senha, recuperação e link para criar conta |
| Criar conta | Entrada e apresentação de benefícios | “Criar uma conta” | `Onboarding-Login / Page Create account` | **Confirmado** | Há mais de uma composição/variante do conteúdo lateral |
| Onboarding — destinatário | Segmentação inicial | Selecionar Leads/Clientes/Investidores/Time interno | `Onboarding-Login / 1` | **Confirmado** | “Pular para dashboard” presente; conexão com tela seguinte é inferida |
| Home/Painel | Resumo operacional | Consultar métricas e documentos | `Interface / Painel` | **Confirmado** | Marca legada BaseDoc no frame; deve ser migrada se a tela for mantida |
| Documentos | Gestão de documentos | Consultar/adicionar documento | `Interface / Documentos` | **Conflitante** | Há frame vazio e tabela preenchida dentro do Painel |
| Analytics — visão geral | Desempenho agregado | Explorar KPIs/rankings | `Interface / Analytics` populado | **Confirmado** | Existem variantes vazias |
| Exportar Relatório | Configurar exportação | Selecionar métricas/exportar | `Interface / Analytics — Exportar Relatório` | **Confirmado** | Corpo da tela incompleto |
| Assistente | Analisar e consultar documentos | Enviar pergunta/anexo | `Interface / Assistente` | **Confirmado** | Uma variante com e outra sem navegação lateral |
| Widget Ojo | Assistência em painel flutuante | Perguntar sobre documentos | `Interface / Widget-IA` | **Confirmado** | Nome do assistente é “Ojo”; relação com assistente de página inteira é inferida |
| Cofre | Módulo navegável | **Pendente** | `Interface / Cofre` | **Confirmado apenas como entrada** | Conteúdo vazio |
| Branding | Módulo navegável | **Pendente** | `Interface / Branding` | **Confirmado apenas como entrada** | Conteúdo vazio; componentes de domínio isolados |
| Configurações | Entrada de navegação | Abrir configurações | navbar recorrente | **Confirmado apenas como entrada** | Tela completa não encontrada |
| Upload/Add Doc | Adição de documento | Selecionar/adicionar arquivo | grupos `Upload Doc`, `Add Doc`, `Pop up - juntar doc...` | **Confirmado** | Fluxo fragmentado em componentes |
| E-mails D0–D7 | Ativação e ciclo comercial | CTAs de documento, planos e assinatura | página `e-mail` | **Confirmado como material legado** | BaseDoc é nome anterior do Localpaper; teste e pagamento não estão confirmados para a versão atual |

## Fluxos do usuário

### 1. Entrada e ativação

1. Acessar `Page Login` ou `Page Create account` — **Confirmado**.
2. Entrar/criar conta por Google ou credenciais apresentadas — **Confirmado**.
3. Responder “Para quem você costuma enviar documentos?” ou pular para o dashboard — **Confirmado**.
4. Chegar ao Painel — **Inferido**, pois o texto “Pular para dashboard” existe, mas não há ligação de protótipo verificada.
5. Adicionar o primeiro documento — **Confirmado como ação oferecida** (`Upload Doc`, `e-mail / D0–D2`).
6. Gerar link e enviá-lo — **Confirmado nos e-mails**, conexão visual completa **Inferida**.

### 2. Compartilhar e acompanhar

1. Adicionar/enviar documento — **Confirmado**.
2. Obter link rastreável — **Confirmado**.
3. Compartilhar com destinatário — **Confirmado no texto**; interface de envio não encontrada.
4. O destinatário abre/navega/retorna — **Confirmado como evento medido**; visualizador do destinatário não encontrado.
5. Painel e Analytics exibem aberturas, leitores, tempo, variação e ranking — **Confirmado**.
6. Usuário decide fazer follow-up — **Inferido como ação externa**, sustentado pela proposta de valor, mas sem botão/fluxo de follow-up.

### 3. Analisar e priorizar

1. Abrir Analytics — **Confirmado**.
2. Escolher período: Hoje, Últimos 7 dias, Últimos 30 dias, Este mês ou Customizado — **Confirmado**.
3. Consultar score de engajamento, taxa de conversão e ranking — **Confirmado**.
4. Exportar relatório e selecionar métricas — **Confirmado como fluxo iniciado**; conclusão ausente.

### 4. Pedir ajuda ao Assistente

1. Abrir Assistente ou Widget Ojo — **Confirmado**.
2. Escrever pergunta e, na página inteira, anexar conteúdo — **Confirmado**.
3. Escolher sugestões como análise, localização, documentos quentes, comparação, exportação, score, timeline ou alertas — **Confirmado como affordance**.
4. Receber resposta/resultado — **Pendente**, pois nenhum estado respondido foi encontrado.

### 5. E-mails da fase BaseDoc

1. Conta criada (`D0`).
2. Lembrete de primeiro documento (`D1`).
3. Explicação de sinais de interesse (`D2`).
4. Identificação de públicos e follow-up (`D3`).
5. Teste ainda ativo (`D4`).
6. Último dia de teste (`D5`).
7. Fim do teste e CTA para planos (`D6`).
8. Assinatura aprovada (`D7`).

Todo esse fluxo é **Confirmado como material legado do Localpaper**. BaseDoc era um nome anterior, mas a existência histórica dos frames não confirma que teste, planos, assinatura, cadência ou textos devam ser mantidos na versão atual.

## Estados da experiência

| Estado | Situação | Evidência/ausência |
|---|---|---|
| Inicial | **Confirmado** | Login, criar conta, onboarding, Assistente vazio e Widget Ojo |
| Vazio | **Confirmado** | Frames vazios de `Documentos`, `Analytics`, `Cofre` e `Branding`; não há copy orientativa em todos eles |
| Carregamento | **Pendente** | Nenhum estado claro encontrado |
| Sucesso | **Confirmado em material legado** | “Conta criada” e “assinatura aprovada” em e-mails da fase BaseDoc; nenhum sucesso de upload/exportação da fase Localpaper encontrado |
| Erro | **Pendente** | Nenhum erro de login, upload, link, analytics ou IA encontrado |
| Confirmação | **Parcial** | E-mails confirmam conta/assinatura; confirmação in-app não encontrada |
| Permissão | **Pendente** | Acesso ao link, compartilhamento e permissões não representados |
| Bloqueio | **Parcial, em material legado** | Fim do teste na fase BaseDoc sugere bloqueio comercial; validade atual e comportamento in-app ausentes |
| Cancelamento | **Pendente** | Nenhum fluxo encontrado |
| Retorno ao fluxo | **Parcial** | Login e CTAs de e-mail retornam ao produto; destinos não estão desenhados |

Estados ausentes devem ser projetados e confirmados como trabalho futuro, sem inventar conteúdo agora.

## Linguagem do domínio

| Termo do Figma | Significado aparente | Evidência | Ambiguidade |
|---|---|---|---|
| Documento/doc | Arquivo enviado e acompanhado | Todo o arquivo | Formatos e unidade de versionamento pendentes |
| Link rastreável | Endereço usado para compartilhar e medir acesso | `e-mail / D0–D2` | Segurança, expiração e identidade do leitor pendentes |
| Abertura | Evento de acesso ao documento | `Painel`, `Analytics` | Única versus total precisa ser formalizada |
| Leitor ativo | Pessoa/identidade que consumiu documento | card “Leitores Ativos” | Critério de atividade e identificação pendentes |
| Visualização | Sessão ou evento de consumo | Onboarding e Analytics | Relação com abertura não definida |
| Tempo de visualização | Duração atribuída ao consumo | `Painel` | Método de medição pendente |
| Última visita | Acesso mais recente | tabela do `Painel` | Fuso, sessão e visitante pendentes |
| Sinal de conversão | Indício de intenção/avanço | `Painel` | Não equivale necessariamente a conversão real; fórmula pendente |
| Sinal quente | Sinal considerado prioritário | `Painel`, “Documentos Quentes” | Limiar e regra pendentes |
| Score de engajamento | Índice agregado de visualização/tempo | `Analytics` | Escala visual percentual; fórmula pendente |
| Score de interesse | Nota de 0–100 por documento | `Assistente` | Relação com score de engajamento pendente |
| Taxa de conversão | Propostas que geraram follow-up efetivo | `Analytics` | Como o follow-up é detectado não está definido |
| Documento quente | Proposta com score 70+ e múltiplas aberturas | `Assistente` | Limiares e janela temporal pendentes |
| Timeline de atividades | Cronologia de visualizações | `Assistente` | Eventos e granularidade pendentes |
| Follow-up | Ação posterior ao sinal de interesse | Onboarding, e-mails, Analytics | O produto alerta, recomenda ou executa? Pendente |
| Cofre | Módulo da navegação | navbar/`Cofre` | Propósito totalmente pendente |
| Branding | Módulo de personalização | navbar/`Branding` | Escopo pendente |
| Ojo | Nome exibido no assistente | `Widget-IA` | OjoDoc é nome anterior confirmado do produto; ainda é pendente se “Ojo” continuará como nome do assistente |
| OjoDoc | Nome anterior do Localpaper | domínio `ojodoc.com` e esclarecimento do responsável pelo produto | **Confirmado como marca legada** |
| Localpaper | Nome atual do produto | `logotipo`, `Onboarding-Login` e esclarecimento do responsável pelo produto | **Confirmado como marca atual** |
| BaseDoc | Nome anterior do Localpaper | `Interface`, `e-mail` e esclarecimento do responsável pelo produto | **Confirmado como marca legada** |

## Identidade visual

### Logo

- **Confirmado:** três grupos em `logotipo`: `Logo-icon`, `Logo-completa` e `Logo-texto`.
- **Confirmado:** o ícone é um anel formado por pequenos traços/blocos arredondados; aparece também em login e cadastro.
- **Confirmado:** no elemento `Logo-texto` inspecionado, o wordmark usa Inter Bold, tamanho 65, tracking -6%, preenchimento `#000000`.
- **Atenção:** esses valores pertencem a um elemento específico e não constituem tokens oficiais.
- **Confirmado:** BaseDoc e OjoDoc são marcas anteriores do Localpaper. Seus símbolos, wordmarks e domínios no Figma são assets legados; permanece pendente se “Ojo” será preservado como nome do assistente.

### Cores observadas

- `#000000`: wordmark Localpaper inspecionado.
- `#F4F2F0`: fundo do frame de login inspecionado.
- `#FFFFFF`: superfícies principais e frames.
- Coral/salmão: CTAs, checks, gráficos e destaques. O valor exato não foi validado como token; não deve ser oficializado por aproximação.
- `#F7F4EF`: preenchimento do `Widget-IA` inspecionado.
- `#D2D1CD`: borda do `Widget-IA` inspecionado.
- `#62615E`: borda do filtro `Frame 246` inspecionado.
- Verde e vermelho: variações positivas/negativas em KPIs e rankings.
- **Conflitante:** a página `e-mail` tem fundo de página `#FFD9D9` e CTAs vermelho-vivo, enquanto as telas Localpaper usam coral mais suave.

### Tipografia e hierarquia

- **Confirmado:** Inter aparece no wordmark; a família das demais telas não foi validada por inspeção de propriedade.
- Títulos grandes e diretos; subtítulos curtos; KPIs em peso forte; labels e metadados menores.
- Cards e tabelas usam hierarquia: nome da métrica → valor → comparação temporal.
- **Pendente:** escala tipográfica oficial, pesos, alturas de linha e tokens.

### Espaçamento e layout

- Telas principais desktop em 1920 × 1080; `Painel` aparece também com 1920 × 1175/estrutura interna 1919 × 1079; Analytics selecionado mostrou área interna 1640 × 1343.
- Navegação lateral fixa e conteúdo em área principal; barra de busca aparece no topo do Painel e Assistente.
- Login centralizado; cadastro dividido em duas colunas de 960 × 1080 dentro de frame 1920 × 1080.
- `Widget-IA`: 420 × 618, raio 15.
- Filtro `Últimos 7 dias`: 162 × 44, raio 8 e padding 10.
- **Pendente:** grid, escala de espaçamento e breakpoints oficiais.

### Ícones, bordas e sombras

- Ícones lineares na navegação, cards, inputs e ações; checks coral no cadastro.
- Cards têm bordas discretas e cantos levemente arredondados; tabelas usam linhas/superfícies alternadas.
- Sombras não foram validadas como propriedade recorrente; não há token oficial.
- Referências de bibliotecas aparecem em nomes de componentes (por exemplo, `heroicons`, `carbon`, `solar`, `hugeicons`), mas isso não define uma biblioteca técnica.

### Componentes recorrentes

- Barra lateral expandida e compacta (`Nav bar`).
- Busca global.
- Cards de KPI com comparação positiva/negativa.
- Tabelas e rankings.
- Botões coral de ação primária.
- Inputs de texto, senha e área de pergunta.
- Filtros/dropdowns de período e domínio.
- Tags, toggles, check, chevron e botão com variantes.
- Modal/popup e controles de upload.
- Painel flutuante do Assistente.

### Formulários e interação

- Login: Google, e-mail, senha, recuperação, entrar, criar conta e links legais.
- Cadastro: e-mail, Google, CTA e links legais; a presença de “Esqueceu sua senha?” no cadastro é **Conflitante** com o contexto.
- Assistente: campo amplo, anexo, atalhos e envio por botão circular.
- Analytics: filtros, exportação, seleção de métricas e período customizado.
- Interações sugeridas: expandir/compactar navegação, abrir dropdown, alternar toggle, selecionar tags, abrir popup, fechar widget.

### Navegação

- Home, Assistente, Documentos, Analytics, Cofre, Branding e Configurações são recorrentes.
- **Conflitante:** algumas composições mostram navegação completa, compacta ou ausente; frames vazios coexistem com telas preenchidas.

### Responsividade

- **Confirmado:** há navbar expandida e compacta, o que sugere adaptação de largura.
- **Pendente:** não foram encontradas telas mobile/tablet nem regras de quebra; responsividade completa não está demonstrada.

### Acessibilidade observável

- **Positivo observado:** labels textuais, contraste forte em títulos/CTAs, ícones acompanhados por texto na navegação expandida e estados positivos/negativos com ícone além da cor.
- **Riscos observados:** textos auxiliares muito pequenos e claros; dependência de coral/verde/vermelho; ícones na navbar compacta sem labels visíveis; placeholders usados como orientação.
- **Pendente:** foco, teclado, leitores de tela, ordem semântica, contraste medido, redução de movimento e mensagens de erro.

## Regras para construção por vibe coding

Todo agente que trabalhar no Localpaper deverá:

1. Ler o README antes de iniciar.
2. Consultar o Figma antes de implementar interfaces.
3. Separar fatos, inferências e decisões pendentes.
4. Não inventar funcionalidades ou regras de negócio.
5. Pedir confirmação quando uma decisão importante não estiver documentada.
6. Trabalhar em mudanças pequenas e verificáveis.
7. Reutilizar componentes e padrões existentes.
8. Manter consistência visual e terminológica.
9. Considerar estados vazios, carregamento, sucesso e erro.
10. Preservar acessibilidade e responsividade.
11. Validar visualmente toda interface implementada.
12. Executar testes, lint, verificação de tipos e build quando existirem.
13. Não declarar conclusão sem verificação.
14. Não acessar, exibir ou registrar segredos.
15. Não executar deploys, publicações, ações destrutivas ou alterações externas sem autorização explícita.
16. Atualizar a documentação quando uma decisão for confirmada ou alterada.

## Definição inicial de pronto

Uma funcionalidade só pode ser considerada pronta quando:

- seu objetivo, usuário, entrada, saída e regras foram confirmados;
- corresponde ao fluxo e à linguagem documentados;
- reutiliza padrões visuais existentes ou registra conscientemente uma nova decisão;
- contempla estados inicial, vazio, carregamento, sucesso e erro aplicáveis;
- contempla permissão, confirmação, cancelamento e retorno quando aplicáveis;
- funciona nas larguras confirmadas e não impede futura adaptação responsiva;
- tem navegação por teclado, foco visível, labels e contraste verificados;
- foi validada visualmente contra o Figma;
- foi verificada por testes e checagens disponíveis no projeto;
- não expõe dados sensíveis nem depende de segredos registrados no repositório;
- atualiza este README quando confirma ou altera uma decisão de produto;
- não deixa lacunas críticas escondidas: toda limitação restante está explícita.

## Hipóteses iniciais

### Decisões confirmadas para o primeiro MVP

- O primeiro MVP será um produto funcional e self-service para o Vendedor, podendo usar operação concierge nos bastidores.
- O Vendedor individual é o usuário principal e acompanha suas próprias propostas; empresa, workspace, membros e administração ficam fora do primeiro MVP.
- O retorno humano válido a uma Proposta comercial depois do acesso inicial é o evento central de valor; a primeira visualização é um sinal secundário.
- Proposta comercial é o termo canônico para a unidade acompanhada no primeiro MVP; Documento permanece como categoria futura mais ampla.
- O Follow-up acontece fora do Localpaper. O produto apresenta o sinal e pode registrar manualmente a realização do contato e a utilidade percebida.
- A fronteira descrita em “Fora do MVP” permanece válida integralmente; exceções exigem demonstrar necessidade para completar o ciclo central.
- O Vendedor entra apenas com uma conta Google no primeiro MVP; senha, link mágico e outros provedores ficam fora.
- O Link rastreável é público e não enumerável, não exige senha, não expira automaticamente e pode ser revogado pelo Vendedor.
- A mensagem apresentada para um retorno válido é “Proposta aberta novamente”. Uma nova Sessão de visualização começa depois de pelo menos trinta minutos sem atividade.
- Cada Proposta comercial contém um único PDF de até 100 MB e 100 páginas. PDFs protegidos por senha ou que não possam ser processados são rejeitados com uma explicação.
- O Destinatário pode ler a Proposta comercial no navegador e baixar o PDF. O clique de download é registrado, mas o consumo posterior fora do Localpaper não é observável.
- E-mail é o único canal de alerta do primeiro MVP.
- O Vendedor pode visualizar e copiar ou revogar o Link rastreável. Arquivamento, substituição do PDF, versionamento e exclusão definitiva no fluxo normal ficam fora.
- Autenticação, upload, processamento, link, visualização, sessões, páginas vistas, download, alertas e registros manuais de Follow-up e utilidade usam dados reais. Dados simulados são reservados a demonstrações e testes.
- Antes de acessar o viewer, o Destinatário informa um endereço de e-mail, que será associado às suas sessões e compartilhado com o Vendedor. O Destinatário não cria conta, o endereço não é verificado e o produto o apresenta somente como E-mail informado.
- “Proposta aberta novamente” significa uma nova sessão humana válida iniciada pelo menos trinta minutos depois da sessão anterior. Bots, scanners e prévias automáticas são descartados por melhor esforço, sem garantia absoluta.
- O primeiro MVP possui somente cinco páginas: login com Google, lista de Propostas comerciais, Nova proposta, detalhe com timeline e viewer público.
- A navegação do Vendedor usa cabeçalho simples com logo, Propostas, Nova proposta e menu da conta. A sidebar completa do Figma não faz parte do primeiro MVP.
- Não há onboarding após o login. O primeiro acesso leva ao estado vazio da lista com a ação “Criar minha primeira proposta”.
- A Proposta comercial tem título obrigatório, inicialmente derivado do nome do PDF e editável, e nome do cliente opcional. Outros metadados de organização ou funil ficam fora.
- Login e viewer funcionam a partir de 320 px. A área do Vendedor funciona integralmente a partir de 768 px, é otimizada para desktop e pode orientar o uso de tela maior abaixo desse limite.
- Todas as páginas devem atender à WCAG 2.2 nível AA, incluindo teclado, foco visível e não encoberto, semântica, labels, mensagens associadas, contraste, alvos adequados, zoom, reflow e informação não dependente apenas de cor.
- A criação acontece em uma página única com título, cliente opcional e um PDF. O Link rastreável aparece somente depois do processamento e é copiado por ação explícita.
- A lista mostra título, cliente quando informado, Status da Proposta, criação, Atividade mais recente e ação de copiar link. “Status” é o termo canônico para disponibilidade, com os valores Processando, Pronta, Falhou e Revogada. A atividade é apresentada separadamente como Ainda não aberta, Aberta ou Proposta aberta novamente.
- O detalhe contém identificação, Status da Proposta, ações, Link rastreável, resumo factual e timeline cronológica de criação, aberturas válidas, encerramento de sessão, páginas vistas, download, Follow-up, utilidade e revogação.
- O primeiro MVP não possui arquivamento. A revogação desativa o Link rastreável e preserva o histórico; um novo link pode ser gerado sem reativar o endereço revogado.
- Páginas vistas correspondem às páginas efetivamente exibidas. O tempo ativo é aproximado, pausa após sessenta segundos sem atividade ou quando a aba deixa de estar visível, e não inclui consumo posterior ao download.
- Cada página contempla os estados aplicáveis de carregamento, vazio, conteúdo, processamento, sucesso, cancelamento, falha recuperável e indisponibilidade definidos para seu fluxo.
- Os componentes compartilhados iniciais limitam-se a cabeçalho, menu da conta, botões, campos e validação, seletor de PDF, indicador de status, feedback inline, confirmação, card de Proposta, item de timeline, toolbar do viewer, skeleton e estado vazio.
- O detalhe oferece “Registrar follow-up”, com data e hora atuais e observação opcional. Depois do registro, pergunta “Esse sinal ajudou você a decidir o follow-up?” com Sim, Não e Ainda não sei.
- Depois da revogação, o Vendedor pode gerar um novo Link rastreável. O endereço anterior permanece inválido e a timeline registra a revogação e a nova geração.
- E-mails de alerta usam os assuntos “Sua proposta foi aberta” e “Sua proposta foi aberta novamente”, mostram título, cliente quando informado, horário, ressalva de aproximação e a ação “Ver atividade”. Páginas vistas e tempo permanecem na área autenticada.
- Cada Proposta comercial pertence a exatamente um Vendedor. Somente ele acessa detalhes e ações; qualquer pessoa com um Link rastreável ativo acessa o viewer e o download. Não existem membros, administradores, transferência de propriedade ou acesso do Destinatário à timeline.
- A jornada principal é entrar com Google, consultar a lista, criar e processar uma Proposta comercial, copiar e compartilhar o Link rastreável, receber o alerta após uma Abertura válida, consultar a atividade, realizar o Follow-up fora do Localpaper, registrá-lo e avaliar a utilidade do sinal.
- O viewer deve informar de forma clara e amigável que aberturas, páginas visualizadas e tempo aproximado serão compartilhados com o remetente e que cookies reconhecem novas visitas. O texto final e os controles dependem de validação jurídica da base legal e não devem apresentar mera confirmação de leitura como consentimento.
- WhatsApp é a única integração futura priorizada. Ela permanece fora do primeiro MVP; Drive, Notion, CRM e Slack não devem gerar interfaces ou preparação arquitetural antecipada.
- O E-mail informado não é verificado no primeiro MVP; somente seu formato é validado. Ele atribui sessões a um endereço declarado, mas não comprova a identidade da pessoa.
- O acesso a cada Proposta comercial é lembrado por noventa dias naquele navegador por meio de um identificador opaco e específico do Link rastreável. O endereço de e-mail não é armazenado diretamente no cookie nem usado para acompanhar outras Propostas.
- Um Link rastreável aceita diversos E-mails informados e não possui lista prévia de endereços autorizados. Cada navegador mantém sessões próprias, mesmo quando informa um endereço já usado em outro navegador.
- Para cada E-mail informado, a primeira Sessão de visualização válida é uma abertura e uma nova sessão após trinta minutos é “Proposta aberta novamente”. Um endereço diferente inicia sua própria primeira abertura.
- A timeline e os alertas mostram o E-mail informado, sem nome ou outros dados. A comunicação usa “acesso informado como” e não afirma que uma pessoa específica abriu a Proposta.
- Antes do viewer, a interface solicita o e-mail e informa que o endereço, as aberturas, as páginas visualizadas e o tempo aproximado serão compartilhados com o remetente. A explicação de cookies fica disponível em “Saiba mais”.
- E-mails falsos ou compartilhados são uma limitação assumida e comunicada. O primeiro MVP não usa OTP, bloqueio de domínios ou inferência de identidade.
- O rastreamento de consumo começa somente depois que o Destinatário informa o e-mail e aciona “Acessar proposta”. Antes disso, acessos técnicos não aparecem na timeline do Vendedor.
- O E-mail informado e o histórico permanecem enquanto a conta e a Proposta comercial existirem. O cookie expira em noventa dias; revogar o Link rastreável não apaga eventos já registrados. A política final depende de validação jurídica.
- IP, user agent, cabeçalhos e padrões de acesso podem ser processados apenas para filtragem, segurança e limitação de requisições. Esses dados não são exibidos ao Vendedor e devem ser minimizados ou pseudonimizados.
- O primeiro MVP não oferece exclusão pela interface, mas exige procedimento administrativo para apagar conta, PDFs, E-mails informados, eventos e identificadores mediante solicitação.
- O primeiro MVP usa português do Brasil, sem definir ou restringir o mercado geográfico. Os primeiros pilotos serão conduzidos no Brasil. Datas e horários são exibidos no fuso do navegador do Vendedor.
- Devem funcionar as duas versões estáveis mais recentes de Chrome, Edge, Firefox e Safari e seus equivalentes móveis. O navegador embutido do WhatsApp deve abrir, navegar e baixar a Proposta comercial.
- A validação interna registra login, Proposta criada, link copiado, E-mail informado, primeira abertura, abertura novamente, alerta entregue, retorno ao detalhe, Follow-up, utilidade e segunda Proposta em até quatorze dias, sem dashboard para o Vendedor.
- Falhas de entrega de alerta recebem novas tentativas automáticas limitadas. A timeline permanece correta e o detalhe informa a falha, sem reenvio manual.
- O piloto busca pelo menos dez Vendedores, cinco deles pagantes; setenta por cento devem criar a primeira Proposta e copiar o link; noventa por cento das sessões humanas auditadas devem aparecer uma única vez sem alertas conhecidos de bots; cinquenta por cento dos Vendedores expostos a “Proposta aberta novamente” devem considerar o sinal útil; e trinta por cento devem criar uma segunda Proposta em até quatorze dias.
- Antes de qualquer piloto com Destinatários reais, uma revisão de privacidade deve validar base legal, aviso, controles de cookies, retenção e processo de exclusão.
- O fluxo principal é aceito somente quando um novo Vendedor conclui login, criação, processamento, compartilhamento, recebimento de alerta, consulta da atividade, registro de Follow-up e avaliação de utilidade sem suporte operacional.
- Os critérios do viewer cobrem ausência de rastreamento antes da ação explícita, validação do e-mail, primeira abertura, retorno antes e depois de trinta minutos, vários E-mails informados e navegadores, páginas vistas, tempo ativo, pausa por inatividade e download.
- Os critérios de segurança cobrem isolamento entre Vendedores, separação entre link público e detalhe privado, não enumeração, revogação permanente do endereço antigo, cookies isolados por Proposta, ausência do e-mail no cookie e exclusão administrativa integral de contas de teste.
- Os limites de arquivo são verificados nas bordas de cem megabytes e cem páginas, incluindo excesso de um byte, página adicional, corrupção e proteção por senha. Falhas recuperáveis preservam os dados já informados.
- Em condições normais, PDFs de até vinte e cinco megabytes ficam prontos em até dois minutos e PDFs até cem megabytes em até cinco minutos; o viewer estrutura em até três segundos e mostra a primeira página em até cinco; aberturas chegam à timeline em até sessenta segundos; alertas são solicitados em até dois minutos.
- A aceitação de interface cobre teclado, foco, leitor de tela, contraste, zoom de duzentos por cento, reflow, mensagens e recuperação para todos os estados aplicáveis, além dos navegadores confirmados.
- O principal seam de teste é um fluxo de navegador que atravessa criação, Link rastreável, E-mail informado, visualização, retorno, caixa de e-mail de teste, timeline, Follow-up e utilidade. Seams menores são reservados a PDF, bots, Google e entrega de e-mail.

- **Confirmado:** BaseDoc e OjoDoc são nomes anteriores do Localpaper.
- **Decisão confirmada:** o ciclo inicial é enviar uma proposta em PDF → gerar link → compartilhar → observar um sinal confiável → decidir o follow-up.
- **Decisão confirmada:** o primeiro ICP é formado por agências e consultorias B2B de pequeno porte, com vendas conduzidas pelo fundador ou por um pequeno time comercial.
- **Inferido:** score, documentos quentes e alertas pretendem reduzir o tempo entre interesse e contato.
- **Inferido:** Ojo é o nome do assistente e pode existir como página e widget.
- **Inferido:** Branding inclui personalização de links/domínio.
- **Inferido:** Cofre pode armazenar documentos ou ativos, mas o Figma não sustenta uma definição.
- **Inferido:** referências ao Papermark são pesquisa/inspiração, não telas do produto.
- **Inferido:** Localpaper pretende oferecer alguma forma de exportação de analytics.
- **Pendente:** todas as hipóteses acima exigem confirmação antes de virarem requisitos.

## Contradições encontradas

1. **Migração de marca:** a marca atual Localpaper coexiste no arquivo com assets legados BaseDoc e OjoDoc; a relação histórica está confirmada, mas o inventário do que deve ser mantido, atualizado ou descartado ainda não está definido.
2. **Maturidade das telas:** Analytics e Painel completos coexistem com versões vazias de Analytics, Documentos, Cofre e Branding.
3. **Cadastro:** `Page Create account` contém “Esqueceu sua senha?”, ação típica de login.
4. **Login/cadastro:** há mais de uma composição e ordem para Google, e-mail e campos.
5. **E-mails:** ciclo D0–D7 descreve teste grátis, planos e assinatura BaseDoc, sem suporte equivalente nas telas Localpaper.
6. **Navegação:** versões expandida, compacta e ausente sem regra de responsividade/estado.
7. **Analytics:** “Score de engajamento” percentual e “Score de interesse” 0–100 aparecem sem relação definida.
8. **Conversão:** a tela fala em “Taxa de Conversão” e “follow-up efetivo”, mas não há fluxo que registre follow-up ou conversão.
9. **Documentos:** tela dedicada vazia versus tabela funcional no Painel.
10. **Exportação:** tela `Exportar Relatório` está incompleta, enquanto cards sugerem PDF/Excel.
11. **Cores/marca:** coral suave nas telas Localpaper versus vermelho intenso e fundo rosa nos e-mails BaseDoc.
12. **Referências externas:** capturas nomeadas `papermark` aparecem misturadas a componentes e frames do produto.
13. **Texto:** “Bem vindo” aparece sem hífen em alguns frames; “Boas vindas” e “Boas-vindas” variam.
14. **Dimensões:** frames principais alternam entre 1920 × 1080, 1920 × 1175 e áreas internas diferentes sem regra documentada.

## Fronteira de decisões do primeiro MVP

A fronteira está vazia: não restam decisões conhecidas de produto, jornada, interface, dados ou arquitetura que impeçam a especificação e o design das cinco páginas confirmadas.

Continuam como hipóteses a validar no piloto, não como decisões pendentes: intensidade da dor, disposição a pagar, utilidade do sinal e recorrência de uso. Revisão jurídica de privacidade, escolha do domínio de produção e credenciais dos fornecedores são pré-condições operacionais posteriores, não lacunas da definição do MVP.

## Decisões técnicas do primeiro MVP

As decisões abaixo foram confirmadas somente depois do esclarecimento dos requisitos. Elas não autorizam iniciar a implementação.

- O desenvolvimento deve permanecer sem custo de infraestrutura. Para os pilotos reais, aceita-se um custo-base de até cinco dólares por mês, além de domínio e excedentes previamente controlados.
- A aplicação, incluindo a interface web, será hospedada no Cloudflare Workers. A Vercel fica fora do primeiro MVP porque seu plano gratuito não permite uso comercial e o plano Pro elevaria o custo sem substituir D1, R2, Queues ou o processador de PDFs.
- A interface será uma SPA sem renderização no servidor, construída com TypeScript, React, Vite e React Router em Data Mode. Lucide React fornece os ícones.
- Tailwind CSS implementa estilos e tokens visuais; Radix Primitives fornece os comportamentos acessíveis necessários de menu, modal e confirmação. A aparência continua definida pelo Localpaper, sem importar um design system visual pronto.
- Recharts fica fora do primeiro MVP porque nenhuma das páginas confirmadas contém gráficos.
- A área autenticada e o viewer público usam a mesma origem, separados por rotas, para simplificar cookies, OAuth, segurança e navegação.
- Metadados, contas, sessões e eventos serão armazenados no Cloudflare D1. PDFs serão mantidos em bucket privado no Cloudflare R2 Standard.
- Drizzle fornece schema tipado, consultas e migrações versionadas para o D1. Zod valida dados recebidos nas interfaces dos módulos e demais entradas externas.
- Os primeiros pilotos ocorrerão no Brasil, mas D1 e R2 não oferecem garantia de residência dos dados no país. A revisão de privacidade anterior ao piloto deve avaliar localização e transferência internacional de dados.
- O Vendedor entra somente com Google. Better Auth administra autenticação e sessões, persistidas no D1, usando apenas os escopos básicos necessários de perfil e e-mail.
- Alertas usam Resend e processamento assíncrono por Cloudflare Queues, com tentativas automáticas limitadas e registro de falha.
- A validação definitiva do PDF acontece em processador assíncrono isolado, acionado pela fila. Validações no navegador podem antecipar feedback, mas não determinam que a Proposta está Pronta.
- A aplicação é um monólito modular, inicialmente dividido nos módulos Identidade, Propostas, Visualização, Notificações e Validação do piloto.
- A atividade é registrada cronologicamente de forma imutável, sem adotar event sourcing completo; o Status da Proposta e demais dados atuais permanecem armazenados diretamente.
- Seams são introduzidos somente para dependências que realmente variam entre produção e testes: armazenamento, fila, entrega de e-mail, relógio e classificação de acessos automatizados.
- A verificação usa Vitest, Playwright e axe-core. A observabilidade começa com os recursos nativos da infraestrutura; Sentry gratuito só será acrescentado se esses recursos forem insuficientes.
- O armazenamento recebe alerta operacional antes de atingir oito gigabytes, acompanhado dos limites de banco, fila e e-mail, sem expor quotas ou planos ao Vendedor no primeiro MVP.

Não restam decisões técnicas conhecidas que bloqueiem a especificação. Pagamentos, analytics de produto visíveis ao Vendedor e integrações futuras permanecem fora do primeiro MVP.

## Inventário da investigação no Figma

### Páginas examinadas

- `logotipo`
- `Onboarding-Login`
- `e-mail`
- `Interface`

### Frames, grupos, seções e componentes relevantes examinados

- `logotipo`: `Logo-icon`, `Logo-completa`, `Logo-texto`.
- `Onboarding-Login`: `Page Login`, variantes de `Page Create account`, onboarding `1`, opções Leads/Clientes/Investidores/Time interno e “Pular para dashboard”.
- `e-mail`: `D0 / Email de boas-vindas`, `D1 / Ativação (não fez upload)`, `D2 / Prova de valor (insight)`, `D3 / Social proof leve (identificação)`, `D4 / Urgência suave (trial)`, `D5 / Última chamada`, `D6 / Fim de teste`, `D7 / conversao`.
- `Interface`: `Painel`, `Documentos`, três variantes de `Analytics`, `Exportar Relatório`, duas variantes de `Assistente`, `Widget-IA`, `Cofre`, `Branding`, `Nav bar` expandida/compacta, `Add Doc`, `Upload Doc`, `Pop up - juntar doc...`, `Frame 244` (períodos), `Frame 245` (adicionar métricas), `Frame 246` (últimos 7 dias), tags, botões, toggles, checks, domínio, notificações de novo documento e componentes de link/configuração.
- Referências externas identificadas e separadas da especificação: assets/capturas com nomes `screencapture-app-papermark-*`.

### Limite da investigação

Todos os agrupamentos visíveis e top-level relevantes foram percorridos. Elementos puramente geométricos, vetores internos e duplicatas de baixo nível foram analisados no contexto de seus frames, não catalogados individualmente. A ausência de protótipos conectados, especificações textuais e estados completos impede transformar várias affordances em regras de negócio.
