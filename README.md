# Raajje Adlist

## Overview
Raajje Adlist is a curated adblock filter list specifically designed to block intrusive and annoying ads on Maldivian (Raajje) websites. The list focuses on providing users a cleaner, faster, and safer browsing experience by blocking pop-ups, large banners, autoplay ads, and other intrusive elements typically found on local websites.

This project aims to improve the user experience on Maldivian websites by enhancing page load speeds, reducing data consumption, and removing visual clutter. The list complements existing adblock filters.

> **Requires uBlock Origin or AdGuard.** The list uses procedural cosmetic filters (`:has`, `:has-text`, `:upward`, `:style`) that Adblock Plus does not support. Adblock Plus will silently discard those rules.

## Features
- **Blocks intrusive ads**: Blocks large banners, pop-ups, and other intrusive elements on various Maldivian websites.
- **Optimized for Maldivian (Raajje) websites**: Specially crafted for websites like Sun.mv, Mihaaru.com, Vaguthu.mv, and many more.
- **Improves page load speeds**: Reduces bandwidth usage and speeds up page loading times by blocking multimedia ads.
- **Easy to integrate**: Works with uBlock Origin and AdGuard.

## How to Use
Follow the steps below to add the Raajje Adlist to your adblocker:

### For uBlock Origin
1. **Open uBlock Origin Dashboard**: Click the uBlock Origin icon in your browser and open the dashboard.
2. **Go to "Filter lists"**: Navigate to the "Filter lists" tab.
3. **Add the Raajje Adlist URL**:
   - Scroll down to the "Custom" section and click on the "Import..." button.
   - Enter the following URL: [Raajje Adlist](https://raw.githubusercontent.com/Mohamed-Iyas/Raajje-AdList/master/filter.txt).
   - Click "Apply changes" to activate the list.
4. **Refresh the page**: For the changes to take effect, refresh any open Maldivian websites.

### For AdGuard
1. **Open AdGuard Settings**: Open AdGuard and go to "Settings."
2. **Go to "Filters"**: Navigate to Filters → Custom.
3. **Add a custom filter**:
   - Click "Add filter" and paste the following URL: [Raajje Adlist](https://raw.githubusercontent.com/Mohamed-Iyas/Raajje-AdList/master/filter.txt).
   - Click "Next", then "Subscribe", and refresh the page for the changes to take effect.

## Validating changes
The list is checked with [AGLint](https://github.com/AdguardTeam/AGLint) using the config in `.aglintrc.yaml`:

```bash
npx @adguard/aglint filter.txt
```

## Websites Supported
Raajje Adlist covers a wide range of Maldivian websites, including:
- Sun.mv
- Mihaaru.com
- Vaguthu.mv
- Vnews.mv
- CNM.mv
- Avas.mv
- And many more...

The list is regularly updated to cover new websites and ad elements as they emerge.

## Contributing
Raajje Adlist is a community-driven project. If you come across any ads that are not blocked or have suggestions for improvement, feel free to contribute. Here's how you can help:
1. **Report issues**: Open a new issue on this repository if you find any ads that bypass the current filters.
2. **Submit a pull request**: If you have experience with filter lists, fork the repository and submit a pull request with your improvements.
3. **Suggest new websites**: If you know other Maldivian websites that have intrusive ads, let us know by opening an issue.

Together, we can make the Maldivian browsing experience smoother, faster, and more enjoyable.

## License
Raajje Adlist is licensed under the [Creative Commons BY-NC 4.0 License](https://creativecommons.org/licenses/by-nc/4.0/). You are free to use and adapt the list as long as it's for non-commercial purposes.

## Additional Information
- **Homepage**: [Raajje Adlist on GitHub](https://github.com/Mohamed-Iyas/Raajje-AdList)
- **Direct Download**: [Download the filter list](https://raw.githubusercontent.com/Mohamed-Iyas/Raajje-AdList/master/filter.txt)
- **Update Frequency**: The list is updated every 7 days to keep up with the latest ad patterns on Maldivian websites.

If you have any questions or need assistance, feel free to open an issue on this repository. Happy browsing!
