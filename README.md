# yatline-rose-pine.yazi

Rose Pine for Yatline

## Requirements

- [yazi](https://github.com/sxyazi/yazi) version >= 0.3.0
- [yatline.yazi](https://github.com/imsi32/yatline.yazi)

## Installation

```sh
ya pack -a wekauwau/yatline-rose-pine
```

## Usage

> [!IMPORTANT]
> Add this to your `~/.config/yazi/init.lua` before Yatline's initialization.

```lua
local rose_pine_theme = require("yatline-rose-pine"):setup("dawn")
```

Then use the `theme` variable in Yatline config's theme parameter.

```lua
require("yatline"):setup({
-- ===

	theme = rose_pine_theme,

-- ===
})
```

## Credits

- [yatline-catppuccin.yazi](https://github.com/imsi32/yatline-catppuccin.yazi)
