# Kör Nokta

Topsuz oyun: savunmacıların görüş ışığından uzak dur, ofsayt çizgisinde kal, doğru anda pası iste.

TTSC Buchen futbol zekası mini oyunu. Tek dosya (index.html), GitHub Pages ile yayınlanır. Diller: TR / DE / EN / FR. Seviyeler: Kolay / Orta / Zor.

Oyun bitince sonuç, içine gömüldüğü sayfaya `postMessage` ile gönderilir: `{source:'ttsc-games', game, level, score, ...}`. TTSC App bu mesajı yakalayıp oyuncu istatistiklerine yazabilir.
