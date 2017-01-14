



<!DOCTYPE html>
<html lang="en" class=" is-u2f-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-c07e6f4b02b556d1d85052fb3853caf84c80e6b23dcdb1ae1b00f051da1115a2.css" integrity="sha256-wH5vSwK1VtHYUFL7OFPK+EyA5rI9zbGuGwDwUdoRFaI=" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-f7908bec66dc71ca22b3075562a80e472f6e9f39ab2bfcb7e5eee9f041237433.css" integrity="sha256-95CL7GbcccoiswdVYqgORy9unzmrK/y35e7p8EEjdDM=" media="all" rel="stylesheet" />
    
    
    
    

    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=device-width">
    
    <title>QwaveSys-RPi-Package_2.0/README.md at master · QWaveSystems/QwaveSys-RPi-Package_2.0</title>
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

      <meta content="https://avatars0.githubusercontent.com/u/12699791?v=3&amp;s=400" name="twitter:image:src" /><meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="QWaveSystems/QwaveSys-RPi-Package_2.0" name="twitter:title" /><meta content="QwaveSys-RPi-Package_2.0 - LabVIEW for Raspberry Pi Package 2.0" name="twitter:description" />
      <meta content="https://avatars0.githubusercontent.com/u/12699791?v=3&amp;s=400" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="QWaveSystems/QwaveSys-RPi-Package_2.0" property="og:title" /><meta content="https://github.com/QWaveSystems/QwaveSys-RPi-Package_2.0" property="og:url" /><meta content="QwaveSys-RPi-Package_2.0 - LabVIEW for Raspberry Pi Package 2.0" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6MTE0NzUzNTAxOjAxNThiNDU0YjI5NzNlNzExNjNkMzhmMDM4NmJkYTIxN2RjMzkwNDgwNDU4YzgxMjYzNWRhNzgwMDU3MDM0ZWM=--ceb0b0e0ae81927c5c779113b31677ba8450e577">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">
    <meta name="request-id" content="DFCD9E7C:6B56:116EAA2B:587A7568" data-pjax-transient>

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
<meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="DFCD9E7C:6B56:116EAA2B:587A7568" name="octolytics-dimension-request_id" /><meta content="12686721" name="octolytics-actor-id" /><meta content="pamornthep" name="octolytics-actor-login" /><meta content="9a39a5c00a4ac6a5d1b7c8694f62da1afc481457378f2e255f52bdfeba9677e8" name="octolytics-actor-hash" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />



  <meta class="js-ga-set" name="dimension1" content="Logged In">



        <meta name="hostname" content="github.com">
    <meta name="user-login" content="pamornthep">

        <meta name="expected-hostname" content="github.com">
      <meta name="js-proxy-site-detection-payload" content="N2MyMGM3YWNjMGRjYTRjZDljODYxMzJiYjQzNjc5YTViYTAyY2I3MzJlODE0N2UzZWY4MDQ3NGY5ZTY0Zjc0N3x7InJlbW90ZV9hZGRyZXNzIjoiMjIzLjIwNS4xNTguMTI0IiwicmVxdWVzdF9pZCI6IkRGQ0Q5RTdDOjZCNTY6MTE2RUFBMkI6NTg3QTc1NjgiLCJ0aW1lc3RhbXAiOjE0ODQ0MjA0NjAsImhvc3QiOiJnaXRodWIuY29tIn0=">


      <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#000000">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

    <meta name="html-safe-nonce" content="407839aec9721b72d5d3bc54b614296244ee7c46">

    <meta http-equiv="x-pjax-version" content="6182178810b65c12b6895178ee61bf5a">
    

      
  <meta name="description" content="QwaveSys-RPi-Package_2.0 - LabVIEW for Raspberry Pi Package 2.0">
  <meta name="go-import" content="github.com/QWaveSystems/QwaveSys-RPi-Package_2.0 git https://github.com/QWaveSystems/QwaveSys-RPi-Package_2.0.git">

  <meta content="12699791" name="octolytics-dimension-user_id" /><meta content="QWaveSystems" name="octolytics-dimension-user_login" /><meta content="78787478" name="octolytics-dimension-repository_id" /><meta content="QWaveSystems/QwaveSys-RPi-Package_2.0" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="78787478" name="octolytics-dimension-repository_network_root_id" /><meta content="QWaveSystems/QwaveSys-RPi-Package_2.0" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/QWaveSystems/QwaveSys-RPi-Package_2.0/commits/master.atom" rel="alternate" title="Recent Commits to QwaveSys-RPi-Package_2.0:master" type="application/atom+xml">


      <link rel="canonical" href="https://github.com/QWaveSystems/QwaveSys-RPi-Package_2.0/blob/master/README.md" data-pjax-transient>
  </head>


  <body class="logged-in  env-production windows vis-public page-blob">
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>

    
    
    



        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg aria-hidden="true" class="octicon octicon-mark-github" height="28" version="1.1" viewBox="0 0 16 16" width="28"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>


        <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/QWaveSystems/QwaveSys-RPi-Package_2.0/search" class="js-site-search-form" data-scoped-search-url="/QWaveSystems/QwaveSys-RPi-Package_2.0/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
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
        autocapitalize="off">
    </label>
</form></div>


      <ul class="header-nav float-left" role="navigation">
        <li class="header-nav-item">
          <a href="/pulls" aria-label="Pull requests you created" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
            Pull requests
</a>        </li>
        <li class="header-nav-item">
          <a href="/issues" aria-label="Issues you created" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
            Issues
</a>        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com/" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>

    
<ul class="header-nav user-nav float-right" id="user-links">
  <li class="header-nav-item">
    
    <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s js-socket-channel js-notification-indicator" data-channel="tenant:1:notification-changed:12686721" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
        <span class="mail-status "></span>
        <svg aria-hidden="true" class="octicon octicon-bell" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 12v1H0v-1l.73-.58c.77-.77.81-2.55 1.19-4.42C2.69 3.23 6 2 6 2c0-.55.45-1 1-1s1 .45 1 1c0 0 3.39 1.23 4.16 5 .38 1.88.42 3.66 1.19 4.42l.66.58H14zm-7 4c1.11 0 2-.89 2-2H5c0 1.11.89 2 2 2z"/></svg>
</a>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <svg aria-hidden="true" class="octicon octicon-plus float-left" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5z"/></svg>
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

<a class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>

  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="QWaveSystems">This organization</span>
  </div>
  <a class="dropdown-item" href="/orgs/QWaveSystems/people#invite-member" data-ga-click="Header, invite someone">
    Invite someone
  </a>
  <a class="dropdown-item" href="/orgs/QWaveSystems/new-team" data-ga-click="Header, create new team">
    New team
  </a>
  <a class="dropdown-item" href="/organizations/QWaveSystems/repositories/new" data-ga-click="Header, create new organization repository, icon:repo">
    New repository
  </a>


  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="QWaveSystems/QwaveSys-RPi-Package_2.0">This repository</span>
  </div>
    <a class="dropdown-item" href="/QWaveSystems/QwaveSys-RPi-Package_2.0/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>
    <a class="dropdown-item" href="/QWaveSystems/QwaveSys-RPi-Package_2.0/settings/collaboration" data-ga-click="Header, create new collaborator">
      New collaborator
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-sw js-menu-target" href="/pamornthep"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@pamornthep" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/12686721?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu dropdown-menu-sw">
        <div class="dropdown-header header-nav-current-user css-truncate">
          Signed in as <strong class="css-truncate-target">pamornthep</strong>
        </div>

        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/pamornthep" data-ga-click="Header, go to profile, text:your profile">
          Your profile
        </a>
        <a class="dropdown-item" href="/pamornthep?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">
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

        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="8D6PsY9yKpl8yBxXC/9HkS3ZxFwMiNOUok87YZo8lqkpZFKSHxks6ezZj0aVtMvbEfOfZ5+8ARV+xjW3lpaSzg==" /></div>
          <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>


      


    <div id="start-of-content" class="accessibility-aid"></div>

      <div id="js-flash-container">
</div>


    <div role="main">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode">
    <div id="js-repo-pjax-container" data-pjax-container>
      
<div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav">
  <div class="container repohead-details-container">

    

<ul class="pagehead-actions">

  <li>
        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="Rmjih8xWtY+dPjgwmy/MUt6a8Qb7tSUfh7eE9e915gnBMXJOfBnlPOG6i7F1ft853ou0IgA8t67Bx6X/wBPVyg==" /></div>      <input class="form-control" id="repository_id" name="repository_id" type="hidden" value="78787478" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/QWaveSystems/QwaveSys-RPi-Package_2.0/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
              <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
              Unwatch
            </span>
          </a>
          <a class="social-count js-social-count"
            href="/QWaveSystems/QwaveSys-RPi-Package_2.0/watchers"
            aria-label="2 users are watching this repository">
            2
          </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header js-navigation-enable" tabindex="-1">
              <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input id="do_included" name="do" type="radio" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input checked="checked" id="do_subscribed" name="do" type="radio" value="subscribed" />
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
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/QWaveSystems/QwaveSys-RPi-Package_2.0/unstar" class="starred" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="75J+mWLBQxUnG6qrDcvMvxmGLG81iry7i10mijgc9Bhz1QDuWcteIDxfOut1bejjzEfHmTLgWvYMJaAEO3+yBQ==" /></div>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar QWaveSystems/QwaveSys-RPi-Package_2.0"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/QWaveSystems/QwaveSys-RPi-Package_2.0/stargazers"
           aria-label="0 users starred this repository">
          0
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/QWaveSystems/QwaveSys-RPi-Package_2.0/star" class="unstarred" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="RtAD6l+9yNRIhwpr56aCOYxHkVIYoweVIPAZf1IQEb1gao7urfElPex2ASfKHFDR8gVE8+Hd/JC5au7b6yBOGg==" /></div>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star QWaveSystems/QwaveSys-RPi-Package_2.0"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
        Star
      </button>
        <a class="social-count js-social-count" href="/QWaveSystems/QwaveSys-RPi-Package_2.0/stargazers"
           aria-label="0 users starred this repository">
          0
        </a>
</form>  </div>

  </li>

  <li>
          <a href="#fork-destination-box" class="btn btn-sm btn-with-count"
              title="Fork your own copy of QWaveSystems/QwaveSys-RPi-Package_2.0 to your account"
              aria-label="Fork your own copy of QWaveSystems/QwaveSys-RPi-Package_2.0 to your account"
              rel="facebox"
              data-ga-click="Repository, show fork modal, action:blob#show; text:Fork">
              <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
            Fork
          </a>

          <div id="fork-destination-box" style="display: none;">
            <h2 class="facebox-header" data-facebox-id="facebox-header">Where should we fork this repository?</h2>
            <include-fragment src=""
                class="js-fork-select-fragment fork-select-fragment"
                data-url="/QWaveSystems/QwaveSys-RPi-Package_2.0/fork?fragment=1">
              <img alt="Loading" height="64" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-128.gif" width="64" />
            </include-fragment>
          </div>

    <a href="/QWaveSystems/QwaveSys-RPi-Package_2.0/network" class="social-count"
       aria-label="0 users forked this repository">
      0
    </a>
  </li>
</ul>

    <h1 class="public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a href="/QWaveSystems" class="url fn" rel="author">QWaveSystems</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/QWaveSystems/QwaveSys-RPi-Package_2.0" data-pjax="#js-repo-pjax-container">QwaveSys-RPi-Package_2.0</a></strong>

</h1>

  </div>
  <div class="container">
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/QWaveSystems/QwaveSys-RPi-Package_2.0" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /QWaveSystems/QwaveSys-RPi-Package_2.0" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a href="/QWaveSystems/QwaveSys-RPi-Package_2.0/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /QWaveSystems/QwaveSys-RPi-Package_2.0/issues" itemprop="url">
        <svg aria-hidden="true" class="octicon octicon-issue-opened" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/QWaveSystems/QwaveSys-RPi-Package_2.0/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /QWaveSystems/QwaveSys-RPi-Package_2.0/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>

  <a href="/QWaveSystems/QwaveSys-RPi-Package_2.0/projects" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /QWaveSystems/QwaveSys-RPi-Package_2.0/projects">
    <svg aria-hidden="true" class="octicon octicon-project" height="16" version="1.1" viewBox="0 0 15 16" width="15"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
    Projects
    <span class="counter">0</span>
</a>
    <a href="/QWaveSystems/QwaveSys-RPi-Package_2.0/wiki" class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /QWaveSystems/QwaveSys-RPi-Package_2.0/wiki">
      <svg aria-hidden="true" class="octicon octicon-book" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"/></svg>
      Wiki
</a>

  <a href="/QWaveSystems/QwaveSys-RPi-Package_2.0/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="pulse /QWaveSystems/QwaveSys-RPi-Package_2.0/pulse">
    <svg aria-hidden="true" class="octicon octicon-pulse" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M11.5 8L8.8 5.4 6.6 8.5 5.5 1.6 2.38 8H0v2h3.6l.9-1.8.9 5.4L9 8.5l1.6 1.5H14V8z"/></svg>
    Pulse
</a>
  <a href="/QWaveSystems/QwaveSys-RPi-Package_2.0/graphs" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors /QWaveSystems/QwaveSys-RPi-Package_2.0/graphs">
    <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
    Graphs
</a>
    <a href="/QWaveSystems/QwaveSys-RPi-Package_2.0/settings" class="js-selected-navigation-item reponav-item" data-selected-links="repo_settings repo_branch_settings hooks integration_installations /QWaveSystems/QwaveSys-RPi-Package_2.0/settings">
      <svg aria-hidden="true" class="octicon octicon-gear" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 8.77v-1.6l-1.94-.64-.45-1.09.88-1.84-1.13-1.13-1.81.91-1.09-.45-.69-1.92h-1.6l-.63 1.94-1.11.45-1.84-.88-1.13 1.13.91 1.81-.45 1.09L0 7.23v1.59l1.94.64.45 1.09-.88 1.84 1.13 1.13 1.81-.91 1.09.45.69 1.92h1.59l.63-1.94 1.11-.45 1.84.88 1.13-1.13-.92-1.81.47-1.09L14 8.75v.02zM7 11c-1.66 0-3-1.34-3-3s1.34-3 3-3 3 1.34 3 3-1.34 3-3 3z"/></svg>
      Settings
</a>
</nav>

  </div>
</div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    

<a href="/QWaveSystems/QwaveSys-RPi-Package_2.0/blob/8c629967f1a8fab567cfe7400758fe5664a1ffe0/README.md" class="d-none js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:e1c9bfb9a1f0cc9b6c6ae0e94dac02a1 -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu branch-select-menu js-menu-container js-select-menu float-left">
  <button class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    
    type="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <i>Branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Find or create a branch…" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Find or create a branch…">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Find or create a branch…" class="js-select-menu-tab" role="tab">Branches</a>
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
               href="/QWaveSystems/QwaveSys-RPi-Package_2.0/blob/master/README.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                master
              </span>
            </a>
        </div>

          <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/QWaveSystems/QwaveSys-RPi-Package_2.0/branches" class="js-create-branch select-menu-item select-menu-new-item-form js-navigation-item js-new-item-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="EvV+9x7hRYceJirUH9SW33Lm1f/1WJEurgzfGXPur5+Kl2pi9sMa+xoBy91V1MPIFgxORrqDlKO4IwAedmobiA==" /></div>
          <svg aria-hidden="true" class="octicon octicon-git-branch select-menu-item-icon" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path fill-rule="evenodd" d="M10 5c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v.3c-.02.52-.23.98-.63 1.38-.4.4-.86.61-1.38.63-.83.02-1.48.16-2 .45V4.72a1.993 1.993 0 0 0-1-3.72C.88 1 0 1.89 0 3a2 2 0 0 0 1 1.72v6.56c-.59.35-1 .99-1 1.72 0 1.11.89 2 2 2 1.11 0 2-.89 2-2 0-.53-.2-1-.53-1.36.09-.06.48-.41.59-.47.25-.11.56-.17.94-.17 1.05-.05 1.95-.45 2.75-1.25S8.95 7.77 9 6.73h-.02C9.59 6.37 10 5.73 10 5zM2 1.8c.66 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2C1.35 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2zm0 12.41c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm6-8c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
            <div class="select-menu-item-text">
              <span class="select-menu-item-heading">Create branch: <span class="js-new-item-name"></span></span>
              <span class="description">from ‘master’</span>
            </div>
            <input type="hidden" name="name" id="name" class="js-new-item-value">
            <input type="hidden" name="branch" id="branch" value="master">
            <input type="hidden" name="path" id="path" value="README.md">
</form>
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
    <a href="/QWaveSystems/QwaveSys-RPi-Package_2.0/find/master"
          class="js-pjax-capture-input btn btn-sm BtnGroup-item"
          data-pjax
          data-hotkey="t">
      Find file
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm BtnGroup-item tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
  </div>
  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/QWaveSystems/QwaveSys-RPi-Package_2.0"><span>QwaveSys-RPi-Package_2.0</span></a></span></span><span class="separator">/</span><strong class="final-path">README.md</strong>
  </div>
</div>


  <div class="commit-tease">
      <span class="float-right">
        <a class="commit-tease-sha" href="/QWaveSystems/QwaveSys-RPi-Package_2.0/commit/8c629967f1a8fab567cfe7400758fe5664a1ffe0" data-pjax>
          8c62996
        </a>
        <relative-time datetime="2017-01-14T18:45:55Z">Jan 15, 2017</relative-time>
      </span>
      <div>
        <img alt="@pamornthep" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/12686721?v=3&amp;s=40" width="20" />
        <a href="/pamornthep" class="user-mention" rel="contributor">pamornthep</a>
          <a href="/QWaveSystems/QwaveSys-RPi-Package_2.0/commit/8c629967f1a8fab567cfe7400758fe5664a1ffe0" class="message" data-pjax="true" title="2.0.0.18">2.0.0.18</a>
      </div>

    <div class="commit-tease-contributors">
      <button type="button" class="btn-link muted-link contributors-toggle" data-facebox="#blob_contributors_box">
        <strong>1</strong>
         contributor
      </button>
      
    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@pamornthep" height="24" src="https://avatars1.githubusercontent.com/u/12686721?v=3&amp;s=48" width="24" />
            <a href="/pamornthep">pamornthep</a>
          </li>
      </ul>
    </div>
  </div>


<div class="file">
  <div class="file-header">
  <div class="file-actions">

    <div class="BtnGroup">
      <a href="/QWaveSystems/QwaveSys-RPi-Package_2.0/raw/master/README.md" class="btn btn-sm BtnGroup-item" id="raw-url">Raw</a>
        <a href="/QWaveSystems/QwaveSys-RPi-Package_2.0/blame/master/README.md" class="btn btn-sm js-update-url-with-hash BtnGroup-item">Blame</a>
      <a href="/QWaveSystems/QwaveSys-RPi-Package_2.0/commits/master/README.md" class="btn btn-sm BtnGroup-item" rel="nofollow">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           href="github-windows://openRepo/https://github.com/QWaveSystems/QwaveSys-RPi-Package_2.0?branch=master&amp;filepath=README.md"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:windows">
            <svg aria-hidden="true" class="octicon octicon-device-desktop" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
        </a>

        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/QWaveSystems/QwaveSys-RPi-Package_2.0/edit/master/README.md" class="inline-form js-update-url-with-hash" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="ia/KHcAHSDXLG3gNJLE8Y8DRwBS1fQqV7toUPYkbFCbwbBRd0Ji0yFGwZbKLVEIrLSedp2dMFGPsyB7wbPPwZQ==" /></div>
          <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
            aria-label="Edit this file" data-hotkey="e" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
          </button>
</form>        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/QWaveSystems/QwaveSys-RPi-Package_2.0/delete/master/README.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="DdNYnh6d63aggqpJRm/tmQc82D1OpmxmQkEL/d3u1Xwe92wJeVkUGjSOnXiIIqCR1Ddv6MSqW0ZJryXgOdytbA==" /></div>
          <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Delete this file" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
          </button>
</form>  </div>

  <div class="file-info">
      157 lines (83 sloc)
      <span class="file-info-divider"></span>
    5.44 KB
  </div>
</div>

  
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-qwavesys-rpi-package-20-for-labview" class="anchor" href="#qwavesys-rpi-package-20-for-labview" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>QwaveSys RPi Package 2.0 for LabVIEW.</h1>

<p>If you find this package is useful, please consider supporting it with a donation. 
<a href="https://www.paypal.me/qwavesystems">https://www.paypal.me/qwavesystems</a></p>

<p><a href="https://camo.githubusercontent.com/a2ccab53b782c07f373000d1d12e9b41fdb0180a/687474703a2f2f6674702e71776176657379732e636f6d2f746d705f706963732f5270693030332e706e67" target="_blank"><img src="https://camo.githubusercontent.com/a2ccab53b782c07f373000d1d12e9b41fdb0180a/687474703a2f2f6674702e71776176657379732e636f6d2f746d705f706963732f5270693030332e706e67" alt="" data-canonical-src="http://ftp.qwavesys.com/tmp_pics/Rpi003.png" style="max-width:100%;"></a></p>

<p><a href="https://camo.githubusercontent.com/318aaad8f30c6ea94f6da25c4e2a4959c9750ff9/687474703a2f2f6674702e71776176657379732e636f6d2f746d705f706963732f5270693030312e706e67" target="_blank"><img src="https://camo.githubusercontent.com/318aaad8f30c6ea94f6da25c4e2a4959c9750ff9/687474703a2f2f6674702e71776176657379732e636f6d2f746d705f706963732f5270693030312e706e67" alt="" data-canonical-src="http://ftp.qwavesys.com/tmp_pics/Rpi001.png" style="max-width:100%;"></a></p>

<p><a href="https://github.com/QWaveSystems/QwaveSys-RPi-Package_2.0"><strong>QwaveSys RPi package 2.0</strong></a> is a LabVIEW additional library based on <a href="http://sine.ni.com/nips/cds/view/p/lang/en/nid/212478">LINX 3.0.xx</a> from <a href="https://www.labviewmakerhub.com">labviewmakerhub.com</a> for Raspberry Pi. It's supported LabVIEW 2014 only for Non-commercial use.</p>

<p>Anyone can get started with the <a href="http://ftp.ni.com/support/softlib/labview/labview_development_system/2014%20SP1/2014sp1LV-WinEng.exe">LabVIEW 45-Day Evaluation</a> and buy LabVIEW 2014 Home Edition for non-commercial use. </p>

<p>QwaveSys RPi Package is a peripheral VIs provides enhance functions over LINX 3.0 standard library. it's an easy to use VIs and provided many examples. It's tested with Raspberry Pi 2B/3B and some functions also works with BBB and Orange Pi (H3) boards.</p>

<p><a href="https://camo.githubusercontent.com/52e65f21d975f1370f53658732c5e563b6e05688/687474703a2f2f6674702e71776176657379732e636f6d2f746d705f706963732f323031372d30312d31325f32312d30352d32362e706e67" target="_blank"><img src="https://camo.githubusercontent.com/52e65f21d975f1370f53658732c5e563b6e05688/687474703a2f2f6674702e71776176657379732e636f6d2f746d705f706963732f323031372d30312d31325f32312d30352d32362e706e67" alt="" data-canonical-src="http://ftp.qwavesys.com/tmp_pics/2017-01-12_21-05-26.png" style="max-width:100%;"></a></p>

<h1><a id="user-content-installation-steps" class="anchor" href="#installation-steps" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Installation Steps.</h1>

<p><strong>1.Download and Install "q_wave_systems_lib_qwavesys_rpi_package-2.0.0.18.vip"</strong></p>

<p><a href="https://github.com/QWaveSystems/QwaveSys-RPi-Package_2.0/blob/master/q_wave_systems_lib_qwavesys_rpi_package-2.0.0.18.vip">https://github.com/QWaveSystems/QwaveSys-RPi-Package_2.0/blob/master/q_wave_systems_lib_qwavesys_rpi_package-2.0.0.18.vip</a></p>

<p><strong>2.Download QwaveSys RPi Image. Refer the link below.</strong> The image is based on <strong>"2016-09-23</strong>-Raspbian-Jessie WITH PIXEL".</p>

<p><a href="https://drive.google.com/file/d/0B5DiaJTnM12RdVBRNl8wOVJ3TzA/view">https://drive.google.com/file/d/0B5DiaJTnM12RdVBRNl8wOVJ3TzA/view</a></p>

<p><strong>3.Navigate to "..\vi.lib\Q-Wave Systems\QwaveSys RPi Package 2.0\Solutions".</strong> There are a lots of shipped solutions for you.</p>

<p><a href="https://camo.githubusercontent.com/a0e457e520389f7a7df9ea3fb534752b024c7032/687474703a2f2f6674702e71776176657379732e636f6d2f746d705f706963732f31343537303735355f313133333735333435333332363639325f353631313633323333363135343036303832385f6f2e706e67" target="_blank"><img src="https://camo.githubusercontent.com/a0e457e520389f7a7df9ea3fb534752b024c7032/687474703a2f2f6674702e71776176657379732e636f6d2f746d705f706963732f31343537303735355f313133333735333435333332363639325f353631313633323333363135343036303832385f6f2e706e67" alt="" data-canonical-src="http://ftp.qwavesys.com/tmp_pics/14570755_1133753453326692_5611632336154060828_o.png" style="max-width:100%;"></a></p>

<h1><a id="user-content-manual-steps-to-install-necessary-packages" class="anchor" href="#manual-steps-to-install-necessary-packages" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Manual Steps to install necessary packages:</h1>

<h1><a id="user-content-for-advanced-users-only" class="anchor" href="#for-advanced-users-only" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>(For Advanced users ONLY)</h1>

<p><strong>1.Download a official "RASPBIAN JESSIE WITH PIXEL"</strong> from <a href="https://www.raspberrypi.org/downloads/raspbian/">https://www.raspberrypi.org/downloads/raspbian/</a></p>

<p>We only tested with "2016-09-23-Raspbian-Jessie WITH PIXEL ONLY.</p>

<p><strong>2.Install LINX 3.0. (LabVIEW run-time: (14.x.xx))</strong> Refer to this turterial <a href="https://youtu.be/zsX0rJQGFqQ">https://youtu.be/zsX0rJQGFqQ</a></p>

<p><strong>3.Login to LabVIEW chroot</strong></p>

<p><code>sudo schroot –c labview</code></p>

<p><strong>4.Check the supported architecture.</strong></p>

<p><code>cat /etc/opkg/arch.conf</code></p>

<p><strong>5.Add “Raspberry Pi 2” architecture to the config file.</strong></p>

<p><code>echo "arch raspberrypi2 71" | tee -a /etc/opkg/arch.conf</code></p>

<p><strong>6.Backup the original feeds source file.</strong> (feeds.labviewmakerhub.com)</p>

<p><code>mv /etc/opkg/base-feeds.conf /etc/opkg/base-feeds.conf_bak</code></p>

<p><strong>7.Add “QWAVESYS” feeds source server,</strong> (<a href="http://ftp.qwavesys.com/ipk/">http://ftp.qwavesys.com/ipk/</a>)</p>

<p><code>echo "src/gz uri-all-0 http://ftp.qwavesys.com/ipk/all" | tee -a /etc/opkg/base-feeds.conf</code></p>

<p><code>echo "src/gz uri-armv7a-vfp-0 http://ftp.qwavesys.com/ipk/armv7a-vfp" | tee -a /etc/opkg/base-feeds.conf</code></p>

<p><code>echo "src/gz uri-generic_armv7a-0 http://ftp.qwavesys.com/ipk/raspberrypi2" | tee -a /etc/opkg/base-feeds.conf</code></p>

<p><strong>8.Install packages from QWAVESYS server.</strong></p>

<p><code>opkg update</code></p>

<p><code>opkg install python</code></p>

<p><code>opkg install opencv</code></p>

<p><code>opkg install packagegroup-core-buildessential</code></p>

<p><code>opkg install wiringpi</code></p>

<p><code>opkg install wiringpi-dev</code></p>

<p><strong>9.Copy the shared library (.so) files from "Shared-Library" on this repo to <code>/srv/chroot/labview/usr/lib</code>.</strong> *Required only ".so" files.</p>

<p><strong>10.Modified the ".profile" config file , located at "/home/pi".</strong>
Refer to "Config-Files" folder on this repo.</p>

<p><strong>11.Modified the "nilvrt" file, Located at "/srv/chroot/labview/usr/local/natinst/etc/init.d", This will allow export DISPLAY inside LV chroot to RPi display, Default =:0.0.</strong>
Refer to "Config-Files" folder on this repo. </p>

<p><strong>12.Navigate to "..\vi.lib\Q-Wave Systems\QwaveSys RPi Package 2.0\Solutions".</strong> There are a lots of shipped solutions for you.</p>

<h1><a id="user-content-released-notes" class="anchor" href="#released-notes" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Released Notes:</h1>

<p><strong>Initial Released 2.0.0.18</strong></p>

<p><strong>Add-ons Library:</strong></p>

<p>-ADC_PCF8591 (Analog ADC: 4Ch AI, 1 Ch for AO)</p>

<p>-DHTxx (DHT11,DHT22 Temperature sensor)</p>

<p>-DS18b20 (1-Wire Digital temperature sensor)</p>

<p>-OpenCV (Based on OpenCV 3.0)</p>

<p>-USBCamera (USB driver)</p>

<p>-WebSockets API (IE) * Created by "Sam Sharp - Intelligent Energy"</p>

<p>-WiringPi (GPIO library)</p>

<p><strong>Examples :</strong></p>

<p><strong>Exercises located at -&gt; LabVIEW 2014\vi.lib\Q-Wave Systems\QwaveSys RPi Package 2.0\Exercises</strong></p>

<p><strong>Solutions located at -&gt; LabVIEW 2014\vi.lib\Q-Wave Systems\QwaveSys RPi Package 2.0\Solutions</strong></p>

<p>-Exercise 1 GPIO</p>

<p>-Exercise 2 Temp Sensor</p>

<p>-Exercise 3 ADC</p>

<p>-Exercise 4 Camera</p>

<p>-Exercise 5 Webservice</p>

<p>-Exercise 6 Network Communucation</p>

<p>-Exercise 7 Websocket</p>

<p>-Exercise 8 OpenCV Color Detect</p>

<p>-Exercise 9 OpenCV Pattern Matching</p>

<p>-Exercise 10 Tag WebUI</p>

<p>-Exercise 11 WebUI ThinClient</p>

<p>-Exercise 12 Webpanel SVG-HTML5</p>

<p>-Exercise 13 Share Library Development</p>

<p>-Exercise 14 WiringPi Library Development</p>

<hr>

<p>-Raspberry Pi™ is a registered trademark of the Raspberry Pi foundation.
-LINX 3.0 for Raspberry Pi 2B/3B create by <code>www.labviewmakerhub.com</code> (LabVIEW 2014 only,***Non-commercial use)</p>

<p>-WiringPi is a GPIO access library based on BCM2835 library used in the Raspberry Pi. It’s released under the GNU LGPLv3 license created by Gordon Henderson. <code>(http://wiringpi.com/)</code>
-OpenCV is released under a BSD license and hence it’s free for both academic and commercial use. <code>(http://opencv.org/)</code></p>

<hr>

<p>Created by <code>Amornthep Phunsin</code> and <code>Supawat Armart</code> (Q-Wave Systems Co.,Ltd)
Contact : <code>"amornthep@qwavesys.com"</code></p>

<p>If you find this package is useful, please consider supporting it with a donation. 
<a href="https://www.paypal.me/qwavesystems">https://www.paypal.me/qwavesystems</a></p>
</article>
  </div>

</div>

<button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="d-none">Jump to Line</button>
<div id="jump-to-line" style="display:none">
  <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>


    </div>
  </div>

    </div>

        <div class="container site-footer-container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links float-right">
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact GitHub</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage" class="site-footer-mark" title="GitHub">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2017 <span title="0.10346s from github-fe131-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>
  </div>
</div>



    

    <div id="ajax-error-message" class="ajax-error-message flash flash-error">
      <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
      <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
        <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
      </button>
      You can't perform that action at this time.
    </div>


      
      <script crossorigin="anonymous" integrity="sha256-uzmufYSNQNbwHmc1XigpZPVPo5E3wOzJ/E7Dfn1GlQg=" src="https://assets-cdn.github.com/assets/frameworks-bb39ae7d848d40d6f01e67355e282964f54fa39137c0ecc9fc4ec37e7d469508.js"></script>
      <script async="async" crossorigin="anonymous" integrity="sha256-eWdDtcNle3lAE930stqMfzh+bw+Bx6YFn7nLg3DHLek=" src="https://assets-cdn.github.com/assets/github-796743b5c3657b794013ddf4b2da8c7f387e6f0f81c7a6059fb9cb8370c72de9.js"></script>
      
      
      
      
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

