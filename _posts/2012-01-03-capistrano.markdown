---
layout: post
title: Capistrano with Bundler
---
<div class='container'>
  <div class='row'>
    <h2>Capistrano with Bundler</h2>
  </div>
  <div class='row'>
    <div class='span12'>
      <pre class='prettyprint'>
        $ ruby -v
        > ruby 1.9.2p180 (2011-02-18 revision 30909) [x86_64-darwin10.7.3]
        $ gem install bundler
        $ cd path_to_project_using_capistrano
        $ bundle install
        $ bundle exec cap deploy
      </pre>
    </div>
    <div class='span4'>
      We are going to use [Capistrano](https://github.com/capistrano/capistrano/wiki/Documentation-v2.x) and [Bundler](http://gembundler.com/).
    </div>
  </div>
</div>
