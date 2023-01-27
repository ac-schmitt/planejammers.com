# planejammers.com

This is the single repo for the [planejammers.com](https://planejammers.com) website based on [Hugo](https://gohugo.io/).

Please use `git clone --recurse-submodules` to clone the repository to include the template.

## Template

planejammers.com is based on the [Eureka Theme](https://github.com/wangchucheng/hugo-eureka) and uses it as a git submodule. Additionally it uses [hugo-notice](https://github.com/martignoni/hugo-notice) for admonition support.

Customizations:
* Custom Style to disable google fonts in [planejammers.yaml](data/styles/planejammers.yaml)

## License

The code, configuration files and structures in this repository are licensed under [MIT License](LICENSE).

Acknowledgment to the upstream projects:
* [Eureka Theme](https://github.com/wangchucheng/hugo-eureka)
* [hugo-notice](https://github.com/martignoni/hugo-notice)

The content of the articles in the [content folder](content/) that are published on the planejammers.com website is licensed unter [Creative Commons CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).

## Mechanics

### Images

Most Images are stored and fetched from imgur.com. Images in the repo are mainly the site icons or part of a stand-alone functionality, like for the homepage backgrounds.

All external images which are remixes of original work are smaller than 125 kilobyte in compliance with european and german law. Remixing usually means cropping, adding transparancy or changing the color scheme to match with the site color scheme.

Image dimensions are usually resized and cropped to 960 pixel maximum width or 720 pixel width to fit into the site style. Smaller sizes follow the default width values: 480, 360 or 240 pixel width.
