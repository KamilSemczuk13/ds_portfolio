# ✈️ Flight 4 U – Inteligentna aplikacja do wyszukiwania lotów

<div style="display: flex; gap: 12px;">

  <a href="https://lotyappmy.streamlit.app/" 
     class="md-button md-button--primary" 
     style="background-color: #1E90FF; color: white; padding: 10px 20px; 
            border-radius: 8px; text-decoration: none; font-weight: bold; display: inline-flex; align-items: center; gap: 8px;">
    🌍 ✈️ 📱 Flight 4 U – Otwórz aplikację
  </a>

  <a href="https://github.com/KamilSemczuk13/Loty_app.git"
     class="md-button md-button--secondary" 
     style="background-color: #333; color: white; padding: 10px 20px; 
            border-radius: 8px; text-decoration: none; font-weight: bold; display: inline-flex; align-items: center; gap: 8px;">
    🐙 Zobacz kod na GitHubie
  </a>

</div>



<iframe
    id="content"
    src="loty.html"
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