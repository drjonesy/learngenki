# Learn Genki Japanese Educational Repository

This is git contains files for development with the book series "GENKI: An Integrated Course in Elementary Japanese"
  - The database has been updated from MySQL to JSON. The current list of words is from the BOOK 1 only.
  - Additional projects will be added to this repository soon... like: Genki no Manga, Genki JpnEng Dictionary, Genki online review.


#### Database Structure (JSON)
The database is quite simple at the moment. Each word is a object made up of kana, kanji, romaji, english, and wordType. All words can be found in the object "words".

```
{
    "words": [
    {
        "kana": "アイスクリーム",
        "kanji": "",
        "romaji": "aisukuriimu",
        "english": "ice cream",
        "wordType": "noun"
    },
```
 