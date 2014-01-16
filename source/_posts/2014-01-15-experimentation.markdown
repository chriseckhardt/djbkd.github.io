---
layout: post
title: "experimentation"
date: 2014-01-15 22:42:58 -0700
comments: true
categories:
  - Ruby
---

Where I avoid using 'hello world'
---------------------------------
Test test test, is this thing on?

I do enjoy the Markdown language.

*I enjoy Clojure, too!*

```clojure example of Misaki static site generator in Clojure
;; Define template options here
; @layout  default
; @title   home

(defn page-header [[fs & rs]]
  [:div {:class "page-header"}
   [:h1 [:span fs] rs]])

(header
  (:title site))
(h2 "The personal blog of Chris Eckhardt.")
(p "These ideas and statements are his
     and not a reflection of his employer.")
;; Posts
(page-header "Entries")
(post-list)
(prev-next-page-link)

;; Sample post tags
(page-header "Tags")
(tag-list)
```

But, I actually type less with Markdown.

So I'll use OctoPress for now
-----------------------------
But I seriously need to fix this default theme business.
