# 💸 App de vitrine para profissionais da beleza - Beleza Beagá

Link de acesso: https://beleza-bh-beauty-finder.lovable.app

•	A dor escolhida e por que ela vale um negócio;
Conectar profissionais da beleza com potenciais clientes, em Belo Horizonte/MG

•	O tamanho de mercado e o Business Model Canvas;
Belo Horizonte tenha cerca de 975 mil a 990 mil mulheres com idade entre 18 e 80 anos (potenciais clientes).
TAM (Mercado Total)	Profissionais autônomas e MEIs de beleza (manicure, cabelo, depilação, estética) formalizadas e informais no Brasil.	~1,5 milhão de profissionais (dados Sebrae/IBGE do setor)	R$ 900 milhões / ano
SAM (Mercado Endereçável)	Profissionais desses 4 nichos atuando em Belo Horizonte e Região Metropolitana (RMBH) com presença digital básica (WhatsApp/Instagram).	~38.000 profissionais (proporcional à população e densidade de MEIs de BH/RMBH)	R$ 22,8 milhões / ano
SOM (Mercado Obtível - Ano 1)	Fatia realista capturada nos primeiros 12 meses focando em bairros de alta densidade em BH (Centro-Sul, Pampulha, Buritis, Barreiro) + Contagem/Nova Lima.	1% do SAM = 380 profissionais pagantes	R$ 228.000 / ano (~R$ 19.000/mês).

BMC
Segmentos de Clientes - Lado Oferta (Pagante): Manicures, cabeleireiras, depiladoras e maquiadoras autônomas/MEIs da RMBH (especialmente quem atende a domicílio ou em estúdio próprio pequeno).Lado Demanda (Gratuito): Mulheres e homens de BH/RMBH que buscam agendamento rápido, confiança e atendimento próximo ou em casa.
Proposta de Valor - Para a Profissional: Fluxo previsível de novos clientes locais sem depender de algoritmo do Instagram ou pagar comissão por serviço. Para o Cliente: Encontrar profissionais verificadas, com preços transparentes e portfólio real no seu bairro, agendando em 1 clique no WhatsApp. Canais - Aquisição Profissional: Abordagem direta no Instagram/WhatsApp, grupos de Facebook de bairros de BH, indicação entre profissionais. Aquisição Cliente: Grupos de condomínios/bairros de BH no WhatsApp, tráfego local (Instagram/Google), boca a boca. Relacionamento Self-service com curadoria humana: Cadastro digital simples, mas aprovação manual e contato próximo via WhatsApp nos primeiros meses para garantir qualidade e retenção. Fontes de Receita Fase 1 (MVP): Gratuito para construir base. Fase 2 (Monetização): Assinatura mensal fixa (ex: R$ 49,90/mês) para perfil ativo + taxa extra opcional para "Destaque no Bairro" (topo das buscas).Recursos-Chave - Plataforma web (Lovable + banco de dados), base curada de profissionais verificadas, selo de confiança e reputação (avaliações reais). Atividades-Chave - Curadoria e verificação de perfis (checar portfólio e identidade), atração de tráfego local qualificado e monitoramento de conversão (cliques no WhatsApp).Parcerias-Chave - Lojas de cosméticos/insumos em BH (ex: pontos no Centro/Savassi para divulgação), cursos profissionalizantes de beleza locais, síndicos/administradores de grupos de condomínio. Estrutura de Custos - Fixos enxutos: Hospedagem/ferramentas no-code (Lovable/Supabase), domínio, registro de marca. - Variáveis: Tráfego pago local (anúncios geolocalizados por bairro em BH) e tempo de curadoria/suporte.
•	A tese que o MVP testa, e o que ficou manual de propósito;
Hipótese de Oferta (Atração sem custo): Profissionais de beleza de BH topam cadastrar seu portfólio, preços e WhatsApp na plataforma gratuitamente quando abordadas.
Métrica de sucesso: Converter pelo menos 25 de 50 profissionais abordadas nos primeiros 10 dias.
Hipótese de Demanda (Intenção de agendamento): Clientes de BH confiam nas informações da vitrine e clicam no botão "Agendar via WhatsApp" ao filtrar por bairro e especialidade.
Métrica de sucesso: Pelo menos 15% dos visitantes únicos da página clicam em "Agendar via WhatsApp" de alguma profissional.
Hipótese de Conversão Real (O clique vira serviço?): Os cliques no WhatsApp realmente se transformam em conversas e agendamentos fechados — e não apenas curiosos perguntando preço.
Métrica de sucesso: Ao perguntar para as 25 profissionais após 15 dias, pelo menos 60% relatam ter recebido mensagens reais vindas do BelezaBH e fechado ao menos 1 atendimento.
Hipótese de Monetização (Disposição a pagar): Depois de receberem os primeiros clientes gratuitos pelo app, as profissionais aceitam pagar uma mensalidade (R$ 39,90 a R$ 49,90) para manter o perfil ativo e receber novos contatos.
Métrica de sucesso: Pelo menos 20% das profissionais ativas no teste aceitam migrar para o plano pago ao final do período gratuito de 30 dias.

Manual: cadastro das primeiras profissionais para startar a demanda.
•	O mega prompt e as correções que você pediu depois;

'''markdown

Crie uma aplicação web responsiva (com foco mobile-first) chamada **"BelezaBH"**, uma plataforma de conexão entre clientes e profissionais de cuidados pessoais (manicure, cabeleireira, depiladora e maquiadora) em Belo Horizonte e Região Metropolitana (Contagem, Betim, Nova Lima, Santa Luzia, Ribeirão das Neves).

Todo o texto da interface, botões, rótulos e dados fictícios devem estar em **Português do Brasil (PT-BR)**.

### 1. Identidade Visual e Paleta de Cores
Use uma estética acolhedora, moderna, limpa e confiável (estilo bem-estar e beleza contemporânea):
- **Fundo Principal (Background):** `#FAF8F6` (Off-white quente)
- **Superfícies / Cards:** `#FFFFFF` com bordas sutis `#EFEAE6` e sombras leves
- **Cor Primária (Destaques, títulos ativos, tags):** `#B85D6F` (Rosa terracota elegante)
- **Cor Secundária (Fundos de destaque suave):** `#F3E5E8` (Nude rosado claro)
- **Cor de Ação / Conversão (Botões principais e WhatsApp):** `#2A7B6F` (Verde esmeralda sofisticado)
- **Texto Principal:** `#1F1D2B` (Grafite escuro)
- **Texto Secundário:** `#6E6A7C` (Cinza arroxeado suave)
- **Selo de Verificado / Avaliações:** `#D99B26` (Dourado âmbar)

---

### 2. Fluxo do Cliente (Busca e Conexão)
1. **Tela Inicial / Vitrine:**
   - Cabeçalho limpo com logo "BelezaBH" e botão discreto "Sou Profissional".
   - Barra de busca e filtros rápidos:
     - **Categoria:** Todas, Manicure/Pedicure, Cabelo, Depilação, Maquiagem.
     - **Localização:** Todos, BH - Centro-Sul/Savassi, BH - Pampulha, BH - Barreiro, BH - Venda Nova, Contagem, Betim, Nova Lima.
     - **Modalidade (Toggle/Filtro):** "Atende a domicílio" | "Espaço próprio".
   - Grid de cards das profissionais contendo: Foto de perfil, Nome, Especialidade principal, Selo "Verificada", Nota média (ex: 4.9 ★), Bairros/Cidades atendidas, Badge ("Vai até você" ou "Salão/Estúdio") e Faixa de preço (ex: "A partir de R$ 45").
2. **Perfil Público da Profissional:**
   - Foto de capa/portfólio, foto de perfil, bio curta, tempo de experiência e selo de verificação.
   - **Galeria de Trabalhos:** Grid com 4 a 6 fotos reais dos serviços realizados.
   - **Tabela de Serviços e Preços:** Lista clara com nome do serviço, duração estimada e valor.
   - **Avaliações de Clientes:** Lista de comentários reais com nota e data.
   - **Botão Fixo no Rodapé (CTA):** "Agendar via WhatsApp" (em verde `#2A7B6F`). Ao clicar, deve registrar um contador de clique/lead no estado da aplicação e abrir um modal simulando o redirecionamento com uma mensagem pré-preenchida: *"Olá [Nome], te encontrei no BelezaBH e gostaria de agendar um horário para [Serviço]!"*.

---

### 3. Fluxo da Profissional (Cadastro e Painel)
1. **Cadastro / Onboarding ("Quero me cadastrar"):**
   - Formulário dividido em 3 etapas simples:
     - *Etapa 1 (Dados Básicos):* Nome completo, WhatsApp, Bio curta, Foto de perfil.
     - *Etapa 2 (Atuação):* Seleção múltipla de especialidades, Bairros/Cidades que atende em BH e RMBH, Modalidade (Domicílio, Espaço próprio ou Ambos) e endereço (se tiver espaço).
     - *Etapa 3 (Serviços e Portfólio):* Adicionar pelo menos 2 serviços com preço e upload simulado de fotos do portfólio.
   - Ao finalizar, o perfil entra com status **"Em Análise"**.
2. **Painel da Profissional (Área Logada):**
   - Banner de status do perfil (Ativo / Em Análise).
   - **Métricas simples:** Total de visualizações no perfil e Total de cliques no botão do WhatsApp nos últimos 30 dias.
   - **Gerenciamento:** Botão para editar preços/serviços, adicionar fotos ao portfólio e alternar disponibilidade ("Agenda Aberta" / "Agenda Lotada").

---

### 4. Painel de Administração (Curadoria e Controle)
Crie uma rota ou aba acessível no menu superior chamada **"Admin"** (para fins de protótipo) contendo:
1. **Cards de Visão Geral (KPIs):**
   - Total de Profissionais Ativas.
   - Cadastros Pendentes de Aprovação.
   - Total de Conexões (Cliques no WhatsApp) geradas na plataforma.
2. **Fila de Aprovação (Curadoria):**
   - Lista de profissionais recém-cadastradas com visualização rápida dos dados e portfólio.
   - Botões de ação: **"Aprovar Perfil"**, **"Reprovar"** e checkbox **"Conceder Selo Verificado"**.
3. **Gestão de Profissionais Ativas:**
   - Tabela com busca e filtro por cidade/categoria.
   - Ações por linha: Destacar no topo da busca (Toggle), Pausar perfil ou Excluir.

---

### 5. Dados Iniciais (Seed Data)
Popule o protótipo inicialmente com **8 perfis fictícios bem detalhados e variados** distribuídos entre BH (Savassi, Buritis, Pampulha, Barreiro) e Região Metropolitana (Contagem e Nova Lima), cobrindo as 4 especialidades (Manicure, Cabeleireira, Depiladora e Maquiadora), com avaliações e tabelas de preços realistas para que o aplicativo já abra pronto para navegação e testes.

'''


