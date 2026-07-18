# Traduko

Tiu chi GitHub-deponejo entenas [MacroDroid](https://www-macrodroid-com.translate.goog/?_x_tr_sl=en&_x_tr_tl=eo&_x_tr_hl=de&_x_tr_pto=wapp)-makroojn por preskau realtempaj transskribo kaj traduko Esperanten de la sono eniranta en la mikrofonan enigon.

## Antaukondichoj

Por la bezonataj dosieroj la makroo uzas dosierujon `/storage/emulated/0/dosierujo/` en la interna memoro de Android.
Certigu, ke tiu dosierujo ekzistas kaj tiucele estas uzebla.
Krome la uzanto bezonas validan OpenAI-API-shlosilon.

## Importi la makroojn

1. Elshutu makroojn [traduko_1.macro](https://www.dropbox.com/scl/fi/o49dmb19gseqarxfyzbx9/traduko_1.macro?rlkey=6lyobwx7a6ynr8i6omoimwa36&st=ntpzrsrt&dl=0) kaj [traduko_2.macro](https://www.dropbox.com/scl/fi/qjv6xq4uw59lxhnob7xbs/traduko_2.macro?rlkey=fjujcpzh3zjolyhysjfjiqhru&st=lfqbbdhd&dl=0) en vian smartfonon.
2. Malfermu apon MacroDroid.
3. En ghin importu la elshutitan makroo-dosieron `traduko_1.macro` trovighantan en via smartfono.
4. Donu chiujn necesajn permesojn al MacroDroid.
5. Ripetu pashojn 3 ghis 4 por la elshutita makroo-dosiero `traduko_2.macro`.
6. En ties agoj `Shell Script` kaj `AI-LLM-peto` anstatauigu la shablonan OpenAI-API-shlosilon per valida OpenAI-API-shlosilo kaj konservu chion.

## Jen kiel funkcias la makrooj

Post kiam la uzanto estas startiginta per la menuo la agojn de makroo `traduko_1` ("Testi agojn"), ghi
1. startigas sonregistron de la mikrofona enigo por malmultaj sekundoj,
2. startigas makroon `traduko_2`, por transskribi kaj traduki Esperanten la sonregistrajhon kaj surekranigi la tradukon, kaj krome
3. ripetas ekde 1, ghis la uzanto malaktivigas makroon `traduko_1` per la menuo.

Temas do pri preskau realtempa traduko. Krome la transskribo kaj traduko estas konservataj en dosieroj. Jamaj tiaj dosieroj estas malplenigataj che chiu denova startigo de makroo `traduko_1`.

Noto: La uzanto povas specifi cellingvon de la traduko alian, ol Esperanton, jene: En ago `AI-LLM-peto` de makroo `traduko_2` la uzanto anstatauigas vorton "Esperanton" per la nomo de la anstataue celata lingvo, ekzemple "la germanan".

## Permesilo ("License")

Chi tiu projekto estas publikigita sub la [MIT-permesilo](./LICENSE).

Vi estas libera uzi, modifi kaj distribui chi tiun projekton, se vi konservas la kopirajtan avizon.
