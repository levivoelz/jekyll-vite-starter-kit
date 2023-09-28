# Jekyll Vite Starter Kit

This starter kit uses [Vite](https://vitejs.dev/) to bundle assets and [Jekyll](https://jekyllrb.com/) to generate static pages. It's a great combination for building fast and modern static websites. You can use vite to bundle React, Vue, Svelte, or vanilla JS/TS along with CSS.

Jekyll Plugins: [jekyll-vite](https://github.com/ElMassimo/jekyll-vite)

## Getting Started

### Prerequisites

- [tmux](https://github.com/tmux/tmux/wiki)
- [overmind](https://github.com/DarthSim/overmind)

### Installation

1. Clone the repo
    ```sh
    git clone https://github.com/levivoelz/jekyll-vite-starter-kit.git
    ```
2. Install dependencies
    ```sh
    # macOS
    brew install tmux
    brew install overmind
    bundle install
    npm install

    # Ubuntu
    sudo apt install tmux
    sudo apt install overmind
    bundle install
    npm install
    ```

## Usage

### Development

```sh
npm start
```

or if your prefered flavor is Ruby

```sh
bundle exec rake start
```

### Documentation

For additional info on how to work with jekyll-vite please review the [ jekyll-vite documentation](https://github.com/ElMassimo/jekyll-vite)

i18n is also supported, for more info on how to work with i18n please review the [jekyll-multiple-languages-plugin documentation](https://github.com/kurtsson/jekyll-multiple-languages-plugin)
