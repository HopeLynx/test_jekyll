# Israh Theme for Jekyll

Israh is a responsive Jekyll theme with a clean single column layout and not much else.

This theme is an evolution of my [Ezora jekyll theme](https://github.com/ezrasavard/ezora-jekyll-theme) that reflects my own changing tastes.
Most notably, Israh takes the focus off of header images so I don't have to find them for posts that don't need them.

### [Try Israh](http://www.ezrasavard.com/israhdemo)

Feel free to use this theme however you like (MIT License).

## Screenshots

### Desktop
![screenshot-desktop](https://github.com/ezrasavard/ezora-jekyll-theme/blob/master/screenshot.png)

### Mobile
![screenshot-mobile](https://github.com/ezrasavard/ezora-jekyll-theme/blob/master/screenshot-mobile.png)

## Installation

In order to semi-modularize themes, I think the cleanest way to use this is to set this repository as a submodule in your own blog repository,
and then use symlinks to point Jekyll to the correct folders within that directory.

[My blog repo](https://github.com/ezrasavard/blog) can serve as an example for this layout.

Some people may prefer to just fork this repository and add their own content, that's fine too =).

## Usage

Like Ezora, Israh uses a fairly minimal set of layouts and sass, and will automatically conform to a sensible layout based on the YAML provided, unless a layout is specified. Width/height values are all defined in the top of main.scss as variables, so you don't have to hunt too far through the SCSS to tweak things.

Notable _includes are the **topbar**, included in the default layout, the **navbar** and the **postlist**, which is a paginated pile of posts you can include in any page, like the default home page does. You can specify your navigation menu links in **navbar** if you don't like it generating them for all your pages, GitHub and LinkedIn accounts. You can also add more social accounts if you like by extending the list in navbar.html.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/ezrasavard/israh-jekyll-theme. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
