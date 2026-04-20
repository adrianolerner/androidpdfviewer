Visualizador de PDF simples para Android baseado em pdf.js e provedores de conteúdo. O aplicativo
Não requer nenhuma permissão. O fluxo de PDF é enviado para o ambiente isolado (sandbox).
WebView sem lhe dar acesso à rede, arquivos, provedores de conteúdo ou quaisquer outros dados.

A Política de Segurança de Conteúdo (Content-Security-Policy) é usada para garantir que o JavaScript e os estilos sejam protegidos.
As propriedades dentro do WebView são conteúdo inteiramente estático dos arquivos APK além de bloquear fontes personalizadas, já que o pdf.js se encarrega de renderizá-las por conta própria.

Ele reutiliza a pilha de renderização Chromium robusta, expondo apenas uma pequena parte dela.
Subconjunto da superfície de ataque em comparação com o conteúdo real da web. A renderização em PDF.
O próprio código é seguro em termos de memória com a avaliação dinâmica de código desativada, e mesmo se um invasor conseguiu executar código explorando a renderização web subjacente.
No mecanismo, eles estão dentro do sandbox do renderizador Chromium com menos acesso do que ele teria dentro do navegador.

O Projeto atual é um fork e totalmente baseado no código em https://github.com/GrapheneOS/PdfViewer
Todos os diretos reservados a ele e seus contribuidores.
