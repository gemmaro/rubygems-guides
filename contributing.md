---
layout: default
title: Contributing to RubyGems
url: /contributing
previous: /resources
next: /faqs
---

<em class="t-gray">How you can help make RubyGems and the surrounding ecosystem better.</em>

Looking to contribute to a RubyGems project? You've come to the right place!
There are many development efforts going on right now, and they could use
your help. Just follow the links below to get started contributing or to contact the
project maintainers.

* [Core Projects](#core-projects)
* [Ecosystem Projects](#ecosystem-projects)
* [Add Your Own Idea](#add-your-own-idea)

Core Projects
-------------

These projects are under the wing of the core [RubyGems team](https://github.com/rubygems/).

<a class="project__name is-first" href="https://github.com/rubygems/rubygems">RubyGems</a>

Ruby's premier packaging system. Bundled with Ruby 1.9+ and available for Ruby 1.8. Any time you run
`gem` at the command line, you're using this project.

<div class="project__links">
  <a class="project__link t-link" href="https://github.com/rubygems/rubygems/issues">Issues</a>
  <a class="project__link t-link" href="https://groups.google.com/forum/#!forum/rubygems-developers">Mailing List</a>
</div>

<p class="avatars">
  <a href="https://github.com/drbrain">
    <img src="https://secure.gravatar.com/avatar/58479f76374a3ba3c69b9804163f39f4?s=32" title="Eric Hodel">
  </a>
  <a href="https://github.com/evanphx">
    <img src="https://secure.gravatar.com/avatar/540cb3b3712ffe045113cb03bab616a2?s=32" title="Evan Phoenix">
  </a>
  <a href="https://github.com/tenderlove">
    <img src="https://secure.gravatar.com/avatar/f29327647a9cff5c69618bae420792ea?s=32" title="Aaron Patterson">
  </a>
  <a href="https://github.com/luislavena">
    <img src="https://secure.gravatar.com/avatar/e7cff3cfd41c495e1012227d7dc24202?s=32" title="Luis Lavena">
  </a>
  <a href="https://github.com/indirect">
    <img src="https://secure.gravatar.com/avatar/4c3ed917e59156a36212d48155831482?s=32" title="André Arko">
  </a>
  <a href="https://github.com/segiddins">
    <img src="https://secure.gravatar.com/avatar/4d6be90af74894fd132fb06dacec04d7?s=32" title="Samuel Giddins">
  </a>
  <a href="https://github.com/hsbt">
    <img src="https://secure.gravatar.com/avatar/f2748d34b03ed11330f2a2218904eb2d?s=32" title="Hiroshi SHIBATA">
  </a>
</p>

<em class="t-gray t-uppercase">Alumni:</em>

<p class="avatars">
  <a href="https://github.com/zenspider">
    <img src="https://secure.gravatar.com/avatar/16c4b19d8670085a428787f8b2438223?s=32" title="Ryan Davis">
  </a>
  <a href="https://github.com/jbarnette">
    <img src="https://secure.gravatar.com/avatar/c237cf537a06b60921c97804679e3b15?s=32" title="John Barnette">
  </a>
</p>

<em class="t-gray t-uppercase">Code Guidelines:</em>

* New features should be coupled with tests.
* Ensure that your code blends well with ours (eg, no trailing whitespace, match indentation and coding style).
* Don’t modify the history file or version number.
* If you have any questions, just ask us on [Bundler.io Slack][slack] or file [an issue][1].

[slack]: https://slack.bundler.io/
[1]: https://github.com/rubygems/rubygems/issues

<a class="project__name" href="https://github.com/rubygems/rubygems/blob/master/bundler/README.md">Bundler</a>

Bundler manages an application's dependencies through its entire life across
many machines systematically and repeatably.

<div class="project__links">
  <a class="project__link t-link" href="https://bundler.io/">Site</a>
  <a class="project__link t-link" href="https://github.com/rubygems/rubygems/labels/Bundler">Issues</a>
  <a class="project__link t-link" href="https://groups.google.com/forum/#!forum/ruby-bundler">Mailing List</a>
  <a class="project__link t-link" href="https://bundler.slack.com/archives/C08V1RPAP">Slack channel</a>
</div>

<p class="avatars">
  <a href="https://github.com/indirect">
    <img src="https://secure.gravatar.com/avatar/fb389f1e8b98d5d03be29e9dd309b3be?s=32" title="Andre Arko">
  </a>
  <a href="https://github.com/hone">
    <img src="https://secure.gravatar.com/avatar/efb7c66871043330ce1310a9bdd0aaf6?s=32" title="Terence Lee">
  </a>
  <a href="https://github.com/wycats">
    <img src="https://secure.gravatar.com/avatar/428167a3ec72235ba971162924492609?s=32" title="Yehuda Katz">
  </a>
  <a href="https://github.com/carllerche">
    <img src="https://secure.gravatar.com/avatar/da5274b27cc6c0f505495bf5d504575d?s=32" title="Carl Lerche">
  </a>
  <a href="https://github.com/segiddins">
    <img src="https://secure.gravatar.com/avatar/4d6be90af74894fd132fb06dacec04d7?s=32" title="Samuel Giddins">
  </a>
  <a href="https://github.com/hsbt">
    <img src="https://secure.gravatar.com/avatar/f2748d34b03ed11330f2a2218904eb2d?s=32" title="Hiroshi SHIBATA">
  </a>
</p>

<a class="project__name" href="https://github.com/rubygems/rubygems.org">RubyGems.org</a>

The Ruby community's gem hosting service. Provides a better API for accessing,
deploying, and managing gems along with clear and accessible project pages.

<div class="project__links">
  <a class="project__link t-link" href="https://rubygems.org">Site</a>
  <a class="project__link t-link" href="https://github.com/rubygems/rubygems.org/issues">Issues</a>
  <a class="project__link t-link" href="https://github.com/rubygems/rubygems.org/discussions/">Discussions</a>
  <a class="project__link t-link" href="http://slack.bundler.io/">Slack</a>
  <a class="project__link t-link" href="https://github.com/rubygems/rubygems.org">Source code</a>
</div>

<p class="avatars">
  <a href="https://github.com/qrush">
    <img src="https://secure.gravatar.com/avatar/eb8975af8e49e19e3dd6b6b84a542e26?s=32" title="Nick Quaranto">
  </a>
  <a href="https://github.com/sferik">
    <img src="https://secure.gravatar.com/avatar/1f74b13f1e5c6c69cb5d7fbaabb1e2cb?s=32" title="Erik Michaels-Ober">
  </a>
  <a href="https://github.com/dwradcliffe">
    <img src="https://secure.gravatar.com/avatar/013fd4dfb0e29744d5f37cf9068ba930?s=32" title="David Radcliffe">
  </a>
  <a href="https://github.com/evanphx">
    <img src="https://secure.gravatar.com/avatar/540cb3b3712ffe045113cb03bab616a2?s=32" title="Evan Phoenix">
  </a>
  <a href="https://github.com/arthurnn">
    <img src="https://secure.gravatar.com/avatar/bd33b5aaf0eb48d67a8145732d8f61a9?s=32" title="Arthur Nogueira Neves">
  </a>
</p>

<a class="project__name" href="https://github.com/rubygems/rubygems-infrastructure">RubyGems Infrastructure</a>

Chef cookbooks and bootstrap scripts to configure and manage Rubygems.org on AWS.

<div class="project__links">
  <a class="project__link t-link" href="https://github.com/rubygems/rubygems-infrastructure/wiki">Wiki</a>
  <a class="project__link t-link" href="https://trello.com/b/cd2HqKnE/infrastructure">Trello</a>
</div>

<p class="avatars">
  <a href="https://github.com/skottler">
    <img src="https://secure.gravatar.com/avatar/ee9182ab4e45d446dfa05c20c341371f?s=32" title="Sam Kottler">
  </a>
  <a href="https://github.com/dwradcliffe">
    <img src="https://secure.gravatar.com/avatar/013fd4dfb0e29744d5f37cf9068ba930?s=32" title="David Radcliffe">
  </a>
  <a href="https://github.com/evanphx">
    <img src="https://secure.gravatar.com/avatar/540cb3b3712ffe045113cb03bab616a2?s=32" title="Evan Phoenix">
  </a>
</p>

<a class="project__name" href="https://github.com/rubygems/guides">RubyGems Guides</a>

The central home for RubyGems documentation, including tutorials and reference material.
User-contributed guides are more than welcome and encouraged!

<div class="project__links">
  <a class="project__link t-link" href="http://guides.rubygems.org">Site</a>
  <a class="project__link t-link" href="https://github.com/rubygems/guides/issues">Issues</a>
</div>

<p class="avatars">
  <a href="https://github.com/qrush">
    <img src="https://secure.gravatar.com/avatar/eb8975af8e49e19e3dd6b6b84a542e26?s=32" title="Nick Quaranto">
  </a>
  <a href="https://github.com/sandal">
    <img src="https://secure.gravatar.com/avatar/31e038e4e9330f6c75ccfd1fca8010ee?s=32" title="Gregory Brown">
  </a>
  <a href="https://github.com/ffmike">
    <img src="https://secure.gravatar.com/avatar/a54251b745d59735ea5e9f0656a5d58d?s=32" title="Mike Gunderloy">
  </a>
</p>

<a class="project__name" href="https://github.com/rubygems/gemwhisperer">Gem Whisperer</a>

An example of how to use [RubyGems.org's
webhooks](http://guides.rubygems.org/rubygems-org-api/#webhook) to listen to every gem being
pushed.

<div class="project__links">
  <a class="project__link t-link" href="http://m.rubygems.org/">Site</a>
  <a class="project__link t-link" href="https://github.com/rubygems/gemwhisperer/issues">Issues</a>
</div>

<p class="avatars">
  <a href="https://github.com/qrush">
    <img src="https://secure.gravatar.com/avatar/eb8975af8e49e19e3dd6b6b84a542e26?s=32" title="Nick Quaranto">
  </a>
  <a href="https://github.com/laserlemon">
    <img src="https://secure.gravatar.com/avatar/0887991a8846577a6aa85433d6ab3ea2?s=32" title="Steve Richert">
  </a>
</p>

<a class="project__name" href="https://github.com/rubygems/gems">RubyGems.org API Library</a>

A Ruby implementation of the various API endpoints available on RubyGems.org.
If you're writing a service in Ruby to interact with gems available to the
community, check this out!

<div class="project__links">
  <a class="project__link t-link" href="https://github.com/rubygems/gems/issues">Issues</a>
</div>

<p class="avatars">
  <a href="https://github.com/sferik">
    <img src="https://secure.gravatar.com/avatar/1f74b13f1e5c6c69cb5d7fbaabb1e2cb?s=32" title="Erik Michaels-Ober">
  </a>
  <a href="https://github.com/arthurnn">
    <img src="https://secure.gravatar.com/avatar/bd33b5aaf0eb48d67a8145732d8f61a9?s=32" title="Arthur Nogueira Neves">
  </a>
</p>

<a class="project__name" href="https://github.com/rubygems/rubygems-mirror">RubyGems Mirror</a>

The current state of mirroring RubyGems is frankly embarrassing. We need
RubyGems to be highly available all over the world, no more excuses! Discussion
is going on in the [rubygems-mirror
wiki](https://github.com/rubygems/rubygems-mirror/wiki/Mirroring-2.0) on how
to improve it.

<div class="project__links">
  <a class="project__link t-link" href="https://github.com/rubygems/rubygems-mirror/issues">Issues</a>
</div>

<p class="avatars">
  <a href="https://github.com/raggi">
    <img src="https://secure.gravatar.com/avatar/b19b02a49b433c9e2e6e6c43785d2bfb?s=32" title="James Tucker">
  </a>
  <a href="https://github.com/hsbt">
    <img src="https://secure.gravatar.com/avatar/f2748d34b03ed11330f2a2218904eb2d?s=32" title="Hiroshi SHIBATA">
  </a>
</p>

## Ecosystem Projects

These projects are outside of the RubyGems core, but work closely with RubyGems to improve the gem experience for everyone.

<a class="project__name is-first" href="https://github.com/docmeta/rubydoc.info">RubyDoc.info</a>

A fantastic provider of [YARD](http://yardoc.org) documentation for every
RubyGem available. Push a gem, and you get docs created instantly!
RubyGems.org links to this site and it uses [RubyGems.org's
webhooks](http://guides.rubygems.org/rubygems-org-api/#webhook) as well.

<div class="project__links">
  <a class="project__link t-link" href="http://rubydoc.info">Site</a>
  <a class="project__link t-link" href="https://github.com/docmeta/rubydoc.info/issues">Issues</a>
  <a class="project__link t-link" href="https://groups.google.com/forum/#!forum/yardoc">Mailing List</a>
</div>

<p class="avatars">
  <a href="https://github.com/indirect">
    <img src="https://secure.gravatar.com/avatar/fb389f1e8b98d5d03be29e9dd309b3be?s=32" title="Andre Arko">
  </a>
  <a href="https://github.com/hone">
    <img src="https://secure.gravatar.com/avatar/efb7c66871043330ce1310a9bdd0aaf6?s=32" title="Terence Lee">
  </a>
</p>

<a class="project__name" href="https://github.com/copiousfreetime/stickler">Stickler</a>

Stickler is a great way to run and organize an internal gem server in your
organization. It helps with mirroring gems and providing a gem source to add
internal or proprietary code to.

<div class="project__links">
  <a class="project__link t-link" href="https://github.com/copiousfreetime/stickler/issues">Issues</a>
</div>

<p class="avatars">
  <a href="https://github.com/copiousfreetime">
    <img src="https://secure.gravatar.com/avatar/cff2d90ae70bbbb5d4865d8412159f85?s=32" title="Jeremy Hinegardner">
  </a>
</p>

<a class="project__name" href="https://github.com/geminabox/geminabox">Geminabox</a>

Need simple RubyGems hosting? Geminabox can do that! This project provides an
easy to setup way to host RubyGems internally and allow uploading of gems
without much hassle.

<div class="project__links">
  <a class="project__link t-link" href="https://github.com/geminabox/geminabox/issues">Issues</a>
</div>

<p class="avatars">
  <a href="https://github.com/tomlea">
    <img src="https://secure.gravatar.com/avatar/f61c5838432c656ea88dd77a56a40f52?s=32" title="Tom Leal">
  </a>
  <a href="https://github.com/tnir">
    <img src="https://secure.gravatar.com/avatar/8c5062689b241827e7532be41ff19e20?s=32" title="Takuya Noguchi">
  </a>
</p>

Add Your Own Idea
-----------------

We’d love for your new idea to be on this list. If you’re working on a
RubyGems related project, just [fork this
repo](https://github.com/rubygems/guides) and add the link!
