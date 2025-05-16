
# Analiza Danych – Irysy (EDA)

Analiza danych dotyczących irysów przeprowadzona w ramach eksploracyjnej analizy danych (EDA). Projekt skupia się na zrozumieniu zależności między cechami tych roślin. Zawiera wizualizacje, wnioski oraz obserwacje, które pokazują, jak wiele informacji można wydobyć z klasycznego zbioru danych.



<a href="iris.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="iris.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>
