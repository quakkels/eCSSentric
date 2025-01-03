# eCSSentric

The anti-dependency "dependency."

[eCSSentric](https://ecssentric.quakkels.com) is not intended to be treated as a library or framework. It is a 
launching point for your CSS. It's a skeleton of styles designed to provide a 
simple start that acts as a springboard. 

Basic decisions have already been made, though anything can be revisited. 
eCSSentric is closer to a reference resource than it is to a library or 
framework. It may help to consider every eCSSentric instance as a fork of the 
original project. Once forked, it's yours, build it up and modify it according 
to your own app's unique needs.


## Getting Started

1. Download [eCSSentric.css](ecssentric.css) and save it to your styles folder.
2. Include the style in your html header with `<link rel="stylesheet" href="/{your styles directory}/ecssentric.css">`
3. Use [index.html](index.html) as a reference for how the different design elements are used.

## Features

- No build step
- No JavaScript dependencies
- Cards
- Columnar Grid
- Forms
- Buttons
- Message Blocks

## Configuration

### Variable Naming Conventions

eCSSentric's philosophy for variable naming has two parts: 

1. Start with specifics for the smallest piece, then get more descriptive by 
appending the next biggest context.
2. No bike-shedding names

For example, if you want a variable for the color, use `--color`. If it's 
for a border, then use `--color-border`. Then, suppose you need the color of a 
border for a form input, look for `--color-border-input`. Then, suppose you 
need the color of a border for an input element that is in an error state, 
look for `--color-border-input-error`.

### Variables

eCSSentric uses `rem` size values. Given the default values in 
[ecssentric.reset.css](), `1.6rem` will be equivalent to `16px`.


## Todo

- [x] grid/masonry styles and demo (multi column example)
- [x] flex styles supporting multi 'columns'
- [x] mobile styles using media queries and/or contaienr queries
- [x] error message block style
- [x] error message list style
- [x] table style
- [x] scrollbar style
- [x] dynamic call-to-action button styles and demo
- [ ] refine configuration variable names for clarity
- [ ] document configuration values

