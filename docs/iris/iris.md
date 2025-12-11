
# Analiza Danych EDA Irysów

Zapraszam do odkrycia analizy danych irysów, w której przyglądamy się trzem najpopularniejszym gatunkom: Iris-setosa, Iris-versicolor oraz Iris-virginica. 

Projekt ten prowadzi przez kluczowe zależności pomiędzy cechami morfologicznymi kwiatów, pokazując, jak różnią się one między gatunkami i jakie powiązania ujawnia dokładniejsza eksploracja danych. 

To świetna okazja, aby zobaczyć, jak prosta analiza może odsłonić fascynujące wzorce w naturze — od korelacji wymiarów płatków po charakterystyczne cechy każdego gatunku. Zanurz się w świecie danych i poznaj irysy z zupełnie nowej perspektywy!

<a href="/iris/iris.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>


<iframe
    id="content"
    src="/iris/iris.html"
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
