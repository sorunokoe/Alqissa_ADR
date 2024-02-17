# Dictionary API

## Investigations
- Elastic Search, non-relational db (?)
- Where to find words with translatons and How to add to our DB?
    - Script (?)
- Where to find sentences with translations and How to add to our DB?
    - Script (?)

## Database

- Word:
    - id
    - title
    - description
    - ru_translation
    - en_translation
    - example: [Sentence]
    - category

- Sentence:
    - id
    - content
    - ru_translation
    - en_translation
    - word: Word
    - category

- Category
    - id
    - title

## Endpoints

- POST addNewWord()
- UPDATE changeWord()
- DELETE removeWord()

- GET getWordBy(word)
- GET getRandomWord()
- GET getTranslationFor(word, language)
- GET getExamplesFor(word)
- GET getListBy(category)
