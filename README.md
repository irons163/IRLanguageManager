# IRLanguageManager

- IRLanguageManager is a light language tool.

For localization strings, you can simple to use like: `_(@"STRING_KEY_IN_THE_LOCALIZATION_STRINGS")`

For set Language for user prefer:

```objc
[[IRLanguageManager sharedInstance] setLanguage:currentChangeLanguage];
if ([[IRLanguageManager sharedInstance] currentLanguage]) {
    currentShowLanguage = currentChangeLanguage;
}else{
    currentShowLanguage = _(@"LANGUAGE_AUTO");
}
```
