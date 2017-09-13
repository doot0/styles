# stylekit

## What?
It's a configurable collection of SCSS utils for webpack + vue projects. Might work for other webpack projects that use `scss-loader`. Never checked tho lol

## I want it
- Clone the repo into your project's styles folder
- Configure your stuff in the `/config/_vars.scss` file
- `@import ./styles/_globals.scss` in a vue component when you need to use the styles

## How do I do the thing
- Set up a webpack alias for your styles folder so you can do cool stuff like this - `@import '~@styles/_globals.scss'`
- Don't include base styles in child vue components: import them in your root component (usually `App.vue`) instead

## It's broken/I'm scared
- don't at me
- lol j/k shout at me on twitter [@doot0](https://twitter.com/doot0)

## I want to make this suck less
- thanks! feel free to submit any PRs 