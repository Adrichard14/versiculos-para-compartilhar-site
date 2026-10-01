# Página pública do aplicativo

Site estático para a política de privacidade de **Versículos para Compartilhar** e para a verificação de anúncios do AdMob. O conteúdo está em `index.html`; o arquivo `app-ads.txt` precisa permanecer na raiz do domínio.

## Publicar no GitHub Pages

1. Crie um repositório público separado do aplicativo com o nome **`SEUUSUARIO.github.io`**, substituindo `SEUUSUARIO` pelo seu nome de usuário no GitHub. Se esse repositório já existir, confirme seu conteúdo antes de adicionar estes arquivos.
2. Envie `index.html` e `app-ads.txt` para a raiz da branch `main` do repositório.
3. Em **Settings → Pages**, selecione **Deploy from a branch**, branch **main**, pasta **/(root)**, e salve.
4. Abra os dois endereços em uma janela anônima para verificar o acesso público:
   - Política: `https://SEUUSUARIO.github.io/`
   - AdMob: `https://SEUUSUARIO.github.io/app-ads.txt`
5. Informe a URL da política e a URL do site do desenvolvedor na Play Console. Após publicar o aplicativo, vincule sua ficha pública ao AdMob e solicite as verificações necessárias.

O arquivo local `app-ads.txt` contém o ID do editor informado para este aplicativo. Antes da verificação no AdMob, confira se a linha corresponde ao trecho personalizado exibido na sua conta. O mesmo texto da política está disponível dentro do aplicativo; mantenha as duas versões atualizadas quando as práticas de dados mudarem.

O site não usa JavaScript, cookies próprios ou serviços de análise adicionados pelo desenvolvedor. O GitHub Pages pode tratar dados de acesso conforme sua própria [declaração de privacidade](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
