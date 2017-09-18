# fp-homework-templates

[![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/chsersh/fp-homework-templates/blob/master/LICENSE)

Template Haskell homework project for [FP ITMO course](https://github.com/jagajaga/FP-course-ITMO).

## Usage

You can clone this project directly or use stack templating engine:

`stack new fp-homework https://raw.githubusercontent.com/ChShersh/fp-homework-templates/master/fp-homework.hsfiles`

Before that, you have to define several parameters in `~/.stack/config.yaml`:

```yaml
templates:
  params:
    author-name: Put your name here
    author-email: your@email.com
    github-username: your_github
```