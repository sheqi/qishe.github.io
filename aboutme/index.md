---
layout: page
title: About me
subtitle: Brief Introduction
---

### **About me**

Qi She was born in Yangzhou (扬州), Jiangsu (江苏) province. He is now working as a Research Scientist at [Bytedance](https://www.bytedance.com/zh/), focusing on landing advanced machine learning, computer vision techniques in Bytedance AI products, e.g., developing ads ranking model&system, computer vision solutions in Douyin & TikTok. He used to be a Research Scientist at [Intel Labs](https://www.intel.com/content/www/us/en/research/overview.html) from 2018 to 2020, studying statistical machine learning, deep learning with applications in computer vision, and robotics.

### **Education**

He obtained Ph.D. in machine learning and neural computation from the Department of Electronic Engineering (now Electrical Engineering) at the [**City University of Hong Kong**](https://www.ee.cityu.edu.hk/) where he was advised by [Prof. Rosa H.M. Chan](https://cityucompuneurolab.github.io/rosa.html). During this period, He won the 2nd place in the 10th Global Artificial Intelligence Hackathon funded by IBM Watson research. He is also closely collaborated with [Prof. Guanrong Chen](https://scholar.google.com/citations?user=O_Eif1YAAAAJ&hl=zh-CN) and [Prof. James Kwok](https://scholar.google.com/citations?user=-oTraZ4AAAAJ&hl=zh-CN), in complex networks and machine learning respectively. He used to be a fully-funded Visiting Student Research Collaborator (VSRC) at [**Princeton University**](https://www.princeton.edu/), advised by [Prof. Jonathan Pillow](https://pillowlab.princeton.edu/people.html), studying latent subspace discovery from high-dimensional neural responses.

<!--Before directly pursuing my Ph.D., he completed B.Eng. within 1% (2/230) in Information Engineering from NUPT, and his bachelor final year project ranked #1 out of 230. Previously, his research focused on statistical machine learning methods to extract hidden structure from high-dimensional neural data, infer brain connectivity using fully & empirical Bayes, and complex network study on multiple brain regions. Studying how information is encoded, decoded, and processed in our brains is one of his interests. Currently, he is developing a lifelong/continual adaptation agent that can shape a cultivated understanding of the world from the current scene and their previous knowledge via an autonomous lifelong development. The ongoing project is listed in "Lifelong Robotic Vision" project page.-->
### **Research**

Qi has more than **40** peer-reviewed publications, including **ICML, UAI, CVPR, ICCV, ICLR, AAAI, ICRA, BMVC, Artificial intelligence, TSP, CSUR** etc. He was the organizer of IROS 2019 Lifelong Robotic Vision Challenge and the organizer of the CVPR 2020 & 2021 Continual Learning in Computer Vision Workshop, also works as the PC member of ICONIP 2019 and serves as a reviewer for prestigious conferences and journals including NeurIPS, ICML, ICLR, CVPR, AAAI, IJCAI, ICONIP, TSP, CSUR, EJN etc. He holds 5 granted/filed US patents, and 20 China patents. The work is more related to developing a continual learning framework/toolkit benefiting quickly prototyping the continual/few-shot/meta-learning applications.

Specifically, his research interests include topics as:

**Statistical Machine Learning**

- Qi was fascinated by Bayesian theory and used this tool for extracting hidden structure from high-dimensional neural data, inferring brain connectivity. Studying how information is encoded, decoded, and processed in the brain is one of his interests.


**Dynamical Systems & RNNs**

- He was also interested in modeling time series, starting from dynamical systems to deep RNNs. This includes altering the optimizer and adding several regularizers to structure the hidden states and dependences of the dynamic/recurrent models.

**Complex Network & Graph Neural Networks**

- Adding meaningful structure to neural networks is definitely an important future direction that we need to understand. He has looked at the impact of graph structured neural networks or how to apply neural models to graph structured data.


**Theory for Representation Learning**

- He is interested in understanding how neural networks work via utilizing deep generative models, such as VAE, GAN, and normalizing flow models.


**Advanced Learning Method**

- Continual Learning, Transfer Learning, Multi-task learning, Meta-learning, Curriculum Learning and Self-paced Learning -- With the explicit goal of improving data efficiency, he has been working on multiple problems formulated around training with multiple tasks or efficient sampling.

<!--
# plainwhite

Simplistic jekyll portfolio-style theme for writers.

**Demo**: [samarsault.com](https://samarsault.com)

![plainwhite theme preview](/screenshot.png)

## Installation on Github Pages

Add this line to your site's `_config.yml`:

```yaml
remote_theme: samarsault/plainwhite-jekyll
```

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "plainwhite"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: plainwhite
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install plainwhite

## Usage

The "plainwhite" key in \_config.yml is used to customize the theme data.

```yaml
plainwhite:
  name: Adam Denisov
  tagline: Developer. Designer
  date_format: "%b %-d, %Y"

  social_links:
    twitter: samarsault
    github: samarsault
    linkedIn: in/samarsault # format: locale/username
```

**Updating Placeholder Image**

The placeholder portfolio image can be replaced by the desired image by placing it as `assets/portfolio.png` in your jekyll website, or by changing the following line in `_config.yaml`

```yaml
plainwhite:
  portfolio_image:  "assets/portfolio.png" # the path from the base directory of the site to the image to display (no / at the start)
```

To use a different image for dark mode, e.g. with different colors that work better in dark mode, add a `portfolio_image_dark` entry in addition to the `portfolio_image`.

```yaml
plainwhite:
  portfolio_image:      "assets/portfolio.png"
  portfolio_image_dark: "assets/portfolio_dark.png"
```

**Comments (Disqus)**

Comments on posts can be enabled by specifying your disqus_shortname under plainwhite in `_config.yml`. For example,

```yaml
plainwhite:
  disqus_shortname: games
```

**Google Analytics**

It can be enabled by specifying your analytics id under plainwhite in `_config.yml`

```yaml
plainwhite:
  analytics_id: "< YOUR ID >"
```

**Sitemap**

It can be toggled by the following line to under plainwhite in `_config.yml`

```yaml
plainwhite:
  sitemap: true
```

**Excerpts**

Excerpts can be enabled by adding the following line to your `_config.yml`

```yaml
show_excerpts: true
```

**Layouts**

- Home
- Page
- Post

**Navigation**

Navigation can be enabled by adding the following line to your `_config.yml`

```yaml
plainwhite:
  navigation:
    - title: My Work
      url: "/my-work"
    - title: Resume
      url: "/resume"
```

**Mobile**

By default, Plainwhite places the sidebar (logo, name, tagline etc.) above the content on mobile (narrow screens).
To condense it (moving some things to the bottom of the page and making the rest smaller) so it takes up less space, add the following to your `_config.yml`:

```yaml
plainwhite:
  condensed_mobile:
    - home
    - post
    - page
```

This chooses which layouts (types of page) should be condensed on mobile screens. E.g. if you want everything but the landing page to be condensed, remove `home` from the list. This option does not affect rendering on wider screens.

**Dark mode**

Dark mode can be enabled by setting the `dark_mode` flag in your `_config.yml`

The website will check the OS preferred color scheme and set the theme accordingly, the preference will then be saved in a cookie

```yaml
plainwhite:
  dark_mode: true
```

![plainwhite dark theme previe](/dark.png)

**Multiline tagline**

Tagline can be multiline in this way

```yaml
plainwhite:
  tagline: |
  First Line. 

  Second Line. 

  Third Line.
```

**Search-bar**

Search-bar can be enabled by adding the following line to `config.yml`

```yaml
plainwhite:
  search: true
```

Search is powered by [Simple-Jekyll-Search](https://github.com/christian-fei/Simple-Jekyll-Search) Jekyll plugin. A `search.json` containing post meta and contents will be generated in site root folder. Plugin JavaScript will then match for posts based on user input. More info and `search.json` customization documentation can be found in plugin repository.

**Base URL**

You can specify a custom base URL (eg. example.com/blog/) by adding the following line to `_config.yaml`. Note that there is no trailing slash on the URL.

```yaml
baseurl: "/blog"
```

**Language**

You can set the `lang` attribute of the `<html>` tag on your pages by changing the following line in `_config.yml`:

```yaml
plainwhite:
  html_lang: "en"
```

[See here for a full list of available language codes](https://www.w3schools.com/tags/ref_country_codes.asp)

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/samarsault/plainwhite-jekyll. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `plainwhite.gemspec` accordingly.

## Donation
If this project help you reduce time to develop, you can give me a cup of coffee :) 

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://paypal.me/thelehhman)

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## More themes

- [Texture](https://github.com/samarsault/texture)
-->
