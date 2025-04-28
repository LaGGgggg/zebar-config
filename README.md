My config for the [Zebar](https://github.com/glzr-io/zebar)

Changes from the default [starter with-glazewm](https://github.com/glzr-io/zebar/tree/main/examples/starter):
- Visual
  - Reduced bar height (40px -> 30px)
  - Changed `zOrder`: `normal` -> `top_most`
  - Changed widgets order
- Fixes
  - Increased the [battery](https://github.com/glzr-io/zebar?tab=readme-ov-file#Battery) provider refresh interval (5 sec -> 60 sec)
- Feautres
  - Changed the [date](https://github.com/glzr-io/zebar?tab=readme-ov-file#Date) provider formatting (`EEE d MMM t` -> `T d MMM EEE`)
  - Removed Windows logo
  - Added information about [traffic usage](https://github.com/glzr-io/zebar?tab=readme-ov-file#networktraffic)
  - Added "unknown" placeholder for networks without ssids
