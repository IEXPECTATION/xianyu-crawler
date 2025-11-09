# XIANYU CRAWLER

[xianyu](http://goofish.com) is a greate second-hand trading website. There are a lot of high equality goods. But it also have many liars. So we need to recognize the it carefully.

## New Feature

- Add the custom location support, such as province, city and district.


## Prerequisite

- `tk`: A GUI framework for dispalying the app.
- `uv`: A python management tool. Use `uv` to run the app.

For the linux user, use your package manager (example for archlinux):

``` fish
    sudo pacman -S tk uv # paru -S tk uv
```

For the windows user, download them on official websize: [tk](https://www.tcl-lang.org/software/tcltk/), [uv](https://docs.astral.sh/uv/#highlights)

## Usage

```
    git clone https://github.com/iexpectation/xianyu-crawler
    cd xianyu

    uv run xianyu-crawler
```

## Acknowledagement

Thanks for the [蜗牛很牛](https://www.52pojie.cn/thread-2048509-1-1.html) provides the origin source.


## License

MIT

