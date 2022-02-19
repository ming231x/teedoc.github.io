---
title: teedoc update history
keywords: teedoc, markdown, jupyter notebook, html, 文档生成, 替代gitbook, 网站生成, 静态网站, 写文档, 更新历史
desc: teedoc's update history
---

## 2021-09-18 v1.23.1

* Add 404.html template, support i18n

## 2021-09-8 v1.19.0

* Add i18n support for plugins and templates
* Add comment plugin teedoc-plugin-comments-gitalk
* Add print page support
* Add anchor for titles
* Add warning log for wrong sidebar item
* Fix bug: not auto refresh page when content changed in previwe mode
* Fix search index file too large bug
* Fix navbar list item z-index error
* Fix toc smooth scroll bug when id is escaped charactors

## 2021-08-7 v1.17.1

* Add layout template customize support(Jinja2)

## 2021-08-3 v1.16.1

* Change markdown parser from markdown2 to mistune, now build faster at least 2x
* Ignore .git folder in file watcher

## 2021-07-22 v1.15.8


* Optimize file watcher, fix rename in file browser can't trigger event issue
* Fix error when copy error(not found error)

plugin theme_default: Add image viewer for img item


## 2021-05-21 v1.15.0

* Add summary2json and summary2yaml command for gitbook sidebar file
* Add sidebar splitter, you can set `sidebar_width`(default sidebar width) config for plugin  `teedoc-plugin-theme-default`, e.g.:
```
"teedoc-plugin-theme-default": {
            "from": "../../plugins/teedoc-plugin-theme-default",
            "config": {
                "env": {
                    "sidebar_width": "300px"
                }
            }
}
```


## 2021-05-21 v1.14.0

Speed up build by change multithread build to multiprocess build


## 2021-05-21 v1.13.0

Add `collapsed: false` option for sidebar directory to show sub directory by default

## 2021-04-14 v1.12.3

* fix sidebar active error
* optimize navbar list type display
* add navbar list type url support
* add --thread parameter, to set build thread number
* update markdown plugin to v1.0.8, warning when parse markdown error instead of program crash

## 2021-1-28 v1.0.1

Basic functions

## 2021-1-16

project started




