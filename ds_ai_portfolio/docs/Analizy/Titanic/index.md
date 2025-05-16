
# Analiza Danych – Titanic (EDA)

Eksploracyjna analiza danych pasażerów Titanica, mająca na celu zidentyfikowanie czynników wpływających na przeżycie podczas katastrofy. Zbiór zawiera informacje takie jak płeć, wiek, klasa podróży, relacje rodzinne na pokładzie czy miejsce zaokrętowania. W ramach analizy przeprowadzono wstępne czyszczenie danych, wizualizacje oraz porównania między grupami pasażerów. Projekt pokazuje, jak dane historyczne można wykorzystać do wyciągania praktycznych wniosków i budowania intuicji analitycznej.

<a href="titanic_analiza.ipynb" class="md-button md-button--primary">Pobierz Notebook z analizą Tytanica</a>

<iframe
    id="content"
    src="titanic_analiza.html"
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
