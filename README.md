Earliz Translations
============

Translations of the Earliz software. Push your language!

## Work in progress

	* DE - German
	* PT - Portugese (Brazil)

## Key format

Localization files contain a PHP array "$t" of all translation keys. The basic format of a key is th
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
	########################################### TRANSLATE ALL AFTER THIS LINE ###########################################
	* Not translated key: // To translate
	* Not sure about a translation: // To check
	* Suggestion about possible improvement: // Check: ...
	* Current format of the key doesn't work with the language: // Dev require: ...