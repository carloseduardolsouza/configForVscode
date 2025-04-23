Claro! Adicionei a seção com os atalhos para acessar o `settings.json` no VSCode. Aqui está o `README.md` atualizado:

---

```markdown
# ⚙️ Configuração do VSCode

Este documento fornece uma configuração completa para personalizar o Visual Studio Code, com foco em produtividade, estética e recursos voltados para desenvolvimento web e integração com ferramentas externas como Figma e bancos de dados.

---

## 📦 Extensões recomendadas

Instale as extensões abaixo para obter a melhor experiência com seu VSCode:

| Extensão | Descrição |
|---------|-----------|
| [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) | Ícones modernos para o explorador de arquivos. |
| [Dracula Official](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula) | Tema escuro e vibrante. |
| [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) | Formatador automático de código. |
| [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) | Verificador ortográfico para múltiplos idiomas. |
| [Brazilian Portuguese - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-portuguese-brazilian) | Suporte ao português brasileiro no spell checker. |
| [Pacote de Idioma Português Brasileiro para VS Code](https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-pt-BR) | Tradução da interface do VSCode para português brasileiro. |
| [Spelling Checker for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ban.spellright) | Verificador ortográfico multilíngue com opções avançadas. |
| [Database Client](https://marketplace.visualstudio.com/items?itemName=cweijan.vscode-database-client2) | Cliente de banco de dados direto no VSCode. |
| [Figma for VS Code](https://marketplace.visualstudio.com/items?itemName=figma.figma-vscode-extension) | Integração com projetos Figma. |
| [htmltagwrap](https://marketplace.visualstudio.com/items?itemName=bradgashler.htmltagwrap) | Envolve seleção com tags HTML. |
| [IntelliCode API Usage Examples](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode-api-usage-examples) | Sugestões de código com base em exemplos do GitHub. |
| [Node.js Exec](https://marketplace.visualstudio.com/items?itemName=Miramac.node.js-exec) | Executa arquivos Node.js diretamente do VSCode. |
| [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) | Autocompletar para módulos npm no `import`. |

---

## ⚙️ Configurações (`settings.json`)

Copie e cole o conteúdo abaixo no seu `settings.json` para personalizar o editor:

```json
{
  "window.zoomLevel": 1,
  "workbench.iconTheme": "material-icon-theme",
  "workbench.tree.indent": 15,

  "editor.bracketPairColorization.enabled": true,
  "editor.fontFamily": "Cascadia Code",
  "editor.fontLigatures": true,

  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "files.autoSave": "afterDelay",
  "workbench.colorTheme": "Dracula",
  "cSpell.language": "en,pt-BR,pt"
}
```

---

## ⌨️ Como abrir o arquivo `settings.json`

Você pode acessar o arquivo de configurações de duas formas:

### 🔧 Via Paleta de Comandos

1. Pressione `Ctrl + Shift + P` (ou `Cmd + Shift + P` no Mac).
2. Digite: `Preferences: Open Settings (JSON)` e selecione a opção.

### 📂 Via Menu Gráfico

1. Vá em `Arquivo > Preferências > Configurações` (ou `Code > Preferências > Configurações` no Mac).
2. Clique no ícone de documento `{}` no canto superior direito para abrir em modo JSON.

---

## 🧠 Dicas adicionais

- Baixe a fonte **Cascadia Code** com suporte a *ligaduras* [aqui](https://github.com/microsoft/cascadia-code).
- Certifique-se de que o Prettier esteja habilitado como formatador padrão para evitar conflitos com outros formatadores.
- Combine o tema Dracula com o Material Icon Theme para um visual moderno e consistente.

---

Com essas configurações e extensões, seu VSCode estará pronto para encarar projetos modernos com estilo e eficiência! 🚀