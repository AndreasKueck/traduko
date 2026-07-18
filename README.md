# Traduko

Tiu chi GitHub-deponejo entenas [MacroDroid](https://www-macrodroid-com.translate.goog/?_x_tr_sl=en&_x_tr_tl=eo&_x_tr_hl=de&_x_tr_pto=wapp)-makroon, kiu

1. estas ekigata per ricevo de `amr`-sondosiero<sup>1</sup>,
2. per `ffmpeg` konvertas la `amr`-sondosieron en `mp3`-sondosieron,
3. ghin transskribas kaj
4. surekrane eligas la transskribon.

La makroo estas fasonita por uzantoj, kiuj volas simpligi la laborfluon de sonkonvertado kaj transskribo rekte en Android-smartfono.

<sup>1</sup> Ekzemple per kunhavigado de vochmesagho trovighanta en Google Messages al MacroDroid.

---

## Antaukondichoj

Antau ol uzi la makroon, certigu, ke jenaj programoj estas instalitaj kaj ghuste agorditaj:

- MacroDroid
- Termux
- `ffmpeg` ene de Termux

Krome la uzanto bezonas validan OpenAI-API-shlosilon por la transskibo. Ghi funkcias per modelo `gpt-4o-transcribe`.

---

## Importi la makroon

1. Elshutu makrojon [tradukoparto1.macro](https://www.dropbox.com/scl/fi/2622d8pfg39ip8pc6qjtq/transskribi_amr.macro?rlkey=ufa0eyy8j65pds97kkcip9i2s&st=jjk691rf&dl=0) kaj [tradukoparto2.macro](https://www.dropbox.com/scl/fi/2622d8pfg39ip8pc6qjtq/transskribi_amr.macro?rlkey=ufa0eyy8j65pds97kkcip9i2s&st=jjk691rf&dl=0)en vian smartfonon.
2. Malfermu apon MacroDroid.
3. En ghin importu la elshutitan makroo-dosieron `tradukoparto1.macro` trovighantan en via smartfono.
4. En agoj `Shell Script` kaj anstatauigu la shablonan OpenAI-API-shlosilon per valida OpenAI-API-shlosilo kaj konservu chion.
5. Donu chiujn necesajn permesojn al MacroDroid.
6. Ripetu paghojn 1 ghis 5 por la elshutita makroo [tradukoparto1.macro](https://www.dropbox.com/scl/fi/2622d8pfg39ip8pc6qjtq/transskribi_amr.macro?rlkey=ufa0eyy8j65pds97kkcip9i2s&st=jjk691rf&dl=0).

## Jen kiel funkcias la makroo

La makroo

1. post ricevo de `amr`-sondosiero ghin shovas en dosierujon `/storage/emulated/0/dosierujo/` kaj renomas en `enigo.amr`.
2. kopias preparitan komandon en la tondejon,
3. malfermas Termux,
4. uzas `ffmpeg`, por konverti la `amr`-dosieron en `mp3`-dosieron nome `eligo.mp3`,
5. atendas permanan algluon de la tondeja enhavo en la Termux-konzolon,
6. preparas la sekvajn pashojn por transskribo,
7. transskribas,
8. forigas dosierojn `enigo.amr` kaj `eligo.mp3` kaj krome
9. surekrane eligas la transskribon.

## Dosierujo por la bezonataj dosieroj

Por la bezonataj dosieroj la makroo uzas dosierujon `/storage/emulated/0/dosierujo/` en la interna memoro de Android.

Certigu, ke tiu dosierujo ekzistas kaj tiucele estas uzebla.

## Permesilo ("License")

Chi tiu projekto estas publikigita sub la [MIT-permesilo](./LICENSE).

Vi estas libera uzi, modifi kaj distribui chi tiun projekton, se vi konservas la kopirajtan avizon.
