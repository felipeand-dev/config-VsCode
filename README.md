# Configurações pessoais do VS Code

Coleção versionada de preferências do Visual Studio Code para desenvolvimento web, com variantes de fonte, temas e organização da interface.

## O que há no repositório

- `comFont.txt`: configuração principal com JetBrains Mono;
- `semFont.txt`: variante sem a fonte personalizada;
- `Themes.txt`: referências de temas;
- `Teste.json` e `Unsaved Workflow.json`: experimentos e versões alternativas.

As configurações abrangem formatação, ESLint, Emmet, terminal integrado, ícones, temas, file nesting, Code Spell Checker e ajustes visuais.

## Como usar

1. Faça backup do seu `settings.json` atual.
2. No VS Code, abra a paleta de comandos.
3. Execute **Preferences: Open User Settings (JSON)**.
4. Copie somente as opções desejadas de `comFont.txt` ou `semFont.txt`.
5. Instale as extensões correspondentes às configurações que decidir manter.

> [!CAUTION]
> Não substitua seu arquivo inteiro sem revisão. Algumas opções dependem do sistema operacional, de extensões específicas e de fontes instaladas localmente.

## Dependências opcionais

A configuração faz referência, entre outras, a:

- Prettier;
- ESLint;
- Code Spell Checker;
- GitLens;
- Code Runner;
- Live Server;
- temas de ícones e produtos;
- extensão APC para personalização da interface;
- JetBrains Mono / Nerd Font na variante com fonte.

## Observações

- Arquivos com comentários devem ser tratados como JSONC, não JSON estrito.
- Atalhos, perfis de terminal e nomes de fontes podem precisar de ajustes para Windows, macOS ou Linux.
- O VS Code não instala automaticamente as extensões apenas porque uma configuração faz referência a elas.

