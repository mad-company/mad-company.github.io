---
layout: single
title:  "10 tools for an iOS developer"
date: 2020-11-04 13:15:20 +0200
categories: Tools
tags: indie_dev, tools
---


Here is a 10 iOS softwares list I use daily, weekly or monthly. Most of them are well known but maybe you’ll find a few one that you’ve never used ;)

I’ve chosen to group them in 3 categories : **Debug** (🛠), **Productivity** (📈) et **Keynote** (🎤).

# 🛠 Debug

## 1. [Sherlock](https://sherlock.inspiredcode.io) (🕵️‍♂️)

This is one of the tools that I use mostly during development process… Mainly because of two major features  :
- **Simulation** of different devices screen sizes while executing code only once
- **Inspection** of the view and constraint in real time

OK, it’s not cheap ($49) but it makes me gain lots of time on new feature I’m developing especially if it’s has to be *pixel perfect* on iPhone SE, Pro Max, 11, XR, etc…
It definitely worth it !


![Sherlock](https://s3.amazonaws.com/sherlock-website-assets/sherlock-hero.mp4)


## 2. [Reveal](https://revealapp.com) (👁)

In the same spirit as Sherlock, here is THE software to inspect your app under all details during development process… A little bit more expensive ($59) but more options and features provided, it allows you to :

- **Browse**  views hierarchies more efficiently than Xcode builtin tool
- **Inspect** your *Gesture Recognizers*
- **Analyse** constraints
- **Edit** views in real time
- Also working with **App Extensions**

![reveal](/assets/images/articles/ios_tools/reveal.jpg)


## 3. [Kaleidoscope](https://www.kaleidoscopeapp.com) (👮‍♀️)

This is the file comparaison specialist. This soft was initialement developed by Blackpixel, and allows you to compare :

- text files
- directories
- images

For my part, it mainly helps me in **Git merge conflicts** (especially in this #@&ç§(&@ `project.pbxproj` file). Luckily, Kaleidoscope ($70) perfectly fit in with my Git. client [Sourcetree](https://www.sourcetreeapp.com).

![kaleidoscope](/assets/images/articles/ios_tools/kaleidoscope.png)


## 4. [Charles proxy](https://www.charlesproxy.com/documentation/ios/) (🔎)

Charles is one of the best friend of my collegues from Q&A team. This soft helps them to validate datas entering the app from different webservices. Briefly, this is :

- a HTTP proxy
- a reverse proxy to sniff all http(s) traffic (request, headers HTTP, responses, etc...)

This app cost $50 on Mac and an iOS client is also available for $10.

![charles](/assets/images/articles/ios_tools/charles.jpg)

Remarque: [une appli iOS](https://itunes.apple.com/fr/app/charles-proxy/id1134218562?mt=8), moins cher (9$) permet de sniffer rapidement et extrêment facilement les flux. *"La recette"* et moi, on est fan !

![charlesios-1](/assets/images/articles/ios_tools/charlesios-1.jpg)

## 5. [Postman](https://www.getpostman.com/downloads/) (📬)

Ce soft permet de gérer vos APIs tout au long de leur cycle de développement :

- développer / debugger
- tester / mocker / monitorer
- partager vos collections
- documenter

Très puissant, il y a plusieurs prix, de gratuit pour les fonctions de base à 18$ / mois.

![postman](/assets/images/articles/ios_tools/postman.png)


# 📈 Productivité

## 6. [Pastebot](https://tapbots.com/pastebot/) (😎)


Voici le **king of copier/coller** !

Que ce soit pour refactoriser du code, écrire un article, un email ou même un simple message Slack, le copier/coller est une indispensable fonctionnalité... 

Mais si vous saviez ce qu'un petit logiciel comme Pastebot pouvait vous apporter, vous l'adopterier sans tarder... On parle de copier de multiples extraits de textes d'une part puis de coller ceux que vous voulez où vous voulez, d'y ajouter des filtres, de formater avant de coller votre texte, etc... Son prix ? 13$

<iframe width="560" height="315" src="https://www.youtube.com/embed/qpEeZ2yaB-k" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## 7. [Alfred](https://www.alfredapp.com) (⚙️)

Vous utilisez Spotlight sous macOS ? Alfred est en quelque sorte son père, enfin disons plutôt son mentor, celui qui lui a tout appris... il est plus complet et plus puissant. 
Personnellement, je n'utilise que lui. Il me permet de :
- **lancer** mes applis
- **rechercher** mes fichiers en local ou quoique ce soit sur le net
- controller ma **musique**
- il fait office de **calculette**

Mais surtout, il me donne la possiblité __d'ajouter des *"workflows"*__ que j'utilise pour __traduire rapidement des textes, ouvrir des sites directement__ où je veux (par exemple la commande PR m'ouvre directement le repo Github, à l'onglet *Pull Request*), **compresser** des images, interagir avec Slack, *switcher* entre wifi et ethernet, **éteindre** ma machine, etc...
La version de base est gratuite et l'extension ajoutant plus de fonctionnalités coûte 23£.

![Alfred](/assets/images/articles/ios_tools/2018-02-23-1.gif)


# 🎤 Présentations

## 8. [Deckset](https://www.deckset.com) (🎥)

Si vous ne connaissez pas ce soft, il s'agit d'un grand classique pour un développeur d'aujourd'hui. Un *must-have* à 29€. 
Il vous sera utile dans la réalisation de vos présentations écrites en **Markdown**, avec la coloration syntaxique du code, les photos, videos, etc...
Deckset vous offrira de nombreux thèmes différents (les goûts et les couleurs, tout ça...) et vous pourrez également les personnaliser à votre guise.

(Remarque: soft initialement développé par Chris Eidhof)

![deckset-adding-images](/assets/images/articles/ios_tools/deckset-adding-images.jpg)

## 9. [Snippetty](http://snippetty.io) (👨‍💻)

This app is for **live coding** adepts. To be brief, you add code pieces (aka *snippets*) in a markdown file and then, step by step during your live session/demo you can very quickly and very easily copy/paste your lines of code.

<iframe src="https://player.vimeo.com/video/250245095" width="640" height="360" frameborder="0" allowfullscreen></iframe>


## 10. [MacDown](https://macdown.uranusjr.com) (📝)

This is my Markdown editor to write articles, keynote (before finishing them on Deckset) and other markdown documents. Easy to use, convenient, opensource and aesthetic, this editor is totally free.

![macDown](/assets/images/articles/ios_tools/macDown.png)

---

# To conclude 

So here was a 10 apps list that facilitate my daily work as an iOS developer. These tools took lots of time to lots of developers as you and me to be developed. So they have a price, most of them are not free. Ideally,  make their price supported by the one you work for. They will make you gain a precious time, you’ll be more efficient at work for the company that hired you…

👉 Work less to work better 👈

