



<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled is-u2f-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-73b6e7254b4ff47628bc2700deeaccfe68ae11f3b55062485e2e586d8a58246a.css" integrity="sha256-c7bnJUtP9HYovCcA3urM/miuEfO1UGJIXi5YbYpYJGo=" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-ff4e1442a7f097b1d8db6f9bc10af12ca6545a84d7385542b8b6f843a9d6558e.css" integrity="sha256-/04UQqfwl7HY22+bwQrxLKZUWoTXOFVCuLb4Q6nWVY4=" media="all" rel="stylesheet" />
    
    
    
    

    <link as="script" href="https://assets-cdn.github.com/assets/frameworks-5cb6f1c6f9211bfeed3bfc7596d8a1b3c5f4bb841d5318645a0aafff48b5b33d.js" rel="preload" />
    
    <link as="script" href="https://assets-cdn.github.com/assets/github-95420f7dee094ef84be94e3d806ad5b523740005c2a326fa92e11935f0f74c4e.js" rel="preload" />

    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=1020">
    
    
    <title>react-hn/README.md at master · mking/react-hn</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" href="/apple-touch-icon.png">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-57x57.png">
    <link rel="apple-touch-icon" sizes="60x60" href="/apple-touch-icon-60x60.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-72x72.png">
    <link rel="apple-touch-icon" sizes="76x76" href="/apple-touch-icon-76x76.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114x114.png">
    <link rel="apple-touch-icon" sizes="120x120" href="/apple-touch-icon-120x120.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144x144.png">
    <link rel="apple-touch-icon" sizes="152x152" href="/apple-touch-icon-152x152.png">
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon-180x180.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="https://avatars0.githubusercontent.com/u/489866?v=3&amp;s=400" name="twitter:image:src" /><meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="mking/react-hn" name="twitter:title" /><meta content="react-hn - Learn React by building the Hacker News front page" name="twitter:description" />
      <meta content="https://avatars0.githubusercontent.com/u/489866?v=3&amp;s=400" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="mking/react-hn" property="og:title" /><meta content="https://github.com/mking/react-hn" property="og:url" /><meta content="react-hn - Learn React by building the Hacker News front page" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/MjgyNTYyNTplNjRkMzJhZmEzYTFkNjBjMDU4YWQ1ODQ0YjU3OTU2ZTpkODUzZjViYzU1Y2I3YTk3OTg5ZGM0ZTUzYTRlYWUxMmI3M2NkMTI4M2E3YzUyMzZjMDEzYWQyNzlkNDBiYjA0--98c6013bcb1e1959faebddb18d9d8fcf44bd6ca1">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
<meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="DA5CCE3A:32B0:C506C24:57302B87" name="octolytics-dimension-request_id" /><meta content="2825625" name="octolytics-actor-id" /><meta content="baxtergu" name="octolytics-actor-login" /><meta content="f9227ff031bb28dc62ee9a881bde2631a47bb8f701115b502bdc5fd0553a3e4a" name="octolytics-actor-hash" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />



  <meta class="js-ga-set" name="dimension1" content="Logged In">



        <meta name="hostname" content="github.com">
    <meta name="user-login" content="baxtergu">

        <meta name="expected-hostname" content="github.com">
      <meta name="js-proxy-site-detection-payload" content="MDY5NDQ5MTVhOTFlNGViZTU2M2NkYWZhMGU3N2JhZGM3ZDc5YTliNWQ0ZWI1MGZjN2UyMGM3ZGNiZTcyNDM1OXx7InJlbW90ZV9hZGRyZXNzIjoiMjE4LjkyLjIwNi41OCIsInJlcXVlc3RfaWQiOiJEQTVDQ0UzQTozMkIwOkM1MDZDMjQ6NTczMDJCODciLCJ0aW1lc3RhbXAiOjE0NjI3NzQ2NjZ9">


      <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

    <meta content="be3d406aafe0f64afafd5e536cb239e50d9e8662" name="form-nonce" />

    <meta http-equiv="x-pjax-version" content="c372f8bdef825e3b42cbaa1b36bf6b82">
    

      
  <meta name="description" content="react-hn - Learn React by building the Hacker News front page">
  <meta name="go-import" content="github.com/mking/react-hn git https://github.com/mking/react-hn.git">

  <meta content="489866" name="octolytics-dimension-user_id" /><meta content="mking" name="octolytics-dimension-user_login" /><meta content="28558522" name="octolytics-dimension-repository_id" /><meta content="mking/react-hn" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="28558522" name="octolytics-dimension-repository_network_root_id" /><meta content="mking/react-hn" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/mking/react-hn/commits/master.atom" rel="alternate" title="Recent Commits to react-hn:master" type="application/atom+xml">


      <link rel="canonical" href="https://github.com/mking/react-hn/blob/master/README.md" data-pjax-transient>
  </head>


  <body class="logged-in   env-production windows vis-public page-blob">
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"></div>
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>

    
    
    



        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg aria-hidden="true" class="octicon octicon-mark-github" height="28" version="1.1" viewBox="0 0 16 16" width="28"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59 0.4 0.07 0.55-0.17 0.55-0.38 0-0.19-0.01-0.82-0.01-1.49-2.01 0.37-2.53-0.49-2.69-0.94-0.09-0.23-0.48-0.94-0.82-1.13-0.28-0.15-0.68-0.52-0.01-0.53 0.63-0.01 1.08 0.58 1.23 0.82 0.72 1.21 1.87 0.87 2.33 0.66 0.07-0.52 0.28-0.87 0.51-1.07-1.78-0.2-3.64-0.89-3.64-3.95 0-0.87 0.31-1.59 0.82-2.15-0.08-0.2-0.36-1.02 0.08-2.12 0 0 0.67-0.21 2.2 0.82 0.64-0.18 1.32-0.27 2-0.27 0.68 0 1.36 0.09 2 0.27 1.53-1.04 2.2-0.82 2.2-0.82 0.44 1.1 0.16 1.92 0.08 2.12 0.51 0.56 0.82 1.27 0.82 2.15 0 3.07-1.87 3.75-3.65 3.95 0.29 0.25 0.54 0.73 0.54 1.48 0 1.07-0.01 1.93-0.01 2.2 0 0.21 0.15 0.46 0.55 0.38C13.71 14.53 16 11.53 16 8 16 3.58 12.42 0 8 0z"></path></svg>
</a>


        <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/mking/react-hn/search" class="js-site-search-form" data-scoped-search-url="/mking/react-hn/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <label class="form-control header-search-wrapper js-chromeless-input-container">
      <div class="header-search-scope">This repository</div>
      <input type="text"
        class="form-control header-search-input js-site-search-focus js-site-search-field is-clearable"
        data-hotkey="s"
        name="q"
        placeholder="Search"
        aria-label="Search this repository"
        data-unscoped-placeholder="Search GitHub"
        data-scoped-placeholder="Search"
        tabindex="1"
        autocapitalize="off">
    </label>
</form></div>


      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item">
          <a href="/pulls" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
            Pull requests
</a>        </li>
        <li class="header-nav-item">
          <a href="/issues" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
            Issues
</a>        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com/" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item">
    
    <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s js-socket-channel js-notification-indicator" data-channel="notification-changed-v2:2825625" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
        <span class="mail-status "></span>
        <svg aria-hidden="true" class="octicon octicon-bell" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 12v1H0v-1l0.73-0.58c0.77-0.77 0.81-2.55 1.19-4.42 0.77-3.77 4.08-5 4.08-5 0-0.55 0.45-1 1-1s1 0.45 1 1c0 0 3.39 1.23 4.16 5 0.38 1.88 0.42 3.66 1.19 4.42l0.66 0.58z m-7 4c1.11 0 2-0.89 2-2H5c0 1.11 0.89 2 2 2z"></path></svg>
</a>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <svg aria-hidden="true" class="octicon octicon-plus left" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 9H7v5H5V9H0V7h5V2h2v5h5v2z"></path></svg>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>


  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="mking/react-hn">This repository</span>
  </div>
    <a class="dropdown-item" href="/mking/react-hn/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-sw js-menu-target" href="/baxtergu"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@baxtergu" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/2825625?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu  dropdown-menu-sw">
        <div class=" dropdown-header header-nav-current-user css-truncate">
            Signed in as <strong class="css-truncate-target">baxtergu</strong>

        </div>


        <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/baxtergu" data-ga-click="Header, go to profile, text:your profile">
            Your profile
          </a>
        <a class="dropdown-item" href="/stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a>
          <a class="dropdown-item" href="/explore" data-ga-click="Header, go to explore, text:explore">
            Explore
          </a>
          <a class="dropdown-item" href="/integrations" data-ga-click="Header, go to integrations, text:integrations">
            Integrations
          </a>
        <a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a>


          <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
            Settings
          </a>

          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/logout" class="logout-form" data-form-nonce="be3d406aafe0f64afafd5e536cb239e50d9e8662" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="c8XAU3wD7pnP6QWodKiNtGAEnUjfNx8FXZF4riLTX66CI2t98M/JnWRRak+vwNcG9hlAs7sUAL5NIf8X0QunJA==" /></div>
            <button class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
              Sign out
            </button>
</form>
      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>


      


    <div id="start-of-content" class="accessibility-aid"></div>

      <div id="js-flash-container">
</div>


    <div role="main" class="main-content">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode">
    <div id="js-repo-pjax-container" data-pjax-container>
      
<div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav">
  <div class="container repohead-details-container">

    

<ul class="pagehead-actions">

  <li>
        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-form-nonce="be3d406aafe0f64afafd5e536cb239e50d9e8662" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="IvGawvknnR8JYl4ta5U2UxDbiWJHXTBFIAgpIM1Ux3DocfhOc48A8hYmufUDbqvHq/R9+bDSjsNrQA+R4xBG2w==" /></div>      <input class="form-control" id="repository_id" name="repository_id" type="hidden" value="28558522" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/mking/react-hn/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
              <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6c4.94 0 7.94-6 7.94-6S13 2 8.06 2z m-0.06 10c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4z m2-4c0 1.11-0.89 2-2 2s-2-0.89-2-2 0.89-2 2-2 2 0.89 2 2z"></path></svg>
              Watch
            </span>
          </a>
          <a class="social-count js-social-count" href="/mking/react-hn/watchers">
            13
          </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header js-navigation-enable" tabindex="-1">
              <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48-3.75-3.75-3.75 3.75-1.48-1.48 3.75-3.75L0.77 4.25l1.48-1.48 3.75 3.75 3.75-3.75 1.48 1.48-3.75 3.75z"></path></svg>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5L4 13 0 9l1.5-1.5 2.5 2.5 6.5-6.5 1.5 1.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6c4.94 0 7.94-6 7.94-6S13 2 8.06 2z m-0.06 10c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4z m2-4c0 1.11-0.89 2-2 2s-2-0.89-2-2 0.89-2 2-2 2 0.89 2 2z"></path></svg>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5L4 13 0 9l1.5-1.5 2.5 2.5 6.5-6.5 1.5 1.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6c4.94 0 7.94-6 7.94-6S13 2 8.06 2z m-0.06 10c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4z m2-4c0 1.11-0.89 2-2 2s-2-0.89-2-2 0.89-2 2-2 2 0.89 2 2z"></path></svg>
                      Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5L4 13 0 9l1.5-1.5 2.5 2.5 6.5-6.5 1.5 1.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input id="do_ignore" name="do" type="radio" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-mute" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8 2.81v10.38c0 0.67-0.81 1-1.28 0.53L3 10H1c-0.55 0-1-0.45-1-1V7c0-0.55 0.45-1 1-1h2l3.72-3.72c0.47-0.47 1.28-0.14 1.28 0.53z m7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06 1.97 1.97-1.97 1.97 1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06-1.97-1.97 1.97-1.97z"></path></svg>
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

    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/mking/react-hn/unstar" class="starred" data-form-nonce="be3d406aafe0f64afafd5e536cb239e50d9e8662" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="hfYVfjRIPgRREa/9tXR2Cd4u8AebI5afxL5mZ5Bg8EdD5OKs28G0tLiMyWFMihagEqpk2hXv8nkVOJrKNfoTYA==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar mking/react-hn"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 6l-4.9-0.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14l4.33-2.33 4.33 2.33L10.4 9.26 14 6z"></path></svg>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/mking/react-hn/stargazers">
          292
        </a>
</form>
    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/mking/react-hn/star" class="unstarred" data-form-nonce="be3d406aafe0f64afafd5e536cb239e50d9e8662" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="x1HxuwrhJIFpkOkem3XdYsNY8AyFeq7Ka+WFxgMwG6/74vUfY1TxIMxiWlh32bfR8lpFiGbEcEwok0KD1KErow==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star mking/react-hn"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 6l-4.9-0.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14l4.33-2.33 4.33 2.33L10.4 9.26 14 6z"></path></svg>
        Star
      </button>
        <a class="social-count js-social-count" href="/mking/react-hn/stargazers">
          292
        </a>
</form>  </div>

  </li>

  <li>
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/mking/react-hn/fork" class="btn-with-count" data-form-nonce="be3d406aafe0f64afafd5e536cb239e50d9e8662" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="dPnOAfklekYagObupASFcWEh00xBP1jv42tgwuAam7nNmKV1Tt+TNV/KE+KtEJdgV4GpPYdnKh+Z04E+bpkOKw==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of mking/react-hn to your account"
                aria-label="Fork your own copy of mking/react-hn to your account">
              <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path d="M8 1c-1.11 0-2 0.89-2 2 0 0.73 0.41 1.38 1 1.72v1.28L5 8 3 6v-1.28c0.59-0.34 1-0.98 1-1.72 0-1.11-0.89-2-2-2S0 1.89 0 3c0 0.73 0.41 1.38 1 1.72v1.78l3 3v1.78c-0.59 0.34-1 0.98-1 1.72 0 1.11 0.89 2 2 2s2-0.89 2-2c0-0.73-0.41-1.38-1-1.72V9.5l3-3V4.72c0.59-0.34 1-0.98 1-1.72 0-1.11-0.89-2-2-2zM2 4.2c-0.66 0-1.2-0.55-1.2-1.2s0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2-0.55 1.2-1.2 1.2z m3 10c-0.66 0-1.2-0.55-1.2-1.2s0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2-0.55 1.2-1.2 1.2z m3-10c-0.66 0-1.2-0.55-1.2-1.2s0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2-0.55 1.2-1.2 1.2z"></path></svg>
              Fork
            </button>
</form>
    <a href="/mking/react-hn/network" class="social-count">
      41
    </a>
  </li>
</ul>

    <h1 class="entry-title public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M4 9h-1v-1h1v1z m0-3h-1v1h1v-1z m0-2h-1v1h1v-1z m0-2h-1v1h1v-1z m8-1v12c0 0.55-0.45 1-1 1H6v2l-1.5-1.5-1.5 1.5V14H1c-0.55 0-1-0.45-1-1V1C0 0.45 0.45 0 1 0h10c0.55 0 1 0.45 1 1z m-1 10H1v2h2v-1h3v1h5V11z m0-10H2v9h9V1z"></path></svg>
  <span class="author" itemprop="author"><a href="/mking" class="url fn" rel="author">mking</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/mking/react-hn" data-pjax="#js-repo-pjax-container">react-hn</a></strong>

</h1>

  </div>
  <div class="container">
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/mking/react-hn" aria-selected="true" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /mking/react-hn" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M9.5 3l-1.5 1.5 3.5 3.5L8 11.5l1.5 1.5 4.5-5L9.5 3zM4.5 3L0 8l4.5 5 1.5-1.5L2.5 8l3.5-3.5L4.5 3z"></path></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a href="/mking/react-hn/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /mking/react-hn/issues" itemprop="url">
        <svg aria-hidden="true" class="octicon octicon-issue-opened" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7S10.14 13.7 7 13.7 1.3 11.14 1.3 8s2.56-5.7 5.7-5.7m0-1.3C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7S10.86 1 7 1z m1 3H6v5h2V4z m0 6H6v2h2V10z"></path></svg>
        <span itemprop="name">Issues</span>
        <span class="counter">2</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/mking/react-hn/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /mking/react-hn/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M11 11.28c0-1.73 0-6.28 0-6.28-0.03-0.78-0.34-1.47-0.94-2.06s-1.28-0.91-2.06-0.94c0 0-1.02 0-1 0V0L4 3l3 3V4h1c0.27 0.02 0.48 0.11 0.69 0.31s0.3 0.42 0.31 0.69v6.28c-0.59 0.34-1 0.98-1 1.72 0 1.11 0.89 2 2 2s2-0.89 2-2c0-0.73-0.41-1.38-1-1.72z m-1 2.92c-0.66 0-1.2-0.55-1.2-1.2s0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2-0.55 1.2-1.2 1.2zM4 3c0-1.11-0.89-2-2-2S0 1.89 0 3c0 0.73 0.41 1.38 1 1.72 0 1.55 0 5.56 0 6.56-0.59 0.34-1 0.98-1 1.72 0 1.11 0.89 2 2 2s2-0.89 2-2c0-0.73-0.41-1.38-1-1.72V4.72c0.59-0.34 1-0.98 1-1.72z m-0.8 10c0 0.66-0.55 1.2-1.2 1.2s-1.2-0.55-1.2-1.2 0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2z m-1.2-8.8c-0.66 0-1.2-0.55-1.2-1.2s0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2-0.55 1.2-1.2 1.2z"></path></svg>
      <span itemprop="name">Pull requests</span>
      <span class="counter">2</span>
      <meta itemprop="position" content="3">
</a>  </span>

    <a href="/mking/react-hn/wiki" class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /mking/react-hn/wiki">
      <svg aria-hidden="true" class="octicon octicon-book" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M2 5h4v1H2v-1z m0 3h4v-1H2v1z m0 2h4v-1H2v1z m11-5H9v1h4v-1z m0 2H9v1h4v-1z m0 2H9v1h4v-1z m2-6v9c0 0.55-0.45 1-1 1H8.5l-1 1-1-1H1c-0.55 0-1-0.45-1-1V3c0-0.55 0.45-1 1-1h5.5l1 1 1-1h5.5c0.55 0 1 0.45 1 1z m-8 0.5l-0.5-0.5H1v9h6V3.5z m7-0.5H8.5l-0.5 0.5v8.5h6V3z"></path></svg>
      Wiki
</a>

  <a href="/mking/react-hn/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="pulse /mking/react-hn/pulse">
    <svg aria-hidden="true" class="octicon octicon-pulse" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M11.5 8L8.8 5.4 6.6 8.5 5.5 1.6 2.38 8H0V10h3.6L4.5 8.2l0.9 5.4L9 8.5l1.6 1.5H14V8H11.5z"></path></svg>
    Pulse
</a>
  <a href="/mking/react-hn/graphs" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors /mking/react-hn/graphs">
    <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M16 14v1H0V0h1v14h15z m-11-1H3V8h2v5z m4 0H7V3h2v10z m4 0H11V6h2v7z"></path></svg>
    Graphs
</a>

</nav>

  </div>
</div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    

<a href="/mking/react-hn/blob/4afe96b6e73b6c4a600bd9a61471c41deb95139c/README.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:3d5c49f3a5d017ca6ba62ce0fa9ff787 -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu branch-select-menu js-menu-container js-select-menu left">
  <button class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    title="master"
    type="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <i>Branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48-3.75-3.75-3.75 3.75-1.48-1.48 3.75-3.75L0.77 4.25l1.48-1.48 3.75 3.75 3.75-3.75 1.48 1.48-3.75 3.75z"></path></svg>
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


            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/mking/react-hn/blob/gh-pages/README.md"
               data-name="gh-pages"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5L4 13 0 9l1.5-1.5 2.5 2.5 6.5-6.5 1.5 1.5z"></path></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text" title="gh-pages">
                gh-pages
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/mking/react-hn/blob/master/README.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5L4 13 0 9l1.5-1.5 2.5 2.5 6.5-6.5 1.5 1.5z"></path></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text" title="master">
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

  <div class="btn-group right">
    <a href="/mking/react-hn/find/master"
          class="js-pjax-capture-input btn btn-sm"
          data-pjax
          data-hotkey="t">
      Find file
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
  </div>
  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/mking/react-hn"><span>react-hn</span></a></span></span><span class="separator">/</span><strong class="final-path">README.md</strong>
  </div>
</div>


  <div class="commit-tease">
      <span class="right">
        <a class="commit-tease-sha" href="/mking/react-hn/commit/fc8dad40ebf7ee13c2232455f3b615dc02aebb67" data-pjax>
          fc8dad4
        </a>
        <relative-time datetime="2015-01-26T05:14:22Z">Jan 25, 2015</relative-time>
      </span>
      <div>
        <img alt="@mking" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/489866?v=3&amp;s=40" width="20" />
        <a href="/mking" class="user-mention" rel="author">mking</a>
          <a href="/mking/react-hn/commit/fc8dad40ebf7ee13c2232455f3b615dc02aebb67" class="message" data-pjax="true" title="use streaming">use streaming</a>
      </div>

    <div class="commit-tease-contributors">
      <button type="button" class="btn-link muted-link contributors-toggle" data-facebox="#blob_contributors_box">
        <strong>3</strong>
         contributors
      </button>
          <a class="avatar-link tooltipped tooltipped-s" aria-label="mking" href="/mking/react-hn/commits/master/README.md?author=mking"><img alt="@mking" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/489866?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="szalansky" href="/mking/react-hn/commits/master/README.md?author=szalansky"><img alt="@szalansky" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/323025?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="johnhenry" href="/mking/react-hn/commits/master/README.md?author=johnhenry"><img alt="@johnhenry" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/393817?v=3&amp;s=40" width="20" /> </a>


    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@mking" height="24" src="https://avatars1.githubusercontent.com/u/489866?v=3&amp;s=48" width="24" />
            <a href="/mking">mking</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@szalansky" height="24" src="https://avatars1.githubusercontent.com/u/323025?v=3&amp;s=48" width="24" />
            <a href="/szalansky">szalansky</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@johnhenry" height="24" src="https://avatars2.githubusercontent.com/u/393817?v=3&amp;s=48" width="24" />
            <a href="/johnhenry">johnhenry</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
  <div class="file-actions">

    <div class="btn-group">
      <a href="/mking/react-hn/raw/master/README.md" class="btn btn-sm " id="raw-url">Raw</a>
        <a href="/mking/react-hn/blame/master/README.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
      <a href="/mking/react-hn/commits/master/README.md" class="btn btn-sm " rel="nofollow">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           href="github-windows://openRepo/https://github.com/mking/react-hn?branch=master&amp;filepath=README.md"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:windows">
            <svg aria-hidden="true" class="octicon octicon-device-desktop" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M15 2H1c-0.55 0-1 0.45-1 1v9c0 0.55 0.45 1 1 1h5.34c-0.25 0.61-0.86 1.39-2.34 2h8c-1.48-0.61-2.09-1.39-2.34-2h5.34c0.55 0 1-0.45 1-1V3c0-0.55-0.45-1-1-1z m0 9H1V3h14v8z"></path></svg>
        </a>

        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/mking/react-hn/edit/master/README.md" class="inline-form js-update-url-with-hash" data-form-nonce="be3d406aafe0f64afafd5e536cb239e50d9e8662" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="SDyNZacZj5JtH080cjV5sb2Mw63Ub1s301HnaupTVjw+m8ZTF4JBaj8T73+bsFpxwdiLFuOCaJkuibMVSJOqhw==" /></div>
          <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M0 12v3h3l8-8-3-3L0 12z m3 2H1V12h1v1h1v1z m10.3-9.3l-1.3 1.3-3-3 1.3-1.3c0.39-0.39 1.02-0.39 1.41 0l1.59 1.59c0.39 0.39 0.39 1.02 0 1.41z"></path></svg>
          </button>
</form>        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/mking/react-hn/delete/master/README.md" class="inline-form" data-form-nonce="be3d406aafe0f64afafd5e536cb239e50d9e8662" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="mFkoEKhre/UyDLKxTF8M2wr9gpue+qbjwd88LthzPFjzacJm7LlKEj00FRUhJ/PPqBVArM1BagP7XPNjbcs7Hg==" /></div>
          <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and delete the file" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M10 2H8c0-0.55-0.45-1-1-1H4c-0.55 0-1 0.45-1 1H1c-0.55 0-1 0.45-1 1v1c0 0.55 0.45 1 1 1v9c0 0.55 0.45 1 1 1h7c0.55 0 1-0.45 1-1V5c0.55 0 1-0.45 1-1v-1c0-0.55-0.45-1-1-1z m-1 12H2V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9z m1-10H1v-1h9v1z"></path></svg>
          </button>
</form>  </div>

  <div class="file-info">
      856 lines (681 sloc)
      <span class="file-info-divider"></span>
    19.9 KB
  </div>
</div>

  
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-react-hn" class="anchor" href="#react-hn" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>React HN</h1>

<p>This is a visual React tutorial. This tutorial should give you a feel for "growing" a React UI from small, modular parts. By the end of this tutorial, you will have built the <a href="https://mking.github.io/react-hn">HN front page in React</a>.</p>

<blockquote>
<p>Note: This tutorial covers React, Browserify, and CSS. It does not cover event handling (not needed for the HN front page), state (not needed for the HN front page), or Flux.</p>
</blockquote>

<p>This tutorial has five parts:</p>

<ol>
<li><p><a href="#setup">Setup</a></p></li>
<li><p><a href="#newsitem">NewsItem component</a></p>

<p><a href="/mking/react-hn/blob/master/img/NewsItem@2x.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsItem@2x.png" width="532" style="max-width:100%;"></a></p></li>
<li><p><a href="#newsheader">NewsHeader component</a></p>

<p><a href="/mking/react-hn/blob/master/img/NewsHeader@2x.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsHeader@2x.png" width="532" style="max-width:100%;"></a></p></li>
<li><p><a href="#newslist">NewsList component</a></p>

<p><a href="/mking/react-hn/blob/master/img/NewsList@2x.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsList@2x.png" width="532" style="max-width:100%;"></a></p></li>
<li><p><a href="#hacker-news-api">Display live data from the Hacker News API</a></p></li>
</ol>

<hr>

<h2><a id="user-content-setup" class="anchor" href="#setup" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>Setup</h2>

<ol>
<li><p>Create the project directory structure.</p>

<div class="highlight highlight-source-shell"><pre>mkdir -p hn/{build/js,css,html,img,js,json}
<span class="pl-c1">cd</span> hn</pre></div>

<blockquote>
<p>Note: We will be building the project from scratch. The solution in this repo is meant primarily to be a reference.</p>
</blockquote></li>
<li><p><a href="https://raw.githubusercontent.com/mking/react-hn/master/json/items.json">Download the sample data</a> into /json.</p></li>
<li><p>Download <a href="https://news.ycombinator.com/y18.gif">y18.gif</a> and <a href="https://news.ycombinator.com/grayarrow2x.gif">grayarrow2x.gif</a> into /img.</p></li>
<li><p>Create /package.json.</p>

<div class="highlight highlight-source-json"><pre>{
  <span class="pl-s"><span class="pl-pds">"</span>name<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>hn<span class="pl-pds">"</span></span>,
  <span class="pl-s"><span class="pl-pds">"</span>version<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>0.1.0<span class="pl-pds">"</span></span>,
  <span class="pl-s"><span class="pl-pds">"</span>private<span class="pl-pds">"</span></span>: <span class="pl-c1">true</span>,
  <span class="pl-s"><span class="pl-pds">"</span>browserify<span class="pl-pds">"</span></span>: {
    <span class="pl-s"><span class="pl-pds">"</span>transform<span class="pl-pds">"</span></span>: [
      [<span class="pl-s"><span class="pl-pds">"</span>reactify<span class="pl-pds">"</span></span>]
    ]
  }
}</pre></div></li>
<li><p>Install Browserify, React, and tools.</p>

<div class="highlight highlight-source-shell"><pre><span class="pl-c"># These dependencies are required for running the app.</span>
npm install --save react jquery lodash moment

<span class="pl-c"># These dependencies are required for building the app.</span>
npm install --save-dev browserify watchify reactify

<span class="pl-c"># These dependencies are globally installed command line tools.</span>
npm install -g browserify watchify http-server</pre></div></li>
</ol>

<p><a href="#newsitem">Next</a></p>

<hr>

<h2><a id="user-content-newsitem" class="anchor" href="#newsitem" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>NewsItem</h2>

<ol>
<li><p><a href="#newsitem-title">Display the title.</a></p>

<p><a href="/mking/react-hn/blob/master/img/NewsItemTitle.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsItemTitle.png" width="110" style="max-width:100%;"></a></p></li>
<li><p><a href="#newsitem-domain">Add the domain.</a></p>

<p><a href="/mking/react-hn/blob/master/img/NewsItemDomain.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsItemDomain.png" width="213" style="max-width:100%;"></a></p></li>
<li><p><a href="#newsitem-subtext">Add the subtext.</a></p>

<p><a href="/mking/react-hn/blob/master/img/NewsItemSubtext.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsItemSubtext.png" width="268" style="max-width:100%;"></a></p></li>
<li><p><a href="#newsitem-rank-and-vote">Add the rank and vote.</a></p>

<p><a href="/mking/react-hn/blob/master/img/NewsItemRankVote.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsItemRankVote.png" width="297" style="max-width:100%;"></a></p></li>
</ol>

<p><a href="#setup">Previous</a> · <a href="#newsitem-title">Next</a></p>

<hr>

<h2><a id="user-content-newsitem-title" class="anchor" href="#newsitem-title" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>NewsItem Title</h2>

<ol>
<li><p>Create a new JS file: /js/NewsItem.js.</p>

<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> $ <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>jquery<span class="pl-pds">'</span></span>);
<span class="pl-k">var</span> React <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>react<span class="pl-pds">'</span></span>);

<span class="pl-k">var</span> NewsItem <span class="pl-k">=</span> <span class="pl-smi">React</span>.<span class="pl-en">createClass</span>({
  <span class="pl-en">render</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsItem<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
        <span class="pl-k">&lt;</span>a className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsItem-titleLink<span class="pl-pds">"</span></span> href<span class="pl-k">=</span>{<span class="pl-v">this</span>.<span class="pl-smi">props</span>.<span class="pl-smi">item</span>.<span class="pl-smi">url</span>}<span class="pl-k">&gt;</span>{<span class="pl-v">this</span>.<span class="pl-smi">props</span>.<span class="pl-smi">item</span>.<span class="pl-c1">title</span>}<span class="pl-k">&lt;</span><span class="pl-k">/</span>a<span class="pl-k">&gt;</span>
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  }
});

<span class="pl-c1">module</span>.<span class="pl-smi">exports</span> <span class="pl-k">=</span> NewsItem;</pre></div>

<blockquote>
<p>Note: You should be able to paste this code directly into your JS file.</p>
</blockquote></li>
<li><p>Create a new JS file: /js/NewsItemTest.js.</p>

<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> $ <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>jquery<span class="pl-pds">'</span></span>);
<span class="pl-k">var</span> NewsItem <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>./NewsItem<span class="pl-pds">'</span></span>);
<span class="pl-k">var</span> React <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>react<span class="pl-pds">'</span></span>);

<span class="pl-smi">$</span>.<span class="pl-en">ajax</span>({
  url<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>/json/items.json<span class="pl-pds">'</span></span>
}).<span class="pl-en">then</span>(<span class="pl-k">function</span> (<span class="pl-smi">items</span>) {
  <span class="pl-c">// Log the data so we can inspect it in the developer console.</span>
  <span class="pl-en">console</span>.<span class="pl-c1">log</span>(<span class="pl-s"><span class="pl-pds">'</span>items<span class="pl-pds">'</span></span>, items);
  <span class="pl-c">// Use a fake rank for now.</span>
  <span class="pl-smi">React</span>.<span class="pl-en">render</span>(<span class="pl-k">&lt;</span>NewsItem item<span class="pl-k">=</span>{items[<span class="pl-c1">0</span>]} rank<span class="pl-k">=</span>{<span class="pl-c1">1</span>}<span class="pl-k">/</span><span class="pl-k">&gt;</span>, <span class="pl-en">$</span>(<span class="pl-s"><span class="pl-pds">'</span>#content<span class="pl-pds">'</span></span>)[<span class="pl-c1">0</span>]);
});</pre></div>

<blockquote>
<p>Note: This lets us develop the NewsItem component in isolation, rather than requiring it to be hooked into the full app.</p>
</blockquote></li>
<li><p>Create a new CSS file: /css/NewsItem.css. We are following <a href="https://medium.com/@fat/mediums-css-is-actually-pretty-fucking-good-b8e2a6c78b06">Jacob Thornton's CSS style guide</a>.</p>

<div class="highlight highlight-source-css"><pre><span class="pl-e">.newsItem</span> {
  <span class="pl-c1"><span class="pl-c1">color</span></span>: <span class="pl-c1">#828282</span>;
  <span class="pl-c1"><span class="pl-c1">margin-top</span></span>: <span class="pl-c1">5<span class="pl-k">px</span></span>;
}

<span class="pl-e">.newsItem-titleLink</span> {
  <span class="pl-c1"><span class="pl-c1">color</span></span>: <span class="pl-c1">black</span>;
  <span class="pl-c1"><span class="pl-c1">font-size</span></span>: <span class="pl-c1">10<span class="pl-k">pt</span></span>;
  <span class="pl-c1"><span class="pl-c1">text-decoration</span></span>: <span class="pl-c1">none</span>;
}</pre></div></li>
<li><p>Create a new CSS file: /css/app.css.</p>

<div class="highlight highlight-source-css"><pre><span class="pl-ent">body</span> {
  <span class="pl-c1"><span class="pl-c1">font-family</span></span>: <span class="pl-c1">Verdana</span>, <span class="pl-c1">sans-serif</span>;
}</pre></div></li>
<li><p>Create a new HTML file: /html/NewsItem.html.</p>

<div class="highlight highlight-text-html-basic"><pre>&lt;!DOCTYPE html&gt;
&lt;<span class="pl-ent">html</span>&gt;
  &lt;<span class="pl-ent">head</span>&gt;
    &lt;<span class="pl-ent">meta</span> <span class="pl-e">charset</span>=<span class="pl-s"><span class="pl-pds">"</span>utf-8<span class="pl-pds">"</span></span>&gt;
    &lt;<span class="pl-ent">title</span>&gt;NewsItem&lt;/<span class="pl-ent">title</span>&gt;
    &lt;<span class="pl-ent">link</span> <span class="pl-e">href</span>=<span class="pl-s"><span class="pl-pds">"</span>../css/NewsItem.css<span class="pl-pds">"</span></span> <span class="pl-e">rel</span>=<span class="pl-s"><span class="pl-pds">"</span>stylesheet<span class="pl-pds">"</span></span>&gt;
    &lt;<span class="pl-ent">link</span> <span class="pl-e">href</span>=<span class="pl-s"><span class="pl-pds">"</span>../css/app.css<span class="pl-pds">"</span></span> <span class="pl-e">rel</span>=<span class="pl-s"><span class="pl-pds">"</span>stylesheet<span class="pl-pds">"</span></span>&gt;
  &lt;/<span class="pl-ent">head</span>&gt;
  &lt;<span class="pl-ent">body</span>&gt;
    &lt;<span class="pl-ent">div</span> <span class="pl-e">id</span>=<span class="pl-s"><span class="pl-pds">"</span>content<span class="pl-pds">"</span></span>&gt;&lt;/<span class="pl-ent">div</span>&gt;
<span class="pl-s1">    &lt;<span class="pl-ent">script</span> <span class="pl-e">src</span>=<span class="pl-s"><span class="pl-pds">"</span>../build/js/NewsItemTest.js<span class="pl-pds">"</span></span>&gt;&lt;/<span class="pl-ent">script</span>&gt;</span>
  &lt;/<span class="pl-ent">body</span>&gt;
&lt;/<span class="pl-ent">html</span>&gt;</pre></div></li>
<li><p>Start Watchify. This compiles your React (JSX) components into ordinary JavaScript.</p>

<div class="highlight highlight-source-shell"><pre>watchify -v -o build/js/NewsItemTest.js js/NewsItemTest.js</pre></div></li>
<li><p>Start the HTTP server.</p>

<div class="highlight highlight-source-shell"><pre>http-server -p 8888</pre></div></li>
<li><p>Visit <a href="http://localhost:8888/html/NewsItem.html">http://localhost:8888/html/NewsItem.html</a>. You should see the following.</p>

<p><a href="/mking/react-hn/blob/master/img/NewsItemTitle.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsItemTitle.png" width="110" style="max-width:100%;"></a></p>

<p><a href="/mking/react-hn/blob/master/img/DeveloperConsole.png" target="_blank"><img src="/mking/react-hn/raw/master/img/DeveloperConsole.png" width="274" style="max-width:100%;"></a></p></li>
</ol>

<p><a href="#newsitem">Previous</a> · <a href="#newsitem-domain">Next</a></p>

<h2><a id="user-content-newsitem-domain" class="anchor" href="#newsitem-domain" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>NewsItem Domain</h2>

<ol>
<li><p>Update the JS.</p>

<div class="highlight highlight-source-js"><pre><span class="pl-c">// ...</span>
<span class="pl-k">var</span> url <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>url<span class="pl-pds">'</span></span>);

<span class="pl-k">var</span> NewsItem <span class="pl-k">=</span> <span class="pl-smi">React</span>.<span class="pl-en">createClass</span>({
  <span class="pl-c">// ...</span>

  <span class="pl-en">getDomain</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> <span class="pl-smi">url</span>.<span class="pl-c1">parse</span>(<span class="pl-v">this</span>.<span class="pl-smi">props</span>.<span class="pl-smi">item</span>.<span class="pl-smi">url</span>).<span class="pl-c1">hostname</span>;
  },

  <span class="pl-en">render</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsItem<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
        <span class="pl-k">...</span>
        <span class="pl-k">&lt;</span>span className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsItem-domain<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
          ({<span class="pl-v">this</span>.<span class="pl-en">getDomain</span>()})
        <span class="pl-k">&lt;</span><span class="pl-k">/</span>span<span class="pl-k">&gt;</span>
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  }</pre></div>

<blockquote>
<p>Note: This code should be added onto the existing code in /js/NewsItem.js.</p>
</blockquote></li>
<li><p>Update the CSS.</p>

<div class="highlight highlight-source-css"><pre><span class="pl-e">.newsItem-domain</span> {
  <span class="pl-c1"><span class="pl-c1">font-size</span></span>: <span class="pl-c1">8<span class="pl-k">pt</span></span>;
  <span class="pl-c1"><span class="pl-c1">margin-left</span></span>: <span class="pl-c1">5<span class="pl-k">px</span></span>;
}</pre></div>

<blockquote>
<p>Note: This code should be added onto the existing code in /css/NewsItem.css.</p>
</blockquote></li>
<li><p>Refresh the browser. You should see the following.</p>

<p><a href="/mking/react-hn/blob/master/img/NewsItemDomain.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsItemDomain.png" width="213" style="max-width:100%;"></a></p></li>
</ol>

<p><a href="#newsitem-title">Previous</a> · <a href="#newsitem-subtext">Next</a></p>

<hr>

<h2><a id="user-content-newsitem-subtext" class="anchor" href="#newsitem-subtext" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>NewsItem Subtext</h2>

<ol>
<li><p>Update the JS. Note: We are factoring out the title part into its own method.</p>

<div class="highlight highlight-source-js"><pre><span class="pl-c">// ...</span>
<span class="pl-k">var</span> moment <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>moment<span class="pl-pds">'</span></span>);

<span class="pl-k">var</span> NewsItem <span class="pl-k">=</span> <span class="pl-smi">React</span>.<span class="pl-en">createClass</span>({
  <span class="pl-c">// ...</span>

  <span class="pl-en">getCommentLink</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">var</span> commentText <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>discuss<span class="pl-pds">'</span></span>;
    <span class="pl-k">if</span> (<span class="pl-v">this</span>.<span class="pl-smi">props</span>.<span class="pl-smi">item</span>.<span class="pl-smi">kids</span> <span class="pl-k">&amp;&amp;</span> <span class="pl-v">this</span>.<span class="pl-smi">props</span>.<span class="pl-smi">item</span>.<span class="pl-smi">kids</span>.<span class="pl-c1">length</span>) {
      <span class="pl-c">// This only counts top-level comments.</span>
      <span class="pl-c">// To get the full count, recursively get item details for this news item.</span>
      commentText <span class="pl-k">=</span> <span class="pl-v">this</span>.<span class="pl-smi">props</span>.<span class="pl-smi">item</span>.<span class="pl-smi">kids</span>.<span class="pl-c1">length</span> <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span> comments<span class="pl-pds">'</span></span>;
    }

    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>a href<span class="pl-k">=</span>{<span class="pl-s"><span class="pl-pds">'</span>https://news.ycombinator.com/item?id=<span class="pl-pds">'</span></span> <span class="pl-k">+</span> <span class="pl-v">this</span>.<span class="pl-smi">props</span>.<span class="pl-smi">item</span>.<span class="pl-c1">id</span>}<span class="pl-k">&gt;</span>{commentText}<span class="pl-k">&lt;</span><span class="pl-k">/</span>a<span class="pl-k">&gt;</span>
    );
  },

  <span class="pl-en">getSubtext</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsItem-subtext<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
        {<span class="pl-v">this</span>.<span class="pl-smi">props</span>.<span class="pl-smi">item</span>.<span class="pl-smi">score</span>} points by <span class="pl-k">&lt;</span>a href<span class="pl-k">=</span>{<span class="pl-s"><span class="pl-pds">'</span>https://news.ycombinator.com/user?id=<span class="pl-pds">'</span></span> <span class="pl-k">+</span> <span class="pl-v">this</span>.<span class="pl-smi">props</span>.<span class="pl-smi">item</span>.<span class="pl-smi">by</span>}<span class="pl-k">&gt;</span>{<span class="pl-v">this</span>.<span class="pl-smi">props</span>.<span class="pl-smi">item</span>.<span class="pl-smi">by</span>}<span class="pl-k">&lt;</span><span class="pl-k">/</span>a<span class="pl-k">&gt;</span> {<span class="pl-smi">moment</span>.<span class="pl-en">utc</span>(<span class="pl-v">this</span>.<span class="pl-smi">props</span>.<span class="pl-smi">item</span>.<span class="pl-smi">time</span> <span class="pl-k">*</span> <span class="pl-c1">1000</span>).<span class="pl-en">fromNow</span>()} <span class="pl-k">|</span> {<span class="pl-v">this</span>.<span class="pl-en">getCommentLink</span>()}
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  },

  <span class="pl-en">getTitle</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsItem-title<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
        <span class="pl-k">...</span>
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  },

  <span class="pl-en">render</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsItem<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
        {<span class="pl-v">this</span>.<span class="pl-en">getTitle</span>()}
        {<span class="pl-v">this</span>.<span class="pl-en">getSubtext</span>()}
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  }</pre></div></li>
<li><p>Update the CSS.</p>

<div class="highlight highlight-source-css"><pre><span class="pl-e">.newsItem-subtext</span> {
  <span class="pl-c1"><span class="pl-c1">font-size</span></span>: <span class="pl-c1">7<span class="pl-k">pt</span></span>;
}

<span class="pl-e">.newsItem-subtext</span> &gt; <span class="pl-ent">a</span> {
  <span class="pl-c1"><span class="pl-c1">color</span></span>: <span class="pl-c1">#828282</span>;
  <span class="pl-c1"><span class="pl-c1">text-decoration</span></span>: <span class="pl-c1">none</span>;
}

<span class="pl-e">.newsItem-subtext</span> &gt; <span class="pl-ent">a</span><span class="pl-e">:hover</span> {
  <span class="pl-c1"><span class="pl-c1">text-decoration</span></span>: <span class="pl-c1">underline</span>;
}</pre></div></li>
<li><p>Refresh the browser. You should see the following.</p>

<p><a href="/mking/react-hn/blob/master/img/NewsItemSubtext.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsItemSubtext.png" width="268" style="max-width:100%;"></a></p></li>
</ol>

<p><a href="#newsitem-domain">Previous</a> · <a href="#newsitem-rank-and-vote">Next</a></p>

<hr>

<h2><a id="user-content-newsitem-rank-and-vote" class="anchor" href="#newsitem-rank-and-vote" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>NewsItem Rank and Vote</h2>

<ol>
<li><p>Update the JS.</p>

<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> NewsItem <span class="pl-k">=</span> <span class="pl-smi">React</span>.<span class="pl-en">createClass</span>({
  <span class="pl-c">// ...</span>

  <span class="pl-en">getRank</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsItem-rank<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
        {<span class="pl-v">this</span>.<span class="pl-smi">props</span>.<span class="pl-smi">rank</span>}.
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  },

  <span class="pl-en">getVote</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsItem-vote<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
        <span class="pl-k">&lt;</span>a href<span class="pl-k">=</span>{<span class="pl-s"><span class="pl-pds">'</span>https://news.ycombinator.com/vote?for=<span class="pl-pds">'</span></span> <span class="pl-k">+</span> <span class="pl-v">this</span>.<span class="pl-smi">props</span>.<span class="pl-smi">item</span>.<span class="pl-c1">id</span> <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span>&amp;dir=up&amp;whence=news<span class="pl-pds">'</span></span>}<span class="pl-k">&gt;</span>
          <span class="pl-k">&lt;</span>img src<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>../img/grayarrow2x.gif<span class="pl-pds">"</span></span> width<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>10<span class="pl-pds">"</span></span><span class="pl-k">/</span><span class="pl-k">&gt;</span>
        <span class="pl-k">&lt;</span><span class="pl-k">/</span>a<span class="pl-k">&gt;</span>
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  },

  <span class="pl-en">render</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsItem<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
        {<span class="pl-v">this</span>.<span class="pl-en">getRank</span>()}
        {<span class="pl-v">this</span>.<span class="pl-en">getVote</span>()}
        <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsItem-itemText<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
          {<span class="pl-v">this</span>.<span class="pl-en">getTitle</span>()}
          {<span class="pl-v">this</span>.<span class="pl-en">getSubtext</span>()}
        <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  }</pre></div></li>
<li><p>Update the CSS.</p>

<div class="highlight highlight-source-css"><pre><span class="pl-e">.newsItem</span> {
  <span class="pl-c">/* ... */</span>
  <span class="pl-c1"><span class="pl-c1">align</span>-items</span>: <span class="pl-c1">baseline</span>;
  <span class="pl-c1"><span class="pl-c1">display</span></span>: flex;  
}

<span class="pl-e">.newsItem-itemText</span> {
  <span class="pl-c1"><span class="pl-c1">flex</span>-grow</span>: <span class="pl-c1">1</span>;
}

<span class="pl-e">.newsItem-rank</span> {
  <span class="pl-c1"><span class="pl-c1">flex</span>-basis</span>: <span class="pl-c1">25<span class="pl-k">px</span></span>;
  <span class="pl-c1"><span class="pl-c1">font-size</span></span>: <span class="pl-c1">10<span class="pl-k">pt</span></span>;
  <span class="pl-c1"><span class="pl-c1">text-align</span></span>: <span class="pl-c1">right</span>;
}

<span class="pl-e">.newsItem-vote</span> {
  <span class="pl-c1"><span class="pl-c1">flex</span>-basis</span>: <span class="pl-c1">15<span class="pl-k">px</span></span>;
  <span class="pl-c1"><span class="pl-c1">text-align</span></span>: <span class="pl-c1">center</span>;
}</pre></div></li>
<li><p>Refresh the browser. You should see the following.</p>

<p><a href="/mking/react-hn/blob/master/img/NewsItemRankVote.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsItemRankVote.png" width="297" style="max-width:100%;"></a></p>

<p>You have now implemented an HN news item in React.</p>

<p><a href="/mking/react-hn/blob/master/img/NewsItem@2x.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsItem@2x.png" width="532" style="max-width:100%;"></a></p></li>
</ol>

<p><a href="#newsitem-subtext">Previous</a> · <a href="#newsheader">Next</a></p>

<hr>

<h2><a id="user-content-newsheader" class="anchor" href="#newsheader" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>NewsHeader</h2>

<ol>
<li><p><a href="#newsheader-logo-and-title">Display the logo and title.</a></p>

<p><a href="/mking/react-hn/blob/master/img/NewsHeaderLogoTitle.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsHeaderLogoTitle.png" width="140" style="max-width:100%;"></a></p></li>
<li><p><a href="#newsheader-nav">Add the nav links.</a></p>

<p><a href="/mking/react-hn/blob/master/img/NewsHeaderNav.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsHeaderNav.png" width="453" style="max-width:100%;"></a></p></li>
<li><p><a href="#newsheader-login">Add the login link.</a></p>

<p><a href="/mking/react-hn/blob/master/img/NewsHeaderLogin.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsHeaderLogin.png" width="530" style="max-width:100%;"></a></p></li>
</ol>

<p><a href="#newsitem-rank-and-vote">Previous</a> · <a href="#newsheader-logo-and-title">Next</a></p>

<hr>

<h2><a id="user-content-newsheader-logo-and-title" class="anchor" href="#newsheader-logo-and-title" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>NewsHeader Logo and Title</h2>

<ol>
<li><p>Create a new JS file: /js/NewsHeader.js.</p>

<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> $ <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>jquery<span class="pl-pds">'</span></span>);
<span class="pl-k">var</span> React <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>react<span class="pl-pds">'</span></span>);

<span class="pl-k">var</span> NewsHeader <span class="pl-k">=</span> <span class="pl-smi">React</span>.<span class="pl-en">createClass</span>({
  <span class="pl-en">getLogo</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsHeader-logo<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
        <span class="pl-k">&lt;</span>a href<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>https://www.ycombinator.com<span class="pl-pds">"</span></span><span class="pl-k">&gt;&lt;</span>img src<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>../img/y18.gif<span class="pl-pds">"</span></span><span class="pl-k">/</span><span class="pl-k">&gt;&lt;</span><span class="pl-k">/</span>a<span class="pl-k">&gt;</span>
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  },

  <span class="pl-en">getTitle</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsHeader-title<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
        <span class="pl-k">&lt;</span>a className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsHeader-textLink<span class="pl-pds">"</span></span> href<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>https://news.ycombinator.com<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>Hacker News<span class="pl-k">&lt;</span><span class="pl-k">/</span>a<span class="pl-k">&gt;</span>
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  },

  <span class="pl-en">render</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsHeader<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
        {<span class="pl-v">this</span>.<span class="pl-en">getLogo</span>()}
        {<span class="pl-v">this</span>.<span class="pl-en">getTitle</span>()}
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  }
});

<span class="pl-c1">module</span>.<span class="pl-smi">exports</span> <span class="pl-k">=</span> NewsHeader;</pre></div></li>
<li><p>Create a new JS file: /js/NewsHeaderTest.js.</p>

<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> $ <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>jquery<span class="pl-pds">'</span></span>);
<span class="pl-k">var</span> NewsHeader <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>./NewsHeader<span class="pl-pds">'</span></span>);
<span class="pl-k">var</span> React <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>react<span class="pl-pds">'</span></span>);

<span class="pl-smi">React</span>.<span class="pl-en">render</span>(<span class="pl-k">&lt;</span>NewsHeader<span class="pl-k">/</span><span class="pl-k">&gt;</span>, <span class="pl-en">$</span>(<span class="pl-s"><span class="pl-pds">'</span>#content<span class="pl-pds">'</span></span>)[<span class="pl-c1">0</span>]);</pre></div></li>
<li><p>Create a new CSS file: /css/NewsHeader.css.</p>

<div class="highlight highlight-source-css"><pre><span class="pl-e">.newsHeader</span> {
  <span class="pl-c1"><span class="pl-c1">align</span>-items</span>: <span class="pl-c1">center</span>;
  <span class="pl-c1"><span class="pl-c1">background</span></span>: <span class="pl-c1">#ff6600</span>;
  <span class="pl-c1"><span class="pl-c1">color</span></span>: <span class="pl-c1">black</span>;
  <span class="pl-c1"><span class="pl-c1">display</span></span>: flex;
  <span class="pl-c1"><span class="pl-c1">font-size</span></span>: <span class="pl-c1">10<span class="pl-k">pt</span></span>;
  <span class="pl-c1"><span class="pl-c1">padding</span></span>: <span class="pl-c1">2<span class="pl-k">px</span></span>;
}

<span class="pl-e">.newsHeader-logo</span> {
  <span class="pl-c1"><span class="pl-c1">border</span></span>: <span class="pl-c1">1<span class="pl-k">px</span></span> <span class="pl-c1">solid</span> <span class="pl-c1">white</span>;
  <span class="pl-c1"><span class="pl-c1">flex</span>-basis</span>: <span class="pl-c1">18<span class="pl-k">px</span></span>;
  <span class="pl-c1"><span class="pl-c1">height</span></span>: <span class="pl-c1">18<span class="pl-k">px</span></span>;
}

<span class="pl-e">.newsHeader-textLink</span> {
  <span class="pl-c1"><span class="pl-c1">color</span></span>: <span class="pl-c1">black</span>;
  <span class="pl-c1"><span class="pl-c1">text-decoration</span></span>: <span class="pl-c1">none</span>;
}

<span class="pl-e">.newsHeader-title</span> {
  <span class="pl-c1"><span class="pl-c1">font-weight</span></span>: <span class="pl-c1">bold</span>;
  <span class="pl-c1"><span class="pl-c1">margin-left</span></span>: <span class="pl-c1">4<span class="pl-k">px</span></span>;
}</pre></div></li>
<li><p>Create a new HTML file: /html/NewsHeader.html.</p>

<div class="highlight highlight-text-html-basic"><pre>&lt;!DOCTYPE html&gt;
&lt;<span class="pl-ent">html</span>&gt;
  &lt;<span class="pl-ent">head</span>&gt;
    &lt;<span class="pl-ent">meta</span> <span class="pl-e">charset</span>=<span class="pl-s"><span class="pl-pds">"</span>utf-8<span class="pl-pds">"</span></span>&gt;
    &lt;<span class="pl-ent">title</span>&gt;NewsHeader&lt;/<span class="pl-ent">title</span>&gt;
    &lt;<span class="pl-ent">link</span> <span class="pl-e">href</span>=<span class="pl-s"><span class="pl-pds">"</span>../css/NewsHeader.css<span class="pl-pds">"</span></span> <span class="pl-e">rel</span>=<span class="pl-s"><span class="pl-pds">"</span>stylesheet<span class="pl-pds">"</span></span>&gt;
    &lt;<span class="pl-ent">link</span> <span class="pl-e">href</span>=<span class="pl-s"><span class="pl-pds">"</span>../css/app.css<span class="pl-pds">"</span></span> <span class="pl-e">rel</span>=<span class="pl-s"><span class="pl-pds">"</span>stylesheet<span class="pl-pds">"</span></span>&gt;
  &lt;/<span class="pl-ent">head</span>&gt;
  &lt;<span class="pl-ent">body</span>&gt;
    &lt;<span class="pl-ent">div</span> <span class="pl-e">id</span>=<span class="pl-s"><span class="pl-pds">"</span>content<span class="pl-pds">"</span></span>&gt;&lt;/<span class="pl-ent">div</span>&gt;
<span class="pl-s1">    &lt;<span class="pl-ent">script</span> <span class="pl-e">src</span>=<span class="pl-s"><span class="pl-pds">"</span>../build/js/NewsHeaderTest.js<span class="pl-pds">"</span></span>&gt;&lt;/<span class="pl-ent">script</span>&gt;</span>
  &lt;/<span class="pl-ent">body</span>&gt;
&lt;/<span class="pl-ent">html</span>&gt;</pre></div></li>
<li><p>Start Watchify.</p>

<div class="highlight highlight-source-shell"><pre>watchify -v -o build/js/NewsHeaderTest.js js/NewsHeaderTest.js</pre></div></li>
<li><p>Start the HTTP server if necessary.</p>

<div class="highlight highlight-source-shell"><pre>http-server -p 8888</pre></div></li>
<li><p>Visit <a href="http://localhost:8888/html/NewsHeader.html">http://localhost:8888/html/NewsHeader.html</a>. You should see the following.</p>

<p><a href="/mking/react-hn/blob/master/img/NewsHeaderLogoTitle.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsHeaderLogoTitle.png" width="140" style="max-width:100%;"></a></p></li>
</ol>

<p><a href="#newsheader">Previous</a> · <a href="#newsheader-nav">Next</a></p>

<hr>

<h2><a id="user-content-newsheader-nav" class="anchor" href="#newsheader-nav" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>NewsHeader Nav</h2>

<ol>
<li><p>Update the JS.</p>

<div class="highlight highlight-source-js"><pre><span class="pl-c">// ...</span>
<span class="pl-k">var</span> _ <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>lodash<span class="pl-pds">'</span></span>);

<span class="pl-k">var</span> NewsHeader <span class="pl-k">=</span> <span class="pl-smi">React</span>.<span class="pl-en">createClass</span>({
  <span class="pl-c">// ...</span>

  <span class="pl-en">getNav</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">var</span> navLinks <span class="pl-k">=</span> [
      {
        name<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>new<span class="pl-pds">'</span></span>,
        url<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>newest<span class="pl-pds">'</span></span>
      },
      {
        name<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>comments<span class="pl-pds">'</span></span>,
        url<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>newcomments<span class="pl-pds">'</span></span>
      },
      {
        name<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>show<span class="pl-pds">'</span></span>,
        url<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>show<span class="pl-pds">'</span></span>
      },
      {
        name<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>ask<span class="pl-pds">'</span></span>,
        url<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>ask<span class="pl-pds">'</span></span>
      },
      {
        name<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>jobs<span class="pl-pds">'</span></span>,
        url<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>jobs<span class="pl-pds">'</span></span>
      },
      {
        name<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>submit<span class="pl-pds">'</span></span>,
        url<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>submit<span class="pl-pds">'</span></span>
      }
    ];

    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsHeader-nav<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
        {<span class="pl-en">_</span>(navLinks).<span class="pl-en">map</span>(<span class="pl-k">function</span> (<span class="pl-smi">navLink</span>) {
          <span class="pl-k">return</span> (
            <span class="pl-k">&lt;</span>a key<span class="pl-k">=</span>{<span class="pl-smi">navLink</span>.<span class="pl-smi">url</span>} className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsHeader-navLink newsHeader-textLink<span class="pl-pds">"</span></span> href<span class="pl-k">=</span>{<span class="pl-s"><span class="pl-pds">'</span>https://news.ycombinator.com/<span class="pl-pds">'</span></span> <span class="pl-k">+</span> <span class="pl-smi">navLink</span>.<span class="pl-smi">url</span>}<span class="pl-k">&gt;</span>
              {<span class="pl-smi">navLink</span>.<span class="pl-c1">name</span>}
            <span class="pl-k">&lt;</span><span class="pl-k">/</span>a<span class="pl-k">&gt;</span>
          );
        }).<span class="pl-c1">value</span>()}
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  },

  <span class="pl-en">render</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsHeader<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
        <span class="pl-k">...</span>
        {<span class="pl-v">this</span>.<span class="pl-en">getNav</span>()}
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  }</pre></div></li>
<li><p>Update the CSS.</p>

<div class="highlight highlight-source-css"><pre><span class="pl-e">.newsHeader-nav</span> {
  <span class="pl-c1"><span class="pl-c1">flex</span>-grow</span>: <span class="pl-c1">1</span>;
  <span class="pl-c1"><span class="pl-c1">margin-left</span></span>: <span class="pl-c1">10<span class="pl-k">px</span></span>;
}

<span class="pl-e">.newsHeader-navLink</span><span class="pl-e">:not</span>(<span class="pl-e">:first-child</span>)<span class="pl-e">::before</span> {
  <span class="pl-c1"><span class="pl-c1">content</span></span>: <span class="pl-s"><span class="pl-pds">'</span> | <span class="pl-pds">'</span></span>;
}</pre></div></li>
<li><p>Refresh the browser. You should see the following.</p>

<p><a href="/mking/react-hn/blob/master/img/NewsHeaderNav.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsHeaderNav.png" width="453" style="max-width:100%;"></a></p></li>
</ol>

<p><a href="#newsheader-logo-and-title">Previous</a> · <a href="#newsheader-login">Next</a></p>

<hr>

<h2><a id="user-content-newsheader-login" class="anchor" href="#newsheader-login" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>NewsHeader Login</h2>

<ol>
<li><p>Update the JS.</p>

<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> NewsHeader <span class="pl-k">=</span> <span class="pl-smi">React</span>.<span class="pl-en">createClass</span>({
  <span class="pl-c">// ...</span>

  <span class="pl-en">getLogin</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsHeader-login<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
        <span class="pl-k">&lt;</span>a className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsHeader-textLink<span class="pl-pds">"</span></span> href<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>https://news.ycombinator.com/login?whence=news<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>login<span class="pl-k">&lt;</span><span class="pl-k">/</span>a<span class="pl-k">&gt;</span>
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  },

  <span class="pl-en">render</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsHeader<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
        <span class="pl-k">...</span>
        {<span class="pl-v">this</span>.<span class="pl-en">getLogin</span>()}
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  }</pre></div></li>
<li><p>Update the CSS.</p>

<div class="highlight highlight-source-css"><pre><span class="pl-e">.newsHeader-login</span> {
  <span class="pl-c1"><span class="pl-c1">margin-right</span></span>: <span class="pl-c1">5<span class="pl-k">px</span></span>;
}</pre></div></li>
<li><p>Refresh the browser. You should see the following.</p>

<p><a href="/mking/react-hn/blob/master/img/NewsHeaderLogin.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsHeaderLogin.png" width="530" style="max-width:100%;"></a></p>

<p>You have now implemented the HN header in React.</p>

<p><a href="/mking/react-hn/blob/master/img/NewsHeader@2x.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsHeader@2x.png" width="532" style="max-width:100%;"></a></p></li>
</ol>

<p><a href="#newsheader-nav">Previous</a> · <a href="#newslist">Next</a></p>

<hr>

<h2><a id="user-content-newslist" class="anchor" href="#newslist" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>NewsList</h2>

<ol>
<li><p><a href="#newslist-header-and-items">Display the header and items.</a></p>

<p><a href="/mking/react-hn/blob/master/img/NewsListHeaderItems.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsListHeaderItems.png" width="270" style="max-width:100%;"></a></p></li>
<li><p><a href="#newslist-more">Add the more link.</a></p>

<p><a href="/mking/react-hn/blob/master/img/NewsListMore.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsListMore.png" width="136" style="max-width:100%;"></a></p></li>
</ol>

<p><a href="#newsheader-login">Previous</a> · <a href="#newslist-header-and-items">Next</a></p>

<hr>

<h2><a id="user-content-newslist-header-and-items" class="anchor" href="#newslist-header-and-items" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>NewsList Header and Items</h2>

<ol>
<li><p>Create a new JS file: /js/NewsList.js.</p>

<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> _ <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>lodash<span class="pl-pds">'</span></span>);
<span class="pl-k">var</span> NewsHeader <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>./NewsHeader<span class="pl-pds">'</span></span>);
<span class="pl-k">var</span> NewsItem <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>./NewsItem<span class="pl-pds">'</span></span>);
<span class="pl-k">var</span> React <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>react<span class="pl-pds">'</span></span>);

<span class="pl-k">var</span> NewsList <span class="pl-k">=</span> <span class="pl-smi">React</span>.<span class="pl-en">createClass</span>({
  <span class="pl-en">render</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsList<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
        <span class="pl-k">&lt;</span>NewsHeader<span class="pl-k">/</span><span class="pl-k">&gt;</span>
        <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsList-newsItems<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
          {<span class="pl-en">_</span>(<span class="pl-v">this</span>.<span class="pl-smi">props</span>.<span class="pl-smi">items</span>).<span class="pl-en">map</span>(<span class="pl-k">function</span> (<span class="pl-smi">item</span>, <span class="pl-smi">index</span>) {
            <span class="pl-k">return</span> <span class="pl-k">&lt;</span>NewsItem key<span class="pl-k">=</span>{<span class="pl-smi">item</span>.<span class="pl-c1">id</span>} item<span class="pl-k">=</span>{item} rank<span class="pl-k">=</span>{index <span class="pl-k">+</span> <span class="pl-c1">1</span>}<span class="pl-k">/</span><span class="pl-k">&gt;</span>;
          }.<span class="pl-en">bind</span>(<span class="pl-v">this</span>)).<span class="pl-c1">value</span>()}
        <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  }
});

<span class="pl-c1">module</span>.<span class="pl-smi">exports</span> <span class="pl-k">=</span> NewsList;</pre></div></li>
<li><p>Create a new JS file: /js/NewsListTest.js.</p>

<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> $ <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>jquery<span class="pl-pds">'</span></span>);
<span class="pl-k">var</span> NewsList <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>./NewsList<span class="pl-pds">'</span></span>);
<span class="pl-k">var</span> React <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>react<span class="pl-pds">'</span></span>);

<span class="pl-smi">$</span>.<span class="pl-en">ajax</span>({
  url<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>/json/items.json<span class="pl-pds">'</span></span>
}).<span class="pl-en">then</span>(<span class="pl-k">function</span> (<span class="pl-smi">items</span>) {
  <span class="pl-smi">React</span>.<span class="pl-en">render</span>(<span class="pl-k">&lt;</span>NewsList items<span class="pl-k">=</span>{items}<span class="pl-k">/</span><span class="pl-k">&gt;</span>, <span class="pl-en">$</span>(<span class="pl-s"><span class="pl-pds">'</span>#content<span class="pl-pds">'</span></span>)[<span class="pl-c1">0</span>]);
});</pre></div></li>
<li><p>Create a new CSS file: /css/NewsList.css.</p>

<div class="highlight highlight-source-css"><pre><span class="pl-e">.newsList</span> {
  <span class="pl-c1"><span class="pl-c1">background</span></span>: <span class="pl-c1">#f6f6ef</span>;
  <span class="pl-c1"><span class="pl-c1">margin-left</span></span>: <span class="pl-c1">auto</span>;
  <span class="pl-c1"><span class="pl-c1">margin-right</span></span>: <span class="pl-c1">auto</span>;
  <span class="pl-c1"><span class="pl-c1">width</span></span>: <span class="pl-c1">85<span class="pl-k">%</span></span>;
}</pre></div></li>
<li><p>Create a new HTML file: /html/NewsList.html.</p>

<div class="highlight highlight-text-html-basic"><pre>&lt;!DOCTYPE html&gt;
&lt;<span class="pl-ent">html</span>&gt;
  &lt;<span class="pl-ent">head</span>&gt;
    &lt;<span class="pl-ent">meta</span> <span class="pl-e">charset</span>=<span class="pl-s"><span class="pl-pds">"</span>utf-8<span class="pl-pds">"</span></span>&gt;
    &lt;<span class="pl-ent">title</span>&gt;NewsList&lt;/<span class="pl-ent">title</span>&gt;
    &lt;<span class="pl-ent">link</span> <span class="pl-e">href</span>=<span class="pl-s"><span class="pl-pds">"</span>../css/NewsHeader.css<span class="pl-pds">"</span></span> <span class="pl-e">rel</span>=<span class="pl-s"><span class="pl-pds">"</span>stylesheet<span class="pl-pds">"</span></span>&gt;
    &lt;<span class="pl-ent">link</span> <span class="pl-e">href</span>=<span class="pl-s"><span class="pl-pds">"</span>../css/NewsItem.css<span class="pl-pds">"</span></span> <span class="pl-e">rel</span>=<span class="pl-s"><span class="pl-pds">"</span>stylesheet<span class="pl-pds">"</span></span>&gt;
    &lt;<span class="pl-ent">link</span> <span class="pl-e">href</span>=<span class="pl-s"><span class="pl-pds">"</span>../css/NewsList.css<span class="pl-pds">"</span></span> <span class="pl-e">rel</span>=<span class="pl-s"><span class="pl-pds">"</span>stylesheet<span class="pl-pds">"</span></span>&gt;
    &lt;<span class="pl-ent">link</span> <span class="pl-e">href</span>=<span class="pl-s"><span class="pl-pds">"</span>../css/app.css<span class="pl-pds">"</span></span> <span class="pl-e">rel</span>=<span class="pl-s"><span class="pl-pds">"</span>stylesheet<span class="pl-pds">"</span></span>&gt;
  &lt;/<span class="pl-ent">head</span>&gt;
  &lt;<span class="pl-ent">body</span>&gt;
    &lt;<span class="pl-ent">div</span> <span class="pl-e">id</span>=<span class="pl-s"><span class="pl-pds">"</span>content<span class="pl-pds">"</span></span>&gt;&lt;/<span class="pl-ent">div</span>&gt;
<span class="pl-s1">    &lt;<span class="pl-ent">script</span> <span class="pl-e">src</span>=<span class="pl-s"><span class="pl-pds">"</span>../build/js/NewsListTest.js<span class="pl-pds">"</span></span>&gt;&lt;/<span class="pl-ent">script</span>&gt;</span>
  &lt;/<span class="pl-ent">body</span>&gt;
&lt;/<span class="pl-ent">html</span>&gt;</pre></div></li>
<li><p>Start Watchify.</p>

<div class="highlight highlight-source-shell"><pre>watchify -v -o build/js/NewsListTest.js js/NewsListTest.js</pre></div></li>
<li><p>Start the HTTP server if necessary.</p>

<div class="highlight highlight-source-shell"><pre>http-server -p 8888</pre></div></li>
<li><p>Visit <a href="http://localhost:8888/html/NewsList.html">http://localhost:8888/html/NewsList.html</a>. You should see the following.</p>

<p><a href="/mking/react-hn/blob/master/img/NewsListHeaderItems.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsListHeaderItems.png" width="270" style="max-width:100%;"></a></p></li>
</ol>

<p><a href="#newslist">Previous</a> · <a href="#newslist-more">Next</a></p>

<hr>

<h2><a id="user-content-newslist-more" class="anchor" href="#newslist-more" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>NewsList More</h2>

<ol>
<li><p>Update the JS.</p>

<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> NewsList <span class="pl-k">=</span> <span class="pl-smi">React</span>.<span class="pl-en">createClass</span>({
  <span class="pl-c">// ...</span>

  <span class="pl-en">getMore</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsList-more<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
        <span class="pl-k">&lt;</span>a className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsList-moreLink<span class="pl-pds">"</span></span> href<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>https://news.ycombinator.com/news?p=2<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>More<span class="pl-k">&lt;</span><span class="pl-k">/</span>a<span class="pl-k">&gt;</span>
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  },

  <span class="pl-en">render</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>newsList<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
        <span class="pl-k">...</span>
        {<span class="pl-v">this</span>.<span class="pl-en">getMore</span>()}
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  }</pre></div></li>
<li><p>Update the CSS.</p>

<div class="highlight highlight-source-css"><pre><span class="pl-e">.newsList-more</span> {
  <span class="pl-c1"><span class="pl-c1">margin-left</span></span>: <span class="pl-c1">40<span class="pl-k">px</span></span>; <span class="pl-c">/* matches NewsItem rank and vote */</span>
  <span class="pl-c1"><span class="pl-c1">margin-top</span></span>: <span class="pl-c1">10<span class="pl-k">px</span></span>;
  <span class="pl-c1"><span class="pl-c1">padding-bottom</span></span>: <span class="pl-c1">10<span class="pl-k">px</span></span>;
}

<span class="pl-e">.newsList-moreLink</span> {
  <span class="pl-c1"><span class="pl-c1">color</span></span>: <span class="pl-c1">black</span>;
  <span class="pl-c1"><span class="pl-c1">font-size</span></span>: <span class="pl-c1">10<span class="pl-k">pt</span></span>;
  <span class="pl-c1"><span class="pl-c1">text-decoration</span></span>: <span class="pl-c1">none</span>;
}</pre></div></li>
<li><p>Refresh the browser. You should see the following.</p>

<p><a href="/mking/react-hn/blob/master/img/NewsListMore.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsListMore.png" width="136" style="max-width:100%;"></a></p>

<p>You have now implemented the HN item list in React.</p>

<p><a href="/mking/react-hn/blob/master/img/NewsList@2x.png" target="_blank"><img src="/mking/react-hn/raw/master/img/NewsList@2x.png" width="532" style="max-width:100%;"></a></p></li>
</ol>

<p><a href="#newslist-header-and-items">Previous</a> · <a href="#hacker-news-api">Next</a></p>

<hr>

<h2><a id="user-content-hacker-news-api" class="anchor" href="#hacker-news-api" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>Hacker News API</h2>

<ol>
<li><p>Create a new JS file: /js/app.js.</p>

<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> _ <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>lodash<span class="pl-pds">'</span></span>);
<span class="pl-k">var</span> $ <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>jquery<span class="pl-pds">'</span></span>);
<span class="pl-k">var</span> NewsList <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>./NewsList<span class="pl-pds">'</span></span>);
<span class="pl-k">var</span> React <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>react<span class="pl-pds">'</span></span>);

<span class="pl-c">// Get the top item ids</span>
<span class="pl-smi">$</span>.<span class="pl-en">ajax</span>({
  url<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>https://hacker-news.firebaseio.com/v0/topstories.json<span class="pl-pds">'</span></span>,
  dataType<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>json<span class="pl-pds">'</span></span>
}).<span class="pl-en">then</span>(<span class="pl-k">function</span> (<span class="pl-smi">stories</span>) {
  <span class="pl-c">// Get the item details in parallel</span>
  <span class="pl-k">var</span> detailDeferreds <span class="pl-k">=</span> <span class="pl-en">_</span>(<span class="pl-smi">stories</span>.<span class="pl-c1">slice</span>(<span class="pl-c1">0</span>, <span class="pl-c1">30</span>)).<span class="pl-en">map</span>(<span class="pl-k">function</span> (<span class="pl-smi">itemId</span>) {
    <span class="pl-k">return</span> <span class="pl-smi">$</span>.<span class="pl-en">ajax</span>({
      url<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>https://hacker-news.firebaseio.com/v0/item/<span class="pl-pds">'</span></span> <span class="pl-k">+</span> itemId <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span>.json<span class="pl-pds">'</span></span>,
      dataType<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>json<span class="pl-pds">'</span></span>
    });
  }).<span class="pl-c1">value</span>();
  <span class="pl-k">return</span> <span class="pl-smi">$</span>.<span class="pl-smi">when</span>.<span class="pl-c1">apply</span>($, detailDeferreds);
}).<span class="pl-en">then</span>(<span class="pl-k">function</span> () {
  <span class="pl-c">// Extract the response JSON</span>
  <span class="pl-k">var</span> items <span class="pl-k">=</span> <span class="pl-en">_</span>(<span class="pl-v">arguments</span>).<span class="pl-en">map</span>(<span class="pl-k">function</span> (<span class="pl-smi">argument</span>) {
    <span class="pl-k">return</span> argument[<span class="pl-c1">0</span>];
  }).<span class="pl-c1">value</span>();

  <span class="pl-c">// Render the items</span>
  <span class="pl-smi">React</span>.<span class="pl-en">render</span>(<span class="pl-k">&lt;</span>NewsList items<span class="pl-k">=</span>{items}<span class="pl-k">/</span><span class="pl-k">&gt;</span>, <span class="pl-en">$</span>(<span class="pl-s"><span class="pl-pds">'</span>#content<span class="pl-pds">'</span></span>)[<span class="pl-c1">0</span>]);
});
</pre></div></li>
<li><p>Create a new HTML file: /html/app.html.</p>

<div class="highlight highlight-text-html-basic"><pre>&lt;!DOCTYPE html&gt;
&lt;<span class="pl-ent">html</span>&gt;
  &lt;<span class="pl-ent">head</span>&gt;
    &lt;<span class="pl-ent">meta</span> <span class="pl-e">charset</span>=<span class="pl-s"><span class="pl-pds">"</span>utf-8<span class="pl-pds">"</span></span>&gt;
    &lt;<span class="pl-ent">title</span>&gt;Hacker News&lt;/<span class="pl-ent">title</span>&gt;
    &lt;<span class="pl-ent">link</span> <span class="pl-e">href</span>=<span class="pl-s"><span class="pl-pds">"</span>../css/NewsHeader.css<span class="pl-pds">"</span></span> <span class="pl-e">rel</span>=<span class="pl-s"><span class="pl-pds">"</span>stylesheet<span class="pl-pds">"</span></span>&gt;
    &lt;<span class="pl-ent">link</span> <span class="pl-e">href</span>=<span class="pl-s"><span class="pl-pds">"</span>../css/NewsItem.css<span class="pl-pds">"</span></span> <span class="pl-e">rel</span>=<span class="pl-s"><span class="pl-pds">"</span>stylesheet<span class="pl-pds">"</span></span>&gt;
    &lt;<span class="pl-ent">link</span> <span class="pl-e">href</span>=<span class="pl-s"><span class="pl-pds">"</span>../css/NewsList.css<span class="pl-pds">"</span></span> <span class="pl-e">rel</span>=<span class="pl-s"><span class="pl-pds">"</span>stylesheet<span class="pl-pds">"</span></span>&gt;
    &lt;<span class="pl-ent">link</span> <span class="pl-e">href</span>=<span class="pl-s"><span class="pl-pds">"</span>../css/app.css<span class="pl-pds">"</span></span> <span class="pl-e">rel</span>=<span class="pl-s"><span class="pl-pds">"</span>stylesheet<span class="pl-pds">"</span></span>&gt;
  &lt;/<span class="pl-ent">head</span>&gt;
  &lt;<span class="pl-ent">body</span>&gt;
    &lt;<span class="pl-ent">div</span> <span class="pl-e">id</span>=<span class="pl-s"><span class="pl-pds">"</span>content<span class="pl-pds">"</span></span>&gt;&lt;/<span class="pl-ent">div</span>&gt;
<span class="pl-s1">    &lt;<span class="pl-ent">script</span> <span class="pl-e">src</span>=<span class="pl-s"><span class="pl-pds">"</span>../build/js/app.js<span class="pl-pds">"</span></span>&gt;&lt;/<span class="pl-ent">script</span>&gt;</span>
  &lt;/<span class="pl-ent">body</span>&gt;
&lt;/<span class="pl-ent">html</span>&gt;</pre></div></li>
<li><p>Start Watchify.</p>

<div class="highlight highlight-source-shell"><pre>watchify -v -o build/js/app.js js/app.js</pre></div></li>
<li><p>Start the HTTP server if necessary.</p>

<div class="highlight highlight-source-shell"><pre>http-server -p 8888</pre></div></li>
<li><p>Visit <a href="http://localhost:8888/html/app.html">http://localhost:8888/html/app.html</a>.</p>

<p>You have now implemented the <a href="https://news.ycombinator.com">HN front page</a> in React.</p></li>
</ol>

<p><a href="#newslist-more">Previous</a></p>
</article>
  </div>

</div>

<button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="hidden">Jump to Line</button>
<div id="jump-to-line" style="display:none">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

  </div>
  <div class="modal-backdrop"></div>
</div>


    </div>
  </div>

    </div>

        <div class="container site-footer-container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage" class="site-footer-mark" title="GitHub">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59 0.4 0.07 0.55-0.17 0.55-0.38 0-0.19-0.01-0.82-0.01-1.49-2.01 0.37-2.53-0.49-2.69-0.94-0.09-0.23-0.48-0.94-0.82-1.13-0.28-0.15-0.68-0.52-0.01-0.53 0.63-0.01 1.08 0.58 1.23 0.82 0.72 1.21 1.87 0.87 2.33 0.66 0.07-0.52 0.28-0.87 0.51-1.07-1.78-0.2-3.64-0.89-3.64-3.95 0-0.87 0.31-1.59 0.82-2.15-0.08-0.2-0.36-1.02 0.08-2.12 0 0 0.67-0.21 2.2 0.82 0.64-0.18 1.32-0.27 2-0.27 0.68 0 1.36 0.09 2 0.27 1.53-1.04 2.2-0.82 2.2-0.82 0.44 1.1 0.16 1.92 0.08 2.12 0.51 0.56 0.82 1.27 0.82 2.15 0 3.07-1.87 3.75-3.65 3.95 0.29 0.25 0.54 0.73 0.54 1.48 0 1.07-0.01 1.93-0.01 2.2 0 0.21 0.15 0.46 0.55 0.38C13.71 14.53 16 11.53 16 8 16 3.58 12.42 0 8 0z"></path></svg>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2016 <span title="0.07969s from github-fe137-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>
  </div>
</div>



    
    

    <div id="ajax-error-message" class="ajax-error-message flash flash-error">
      <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M15.72 12.5l-6.85-11.98C8.69 0.21 8.36 0.02 8 0.02s-0.69 0.19-0.87 0.5l-6.85 11.98c-0.18 0.31-0.18 0.69 0 1C0.47 13.81 0.8 14 1.15 14h13.7c0.36 0 0.69-0.19 0.86-0.5S15.89 12.81 15.72 12.5zM9 12H7V10h2V12zM9 9H7V5h2V9z"></path></svg>
      <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
        <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48-3.75-3.75-3.75 3.75-1.48-1.48 3.75-3.75L0.77 4.25l1.48-1.48 3.75 3.75 3.75-3.75 1.48 1.48-3.75 3.75z"></path></svg>
      </button>
      Something went wrong with that request. Please try again.
    </div>


      
      <script crossorigin="anonymous" integrity="sha256-XLbxxvkhG/7tO/x1ltihs8X0u4QdUxhkWgqv/0i1sz0=" src="https://assets-cdn.github.com/assets/frameworks-5cb6f1c6f9211bfeed3bfc7596d8a1b3c5f4bb841d5318645a0aafff48b5b33d.js"></script>
      <script async="async" crossorigin="anonymous" integrity="sha256-lUIPfe4JTvhL6U49gGrVtSN0AAXCoyb6kuEZNfD3TE4=" src="https://assets-cdn.github.com/assets/github-95420f7dee094ef84be94e3d806ad5b523740005c2a326fa92e11935f0f74c4e.js"></script>
      
      
      
      
      
      
    <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner hidden">
      <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M15.72 12.5l-6.85-11.98C8.69 0.21 8.36 0.02 8 0.02s-0.69 0.19-0.87 0.5l-6.85 11.98c-0.18 0.31-0.18 0.69 0 1C0.47 13.81 0.8 14 1.15 14h13.7c0.36 0 0.69-0.19 0.86-0.5S15.89 12.81 15.72 12.5zM9 12H7V10h2V12zM9 9H7V5h2V9z"></path></svg>
      <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
      <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
    </div>
    <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48-3.75-3.75-3.75 3.75-1.48-1.48 3.75-3.75L0.77 4.25l1.48-1.48 3.75 3.75 3.75-3.75 1.48 1.48-3.75 3.75z"></path></svg>
    </button>
  </div>
</div>

  </body>
</html>

