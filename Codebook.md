



<!DOCTYPE html>
<html lang="en" class="">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>Getting-and-Cleaning-Data/Codebook.md at master · foxyreign/Getting-and-Cleaning-Data</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="foxyreign/Getting-and-Cleaning-Data" name="twitter:title" /><meta content="Getting-and-Cleaning-Data - Getting and Cleaning Data" name="twitter:description" /><meta content="https://avatars0.githubusercontent.com/u/6061469?v=2&amp;s=400" name="twitter:image:src" />
<meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars0.githubusercontent.com/u/6061469?v=2&amp;s=400" property="og:image" /><meta content="foxyreign/Getting-and-Cleaning-Data" property="og:title" /><meta content="https://github.com/foxyreign/Getting-and-Cleaning-Data" property="og:url" /><meta content="Getting-and-Cleaning-Data - Getting and Cleaning Data" property="og:description" />

      <meta name="browser-stats-url" content="/_stats">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="conduit-xhr" href="https://ghconduit.com:25035">
    <link rel="xhr-socket" href="/_sockets">
    <meta name="pjax-timeout" content="1000">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>
      <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="C98DCF92:33D4:21EB4D3:544D41AF" name="octolytics-dimension-request_id" /><meta content="8368303" name="octolytics-actor-id" /><meta content="rvaldivieso" name="octolytics-actor-login" /><meta content="de185714281a4eeda04aaa90f6cbac0649644fdeae74abcee1ccc64b87ac9513" name="octolytics-actor-hash" />
    
    <meta content="Rails, view, blob#show" name="analytics-event" />

    
    
    <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="7yy8p4nKhMmyTe512VWKDcf2NXNn43jjWhltA1Qn6JiF/8kRIvE10hfNR1MXrEIreT5zF9XW38iHHYEjombkTw==" name="csrf-token" />

    <link href="https://assets-cdn.github.com/assets/github-fd24da028f7f2d737c9a6d97bdd8aa7a5d7ec419c4cc4e89b169d30c58bed96b.css" media="all" rel="stylesheet" type="text/css" />
    <link href="https://assets-cdn.github.com/assets/github2-e601e4dc2eec6decc441b9f7e15eec77891539a1a5e2d8af7af600d1d061a150.css" media="all" rel="stylesheet" type="text/css" />
    
    


    <meta http-equiv="x-pjax-version" content="e375408a179f2ef68cd4fb7efa2d26f7">

      
  <meta name="description" content="Getting-and-Cleaning-Data - Getting and Cleaning Data">
  <meta name="go-import" content="github.com/foxyreign/Getting-and-Cleaning-Data git https://github.com/foxyreign/Getting-and-Cleaning-Data.git">

  <meta content="6061469" name="octolytics-dimension-user_id" /><meta content="foxyreign" name="octolytics-dimension-user_login" /><meta content="18573291" name="octolytics-dimension-repository_id" /><meta content="foxyreign/Getting-and-Cleaning-Data" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="18573291" name="octolytics-dimension-repository_network_root_id" /><meta content="foxyreign/Getting-and-Cleaning-Data" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/foxyreign/Getting-and-Cleaning-Data/commits/master.atom" rel="alternate" title="Recent Commits to Getting-and-Cleaning-Data:master" type="application/atom+xml">

  </head>


  <body class="logged_in  env-production  vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      
      


      <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" ga-data-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <form accept-charset="UTF-8" action="/foxyreign/Getting-and-Cleaning-Data/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/foxyreign/Getting-and-Cleaning-Data/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <input type="text"
    class="js-site-search-field is-clearable"
    data-hotkey="s"
    name="q"
    placeholder="Search"
    data-global-scope-placeholder="Search GitHub"
    data-repo-scope-placeholder="Search"
    tabindex="1"
    autocapitalize="off">
  <div class="scope-badge">This repository</div>
</form>
      </div>
      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item explore">
          <a class="header-nav-link" href="/explore" data-ga-click="Header, go to explore, text:explore">Explore</a>
        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="/blog" data-ga-click="Header, go to blog, text:blog">Blog</a>
          </li>
        <li class="header-nav-item">
          <a class="header-nav-link" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
        </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name" href="/rvaldivieso" data-ga-click="Header, go to profile, text:username">
      <img alt="Raúl Valdivieso Martínez" class="avatar" data-user="8368303" height="20" src="https://avatars0.githubusercontent.com/u/8368303?v=2&amp;s=40" width="20" />
      <span class="css-truncate">
        <span class="css-truncate-target">rvaldivieso</span>
      </span>
    </a>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link js-menu-target tooltipped tooltipped-s" href="#" aria-label="Create new..." data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      
<ul class="dropdown-menu">
  <li>
    <a href="/new"><span class="octicon octicon-repo"></span> New repository</a>
  </li>
  <li>
    <a href="/organizations/new"><span class="octicon octicon-organization"></span> New organization</a>
  </li>


    <li class="dropdown-divider"></li>
    <li class="dropdown-header">
      <span title="foxyreign/Getting-and-Cleaning-Data">This repository</span>
    </li>
      <li>
        <a href="/foxyreign/Getting-and-Cleaning-Data/issues/new"><span class="octicon octicon-issue-opened"></span> New issue</a>
      </li>
</ul>

    </div>
  </li>

  <li class="header-nav-item">
        <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
        <span class="mail-status all-read"></span>
        <span class="octicon octicon-inbox"></span>
</a>
  </li>

  <li class="header-nav-item">
    <a class="header-nav-link tooltipped tooltipped-s" href="/settings/profile" id="account_settings" aria-label="Settings" data-ga-click="Header, go to settings, icon:settings">
      <span class="octicon octicon-gear"></span>
    </a>
  </li>

  <li class="header-nav-item">
    <form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="IYMBk4B4UVzbteYZ/asyKCAIrMqqbc4kCTtQBfAQ/6rQhd60t2s42U7zA3Dek4lXqnPrbiWFh/IVM1DwBwAUzw==" /></div>
      <button class="header-nav-link sign-out-button tooltipped tooltipped-s" aria-label="Sign out" data-ga-click="Header, sign out, icon:logout">
        <span class="octicon octicon-sign-out"></span>
      </button>
</form>  </li>

</ul>


    
  </div>
</div>

      

        


      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    <div id="js-flash-container">
      
    </div>
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">
        
<ul class="pagehead-actions">

    <li class="subscription">
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="bFkeg/+z+jjucBK+rMoGybwbzehiWhTV3SYr89by89FSxmHeUxIwPsA0R9Spa8Z20ttQLJ7anpjkjN1ip58mSA==" /></div>  <input id="repository_id" name="repository_id" type="hidden" value="18573291" />

    <div class="select-menu js-menu-container js-select-menu">
      <a class="social-count js-social-count" href="/foxyreign/Getting-and-Cleaning-Data/watchers">
        1
      </a>
      <a href="/foxyreign/Getting-and-Cleaning-Data/subscription"
        class="minibutton select-menu-button with-count js-menu-target" role="button" tabindex="0" aria-haspopup="true">
        <span class="js-select-button">
          <span class="octicon octicon-eye"></span>
          Watch
        </span>
      </a>

      <div class="select-menu-modal-holder">
        <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
          <div class="select-menu-header">
            <span class="select-menu-title">Notifications</span>
            <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
          </div> <!-- /.select-menu-header -->

          <div class="select-menu-list js-navigation-container" role="menu">

            <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                <h4>Not watching</h4>
                <span class="description">Be notified when participating or @mentioned.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-eye"></span>
                  Watch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                <h4>Watching</h4>
                <span class="description">Be notified of all conversations.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-eye"></span>
                  Unwatch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input id="do_ignore" name="do" type="radio" value="ignore" />
                <h4>Ignoring</h4>
                <span class="description">Never be notified.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-mute"></span>
                  Stop ignoring
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

          </div> <!-- /.select-menu-list -->

        </div> <!-- /.select-menu-modal -->
      </div> <!-- /.select-menu-modal-holder -->
    </div> <!-- /.select-menu -->

</form>
    </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <form accept-charset="UTF-8" action="/foxyreign/Getting-and-Cleaning-Data/unstar" class="js-toggler-form starred js-unstar-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="K7+5CgGtSds+7KAFFhPJMY9+N137hxB/SMbJWhFl8fRO++kxvHLWx4Rp/sTZMtSgwGkkWjKdT/1D5xIiIqi3dA==" /></div>
      <button
        class="minibutton with-count js-toggler-target star-button"
        aria-label="Unstar this repository" title="Unstar foxyreign/Getting-and-Cleaning-Data">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/foxyreign/Getting-and-Cleaning-Data/stargazers">
          0
        </a>
</form>
    <form accept-charset="UTF-8" action="/foxyreign/Getting-and-Cleaning-Data/star" class="js-toggler-form unstarred js-star-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="01gNzArtkuU3/nl3vdXLxzHp5zmGS/gQiIDw3L3NaGuoJscppzgtdTPgCPm1EDDMW5KxZQ9j83lxH1NS1njaQQ==" /></div>
      <button
        class="minibutton with-count js-toggler-target star-button"
        aria-label="Star this repository" title="Star foxyreign/Getting-and-Cleaning-Data">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/foxyreign/Getting-and-Cleaning-Data/stargazers">
          0
        </a>
</form>  </div>

  </li>


        <li>
          <a href="/foxyreign/Getting-and-Cleaning-Data/fork" class="minibutton with-count js-toggler-target fork-button tooltipped-n" title="Fork your own copy of foxyreign/Getting-and-Cleaning-Data to your account" aria-label="Fork your own copy of foxyreign/Getting-and-Cleaning-Data to your account" rel="nofollow" data-method="post">
            <span class="octicon octicon-repo-forked"></span>
            Fork
          </a>
          <a href="/foxyreign/Getting-and-Cleaning-Data/network" class="social-count">2</a>
        </li>

</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/foxyreign" class="url fn" itemprop="url" rel="author"><span itemprop="title">foxyreign</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/foxyreign/Getting-and-Cleaning-Data" class="js-current-repository js-repo-home-link" data-pjax-container-selector="#js-repo-pjax-container">Getting-and-Cleaning-Data</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
          </span>

        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline  ">
        <div class="repository-sidebar clearfix">
            
<div class="sunken-menu vertical-right repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders" role="navigation" data-issue-count-url="/foxyreign/Getting-and-Cleaning-Data/issues/counts" data-pjax-container-selector="#js-repo-pjax-container">
  <div class="sunken-menu-contents">
    <ul class="sunken-menu-group">
      <li class="tooltipped tooltipped-w" aria-label="Code">
        <a href="/foxyreign/Getting-and-Cleaning-Data" aria-label="Code" class="selected js-selected-navigation-item sunken-menu-item" data-hotkey="g c" data-pjax="true" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /foxyreign/Getting-and-Cleaning-Data">
          <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

        <li class="tooltipped tooltipped-w" aria-label="Issues">
          <a href="/foxyreign/Getting-and-Cleaning-Data/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item js-disable-pjax" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /foxyreign/Getting-and-Cleaning-Data/issues">
            <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
            <span class="js-issue-replace-counter"></span>
            <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>        </li>

      <li class="tooltipped tooltipped-w" aria-label="Pull Requests">
        <a href="/foxyreign/Getting-and-Cleaning-Data/pulls" aria-label="Pull Requests" class="js-selected-navigation-item sunken-menu-item js-disable-pjax" data-hotkey="g p" data-selected-links="repo_pulls /foxyreign/Getting-and-Cleaning-Data/pulls">
            <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull Requests</span>
            <span class="js-pull-replace-counter"></span>
            <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>


        <li class="tooltipped tooltipped-w" aria-label="Wiki">
          <a href="/foxyreign/Getting-and-Cleaning-Data/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item js-disable-pjax" data-hotkey="g w" data-selected-links="repo_wiki /foxyreign/Getting-and-Cleaning-Data/wiki">
            <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
            <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>        </li>
    </ul>
    <div class="sunken-menu-separator"></div>
    <ul class="sunken-menu-group">

      <li class="tooltipped tooltipped-w" aria-label="Pulse">
        <a href="/foxyreign/Getting-and-Cleaning-Data/pulse/weekly" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-pjax="true" data-selected-links="pulse /foxyreign/Getting-and-Cleaning-Data/pulse/weekly">
          <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

      <li class="tooltipped tooltipped-w" aria-label="Graphs">
        <a href="/foxyreign/Getting-and-Cleaning-Data/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-pjax="true" data-selected-links="repo_graphs repo_contributors /foxyreign/Getting-and-Cleaning-Data/graphs">
          <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>
    </ul>


  </div>
</div>

              <div class="only-with-full-nav">
                
  
<div class="clone-url open"
  data-protocol-type="http"
  data-url="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group">
    <input type="text" class="input-mini input-monospace js-url-field"
           value="https://github.com/foxyreign/Getting-and-Cleaning-Data.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-clipboard-text="https://github.com/foxyreign/Getting-and-Cleaning-Data.git" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="ssh"
  data-url="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone">
  <h3><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group">
    <input type="text" class="input-mini input-monospace js-url-field"
           value="git@github.com:foxyreign/Getting-and-Cleaning-Data.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-clipboard-text="git@github.com:foxyreign/Getting-and-Cleaning-Data.git" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="subversion"
  data-url="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group">
    <input type="text" class="input-mini input-monospace js-url-field"
           value="https://github.com/foxyreign/Getting-and-Cleaning-Data" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-clipboard-text="https://github.com/foxyreign/Getting-and-Cleaning-Data" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>


<p class="clone-options">You can clone with
      <a href="#" class="js-clone-selector" data-protocol="http">HTTPS</a>,
      <a href="#" class="js-clone-selector" data-protocol="ssh">SSH</a>,
      or <a href="#" class="js-clone-selector" data-protocol="subversion">Subversion</a>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</p>



                <a href="/foxyreign/Getting-and-Cleaning-Data/archive/master.zip"
                   class="minibutton sidebar-button"
                   aria-label="Download the contents of foxyreign/Getting-and-Cleaning-Data as a zip file"
                   title="Download the contents of foxyreign/Getting-and-Cleaning-Data as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>
          

<a href="/foxyreign/Getting-and-Cleaning-Data/blob/5064ddb52831676669c37cdf00b33d69b8ef7a7e/Codebook.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:75ac926f48aca05338d5b4f6cec2468b -->

<div class="file-navigation">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="minibutton select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-master-branch="master"
    data-ref="master"
    title="master"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div> <!-- /.select-menu-header -->

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" class="js-select-menu-tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" class="js-select-menu-tab">Tags</a>
            </li>
          </ul>
        </div><!-- /.select-menu-tabs -->
      </div><!-- /.select-menu-filters -->

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <div class="select-menu-item js-navigation-item selected">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/foxyreign/Getting-and-Cleaning-Data/blob/master/Codebook.md"
                 data-name="master"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="master">master</a>
            </div> <!-- /.select-menu-item -->
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div> <!-- /.select-menu-list -->

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div> <!-- /.select-menu-list -->

    </div> <!-- /.select-menu-modal -->
  </div> <!-- /.select-menu-modal-holder -->
</div> <!-- /.select-menu -->

  <div class="button-group right">
    <a href="/foxyreign/Getting-and-Cleaning-Data/find/master"
          class="js-show-file-finder minibutton empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button class="js-zeroclipboard minibutton zeroclipboard-button"
          data-clipboard-text="Codebook.md"
          aria-label="Copy to clipboard"
          data-copied-hint="Copied!">
      <span class="octicon octicon-clippy"></span>
    </button>
  </div>

  <div class="breadcrumb">
    <span class='repo-root js-repo-root'><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/foxyreign/Getting-and-Cleaning-Data" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">Getting-and-Cleaning-Data</span></a></span></span><span class="separator"> / </span><strong class="final-path">Codebook.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="Adrian Cuyugan" class="avatar" data-user="6061469" height="24" src="https://avatars1.githubusercontent.com/u/6061469?v=2&amp;s=48" width="24" />
        <span class="author"><a href="/foxyreign" rel="author">foxyreign</a></span>
        <time datetime="2014-05-20T15:59:49Z" is="relative-time">May 20, 2014</time>
        <div class="commit-title">
            <a href="/foxyreign/Getting-and-Cleaning-Data/commit/812b2c48b87f0e1aaae85b5b4f32c7abe423853e" class="message" data-pjax="true" title="Modify attribute info">Modify attribute info</a>
        </div>
    </div>

    <div class="participation">
      <p class="quickstat">
        <a href="#blob_contributors_box" rel="facebox">
          <strong>1</strong>
           contributor
        </a>
      </p>
      
    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list">
          <li class="facebox-user-list-item">
            <img alt="Adrian Cuyugan" data-user="6061469" height="24" src="https://avatars1.githubusercontent.com/u/6061469?v=2&amp;s=48" width="24" />
            <a href="/foxyreign">foxyreign</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file-box">
  <div class="file">
    <div class="meta clearfix">
      <div class="info file-name">
          <span>101 lines (87 sloc)</span>
          <span class="meta-divider"></span>
        <span>7.553 kb</span>
      </div>
      <div class="actions">
        <div class="button-group">
          <a href="/foxyreign/Getting-and-Cleaning-Data/raw/master/Codebook.md" class="minibutton " id="raw-url">Raw</a>
            <a href="/foxyreign/Getting-and-Cleaning-Data/blame/master/Codebook.md" class="minibutton js-update-url-with-hash">Blame</a>
          <a href="/foxyreign/Getting-and-Cleaning-Data/commits/master/Codebook.md" class="minibutton " rel="nofollow">History</a>
        </div><!-- /.button-group -->


              <a class="octicon-button tooltipped tooltipped-n js-update-url-with-hash"
                 aria-label="Clicking this button will fork this project so you can edit the file"
                 href="/foxyreign/Getting-and-Cleaning-Data/edit/master/Codebook.md"
                 data-method="post" rel="nofollow"><span class="octicon octicon-pencil"></span></a>

            <a class="octicon-button danger tooltipped tooltipped-s"
               href="/foxyreign/Getting-and-Cleaning-Data/delete/master/Codebook.md"
               aria-label="Fork this project and delete file"
               data-method="post" data-test-id="delete-blob-file" rel="nofollow">
          <span class="octicon octicon-trashcan"></span>
        </a>
      </div><!-- /.actions -->
    </div>
      <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1>
<a name="user-content-codebook" class="anchor" href="#codebook" aria-hidden="true"><span class="octicon octicon-link"></span></a>Codebook</h1>

<h2>
<a name="user-content-data-set-information" class="anchor" href="#data-set-information" aria-hidden="true"><span class="octicon octicon-link"></span></a>Data Set Information</h2>

<p>The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.</p>

<p>The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain. </p>

<h2>
<a name="user-content-attribute-information" class="anchor" href="#attribute-information" aria-hidden="true"><span class="octicon octicon-link"></span></a>Attribute Information</h2>

<p>For each record in the dataset it is provided:</p>

<ul class="task-list">
<li>Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.</li>
<li>Triaxial Angular velocity from the gyroscope.</li>
<li>Its activity label.</li>
</ul>

<h2>
<a name="user-content-citation-request" class="anchor" href="#citation-request" aria-hidden="true"><span class="octicon octicon-link"></span></a>Citation Request</h2>

<p>[1] Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. Human Activity Recognition on Smartphones using a Multiclass Hardware-Friendly Support Vector Machine. International Workshop of Ambient Assisted Living (IWAAL 2012). Vitoria-Gasteiz, Spain. Dec 2012</p>

<p><a href="http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones">http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones</a></p>

<h3>
<a name="user-content-variable-descriptions" class="anchor" href="#variable-descriptions" aria-hidden="true"><span class="octicon octicon-link"></span></a>Variable Descriptions</h3>

<table>
<thead>
<tr>
<th>Variable</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>subject</td>
<td>Subject ID</td>
</tr>
<tr>
<td>tbodyacc.mean.x</td>
<td>Mean time for acceleration of body for X direction</td>
</tr>
<tr>
<td>tbodyacc.mean.y</td>
<td>Mean time for acceleration of body for Y direction</td>
</tr>
<tr>
<td>tbodyacc.mean.z</td>
<td>Mean time for acceleration of body for Z direction</td>
</tr>
<tr>
<td>tbodyacc.std.x</td>
<td>Standard deviation of time for acceleration of body for X direction</td>
</tr>
<tr>
<td>tbodyacc.std.y</td>
<td>Standard deviation of time for acceleration of body for Y direction</td>
</tr>
<tr>
<td>tbodyacc.std.z</td>
<td>Standard deviation of time for acceleration of body for Z direction</td>
</tr>
<tr>
<td>tgravityacc.mean.x</td>
<td>Mean time of acceleration of gravity for X direction</td>
</tr>
<tr>
<td>tgravityacc.mean.y</td>
<td>Mean time of acceleration of gravity for Y direction</td>
</tr>
<tr>
<td>tgravityacc.mean.z</td>
<td>Mean time of acceleration of gravity for Z direction</td>
</tr>
<tr>
<td>tgravityacc.std.x</td>
<td>Standard deviation of time of acceleration of gravity for X direction</td>
</tr>
<tr>
<td>tgravityacc.std.y</td>
<td>Standard deviation of time of acceleration of gravity for Y direction</td>
</tr>
<tr>
<td>tgravityacc.std.z</td>
<td>Standard deviation of time of acceleration of gravity for Z direction</td>
</tr>
<tr>
<td>tbodyaccjerk.mean.x</td>
<td>Mean time of body acceleration jerk for X direction</td>
</tr>
<tr>
<td>tbodyaccjerk.mean.y</td>
<td>Mean time of body acceleration jerk for Y direction</td>
</tr>
<tr>
<td>tbodyaccjerk.mean.z</td>
<td>Mean time of body acceleration jerk for Z direction</td>
</tr>
<tr>
<td>tbodyaccjerk.std.x</td>
<td>Standard deviation of time of body acceleration jerk for X direction</td>
</tr>
<tr>
<td>tbodyaccjerk.std.y</td>
<td>Standard deviation of time of body acceleration jerk for Y direction</td>
</tr>
<tr>
<td>tbodyaccjerk.std.z</td>
<td>Standard deviation of time of body acceleration jerk for Z direction</td>
</tr>
<tr>
<td>tbodygyro.mean.x</td>
<td>Mean body gyroscope measurement for X direction</td>
</tr>
<tr>
<td>tbodygyro.mean.y</td>
<td>Mean body gyroscope measurement for Y direction</td>
</tr>
<tr>
<td>tbodygyro.mean.z</td>
<td>Mean body gyroscope measurement for Z direction</td>
</tr>
<tr>
<td>tbodygyro.std.x</td>
<td>Standard deviation of body gyroscope measurement for X direction</td>
</tr>
<tr>
<td>tbodygyro.std.y</td>
<td>Standard deviation of body gyroscope measurement for Y direction</td>
</tr>
<tr>
<td>tbodygyro.std.z</td>
<td>Standard deviation of body gyroscope measurement for Z direction</td>
</tr>
<tr>
<td>tbodygyrojerk.mean.x</td>
<td>Mean jerk signal of body for X direction</td>
</tr>
<tr>
<td>tbodygyrojerk.mean.y</td>
<td>Mean jerk signal of body for Y direction</td>
</tr>
<tr>
<td>tbodygyrojerk.mean.z</td>
<td>Mean jerk signal of body for Z direction</td>
</tr>
<tr>
<td>tbodygyrojerk.std.x</td>
<td>Standard deviation of jerk signal of body for X direction</td>
</tr>
<tr>
<td>tbodygyrojerk.std.y</td>
<td>Standard deviation of jerk signal of body for Y direction</td>
</tr>
<tr>
<td>tbodygyrojerk.std.z</td>
<td>Standard deviation of jerk signal of body for Z direction</td>
</tr>
<tr>
<td>tbodyaccmag.mean</td>
<td>Mean magnitude of body Acc</td>
</tr>
<tr>
<td>tbodyaccmag.std</td>
<td>Standard deviation of magnitude of body Acc</td>
</tr>
<tr>
<td>tgravityaccmag.mean</td>
<td>Mean gravity acceleration magnitude</td>
</tr>
<tr>
<td>tgravityaccmag.std</td>
<td>Standard deviation of gravity acceleration magnitude</td>
</tr>
<tr>
<td>tbodyaccjerkmag.mean</td>
<td>Mean magnitude of body acceleration jerk</td>
</tr>
<tr>
<td>tbodyaccjerkmag.std</td>
<td>Standard deviation of magnitude of body acceleration jerk</td>
</tr>
<tr>
<td>tbodygyromag.mean</td>
<td>Mean magnitude of body gyroscope measurement</td>
</tr>
<tr>
<td>tbodygyromag.std</td>
<td>Standard deviation of magnitude of body gyroscope measurement</td>
</tr>
<tr>
<td>tbodygyrojerkmag.mean</td>
<td>Mean magnitude of body body gyroscope jerk measurement</td>
</tr>
<tr>
<td>tbodygyrojerkmag.std</td>
<td>Standard deviation of magnitude of body body gyroscope jerk measurement</td>
</tr>
<tr>
<td>fbodyacc.mean.x</td>
<td>Mean frequency of body acceleration for X direction</td>
</tr>
<tr>
<td>fbodyacc.mean.y</td>
<td>Mean frequency of body acceleration for Y direction</td>
</tr>
<tr>
<td>fbodyacc.mean.z</td>
<td>Mean frequency of body acceleration for Z direction</td>
</tr>
<tr>
<td>fbodyacc.std.x</td>
<td>Standard deviation of frequency of body acceleration for X direction</td>
</tr>
<tr>
<td>fbodyacc.std.y</td>
<td>Standard deviation of frequency of body acceleration for Y direction</td>
</tr>
<tr>
<td>fbodyacc.std.z</td>
<td>Standard deviation of frequency of body acceleration for Z direction</td>
</tr>
<tr>
<td>fbodyaccjerk.mean.x</td>
<td>Mean frequency of body accerlation jerk for X direction</td>
</tr>
<tr>
<td>fbodyaccjerk.mean.y</td>
<td>Mean frequency of body accerlation jerk for Y direction</td>
</tr>
<tr>
<td>fbodyaccjerk.mean.z</td>
<td>Mean frequency of body accerlation jerk for Z direction</td>
</tr>
<tr>
<td>fbodyaccjerk.std.x</td>
<td>Standard deviation frequency of body accerlation jerk for X direction</td>
</tr>
<tr>
<td>fbodyaccjerk.std.y</td>
<td>Standard deviation frequency of body accerlation jerk for Y direction</td>
</tr>
<tr>
<td>fbodyaccjerk.std.z</td>
<td>Standard deviation frequency of body accerlation jerk for Z direction</td>
</tr>
<tr>
<td>fbodygyro.mean.x</td>
<td>Mean frequency of body gyroscope measurement for X direction</td>
</tr>
<tr>
<td>fbodygyro.mean.y</td>
<td>Mean frequency of body gyroscope measurement for Y direction</td>
</tr>
<tr>
<td>fbodygyro.mean.z</td>
<td>Mean frequency of body gyroscope measurement for Z direction</td>
</tr>
<tr>
<td>fbodygyro.std.x</td>
<td>Standard deviation frequency of body gyroscope measurement for X direction</td>
</tr>
<tr>
<td>fbodygyro.std.y</td>
<td>Standard deviation frequency of body gyroscope measurement for Y direction</td>
</tr>
<tr>
<td>fbodygyro.std.z</td>
<td>Standard deviation frequency of body gyroscope measurement for Z direction</td>
</tr>
<tr>
<td>fbodyaccmag.mean</td>
<td>Mean frequency of body acceleration magnitude</td>
</tr>
<tr>
<td>fbodyaccmag.std</td>
<td>Standard deviation of frequency of body acceleration magnitude</td>
</tr>
<tr>
<td>fbodybodyaccjerkmag.mean</td>
<td>Mean frequency of body acceleration jerk magnitude</td>
</tr>
<tr>
<td>fbodybodyaccjerkmag.std</td>
<td>Standard deviation of frequency of body acceleration jerk magnitude</td>
</tr>
<tr>
<td>fbodybodygyromag.mean</td>
<td>Mean frequency of magnitude of body gyroscope measurement</td>
</tr>
<tr>
<td>fbodybodygyromag.std</td>
<td>Standard deviation of frequency of magnitude of body gyroscope measurement</td>
</tr>
<tr>
<td>fbodybodygyrojerkmag.mean</td>
<td>Mean frequency of magnitude of body gyroscope jerk measurement</td>
</tr>
<tr>
<td>fbodybodygyrojerkmag.std</td>
<td>Standard deviation frequency of magnitude of body gyroscope jerk measurement</td>
</tr>
<tr>
<td>activity</td>
<td>The activity performed</td>
</tr>
</tbody>
</table>
</article>
  </div>

  </div>
</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" class="js-jump-to-line-form">
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="button">Go</button>
  </form>
</div>

        </div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
      <li><a href="https://status.github.com/">Status</a></li>
      <li><a href="https://developer.github.com">API</a></li>
      <li><a href="http://training.github.com">Training</a></li>
      <li><a href="http://shop.github.com">Shop</a></li>
      <li><a href="/blog">Blog</a></li>
      <li><a href="/about">About</a></li>

    </ul>

    <a href="/" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
    </a>

    <ul class="site-footer-links">
      <li>&copy; 2014 <span title="0.03811s from github-fe131-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="/site/terms">Terms</a></li>
        <li><a href="/site/privacy">Privacy</a></li>
        <li><a href="/security">Security</a></li>
        <li><a href="/contact">Contact</a></li>
    </ul>
  </div><!-- /.site-footer -->
</div><!-- /.container -->


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents js-suggester-field" placeholder=""></textarea>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped tooltipped-w" aria-label="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped tooltipped-w"
      aria-label="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-x flash-close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-dabc650f8a51dffd1d4376a3522cbda5536e4807e01d2a86ff7e60d8d6ee3029.js" type="text/javascript"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-d01013daa80c5a341ba3ddb684f2f26679eb369d67459151d5175a634a9e98a5.js" type="text/javascript"></script>
      
      
  </body>
</html>

