# Traduko

Tiu chi GitHub-deponejo entenas [MacroDroid](https://www-macrodroid-com.translate.goog/?_x_tr_sl=en&_x_tr_tl=eo&_x_tr_hl=de&_x_tr_pto=wapp)-makroojn por preskau realtempaj transskribo kaj traduko Esperanten (au alilingven) de la sono eniranta en la mikrofonan enigon.

## Antaukondichoj

Por la bezonataj dosieroj la makroo uzas dosierujon `/storage/emulated/0/dosierujo/` en la interna memoro de Android.
Certigu, ke tiu dosierujo ekzistas kaj tiucele estas uzebla.
Krome la uzanto bezonas validan OpenAI-API-shlosilon.

## Importi la makroojn

1. Elshutu en vian smartfonon makroojn [traduko_0.macro](https://www.dropbox.com/scl/fi/v6vnuzr9i4f9h8j7ez1kt/traduko_0.macro?rlkey=8ia2q8jsnlzg2upnm0qioulqt&st=n658bj9k&dl=0), [traduko_1.macro](https://www.dropbox.com/scl/fi/e00lymi3in4sv5g4xsu9f/traduko_1.macro?rlkey=l9i1dhuz0fqni0cof5wrltfxp&st=0chg7c24&dl=0), [traduko_2.macro](https://www.dropbox.com/scl/fi/5kquyv5vtfmf2oj4bcg3t/traduko_2.macro?rlkey=n20v0gb0x3pau5a4o38toiqk4&st=fmaapvmr&dl=0), [traduko_3.macro](https://www.dropbox.com/scl/fi/lol0xit7q8xdwkoat6lf3/traduko_3.macro?rlkey=97ff56y3dvts92brv7evn310r&st=zwmkqnj3&dl=0), [traduko_4.macro](https://www.dropbox.com/scl/fi/svtuhonff9faspwlvbiia/traduko_4.macro?rlkey=41uzhnc1t1sut3o8a6yvzro6s&st=vxklifs9&dl=0), [traduko_5.macro](https://www.dropbox.com/scl/fi/ak6wglhjlqn79dwyqf9co/traduko_5.macro?rlkey=zzyk1rv8nso96misldlnffqxw&st=5xoz33os&dl=0), [traduko_6.macro](https://www.dropbox.com/scl/fi/vrqvg92xm2h0yymiz6ypg/traduko_6.macro?rlkey=45x2xejaiu81llq6jp7kep22f&st=qkk728d7&dl=0) kaj [traduko_7.macro](https://www.dropbox.com/scl/fi/pwd14c25r780ajqs4vcbz/traduko_7.macro?rlkey=o83o150zmfg7ceu04q87b6o44&st=ycmq1y5t&dl=0).
2. Malfermu apon MacroDroid.
3. En ghin importu la elshutitan makroo-dosieron `traduko_0.macro` trovighantan en via smartfono.
4. Donu chiujn necesajn permesojn al MacroDroid.
5. Ripetu pashojn 3 ghis 4 por la ceteraj elshutita makroo-dosiero `traduko_1.macro` ghis `traduko_7.macro`.
6. En ties agoj `Shell Script` kaj `AI-LLM-peto` anstatauigu la shablonan OpenAI-API-shlosilon per valida OpenAI-API-shlosilo kaj konservu chion.

## Jen kiel funkcias la makrooj

Post kiam la uzanto estas startiginta per la menuo la agojn de makroo `traduko_0` ("Testi agojn"), ghi
1. startigas sonregistron de la mikrofona enigo por malmultaj sekundoj,
2. startigas makroojn `traduko_1` ghis `traduko_7`, por transskribi kaj traduki Esperanten la sonregistrajhon kaj surekranigi la tradukon, kaj krome
3. ripetas ekde 1, ghis la uzanto malaktivigas makroon `traduko_0` per la menuo.

Temas do pri preskau realtempa traduko.

Noto: La uzanto povas specifi cellingvon de la traduko alian, ol Esperanton, jene: En ago `AI-LLM-peto` de la makrooj `traduko_1` ghis `traduko_7` la uzanto anstatauigas vorton "Esperanton" per la nomo de la anstataue celata lingvo, ekzemple "la germanan".

## Permesilo ("License")

Chi tiu projekto estas publikigita sub la [MIT-permesilo](./LICENSE).

Vi estas libera uzi, modifi kaj distribui chi tiun projekton, se vi konservas la kopirajtan avizon.
