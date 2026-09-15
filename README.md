<div align="center">

<img src="https://trocaticket.com.br/logotipo_troca_ticket.png" alt="TrocaTicket" width="420" />

# 🎟️ TrocaTicket Assets

**Repositório oficial de assets, identidade visual e recursos públicos do TrocaTicket.**

[![GitHub](https://img.shields.io/badge/GitHub-TCTK1%2FTrocaTicket--Assets-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/TCTK1/TrocaTicket-Assets)
[![TrocaTicket](https://img.shields.io/badge/TrocaTicket-trocaticket.com.br-0C0C0C?style=for-the-badge)](https://trocaticket.com.br)

</div>

---

## 📖 Sobre

O **TrocaTicket-Assets** é o repositório central responsável por armazenar, organizar e versionar os recursos visuais e arquivos públicos utilizados no ecossistema **TrocaTicket**.

Aqui são centralizados:

* logotipos;
* símbolos da marca;
* ícones;
* favicons;
* assets para PWA;
* imagens para dispositivos mobile;
* splash screens;
* imagens Open Graph;
* assets de integrações;
* arquivos de SEO;
* manifests;
* metadados públicos;
* materiais visuais compartilhados entre aplicações.

O objetivo é manter uma **fonte única de verdade para a identidade visual do TrocaTicket**, reduzindo duplicações e garantindo consistência entre todos os produtos da plataforma.

> **TrocaTicket** é uma plataforma digital para descoberta, criação, gerenciamento, comercialização, revenda e transferência segura de ingressos para eventos.

🌐 **Site oficial:** [trocaticket.com.br](https://trocaticket.com.br)

📦 **Repositório:** [github.com/TCTK1/TrocaTicket-Assets](https://github.com/TCTK1/TrocaTicket-Assets)

---

# 🗂️ Assets disponíveis

Os arquivos documentados abaixo correspondem aos recursos atualmente utilizados na pasta `public` do ecossistema TrocaTicket.

---

## 🎨 Branding e logotipos

| Arquivo                       |  Dimensão | Uso principal                                |
| ----------------------------- | --------: | -------------------------------------------- |
| `logotipo_troca_ticket.png`   |  2104×747 | Logotipo horizontal principal                |
| `logo_troca_ticket.png`       | 1254×1254 | Símbolo/logo quadrado                        |
| `logo_navbar_web.png`         | 1024×1024 | Logo utilizada na navegação Web              |
| `TrocaTicket-logo-stripe.jpg` |  1600×568 | Logotipo preparado para integrações e Stripe |
| `TrocaTicket-icon-stripe.png` |   512×512 | Ícone utilizado em integrações e Stripe      |

### Uso recomendado

O arquivo:

```text
logotipo_troca_ticket.png
```

deve ser priorizado quando a marca completa precisar ser apresentada.

Já:

```text
logo_troca_ticket.png
```

é mais indicado para espaços quadrados, avatares, ícones, cards e contextos em que o logotipo horizontal não seja adequado.

---

## 📱 App, PWA e dispositivos

| Arquivo                        |  Dimensão | Uso principal                             |
| ------------------------------ | --------: | ----------------------------------------- |
| `icon.png`                     | 1024×1024 | Ícone principal da aplicação              |
| `adaptive-icon.png`            | 1024×1024 | Ícone adaptativo para dispositivos móveis |
| `splash.png`                   | 1284×2778 | Splash screen da aplicação                |
| `splash-icon.png`              | 1024×1024 | Ícone utilizado na splash screen          |
| `web-app-manifest-192x192.png` |   192×192 | Ícone PWA                                 |
| `web-app-manifest-512x512.png` |   512×512 | Ícone PWA em alta resolução               |
| `apple-icon.png`               |   180×180 | Ícone para dispositivos Apple             |
| `apple-touch-icon.png`         |   180×180 | Apple Touch Icon                          |

Esses arquivos são utilizados principalmente em:

* Progressive Web App;
* atalhos na tela inicial;
* dispositivos Android;
* dispositivos iOS;
* instalação da aplicação;
* splash screen;
* manifests Web.

---

## 🌐 Favicons

| Arquivo             | Dimensão / Formato | Uso                        |
| ------------------- | -----------------: | -------------------------- |
| `favicon.ico`       |        48×48 / ICO | Compatibilidade geral      |
| `favicon.png`       |        48×48 / PNG | Favicon padrão             |
| `favicon-96x96.png` |        96×96 / PNG | Favicon em maior resolução |
| `favicon.svg`       |                SVG | Favicon vetorial           |
| `icon0.svg`         |                SVG | Ícone vetorial auxiliar    |
| `icon1.png`         |              96×96 | Ícone auxiliar             |

Sempre que possível, recomenda-se utilizar `favicon.svg` em navegadores modernos, mantendo `.ico` e `.png` para compatibilidade.

---

## 🔎 SEO e compartilhamento

| Arquivo        | Dimensão / Tipo | Uso principal                                         |
| -------------- | --------------: | ----------------------------------------------------- |
| `og-image.png` |        1200×630 | Open Graph e compartilhamento social                  |
| `sitemap.xml`  |             XML | Sitemap público da plataforma                         |
| `llms.txt`     |             TXT | Informações públicas estruturadas para agentes e LLMs |

---

### Open Graph

O arquivo:

```text
og-image.png
```

possui:

```text
1200 × 630 px
```

Essa é uma proporção adequada para previews de compartilhamento em plataformas como:

* WhatsApp;
* LinkedIn;
* Facebook;
* Discord;
* Telegram;
* X;
* mecanismos de busca;
* outras plataformas compatíveis com Open Graph.

---

## 🤖 llms.txt

O arquivo:

```text
llms.txt
```

pode ser utilizado para disponibilizar informações públicas estruturadas sobre o TrocaTicket para:

* agentes de IA;
* assistentes;
* crawlers;
* ferramentas de pesquisa;
* Large Language Models;
* sistemas automatizados de descoberta de conteúdo.

Ele deve conter somente informações apropriadas para acesso público.

---

# ⚙️ Manifestos Web / PWA

Atualmente o projeto possui:

```text
manifest.json
site.webmanifest
```

Eles são responsáveis por definir propriedades relacionadas à instalação e funcionamento do TrocaTicket como aplicação Web.

Entre as configurações estão:

```text
name
short_name
icons
theme_color
background_color
display
```

Configuração visual principal:

```text
theme_color:      #0C0C0C
background_color: #0C0C0C
```

A aplicação utiliza o modo:

```text
standalone
```

permitindo que a PWA seja executada com aparência semelhante a uma aplicação nativa.

---

# 🧩 Outros arquivos

Também estão presentes:

```text
spotify.png

partial-react-logo.png
react-logo.png
react-logo@2x.png
react-logo@3x.png
```

### `spotify.png`

Antes de qualquer remoção, verifique onde esse arquivo está sendo utilizado.

Ele pode estar associado a:

* integrações;
* eventos;
* links externos;
* autenticação;
* componentes da interface.

### Assets React

Os arquivos:

```text
partial-react-logo.png
react-logo.png
react-logo@2x.png
react-logo@3x.png
```

aparentam ser assets legados provenientes de templates ou implementações anteriores.

Caso não existam referências ativas no projeto, recomenda-se removê-los para manter o repositório focado exclusivamente em recursos oficiais do TrocaTicket.

---

# 📁 Estrutura atual

```text
public/
├── TrocaTicket-icon-stripe.png
├── TrocaTicket-logo-stripe.jpg
├── adaptive-icon.png
├── apple-icon.png
├── apple-touch-icon.png
├── favicon-96x96.png
├── favicon.ico
├── favicon.png
├── favicon.svg
├── icon.png
├── icon0.svg
├── icon1.png
├── llms.txt
├── logo_navbar_web.png
├── logo_troca_ticket.png
├── logotipo_troca_ticket.png
├── manifest.json
├── og-image.png
├── partial-react-logo.png
├── react-logo.png
├── react-logo@2x.png
├── react-logo@3x.png
├── site.webmanifest
├── sitemap.xml
├── splash-icon.png
├── splash.png
├── spotify.png
├── web-app-manifest-192x192.png
└── web-app-manifest-512x512.png
```

---

# 🏗️ Estrutura recomendada

Conforme o repositório crescer, recomenda-se organizar os assets por contexto e finalidade.

```text
TrocaTicket-Assets/
│
├── public/
│   │
│   ├── branding/
│   │   ├── logos/
│   │   │   ├── logotipo_troca_ticket.png
│   │   │   ├── logo_troca_ticket.png
│   │   │   └── logo_navbar_web.png
│   │   │
│   │   └── integrations/
│   │       ├── TrocaTicket-logo-stripe.jpg
│   │       └── TrocaTicket-icon-stripe.png
│   │
│   ├── icons/
│   │   ├── app/
│   │   │   ├── icon.png
│   │   │   └── adaptive-icon.png
│   │   │
│   │   ├── apple/
│   │   │   ├── apple-icon.png
│   │   │   └── apple-touch-icon.png
│   │   │
│   │   ├── pwa/
│   │   │   ├── web-app-manifest-192x192.png
│   │   │   └── web-app-manifest-512x512.png
│   │   │
│   │   └── favicon/
│   │       ├── favicon.ico
│   │       ├── favicon.png
│   │       ├── favicon.svg
│   │       └── favicon-96x96.png
│   │
│   ├── mobile/
│   │   ├── splash.png
│   │   └── splash-icon.png
│   │
│   ├── social/
│   │   └── og-image.png
│   │
│   ├── integrations/
│   │   └── spotify.png
│   │
│   └── metadata/
│       ├── manifest.json
│       ├── site.webmanifest
│       ├── sitemap.xml
│       └── llms.txt
│
├── docs/
│   ├── brand-guidelines/
│   └── asset-guidelines/
│
├── README.md
└── LICENSE
```

> ⚠️ **Importante:** arquivos já utilizados em produção não devem ser movidos ou renomeados sem atualizar primeiro todas as referências existentes nas aplicações.

---

# 🎯 Finalidade do repositório

O `TrocaTicket-Assets` deve funcionar como fonte oficial de recursos utilizados em:

* aplicação Web;
* aplicação mobile;
* Progressive Web App;
* landing pages;
* páginas públicas de eventos;
* marketplace;
* dashboard de usuários;
* dashboard de organizadores;
* gestão de eventos;
* ingressos digitais;
* QR Codes;
* check-in;
* check-out;
* transferência de ingressos;
* revenda de ingressos;
* pagamentos;
* Stripe;
* e-mails transacionais;
* SEO;
* redes sociais;
* Open Graph;
* integrações externas;
* materiais institucionais.

---

# 🚀 Como utilizar os assets

## Next.js

Arquivos localizados dentro da pasta `public` podem ser utilizados diretamente pela raiz da aplicação.

```tsx
import Image from 'next/image'

export function TrocaTicketLogo() {
  return (
    <Image
      src="/logotipo_troca_ticket.png"
      alt="TrocaTicket"
      width={420}
      height={149}
      priority
    />
  )
}
```

---

## HTML

```html
<img
  src="/logotipo_troca_ticket.png"
  alt="TrocaTicket"
/>
```

---

# 🌎 Assets hospedados no domínio

Caso os arquivos estejam disponíveis no `public` da aplicação principal, podem ser acessados diretamente pelo domínio.

Exemplo:

```text
https://trocaticket.com.br/logotipo_troca_ticket.png
```

Uso:

```html
<img
  src="https://trocaticket.com.br/logotipo_troca_ticket.png"
  alt="TrocaTicket"
/>
```

> Em aplicações Next.js, o conteúdo da pasta `public` é servido a partir da raiz do domínio. Por isso, não se utiliza `/public/` na URL pública.

---

# GitHub Raw

Quando necessário, também é possível utilizar os arquivos diretamente através do GitHub Raw.

```text
https://raw.githubusercontent.com/TCTK1/TrocaTicket-Assets/main/public/logotipo_troca_ticket.png
```

Exemplo:

```html
<img
  src="https://raw.githubusercontent.com/TCTK1/TrocaTicket-Assets/main/public/logotipo_troca_ticket.png"
  alt="TrocaTicket"
/>
```

> Para recursos críticos utilizados em produção, recomenda-se utilizar infraestrutura própria, CDN ou storage dedicado em vez de depender diretamente do GitHub Raw.

---

# 🖼️ Open Graph

Arquivo atual:

```text
/public/og-image.png
```

Dimensão:

```text
1200 × 630 px
```

Exemplo utilizando Next.js App Router:

```ts
import type { Metadata } from 'next'

export const metadata: Metadata = {
  title: 'TrocaTicket',
  description:
    'Descubra, compre, venda, transfira e gerencie ingressos para eventos.',

  openGraph: {
    title: 'TrocaTicket',
    description:
      'Descubra, compre, venda, transfira e gerencie ingressos para eventos.',

    url: 'https://trocaticket.com.br',

    siteName: 'TrocaTicket',

    images: [
      {
        url: '/og-image.png',
        width: 1200,
        height: 630,
        alt: 'TrocaTicket',
      },
    ],

    locale: 'pt_BR',
    type: 'website',
  },
}
```

---

# 📲 PWA

Os principais assets utilizados pela Progressive Web App são:

```text
/icon.png
/adaptive-icon.png
/web-app-manifest-192x192.png
/web-app-manifest-512x512.png
```

Configuração principal:

```json
{
  "name": "Troca Ticket",
  "short_name": "TrocaTicket",
  "theme_color": "#0C0C0C",
  "background_color": "#0C0C0C",
  "display": "standalone"
}
```

---

## Ao atualizar assets da PWA

Sempre valide:

* dimensões declaradas;
* transparência;
* proporção;
* área segura;
* suporte a `maskable`;
* Android;
* iOS;
* navegadores desktop;
* manifest;
* service worker;
* cache;
* reinstalação da PWA.

Arquivos de PWA costumam permanecer em cache por longos períodos.

---

# 🍎 Apple

Os assets atualmente destinados a dispositivos Apple são:

```text
apple-icon.png
apple-touch-icon.png
```

Dimensão:

```text
180 × 180 px
```

Exemplo:

```html
<link
  rel="apple-touch-icon"
  href="/apple-touch-icon.png"
/>
```

---

# 🎨 Identidade visual

Todos os logos, símbolos, ícones e elementos gráficos presentes neste repositório fazem parte da identidade visual oficial do TrocaTicket.

## Boas práticas

Sempre:

* preserve a proporção original;
* mantenha a qualidade do arquivo;
* utilize a versão apropriada para o contexto;
* mantenha área de respiro ao redor da marca;
* utilize assets oficiais;
* prefira SVG para elementos vetoriais;
* comprima imagens antes da publicação;
* considere WebP ou AVIF para imagens destinadas à Web.

Não:

* distorça a marca;
* estique logos;
* comprima logos;
* altere cores arbitrariamente;
* aplique efeitos sem necessidade;
* altere a tipografia da marca;
* adicione sombras não previstas;
* recrie logos manualmente;
* utilize versões não oficiais.

---

# 🏷️ Convenção de nomes

Para novos arquivos, prefira:

```text
kebab-case
```

## ✅ Recomendado

```text
trocaticket-logo.svg
trocaticket-logo-horizontal.svg
trocaticket-symbol.svg
trocaticket-logo-dark.svg
trocaticket-logo-light.svg

event-placeholder.webp
ticket-email-header.webp
ticket-wallet-icon.png

instagram-profile.png
instagram-cover.webp
og-default.webp
```

## ❌ Evitar

```text
Logo Final.png
Logo Novo.png
logo_novo_FINAL_2.png
Troca Ticket Novo.svg
imagem teste 3.png
NOVO_LOGO_OFICIAL_FINAL.png
```

Não utilize sufixos como:

```text
final
final2
novo
nova
teste
copia
copy
último
definitivo
```

O histórico de versões deve ser controlado pelo **Git**.

---

# ⚡ Otimização

Antes de adicionar qualquer asset ao repositório, faça a otimização adequada.

## PNG / JPG

Recomendações:

* comprima imagens;
* remova metadados desnecessários;
* evite resoluções superiores às necessárias;
* utilize WebP quando apropriado;
* utilize AVIF quando compatível;
* preserve transparência somente quando necessária.

---

## SVG

Recomendações:

* mantenha o `viewBox`;
* remova metadados desnecessários;
* remova grupos vazios;
* remova elementos invisíveis;
* elimine propriedades redundantes;
* utilize ferramentas como **SVGO**.

Exemplo:

```bash
npx svgo trocaticket-logo.svg
```

---

# 📐 Dimensões recomendadas

## Open Graph

```text
1200 × 630 px
```

## Apple Touch Icon

```text
180 × 180 px
```

## PWA

```text
192 × 192 px
512 × 512 px
```

## Ícone principal

```text
1024 × 1024 px
```

---

# 🧹 Assets legados

Antes de remover qualquer arquivo, procure referências em:

```text
src/
app/
pages/
components/
public/
styles/
emails/
metadata/
manifest/
service-worker/
```

Também verifique:

* Vercel;
* Supabase;
* Stripe;
* Resend;
* Apple;
* Google;
* páginas externas;
* e-mails;
* integrações.

Atualmente os principais candidatos a revisão são:

```text
partial-react-logo.png
react-logo.png
react-logo@2x.png
react-logo@3x.png
```

Caso não possuam referências ativas, podem ser removidos.

---

# ⚠️ Manifestos duplicados

Atualmente existem:

```text
manifest.json
site.webmanifest
```

Antes de remover qualquer um deles, verifique qual arquivo está sendo referenciado pela aplicação.

Exemplo:

```html
<link rel="manifest" href="/site.webmanifest" />
```

ou:

```html
<link rel="manifest" href="/manifest.json" />
```

Idealmente, o projeto deve possuir uma fonte oficial para evitar configurações divergentes.

---

# 🔐 Segurança

Este repositório deve armazenar somente conteúdos apropriados para exposição pública ou distribuição controlada.

Nunca adicione:

```text
.env
.env.local
.env.production

API keys
access tokens
refresh tokens
private keys

Stripe Secret Key
Stripe Webhook Secret

Supabase Service Role Key
Supabase JWT Secret

Resend API Key

credenciais de banco de dados
credenciais administrativas
certificados privados
tokens OAuth
```

Também nunca devem ser adicionados dados pessoais de usuários, como:

```text
CPF
RG
telefone
endereço
documentos
dados bancários
dados de pagamento
biometria
```

---

# 🤝 Contribuição

Antes de adicionar ou alterar um asset:

1. Verifique se já existe um arquivo equivalente.
2. Confirme que o recurso pertence ao TrocaTicket.
3. Utilize o diretório correto.
4. Utilize nomenclatura padronizada.
5. Otimize o arquivo.
6. Verifique resolução e proporção.
7. Valide transparência quando aplicável.
8. Verifique onde o arquivo é utilizado.
9. Não quebre URLs existentes.
10. Faça um commit descritivo.
11. Abra um Pull Request para alterações importantes.
12. Valide a alteração antes de realizar merge para `main`.

---

# 🌿 Fluxo Git

Clone o projeto:

```bash
git clone https://github.com/TCTK1/TrocaTicket-Assets.git
```

Entre no diretório:

```bash
cd TrocaTicket-Assets
```

Atualize a branch principal:

```bash
git checkout main
git pull origin main
```

Crie uma nova branch:

```bash
git checkout -b feat/new-brand-assets
```

Adicione as alterações:

```bash
git add .
```

Verifique:

```bash
git status
```

Crie o commit:

```bash
git commit -m "feat: add new TrocaTicket brand assets"
```

Envie a branch:

```bash
git push origin feat/new-brand-assets
```

Depois, abra um **Pull Request** no GitHub.

---

# 📝 Conventional Commits

O projeto recomenda utilizar **Conventional Commits**.

## Novo recurso

```text
feat: add new TrocaTicket brand assets
```

```text
feat: add new PWA icons
```

## Correção

```text
fix: replace incorrect favicon
```

```text
fix: update Open Graph image dimensions
```

## Refatoração

```text
refactor: reorganize branding assets
```

## Manutenção

```text
chore: remove deprecated React assets
```

## Documentação

```text
docs: update assets documentation
```

---

# 🔄 Versionamento e cache

Assets estáticos podem permanecer em cache em diferentes pontos da infraestrutura.

Por exemplo:

```text
Browser
   ↓
Service Worker
   ↓
PWA Cache
   ↓
Vercel CDN
   ↓
Next.js Cache
   ↓
Asset
```

Por isso, substituir um arquivo mantendo exatamente o mesmo nome pode não refletir imediatamente em todos os clientes.

---

## Para alterações relevantes

Considere versionar o nome:

```text
trocaticket-logo-v2.svg
og-image-v2.png
event-placeholder-v2.webp
```

Outra opção é utilizar cache busting:

```text
/logo.png?v=2
```

Entretanto, para assets controlados pelo código, prefira estratégias de versionamento implementadas pela própria aplicação.

---

# 🚫 Evite alterações destrutivas

Não:

```text
renomeie
mova
substitua
remova
```

um asset utilizado em produção sem verificar suas dependências.

Um único arquivo pode estar sendo utilizado simultaneamente por:

```text
Web
PWA
Mobile
E-mail
Stripe
Open Graph
SEO
Apple
Google
Vercel
integrações externas
```

---

# 🌐 Ecossistema TrocaTicket

Os recursos deste repositório podem ser utilizados por diferentes componentes da plataforma.

```text
TrocaTicket
│
├── 🌐 Web
│
├── 📲 PWA
│
├── 📱 Mobile
│
├── 🎟️ Eventos
│
├── 🛒 Marketplace
│
├── 👤 Dashboard do usuário
│
├── 🏢 Dashboard do organizador
│
├── 🎫 Ingressos digitais
│
├── 📷 QR Code
│
├── ✅ Check-in
│
├── 🚪 Check-out
│
├── 🔁 Transferência
│
├── ♻️ Revenda
│
├── 💳 Pagamentos
│
├── 📧 E-mails transacionais
│
├── 🔎 SEO
│
├── 🌍 Open Graph
│
├── 🤖 Agentes e LLMs
│
└── 🔌 Integrações externas
```

---

# 📄 Licença e uso da marca

Os logos, símbolos, ícones, elementos visuais e demais materiais relacionados à identidade do **TrocaTicket** são destinados aos produtos, serviços e parceiros autorizados do ecossistema TrocaTicket.

A disponibilização destes arquivos neste repositório **não concede automaticamente autorização para reprodução, modificação ou utilização comercial da marca por terceiros**.

Para utilizações externas, comerciais ou institucionais da identidade TrocaTicket, consulte previamente os responsáveis pelo projeto.

---

# 🔗 Links

| Recurso         | Link                                                                               |
| --------------- | ---------------------------------------------------------------------------------- |
| 🌐 Site oficial | [trocaticket.com.br](https://trocaticket.com.br)                                   |
| 📦 Assets       | [github.com/TCTK1/TrocaTicket-Assets](https://github.com/TCTK1/TrocaTicket-Assets) |
| 🏢 Organização  | [github.com/TCTK1](https://github.com/TCTK1)                                       |

---

<div align="center">

<br>

## 🎟️ TrocaTicket

### **Descubra, compre, venda, transfira e gerencie ingressos em um só lugar.**

**Tecnologia para conectar pessoas a experiências.**

<br>

[🌐 Site oficial](https://trocaticket.com.br) •
[📦 Repositório de Assets](https://github.com/TCTK1/TrocaTicket-Assets) •
[💻 GitHub](https://github.com/TCTK1)

<br>

---

<sub>© TrocaTicket. Todos os direitos reservados.</sub>

</div>
