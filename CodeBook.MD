





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://assets-cdn.github.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-700c269c41d75b60698a62d9306dae4a0f840bec4718545615f752400f1fd908.css" media="all" rel="stylesheet" />
  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-c7fa3a7e0dba4dcf7a3fa38cfcddd70a30e01fd27aee0b455615e7967047b47c.css" media="all" rel="stylesheet" />
  
  
  
  

  <meta name="viewport" content="width=device-width">
  
  <title>gcd/CodeBook.md at master · cosmogyrals/gcd</title>
  <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    
    <meta content="https://avatars3.githubusercontent.com/u/12698416?s=400&amp;v=4" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="cosmogyrals/gcd" property="og:title" /><meta content="https://github.com/cosmogyrals/gcd" property="og:url" /><meta content="gcd - getting and cleaning data assignment" property="og:description" />

  <link rel="assets" href="https://assets-cdn.github.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6MjM2NzcyMTY4OjBmYTY1NzNkZjYyNTg5MmIwOWE5YzYwN2ZjZTg4ZGIwYjliNjNhMzQ5NTllMDIzYmFhNTQ2NGViZDdkNzZiM2U=--73964044bc9f20e45e8cf92a5f859ed7e2ea85f3">
  <meta name="pjax-timeout" content="1000">
  <link rel="sudo-modal" href="/sessions/sudo_modal">
  <meta name="request-id" content="C08F:0A00:339CA74:5617378:5A5A639F" data-pjax-transient>
  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
  <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
  <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="https://collector.githubapp.com/github-external/browser_event" name="octolytics-event-url" /><meta content="C08F:0A00:339CA74:5617378:5A5A639F" name="octolytics-dimension-request_id" /><meta content="iad" name="octolytics-dimension-region_edge" /><meta content="iad" name="octolytics-dimension-region_render" /><meta content="35160233" name="octolytics-actor-id" /><meta content="shivaaniket" name="octolytics-actor-login" /><meta content="33252a06b7aed5aeb93ec08299ba5a36ad075dd394244eeefca0199ffa9c4a07" name="octolytics-actor-hash" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />




  <meta class="js-ga-set" name="dimension1" content="Logged In">


  

      <meta name="hostname" content="github.com">
  <meta name="user-login" content="shivaaniket">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="MTJjOTBlOWYyODM0ZjA3Y2EyODhmMDQyYWFkMTJjOTc4ZDVlOGQ2NDE1MDE4ZDQyZDFjZTJlMDg2OTU5ZGZhOHx7InJlbW90ZV9hZGRyZXNzIjoiMTIxLjI0NS4xODAuMTg4IiwicmVxdWVzdF9pZCI6IkMwOEY6MEEwMDozMzlDQTc0OjU2MTczNzg6NUE1QTYzOUYiLCJ0aW1lc3RhbXAiOjE1MTU4NzMxODMsImhvc3QiOiJnaXRodWIuY29tIn0=">

    <meta name="enabled-features" content="LOG_ACCESSIBILITY,UNIVERSE_BANNER,FREE_TRIALS">

  <meta name="html-safe-nonce" content="cebe94d39484fd4dd152fd98a93b5342d127ada0">

  <meta http-equiv="x-pjax-version" content="bf209e2338407b8d335e531f92159bfe">
  

      <link href="https://github.com/cosmogyrals/gcd/commits/master.atom" rel="alternate" title="Recent Commits to gcd:master" type="application/atom+xml">

  <meta name="description" content="gcd - getting and cleaning data assignment">
  <meta name="go-import" content="github.com/cosmogyrals/gcd git https://github.com/cosmogyrals/gcd.git">

  <meta content="12698416" name="octolytics-dimension-user_id" /><meta content="cosmogyrals" name="octolytics-dimension-user_login" /><meta content="117327758" name="octolytics-dimension-repository_id" /><meta content="cosmogyrals/gcd" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="117327758" name="octolytics-dimension-repository_network_root_id" /><meta content="cosmogyrals/gcd" name="octolytics-dimension-repository_network_root_nwo" /><meta content="false" name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" />


    <link rel="canonical" href="https://github.com/cosmogyrals/gcd/blob/master/CodeBook.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://assets-cdn.github.com/favicon.ico">

<meta name="theme-color" content="#1e2327">

  <meta name="msapplication-TileImage" content="/windows-tile.png">
  <meta name="msapplication-TileColor" content="#ffffff">


  </head>

  <body class="logged-in env-production page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="bg-black text-white p-3 show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    



        
<header class="Header  f5" role="banner">
  <div class="d-flex px-3 flex-justify-between container-lg">
    <div class="d-flex flex-justify-between">
      <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg aria-hidden="true" class="octicon octicon-mark-github" height="32" version="1.1" viewBox="0 0 16 16" width="32"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>


    </div>

    <div class="HeaderMenu d-flex flex-justify-between flex-auto">
      <div class="d-flex">
            <div class="">
              <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/cosmogyrals/gcd/search" class="js-site-search-form" data-scoped-search-url="/cosmogyrals/gcd/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <label class="form-control header-search-wrapper js-chromeless-input-container">
        <a href="/cosmogyrals/gcd/blob/master/CodeBook.md" class="header-search-scope no-underline">This repository</a>
      <input type="text"
        class="form-control header-search-input js-site-search-focus js-site-search-field is-clearable"
        data-hotkey="s"
        name="q"
        value=""
        placeholder="Search"
        aria-label="Search this repository"
        data-unscoped-placeholder="Search GitHub"
        data-scoped-placeholder="Search"
        autocapitalize="off">
        <input type="hidden" class="js-site-search-type-field" name="type" >
    </label>
</form></div>

            </div>

          <ul class="d-flex pl-2 flex-items-center text-bold list-style-none" role="navigation">
            <li>
              <a href="/pulls" aria-label="Pull requests you created" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
                Pull requests
</a>            </li>
            <li>
              <a href="/issues" aria-label="Issues you created" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
                Issues
</a>            </li>
                <li>
                  <a href="/marketplace" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-selected-links=" /marketplace">
                    Marketplace
</a>                </li>
            <li>
              <a href="/explore" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore">
                Explore
</a>            </li>
          </ul>
      </div>

      <div class="d-flex">
        
<ul class="user-nav d-flex flex-items-center list-style-none" id="user-links">
  <li class="dropdown js-menu-container">
    <span class="d-inline-block  px-2">
      

    </span>
  </li>

  <li class="dropdown js-menu-container">
    <details class="dropdown-details details-reset js-dropdown-details d-flex px-2 flex-items-center">
      <summary class="HeaderNavlink"
         aria-label="Create new…"
         data-ga-click="Header, create new, icon:add">
        <svg aria-hidden="true" class="octicon octicon-plus float-left mr-1 mt-1" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5z"/></svg>
        <span class="dropdown-caret mt-1"></span>
      </summary>

      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="cosmogyrals/gcd">This repository</span>
  </div>
    <a class="dropdown-item" href="/cosmogyrals/gcd/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </details>
  </li>

  <li class="dropdown js-menu-container">

    <details class="dropdown-details details-reset js-dropdown-details d-flex pl-2 flex-items-center">
      <summary class="HeaderNavlink name mt-1"
        aria-label="View profile and more"
        data-ga-click="Header, show menu, icon:avatar">
        <img alt="@shivaaniket" class="avatar float-left mr-1" src="https://avatars0.githubusercontent.com/u/35160233?s=40&amp;v=4" height="20" width="20">
        <span class="dropdown-caret"></span>
      </summary>

      <ul class="dropdown-menu dropdown-menu-sw">
        <li class="dropdown-header header-nav-current-user css-truncate">
          Signed in as <strong class="css-truncate-target">shivaaniket</strong>
        </li>

        <li class="dropdown-divider"></li>

        <li><a class="dropdown-item" href="/shivaaniket" data-ga-click="Header, go to profile, text:your profile">
          Your profile
        </a></li>
        <li><a class="dropdown-item" href="/shivaaniket?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a></li>
          <li><a class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, your gists, text:your gists">Your Gists</a></li>

        <li class="dropdown-divider"></li>

        <li><a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a></li>

        <li><a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
          Settings
        </a></li>

        <li><!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="bs/ci39dQQ8u2Fx1RJ16wkoijHSvpj11e5ZmRMI0tzkP17NFdfD3/yxZhrwcCSI7v+Y0gKwst71McRKnSrO07g==" /></div>
          <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
        </form></li>
      </ul>
    </details>
  </li>
</ul>


        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/logout" class="sr-only right-0" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="57K14mr9CiYoRfmq2YHewZy13ghuZBFWx09dqDXYNM6GqtosYFC81irEI2OBFYY4aXFm/G3um57wqClLvV83GQ==" /></div>
          <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </div>
</header>

      

  </div>

  <div id="start-of-content" class="show-on-focus"></div>

    <div id="js-flash-container">
</div>



  <div role="main" >
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <div id="js-repo-pjax-container" data-pjax-container >
      






  <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav  ">
    <div class="repohead-details-container clearfix container">

      <ul class="pagehead-actions">
  <li>
        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="i7m42zlH1PRlVpVD4Gf8KqzrqZVEg85JbErxjO9scYuA1Kj7S9qI0uLKXP6jdeNAy8XNUzQI+p8p7R3E3bhVeg==" /></div>      <input class="form-control" id="repository_id" name="repository_id" type="hidden" value="117327758" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/cosmogyrals/gcd/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target"
            role="button"
            aria-haspopup="true"
            aria-expanded="false"
            aria-label="Toggle repository notifications menu"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
                <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                Watch
            </span>
          </a>
          <a class="social-count js-social-count"
            href="/cosmogyrals/gcd/watchers"
            aria-label="1 user is watching this repository">
            1
          </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content">
            <div class="select-menu-header js-navigation-enable" tabindex="-1">
              <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                        Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input id="do_ignore" name="do" type="radio" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-mute" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"/></svg>
                        Stop ignoring
                    </span>
                  </div>
                </div>

              </div>

            </div>
          </div>
        </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/cosmogyrals/gcd/unstar" class="starred js-social-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="nw7R2kKELOWtCRgsEJA/IbsOY3LAI98mxlkDKFcMZpIyhH6+U98aL08yNLz5SVjlp12j03AaCxg8GKceqB6DUA==" /></div>
      <input type="hidden" name="context" value="repository"></input>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar cosmogyrals/gcd"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/cosmogyrals/gcd/stargazers"
           aria-label="0 users starred this repository">
          0
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/cosmogyrals/gcd/star" class="unstarred js-social-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="9K5wSW/wfvhtpypn5bz65GNHjeXpg+u5QR/ldewdb9E2w+FPDupHb5XygedIw7dSJRaLjzHKj3bVMT84tMkekA==" /></div>
      <input type="hidden" name="context" value="repository"></input>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star cosmogyrals/gcd"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
        Star
      </button>
        <a class="social-count js-social-count" href="/cosmogyrals/gcd/stargazers"
           aria-label="0 users starred this repository">
          0
        </a>
</form>  </div>

  </li>

  <li>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/cosmogyrals/gcd/fork" class="btn-with-count" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="KbD1to11NSJje1Pe7DIW1QX3wEdgQq+fxFDv0S20khCD13JtKgTAu9VBbO1C7QnWaqbxcbpL11SsSLW7VVr3Ew==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of cosmogyrals/gcd to your account"
                aria-label="Fork your own copy of cosmogyrals/gcd to your account">
              <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
              Fork
            </button>
</form>
    <a href="/cosmogyrals/gcd/network" class="social-count"
       aria-label="0 users forked this repository">
      0
    </a>
  </li>
</ul>

      <h1 class="public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a href="/cosmogyrals" class="url fn" rel="author">cosmogyrals</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/cosmogyrals/gcd" data-pjax="#js-repo-pjax-container">gcd</a></strong>

</h1>

    </div>
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax container"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/cosmogyrals/gcd" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /cosmogyrals/gcd" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a href="/cosmogyrals/gcd/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /cosmogyrals/gcd/issues" itemprop="url">
        <svg aria-hidden="true" class="octicon octicon-issue-opened" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/cosmogyrals/gcd/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /cosmogyrals/gcd/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>

    <a href="/cosmogyrals/gcd/projects" class="js-selected-navigation-item reponav-item" data-hotkey="g b" data-selected-links="repo_projects new_repo_project repo_project /cosmogyrals/gcd/projects">
      <svg aria-hidden="true" class="octicon octicon-project" height="16" version="1.1" viewBox="0 0 15 16" width="15"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      Projects
      <span class="Counter" >0</span>
</a>
    <a href="/cosmogyrals/gcd/wiki" class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /cosmogyrals/gcd/wiki">
      <svg aria-hidden="true" class="octicon octicon-book" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"/></svg>
      Wiki
</a>

  <a href="/cosmogyrals/gcd/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse /cosmogyrals/gcd/pulse">
    <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
    Insights
</a>

</nav>


  </div>

<div class="container new-discussion-timeline experiment-repo-nav ">
  <div class="repository-content ">

    
  <a href="/cosmogyrals/gcd/blob/8915a8fd223aee53835f0c428cf1d068795a1798/CodeBook.md" class="d-none js-permalink-shortcut" data-hotkey="y">Permalink</a>

  <!-- blob contrib key: blob_contributors:v21:7aab45b6b305585ef28b1113268a865e -->

  <div class="file-navigation js-zeroclipboard-container">
    
<div class="select-menu branch-select-menu js-menu-container js-select-menu float-left">
  <button class=" btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    
    type="button" aria-label="Switch branches or tags" aria-expanded="false" aria-haspopup="true">
      <i>Branch:</i>
      <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax>

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/cosmogyrals/gcd/blob/master/CodeBook.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

    <div class="BtnGroup float-right">
      <a href="/cosmogyrals/gcd/find/master"
            class="js-pjax-capture-input btn btn-sm BtnGroup-item"
            data-pjax
            data-hotkey="t">
        Find file
      </a>
      <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm BtnGroup-item tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
    </div>
    <div class="breadcrumb js-zeroclipboard-target">
      <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/cosmogyrals/gcd"><span>gcd</span></a></span></span><span class="separator">/</span><strong class="final-path">CodeBook.md</strong>
    </div>
  </div>


  
  <div class="commit-tease">
      <span class="float-right">
        <a class="commit-tease-sha" href="/cosmogyrals/gcd/commit/1afe097aa1904f1bf693d0d1a16b401c82e3d9f1" data-pjax>
          1afe097
        </a>
        <relative-time datetime="2018-01-13T08:46:16Z">Jan 13, 2018</relative-time>
      </span>
      <div>
        <img alt="" class="avatar" data-canonical-src="https://2.gravatar.com/avatar/2644ebdad8b177c5a168ee1964eccdf1?d=https%3A%2F%2Fassets-cdn.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png&amp;r=g&amp;s=140" height="20" src="https://camo.githubusercontent.com/7899fce23f5259f4791cb798f38dedd87d3cb9eb/68747470733a2f2f322e67726176617461722e636f6d2f6176617461722f32363434656264616438623137376335613136386565313936346563636466313f643d68747470732533412532462532466173736574732d63646e2e6769746875622e636f6d253246696d6167657325324667726176617461727325324667726176617461722d757365722d3432302e706e6726723d6726733d313430" width="20" />
        <span class="user-mention">Bill</span>
          <a href="/cosmogyrals/gcd/commit/1afe097aa1904f1bf693d0d1a16b401c82e3d9f1" class="message" data-pjax="true" title="added files 1">added files 1</a>
      </div>

    <div class="commit-tease-contributors">
      <button type="button" class="btn-link muted-link contributors-toggle" data-facebox="#blob_contributors_box">
        <strong>0</strong>
         contributors
      </button>
      
    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
      </ul>
    </div>
  </div>


  <div class="file">
    <div class="file-header">
  <div class="file-actions">

    <div class="BtnGroup">
      <a href="/cosmogyrals/gcd/raw/master/CodeBook.md" class="btn btn-sm BtnGroup-item" id="raw-url">Raw</a>
        <a href="/cosmogyrals/gcd/blame/master/CodeBook.md" class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b">Blame</a>
      <a href="/cosmogyrals/gcd/commits/master/CodeBook.md" class="btn btn-sm BtnGroup-item" rel="nofollow">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           href="https://desktop.github.com"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:windows">
            <svg aria-hidden="true" class="octicon octicon-device-desktop" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
        </a>

          <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/cosmogyrals/gcd/edit/master/CodeBook.md" class="inline-form js-update-url-with-hash" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="LG/9KHoJpCHjI4X27Oe8nMqCqkrvIPuPBIIP1wD32EEI08cj4od7Su48e+lapAC/Ig1JsF2jeQ2kKj/PbFWofg==" /></div>
            <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
              aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
              <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
            </button>
</form>
        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/cosmogyrals/gcd/delete/master/CodeBook.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="NB1oHg2o2C/g/CzC03iRBwEC1BNvVt30DedAY1hHFm5Wp6emGyHGWYUJp3dz1fOjgq+tH6YpqRmiok+T/oNrKg==" /></div>
          <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and delete the file" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
          </button>
</form>  </div>

  <div class="file-info">
      717 lines (634 sloc)
      <span class="file-info-divider"></span>
    22.2 KB
  </div>
</div>

    
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><p>Codebook for a summary table of a subset of data from the Human Activity Recognition
Using Smartphones Dataset Version 1.0 provided by Jorge L. Reyes-Ortiz, Davide Anguita,
Alessandro Ghio, Luca Oneto. Smartlab - Non Linear Complex Systems Laboratory, DITEN -
Università degli Studi di Genova.</p>
<p>The original READMED and codebook for these data are pasted at the bottom of this file.</p>
<p>=========================================</p>
<p>The tidy data set presented here consists of summary data from the UCI_HAR_dataset.</p>
<p>The data were estimated from 33 signals reported in the orignal study:</p>
<p>tBodyAcc-X,
tBodyAcc-Y,
tBodyAcc-Z,
tGravityAcc-X,
tGravityAcc-Y,
tGravityAcc-Z,
tBodyAccJerk-X,
tBodyAccJerk-Y,
tBodyAccJerk-Z,
tBodyGyro-X,
tBodyGyro-Y,
tBodyGyro-Z,
tBodyGyroJerk-X,
tBodyGyroJerk-Y,
tBodyGyroJerk-Z,
tBodyAccMag,
tGravityAccMag,
tBodyAccJerkMag,
tBodyGyroMag,
tBodyGyroJerkMag,
fBodyAcc-X,
fBodyAcc-Y,
fBodyAcc-Z,
fBodyAccJerk-X,
fBodyAccJerk-Y,
fBodyAccJerk-Z,
fBodyGyro-X,
fBodyGyro-Y,
fBodyGyro-Z,
fBodyAccMag,
fBodyAccJerkMag,
fBodyGyroMag,
fBodyGyroJerkMag</p>
<p>In concordance with the assignment's instructions, only data from the mean() and std()
variables are summarized in the file "tidy.table.txt". Additional vectors (gravityMean,
tBodyAccMean,tBodyAccJerkMean, tBodyGyroMean,tBodyGyroJerkMean), which were obtained by
averaging the signals in a signal window sample were excluded from the summary because
they were not themsleves the mean of one of the 33 signals shown above.</p>
<p>The data are organized into a 30 X 397 table (in tidy.table.txt) with headers for each
column. Each data value in this table represents the mean value of a measurement that was
calculated for each subject across multiple trials. The UCI_HAR_dataset originally randomly
partitioned these data into training and testing sets. The present summary table collapses
across those original sets.</p>
<p>========================================</p>
<p>Units:</p>
<p>The original acceleration measurements were shown in standard gravity units "g". The body acceleration signal was obtained by subtracting gravity from the total acceleration. The angular velocity vector was measured by the gyroscope for each window sample. The units were radians/second. These raw measurements were subsequently normalized and bound between -1 and 1.</p>
<p>Column descriptions:</p>
<p>Subject:
Positioned at the first column (left side) of the table, the Subject column provides a numeric
id label for each of the 30 individuals who participated in the study. Each subject's data is
spread out on the same row of the table as their Subject id.</p>
<p>Each of the subsequent 396 columns correspond to a data variable that contains the mean value
(for each subject) for the mean or standard deviation of one of the measurements that were
provided in the X_train.txt and X_test.txt files. The header of each of the columns corresponds
to a multi-element code that identifies the specific measurement.</p>
<pre><code>Code element:			Possible entries:
Activity 				Lay, Sit, Stand, Walk, WalkUp, WalkDown
Frequency or Time 		f, t
Signal Component 		Body, Gravity
Measurement				Acc, Gyro
Jerk:					Jerk
Magnitude:				Mag
Statistic 				mean, std
Axis					x,y,z
</code></pre>
<p>Activity:</p>
<p>The first element of the code corresponds to a label for 1 of 6 activities (behavioral actions)
that were performed by each subject. The original UCI_HAR activity labels were modified to
improve readability in table format. Here is a list showing the correspondence between the
original and modified activity labels:</p>
<pre><code>Original Label		Modified Label
Laying				Lay
Sitting				Sit
Standing			Stand
Walking				Walk
Walking_Down		WalkDown
Walking_Up			WalkUp
</code></pre>
<p>Frequency or Time:</p>
<p>This code element indicates whether the variable was frequency-based or time-based.
"f" labels data that were submitted to a Free Fourier Transformation (FFT), which correspond
to frequency domain signals.
"t" labels measurements that were captured at a constant rate of 50 Hz, which correspond to
time domain signals.</p>
<p>Body or Gravity:</p>
<p>This code element corresponds to different components of signals collected by the sensors.
"Body" were body motion components.
"Gravity" represents a sensor acceleration signal.</p>
<p>Acc or Gyro:</p>
<p>Signal detected from either an accelerometer (Acc), which estimated axial acceleration, or
from a gyroscope (Gyro), which estimated angular velocity.</p>
<p>Jerk:</p>
<p>Some variables contain the code element "Jerk". These columns consist of data of body linear
acceleration or angular velocity that were derived in time.</p>
<p>Mag:</p>
<p>Some variables contain the code element "Mag". These columns consist of the calculated magnitude
of the three-dimensional signals. The magnitude was original calculated using the Euclidian norm.</p>
<p>Statisic:</p>
<p>The UCI_HAR_dataset contained a numerous measurements that were excluded from this data summary.
This summary includes variables that contained mean() or std() in its header. The code elements
"mean" and "std" correspond to those original statistical calculations.</p>
<p>Axis:</p>
<p>Some variables end with the code element X, Y, or Z. The accelerometer and gyroscopes provided
3-axial signals. The last code element (X,Y, or Z) labels the corresponding axis.</p>
<p>========================================</p>
<p>Here is a complete list of all the column headers used in the summary table:</p>
<p>Lay_fBodyAcc_mean_X,
Lay_fBodyAcc_mean_Y,
Lay_fBodyAcc_mean_Z,
Lay_fBodyAcc_std_X,
Lay_fBodyAcc_std_Y,
Lay_fBodyAcc_std_Z,
Lay_fBodyAccJerk_mean_X,
Lay_fBodyAccJerk_mean_Y,
Lay_fBodyAccJerk_mean_Z,
Lay_fBodyAccJerk_std_X,
Lay_fBodyAccJerk_std_Y,
Lay_fBodyAccJerk_std_Z,
Lay_fBodyAccJerkMag_mean,
Lay_fBodyAccJerkMag_std,
Lay_fBodyAccMag_mean,
Lay_fBodyAccMag_std,
Lay_fBodyGyro_mean_X,
Lay_fBodyGyro_mean_Y,
Lay_fBodyGyro_mean_Z,
Lay_fBodyGyro_std_X,
Lay_fBodyGyro_std_Y,
Lay_fBodyGyro_std_Z,
Lay_fBodyGyroJerkMag_mean,
Lay_fBodyGyroJerkMag_std,
Lay_fBodyGyroMag_mean,
Lay_fBodyGyroMag_std,
Lay_tBodyAcc_mean_X,
Lay_tBodyAcc_mean_Y,
Lay_tBodyAcc_mean_Z,
Lay_tBodyAcc_std_X,
Lay_tBodyAcc_std_Y,
Lay_tBodyAcc_std_Z,
Lay_tBodyAccJerk_mean_X,
Lay_tBodyAccJerk_mean_Y,
Lay_tBodyAccJerk_mean_Z,
Lay_tBodyAccJerk_std_X,
Lay_tBodyAccJerk_std_Y,
Lay_tBodyAccJerk_std_Z,
Lay_tBodyAccJerkMag_mean,
Lay_tBodyAccJerkMag_std,
Lay_tBodyAccMag_mean,
Lay_tBodyAccMag_std,
Lay_tBodyGyro_mean_X,
Lay_tBodyGyro_mean_Y,
Lay_tBodyGyro_mean_Z,
Lay_tBodyGyro_std_X,
Lay_tBodyGyro_std_Y,
Lay_tBodyGyro_std_Z,
Lay_tBodyGyroJerk_mean_X,
Lay_tBodyGyroJerk_mean_Y,
Lay_tBodyGyroJerk_mean_Z,
Lay_tBodyGyroJerk_std_X,
Lay_tBodyGyroJerk_std_Y,
Lay_tBodyGyroJerk_std_Z,
Lay_tBodyGyroJerkMag_mean,
Lay_tBodyGyroJerkMag_std,
Lay_tBodyGyroMag_mean,
Lay_tBodyGyroMag_std,
Lay_tGravityAcc_mean_X,
Lay_tGravityAcc_mean_Y,
Lay_tGravityAcc_mean_Z,
Lay_tGravityAcc_std_X,
Lay_tGravityAcc_std_Y,
Lay_tGravityAcc_std_Z,
Lay_tGravityAccMag_mean,
Lay_tGravityAccMag_std</p>
<p>Sit_fBodyAcc_mean_X,
Sit_fBodyAcc_mean_Y,
Sit_fBodyAcc_mean_Z,
Sit_fBodyAcc_std_X,
Sit_fBodyAcc_std_Y,
Sit_fBodyAcc_std_Z,
Sit_fBodyAccJerk_mean_X,
Sit_fBodyAccJerk_mean_Y,
Sit_fBodyAccJerk_mean_Z,
Sit_fBodyAccJerk_std_X,
Sit_fBodyAccJerk_std_Y,
Sit_fBodyAccJerk_std_Z,
Sit_fBodyAccJerkMag_mean,
Sit_fBodyAccJerkMag_std,
Sit_fBodyAccMag_mean,
Sit_fBodyAccMag_std,
Sit_fBodyGyro_mean_X,
Sit_fBodyGyro_mean_Y,
Sit_fBodyGyro_mean_Z,
Sit_fBodyGyro_std_X,
Sit_fBodyGyro_std_Y,
Sit_fBodyGyro_std_Z,
Sit_fBodyGyroJerkMag_mean,
Sit_fBodyGyroJerkMag_std,
Sit_fBodyGyroMag_mean,
Sit_fBodyGyroMag_std,
Sit_tBodyAcc_mean_X,
Sit_tBodyAcc_mean_Y,
Sit_tBodyAcc_mean_Z,
Sit_tBodyAcc_std_X,
Sit_tBodyAcc_std_Y,
Sit_tBodyAcc_std_Z,
Sit_tBodyAccJerk_mean_X,
Sit_tBodyAccJerk_mean_Y,
Sit_tBodyAccJerk_mean_Z,
Sit_tBodyAccJerk_std_X,
Sit_tBodyAccJerk_std_Y,
Sit_tBodyAccJerk_std_Z,
Sit_tBodyAccJerkMag_mean,
Sit_tBodyAccJerkMag_std,
Sit_tBodyAccMag_mean,
Sit_tBodyAccMag_std,
Sit_tBodyGyro_mean_X,
Sit_tBodyGyro_mean_Y,
Sit_tBodyGyro_mean_Z,
Sit_tBodyGyro_std_X,
Sit_tBodyGyro_std_Y,
Sit_tBodyGyro_std_Z,
Sit_tBodyGyroJerk_mean_X,
Sit_tBodyGyroJerk_mean_Y,
Sit_tBodyGyroJerk_mean_Z,
Sit_tBodyGyroJerk_std_X,
Sit_tBodyGyroJerk_std_Y,
Sit_tBodyGyroJerk_std_Z,
Sit_tBodyGyroJerkMag_mean,
Sit_tBodyGyroJerkMag_std,
Sit_tBodyGyroMag_mean,
Sit_tBodyGyroMag_std,
Sit_tGravityAcc_mean_X,
Sit_tGravityAcc_mean_Y,
Sit_tGravityAcc_mean_Z,
Sit_tGravityAcc_std_X,
Sit_tGravityAcc_std_Y,
Sit_tGravityAcc_std_Z,
Sit_tGravityAccMag_mean,
Sit_tGravityAccMag_std</p>
<p>Stand_fBodyAcc_mean_X,
Stand_fBodyAcc_mean_Y,
Stand_fBodyAcc_mean_Z,
Stand_fBodyAcc_std_X,
Stand_fBodyAcc_std_Y,
Stand_fBodyAcc_std_Z,
Stand_fBodyAccJerk_mean_X,
Stand_fBodyAccJerk_mean_Y,
Stand_fBodyAccJerk_mean_Z,
Stand_fBodyAccJerk_std_X,
Stand_fBodyAccJerk_std_Y,
Stand_fBodyAccJerk_std_Z,
Stand_fBodyAccJerkMag_mean,
Stand_fBodyAccJerkMag_std,
Stand_fBodyAccMag_mean,
Stand_fBodyAccMag_std,
Stand_fBodyGyro_mean_X,
Stand_fBodyGyro_mean_Y,
Stand_fBodyGyro_mean_Z,
Stand_fBodyGyro_std_X,
Stand_fBodyGyro_std_Y,
Stand_fBodyGyro_std_Z,
Stand_fBodyGyroJerkMag_mean,
Stand_fBodyGyroJerkMag_std,
Stand_fBodyGyroMag_mean,
Stand_fBodyGyroMag_std,
Stand_tBodyAcc_mean_X,
Stand_tBodyAcc_mean_Y,
Stand_tBodyAcc_mean_Z,
Stand_tBodyAcc_std_X,
Stand_tBodyAcc_std_Y,
Stand_tBodyAcc_std_Z,
Stand_tBodyAccJerk_mean_X,
Stand_tBodyAccJerk_mean_Y,
Stand_tBodyAccJerk_mean_Z,
Stand_tBodyAccJerk_std_X,
Stand_tBodyAccJerk_std_Y,
Stand_tBodyAccJerk_std_Z,
Stand_tBodyAccJerkMag_mean,
Stand_tBodyAccJerkMag_std,
Stand_tBodyAccMag_mean,
Stand_tBodyAccMag_std,
Stand_tBodyGyro_mean_X,
Stand_tBodyGyro_mean_Y,
Stand_tBodyGyro_mean_Z,
Stand_tBodyGyro_std_X,
Stand_tBodyGyro_std_Y,
Stand_tBodyGyro_std_Z,
Stand_tBodyGyroJerk_mean_X,
Stand_tBodyGyroJerk_mean_Y,
Stand_tBodyGyroJerk_mean_Z,
Stand_tBodyGyroJerk_std_X,
Stand_tBodyGyroJerk_std_Y,
Stand_tBodyGyroJerk_std_Z,
Stand_tBodyGyroJerkMag_mean,
Stand_tBodyGyroJerkMag_std,
Stand_tBodyGyroMag_mean,
Stand_tBodyGyroMag_std,
Stand_tGravityAcc_mean_X,
Stand_tGravityAcc_mean_Y,
Stand_tGravityAcc_mean_Z,
Stand_tGravityAcc_std_X,
Stand_tGravityAcc_std_Y,
Stand_tGravityAcc_std_Z,
Stand_tGravityAccMag_mean,
Stand_tGravityAccMag_std</p>
<p>Walk_fBodyAcc_mean_X,
Walk_fBodyAcc_mean_Y,
Walk_fBodyAcc_mean_Z,
Walk_fBodyAcc_std_X,
Walk_fBodyAcc_std_Y,
Walk_fBodyAcc_std_Z,
Walk_fBodyAccJerk_mean_X,
Walk_fBodyAccJerk_mean_Y,
Walk_fBodyAccJerk_mean_Z,
Walk_fBodyAccJerk_std_X,
Walk_fBodyAccJerk_std_Y,
Walk_fBodyAccJerk_std_Z,
Walk_fBodyAccJerkMag_mean,
Walk_fBodyAccJerkMag_std,
Walk_fBodyAccMag_mean,
Walk_fBodyAccMag_std,
Walk_fBodyGyro_mean_X,
Walk_fBodyGyro_mean_Y,
Walk_fBodyGyro_mean_Z,
Walk_fBodyGyro_std_X,
Walk_fBodyGyro_std_Y,
Walk_fBodyGyro_std_Z,
Walk_fBodyGyroJerkMag_mean,
Walk_fBodyGyroJerkMag_std,
Walk_fBodyGyroMag_mean,
Walk_fBodyGyroMag_std,
Walk_tBodyAcc_mean_X,
Walk_tBodyAcc_mean_Y,
Walk_tBodyAcc_mean_Z,
Walk_tBodyAcc_std_X,
Walk_tBodyAcc_std_Y,
Walk_tBodyAcc_std_Z,
Walk_tBodyAccJerk_mean_X,
Walk_tBodyAccJerk_mean_Y,
Walk_tBodyAccJerk_mean_Z,
Walk_tBodyAccJerk_std_X,
Walk_tBodyAccJerk_std_Y,
Walk_tBodyAccJerk_std_Z,
Walk_tBodyAccJerkMag_mean,
Walk_tBodyAccJerkMag_std,
Walk_tBodyAccMag_mean,
Walk_tBodyAccMag_std,
Walk_tBodyGyro_mean_X,
Walk_tBodyGyro_mean_Y,
Walk_tBodyGyro_mean_Z,
Walk_tBodyGyro_std_X,
Walk_tBodyGyro_std_Y,
Walk_tBodyGyro_std_Z,
Walk_tBodyGyroJerk_mean_X,
Walk_tBodyGyroJerk_mean_Y,
Walk_tBodyGyroJerk_mean_Z,
Walk_tBodyGyroJerk_std_X,
Walk_tBodyGyroJerk_std_Y,
Walk_tBodyGyroJerk_std_Z,
Walk_tBodyGyroJerkMag_mean,
Walk_tBodyGyroJerkMag_std,
Walk_tBodyGyroMag_mean,
Walk_tBodyGyroMag_std,
Walk_tGravityAcc_mean_X,
Walk_tGravityAcc_mean_Y,
Walk_tGravityAcc_mean_Z,
Walk_tGravityAcc_std_X,
Walk_tGravityAcc_std_Y,
Walk_tGravityAcc_std_Z,
Walk_tGravityAccMag_mean,
Walk_tGravityAccMag_std</p>
<p>WalkDown_fBodyAcc_mean_X,
WalkDown_fBodyAcc_mean_Y,
WalkDown_fBodyAcc_mean_Z,
WalkDown_fBodyAcc_std_X,
WalkDown_fBodyAcc_std_Y,
WalkDown_fBodyAcc_std_Z,
WalkDown_fBodyAccJerk_mean_X,
WalkDown_fBodyAccJerk_mean_Y,
WalkDown_fBodyAccJerk_mean_Z,
WalkDown_fBodyAccJerk_std_X,
WalkDown_fBodyAccJerk_std_Y,
WalkDown_fBodyAccJerk_std_Z,
WalkDown_fBodyAccJerkMag_mean,
WalkDown_fBodyAccJerkMag_std,
WalkDown_fBodyAccMag_mean,
WalkDown_fBodyAccMag_std,
WalkDown_fBodyGyro_mean_X,
WalkDown_fBodyGyro_mean_Y,
WalkDown_fBodyGyro_mean_Z,
WalkDown_fBodyGyro_std_X,
WalkDown_fBodyGyro_std_Y,
WalkDown_fBodyGyro_std_Z,
WalkDown_fBodyGyroJerkMag_mean,
WalkDown_fBodyGyroJerkMag_std,
WalkDown_fBodyGyroMag_mean,
WalkDown_fBodyGyroMag_std,
WalkDown_tBodyAcc_mean_X,
WalkDown_tBodyAcc_mean_Y,
WalkDown_tBodyAcc_mean_Z,
WalkDown_tBodyAcc_std_X,
WalkDown_tBodyAcc_std_Y,
WalkDown_tBodyAcc_std_Z,
WalkDown_tBodyAccJerk_mean_X,
WalkDown_tBodyAccJerk_mean_Y,
WalkDown_tBodyAccJerk_mean_Z,
WalkDown_tBodyAccJerk_std_X,
WalkDown_tBodyAccJerk_std_Y,
WalkDown_tBodyAccJerk_std_Z,
WalkDown_tBodyAccJerkMag_mean,
WalkDown_tBodyAccJerkMag_std,
WalkDown_tBodyAccMag_mean,
WalkDown_tBodyAccMag_std,
WalkDown_tBodyGyro_mean_X,
WalkDown_tBodyGyro_mean_Y,
WalkDown_tBodyGyro_mean_Z,
WalkDown_tBodyGyro_std_X,
WalkDown_tBodyGyro_std_Y,
WalkDown_tBodyGyro_std_Z,
WalkDown_tBodyGyroJerk_mean_X,
WalkDown_tBodyGyroJerk_mean_Y,
WalkDown_tBodyGyroJerk_mean_Z,
WalkDown_tBodyGyroJerk_std_X,
WalkDown_tBodyGyroJerk_std_Y,
WalkDown_tBodyGyroJerk_std_Z,
WalkDown_tBodyGyroJerkMag_mean,
WalkDown_tBodyGyroJerkMag_std,
WalkDown_tBodyGyroMag_mean,
WalkDown_tBodyGyroMag_std,
WalkDown_tGravityAcc_mean_X,
WalkDown_tGravityAcc_mean_Y,
WalkDown_tGravityAcc_mean_Z,
WalkDown_tGravityAcc_std_X,
WalkDown_tGravityAcc_std_Y,
WalkDown_tGravityAcc_std_Z,
WalkDown_tGravityAccMag_mean,
WalkDown_tGravityAccMag_std</p>
<p>WalkUp_fBodyAcc_mean_X,
WalkUp_fBodyAcc_mean_Y,
WalkUp_fBodyAcc_mean_Z,
WalkUp_fBodyAcc_std_X,
WalkUp_fBodyAcc_std_Y,
WalkUp_fBodyAcc_std_Z,
WalkUp_fBodyAccJerk_mean_X,
WalkUp_fBodyAccJerk_mean_Y,
WalkUp_fBodyAccJerk_mean_Z,
WalkUp_fBodyAccJerk_std_X,
WalkUp_fBodyAccJerk_std_Y,
WalkUp_fBodyAccJerk_std_Z,
WalkUp_fBodyAccJerkMag_mean,
WalkUp_fBodyAccJerkMag_std,
WalkUp_fBodyAccMag_mean,
WalkUp_fBodyAccMag_std,
WalkUp_fBodyGyro_mean_X,
WalkUp_fBodyGyro_mean_Y,
WalkUp_fBodyGyro_mean_Z,
WalkUp_fBodyGyro_std_X,
WalkUp_fBodyGyro_std_Y,
WalkUp_fBodyGyro_std_Z,
WalkUp_fBodyGyroJerkMag_mean,
WalkUp_fBodyGyroJerkMag_std,
WalkUp_fBodyGyroMag_mean,
WalkUp_fBodyGyroMag_std,
WalkUp_tBodyAcc_mean_X,
WalkUp_tBodyAcc_mean_Y,
WalkUp_tBodyAcc_mean_Z,
WalkUp_tBodyAcc_std_X,
WalkUp_tBodyAcc_std_Y,
WalkUp_tBodyAcc_std_Z,
WalkUp_tBodyAccJerk_mean_X,
WalkUp_tBodyAccJerk_mean_Y,
WalkUp_tBodyAccJerk_mean_Z,
WalkUp_tBodyAccJerk_std_X,
WalkUp_tBodyAccJerk_std_Y,
WalkUp_tBodyAccJerk_std_Z,
WalkUp_tBodyAccJerkMag_mean,
WalkUp_tBodyAccJerkMag_std,
WalkUp_tBodyAccMag_mean,
WalkUp_tBodyAccMag_std,
WalkUp_tBodyGyro_mean_X,
WalkUp_tBodyGyro_mean_Y,
WalkUp_tBodyGyro_mean_Z,
WalkUp_tBodyGyro_std_X,
WalkUp_tBodyGyro_std_Y,
WalkUp_tBodyGyro_std_Z,
WalkUp_tBodyGyroJerk_mean_X,
WalkUp_tBodyGyroJerk_mean_Y,
WalkUp_tBodyGyroJerk_mean_Z,
WalkUp_tBodyGyroJerk_std_X,
WalkUp_tBodyGyroJerk_std_Y,
WalkUp_tBodyGyroJerk_std_Z,
WalkUp_tBodyGyroJerkMag_mean,
WalkUp_tBodyGyroJerkMag_std,
WalkUp_tBodyGyroMag_mean,
WalkUp_tBodyGyroMag_std,
WalkUp_tGravityAcc_mean_X,
WalkUp_tGravityAcc_mean_Y,
WalkUp_tGravityAcc_mean_Z,
WalkUp_tGravityAcc_std_X,
WalkUp_tGravityAcc_std_Y,
WalkUp_tGravityAcc_std_Z,
WalkUp_tGravityAccMag_mean,
WalkUp_tGravityAccMag_std</p>
<p>========================================</p>
<p>Here is the text of the original README file provided with the UCI_HAR_dataset:</p>
<h1><a href="#human-activity-recognition-using-smartphones-datasetversion-10" aria-hidden="true" class="anchor" id="user-content-human-activity-recognition-using-smartphones-datasetversion-10"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>==================================================================
Human Activity Recognition Using Smartphones Dataset
Version 1.0</h1>
<h1><a href="#jorge-l-reyes-ortiz-davide-anguita-alessandro-ghio-luca-onetosmartlab---non-linear-complex-systems-laboratoryditen---università-degli-studi-di-genovavia-opera-pia-11a-i-16145-genoa-italyactivityrecognitionsmartlabwswwwsmartlabws" aria-hidden="true" class="anchor" id="user-content-jorge-l-reyes-ortiz-davide-anguita-alessandro-ghio-luca-onetosmartlab---non-linear-complex-systems-laboratoryditen---università-degli-studi-di-genovavia-opera-pia-11a-i-16145-genoa-italyactivityrecognitionsmartlabwswwwsmartlabws"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Jorge L. Reyes-Ortiz, Davide Anguita, Alessandro Ghio, Luca Oneto.
Smartlab - Non Linear Complex Systems Laboratory
DITEN - Università degli Studi di Genova.
Via Opera Pia 11A, I-16145, Genoa, Italy.
<a href="mailto:activityrecognition@smartlab.ws">activityrecognition@smartlab.ws</a>
<a href="http://www.smartlab.ws" rel="nofollow">www.smartlab.ws</a></h1>
<p>The experiments have been carried out with a group of 30 volunteers within an age
bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS,
WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II)
on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear
acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have
been video-recorded to label the data manually. The obtained dataset has been randomly
partitioned into two sets, where 70% of the volunteers was selected for generating the
training data and 30% the test data.</p>
<p>The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise
filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap
(128 readings/window). The sensor acceleration signal, which has gravitational and
body motion components, was separated using a Butterworth low-pass filter into body
acceleration and gravity. The gravitational force is assumed to have only low frequency
components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window,
a vector of features was obtained by calculating variables from the time and frequency
domain. See 'features_info.txt' for more details.</p>
<h1><a href="#for-each-record-it-is-provided" aria-hidden="true" class="anchor" id="user-content-for-each-record-it-is-provided"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>For each record it is provided:</h1>
<ul>
<li>Triaxial acceleration from the accelerometer (total acceleration) and the estimated
body acceleration.</li>
<li>Triaxial Angular velocity from the gyroscope.</li>
<li>A 561-feature vector with time and frequency domain variables.</li>
<li>Its activity label.</li>
<li>An identifier of the subject who carried out the experiment.</li>
</ul>
<h1><a href="#the-dataset-includes-the-following-files" aria-hidden="true" class="anchor" id="user-content-the-dataset-includes-the-following-files"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>The dataset includes the following files:</h1>
<ul>
<li>
<p>'README.txt'</p>
</li>
<li>
<p>'features_info.txt': Shows information about the variables used on the feature
vector.</p>
</li>
<li>
<p>'features.txt': List of all features.</p>
</li>
<li>
<p>'activity_labels.txt': Links the class labels with their activity name.</p>
</li>
<li>
<p>'train/X_train.txt': Training set.</p>
</li>
<li>
<p>'train/y_train.txt': Training labels.</p>
</li>
<li>
<p>'test/X_test.txt': Test set.</p>
</li>
<li>
<p>'test/y_test.txt': Test labels.</p>
</li>
</ul>
<p>The following files are available for the train and test data. Their descriptions
are equivalent.</p>
<ul>
<li>
<p>'train/subject_train.txt': Each row identifies the subject who performed the
activity for each window sample. Its range is from 1 to 30.</p>
</li>
<li>
<p>'train/Inertial Signals/total_acc_x_train.txt': The acceleration signal from the
smartphone accelerometer X axis in standard gravity units 'g'. Every row shows a 128
element vector. The same description applies for the 'total_acc_x_train.txt'
and 'total_acc_z_train.txt' files for the Y and Z axis.</p>
</li>
<li>
<p>'train/Inertial Signals/body_acc_x_train.txt': The body acceleration signal obtained
by subtracting the gravity from the total acceleration.</p>
</li>
<li>
<p>'train/Inertial Signals/body_gyro_x_train.txt': The angular velocity vector measured
by the gyroscope for each window sample. The units are radians/second.</p>
</li>
</ul>
<h1><a href="#notes" aria-hidden="true" class="anchor" id="user-content-notes"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Notes:</h1>
<ul>
<li>Features are normalized and bounded within [-1,1].</li>
<li>Each feature vector is a row on the text file.</li>
</ul>
<p>For more information about this dataset contact: <a href="mailto:activityrecognition@smartlab.ws">activityrecognition@smartlab.ws</a></p>
<h1><a href="#license" aria-hidden="true" class="anchor" id="user-content-license"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>License:</h1>
<p>Use of this dataset in publications must be acknowledged by referencing the following publication [1]</p>
<p>[1] Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz.
Human Activity Recognition on Smartphones using a Multiclass Hardware-Friendly Support
Vector Machine. International Workshop of Ambient Assisted Living (IWAAL 2012).
Vitoria-Gasteiz, Spain. Dec 2012</p>
<p>This dataset is distributed AS-IS and no responsibility implied or explicit can be
addressed to the authors or their institutions for its use or misuse. Any commercial
use is prohibited.</p>
<p>Jorge L. Reyes-Ortiz, Alessandro Ghio, Luca Oneto, Davide Anguita. November 2012.</p>
<p>Original codebook.</p>
<h1><a href="#feature-selection" aria-hidden="true" class="anchor" id="user-content-feature-selection"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Feature Selection</h1>
<p>The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz.</p>
<p>Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag).</p>
<p>Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals).</p>
<p>These signals were used to estimate variables of the feature vector for each pattern:<br>
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.</p>
<p>tBodyAcc-XYZ
tGravityAcc-XYZ
tBodyAccJerk-XYZ
tBodyGyro-XYZ
tBodyGyroJerk-XYZ
tBodyAccMag
tGravityAccMag
tBodyAccJerkMag
tBodyGyroMag
tBodyGyroJerkMag
fBodyAcc-XYZ
fBodyAccJerk-XYZ
fBodyGyro-XYZ
fBodyAccMag
fBodyAccJerkMag
fBodyGyroMag
fBodyGyroJerkMag</p>
<p>The set of variables that were estimated from these signals are:</p>
<p>mean(): Mean value
std(): Standard deviation
mad(): Median absolute deviation
max(): Largest value in array
min(): Smallest value in array
sma(): Signal magnitude area
energy(): Energy measure. Sum of the squares divided by the number of values.
iqr(): Interquartile range
entropy(): Signal entropy
arCoeff(): Autorregresion coefficients with Burg order equal to 4
correlation(): correlation coefficient between two signals
maxInds(): index of the frequency component with largest magnitude
meanFreq(): Weighted average of the frequency components to obtain a mean frequency
skewness(): skewness of the frequency domain signal
kurtosis(): kurtosis of the frequency domain signal
bandsEnergy(): Energy of a frequency interval within the 64 bins of the FFT of each window.
angle(): Angle between to vectors.</p>
<p>Additional vectors obtained by averaging the signals in a signal window sample. These are used on the angle() variable:</p>
<p>gravityMean
tBodyAccMean
tBodyAccJerkMean
tBodyGyroMean
tBodyGyroJerkMean</p>
<p>The complete list of variables of each feature vector is available in 'features.txt'</p>
</article>
  </div>

  </div>

  <button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="d-none">Jump to Line</button>
  <div id="jump-to-line" style="display:none">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
      <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
      <button type="submit" class="btn">Go</button>
</form>  </div>


  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </div>
  </div>

  </div>

      
<div class="footer container-lg px-3" role="contentinfo">
  <div class="position-relative d-flex flex-justify-between py-6 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap ">
      <li class="mr-3">&copy; 2018 <span title="0.24730s from unicorn-829224309-jd4h6">GitHub</span>, Inc.</li>
        <li class="mr-3"><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li class="mr-3"><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li class="mr-3"><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li class="mr-3"><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>

    <a href="https://github.com" aria-label="Homepage" class="footer-octicon" title="GitHub">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
    <ul class="list-style-none d-flex flex-wrap ">
        <li class="mr-3"><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact GitHub</a></li>
      <li class="mr-3"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li class="mr-3"><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li class="mr-3"><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
    You can't perform that action at this time.
  </div>


    
    <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-3d1b998000028ce3709798fa6acf702b12c3f4e3fd24afd0e07609792f0674af.js"></script>
    
    <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-592bdcc9916cebab402ce09d893f4335b9f78a02dc206798816c3ed48a69183c.js"></script>
    
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner d-none">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
  </div>
</div>


  </body>
</html>

