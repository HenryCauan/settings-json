# ⚙️ settings-json

Personalização completa da minha IDE **Cursor** (baseada no VS Code).  
Este repositório contém meu arquivo `settings.json` com todas as configurações visuais, atalhos, extensões e ajustes que otimizam meu fluxo de trabalho diário como desenvolvedor full-stack. Ele reflete preferências por produtividade, estética clean e eficiência em projetos.

O objetivo é compartilhar uma setup pronta para quem busca um ambiente moderno e focado – sinta-se à vontade para fork e adaptar!

---

## 🧰 Extensões Usadas Diariamente

Aqui vai uma lista das extensões essenciais que instalo em todo setup novo. Elas melhoram a formatação, visualização e depuração, reduzindo tempo gasto em tarefas repetitivas.

| Extensão | ID da Extensão (para instalação) | Função / Motivo |
|----------|-----------------------------------|-----------------|
| **Prettier – Code Formatter** | `esbenp.prettier-vscode` | Formata código automaticamente em salvar, seguindo padrões consistentes (ESLint-friendly). Evita debates de estilo em equipes. |
| **Symbols (Icon)** | `vangware.symbols` | Adiciona ícones temáticos ao explorador de arquivos, facilitando navegação visual em projetos grandes. |
| **Vesper – Theme** | `drcidr.vscode-vesper` | Tema principal dark com alto contraste, reduz fadiga ocular em sessões longas de coding. Perfeito para foco noturno. |
| **Import Cost** | `wix.vscode-import-cost` | Mostra o tamanho de pacotes importados inline – ajuda a otimizar bundles em apps React/Next.js. |
| **Auto Rename Tag** | `formulahendry.auto-rename-tag` | Renomeia tags HTML/XML pareadas automaticamente, acelerando edição de markup. |
| **Error Lens** | `usernamehw.errorlens` | Destaca erros, warnings e infos diretamente na linha de código, sem precisar abrir o terminal. |
| **Min Theme – Theme Secondary** | `miguelsolorio.min-theme` | Tema alternativo minimalista para switches rápidos (ex: modo light em reuniões). |
| **Better Comments** | `aaron-bond.better-comments` | Colore e categoriza comentários (! para alerts, // TODO para tarefas, ? para dúvidas) – organiza código legado. |
---

## 🔧 O Que Está Configurado no settings.json

O arquivo principal (`settings.json`) é o coração do repositório. Ele inclui ajustes globais para:

- **Temas e Aparência**: Ativação automática do Vesper como tema dark principal, com fallback para Min Theme. Customizações de fontes (ex: Fira Code com ligaduras) e ícones via Symbols.
- **Formatação e Lint**: Prettier como formatador default, com auto-save e format on paste. Integração com ESLint para JS/TS.
- **Produtividade**: Error Lens para highlights inline; atalhos customizados (ex: Ctrl + Alt + F para formatar); Import Cost para monitoramento de imports.
- **Usabilidade Geral**: Auto Rename Tag para HTML; Better Comments para anotações coloridas; desativações de telemetria desnecessária para privacidade.
- **Outros Ajustes**: Zoom level, tab size (2 espaços), git integrations e suporte a emmet abreviado.

## 🚀 Como Usar

Siga esses passos para aplicar as configs na sua Cursor (ou VS Code):

### 🧩 **Via Menu da IDE**
1. Abra a Cursor e pressione `Ctrl + Shift + P` (ou `Cmd + Shift + P` no Mac).
2. Digite e selecione: **Preferences: Open Settings (JSON)**.
3. Copie todo o conteúdo do `settings.json` deste repositório.
4. Cole substituindo o existente (faça backup do seu atual primeiro!).
5. Salve e recarregue a janela (`Ctrl + Shift + P` > "Reload Window").

**Compatibilidade:** Testado na Cursor v0.XX (base VS Code 1.XX). Pode conflitar com extensões existentes – resolva via UI.

---

## 📂 Estrutura do Repositório

```
├── settings.json     ← Arquivo principal com todas as configs JSON
├── README.md         ← Este guia detalhado
└── .gitignore        ← Ignora arquivos desnecessários (adicionei para boas práticas)
```

---

## ✨ Nota Final

Essas configurações são otimizadas para meu workflow em desenvolvimento web full-stack. Não é uma "one-size-fits-all" – experimente, ajuste (ex: mude o tema para Dracula se preferir) e faça sua IDE brilhar. Se ajudou, dê uma star no repo! 💻🚀

**Atualizado em: Outubro 2025** – Qualquer dúvida, comente nas issues. Happy coding!
