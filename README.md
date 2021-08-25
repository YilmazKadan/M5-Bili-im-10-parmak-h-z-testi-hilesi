# M5-Bili-im-10-parmak-h-z-testi-hilesi
Tamamen zevk amaçlı yapılmıştır hiç bir art niyet içermez! Art niyetli tutumlardan sorumluluk kabul etmiyorum.

```Javascript// Jquery aracılığı ile bir event objesi oluşturuyoruz, bu obje enter keycode'sine sahip 
var ev = $.Event('keyup')
ev.which = 32;

// Saniyenin onda biri kadar dönen bir döngü başlatıyoruz.Ve gerekli değerleri input'a basıp ardından trigger ile yukarıda oluşturduğumuz event nesnemizi çalıştırıyoruz.
setInterval(function(){
    $('#yaziyaz').val($('.golge1').text());
    $('#yaziyaz').trigger(ev);
},100);
```
    
// Buradan console'ya bu kodları yapıştırırak çalıştırabilirsiniz.https://www.m5bilisim.com/tr/on-parmak/hiz-testi/
