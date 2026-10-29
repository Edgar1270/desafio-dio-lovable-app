# SocialFlow — Gestão de Redes Sociais

> Organize seus clientes e suas redes sociais em um só lugar.

![Landing page do SocialFlow](docs/imagens/landing-page.png)

## Sobre o projeto

O **SocialFlow** é uma aplicação web criada para ajudar profissionais de social media, freelancers e pequenas agências a organizar clientes, publicações, tarefas e oportunidades de negócio em um único lugar.

Este projeto foi idealizado como um **MVP (Produto Mínimo Viável)**, com foco em validar uma ideia de negócio antes de investir em funcionalidades mais complexas.

## 🔗 Links

- **Aplicação publicada:** `[INSIRA AQUI O LINK DO SITE PUBLICADO]`
- **Repositório:** `[INSIRA AQUI O LINK DO REPOSITÓRIO PÚBLICO]`

## 1. Dor identificada

Profissionais de social media costumam usar várias ferramentas para organizar clientes, planejar publicações, acompanhar tarefas e controlar contatos comerciais. Com informações espalhadas entre planilhas, mensagens e anotações, surgem problemas como:

- Perda de informações importantes.
- Esquecimento de prazos.
- Dificuldade para acompanhar o andamento das publicações.
- Falta de organização dos clientes.
- Dificuldade para acompanhar potenciais clientes interessados.

O SocialFlow reúne as principais atividades de organização em uma única plataforma.

## 2. Público-alvo

- Profissionais autônomos de social media.
- Freelancers de marketing digital.
- Pequenas agências de comunicação.
- Empreendedores que administram as redes sociais do próprio negócio.

## 3. Tamanho de mercado (TAM, SAM e SOM)

- **TAM:** todo o mercado potencial de ferramentas de gestão de redes sociais.
- **SAM:** parcela que o SocialFlow pretende atender (profissionais autônomos e pequenas agências no Brasil).
- **SOM:** parcela que o negócio espera conquistar inicialmente.

Os valores ainda precisam ser estimados com base em fontes de mercado confiáveis, sem números arbitrários.

## 4. Business Model Canvas

| Bloco | Descrição |
|---|---|
| **Proposta de valor** | Plataforma simples para organizar clientes, publicações, tarefas e leads em um único ambiente. |
| **Segmentos de clientes** | Social medias autônomos, freelancers, pequenas agências e pequenos empreendedores. |
| **Canais** | Landing page, redes sociais, WhatsApp, indicações e comunidades de marketing digital. |
| **Relacionamento** | Cadastro na plataforma, atendimento pelo WhatsApp, orientações de uso e coleta de sugestões. |
| **Fontes de receita** | Modelo freemium: plano gratuito + plano profissional (cobrança só após validação). |
| **Recursos principais** | Aplicação web, banco de dados, autenticação, interface responsiva, hospedagem e conhecimento técnico. |
| **Atividades principais** | Desenvolvimento, divulgação, atendimento e coleta de feedback. |
| **Parcerias principais** | Lovable, Lovable Cloud, GitHub e WhatsApp. |
| **Estrutura de custos** | Hospedagem, planos de ferramentas, manutenção, divulgação e serviços adicionais. |

## 5. A tese que o MVP pretende testar

> Profissionais de social media têm interesse em utilizar uma ferramenta simples que centralize clientes, publicações, tarefas e leads, e parte deles pode estar disposta a pagar por recursos adicionais.

**Hipóteses:**

1. Os profissionais reconhecem a dificuldade de organizar suas atividades em diferentes ferramentas.
2. A centralização das informações torna a rotina mais organizada.
3. O público consegue usar as principais funcionalidades sem treinamento complexo.
4. Os usuários demonstram interesse em continuar usando a ferramenta.
5. Parte dos usuários considera viável pagar por um plano profissional.

**Indicadores de validação:** pessoas interessadas, cadastros realizados, usuários que cadastram clientes e publicações, frequência de uso, feedback recebido e interesse em um plano pago.

## 6. Funcionalidades do MVP

| Funcionalidade | Descrição | Status |
|---|---|---|
| Landing page | Apresentação do produto, benefícios e formulário de interesse | ✅ Implementada |
| Autenticação | Cadastro, login e acesso às áreas privadas | ⏳ Confirmar |
| Painel administrativo | Visão geral de clientes, publicações, tarefas e leads | ⏳ Confirmar |
| Gestão de clientes | Cadastro, edição, consulta e exclusão | ⏳ Confirmar |
| Gestão de publicações | Conteúdos por cliente, rede social, data e status | ⏳ Confirmar |
| Calendário editorial | Visualização das publicações planejadas | ⏳ Confirmar |
| Gestão de tarefas | Prioridades, prazos e status | ⏳ Confirmar |
| Gestão de leads | Registro e conversão de leads em clientes | ⏳ Confirmar |
| Integração com WhatsApp | Abertura de conversas para contato comercial | ⏳ Confirmar |

> Atualize a coluna **Status** conforme cada funcionalidade for implementada e testada.

## 7. O que ficou manual de propósito?

Para manter o MVP simples e barato, estas etapas são manuais:

- Atendimento e negociação pelo WhatsApp.
- Envio de propostas comerciais.
- Confirmação de contratação.
- Envio de links de pagamento, se necessário.
- Publicação efetiva dos conteúdos nas redes sociais.
- Coleta de feedback dos primeiros usuários.

## 8. Tecnologias e ferramentas

- **Lovable** — construção da interface e apoio ao desenvolvimento.
- **Lovable Cloud** — back-end, autenticação e persistência de dados.
- **GitHub** — versionamento e disponibilização do código.
- **WhatsApp** — comunicação com potenciais clientes.
- **HTML, CSS e TypeScript** — estrutura, estilo e lógica da aplicação.

> Confirme as tecnologias efetivamente usadas no código final.

## 9. Mega prompt utilizado

O desenvolvimento foi planejado com o ChatGPT como parceiro na estruturação da ideia e na criação das instruções para o Lovable. O mega prompt solicita:

- Landing page responsiva.
- Cadastro e autenticação.
- Painel administrativo.
- Gestão de clientes, publicações e tarefas.
- Calendário editorial e gestão de leads.
- Integração com WhatsApp.
- Persistência de dados.
- Controles de segurança e privacidade.
- Testes das funcionalidades principais.

A IA acelera o desenvolvimento, mas as decisões, o código e os resultados passam por revisão humana.

## 10. Correções e melhorias

Durante os testes, as falhas e correções são registradas. Pontos verificados:

- Funcionamento dos formulários e validação de campos obrigatórios.
- Persistência dos dados após atualizar a página.
- Navegação entre páginas.
- Filtros e pesquisas.
- Conversão de leads em clientes.
- Responsividade em celulares.
- Proteção dos dados entre usuários diferentes.

## 11. Segurança e privacidade

- Controle de acesso às páginas privadas.
- Restrição de acesso aos registros conforme as permissões do usuário.
- Proteção dos dados armazenados.
- Validação dos dados enviados pelos formulários.
- Nenhuma senha, token ou chave privada no repositório público.
- Coleta apenas das informações necessárias.
- Formulário de interesse com consentimento explícito e link para a política de privacidade.

## 12. Como executar o projeto

```bash
# 1. Clone o repositório
git clone [URL-DO-REPOSITORIO]
cd socialflow

# 2. Instale as dependências
npm install

# 3. Configure as variáveis de ambiente (arquivo .env local, nunca publicado)

# 4. Inicie o projeto
npm run dev
```

> Ajuste os comandos conforme o `package.json` real do projeto.

## 13. Evidências do projeto

### Página inicial

![Página inicial](docs/imagens/landing-page.png)

### Seção de recursos

![Seção de recursos](docs/imagens/recursos-secao.png)

### Página de recursos

![Página de recursos](docs/imagens/pagina-recursos.png)

### Seção "Como funciona"

![Seção Como funciona](docs/imagens/como-funciona-secao.png)

### Página "Como funciona"

![Página Como funciona](docs/imagens/pagina-como-funciona.png)

### Planos

Planos demonstrativos: nenhuma cobrança é feita nesta versão.

![Planos](docs/imagens/planos.png)

### Formulário de interesse

![Formulário de interesse](docs/imagens/formulario-interesse.png)

## 14. Próximas melhorias

- Integração com serviços de envio de e-mail.
- Notificações de prazos e tarefas.
- Relatórios de utilização.
- Integração oficial com plataformas de redes sociais, quando viável.
- Pagamentos integrados.
- Automação de atendimento.
- Novos planos e funcionalidades conforme o feedback dos usuários.

## 15. Conclusão

O SocialFlow mostra como uma ideia de negócio pode virar um produto digital usando inteligência artificial como apoio ao planejamento e ao desenvolvimento. O objetivo é construir uma solução funcional, testar as hipóteses e usar os resultados para orientar os próximos passos.

---

**Projeto desenvolvido como atividade prática de criação e validação de um MVP com apoio de inteligência artificial.**
