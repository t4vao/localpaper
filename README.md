# Localpaper

> Documento fundador baseado exclusivamente na investigação visual do arquivo Figma `localpaper`. Nenhuma tecnologia, arquitetura ou regra não representada no design foi definida aqui.

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
7. Alerta de primeira abertura e retorno relevante por um único canal, ainda a confirmar.
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

## Perguntas pendentes

### Identidade e posicionamento

1. Quais assets e textos das fases BaseDoc e OjoDoc continuam válidos e quais devem ser descartados ou migrados para Localpaper?
2. Ojo é o nome final do assistente? Ele precisa de identidade separada?
3. Qual variação da proposta “Saiba quando uma proposta voltou a receber atenção e priorize seu próximo follow-up” é mais compreendida e valorizada pelo ICP?
4. O ICP escolhido sente a dor com frequência e intensidade suficientes para sustentar aquisição, retenção e pagamento?

### Ciclo principal

5. Quais tipos e tamanhos de documento serão aceitos?
6. O documento é enviado, importado, criado ou todas essas opções?
7. Como o link é gerado, protegido, revogado e expirado?
8. O destinatário precisa se identificar? Como leitores únicos são reconhecidos?
9. Existe um visualizador próprio do documento? Onde estão seus estados?
10. O follow-up ocorre dentro ou fora do produto? Como “follow-up efetivo” é registrado?

### Métricas e decisões

11. Qual a definição de abertura, visualização, leitor ativo, visita e compartilhamento?
12. Como tempo de visualização e tempo por página são calculados?
13. Como são calculados score de engajamento, score de interesse, sinal quente e taxa de conversão?
14. Quais períodos e comparações são padrão?
15. Rankings e variações usam qual janela e base de comparação?
16. Quais métricas podem ser exportadas e em quais formatos?

### Assistente e alertas

17. Quais ações do Assistente realmente fazem parte do primeiro produto?
18. O Assistente apenas responde ou também altera/configura dados?
19. Quais fontes, limites e critérios de confiança uma resposta deve mostrar?
20. Quais eventos disparam alertas e por quais canais?

### Produto e operação

21. O que é o Cofre?
22. O que pode ser configurado em Branding e domínio personalizado?
23. Quais papéis de usuário e permissões existem?
24. Conta, time e workspace são entidades diferentes?
25. O produto terá teste grátis, planos e assinatura? Os e-mails BaseDoc continuam válidos?
26. Qual é o fluxo correto entre cadastro e login, incluindo senha e recuperação?
27. Quais versões de cada frame são as atuais e quais devem ser arquivadas?
28. Quais requisitos de acessibilidade e dispositivos precisam ser suportados primeiro?

## Fora de escopo neste momento

Ainda **não foram definidos**:

- stack;
- arquitetura;
- banco de dados;
- autenticação;
- integrações;
- infraestrutura;
- hospedagem;
- pagamentos;
- analytics;
- estratégia de testes;
- modelo de segurança.

Nenhuma dessas decisões deve ser presumida a partir deste README ou escolhida sem uma tarefa e confirmação específicas.

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
