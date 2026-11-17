# Editor de Vídeo para Claude Code e Codex

O Editor de Vídeo usa a identidade da sua marca. Primeiro pede o nome do editor, a paleta, as fontes e as referências. Depois analisa os vídeos com `watch`, monta um guia de edição e pede a narração ou gravação e a trilha de fundo.

## Instalar no Codex

**Pelo GitHub**, cole esta mensagem no Codex:

```text
Use $skill-installer para instalar as skills editor-de-video e watch do repositório ricka2b/editor-de-video. Se uma delas já estiver instalada, instale só a que falta.
```

**Pelo ZIP**, [baixe o pacote](https://github.com/ricka2b/editor-de-video/releases/latest/download/editor-de-video.zip), descompacte e copie as pastas `editor-de-video` e `watch` para `~/.codex/skills/` no macOS ou Linux, ou `%USERPROFILE%\.codex\skills\` no Windows. Se você usa um diretório `CODEX_HOME` personalizado, copie as pastas para o subdiretório `skills` dele. Mantenha a versão existente se já tiver `watch` instalado.

Abra um novo chat no Codex em uma pasta de trabalho e envie:

```text
Use $editor-de-video para configurar meu editor e analisar os vídeos de referência que vou enviar.
```

## Instalar no Claude Code

1. [Baixe o ZIP com as duas skills](https://github.com/ricka2b/editor-de-video/releases/latest/download/editor-de-video.zip) e descompacte.
2. Copie as pastas `editor-de-video` e `watch` inteiras para `~/.claude/skills/` no macOS ou Linux, ou `%USERPROFILE%\.claude\skills\` no Windows. Crie a pasta `skills` se ela ainda não existir. Cada pasta de skill deve conter seu próprio arquivo `SKILL.md`.
3. Abra uma nova sessão local do Claude Code. Se estiver no app Claude Desktop, abra a aba **Code**.
4. Digite `/editor-de-video` para configurar seu editor e enviar referências. Para analisar um vídeo avulso, use `/watch`.

Consulte o [guia oficial de skills do Claude Code](https://code.claude.com/docs/en/skills) para ver as opções de instalação por projeto.

## Requisitos

O `watch` usa Python 3.10 ou superior. Para o modo local, tenha FFmpeg, ffprobe e yt-dlp disponíveis. Na primeira análise, o assistente pode ajudar a verificar as dependências e você pode escolher o modo local para começar sem chave de API. A transcrição local com WhisperX é opcional e baixa um modelo na primeira configuração. O render padrão no Remotion usa Node.js e npm.

## Créditos

A análise de vídeo usa [Watch 0.3.2](https://github.com/bradautomates/claude-video/tree/03ceb42f7fa2c4439aca01752118044baabffb8f/skills/watch), de Bradley Bonanno, com a [licença MIT original](watch/LICENSE).
