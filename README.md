# Locale

#### Instantiate Locale
- `new Locale(String language)`
- `new Locale(String language, String country)`
- `new Locale.Builder().setLanguage("en").setRegion("US").build();`

#### Set Default Locale
- `Locale.setDefault(localVar)`
  + `Locale.setDefault(Locale.FORMAT, localVar)`
  + `Locale.setDefault(Locale.DISPLAY, localVar)`

#### Standardized Language Code
ISO 639-1 (alpha-2) or ISO 639-2 (alpha-3) language code (2 or 3 digit). Seems like the 639-1 language code works better.
- [Browse or Search the ISO Language Codes](https://www.loc.gov/standards/iso639-2/php/langcodes-search.php)
- [Wikipedia](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)

#### Standardized Country Code
ISO 3166 alpha-2 country code OR 3 digit UN M.49 Area Code
- [Search Country Code](https://www.iso.org/obp/ui/#search)
- [UN Standard country or area codes for statistical use (M49)](https://unstats.un.org/unsd/methodology/m49/)
- [ISO 3166 Codes (Countries)](http://kirste.userpage.fu-berlin.de/diverse/doc/ISO_3166.html)
