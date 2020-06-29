This script downloads the rain radar from the Dutch website [buienradar.nl](buienradar.nl) and shows it in the image viewer [sxiv](https://github.com/muennich/sxiv).

## Dependencies
- sxiv
- imagemagick
- wget

## Usage

You can get the 1-, 3- and 24-hour forecast with:

```
buienradar n
```

, where n is the number of hours. Without an argument, you will get the 1-hour forecast. Make sure to put the script somewhere in your PATH.
