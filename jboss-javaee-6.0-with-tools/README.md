


<!DOCTYPE html>
<html>
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# githubog: http://ogp.me/ns/fb/githubog#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>jboss-eap-boms/jboss-javaee-6.0-with-tools/README.md at master · jboss-developer/jboss-eap-boms</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub" />
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub" />
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png" />
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png" />
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png" />
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png" />
    <link rel="logo" type="image/svg" href="https://github-media-downloads.s3.amazonaws.com/github-logo.svg" />
    <meta property="og:image" content="https://github.global.ssl.fastly.net/images/modules/logos_page/Octocat.png">
    <meta name="hostname" content="github-fe125-cp1-prd.iad.github.net">
    <meta name="ruby" content="ruby 2.0.0p247-github5 (2013-06-27) [x86_64-linux]">
    <link rel="assets" href="https://github.global.ssl.fastly.net/">
    <link rel="xhr-socket" href="/_sockets" />
    
    


    <meta name="msapplication-TileImage" content="/windows-tile.png" />
    <meta name="msapplication-TileColor" content="#ffffff" />
    <meta name="selected-link" value="repo_source" data-pjax-transient />
    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="6044667d-4353-4990-aa9f-ea471651f208" name="octolytics-dimension-request_id" /><meta content="177257" name="octolytics-actor-id" /><meta content="mareknovotny" name="octolytics-actor-login" /><meta content="85dd65da23311fb5f0e2f9f97eba86bcd4aaa520601d6d304fe5dcef985d6aab" name="octolytics-actor-hash" />
    

    
    
    <link rel="icon" type="image/x-icon" href="/favicon.ico" />

    <meta content="authenticity_token" name="csrf-param" />
<meta content="mT0Ar9XsyXPCtUC66yJUl+o7sdZUx6hb6T0wWxV6eAA=" name="csrf-token" />

    <link href="https://github.global.ssl.fastly.net/assets/github-1571e8531c9d48a5e17e976e56fb9f29b8e41cf2.css" media="all" rel="stylesheet" type="text/css" />
    <link href="https://github.global.ssl.fastly.net/assets/github2-4aac1f1fa7a38c2fbe63b6951d4f85decbe92c03.css" media="all" rel="stylesheet" type="text/css" />
    

    

      <script src="https://github.global.ssl.fastly.net/assets/frameworks-f86a2975a82dceee28e5afe598d1ebbfd7109d79.js" type="text/javascript"></script>
      <script src="https://github.global.ssl.fastly.net/assets/github-a4a7207e7dacc57635e1d9db14d6becb2053fc5f.js" type="text/javascript"></script>
      
      <meta http-equiv="x-pjax-version" content="f2d29d78ad073bd72577c94b9109a724">

        <link data-pjax-transient rel='permalink' href='/jboss-developer/jboss-eap-boms/blob/3fcde119b5f56ef3a3c2eaadc1aa0723900ceefb/jboss-javaee-6.0-with-tools/README.md'>
  <meta property="og:title" content="jboss-eap-boms"/>
  <meta property="og:type" content="githubog:gitrepository"/>
  <meta property="og:url" content="https://github.com/jboss-developer/jboss-eap-boms"/>
  <meta property="og:image" content="https://github.global.ssl.fastly.net/images/gravatars/gravatar-user-420.png"/>
  <meta property="og:site_name" content="GitHub"/>
  <meta property="og:description" content="jboss-eap-boms - BOMs for JBoss projects"/>

  <meta name="description" content="jboss-eap-boms - BOMs for JBoss projects" />

  <meta content="1744809" name="octolytics-dimension-user_id" /><meta content="jboss-developer" name="octolytics-dimension-user_login" /><meta content="4373770" name="octolytics-dimension-repository_id" /><meta content="jboss-developer/jboss-eap-boms" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="true" name="octolytics-dimension-repository_is_fork" /><meta content="3345981" name="octolytics-dimension-repository_parent_id" /><meta content="jboss/jboss-bom" name="octolytics-dimension-repository_parent_nwo" /><meta content="3345981" name="octolytics-dimension-repository_network_root_id" /><meta content="jboss/jboss-bom" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/jboss-developer/jboss-eap-boms/commits/master.atom" rel="alternate" title="Recent Commits to jboss-eap-boms:master" type="application/atom+xml" />

  </head>


  <body class="logged_in  env-production linux vis-public fork page-blob">
    <div class="wrapper">
      
      
      


      <div class="header header-logged-in true">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/organizations/jboss-eap">
  <span class="mega-octicon octicon-mark-github"></span>
</a>

    <div class="divider-vertical"></div>

    
    <a href="/notifications" class="notification-indicator tooltipped downwards" data-gotokey="n" title="You have unread notifications">
        <span class="mail-status unread"></span>
</a>    <div class="divider-vertical"></div>


      <div class="command-bar js-command-bar  in-repository">
          <form accept-charset="UTF-8" action="/search" class="command-bar-form" id="top_search_form" method="get">

<input type="text" data-hotkey="/ s" name="q" id="js-command-bar-field" placeholder="Search or type a command" tabindex="1" autocapitalize="off"
    
    data-username="mareknovotny"
      data-repo="jboss-developer/jboss-eap-boms"
      data-branch="master"
      data-sha="335a08a7ae02139468f8d909e8492c383de5cfbb"
  >

    <input type="hidden" name="nwo" value="jboss-developer/jboss-eap-boms" />

    <div class="select-menu js-menu-container js-select-menu search-context-select-menu">
      <span class="minibutton select-menu-button js-menu-target">
        <span class="js-select-button">This repository</span>
      </span>

      <div class="select-menu-modal-holder js-menu-content js-navigation-container">
        <div class="select-menu-modal">

          <div class="select-menu-item js-navigation-item js-this-repository-navigation-item selected">
            <span class="select-menu-item-icon octicon octicon-check"></span>
            <input type="radio" class="js-search-this-repository" name="search_target" value="repository" checked="checked" />
            <div class="select-menu-item-text js-select-button-text">This repository</div>
          </div> <!-- /.select-menu-item -->

          <div class="select-menu-item js-navigation-item js-all-repositories-navigation-item">
            <span class="select-menu-item-icon octicon octicon-check"></span>
            <input type="radio" name="search_target" value="global" />
            <div class="select-menu-item-text js-select-button-text">All repositories</div>
          </div> <!-- /.select-menu-item -->

        </div>
      </div>
    </div>

  <span class="octicon help tooltipped downwards" title="Show command bar help">
    <span class="octicon octicon-question"></span>
  </span>


  <input type="hidden" name="ref" value="cmdform">

</form>
        <ul class="top-nav">
          <li class="explore"><a href="/explore">Explore</a></li>
            <li><a href="https://gist.github.com">Gist</a></li>
            <li><a href="/blog">Blog</a></li>
          <li><a href="https://help.github.com">Help</a></li>
        </ul>
      </div>

    


  <ul id="user-links">
    <li>
      <a href="/mareknovotny" class="name">
        <img height="20" src="https://2.gravatar.com/avatar/e0e735e337e8c7eadb8079aaa12c77ec?d=https%3A%2F%2Fidenticons.github.com%2F572cfd33e6aaafd8476474011af5b59d.png&amp;s=140" width="20" /> mareknovotny
      </a>
    </li>

      <li>
        <a href="/new" id="new_repo" class="tooltipped downwards" title="Create a new repo" aria-label="Create a new repo">
          <span class="octicon octicon-repo-create"></span>
        </a>
      </li>

      <li>
        <a href="/settings/profile" id="account_settings"
          class="tooltipped downwards"
          aria-label="Account settings "
          title="Account settings ">
          <span class="octicon octicon-tools"></span>
        </a>
      </li>
      <li>
        <a class="tooltipped downwards" href="/logout" data-method="post" id="logout" title="Sign out" aria-label="Sign out">
          <span class="octicon octicon-log-out"></span>
        </a>
      </li>

  </ul>

<div class="js-new-dropdown-contents hidden">
  

<ul class="dropdown-menu">
  <li>
    <a href="/new"><span class="octicon octicon-repo-create"></span> New repository</a>
  </li>
  <li>
    <a href="/organizations/new"><span class="octicon octicon-organization"></span> New organization</a>
  </li>



    <li class="section-title">
      <span title="jboss-developer/jboss-eap-boms">This repository</span>
    </li>
    <li>
      <a href="/jboss-developer/jboss-eap-boms/issues/new"><span class="octicon octicon-issue-opened"></span> New issue</a>
    </li>
</ul>

</div>


    
  </div>
</div>

      

      




          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">
        

<ul class="pagehead-actions">

    <li class="subscription">
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="authenticity_token" type="hidden" value="mT0Ar9XsyXPCtUC66yJUl+o7sdZUx6hb6T0wWxV6eAA=" /></div>  <input id="repository_id" name="repository_id" type="hidden" value="4373770" />

    <div class="select-menu js-menu-container js-select-menu">
        <a class="social-count js-social-count" href="/jboss-developer/jboss-eap-boms/watchers">
          6
        </a>
      <span class="minibutton select-menu-button with-count js-menu-target" role="button" tabindex="0">
        <span class="js-select-button">
          <span class="octicon octicon-eye-watch"></span>
          Watch
        </span>
      </span>

      <div class="select-menu-modal-holder">
        <div class="select-menu-modal subscription-menu-modal js-menu-content">
          <div class="select-menu-header">
            <span class="select-menu-title">Notification status</span>
            <span class="octicon octicon-remove-close js-menu-close"></span>
          </div> <!-- /.select-menu-header -->

          <div class="select-menu-list js-navigation-container" role="menu">

            <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                <h4>Not watching</h4>
                <span class="description">You only receive notifications for discussions in which you participate or are @mentioned.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-eye-watch"></span>
                  Watch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                <h4>Watching</h4>
                <span class="description">You receive notifications for all discussions in this repository.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-eye-unwatch"></span>
                  Unwatch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input id="do_ignore" name="do" type="radio" value="ignore" />
                <h4>Ignoring</h4>
                <span class="description">You do not receive any notifications for discussions in this repository.</span>
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
  <a href="/jboss-developer/jboss-eap-boms/unstar" class="minibutton with-count js-toggler-target star-button starred upwards" title="Unstar this repo" data-remote="true" data-method="post" rel="nofollow">
    <span class="octicon octicon-star-delete"></span><span class="text">Unstar</span>
  </a>
  <a href="/jboss-developer/jboss-eap-boms/star" class="minibutton with-count js-toggler-target star-button unstarred upwards" title="Star this repo" data-remote="true" data-method="post" rel="nofollow">
    <span class="octicon octicon-star"></span><span class="text">Star</span>
  </a>
  <a class="social-count js-social-count" href="/jboss-developer/jboss-eap-boms/stargazers">15</a>
</div>

  </li>


        <li>
          <a href="/jboss-developer/jboss-eap-boms/fork" class="minibutton with-count js-toggler-target fork-button lighter upwards" title="Fork this repo" rel="facebox nofollow">
            <span class="octicon octicon-git-branch-create"></span><span class="text">Fork</span>
          </a>
          <a href="/jboss-developer/jboss-eap-boms/network" class="social-count">33</a>
        </li>


</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="repo-label"><span>public</span></span>
          <span class="mega-octicon octicon-repo-forked"></span>
          <span class="author">
            <a href="/jboss-developer" class="url fn" itemprop="url" rel="author"><span itemprop="title">jboss-developer</span></a></span
          ><span class="repohead-name-divider">/</span><strong
          ><a href="/jboss-developer/jboss-eap-boms" class="js-current-repository js-repo-home-link">jboss-eap-boms</a></strong>

          <span class="page-context-loader">
            <img alt="Octocat-spinner-32" height="16" src="https://github.global.ssl.fastly.net/images/spinners/octocat-spinner-32.gif" width="16" />
          </span>

            <span class="fork-flag">
              <span class="text">forked from <a href="/jboss/jboss-bom">jboss/jboss-bom</a></span>
            </span>
        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">

      <div class="repository-with-sidebar repo-container ">

        <div class="repository-sidebar">
            

<div class="repo-nav repo-nav-full js-repository-container-pjax js-octicon-loaders">
  <div class="repo-nav-contents">
    <ul class="repo-menu">
      <li class="tooltipped leftwards" title="Code">
        <a href="/jboss-developer/jboss-eap-boms" aria-label="Code" class="js-selected-navigation-item selected" data-gotokey="c" data-pjax="true" data-selected-links="repo_source repo_downloads repo_commits repo_tags repo_branches /jboss-developer/jboss-eap-boms">
          <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
          <img alt="Octocat-spinner-32" class="mini-loader" height="16" src="https://github.global.ssl.fastly.net/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>


      <li class="tooltipped leftwards" title="Pull Requests"><a href="/jboss-developer/jboss-eap-boms/pulls" aria-label="Pull Requests" class="js-selected-navigation-item js-disable-pjax" data-gotokey="p" data-selected-links="repo_pulls /jboss-developer/jboss-eap-boms/pulls">
            <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull Requests</span>
            <span class='counter'>0</span>
            <img alt="Octocat-spinner-32" class="mini-loader" height="16" src="https://github.global.ssl.fastly.net/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>


        <li class="tooltipped leftwards" title="Wiki">
          <a href="/jboss-developer/jboss-eap-boms/wiki" aria-label="Wiki" class="js-selected-navigation-item " data-pjax="true" data-selected-links="repo_wiki /jboss-developer/jboss-eap-boms/wiki">
            <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
            <img alt="Octocat-spinner-32" class="mini-loader" height="16" src="https://github.global.ssl.fastly.net/images/spinners/octocat-spinner-32.gif" width="16" />
</a>        </li>
    </ul>
    <div class="repo-menu-separator"></div>
    <ul class="repo-menu">

      <li class="tooltipped leftwards" title="Pulse">
        <a href="/jboss-developer/jboss-eap-boms/pulse" aria-label="Pulse" class="js-selected-navigation-item " data-pjax="true" data-selected-links="pulse /jboss-developer/jboss-eap-boms/pulse">
          <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
          <img alt="Octocat-spinner-32" class="mini-loader" height="16" src="https://github.global.ssl.fastly.net/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

      <li class="tooltipped leftwards" title="Graphs">
        <a href="/jboss-developer/jboss-eap-boms/graphs" aria-label="Graphs" class="js-selected-navigation-item " data-pjax="true" data-selected-links="repo_graphs repo_contributors /jboss-developer/jboss-eap-boms/graphs">
          <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
          <img alt="Octocat-spinner-32" class="mini-loader" height="16" src="https://github.global.ssl.fastly.net/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

      <li class="tooltipped leftwards" title="Network">
        <a href="/jboss-developer/jboss-eap-boms/network" aria-label="Network" class="js-selected-navigation-item js-disable-pjax" data-selected-links="repo_network /jboss-developer/jboss-eap-boms/network">
          <span class="octicon octicon-git-branch"></span> <span class="full-word">Network</span>
          <img alt="Octocat-spinner-32" class="mini-loader" height="16" src="https://github.global.ssl.fastly.net/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>
    </ul>


  </div>
</div>

            <div class="only-with-full-nav">
              

  

<div class="clone-url "
  data-protocol-type="http"
  data-url="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone">
  <h3><strong>HTTPS</strong> clone URL</h3>
  <div class="clone-url-box">
    <input type="text" class="clone js-url-field"
           value="https://github.com/jboss-developer/jboss-eap-boms.git" readonly="readonly">

    <span class="js-zeroclipboard url-box-clippy minibutton zeroclipboard-button" data-clipboard-text="https://github.com/jboss-developer/jboss-eap-boms.git" data-copied-hint="copied!" title="copy to clipboard"><span class="octicon octicon-clippy"></span></span>
  </div>
</div>

  

<div class="clone-url open"
  data-protocol-type="ssh"
  data-url="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone">
  <h3><strong>SSH</strong> clone URL</h3>
  <div class="clone-url-box">
    <input type="text" class="clone js-url-field"
           value="git@github.com:jboss-developer/jboss-eap-boms.git" readonly="readonly">

    <span class="js-zeroclipboard url-box-clippy minibutton zeroclipboard-button" data-clipboard-text="git@github.com:jboss-developer/jboss-eap-boms.git" data-copied-hint="copied!" title="copy to clipboard"><span class="octicon octicon-clippy"></span></span>
  </div>
</div>

  

<div class="clone-url "
  data-protocol-type="subversion"
  data-url="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone">
  <h3><strong>Subversion</strong> checkout URL</h3>
  <div class="clone-url-box">
    <input type="text" class="clone js-url-field"
           value="https://github.com/jboss-developer/jboss-eap-boms" readonly="readonly">

    <span class="js-zeroclipboard url-box-clippy minibutton zeroclipboard-button" data-clipboard-text="https://github.com/jboss-developer/jboss-eap-boms" data-copied-hint="copied!" title="copy to clipboard"><span class="octicon octicon-clippy"></span></span>
  </div>
</div>


<p class="clone-options">You can clone with
      <a href="#" class="js-clone-selector" data-protocol="http">HTTPS</a>,
      <a href="#" class="js-clone-selector" data-protocol="ssh">SSH</a>,
      or <a href="#" class="js-clone-selector" data-protocol="subversion">Subversion</a>.
  <span class="octicon help tooltipped upwards" title="Get help on which URL is right for you.">
    <a href="https://help.github.com/articles/which-remote-url-should-i-use">
    <span class="octicon octicon-question"></span>
    </a>
  </span>
</p>



                <a href="/jboss-developer/jboss-eap-boms/archive/master.zip"
                   class="minibutton sidebar-button"
                   title="Download this repository as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
            </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>
          


<!-- blob contrib key: blob_contributors:v21:562ea3b4641d410fb6ff820d93125d9c -->
<!-- blob contrib frag key: views10/v8/blob_contributors:v21:562ea3b4641d410fb6ff820d93125d9c -->

<p title="This is a placeholder element" class="js-history-link-replace hidden"></p>

<a href="/jboss-developer/jboss-eap-boms/find/master" data-pjax data-hotkey="t" style="display:none">Show File Finder</a>

<div class="file-navigation">
  


<div class="select-menu js-menu-container js-select-menu" >
  <span class="minibutton select-menu-button js-menu-target" data-hotkey="w"
    data-master-branch="master"
    data-ref="master"
    role="button" aria-label="Switch branches or tags" tabindex="0">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
    <span class="js-select-button">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax>

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-remove-close js-menu-close"></span>
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


            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/blob/6.2.x/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="6.2.x" data-skip-pjax="true" rel="nofollow" title="6.2.x">6.2.x</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/blob/deprecated/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="deprecated" data-skip-pjax="true" rel="nofollow" title="deprecated">deprecated</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item selected">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/blob/master/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="master" data-skip-pjax="true" rel="nofollow" title="master">master</a>
            </div> <!-- /.select-menu-item -->
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div> <!-- /.select-menu-list -->

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/6.2.0-redhat-1/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="6.2.0-redhat-1" data-skip-pjax="true" rel="nofollow" title="6.2.0-redhat-1">6.2.0-redhat-1</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/6.1.0-redhat-1/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="6.1.0-redhat-1" data-skip-pjax="true" rel="nofollow" title="6.1.0-redhat-1">6.1.0-redhat-1</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.7.Final/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.7.Final" data-skip-pjax="true" rel="nofollow" title="1.0.7.Final">1.0.7.Final</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.7.CR10/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.7.CR10" data-skip-pjax="true" rel="nofollow" title="1.0.7.CR10">1.0.7.CR10</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.7.CR9/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.7.CR9" data-skip-pjax="true" rel="nofollow" title="1.0.7.CR9">1.0.7.CR9</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.7.CR8/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.7.CR8" data-skip-pjax="true" rel="nofollow" title="1.0.7.CR8">1.0.7.CR8</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.7.CR7/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.7.CR7" data-skip-pjax="true" rel="nofollow" title="1.0.7.CR7">1.0.7.CR7</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.7.CR6/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.7.CR6" data-skip-pjax="true" rel="nofollow" title="1.0.7.CR6">1.0.7.CR6</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.7.CR5/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.7.CR5" data-skip-pjax="true" rel="nofollow" title="1.0.7.CR5">1.0.7.CR5</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.7.CR4/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.7.CR4" data-skip-pjax="true" rel="nofollow" title="1.0.7.CR4">1.0.7.CR4</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.7.CR3/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.7.CR3" data-skip-pjax="true" rel="nofollow" title="1.0.7.CR3">1.0.7.CR3</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.7.CR2/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.7.CR2" data-skip-pjax="true" rel="nofollow" title="1.0.7.CR2">1.0.7.CR2</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.7.CR1/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.7.CR1" data-skip-pjax="true" rel="nofollow" title="1.0.7.CR1">1.0.7.CR1</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.6.Final/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.6.Final" data-skip-pjax="true" rel="nofollow" title="1.0.6.Final">1.0.6.Final</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.6.CR1/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.6.CR1" data-skip-pjax="true" rel="nofollow" title="1.0.6.CR1">1.0.6.CR1</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.5.Final/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.5.Final" data-skip-pjax="true" rel="nofollow" title="1.0.5.Final">1.0.5.Final</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.5.CR6/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.5.CR6" data-skip-pjax="true" rel="nofollow" title="1.0.5.CR6">1.0.5.CR6</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.5.CR5/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.5.CR5" data-skip-pjax="true" rel="nofollow" title="1.0.5.CR5">1.0.5.CR5</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.5.CR4/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.5.CR4" data-skip-pjax="true" rel="nofollow" title="1.0.5.CR4">1.0.5.CR4</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.5.CR3/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.5.CR3" data-skip-pjax="true" rel="nofollow" title="1.0.5.CR3">1.0.5.CR3</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.5.CR2/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.5.CR2" data-skip-pjax="true" rel="nofollow" title="1.0.5.CR2">1.0.5.CR2</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.5.CR1/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.5.CR1" data-skip-pjax="true" rel="nofollow" title="1.0.5.CR1">1.0.5.CR1</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.4.Final/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.4.Final" data-skip-pjax="true" rel="nofollow" title="1.0.4.Final">1.0.4.Final</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.4.CR8/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.4.CR8" data-skip-pjax="true" rel="nofollow" title="1.0.4.CR8">1.0.4.CR8</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.4.CR7/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.4.CR7" data-skip-pjax="true" rel="nofollow" title="1.0.4.CR7">1.0.4.CR7</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.4.CR6/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.4.CR6" data-skip-pjax="true" rel="nofollow" title="1.0.4.CR6">1.0.4.CR6</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.4.CR5/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.4.CR5" data-skip-pjax="true" rel="nofollow" title="1.0.4.CR5">1.0.4.CR5</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.4.CR4/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.4.CR4" data-skip-pjax="true" rel="nofollow" title="1.0.4.CR4">1.0.4.CR4</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.4.CR3/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.4.CR3" data-skip-pjax="true" rel="nofollow" title="1.0.4.CR3">1.0.4.CR3</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.4.CR2/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.4.CR2" data-skip-pjax="true" rel="nofollow" title="1.0.4.CR2">1.0.4.CR2</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.4.CR1/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.4.CR1" data-skip-pjax="true" rel="nofollow" title="1.0.4.CR1">1.0.4.CR1</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.3.Final/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.3.Final" data-skip-pjax="true" rel="nofollow" title="1.0.3.Final">1.0.3.Final</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.2.Final/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.2.Final" data-skip-pjax="true" rel="nofollow" title="1.0.2.Final">1.0.2.Final</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.1.Final/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.1.Final" data-skip-pjax="true" rel="nofollow" title="1.0.1.Final">1.0.1.Final</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.1.CR5/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.1.CR5" data-skip-pjax="true" rel="nofollow" title="1.0.1.CR5">1.0.1.CR5</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.1.CR4/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.1.CR4" data-skip-pjax="true" rel="nofollow" title="1.0.1.CR4">1.0.1.CR4</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.1.CR3/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.1.CR3" data-skip-pjax="true" rel="nofollow" title="1.0.1.CR3">1.0.1.CR3</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.1.CR2/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.1.CR2" data-skip-pjax="true" rel="nofollow" title="1.0.1.CR2">1.0.1.CR2</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.1.CR1/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.1.CR1" data-skip-pjax="true" rel="nofollow" title="1.0.1.CR1">1.0.1.CR1</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.0.M14/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.0.M14" data-skip-pjax="true" rel="nofollow" title="1.0.0.M14">1.0.0.M14</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.0.M13/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.0.M13" data-skip-pjax="true" rel="nofollow" title="1.0.0.M13">1.0.0.M13</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.0.M12-redhat-1/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.0.M12-redhat-1" data-skip-pjax="true" rel="nofollow" title="1.0.0.M12-redhat-1">1.0.0.M12-redhat-1</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.0.M12/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.0.M12" data-skip-pjax="true" rel="nofollow" title="1.0.0.M12">1.0.0.M12</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.0.M11/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.0.M11" data-skip-pjax="true" rel="nofollow" title="1.0.0.M11">1.0.0.M11</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.0.M10/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.0.M10" data-skip-pjax="true" rel="nofollow" title="1.0.0.M10">1.0.0.M10</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.0.M9/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.0.M9" data-skip-pjax="true" rel="nofollow" title="1.0.0.M9">1.0.0.M9</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.0.M8/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.0.M8" data-skip-pjax="true" rel="nofollow" title="1.0.0.M8">1.0.0.M8</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.0.M7/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.0.M7" data-skip-pjax="true" rel="nofollow" title="1.0.0.M7">1.0.0.M7</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.0.M6/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.0.M6" data-skip-pjax="true" rel="nofollow" title="1.0.0.M6">1.0.0.M6</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.0.M5/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.0.M5" data-skip-pjax="true" rel="nofollow" title="1.0.0.M5">1.0.0.M5</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.0.M4/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.0.M4" data-skip-pjax="true" rel="nofollow" title="1.0.0.M4">1.0.0.M4</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.0.M3/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.0.M3" data-skip-pjax="true" rel="nofollow" title="1.0.0.M3">1.0.0.M3</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.0.M2/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.0.M2" data-skip-pjax="true" rel="nofollow" title="1.0.0.M2">1.0.0.M2</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.0.M1/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.0.M1" data-skip-pjax="true" rel="nofollow" title="1.0.0.M1">1.0.0.M1</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.0.Final/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.0.Final" data-skip-pjax="true" rel="nofollow" title="1.0.0.Final">1.0.0.Final</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jboss-developer/jboss-eap-boms/tree/1.0.0.CR1/jboss-javaee-6.0-with-tools/README.md" class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target" data-name="1.0.0.CR1" data-skip-pjax="true" rel="nofollow" title="1.0.0.CR1">1.0.0.CR1</a>
            </div> <!-- /.select-menu-item -->
        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div> <!-- /.select-menu-list -->

    </div> <!-- /.select-menu-modal -->
  </div> <!-- /.select-menu-modal-holder -->
</div> <!-- /.select-menu -->

  <div class="breadcrumb">
    <span class='repo-root js-repo-root'><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/jboss-developer/jboss-eap-boms" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">jboss-eap-boms</span></a></span></span><span class="separator"> / </span><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/jboss-developer/jboss-eap-boms/tree/master/jboss-javaee-6.0-with-tools" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">jboss-javaee-6.0-with-tools</span></a></span><span class="separator"> / </span><strong class="final-path">README.md</strong> <span class="js-zeroclipboard minibutton zeroclipboard-button" data-clipboard-text="jboss-javaee-6.0-with-tools/README.md" data-copied-hint="copied!" title="copy to clipboard"><span class="octicon octicon-clippy"></span></span>
  </div>
</div>


  <div class="commit commit-loader file-history-tease js-deferred-content" data-url="/jboss-developer/jboss-eap-boms/contributors/master/jboss-javaee-6.0-with-tools/README.md">
    Fetching contributors…

    <div class="participation">
      <p class="loader-loading"><img alt="Octocat-spinner-32-eaf2f5" height="16" src="https://github.global.ssl.fastly.net/images/spinners/octocat-spinner-32-EAF2F5.gif" width="16" /></p>
      <p class="loader-error">Cannot retrieve contributors at this time</p>
    </div>
  </div>

<div id="files" class="bubble">
  <div class="file">
    <div class="meta">
      <div class="info">
        <span class="icon"><b class="octicon octicon-file-text"></b></span>
        <span class="mode" title="File Mode">file</span>
          <span>178 lines (137 sloc)</span>
        <span>8.185 kb</span>
      </div>
      <div class="actions">
        <div class="button-group">
                <a class="minibutton tooltipped leftwards"
                   title="Clicking this button will automatically fork this project so you can edit the file"
                   href="/jboss-developer/jboss-eap-boms/edit/master/jboss-javaee-6.0-with-tools/README.md"
                   data-method="post" rel="nofollow">Edit</a>
          <a href="/jboss-developer/jboss-eap-boms/raw/master/jboss-javaee-6.0-with-tools/README.md" class="button minibutton " id="raw-url">Raw</a>
            <a href="/jboss-developer/jboss-eap-boms/blame/master/jboss-javaee-6.0-with-tools/README.md" class="button minibutton ">Blame</a>
          <a href="/jboss-developer/jboss-eap-boms/commits/master/jboss-javaee-6.0-with-tools/README.md" class="button minibutton " rel="nofollow">History</a>
        </div><!-- /.button-group -->
            <a class="minibutton danger empty-icon tooltipped downwards"
               href="/jboss-developer/jboss-eap-boms/delete/master/jboss-javaee-6.0-with-tools/README.md"
               title="Fork this project and delete file"
               data-method="post" data-test-id="delete-blob-file" rel="nofollow">
            Delete
          </a>
      </div><!-- /.actions -->

    </div>
      
  <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1>
<a name="jboss-java-ee-6-with-tools-recommended-by-jboss" class="anchor" href="#jboss-java-ee-6-with-tools-recommended-by-jboss"><span class="octicon octicon-link"></span></a>JBoss Java EE 6 with tools recommended by JBoss</h1>

<p>Java EE lacks any testing APIs, and for this reason JBoss developed the Arquillian project, along with it's various component projects, such as Arquillian Drone, and the sister project Shrinkwrap. This BOM builds on the Java EE full profile BOM, adding Arquillian to the mix. It also provides a version of JUnit and TestNG recommended for use with Arquillian.</p>

<p>Furthermore, this BOM adds the JBoss AS Maven deployment plugin. EAP 6's recommended mode of deployment is via the management APIs, and the Maven plugin is the recommended way to do this, if the customer is using Maven for building.</p>

<h2>
<a name="usage" class="anchor" href="#usage"><span class="octicon octicon-link"></span></a>Usage</h2>

<p>To use the BOM, import into your dependency management:</p>

<pre><code>&lt;dependencyManagement&gt;
    &lt;dependencies&gt;
        &lt;dependency&gt;
           &lt;groupId&gt;org.jboss.bom.eap&lt;/groupId&gt;
           &lt;artifactId&gt;jboss-javaee-6.0-with-tools&lt;/artifactId&gt;
           &lt;version&gt;6.2.0-redhat-SNAPSHOT&lt;/version&gt;
           &lt;type&gt;pom&lt;/type&gt;
           &lt;scope&gt;import&lt;/scope&gt;
        &lt;/dependency&gt;
    &lt;/dependencies&gt;
&lt;/dependencyManagement&gt;
</code></pre>

<p>Unfortunately, Maven doesn't allow you to specify plugin versions this way. To use the plugins associated with "Java EE with Tools recommended by JBoss" BOM, add:</p>

<pre><code>&lt;pluginManagement&gt;
    &lt;plugins&gt;
        &lt;!-- The Maven Surefire plugin tests your application. Here we ensure we are using a version compatible with Arquillian --&gt;
        &lt;plugin&gt;
            &lt;artifactId&gt;maven-surefire-plugin&lt;/artifactId&gt;
            &lt;version&gt;2.10&lt;/version&gt;
        &lt;/plugin&gt;
        &lt;!-- The JBoss AS plugin deploys your war to a local JBoss AS container --&gt;
        &lt;!-- To use, set the JBOSS_HOME environment variable and run:
             mvn package jboss-as:deploy --&gt;
        &lt;plugin&gt;
            &lt;groupId&gt;org.jboss.as.plugins&lt;/groupId&gt;
            &lt;artifactId&gt;jboss-as-maven-plugin&lt;/artifactId&gt;
            &lt;version&gt;7.3.Final&lt;/version&gt;
        &lt;/plugin&gt;
    &lt;/plugins&gt;
&lt;/pluginManagement&gt;
</code></pre>

<p>You'll need to take a look at the POM source in order to find the latest versions of plugins recommended.</p>

<h3>
<a name="deployingundeploying-your-application-to-server" class="anchor" href="#deployingundeploying-your-application-to-server"><span class="octicon octicon-link"></span></a>Deploying/undeploying your application to server</h3>

<p>To be able to easily deploy (or undeploy) your application from the application server, include following in the <code>&lt;build&gt;</code> section of your pom.xml file:</p>

<pre><code>&lt;plugins&gt;    
    &lt;plugin&gt;
        &lt;groupId&gt;org.jboss.as.plugins&lt;/groupId&gt;
        &lt;artifactId&gt;jboss-as-maven-plugin&lt;/artifactId&gt;
    &lt;/plugin&gt;
&lt;/plugins&gt;
</code></pre>

<p>You'll be able to deploy your application via <code>mvn package jboss-as:deploy</code>. See <a href="https://github.com/jbossas/jboss-as-maven-plugin">https://github.com/jbossas/jboss-as-maven-plugin</a> for further information how to use the plugin.</p>

<h3>
<a name="testing-your-application-with-arquillian" class="anchor" href="#testing-your-application-with-arquillian"><span class="octicon octicon-link"></span></a>Testing your application with Arquillian</h3>

<p>To able to test your application with Arquillian, you have decide which type container you prefer. Arquillian allows you to choose 
between a managed invocation, where it controls startup and shutdown of the container and a remote invocation, which connects to a running instance of JBoss AS.
See <a href="https://docs.jboss.org/author/display/ARQ/Container+varieties">https://docs.jboss.org/author/display/ARQ/Container+varieties</a> for further details. You may wish to set up two distint profiles, each using one type of
the container.</p>

<p>To select JBoss AS 7 managed container, following dependency has to be added into the <code>&lt;dependencies&gt;</code> section of your pom.xml file:</p>

<pre><code>&lt;dependency&gt;
    &lt;groupId&gt;org.jboss.as&lt;/groupId&gt;
    &lt;artifactId&gt;jboss-as-arquillian-container-managed&lt;/artifactId&gt;
    &lt;scope&gt;test&lt;/scope&gt;
&lt;/dependency&gt;
</code></pre>

<p>Or for JBoss AS 7 remote container:</p>

<pre><code>&lt;dependency&gt;
    &lt;groupId&gt;org.jboss.as&lt;/groupId&gt;
    &lt;artifactId&gt;jboss-as-arquillian-container-remote&lt;/artifactId&gt;
    &lt;scope&gt;test&lt;/scope&gt;
&lt;/dependency&gt;
</code></pre>

<p>Apart from setting a container, you need to choose a testing framework (e.g. JUnit) and add the Arquillan bindings for it:</p>

<pre><code>&lt;dependency&gt;
    &lt;groupId&gt;junit&lt;/groupId&gt;
    &lt;artifactId&gt;junit&lt;/artifactId&gt;
    &lt;scope&gt;test&lt;/scope&gt;
&lt;/dependency&gt;

&lt;dependency&gt;
    &lt;groupId&gt;org.jboss.arquillian.junit&lt;/groupId&gt;
    &lt;artifactId&gt;arquillian-junit-container&lt;/artifactId&gt;
    &lt;scope&gt;test&lt;/scope&gt;
&lt;/dependency&gt;
</code></pre>

<p><em>Note: Don't forget to set JBOSS_HOME environment variable so Arquillian will be able to find your container location.
If you want to experiment with Arquillian settings, you can find plenty of information at <a href="http://arquillian.org/">http://arquillian.org/</a></em></p>

<p>Arquillian allows you to setup two distinct protocols for communication between Arquillian and application server, a Servlet
based and a JMX based one. In order to have a protocol activated, you need to add its artifact into <code>&lt;dependencies&gt;</code> section and configure
it in <code>arquillian.xml</code> file. We recommend you to use the Servlet 3.0 protocol. To set up it, add following dependency:</p>

<pre><code>&lt;dependency&gt;
    &lt;groupId&gt;org.jboss.arquillian.protocol&lt;/groupId&gt;
    &lt;artifactId&gt;arquillian-protocol-servlet&lt;/artifactId&gt;
    &lt;scope&gt;test&lt;/scope&gt;
&lt;/dependency&gt;
</code></pre>

<p>Arquillian configuration file (<code>arquillian.xml</code>) is located by default in <code>src/test/resources</code> directory. You need to setup
Servlet protocol as default:</p>

<pre><code>&lt;?xml version="1.0" encoding="UTF-8"?&gt;
&lt;arquillian xmlns="http://jboss.org/schema/arquillian"
    xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xsi:schemaLocation="http://jboss.org/schema/arquillian
    http://jboss.org/schema/arquillian/arquillian_1_0.xsd"&gt;

    &lt;!-- Uncomment to have test archives exported to the file system for inspection --&gt;
    &lt;!--    &lt;engine&gt;  --&gt;
    &lt;!--       &lt;property name="deploymentExportPath"&gt;target/&lt;/property&gt;  --&gt;
    &lt;!--    &lt;/engine&gt; --&gt;

    &lt;!-- Force the use of the Servlet 3.0 protocol with all containers, as it is the most mature --&gt;
    &lt;defaultProtocol type="Servlet 3.0" /&gt;

    &lt;!-- Example configuration for a managed/remote JBoss AS 7 instance --&gt;
    &lt;container qualifier="jboss" default="true"&gt;
    &lt;!-- If you want to use the JBOSS_HOME environment variable, just delete the jbossHome property --&gt;
    &lt;!--&lt;configuration&gt;--&gt;
    &lt;!--&lt;property name="jbossHome"&gt;/path/to/jboss/as&lt;/property&gt;--&gt;
    &lt;!--&lt;/configuration&gt;--&gt;
    &lt;/container&gt;
&lt;/arquillian&gt;
</code></pre>

<h3>
<a name="testing-your-application-with-arquillian-drone" class="anchor" href="#testing-your-application-with-arquillian-drone"><span class="octicon octicon-link"></span></a>Testing your application with Arquillian Drone</h3>

<p>Arquillian Drone uses the very same setup as plain Arquillian. Arquillian Drone lets you choice between different Selenium bindings.
Currently, we support three different Selenium based frameworks:</p>

<ul>
<li>Selenium DefaultSelenium - as known as Selenium 1.0</li>
<li>Selenium WebDriver - as known as Selenium 2.0</li>
<li>Arquillian Graphene - AJAX-enhanced Selenium 1.0 with a type safe API</li>
</ul><p>In order to use Arquillian Drone, include following dependency into your <code>&lt;dependencies&gt;</code> section. You can use one of the
frameworks or include all of them together. More information about binding can be found at <a href="https://docs.jboss.org/author/display/ARQ/Drone">https://docs.jboss.org/author/display/ARQ/Drone</a>:</p>

<pre><code>&lt;!-- Arquillian Drone with DefaultSelenium --&gt;
&lt;dependency&gt;
    &lt;groupId&gt;org.jboss.arquillian.extension&lt;/groupId&gt;
    &lt;artifactId&gt;arquillian-drone-selenium-depchain&lt;/artifactId&gt;
    &lt;type&gt;pom&lt;/type&gt;
    &lt;scope&gt;test&lt;/scope&gt;
&lt;/dependency&gt;

&lt;!-- Arquillian Drone with WebDriver --&gt;
&lt;dependency&gt;
    &lt;groupId&gt;org.jboss.arquillian.extension&lt;/groupId&gt;
    &lt;artifactId&gt;arquillian-drone-webdriver-depchain&lt;/artifactId&gt;
    &lt;type&gt;pom&lt;/type&gt;
    &lt;scope&gt;test&lt;/scope&gt;
&lt;/dependency&gt;

&lt;!-- Arquillian Drone with Arquillian Graphene --&gt;
&lt;dependency&gt;
    &lt;groupId&gt;org.jboss.arquillian.graphene&lt;/groupId&gt;
    &lt;artifactId&gt;arquillian-graphene&lt;/artifactId&gt;
    &lt;type&gt;pom&lt;/type&gt;
    &lt;scope&gt;test&lt;/scope&gt;
&lt;/dependency&gt;
</code></pre>

<p><em>Note: Each of listed Arquillian Dependency Chains already contains a certified version of Selenium. Should you need to use a different version (for example to test your 
application in a newer browser, compatible with the latest Selenium version only), you can get more information how to do that
at <a href="https://community.jboss.org/wiki/SpecifyingSeleniumVersionInArquillianDrone">https://community.jboss.org/wiki/SpecifyingSeleniumVersionInArquillianDrone</a></em>  </p></article>
  </div>

  </div>
</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" class="js-jump-to-line" style="display:none">Jump to Line</a>
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
  <div class="site-footer">
    <ul class="site-footer-links right">
      <li><a href="https://status.github.com/">Status</a></li>
      <li><a href="http://developer.github.com">API</a></li>
      <li><a href="http://training.github.com">Training</a></li>
      <li><a href="http://shop.github.com">Shop</a></li>
      <li><a href="/blog">Blog</a></li>
      <li><a href="/about">About</a></li>

    </ul>

    <a href="/">
      <span class="mega-octicon octicon-mark-github"></span>
    </a>

    <ul class="site-footer-links">
      <li>&copy; 2013 <span title="0.12931s from github-fe125-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="/site/terms">Terms</a></li>
        <li><a href="/site/privacy">Privacy</a></li>
        <li><a href="/security">Security</a></li>
        <li><a href="/contact">Contact</a></li>
    </ul>
  </div><!-- /.site-footer -->
</div><!-- /.container -->


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-fullscreen-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="js-fullscreen-contents" placeholder="" data-suggester="fullscreen_suggester"></textarea>
          <div class="suggester-container">
              <div class="suggester fullscreen-suggester js-navigation-container" id="fullscreen_suggester"
                 data-url="/jboss-developer/jboss-eap-boms/suggestions/commit">
              </div>
          </div>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped leftwards" title="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped leftwards"
      title="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-remove-close close ajax-error-dismiss"></a>
      Something went wrong with that request. Please try again.
    </div>

    
  </body>
</html>

