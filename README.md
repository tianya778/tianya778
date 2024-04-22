### Hi there 👋

# 博客文章
<!-- BLOG-POST-LIST:START -->
- [《软技能——代码之外的生存指南》不完全阅读笔记](https://blog.awumiao.org/1030/)
- [工作和兴趣？](https://blog.awumiao.org/1016/)
- [Hey , 涯。](https://blog.awumiao.org/988/)
- [找点事干](https://blog.awumiao.org/975/)
- [试着放过自己](https://blog.awumiao.org/962/)
<!-- BLOG-POST-LIST:END -->

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ tianya778 }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
