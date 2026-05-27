# npminho

<p align="center">
  <img src="./logo.png" alt="NPMinho Logo" width="160" height="160" />
</p>

<p align="center">
  <strong>O centralizador de projetos e scripts locais definitivo para desenvolvedores.</strong>
</p>

<p align="center">
  <a href="https://github.com/CristoferEichstadt/npminho-app/releases/latest">
    <img src="https://img.shields.io/github/v/release/CristoferEichstadt/npminho-app?style=for-the-badge&color=black" alt="Latest Release" />
  </a>
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS-black?style=for-the-badge" alt="Platforms" />
</p>

---

O **NPMinho** é um aplicativo desktop local-first de alta performance feito sob medida para desenvolvedores que gerenciam múltiplos projetos locais diariamente. Inspirado no design system sofisticado do **Paperclip**, ele elimina o atrito de abrir terminais manuais e navegar entre pastas, reunindo todos os seus scripts do `package.json` e comandos personalizados em uma única interface fluida, densa e elegante.

---

## ⚡ Recursos Principais

- 📂 **Varredura Inteligente e Assíncrona:** Aponte para uma pasta raiz e o app mapeia todos os seus projetos (`package.json`) em background de forma incremental e ultra-rápida, sem travar a interface e ignorando automaticamente pastas gigantes (`node_modules`, `.git`, `.next`, etc.).
- 💻 **Consoles Integrados Reais:** Terminais reais de alta performance emulados via `node-pty` e renderizados por `xterm.js`, com suporte a comandos interativos, cores ANSI completas, cópia rápida de logs e limpeza de buffer.
- 🚀 **Execução em 1 Clique (Fewer Clicks):** Execute seus comandos favoritos diretamente na barra lateral de projetos, sem precisar alternar o projeto ativo ou carregar outras telas secundárias.
- 🌟 **Favoritos e Customizações:** Adicione scripts como favoritos permanentes e crie comandos manuais personalizados por projeto (configurando shell de execução, variáveis de ambiente e diretórios específicos).
- 🔔 **Notificações Nativas do Sistema:** Alertas Toast integrados diretamente à Central de Ações do Windows (Windows Toast) caso qualquer script ou tarefa longa em background falhe ou retorne erro.
- 🌓 **Design Dark Premium (OKLCH):** Visual ultra-moderno e fluido baseado no design do Paperclip com contraste otimizado para longas jornadas de trabalho e cansaço visual reduzido.
- ⌨️ **Global Shortcut (Alt+Space):** Ative ou oculte o aplicativo de qualquer lugar no sistema com foco automático instantâneo na barra de pesquisa rápida.

---

## 📥 Como Baixar e Instalar

O NPMinho é distribuído como um aplicativo de desktop nativo e pronto para uso, **sem necessidade de instalar o Node ou rodar comandos de terminal no seu computador**.

### 💻 Para Windows
1.  Acesse a página de [Lançamentos Mais Recentes (Latest Releases)](https://github.com/CristoferEichstadt/npminho-app/releases/latest).
2.  Faça o download do instalador executável: **`npminho-1.0.0-setup.exe`** (ou a versão mais recente disponível).
3.  Dê dois cliques no arquivo baixado. O instalador configurará o aplicativo e criará atalhos na Área de Trabalho e Menu Iniciar automaticamente.

### 🍏 Para macOS
1.  Acesse a página de [Lançamentos Mais Recentes (Latest Releases)](https://github.com/CristoferEichstadt/npminho-app/releases/latest).
2.  Faça o download do arquivo de imagem de disco: **`npminho-1.0.0.dmg`**.
3.  Dê dois cliques no arquivo `.dmg` baixado e arraste o ícone do **NPMinho** para a sua pasta de **Aplicações** (Applications).

---

## 🔄 Como Atualizar o Aplicativo

Para atualizar o seu NPMinho para a versão mais recente com novas correções e melhorias:
1.  Basta acessar a página de [Releases](https://github.com/CristoferEichstadt/npminho-app/releases) e baixar o novo instalador correspondente à sua plataforma.
2.  Execute o novo instalador. Ele substituirá a versão antiga de forma automática e silenciosa.
3.  **Seus dados estão protegidos:** Todos os seus projetos salvos, configurações, comandos customizados e favoritos permanecem **100% preservados e intactos** após qualquer atualização (armazenados em local persistente sob a pasta `%APPDATA%/NPMinho`, isolada de arquivos do sistema).

---

## 🛡️ Segurança e Privacidade
O NPMinho é **local-first**. Isso significa que nenhum dado sobre os seus projetos, caminhos locais, variáveis de ambiente ou logs de terminal é enviado para servidores externos. Tudo é executado, processado e armazenado de forma estritamente privada no seu próprio computador.

---

<p align="center">
  <sub>Feito de desenvolvedor para desenvolvedores. 🐒</sub>
</p>
