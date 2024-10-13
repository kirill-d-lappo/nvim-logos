# nvim-logos

Small collection of nvim logos and helper function to get any or random of them.

## Usage

```lua
local logos = require("nvim-logos")

-- retrieve random function to get logo text
local get_logo = logos.get_random_logo_func()

-- or
-- retrieve get-function of specific logo
local get_logo = logos.logo["pretty"]

-- get logo, table of string lines
local logo = get_logo()
```
