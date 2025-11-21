# XIANYU CRAWLER

[xianyu](http://goofish.com) is a greate second-hand trading platform. There are a lot of highly similar goods, so this tool helps you collect the them.

**But it also has many liars. So you need to identify them carefully.**

## New Feature

- Add the custom location support, such as province, city and district.


## Prerequisite

- `tk`: A GUI framework for dispalying the app.
- `uv`: A python management tool. Use `uv` to run the app.

For the linux user, use your package manager (example for archlinux):

``` fish
    sudo pacman -S tk uv # paru -S tk uv
```

For the windows user, download them on official website: [tk](https://www.tcl-lang.org/software/tcltk/), [uv](https://docs.astral.sh/uv/#highlights)

## Usage

```
    git clone https://github.com/iexpectation/xianyu-crawler
    cd xianyu-crawler

    uv run xianyu-crawler
```

## Acknowledagement

Thank [蜗牛很牛](https://www.52pojie.cn/thread-2048509-1-1.html) to provide the origin source.


## License

MIT

