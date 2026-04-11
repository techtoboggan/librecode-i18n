# LibreCode Internationalization

Community-maintained translations for [LibreCode](https://github.com/techtoboggan/librecode).

## Structure

```
src/
  app/     App-level strings (dialogs, settings, commands)
  ui/      UI component strings (session review, tooltips, prompts)
```

Each locale is a `.ts` file exporting `dict` — a flat `Record<string, string>` of translation keys.

## Contributing a Translation

1. Copy `src/app/en.ts` → `src/app/<lang>.ts`
2. Copy `src/ui/en.ts` → `src/ui/<lang>.ts`
3. Translate all values (keys stay the same)
4. Submit a PR

English (`en.ts`) is the reference locale. All other locales should have the same keys.

## Adding New Keys

Add keys to `src/app/en.ts` or `src/ui/en.ts` first, then update other locales.

## License

MIT
