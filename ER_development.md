



<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-3b7a1de05e9e139acebe3d3c0598c589d2ac68abaeeb757c8b7cf42d9bf64b46.css" integrity="sha256-O3od4F6eE5rOvj08BZjFidKsaKuu63V8i3z0LZv2S0Y=" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-5cc286475cd91b1474cc0f24df46cebbfab640427dd37a274f348589a2cf4407.css" integrity="sha256-XMKGR1zZGxR0zA8k30bOu/q2QEJ903onTzSFiaLPRAc=" media="all" rel="stylesheet" />
    
    
    
    

    <link as="script" href="https://assets-cdn.github.com/assets/frameworks-411d610e4b2b1ffa3d063904534406d08c8351d9ba9b4b3f339bab35e86bb4f3.js" rel="preload" />
    
    <link as="script" href="https://assets-cdn.github.com/assets/github-4c9276ec4d3618972ac65b79e4db3fae6e064724ed3b9526fcd8e8f6a9ad85d7.js" rel="preload" />

    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=device-width">
    
    <title>old-sbgn-wiki-archive/ER_development.md at master · sbgn/old-sbgn-wiki-archive</title>
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

      <meta content="https://avatars3.githubusercontent.com/u/19808539?v=3&amp;s=400" name="twitter:image:src" /><meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="sbgn/old-sbgn-wiki-archive" name="twitter:title" /><meta content="old-sbgn-wiki-archive - Contains exported files from a previous SBGN website" name="twitter:description" />
      <meta content="https://avatars3.githubusercontent.com/u/19808539?v=3&amp;s=400" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="sbgn/old-sbgn-wiki-archive" property="og:title" /><meta content="https://github.com/sbgn/old-sbgn-wiki-archive" property="og:url" /><meta content="old-sbgn-wiki-archive - Contains exported files from a previous SBGN website" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/MzY5NDUxODo1NDlkOWVmMzNmOWExODYzZjZiM2IxNjI4YTliOTViZDowMjE0YzY2NzQyOTc0MTkzMjg3ZTU3Y2ZlNDI2ZTliODc5OTdkNzM1Y2I1N2IzZDcyZmZkZGQxYmViMjQwNmU2--5d0bc33cd2faafb1e5245511b12484530b9d828f">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">
    <meta name="request-id" content="959B9535:2B25:C4E13D:57EE571C" data-pjax-transient>

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
<meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="959B9535:2B25:C4E13D:57EE571C" name="octolytics-dimension-request_id" /><meta content="3694518" name="octolytics-actor-id" /><meta content="lenov" name="octolytics-actor-login" /><meta content="8e0690ce53f1e653fe7bbc48c35c939630d1852f8645304da8f2ccf6c74edb61" name="octolytics-actor-hash" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />



  <meta class="js-ga-set" name="dimension1" content="Logged In">



        <meta name="hostname" content="github.com">
    <meta name="user-login" content="lenov">

        <meta name="expected-hostname" content="github.com">
      <meta name="js-proxy-site-detection-payload" content="NTA0NDc0MDBmNjI2MGE3MmEzYjZhNWIzNmVkYTAzZjVmN2Y2YzI0YWY2YzY4NGM4MDAxZWQ5NjNjNGNjMGZkNHx7InJlbW90ZV9hZGRyZXNzIjoiMTQ5LjE1NS4xNDkuNTMiLCJyZXF1ZXN0X2lkIjoiOTU5Qjk1MzU6MkIyNTpDNEUxM0Q6NTdFRTU3MUMiLCJ0aW1lc3RhbXAiOjE0NzUyMzc2NjB9">


      <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

    <meta name="html-safe-nonce" content="fd4b74d32029ff0d0e539365efede10b4001adae">
    <meta content="4d9ac8234a7630ac0cbd07bff059eb53005b3013" name="form-nonce" />

    <meta http-equiv="x-pjax-version" content="6704c2e8184b28aacffc8055fbdc86f3">
    

      
  <meta name="description" content="old-sbgn-wiki-archive - Contains exported files from a previous SBGN website">
  <meta name="go-import" content="github.com/sbgn/old-sbgn-wiki-archive git https://github.com/sbgn/old-sbgn-wiki-archive.git">

  <meta content="19808539" name="octolytics-dimension-user_id" /><meta content="sbgn" name="octolytics-dimension-user_login" /><meta content="69659363" name="octolytics-dimension-repository_id" /><meta content="sbgn/old-sbgn-wiki-archive" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="69659363" name="octolytics-dimension-repository_network_root_id" /><meta content="sbgn/old-sbgn-wiki-archive" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/sbgn/old-sbgn-wiki-archive/commits/master.atom" rel="alternate" title="Recent Commits to old-sbgn-wiki-archive:master" type="application/atom+xml">


      <link rel="canonical" href="https://github.com/sbgn/old-sbgn-wiki-archive/blob/master/ER_development.md" data-pjax-transient>
  </head>


  <body class="logged-in  env-production linux vis-public page-blob">
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>

    
    
    



        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg aria-hidden="true" class="octicon octicon-mark-github" height="28" version="1.1" viewBox="0 0 16 16" width="28"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path></svg>
</a>


        <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/sbgn/old-sbgn-wiki-archive/search" class="js-site-search-form" data-scoped-search-url="/sbgn/old-sbgn-wiki-archive/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
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
    
    <a href="/notifications" aria-label="You have unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s js-socket-channel js-notification-indicator" data-channel="tenant:1:notification-changed:3694518" data-ga-click="Header, go to notifications, icon:unread" data-hotkey="g n">
        <span class="mail-status unread"></span>
        <svg aria-hidden="true" class="octicon octicon-bell" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 12v1H0v-1l.73-.58c.77-.77.81-2.55 1.19-4.42C2.69 3.23 6 2 6 2c0-.55.45-1 1-1s1 .45 1 1c0 0 3.39 1.23 4.16 5 .38 1.88.42 3.66 1.19 4.42l.66.58H14zm-7 4c1.11 0 2-.89 2-2H5c0 1.11.89 2 2 2z"></path></svg>
</a>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <svg aria-hidden="true" class="octicon octicon-plus float-left" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 9H7v5H5V9H0V7h5V2h2v5h5z"></path></svg>
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
    <span title="sbgn">This organization</span>
  </div>
  <a class="dropdown-item" href="/orgs/sbgn/people#invite-member" data-ga-click="Header, invite someone">
    Invite someone
  </a>
  <a class="dropdown-item" href="/orgs/sbgn/new-team" data-ga-click="Header, create new team">
    New team
  </a>
  <a class="dropdown-item" href="/organizations/sbgn/repositories/new" data-ga-click="Header, create new organization repository, icon:repo">
    New repository
  </a>


  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="sbgn/old-sbgn-wiki-archive">This repository</span>
  </div>
    <a class="dropdown-item" href="/sbgn/old-sbgn-wiki-archive/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>
    <a class="dropdown-item" href="/sbgn/old-sbgn-wiki-archive/settings/collaboration" data-ga-click="Header, create new collaborator">
      New collaborator
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-sw js-menu-target" href="/lenov"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@lenov" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/3694518?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu dropdown-menu-sw">
        <div class="dropdown-header header-nav-current-user css-truncate">
          Signed in as <strong class="css-truncate-target">lenov</strong>
        </div>

        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/lenov" data-ga-click="Header, go to profile, text:your profile">
          Your profile
        </a>
        <a class="dropdown-item" href="/lenov?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">
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

        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/logout" class="logout-form" data-form-nonce="4d9ac8234a7630ac0cbd07bff059eb53005b3013" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="xFrGwVBswgPbix3Xr+KAxJpoYU4yet+6WQI/PH1qnhxz1UgBcZy2EM5zvHaHUmD18Ecewp6uI6gTaQTZh95JAQ==" /></div>
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
        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-form-nonce="4d9ac8234a7630ac0cbd07bff059eb53005b3013" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="Na7uzU8sCQ3GXc/wmK7pMhVri8heFbq+G7eaDVeHteEeEZWakiKeHftYBmxgEPR2wbsFGFCvT9X52UukYe+epw==" /></div>      <input class="form-control" id="repository_id" name="repository_id" type="hidden" value="69659363" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/sbgn/old-sbgn-wiki-archive/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
              <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"></path></svg>
              Unwatch
            </span>
          </a>
          <a class="social-count js-social-count"
            href="/sbgn/old-sbgn-wiki-archive/watchers"
            aria-label="5 users are watching this repository">
            5
          </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header js-navigation-enable" tabindex="-1">
              <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"></path></svg>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input id="do_included" name="do" type="radio" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"></path></svg>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input checked="checked" id="do_subscribed" name="do" type="radio" value="subscribed" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"></path></svg>
                      Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input id="do_ignore" name="do" type="radio" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-mute" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"></path></svg>
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

    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/sbgn/old-sbgn-wiki-archive/unstar" class="starred" data-form-nonce="4d9ac8234a7630ac0cbd07bff059eb53005b3013" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="3q+EIw5Vla/fCJ9ZzqpQ7MzjZuU/pSczpfeejtGP0BvDCNGMsygAqL7awEyV4RaWnMES/p4UeUSMD03WJV2Wug==" /></div>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar sbgn/old-sbgn-wiki-archive"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"></path></svg>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/sbgn/old-sbgn-wiki-archive/stargazers"
           aria-label="0 users starred this repository">
          0
        </a>
</form>
    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/sbgn/old-sbgn-wiki-archive/star" class="unstarred" data-form-nonce="4d9ac8234a7630ac0cbd07bff059eb53005b3013" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="z6L01IYuh8mFQ7v7wLR25DSWnaK5mfwKxbC28gAHDlj4b7kBB5jgVDcQvL93QTmOtv+V8xautw4IArvI/WJj1w==" /></div>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star sbgn/old-sbgn-wiki-archive"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"></path></svg>
        Star
      </button>
        <a class="social-count js-social-count" href="/sbgn/old-sbgn-wiki-archive/stargazers"
           aria-label="0 users starred this repository">
          0
        </a>
</form>  </div>

  </li>

  <li>
          <a href="#fork-destination-box" class="btn btn-sm btn-with-count"
              title="Fork your own copy of sbgn/old-sbgn-wiki-archive to your account"
              aria-label="Fork your own copy of sbgn/old-sbgn-wiki-archive to your account"
              rel="facebox"
              data-ga-click="Repository, show fork modal, action:blob#show; text:Fork">
              <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"></path></svg>
            Fork
          </a>

          <div id="fork-destination-box" style="display: none;">
            <h2 class="facebox-header" data-facebox-id="facebox-header">Where should we fork this repository?</h2>
            <include-fragment src=""
                class="js-fork-select-fragment fork-select-fragment"
                data-url="/sbgn/old-sbgn-wiki-archive/fork?fragment=1">
              <img alt="Loading" height="64" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-128.gif" width="64" />
            </include-fragment>
          </div>

    <a href="/sbgn/old-sbgn-wiki-archive/network" class="social-count"
       aria-label="0 users are forked this repository">
      0
    </a>
  </li>
</ul>

    <h1 class="public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"></path></svg>
  <span class="author" itemprop="author"><a href="/sbgn" class="url fn" rel="author">sbgn</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/sbgn/old-sbgn-wiki-archive" data-pjax="#js-repo-pjax-container">old-sbgn-wiki-archive</a></strong>

</h1>

  </div>
  <div class="container">
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/sbgn/old-sbgn-wiki-archive" aria-selected="true" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /sbgn/old-sbgn-wiki-archive" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"></path></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a href="/sbgn/old-sbgn-wiki-archive/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /sbgn/old-sbgn-wiki-archive/issues" itemprop="url">
        <svg aria-hidden="true" class="octicon octicon-issue-opened" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"></path></svg>
        <span itemprop="name">Issues</span>
        <span class="counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/sbgn/old-sbgn-wiki-archive/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /sbgn/old-sbgn-wiki-archive/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"></path></svg>
      <span itemprop="name">Pull requests</span>
      <span class="counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>

  <a href="/sbgn/old-sbgn-wiki-archive/projects" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /sbgn/old-sbgn-wiki-archive/projects">
    <svg class="octicon" aria-hidden="true" version="1.1" width="15" height="16" viewBox="0 0 15 16">
      <path d="M1 15h13V1H1v14zM15 1v14a1 1 0 0 1-1 1H1a1 1 0 0 1-1-1V1a1 1 0 0 1 1-1h13a1 1 0 0 1 1 1zm-4.41 11h1.82c.59 0 .59-.41.59-1V3c0-.59 0-1-.59-1h-1.82C10 2 10 2.41 10 3v8c0 .59 0 1 .59 1zm-4-2h1.82C9 10 9 9.59 9 9V3c0-.59 0-1-.59-1H6.59C6 2 6 2.41 6 3v6c0 .59 0 1 .59 1zM2 13V3c0-.59 0-1 .59-1h1.82C5 2 5 2.41 5 3v10c0 .59 0 1-.59 1H2.59C2 14 2 13.59 2 13z"></path>
    </svg>
    Projects
    <span class="counter">0</span>
</a>
    <a href="/sbgn/old-sbgn-wiki-archive/wiki" class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /sbgn/old-sbgn-wiki-archive/wiki">
      <svg aria-hidden="true" class="octicon octicon-book" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"></path></svg>
      Wiki
</a>

  <a href="/sbgn/old-sbgn-wiki-archive/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="pulse /sbgn/old-sbgn-wiki-archive/pulse">
    <svg aria-hidden="true" class="octicon octicon-pulse" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M11.5 8L8.8 5.4 6.6 8.5 5.5 1.6 2.38 8H0v2h3.6l.9-1.8.9 5.4L9 8.5l1.6 1.5H14V8z"></path></svg>
    Pulse
</a>
  <a href="/sbgn/old-sbgn-wiki-archive/graphs" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors /sbgn/old-sbgn-wiki-archive/graphs">
    <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"></path></svg>
    Graphs
</a>
    <a href="/sbgn/old-sbgn-wiki-archive/settings" class="js-selected-navigation-item reponav-item" data-selected-links="repo_settings repo_branch_settings hooks integration_installations /sbgn/old-sbgn-wiki-archive/settings">
      <svg aria-hidden="true" class="octicon octicon-gear" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 8.77v-1.6l-1.94-.64-.45-1.09.88-1.84-1.13-1.13-1.81.91-1.09-.45-.69-1.92h-1.6l-.63 1.94-1.11.45-1.84-.88-1.13 1.13.91 1.81-.45 1.09L0 7.23v1.59l1.94.64.45 1.09-.88 1.84 1.13 1.13 1.81-.91 1.09.45.69 1.92h1.59l.63-1.94 1.11-.45 1.84.88 1.13-1.13-.92-1.81.47-1.09L14 8.75v.02zM7 11c-1.66 0-3-1.34-3-3s1.34-3 3-3 3 1.34 3 3-1.34 3-3 3z"></path></svg>
      Settings
</a>
</nav>

  </div>
</div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    

<a href="/sbgn/old-sbgn-wiki-archive/blob/b4ceb3becf061d1f9ce7579760eaf2f33eaa8a78/ER_development.md" class="d-none js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:40b184f2aac5a18561998e9b48bc71ec -->

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
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"></path></svg>
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
               href="/sbgn/old-sbgn-wiki-archive/blob/master/ER_development.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                master
              </span>
            </a>
        </div>

          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/sbgn/old-sbgn-wiki-archive/branches" class="js-create-branch select-menu-item select-menu-new-item-form js-navigation-item js-new-item-form" data-form-nonce="4d9ac8234a7630ac0cbd07bff059eb53005b3013" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="a42K00TAhQs7Ch1LuFEFy7ccRSr4otLLroukJdRC/TsClm1qs9MZ/sBspLvgHtbMOxhyRaUTHWTOhhVXLw5OPg==" /></div>
          <svg aria-hidden="true" class="octicon octicon-git-branch select-menu-item-icon" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path d="M10 5c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v.3c-.02.52-.23.98-.63 1.38-.4.4-.86.61-1.38.63-.83.02-1.48.16-2 .45V4.72a1.993 1.993 0 0 0-1-3.72C.88 1 0 1.89 0 3a2 2 0 0 0 1 1.72v6.56c-.59.35-1 .99-1 1.72 0 1.11.89 2 2 2 1.11 0 2-.89 2-2 0-.53-.2-1-.53-1.36.09-.06.48-.41.59-.47.25-.11.56-.17.94-.17 1.05-.05 1.95-.45 2.75-1.25S8.95 7.77 9 6.73h-.02C9.59 6.37 10 5.73 10 5zM2 1.8c.66 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2C1.35 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2zm0 12.41c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm6-8c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"></path></svg>
            <div class="select-menu-item-text">
              <span class="select-menu-item-heading">Create branch: <span class="js-new-item-name"></span></span>
              <span class="description">from ‘master’</span>
            </div>
            <input type="hidden" name="name" id="name" class="js-new-item-value">
            <input type="hidden" name="branch" id="branch" value="master">
            <input type="hidden" name="path" id="path" value="ER_development.md">
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
    <a href="/sbgn/old-sbgn-wiki-archive/find/master"
          class="js-pjax-capture-input btn btn-sm BtnGroup-item"
          data-pjax
          data-hotkey="t">
      Find file
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm BtnGroup-item tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
  </div>
  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/sbgn/old-sbgn-wiki-archive"><span>old-sbgn-wiki-archive</span></a></span></span><span class="separator">/</span><strong class="final-path">ER_development.md</strong>
  </div>
</div>


  <div class="commit-tease">
      <span class="float-right">
        <a class="commit-tease-sha" href="/sbgn/old-sbgn-wiki-archive/commit/b4ceb3becf061d1f9ce7579760eaf2f33eaa8a78" data-pjax>
          b4ceb3b
        </a>
        <relative-time datetime="2016-09-30T11:01:45Z">Sep 30, 2016</relative-time>
      </span>
      <div>
        <img alt="@cannin" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/790284?v=3&amp;s=40" width="20" />
        <a href="/cannin" class="user-mention" rel="contributor">cannin</a>
          <a href="/sbgn/old-sbgn-wiki-archive/commit/b4ceb3becf061d1f9ce7579760eaf2f33eaa8a78" class="message" data-pjax="true" title="Initial commit">Initial commit</a>
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
            <img alt="@cannin" height="24" src="https://avatars0.githubusercontent.com/u/790284?v=3&amp;s=48" width="24" />
            <a href="/cannin">cannin</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
  <div class="file-actions">

    <div class="BtnGroup">
      <a href="/sbgn/old-sbgn-wiki-archive/raw/master/ER_development.md" class="btn btn-sm BtnGroup-item" id="raw-url">Raw</a>
        <a href="/sbgn/old-sbgn-wiki-archive/blame/master/ER_development.md" class="btn btn-sm js-update-url-with-hash BtnGroup-item">Blame</a>
      <a href="/sbgn/old-sbgn-wiki-archive/commits/master/ER_development.md" class="btn btn-sm BtnGroup-item" rel="nofollow">History</a>
    </div>


        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/sbgn/old-sbgn-wiki-archive/edit/master/ER_development.md" class="inline-form js-update-url-with-hash" data-form-nonce="4d9ac8234a7630ac0cbd07bff059eb53005b3013" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="XY8p8Owu9AEQt3g+uw3JJYhXTdudNuBH4Jqbov5UPcFAosVWsZRe2oaKviCDaVH5Y04TREXM8P+bv/EQiiTdEw==" /></div>
          <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
            aria-label="Edit this file" data-hotkey="e" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"></path></svg>
          </button>
</form>        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/sbgn/old-sbgn-wiki-archive/delete/master/ER_development.md" class="inline-form" data-form-nonce="4d9ac8234a7630ac0cbd07bff059eb53005b3013" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="8k6KsbGteqnjY1WT08TJoutEvBG3gj0z9CE0f6KyT3+gnL1P+4B4n/95YqqyAk3k0v/E2toQ+AzPzOgcXK0fmQ==" /></div>
          <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Delete this file" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"></path></svg>
          </button>
</form>  </div>

  <div class="file-info">
      98 lines (61 sloc)
      <span class="file-info-divider"></span>
    7.33 KB
  </div>
</div>

  
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><h2><a id="user-content-survey-on-clarification-of-the-outcome" class="anchor" href="#survey-on-clarification-of-the-outcome" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Survey on clarification of the "outcome"</h2>

<p>In SBGN Entity Relationships L1V1, an "outcome", visualised by a black disc, represents the truth of a statement, such an interaction or a variable assignmment. One can then use the outcome as an interactor, or as the source of an influence. Over the past few years, we have discussed much of the meaning of the outcome. Such discussions can be found at:</p>

<p><a href="http://sbgn.org/Events/SBGN-6/SBGN_languages_breakout_topics#Differentiating_continuant_and_occurrent_entities">http://sbgn.org/Events/SBGN-6/SBGN_languages_breakout_topics#Differentiating_continuant_and_occurrent_entities</a></p>

<p><a href="https://utils.its.caltech.edu/pipermail/sbgn-discuss/2011-February/000475.html">https://utils.its.caltech.edu/pipermail/sbgn-discuss/2011-February/000475.html</a></p>

<p><a href="https://utils.its.caltech.edu/pipermail/sbgn-discuss/2011-April/000578.html">https://utils.its.caltech.edu/pipermail/sbgn-discuss/2011-April/000578.html</a></p>

<p>Prior to HARMONY 2011, the outcome was interpreted by some as the result of the statement (e.g. a complex created by an interaction) or the statement itself becoming true (e.g. the interaction itself). SBGN aiming to be unambiguously interpreted, this was an unsatisfactory situation. During HARMONY 2011, the discussion led to the conclusion that for most people (not all since the specification is fuzzy on this point), the outcome</p>

<ul>
<li>  currently* represents a restriction of the possible states of the</li>
</ul>

<p>participants. For an interaction between an entity A and an entity B, the outcome of an interaction between A and B would represent (the instances of B bound to A) AND (the instances of A bound to B). This interpretation was confirmed without dissent by the participants of COMBINE 2011.</p>

<p>This let us to the question of representing the interaction itself, or a phosphorylation event (by opposition to the phosphorylated entity) etc. It was proposed (see discussions referenced above) to create another glyph.</p>

<hr>

<p>A vote was opened on September 9th 2011 and closed on September 30th 2011. 8 votes have been expressed. Two questions aimed at assessing the background understanding of the specification, and two questions aimed at taking decisions.</p>

<ol>
<li>In your understanding of the current ER specification, what can be represented by an entity glyph</li>
</ol>

<table><thead>
<tr>
<th></th>
<th>yes</th>
<th>no</th>
<th>not sure</th>
</tr>
</thead><tbody>
<tr>
<td>a material entity (e.g. molecule)</td>
<td>7</td>
<td>1</td>
<td>0</td>
</tr>
<tr>
<td>a process (e.g. glycolysis)</td>
<td>1</td>
<td>4</td>
<td>3</td>
</tr>
<tr>
<td>a variable (e.g blood pressure)</td>
<td>2</td>
<td>2</td>
<td>4</td>
</tr>
</tbody></table>

<p>Comments: "An entity can be anything..."</p>

<p>While the answers are diverse, a trend emerges to say that an ER entity is currently representing continuants and not occurrents. This calls for the creation of another glyph to represent occurrent. That issue will be the topic of a further vote.</p>

<ol>
<li>In your understanding of the current ER specification, what does the outcome of an interaction represent?</li>
</ol>

<table><thead>
<tr>
<th></th>
<th></th>
</tr>
</thead><tbody>
<tr>
<td>A material complex formed by the interactors?</td>
<td>7</td>
</tr>
<tr>
<td>The interaction itself when realised?</td>
<td>0</td>
</tr>
<tr>
<td>None of the above</td>
<td>1</td>
</tr>
<tr>
<td>Not sure</td>
<td>0</td>
</tr>
</tbody></table>

<p>Comments: "It's the result of the interaction where both entities are in a bound state. But NOT a new complex entity."</p>

<p>There seems to be a consensus here that the current outcome represents a continuant, whether material complex, or restriction of the states of the participants.</p>

<ol>
<li>There is a proposal to split the ER "outcome" glyph into the current filled disk, that would then represent the result of a statement, e.g. a complex, and another symbol, representing the realisation of the statement, e.g. an interaction. Do-you agree with this proposal?</li>
</ol>

<table><thead>
<tr>
<th></th>
<th></th>
</tr>
</thead><tbody>
<tr>
<td>yes</td>
<td>6</td>
</tr>
<tr>
<td>no</td>
<td>6</td>
</tr>
<tr>
<td>unsure</td>
<td>1</td>
</tr>
</tbody></table>

<p>Comments: "I think the working of this question is not clear. I'm not sure what is the diff between result and realisation"</p>

<p>Decision: Creation of two outcome glyphs, with the current one representing the result of the interaction.</p>

<ol>
<li>Several proposition were made to represent the new outcome. An empty square would remind of the process in Process Descriptions, and the activity in Activity Flows. But it would potentially be confusing with the cardinality of an interation, also represented by a square (but tangent to the interaction arc). A filled square would remind of the current outcome, but may be confused with the circle outcome if too small. If we introduce a new glyph to represent the realisation of a statement, should it be:</li>
</ol>

<table><thead>
<tr>
<th></th>
<th></th>
</tr>
</thead><tbody>
<tr>
<td>filled square</td>
<td>1</td>
</tr>
<tr>
<td>empty square</td>
<td>4</td>
</tr>
<tr>
<td>Others</td>
<td>2 ("Not sure.", "empty circle")</td>
</tr>
</tbody></table>

<p>Decision: The outcome glyph representing the interaction itself will be an empty square.</p>

<h2><a id="user-content-domains-sites-and-motives" class="anchor" href="#domains-sites-and-motives" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Domains, sites and motives</h2>

<p>SBGN ER Level 1 Version 1 does not provide structures to represent physical or functional subdivisions of entities. Nevertheless, it is clear that domains are important, and that people want, and need, to represent them.</p>

<p>Different approaches have been proposed so far, in particular the nesting and the subdivision. Both have advantages and disadvantages. Nesting is closer to the underlying, or conceptual, representation, and will probably be favored by computer scientists. Subdivision is closer to the physical structure of the entities and to what we draw in the back on an envelop and in a power-point presentation. It will likely be preferred by biologists. Designing a consistent and robust system will require a significant amount of work and discussion and this page provide materials to base the discussion.</p>

<h3><a id="user-content-proposal-by-kurt-kohn" class="anchor" href="#proposal-by-kurt-kohn" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Proposal by Kurt Kohn</h3>

<p>Kurt Kohn proposed a comprehensive proposal to encode structures using subdivisions.</p>

<ul>
<li>  <a href="/sbgn/old-sbgn-wiki-archive/blob/master/media:Proposal-FineStructure.doc" title="wikilink">detailed proposal</a> to represent internal structures of entities.</li>
<li>  <a href="/sbgn/old-sbgn-wiki-archive/blob/master/media:P53-structure.pdf" title="wikilink">map of p53</a></li>
<li>  <a href="/sbgn/old-sbgn-wiki-archive/blob/master/media:P53-structure-description.doc" title="wikilink">explanation of the map</a></li>
</ul>

<h3><a id="user-content-proposal-by-michael-blinov" class="anchor" href="#proposal-by-michael-blinov" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Proposal by Michael Blinov</h3>

<p>A proposal for hierarchical nesting of entities. It provides a description of domains, sites and individual atoms of biomolecules. The proposal is designed to cover all the requirements and capabilities of subdivision proposal of MIM group. The proposal is consistent with rule-based description used in BioNetGen software and it is expected to be consistent with SBML level 3 extension describing multi-state multi-component species.</p>

<ul>
<li>  <a href="/sbgn/old-sbgn-wiki-archive/blob/master/media:SBGN-hierarchical-blinov.pdf" title="wikilink">Proposal (pdf)</a> to represent internal structures of entities usinh hierarchical nesting.</li>
<li>  <a href="/sbgn/old-sbgn-wiki-archive/blob/master/media:SBGN-hierarchical-blinov.doc" title="wikilink">MS Word file</a>.</li>
<li>  <a href="/sbgn/old-sbgn-wiki-archive/blob/master/media:SBGN-hierarchical-blinov.svg" title="wikilink">Inkscape file</a> with all pictures used in the proposal.</li>
</ul>

<p>Chylek et al. published a paper on "Guidelines for visualizing and annotating rule-based models" (<a href="http://www.ncbi.nlm.nih.gov/pubmed/21647530">http://www.ncbi.nlm.nih.gov/pubmed/21647530</a>) describing a human-readable (vs machine-readable, as the main focus of SBGN efforts) way to describe rule-based models. This approach can be restricted to the SBGN domain to describe multi-component multi-state features, as illustrated in <a href="/sbgn/old-sbgn-wiki-archive/blob/master/media:Chylek2011.pdf" title="wikilink">this figure (pdf)</a></p>

<h3><a id="user-content-current-state-of-discussion" class="anchor" href="#current-state-of-discussion" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Current state of discussion</h3>

<p><a href="/sbgn/old-sbgn-wiki-archive/blob/master/Entity_Relationship_domains" title="wikilink">Minutes of the discussion at SBGN 5 in Stanford</a></p>
</article>
  </div>

</div>

<button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="d-none">Jump to Line</button>
<div id="jump-to-line" style="display:none">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
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
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path></svg>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2016 <span title="0.11175s from github-fe164-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>
  </div>
</div>



    

    <div id="ajax-error-message" class="ajax-error-message flash flash-error">
      <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"></path></svg>
      <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
        <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"></path></svg>
      </button>
      You can't perform that action at this time.
    </div>


      
      <script crossorigin="anonymous" integrity="sha256-QR1hDksrH/o9BjkEU0QG0IyDUdm6m0s/M5urNehrtPM=" src="https://assets-cdn.github.com/assets/frameworks-411d610e4b2b1ffa3d063904534406d08c8351d9ba9b4b3f339bab35e86bb4f3.js"></script>
      <script async="async" crossorigin="anonymous" integrity="sha256-TJJ27E02GJcqxlt55Ns/rm4GRyTtO5Um/Njo9qmthdc=" src="https://assets-cdn.github.com/assets/github-4c9276ec4d3618972ac65b79e4db3fae6e064724ed3b9526fcd8e8f6a9ad85d7.js"></script>
      
      
      
      
      
      
    <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner d-none">
      <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"></path></svg>
      <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
      <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
    </div>
    <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"></path></svg>
    </button>
  </div>
</div>

  </body>
</html>

