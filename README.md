<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

નિર્દેશિકા દાખલ કર્યા પછી નોડજ, [direnv](https://direnv.net) , [bun ને](https://github.com/oven-sh/bun) પહેલા ઇન્સ્ટોલ કરવાની ભલામણ કરવામાં આવે છે અને પછી `direnv allow` ( ડિરેક્ટરી દાખલ કર્યા પછી [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) આપોઆપ એક્ઝિક્યુટ થશે).

અર્થ છે: ચાઇનીઝ અનુવાદ જાપાનીઝ, કોરિયન, અંગ્રેજી, અન્ય તમામ ભાષાઓમાં અંગ્રેજી અનુવાદ. જો તમે માત્ર ચાઈનીઝ અને અંગ્રેજીને સમર્થન આપવા માંગતા હો, તો તમે ફક્ત `zh: en` લખી શકો છો.

અર્થ છે: ચાઇનીઝ અનુવાદ જાપાનીઝ, કોરિયન, અંગ્રેજી, અન્ય તમામ ભાષાઓમાં અંગ્રેજી અનુવાદ. જો તમે માત્ર ચાઈનીઝ અને અંગ્રેજીને સમર્થન આપવા માંગતા હો, તો તમે ફક્ત `zh: en` લખી શકો છો.

* [ફ્રન્ટ-એન્ડ કોડ](https://github.com/xxai-art/web)
* [સમગ્ર સાઇટ માટે ભાષા પેક](https://github.com/xxai-art/web/tree/main/i18n)
* [લૉગિન મોડ્યુલો માટે ભાષા પેક](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [વેબસાઇટ બહુભાષી દસ્તાવેજીકરણ](https://github.com/xxai-doc)

ફ્રન્ટ-એન્ડ પ્રોગ્રામિંગ લેંગ્વેજ [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) છે, જે કોફીસ્ક્રિપ્ટ સિન્ટેક્સ પર આધારિત કેટલીક સુવિધાઓ ઉમેરે છે, જુઓ [./coffee_plus.md](./coffee_plus.md) .

## વેબસાઇટ્સ અને દસ્તાવેજોનું આંતરરાષ્ટ્રીયકરણ

નીચેના 3 પ્રોજેક્ટ્સ પર બિલ્ડ કરો

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  પ્રત્યય છે `.mdt` , તમે બાહ્ય ફાઇલોનો સંદર્ભ આપવા માટે `<+ ./coffee_plus/import.js>` જેવા સિન્ટેક્સનો ઉપયોગ કરી શકો છો અને પ્રત્યય સાથે માર્કડાઉન જનરેટ કરી શકો છો `.md` .

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  માર્કડાઉન અનુવાદ કોડ્સ અને લિંક્સનું ભાષાંતર કરશે નહીં અને અનુવાદિત વાક્યોને કેશ કરશે. જો અનુવાદમાં ફેરફાર કરવામાં આવ્યો છે પરંતુ મૂળ લખાણમાં ફેરફાર કરવામાં આવ્યો નથી, તો તેને ફરીથી ચલાવવાથી અનુવાદના ફેરફાર પર ફરીથી લખાશે નહીં.

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  `yaml` જનરેટ કરેલી વેબસાઇટ્સનું ભાષાંતર કરવા માટેની ભાષા ફાઇલો.

### દસ્તાવેજ અનુવાદ ઓટોમેશન સૂચનાઓ

કોડ રીપોઝીટરી [xxai-art/doc](https://github.com/xxai-art/doc) જુઓ

નિર્દેશિકા દાખલ કર્યા પછી નોડજ, [direnv](https://direnv.net) , [bun ને](https://github.com/oven-sh/bun) પહેલા ઇન્સ્ટોલ કરવાની ભલામણ કરવામાં આવે છે અને પછી `direnv allow` ( ડિરેક્ટરી દાખલ કર્યા પછી [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) આપોઆપ એક્ઝિક્યુટ થશે).

સેંકડો ભાષાઓમાં અનુવાદિત મોટા કોડ બેઝને ટાળવા માટે, મેં દરેક ભાષા માટે એક અલગ કોડ બેઝ બનાવ્યો અને કોડ બેઝ સ્ટોર કરવા માટે એક સંસ્થા બનાવી.

પર્યાવરણ વેરીએબલ `GITHUB_ACCESS_TOKEN` સેટ કરવું અને પછી [create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) ચલાવવાથી કોડ રિપોઝીટરી આપોઆપ બનશે.

અલબત્ત, તમે તેને કોડ બેઝમાં પણ મૂકી શકો છો.

અનુવાદ સ્ક્રિપ્ટ સંદર્ભ [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

સ્ક્રિપ્ટ કોડ નીચે પ્રમાણે અર્થઘટન કરવામાં આવે છે:

[bunx](https://bun.sh/docs/cli/bunx) એ npx માટે રિપ્લેસમેન્ટ છે, જે ઝડપી છે. અલબત્ત, જો તમારી પાસે બન ઇન્સ્ટોલ કરેલ નથી, તો તમે તેના બદલે `npx` ઉપયોગ કરી શકો છો.

`bunx mdt zh` `.mdt` zh ડિરેક્ટરીમાં `.md` તરીકે રેન્ડર કરે છે, નીચે 2 લિંક કરેલી ફાઇલો જુઓ

* [coffee_plus.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [coffee_plus.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` એ અનુવાદ માટેનો મુખ્ય કોડ છે (જો તમારી પાસે ફક્ત `nodejs` ઇન્સ્ટોલ કરેલ હોય, પરંતુ `bun` અને `direnv` ઇન્સ્ટોલ કરેલ ન હોય, તો તમે અનુવાદ કરવા માટે `npx i18n` પણ ચલાવી શકો છો).

તે [i18n.yml ને](https://github.com/xxai-art/doc/blob/main/i18n.yml) પાર્સ કરશે, આ દસ્તાવેજમાં `i18n.yml` નું રૂપરેખાંકન નીચે મુજબ છે:

```
en:
zh: ja ko en
```

અર્થ છે: ચાઇનીઝ અનુવાદ જાપાનીઝ, કોરિયન, અંગ્રેજી, અન્ય તમામ ભાષાઓમાં અંગ્રેજી અનુવાદ. જો તમે માત્ર ચાઈનીઝ અને અંગ્રેજીને સમર્થન આપવા માંગતા હો, તો તમે ફક્ત `zh: en` લખી શકો છો.

છેલ્લું છે [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) , જે `README.md` એન્ટ્રી જનરેટ કરવા માટે દરેક ભાષાના `README.md` ના મુખ્ય શીર્ષક અને પ્રથમ ઉપશીર્ષક વચ્ચેની સામગ્રીને બહાર કાઢે છે. કોડ ખૂબ જ સરળ છે, તમે તેને જાતે જોઈ શકો છો.

Google API નો ઉપયોગ મફત અનુવાદ માટે થાય છે. જો તમે Google ને ઍક્સેસ કરી શકતા નથી, તો કૃપા કરીને પ્રોક્સી ગોઠવો અને સેટ કરો, જેમ કે:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

અનુવાદ સ્ક્રિપ્ટ `.i18n` ડિરેક્ટરીમાં અનુવાદિત કેશ જનરેટ કરશે, કૃપા કરીને તેને `git status` સાથે તપાસો અને પુનરાવર્તિત અનુવાદોને ટાળવા માટે તેને કોડ રિપોઝીટરીમાં ઉમેરો.

કૃપા કરીને જ્યારે પણ તમે કેશ અપડેટ કરવા અનુવાદમાં ફેરફાર કરો ત્યારે `bunx i18n` ચલાવો.

જો મૂળ લખાણ અને અનુવાદ એક જ સમયે સંશોધિત કરવામાં આવે, તો કેશ મૂંઝવણમાં આવશે, તેથી જો તમે ફેરફાર કરવા માંગતા હો, તો તમે ફક્ત એક જ સંશોધિત કરી શકો છો, અને પછી કેશને અપડેટ કરવા માટે `bunx i18n` ચલાવો.
