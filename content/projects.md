---
title: "Projects"
date: 2019-09-11T20:27:37-04:00
draft: false
---

So if you read my about me, you know I like to make things. A lot of things.
A lot of those things turn out to be dropped because I think it's not worth to continue it or maybe I had to prioritize something else and it just happened to get dropped. Regardless, here's where I'll be listing (or attempting to list) all my past projects and maybe what I learned from them.

I'll try to keep links updated but I tend to change hosting and servers quite often to get exposure doing things differently, so the source will be listed alongside the links.

## Gophoto [source][gophoto-source] [post][gophoto-blog]
A small image manipulation program writtin in Go. Allows you to take an image and essentially apply filters on top, changing the look of the image. Had to write my own KD-Tree implementation for a filter and ended up learning an intense amount. Also created a cool filter that I'm not aware of existing elsewhere that I called tablify.

## [Cubestory][cubestory-deploy] [source][cubestory-source]
After playing a cube called story cubes with my niece and nephew, I was inspired to bring it onto the online world. It's essentially a creativity game where you roll a die with images on it, and whatever you roll you come up with a sentence or so. Then the next person does the same as you end up with some imaginative story with mini prompts. Written in React/Redux frontend with a Node Express backend and SocketIO to weld them together.

## [Hanabite][hanabite-deploy] [source][hanabite-source]
After making Cubestory, I took some of the code for room management from there and went to work on Hanabi online. A multiplayer turn based collaborative card game written in Svelte frontend and Polka backend again with SocketIO to hold them together. Had fun working with Svelte for the first time and would definitely use it again in the future but I would like to read more about it and common practices before investing in another project with it.

## Nilm [source][nilm-source]
A failed hackaton project where I used Elixir (with Phoenix/Ecto) and Elm to try to recreate Reddit. Unfortunately, I was faced with several issues during the project which stopped my progress. Not knowing the languages contributed to that, but I was unable to get an environment setup so the two languages could communicate with each other. Definitely learned that I should fix communication issues in any project before starting a lot of work. I spent tons of time on a front-end, back-end mocking before even attempting to link them together.

## Crossword [source][crossword-source]
An attempt to copy the popular mobile game called Wordscapes where you're given some letters and have to fill in a crossword-style board by guessing words without clues. I went mainly to see how to simulate some kind of UI but I ran into display issues early on and spent an absurb amount of time thinking of strategies on how to fix. The basic idea is there but it needs a ton more polish before I would be happy deploying this.

# oo [source][oo-source]
Another attempt at copying a mobile game called oo (like infinity sign) where you rotate pipes to form closed loops. I had written something like this in Java years ago but lost the code and wanted to redo in JavaScript. The bare functionaly exists but I would like to make a solver and generate levels randomly. I believe this type of problem can be solved entirely with constraint propagation but I have yet to attempt the solver. Definitely something I will revisit!

# Minesweeper [source][minesweeper-source]
I had played minesweeper on Windows when I was younger and one day I suddenly wanted to attempt to recreate it. I went a bit overkill using React but it was more of just a fun thing. This wasn't to prove anything necessarily, just some practice with time-based Redux stores.

# Island Gen [source][island-gen-source]
One of my earlier JavaScript projects that I grabbed inspiration from another site. It generates cool looking islands with configurable parameters. There's no exporting (other than saving as a picture) but it was meant more as a quick show-and-tell site rather than something that would actually be used for generate islands.

[gophoto-source]: https://github.com/marvinody/gophoto/
[gophoto-blog]: https://blog.sadpanda.moe/posts/oct-18/gophoto/

[cubestory-deploy]: https://cubestory.herokuapp.com/
[cubestory-source]: https://github.com/marvinody/cubestory/

[hanabite-deploy]: https://hanabite.deploy.sadpanda.moe/
[hanabite-source]: https://github.com/marvinody/hanabite/

[nilm-source]: https://github.com/marvinody/nilm/

[crossword-source]: https://github.com/marvinody/crossword

[oo-source]: https://github.com/marvinody/oo/

[minesweeper-source]: https://github.com/marvinody/minesweeper-react/

[island-gen-source]: https://github.com/marvinody/island-gen/
