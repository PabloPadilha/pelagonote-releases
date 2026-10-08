# PelagoNote

Aplicativo de notas de estudo para quem aprende em profundidade: painéis por domínio (Java, Oracle, Linux, redes, ciências e mais), editor de código, planilhas, documentos com imagens, exportação em PDF e um Document Vault para seus arquivos. Funciona offline, sem conta e sem custo.

Este repositório publica os **instaladores**. O código-fonte não é distribuído aqui.

## Baixar

Vá em **[Releases](../../releases/latest)** e baixe o arquivo `PelagoNote_..._x64-setup.exe` (Windows 10 ou 11).

## Instalação

1. Execute o instalador. Não pede permissão de administrador.
2. Se o Windows mostrar "O Windows protegeu seu computador", clique em **Mais informações → Executar assim mesmo**. O instalador ainda não é assinado digitalmente, então esse aviso é esperado.
3. Abra o PelagoNote pelo atalho.

## Recursos

- Seus dados ficam no seu computador. A sincronização com o Google Drive é opcional (só a pasta do app).
- Importa do **Evernote** (.enex) e de **OneNote, Notion, Obsidian, Joplin, Bear e Google Keep** (Word, Markdown, HTML ou .zip). Exporta para Evernote e em PDF.
- **API local** opcional para scripts e assistentes de IA, com token de escrita e de leitura, e acesso externo via ngrok com a sua própria conta. Não há chat de IA embutido, de propósito: o app não gera custo para ninguém.

## API local (opcional)

Precisa de Python com `pip install fastapi uvicorn`. Ligue em **Ajustes → Servidor de API local**. A documentação das rotas aparece em `http://127.0.0.1:8765/docs` com o app aberto.

## Site

Documentação e detalhes técnicos: https://lively-limit-2e6f.bluepadog.workers.dev/

## Licença

Copyright © 2026 Pablo Padilha. Todos os direitos reservados. O uso do aplicativo é gratuito; a redistribuição do código ou do instalador sem autorização não é permitida.
