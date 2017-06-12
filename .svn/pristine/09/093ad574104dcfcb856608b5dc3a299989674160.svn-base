(function() {
  function resetFontBase() {
    // var width = document.documentElement.clientWidth;
    var width = window.innerWidth;
    var fontSize;
    if (width < 768) {
      fontSize = width / 37.5;
    } else {
      fontSize = 12;
    }
    fontSize = fontSize > 18 ? 18 : fontSize;
    document.documentElement.style.fontSize = fontSize + 'px';
  }
  resetFontBase();
  // window.addEventListener('resize', resetFontBase);
  window.onresize = resetFontBase;
})();
