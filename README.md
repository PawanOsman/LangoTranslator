# Welcome to Lango Translator API

**Lango Translator** is a free Translation chat bot in Facebook Messenger, it provide a free translation api.

# How to use Lango Translator API?
Lango Translator api provide you both Google Translate and Microsoft Translator api 

you can use it by sending `HTTP GET` Request to endpoints below:

## Google Translate

| Query | Definition |
|--|--|
| from | The language of Text Query[ \[Language Codes\]](https://cloud.google.com/translate/docs/languages)|
| to | The Language you want to translate to [ \[Language Codes\]](https://cloud.google.com/translate/docs/languages)|
| text | The text or paragraph you want translate |


GET https://api.pawan.krd/gtranslate?from=en&to=ckb&text=hello

**Response**
You will get json response like this:

    {"status":true,"translated":"سڵاو","time":60}


## Microsoft Translator

| Query | Definition |
|--|--|
| from | The language of Text Query [ \[Language Codes\]](https://docs.microsoft.com/en-us/azure/cognitive-services/translator/language-support)|
| to | The Language you want to translate to [ \[Language Codes\]](https://docs.microsoft.com/en-us/azure/cognitive-services/translator/language-support)|
| text | The text or paragraph you want translate |


GET https://api.pawan.krd/mtranslate?from=en&to=ku&text=hello

**Response**
You will get json response like this:

    {"status":true,"translated":"سڵاو","time":60}


