
# Analiza Danych EDA Titanic

Zapraszam do wglądu w poruszającą analizę danych dotyczących pasażerów Titanica — jednego z najbardziej symbolicznych wydarzeń w historii transportu morskiego. 

W tym projekcie zagłębiamy się w struktury demograficzne, różnice społeczne oraz czynniki, które miały kluczowy wpływ na przeżywalność podczas katastrofy. 

Analiza odsłania zarówno dramatyczne braki danych wynikające z realiów tamtego czasu, jak i wyraźne wzorce związane z klasą podróży, wiekiem czy ceną biletu. To fascynujące połączenie statystyki, historii oraz ludzkich losów, które pozwala lepiej zrozumieć, jak przebiegała ewakuacja i kto miał największe szanse na uratowanie się. 

Ta eksploracja z pewnością zaciekawi każdego miłośnika danych, a jednocześnie skłoni do refleksji nad wydarzeniem, które od ponad wieku budzi ogromne emocje.


<a href="/portfolio/titanic/titanic.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>
docs/titanic
<iframe
    id="content"
    src="/portfolio/titanic/titanic.html"
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
