Earliz Translations
============

Translations of the Earliz software. Push your language!

## Work in progress

   * DE - German
   * PT - Portugese (Brazil)

## Key format

Localization files contain a PHP array "$t" of all translation keys. The basis format of a key is the format of a PHP array item.
```php
$t['home'] = "Home";
```

Some keys contain variables. They are numbered from 1 to 3 and will be replaced while page rendering on Earliz. Be sure to keep them in your translations.
```php
$t['commented_your_post'] = '{1} commented your {2}';
```

Some keys contain HTML tags. Be sure to keep them in your translations.
```php
$t['free_sign_up'] = "<strong>Free</strong> sign up";
```

Quotes or double-quotes must be escaped if they are in a key enclosed respectively in quotes and double-quotes
```php
$t['subject_group_invitation'] = "{1} invites you to join the project \"{2}\"";
$t['invite_sentence'] = 'You\'ve been invited to this project';
```

## Comment rules

When translating Earliz, you can add comments to inform other contributors about the advancement of you translation. We define some standard rules to explain it :

   * All following keys are not translated:
```php
########################################### TRANSLATE ALL AFTER THIS LINE ###########################################
```
   * Not translated key: _// To translate_
   * Not sure about a translation: _// To check_
   * Suggestion about possible improvement: _// Check: ..._
   * Current format of the key doesn't work with the language: _// Dev require: ..._

## Licence
(LGPL v2)

Earliz Translations is free software: you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published by
the Free Software Foundation, either version 2 of the License, or
(at your option) any later version.

Earliz Translations is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License along
with this Earliz Translations. If not, see <http://www.gnu.org/licenses/>.