安装bundle的东西

```shell
E:\School\homepage\handle999.github.io>ruby -v
ruby 3.0.4p208 (2022-04-12 revision 3fa771dded) [x64-mingw32]

E:\School\homepage\handle999.github.io>gem -v
3.2.33

E:\School\homepage\handle999.github.io>bundle -v
Bundler version 2.5.23

E:\School\homepage\handle999.github.io>jekyll -v
Resolving dependencies...
E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler/definition.rb:605:in `materialize': Could not find tzinfo-data-1.2024.1, webrick-1.8.1, addressable-2.8.6, i18n-1.14.1, concurrent-ruby-1.2.3, dnsruby-1.70.0, commonmarker-0.23.10, rubyzip-2.3.2, rexml-3.2.6, listen-3.8.0, simpleidn-0.2.1, faraday-2.9.0, execjs-2.9.1, activesupport-7.1.3, rb-inotify-0.10.1, unf-0.1.4, faraday-net_http-3.1.0, bigdecimal-3.1.6, connection_pool-2.4.1, drb-2.2.0, minitest-5.22.2, mutex_m-0.2.0, net-http-0.4.1, ruby2_keywords-0.0.5, uri-0.13.0 in locally installed gems (Bundler::GemNotFound)
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler/definition.rb:201:in `specs'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler/definition.rb:268:in `specs_for'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler/runtime.rb:18:in `setup'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler.rb:164:in `setup'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/jekyll-3.9.3/lib/jekyll/plugin_manager.rb:50:in `require_from_bundler'        
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/jekyll-3.9.3/exe/jekyll:11:in `<top (required)>'
        from E:/Softwares/Ruby/Ruby30-x64/bin/jekyll:25:in `load'
        from E:/Softwares/Ruby/Ruby30-x64/bin/jekyll:25:in `<main>'

E:\School\homepage\handle999.github.io>bundle install
Fetching gem metadata from https://rubygems.org/..


Resolving dependencies...
Fetching bigdecimal 3.1.6
Fetching concurrent-ruby 1.2.3
Fetching connection_pool 2.4.1
Fetching ruby2_keywords 0.0.5
Fetching minitest 5.22.2
Fetching mutex_m 0.2.0
Fetching execjs 2.9.1
Fetching commonmarker 0.23.10
Fetching unf_ext 0.0.9.1 (x64-mingw32)
Fetching ffi 1.16.3 (x64-mingw32)
Fetching uri 0.13.0
Fetching rexml 3.2.6
Fetching racc 1.7.3
Fetching rubyzip 2.3.2
Fetching webrick 1.8.1
Fetching addressable 2.8.6
Installing bigdecimal 3.1.6 with native extensions
current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bigdecimal-3.1.6/ext/bigdecimal
["E:/Softwares/Ruby/Ruby30-x64/bin/ruby.exe", "-I", "E:/Softwares/Ruby/Ruby30-x64/lib/ruby/3.0.0", "-r", "./siteconf20250724-1596-nfpqz3.rb", "extconf.rb"]
checking for __builtin_clz()... yes
checking for __builtin_clzl()... yes
checking for __builtin_clzll()... yes
checking for float.h... yes
checking for math.h... yes
checking for stdbool.h... yes
checking for stdlib.h... yes
checking for x86intrin.h... yes
checking for _lzcnt_u32() in x86intrin.h... no
checking for _lzcnt_u64() in x86intrin.h... no
checking for intrin.h... yes
checking for __lzcnt() in intrin.h... no
checking for __lzcnt64() in intrin.h... no
checking for _BitScanReverse() in intrin.h... yes
checking for _BitScanReverse64() in intrin.h... yes
checking for labs() in stdlib.h... yes
checking for llabs() in stdlib.h... yes
checking for finite() in math.h... yes
checking for isfinite() in math.h... no
checking for ruby/atomic.h... yes
checking for ruby/internal/has/builtin.h... yes
checking for ruby/internal/static_assert.h... yes
checking for rb_rational_num() in ruby.h... yes
checking for rb_rational_den() in ruby.h... yes
checking for rb_complex_real() in ruby.h... yes
checking for rb_complex_imag() in ruby.h... yes
checking for rb_opts_exception_p() in ruby.h... yes
checking for rb_category_warn() in ruby.h... yes
checking for RB_WARN_CATEGORY_DEPRECATED in ruby.h... yes
creating Makefile
current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bigdecimal-3.1.6/ext/bigdecimal
["make", "DESTDIR=", "clean"]

current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bigdecimal-3.1.6/ext/bigdecimal
["make", "DESTDIR="]
generating bigdecimal-x64-mingw32.def
compiling bigdecimal.c
compiling missing.c
linking shared-object bigdecimal.so
current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bigdecimal-3.1.6/ext/bigdecimal
["make", "DESTDIR=", "install"]
/usr/bin/install -c -m 0755 bigdecimal.so ./.gem.20250724-1596-7iw70c

Retrying download gem from https://rubygems.org/ due to error (2/4): Gem::RemoteFetcher::FetchError too many connection resets (https://rubygems.org/gems/concurrent-ruby-1.2.3.gem)
Installing connection_pool 2.4.1
Installing ruby2_keywords 0.0.5
Fetching drb 2.2.0
Installing minitest 5.22.2
Installing mutex_m 0.2.0
Installing execjs 2.9.1
Installing commonmarker 0.23.10 with native extensions
current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/commonmarker-0.23.10/ext/commonmarker
["E:/Softwares/Ruby/Ruby30-x64/bin/ruby.exe", "-I", "E:/Softwares/Ruby/Ruby30-x64/lib/ruby/3.0.0", "-r", "./siteconf20250725-1596-rhf7o0.rb", "extconf.rb"]
creating Makefile
current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/commonmarker-0.23.10/ext/commonmarker
["make", "DESTDIR=", "clean"]

current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/commonmarker-0.23.10/ext/commonmarker
["make", "DESTDIR="]
generating commonmarker-x64-mingw32.def
compiling arena.c
compiling autolink.c
compiling blocks.c
compiling buffer.c
compiling cmark.c
compiling cmark_ctype.c
compiling commonmark.c
compiling commonmarker.c
In file included from houdini.h:9,
                 from commonmarker.c:3:
config.h:8: warning: "HAVE_STDBOOL_H" redefined
    8 | #define HAVE_STDBOOL_H
      |
In file included from E:/Softwares/Ruby/Ruby30-x64/include/ruby-3.0.0/ruby/internal/config.h:23,
                 from E:/Softwares/Ruby/Ruby30-x64/include/ruby-3.0.0/ruby/ruby.h:15,
                 from E:/Softwares/Ruby/Ruby30-x64/include/ruby-3.0.0/ruby.h:38,
                 from commonmarker.h:9,
                 from commonmarker.c:1:
E:/Softwares/Ruby/Ruby30-x64/include/ruby-3.0.0/x64-mingw32/ruby/config.h:28: note: this is the location of the previous definition
   28 | #define HAVE_STDBOOL_H 1
      |
compiling core-extensions.c
compiling ext_scanners.c
compiling footnotes.c
compiling houdini_href_e.c
compiling houdini_html_e.c
compiling houdini_html_u.c
compiling html.c
compiling inlines.c
compiling iterator.c
compiling latex.c
compiling linked_list.c
compiling man.c
compiling map.c
compiling node.c
compiling plaintext.c
compiling plugin.c
compiling references.c
compiling registry.c
compiling render.c
compiling scanners.c
compiling strikethrough.c
compiling syntax_extension.c
compiling table.c
compiling tagfilter.c
compiling tasklist.c
compiling utf8.c
compiling xml.c
linking shared-object commonmarker/commonmarker.so
current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/commonmarker-0.23.10/ext/commonmarker
["make", "DESTDIR=", "install"]
/usr/bin/install -c -m 0755 commonmarker.so ./.gem.20250725-1596-dcifgo/commonmarker

Retrying download gem from https://rubygems.org/ due to error (2/4): Gem::RemoteFetcher::FetchError too many connection resets (https://rubygems.org/gems/unf_ext-0.0.9.1-x64-mingw32.gem)
Installing ffi 1.16.3 (x64-mingw32)
Fetching rb-inotify 0.10.1
Installing uri 0.13.0
Fetching net-http 0.4.1
Installing rexml 3.2.6
Installing racc 1.7.3 with native extensions
current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/racc-1.7.3/ext/racc/cparse
["E:/Softwares/Ruby/Ruby30-x64/bin/ruby.exe", "-I", "E:/Softwares/Ruby/Ruby30-x64/lib/ruby/3.0.0", "-r", "./siteconf20250725-1596-onrg2y.rb", "extconf.rb"]
creating Makefile
current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/racc-1.7.3/ext/racc/cparse
["make", "DESTDIR=", "clean"]

current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/racc-1.7.3/ext/racc/cparse
["make", "DESTDIR="]
Installing rubyzip 2.3.2
generating cparse-x64-mingw32.def
compiling cparse.c
linking shared-object racc/cparse.so
current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/racc-1.7.3/ext/racc/cparse
["make", "DESTDIR=", "install"]
/usr/bin/install -c -m 0755 cparse.so ./.gem.20250725-1596-x7fwj7/racc
Fetching nokogiri 1.16.2 (x64-mingw32)
Installing webrick 1.8.1
Installing addressable 2.8.6
Installing concurrent-ruby 1.2.3
Fetching i18n 1.14.1
Fetching tzinfo-data 1.2024.1
Installing drb 2.2.0
Installing unf_ext 0.0.9.1 (x64-mingw32)
Fetching unf 0.1.4
Installing rb-inotify 0.10.1
Fetching listen 3.8.0
Installing net-http 0.4.1
Fetching faraday-net_http 3.1.0
Installing nokogiri 1.16.2 (x64-mingw32)
Installing i18n 1.14.1
Fetching activesupport 7.1.3
Installing tzinfo-data 1.2024.1
Installing unf 0.1.4
Fetching simpleidn 0.2.1
Installing listen 3.8.0
Installing faraday-net_http 3.1.0
Fetching faraday 2.9.0
Installing activesupport 7.1.3
Installing simpleidn 0.2.1
Fetching dnsruby 1.70.0
Installing faraday 2.9.0
Installing dnsruby 1.70.0
Bundle complete! 8 Gemfile dependencies, 100 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
Post-install message from dnsruby:
Installing dnsruby...
  For issues and source code: https://github.com/alexdalitz/dnsruby
  For general discussion (please tell us how you use dnsruby): https://groups.google.com/forum/#!forum/dnsruby
Post-install message from rubyzip:
RubyZip 3.0 is coming!
**********************

The public API of some Rubyzip classes has been modernized to use named
parameters for optional arguments. Please check your usage of the
following classes:
  * `Zip::File`
  * `Zip::Entry`
  * `Zip::InputStream`
  * `Zip::OutputStream`

Please ensure that your Gemfiles and .gemspecs are suitably restrictive
to avoid an unexpected breakage when 3.0 is released (e.g. ~> 2.3.0).
See https://github.com/rubyzip/rubyzip for details. The Changelog also
lists other enhancements and bugfixes that have been implemented since
version 2.3.0.
```

测试安装好的东西

```shell
E:\School\homepage\handle999.github.io>bundle info jekyll
  * jekyll (3.9.3)
        Summary: A simple, blog aware, static site generator.
        Homepage: https://github.com/jekyll/jekyll
        Path: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/jekyll-3.9.3
        Reverse Dependencies:
                github-pages (228) depends on jekyll (= 3.9.3)
                hawkins (2.0.5) depends on jekyll (~> 3.1)
                jekyll-avatar (0.7.0) depends on jekyll (>= 3.0, < 5.0)
                jekyll-commonmark-ghpages (0.4.0) depends on jekyll (~> 3.9.0)
                jekyll-default-layout (0.1.4) depends on jekyll (~> 3.0)
                jekyll-feed (0.15.1) depends on jekyll (>= 3.7, < 5.0)
                jekyll-github-metadata (2.13.0) depends on jekyll (>= 3.4, < 5.0)
                jekyll-include-cache (0.2.1) depends on jekyll (>= 3.7, < 5.0)
                jekyll-mentions (1.6.0) depends on jekyll (>= 3.7, < 5.0)
                jekyll-optional-front-matter (0.3.2) depends on jekyll (>= 3.0, < 5.0)
                jekyll-readme-index (0.3.0) depends on jekyll (>= 3.0, < 5.0)
                jekyll-redirect-from (0.16.0) depends on jekyll (>= 3.3, < 5.0)
                jekyll-relative-links (0.6.1) depends on jekyll (>= 3.3, < 5.0)
                jekyll-remote-theme (0.4.3) depends on jekyll (>= 3.5, < 5.0)
                jekyll-seo-tag (2.8.0) depends on jekyll (>= 3.8, < 5.0)
                jekyll-sitemap (1.4.0) depends on jekyll (>= 3.7, < 5.0)
                jekyll-theme-architect (0.2.0) depends on jekyll (> 3.5, < 5.0)
                jekyll-theme-cayman (0.2.0) depends on jekyll (> 3.5, < 5.0)
                jekyll-theme-dinky (0.2.0) depends on jekyll (> 3.5, < 5.0)
                jekyll-theme-hacker (0.2.0) depends on jekyll (> 3.5, < 5.0)
                jekyll-theme-leap-day (0.2.0) depends on jekyll (> 3.5, < 5.0)
                jekyll-theme-merlot (0.2.0) depends on jekyll (> 3.5, < 5.0)
                jekyll-theme-midnight (0.2.0) depends on jekyll (> 3.5, < 5.0)
                jekyll-theme-minimal (0.2.0) depends on jekyll (> 3.5, < 5.0)
                jekyll-theme-modernist (0.2.0) depends on jekyll (> 3.5, < 5.0)
                jekyll-theme-primer (0.6.0) depends on jekyll (> 3.5, < 5.0)
                jekyll-theme-slate (0.2.0) depends on jekyll (> 3.5, < 5.0)
                jekyll-theme-tactile (0.2.0) depends on jekyll (> 3.5, < 5.0)
                jekyll-theme-time-machine (0.2.0) depends on jekyll (> 3.5, < 5.0)
                jekyll-titles-from-headings (0.5.3) depends on jekyll (>= 3.3, < 5.0)
                jemoji (0.12.0) depends on jekyll (>= 3.0, < 5.0)
                minima (2.5.1) depends on jekyll (>= 3.5, < 5.0)

```



```shell
E:\School\homepage\handle999.github.io>bundle exec jekyll server
Unable to load the EventMachine C extension; To use the pure-ruby reactor, require 'em/pure_ruby'
E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/eventmachine-1.2.7-x64-mingw32/lib/rubyeventmachine.rb:2:in `require': cannot load such file -- 3.0/rubyeventmachine (LoadError)
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/eventmachine-1.2.7-x64-mingw32/lib/rubyeventmachine.rb:2:in `<top (required)>'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/eventmachine-1.2.7-x64-mingw32/lib/eventmachine.rb:8:in `require'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/eventmachine-1.2.7-x64-mingw32/lib/eventmachine.rb:8:in `<top (required)>'    
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/em-websocket-0.5.3/lib/em-websocket.rb:3:in `require'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/em-websocket-0.5.3/lib/em-websocket.rb:3:in `<top (required)>'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/hawkins-2.0.5/lib/hawkins/websockets.rb:2:in `require'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/hawkins-2.0.5/lib/hawkins/websockets.rb:2:in `<top (required)>'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/hawkins-2.0.5/lib/hawkins.rb:8:in `require'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/hawkins-2.0.5/lib/hawkins.rb:8:in `<module:Hawkins>'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/hawkins-2.0.5/lib/hawkins.rb:3:in `<top (required)>'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler/runtime.rb:60:in `require'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler/runtime.rb:60:in `block (2 levels) in require'     
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler/runtime.rb:55:in `each'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler/runtime.rb:55:in `block in require'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler/runtime.rb:44:in `each'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler/runtime.rb:44:in `require'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler.rb:212:in `require'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/jekyll-3.9.3/lib/jekyll/plugin_manager.rb:51:in `require_from_bundler'        
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/jekyll-3.9.3/exe/jekyll:11:in `<top (required)>'
        from E:/Softwares/Ruby/Ruby30-x64/bin/jekyll:25:in `load'
        from E:/Softwares/Ruby/Ruby30-x64/bin/jekyll:25:in `<main>'

E:\School\homepage\handle999.github.io>bundle exec jekyll serve 
Unable to load the EventMachine C extension; To use the pure-ruby reactor, require 'em/pure_ruby'
E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/eventmachine-1.2.7-x64-mingw32/lib/rubyeventmachine.rb:2:in `require': cannot load such file -- 3.0/rubyeventmachine (LoadError)
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/eventmachine-1.2.7-x64-mingw32/lib/rubyeventmachine.rb:2:in `<top (required)>'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/eventmachine-1.2.7-x64-mingw32/lib/eventmachine.rb:8:in `require'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/eventmachine-1.2.7-x64-mingw32/lib/eventmachine.rb:8:in `<top (required)>'    
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/em-websocket-0.5.3/lib/em-websocket.rb:3:in `require'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/em-websocket-0.5.3/lib/em-websocket.rb:3:in `<top (required)>'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/hawkins-2.0.5/lib/hawkins/websockets.rb:2:in `require'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/hawkins-2.0.5/lib/hawkins/websockets.rb:2:in `<top (required)>'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/hawkins-2.0.5/lib/hawkins.rb:8:in `require'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/hawkins-2.0.5/lib/hawkins.rb:8:in `<module:Hawkins>'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/hawkins-2.0.5/lib/hawkins.rb:3:in `<top (required)>'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler/runtime.rb:60:in `require'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler/runtime.rb:60:in `block (2 levels) in require'     
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler/runtime.rb:55:in `each'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler/runtime.rb:55:in `block in require'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler/runtime.rb:44:in `each'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler/runtime.rb:44:in `require'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/bundler-2.5.23/lib/bundler.rb:212:in `require'
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/jekyll-3.9.3/lib/jekyll/plugin_manager.rb:51:in `require_from_bundler'        
        from E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/gems/jekyll-3.9.3/exe/jekyll:11:in `<top (required)>'
        from E:/Softwares/Ruby/Ruby30-x64/bin/jekyll:25:in `load'
        from E:/Softwares/Ruby/Ruby30-x64/bin/jekyll:25:in `<main>'

E:\School\homepage\handle999.github.io>bundle install           
Fetching https://github.com/eventmachine/eventmachine.git
Fetching source index from https://rubygems.org/
Resolving dependencies...
Your bundle is locked to eventmachine (1.2.7) from
https://github.com/eventmachine/eventmachine.git (at master@e732041), but that
version can no longer be found in that source. That means the author of
eventmachine (1.2.7) has removed it. You'll need to update your bundle to a
version other than eventmachine (1.2.7) that hasn't been removed in order to
install.

E:\School\homepage\handle999.github.io>bundle exec jekyll serve 
The git source https://github.com/eventmachine/eventmachine.git is not yet checked out. Please run `bundle install` before trying to start your application

E:\School\homepage\handle999.github.io>bundle install           
Fetching https://github.com/eventmachine/eventmachine.git
Fetching gem metadata from https://rubygems.org/..........
Resolving dependencies...
错误：无法从 mirror.msys2.org : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 mirror.msys2.org : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
错误：无法从 mirror.msys2.org : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
警告：mirror.msys2.org 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 mirror.msys2.org : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
错误：无法从 mirror.msys2.org : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
错误：无法从 repo.msys2.org : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
错误：无法从 repo.msys2.org : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
错误：无法从 repo.msys2.org : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
警告：repo.msys2.org 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 repo.msys2.org : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 repo.msys2.org : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
错误：无法从 mirror.umd.edu : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
错误：无法从 mirror.umd.edu : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
错误：无法从 mirror.umd.edu : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
警告：mirror.umd.edu 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 mirror.umd.edu : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 mirror.umd.edu : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
错误：无法从 mirror.yandex.ru : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
错误：无法从 mirror.yandex.ru : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
错误：无法从 mirror.yandex.ru : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
警告：mirror.yandex.ru 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 mirror.yandex.ru : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 mirror.yandex.ru : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
错误：无法从 download.nus.edu.sg : SSL certificate problem: certificate has expired 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'     
错误：无法从 download.nus.edu.sg : SSL certificate problem: certificate has expired 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst' 
错误：无法从 download.nus.edu.sg : SSL certificate problem: certificate has expired 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
警告：download.nus.edu.sg 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 download.nus.edu.sg : SSL certificate problem: certificate has expired 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
错误：无法从 download.nus.edu.sg : SSL certificate problem: certificate has expired 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 ftp.acc.umu.se : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
错误：无法从 ftp.acc.umu.se : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
错误：无法从 ftp.acc.umu.se : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
警告：ftp.acc.umu.se 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 ftp.acc.umu.se : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
错误：无法从 ftp.acc.umu.se : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 ftp.nluug.nl : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
错误：无法从 ftp.nluug.nl : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
错误：无法从 ftp.nluug.nl : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
警告：ftp.nluug.nl 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 ftp.nluug.nl : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 ftp.nluug.nl : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
错误：无法从 ftp.osuosl.org : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
错误：无法从 ftp.osuosl.org : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
错误：无法从 ftp.osuosl.org : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
警告：ftp.osuosl.org 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 ftp.osuosl.org : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 ftp.osuosl.org : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
错误：无法从 mirror.internet.asn.au : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 mirror.internet.asn.au : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'        
错误：无法从 mirror.internet.asn.au : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
警告：mirror.internet.asn.au 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 mirror.internet.asn.au : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
错误：无法从 mirror.internet.asn.au : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
错误：无法从 mirror.selfnet.de : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 mirror.selfnet.de : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
错误：无法从 mirror.selfnet.de : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
警告：mirror.selfnet.de 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 mirror.selfnet.de : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
错误：无法从 mirror.selfnet.de : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
错误：无法从 mirror.ufro.cl : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 mirror.ufro.cl : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
错误：无法从 mirror.ufro.cl : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
警告：mirror.ufro.cl 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 mirror.ufro.cl : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
错误：无法从 mirror.ufro.cl : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
错误：无法从 mirrors.dotsrc.org : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 mirrors.dotsrc.org : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
错误：无法从 mirrors.dotsrc.org : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
警告：mirrors.dotsrc.org 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 mirrors.dotsrc.org : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
错误：无法从 mirrors.dotsrc.org : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
错误：无法从 mirrors.bfsu.edu.cn : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 mirrors.bfsu.edu.cn : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
错误：无法从 mirrors.bfsu.edu.cn : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
警告：mirrors.bfsu.edu.cn 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 mirrors.bfsu.edu.cn : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
错误：无法从 mirrors.bfsu.edu.cn : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
错误：无法从 mirrors.tuna.tsinghua.edu.cn : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 mirrors.tuna.tsinghua.edu.cn : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'       
错误：无法从 mirrors.tuna.tsinghua.edu.cn : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'  
警告：mirrors.tuna.tsinghua.edu.cn 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 mirrors.tuna.tsinghua.edu.cn : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
错误：无法从 mirrors.tuna.tsinghua.edu.cn : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'   
错误：无法从 mirrors.ustc.edu.cn : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
错误：无法从 mirrors.ustc.edu.cn : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
错误：无法从 mirrors.ustc.edu.cn : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
警告：mirrors.ustc.edu.cn 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 mirrors.ustc.edu.cn : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
错误：无法从 mirrors.ustc.edu.cn : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 mirror.nju.edu.cn : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
错误：无法从 mirror.nju.edu.cn : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
错误：无法从 mirror.nju.edu.cn : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
警告：mirror.nju.edu.cn 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 mirror.nju.edu.cn : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
错误：无法从 mirror.nju.edu.cn : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 repo.extreme-ix.org : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
错误：无法从 repo.extreme-ix.org : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
错误：无法从 repo.extreme-ix.org : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
警告：repo.extreme-ix.org 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 mirrors.hit.edu.cn : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
错误：无法从 mirrors.hit.edu.cn : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 repo.extreme-ix.org : SSL connection timeout 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
错误：无法从 repo.extreme-ix.org : SSL connection timeout 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
错误：无法从 mirrors.hit.edu.cn : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
警告：mirrors.hit.edu.cn 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 mirrors.hit.edu.cn : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
错误：无法从 mirrors.hit.edu.cn : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
错误：无法从 mirror.clarkson.edu : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 mirror.clarkson.edu : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
错误：无法从 mirror.clarkson.edu : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
警告：mirror.clarkson.edu 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 mirror.clarkson.edu : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
错误：无法从 mirror.clarkson.edu : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
错误：无法从 fastmirror.pp.ua : Connection timeout after 10003 ms 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 fastmirror.pp.ua : Connection timeout after 10002 ms 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
错误：无法从 fastmirror.pp.ua : Connection timeout after 10001 ms 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
警告：fastmirror.pp.ua 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 fastmirror.pp.ua : Connection timeout after 10000 ms 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
错误：无法从 fastmirror.pp.ua : Connection timeout after 10012 ms 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
错误：无法从 ftp.cc.uoc.gr : Failed to connect to ftp.cc.uoc.gr port 443 after 5239 ms: Connection timed out 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 ftp.cc.uoc.gr : Failed to connect to ftp.cc.uoc.gr port 443 after 5237 ms: Connection timed out 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
错误：无法从 ftp.cc.uoc.gr : Failed to connect to ftp.cc.uoc.gr port 443 after 5236 ms: Connection timed out 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
警告：ftp.cc.uoc.gr 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 ftp.cc.uoc.gr : Failed to connect to ftp.cc.uoc.gr port 443 after 5235 ms: Connection timed out 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
错误：无法从 ftp.cc.uoc.gr : Failed to connect to ftp.cc.uoc.gr port 443 after 5241 ms: Connection timed out 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
错误：无法从 mirror.jmu.edu : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-ca-certificates-20210119-1-any.pkg.tar.zst'
错误：无法从 mirror.jmu.edu : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-p11-kit-0.24.1-2-any.pkg.tar.zst'
错误：无法从 mirror.jmu.edu : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libffi-3.3-4-any.pkg.tar.zst'
警告：mirror.jmu.edu 返回错误过多，将在此事务的剩余部分中跳过
错误：无法从 mirror.jmu.edu : HTTP server doesn't seem to support byte ranges. Cannot resume. 获取文件 'mingw-w64-x86_64-openssl-1.1.1.n-1-any.pkg.tar.zst'
错误：无法从 mirror.jmu.edu : The requested URL returned error: 404 获取文件 'mingw-w64-x86_64-libtasn1-4.18.0-1-any.pkg.tar.zst'
current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/bundler/gems/eventmachine-e7320417cf29/ext
["E:/Softwares/Ruby/Ruby30-x64/bin/ruby.exe", "-I", "E:/Softwares/Ruby/Ruby30-x64/lib/ruby/3.0.0", "-r", "./siteconf20250725-20708-zwpz5a.rb", "extconf.rb"]
-----
Using OpenSSL from pkg-config -IE:/Softwares/Ruby/Ruby30-x64/msys64/mingw64/bin/../include  && -LE:/Softwares/Ruby/Ruby30-x64/msys64/mingw64/bin/../lib && -lssl -lcrypto
-----
checking for -lgdi32... yes
checking for -lcrypt32... yes
checking for openssl/ssl.h... yes
checking for openssl/err.h... yes
checking for BIO_read() in -lcrypto... yes
checking for SSL_CTX_new() in -lssl... yes
checking for rb_fdset_t in ruby/intern.h... yes
checking for rb_wait_for_single_fd()... yes
checking for rb_thread_fd_select()... yes
checking for inotify_init() in sys/inotify.h... no
checking for __NR_inotify_init in sys/syscall.h... no
checking for writev() in sys/uio.h... no
checking for pipe2() in unistd.h... no
checking for accept4() in sys/socket.h... no
checking for SOCK_CLOEXEC in sys/socket.h... no
checking for whether -l:libssp.a -fstack-protector is accepted as LDFLAGS... yes
checking for windows.h... yes
checking for winsock.h... yes
checking for -lkernel32... yes
checking for -lrpcrt4... yes
checking for -lgdi32... yes
checking for getaddrinfo()... yes
checking for clock_gettime()... yes
checking for CLOCK_MONOTONIC_RAW in time.h... no
checking for CLOCK_MONOTONIC in time.h... yes
checking for TLS_server_method() in openssl/ssl.h... yes
checking for SSL_CTX_set_min_proto_version in openssl/ssl.h... yes
checking for SSL_CTX_set_dh_auto(NULL, 0) in openssl/ssl.h... yes
checking for SSL_get1_peer_certificate() in openssl/ssl.h... no
CXXFLAGS=-march=x86-64 -mtune=generic -O2 -pipe -Wall -Wextra -Wno-deprecated-declarations -Wno-ignored-qualifiers -Wno-unused-result -Wno-address
creating Makefile
current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/bundler/gems/eventmachine-e7320417cf29/ext
["make", "DESTDIR=", "clean"]

current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/bundler/gems/eventmachine-e7320417cf29/ext
["make", "DESTDIR="]
generating rubyeventmachine-x64-mingw32.def
compiling binder.cpp
compiling cmain.cpp
compiling ed.cpp
compiling em.cpp
compiling kb.cpp
compiling page.cpp
compiling pipe.cpp
compiling rubymain.cpp
compiling ssl.cpp
linking shared-object rubyeventmachine.so
current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/bundler/gems/eventmachine-e7320417cf29/ext
["make", "DESTDIR=", "install"]
/usr/bin/install -c -m 0755 rubyeventmachine.so ./.gem.20250725-20708-wmzo4k
current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/bundler/gems/eventmachine-e7320417cf29/ext/fastfilereader
["E:/Softwares/Ruby/Ruby30-x64/bin/ruby.exe", "-I", "E:/Softwares/Ruby/Ruby30-x64/lib/ruby/3.0.0", "-r", "./siteconf20250725-20708-lujgh8.rb", "extconf.rb"]
checking for whether -l:libssp.a -fstack-protector is accepted as LDFLAGS... yes
checking for windows.h... yes
checking for winsock.h... yes
checking for -lkernel32... yes
checking for -lrpcrt4... yes
checking for -lgdi32... yes
creating Makefile
current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/bundler/gems/eventmachine-e7320417cf29/ext/fastfilereader
["make", "DESTDIR=", "clean"]

current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/bundler/gems/eventmachine-e7320417cf29/ext/fastfilereader
["make", "DESTDIR="]
generating fastfilereaderext-x64-mingw32.def
compiling mapper.cpp
compiling rubymain.cpp
linking shared-object fastfilereaderext.so
current directory: E:/Softwares/Ruby/Ruby30-x64/lib/ruby/gems/3.0.0/bundler/gems/eventmachine-e7320417cf29/ext/fastfilereader
["make", "DESTDIR=", "install"]
/usr/bin/install -c -m 0755 fastfilereaderext.so ./.gem.20250725-20708-3b15pg
Bundle complete! 9 Gemfile dependencies, 101 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
```
