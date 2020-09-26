# Google Analytics Beacon

```markdown
![Analytics](https://<appengine-url>/UA-XXXXX-X/{ref-url-for analytics})
```

## Variants

Can be customized using `color` query.

| Variant    | Query           | Example
| ---------- | --------------- | ---------
| Blue       | `?color=blue`   | ![blue][]
| Green      | `?color=green`  | ![green][]
| Orange     | `?color=orange` | ![orange][]
| Pink       | `?color=pink`   | ![pink][]
| Red        | `?color=red`    | ![red][]
| Yellow        | `?color=yellow`    | ![yellow][]
| default             | none            | ![default][]

## Changes

- Updated badges to use SVG instead of gif
- More color options
- Support go1.12+, use logrus

[blue]: ./static/badges/blue.svg
[green]: ./static/badges/green.svg
[orange]: ./static/badges/orange.svg
[pink]: ./static/badges/pink.svg
[red]: ./static/badges/red.svg
[yellow]: ./static/badges/yellow.svg
[default]: ./static/badges/default.svg

![Analytics](https://ga-beacon.prasadt.com/UA-101760811-3/github/ga-beacon?color=green)
