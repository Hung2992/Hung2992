<nav>
    <ul>
        <li><a href="index.html">Főoldal</a></li>
        <li><a href="about.html">Rólunk</a></li>
        <li><a href="contact.html">Kapcsolat</a></li>
    </ul>
</nav>
@media (max-width: 768px) {
    header, footer {
        padding: 0.5rem;
    }
}
document.querySelector('form').addEventListener('submit', function(e) {
    e.preventDefault();
    alert('Űrlap elküldve!');
});
<meta name="description" content="Ez a Szívtelen weboldal bemutatja a legújabb trendeket és információkat.">
<meta name="keywords" content="weboldal, szívtelen, informatika">
<meta name="author" content="Te Neved">
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR_TRACKING_ID');
</script>
