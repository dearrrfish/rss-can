# RSS Can / RSS 罐头

![](./assets/images/project.jpg)
*generated by stable diffusion*

[WIP] 📰 🥫 Got RSS CAN be better and simple.

## PLAN

- Support fetch remote website page as feeds
- Support fetch with CSR
- Support fetch with SSR
- Support dynamic fetch with rules or config
- Dockerize

## License

This project is licensed under the [MIT License](https://github.com/soulteary/RSS-Can/blob/main/LICENSE)

## Credits

- [@PuerkitoBio](https://github.com/PuerkitoBio), He implements a good DOM parsing tool library [/goquery](https://github.com/PuerkitoBio/goquery) for Go under the [BSD-3-Clause license](https://github.com/PuerkitoBio/goquery/blob/master/LICENSE). In the project, it is used as a CSR method to parse remote document data. Because there is no Release for the new version, the code base used by the project is [[#3b7929a](https://github.com/PuerkitoBio/goquery/commit/3b7929a0d759a20968ba605c56bc3027c30d3527)].

- CSS Selector Library: [andybalholm/cascadia](https://github.com/andybalholm/cascadia) [[#c6065e4](https://github.com/andybalholm/cascadia/commit/c6065e4618b7f538edf5ca0d6b5b2fd0fe129fdd)]
    - [BSD-2-Clause license](https://github.com/andybalholm/cascadia/blob/master/LICENSE)
- JavaScript Runtime With Golang: [https://github.com/rogchap/v8go](https://github.com/rogchap/v8go) [[v0.7.0](https://github.com/rogchap/v8go/releases/tag/v0.7.0)]
    - [BSD-3-Clause license](https://github.com/rogchap/v8go/blob/master/LICENSE)
