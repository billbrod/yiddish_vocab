# Yiddish vocab

Currently, this just contains a single txt file, which contains words to study
for Yiddish. These are formatted so Anki can import them: three fields,
separated by a semicolon, corresponding to the Yiddish word, the English
translation, and the YIVO-standard transliteration.

These words are those that I've added from YIVO's intensive beginner Yiddish III
and IV, which uses In Eynem, starting at chapter 7. I'll probably go back and
add some from last semester as well, but that's a work in progress.

No guarantees that there won't be typos or mistranslations! If you find any,
please [open an issue](https://github.com/billbrod/yiddish_vocab/issues).

I'm also using AnkiWeb to sync the cards, but this serves as an extra source, in
case I need them. 

## Conventions

- For verbs, I have listed the infinitive.
- For nouns, I include the article for the singular form and add the plural form
  (no article) in parentheses. For example, `דאָס קנעכל(ן)`: `knekhl` is the
  singular form, `knekhln` is the plural. When the plural form is completely
  separate (not just a suffix), there's a space between the two: `די קרובֿה
  (קרובֿות)`.
- Most notes are included with the transliteration, though disambiguation notes,
  such as `to lie (e.g., "the chair lies on the table")` may be included with
  the English or Yiddish, as appropriate.

## Anki

I use [Anki](https://apps.ankiweb.net/) for reviewing flashcards. The
`anki_words.txt` file is written so that it can be
[imported](https://docs.ankiweb.net/importing.html) by Anki into a deck with
three fields: Yiddish, English, and Transliteration. To simplify use of these
words with Anki, I'm also including `Yiddish.apkg`, which is a binary file
containing that deck which can be imported directly into Anki.

In either case, re-importing the file (either txt or apkg) after it changes will
update the existing deck in place. Sometimes if I modify existing lines in the
txt file (for example, fixing a typo), Anki imports the line as a new card
instead of modifying the old one, so I'd periodically check for duplicates using
the browse cards option in Anki.

### How to import

If you're unfamiliar with GitHub and similar, the following instructions should
hopefully help:

- Click on the `Yiddish.apkg` file in this repository:

![Click on Yiddish.apkg](assets/gh-1.png)

- Click on the download button in the top right to download the file to your computer:

![Download Yiddish.apkg](assets/gh-2.png)

- Open up Anki, then click on `File -> Import`:

![Open up the deck import](assets/anki-1.png)

- Click on the deck to import it.

![Import Yiddish.apkg](assets/anki-2.png)

- Hopefully that works! The [Anki docs](https://docs.ankiweb.net/importing.html)
  have more information.

- If you want to use Anki on multiple devices (e.g., computer and phone), you'll
  need to use [AnkiWeb](https://ankiweb.net/about) to sync between them. See the
  [Anki documentation](https://docs.ankiweb.net/syncing.html) for details.
