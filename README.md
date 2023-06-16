<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

# xxAI.art

વેબસાઇટ કોડનો ભાગ ઓપન સોર્સ છે, અનુવાદને ઑપ્ટિમાઇઝ કરવામાં મદદ કરવા માટે આપનું સ્વાગત છે.

## ફ્રન્ટ-એન્ડ કોડ

* [ફ્રન્ટ-એન્ડ કોડ](https://github.com/xxai-art/web)
* [સમગ્ર સાઇટ માટે ભાષા પેક](https://github.com/xxai-art/web/tree/main/i18n)
* [લૉગિન મોડ્યુલો માટે ભાષા પેક](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [વેબસાઇટ બહુભાષી દસ્તાવેજીકરણ](https://github.com/xxai-doc)

ફ્રન્ટ-એન્ડ પ્રોગ્રામિંગ લેંગ્વેજ [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) છે, જે કોફીસ્ક્રિપ્ટ સિન્ટેક્સ પર આધારિત કેટલીક સુવિધાઓ ઉમેરે છે, જુઓ [./coffee_plus.md](./coffee_plus.md) .

## વેબસાઇટ્સ અને દસ્તાવેજોનું આંતરરાષ્ટ્રીયકરણ

નીચેના 3 પ્રોજેક્ટ્સ પર બિલ્ડ કરો

### [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

માર્કડાઉન ટેમ્પ્લેટ, પ્રત્યય સાથે `.mdt` , `<+ ./coffee_plus/import.js>` સમાન સિન્ટેક્સ સાથે બાહ્ય ફાઇલોનો સંદર્ભ લઈ શકે છે.

[@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

માર્કડાઉન અનુવાદ કોડ્સ અને લિંક્સનું ભાષાંતર કરશે નહીં અને અનુવાદિત વાક્યોને કેશ કરશે. જો અનુવાદમાં ફેરફાર કરવામાં આવ્યો છે પરંતુ મૂળ લખાણમાં ફેરફાર કરવામાં આવ્યો નથી, તો તેને ફરીથી ચલાવવાથી અનુવાદના ફેરફાર પર ફરીથી લખાશે નહીં.

[@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

`yaml` જનરેટ કરેલી વેબસાઇટ્સનું ભાષાંતર કરવા માટેની ભાષા ફાઇલો.
