<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Square Open Source</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0">

    <link href="/assets/base.css" media="screen" rel="stylesheet" type="text/css" />
    <link rel="shortcut icon" href="/assets/public/favicon.ico" />

    <script src="/assets/modernizr.js" type="text/javascript"></script>
  </head>
  <body>
    <div class="wrapper">
      <div class="profile">
        <section class="profile-masthead" id="masthead">
          <header class="profile-logo">
            <div class="profile-logo-image">
              <img alt="Square Open Source " src="/images/logo.png" />
            </div>
            <div class="profile-name">
              <h1>Square Open Source</h1>
            </div>
          </header>
          <aside class="profile-summary">
            <div class="summary-location summary-module">
              <a href="http://github.com/square">github.com/square</a>
            </div>
          </aside>
        </section>

        <section class="profile-content" id="content">
          <!-- TODO header? -->

          <div class="profile-description">
            <p>As a company built on open source, here are some of the internally-developed libraries we have contributed back to the community.</p>
          </div>

          <article class="profile-menu" id="menu">
            <nav class="menu-navigation">
              <ul class="menu-navigation-list">
                <li class="menu-navigation-list-item"><a href="#android">Android</a></li>
                <li class="menu-navigation-list-item"><a href="#c">C</a></li>
                <li class="menu-navigation-list-item"><a href="#go">Go</a></li>
                <li class="menu-navigation-list-item"><a href="#ios">iOS</a></li>
                <li class="menu-navigation-list-item"><a href="#java">Java</a></li>
                <li class="menu-navigation-list-item"><a href="#javascript">JavaScript</a></li>
                <li class="menu-navigation-list-item"><a href="#kotlin">Kotlin</a></li>
                <li class="menu-navigation-list-item"><a href="#ruby">Ruby</a></li>
                <li class="menu-navigation-list-item"><a href="#other">Other</a></li>
              </ul>
            </nav>

            <div id="android" class="menu-category">
              <h3 class="menu-category-name">Android</h3>
              <ol class="menu-category-list has-images">
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">android-times-square</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/android-times-square" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Standalone Android widget for picking a single date from a calendar view.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/android-times-square.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">assertj-android</h4>
                  <span class="menu-item-price"><a href="http://square.github.io/assertj-android/" target="_blank">Website</a> &middot; <a href="https://github.com/square/assertj-android" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">A set of AssertJ helpers geared toward testing Android.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/assertj-android.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">leakcanary</h4>
                  <span class="menu-item-price"><a href="https://square.github.io/leakcanary" target="_blank">Website</a> &middot; <a href="https://github.com/square/leakcanary" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">LeakCanary is a memory leak detection library for Android.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/leakcanary.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">moshi</h4>
                  <span class="menu-item-price"><a href="http://square.github.io/moshi/1.x/moshi/" target="_blank">Website</a> &middot; <a href="https://github.com/square/moshi" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">A modern JSON library for Kotlin and Java.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/moshi.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">okhttp</h4>
                  <span class="menu-item-price"><a href="http://square.github.io/okhttp/" target="_blank">Website</a> &middot; <a href="https://github.com/square/okhttp" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">An HTTP client for Android, Kotlin, and Java.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/okhttp.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">okio</h4>
                  <span class="menu-item-price"><a href="https://square.github.io/okio/" target="_blank">Website</a> &middot; <a href="https://github.com/square/okio" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">A modern I/O library for Android, Kotlin, and Java.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/okio.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">picasso</h4>
                  <span class="menu-item-price"><a href="http://square.github.io/picasso/" target="_blank">Website</a> &middot; <a href="https://github.com/square/picasso" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">A powerful image downloading and caching library for Android</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/picasso.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">pollexor</h4>
                  <span class="menu-item-price"><a href="http://square.github.io/pollexor/" target="_blank">Website</a> &middot; <a href="https://github.com/square/pollexor" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Java client for the Thumbor image service which allows you to build URIs in an expressive fashion using a fluent API.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/pollexor.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">retrofit</h4>
                  <span class="menu-item-price"><a href="http://square.github.io/retrofit/" target="_blank">Website</a> &middot; <a href="https://github.com/square/retrofit" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Type-safe HTTP client for Android and Java by Square, Inc.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/retrofit.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">spoon</h4>
                  <span class="menu-item-price"><a href="http://square.github.io/spoon/" target="_blank">Website</a> &middot; <a href="https://github.com/square/spoon" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Distributing instrumentation tests to all your Androids.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/spoon.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">wire</h4>
                  <span class="menu-item-price"><a href="https://square.github.io/wire/" target="_blank">Website</a> &middot; <a href="https://github.com/square/wire" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Clean, lightweight protocol buffers for Android and Java.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/wire.jpg" />
                </div>
              </li>
              </ol>
              <ol class="menu-category-list">
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">seismic</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/seismic" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Android device shake detection.</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">sqldelight</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/sqldelight" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Generates typesafe Kotlin APIs from SQL</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">tape</h4>
                  <span class="menu-item-price"><a href="http://square.github.io/tape/" target="_blank">Website</a> &middot; <a href="https://github.com/square/tape" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">A lightning fast, transactional, file-based FIFO for Android and Java.</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">workflow</h4>
                  <span class="menu-item-price"><a href="https://square.github.io/workflow" target="_blank">Website</a> &middot; <a href="https://github.com/square/workflow" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">A library for making composable state machines, and UIs driven by those state machines.</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">anvil</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/anvil" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">A Kotlin compiler plugin to make dependency injection with Dagger 2 easier.</p>
                </div>
              </li>
              </ol>
            </div>
            <div id="c" class="menu-category">
              <h3 class="menu-category-name">C</h3>
              <ol class="menu-category-list has-images">
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">subzero</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/subzero" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Square&#x27;s Bitcoin Cold Storage solution.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/subzero.jpg" />
                </div>
              </li>
              </ol>
            </div>
            <div id="go" class="menu-category">
              <h3 class="menu-category-name">Go</h3>
              <ol class="menu-category-list has-images">
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">beancounter</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/beancounter" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Utility to audit the balance of Hierarchical Deterministic (HD) wallets. Supports multisig + segwit wallets.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/beancounter.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">subzero</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/subzero" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Square&#x27;s Bitcoin Cold Storage solution.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/subzero.jpg" />
                </div>
              </li>
              </ol>
              <ol class="menu-category-list">
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">certigo</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/certigo" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">A utility to examine and validate certificates in a variety of formats</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">certstrap</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/certstrap" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Tools to bootstrap CAs, certificate requests, and signed certificates.</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">ghostunnel</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/ghostunnel" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">A simple SSL/TLS proxy with mutual authentication for securing non-TLS services</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">go-jose</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/go-jose" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">An implementation of JOSE standards (JWE, JWS, JWT) in Go</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">gssh</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/gssh" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">simple command line to utility to run commands on multiple hosts in parallel</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">metrics</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/metrics" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Metrics Query Engine</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">squalor</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/squalor" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Go SQL utility library</p>
                </div>
              </li>
              </ol>
            </div>
            <div id="ios" class="menu-category">
              <h3 class="menu-category-name">iOS</h3>
              <ol class="menu-category-list has-images">
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">PonyDebugger</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/PonyDebugger" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Remote network and data debugging for your native iOS app using Chrome Developer Tools</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/PonyDebugger.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">spacecommander</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/spacecommander" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Commit fully-formatted Objective-C as a team without even trying.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/spacecommander.jpg" />
                </div>
              </li>
              </ol>
              <ol class="menu-category-list">
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">Aardvark</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/Aardvark" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Aardvark is a library that makes it dead simple to create actionable bug reports.</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">Ackbar</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/Ackbar" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Testable debug assertions for Swift.</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">Cleanse</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/Cleanse" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Lightweight Swift Dependency Injection Framework</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">sqldelight</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/sqldelight" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Generates typesafe Kotlin APIs from SQL</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">SuperDelegate</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/SuperDelegate" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">SuperDelegate provides a clean application delegate interface and protects you from bugs in the application lifecycle</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">Valet</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/Valet" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Valet lets you securely store data in the iOS, tvOS, or macOS Keychain without knowing a thing about how the Keychain works. It’s easy. We promise.</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">workflow</h4>
                  <span class="menu-item-price"><a href="https://square.github.io/workflow" target="_blank">Website</a> &middot; <a href="https://github.com/square/workflow" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">A library for making composable state machines, and UIs driven by those state machines.</p>
                </div>
              </li>
              </ol>
            </div>
            <div id="java" class="menu-category">
              <h3 class="menu-category-name">Java</h3>
              <ol class="menu-category-list has-images">
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">moshi</h4>
                  <span class="menu-item-price"><a href="http://square.github.io/moshi/1.x/moshi/" target="_blank">Website</a> &middot; <a href="https://github.com/square/moshi" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">A modern JSON library for Kotlin and Java.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/moshi.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">okhttp</h4>
                  <span class="menu-item-price"><a href="http://square.github.io/okhttp/" target="_blank">Website</a> &middot; <a href="https://github.com/square/okhttp" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">An HTTP client for Android, Kotlin, and Java.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/okhttp.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">okio</h4>
                  <span class="menu-item-price"><a href="https://square.github.io/okio/" target="_blank">Website</a> &middot; <a href="https://github.com/square/okio" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">A modern I/O library for Android, Kotlin, and Java.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/okio.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">pollexor</h4>
                  <span class="menu-item-price"><a href="http://square.github.io/pollexor/" target="_blank">Website</a> &middot; <a href="https://github.com/square/pollexor" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Java client for the Thumbor image service which allows you to build URIs in an expressive fashion using a fluent API.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/pollexor.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">retrofit</h4>
                  <span class="menu-item-price"><a href="http://square.github.io/retrofit/" target="_blank">Website</a> &middot; <a href="https://github.com/square/retrofit" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Type-safe HTTP client for Android and Java by Square, Inc.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/retrofit.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">subzero</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/subzero" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Square&#x27;s Bitcoin Cold Storage solution.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/subzero.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">wire</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/wire" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Clean, lightweight protocol buffers for Android and Java.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/wire.jpg" />
                </div>
              </li>
              </ol>
              <ol class="menu-category-list">
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">javapoet</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/javapoet" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">A Java API for generating .java source files.</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">keywhiz</h4>
                  <span class="menu-item-price"><a href="https://square.github.io/keywhiz/" target="_blank">Website</a> &middot; <a href="https://github.com/square/keywhiz" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">A system for distributing and managing secrets</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">rack-servlet</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/rack-servlet" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Embed JRuby Rack applications in your Java container.</p>
                </div>
              </li>
              </ol>
            </div>
            <div id="javascript" class="menu-category">
              <h3 class="menu-category-name">JavaScript</h3>
              <ol class="menu-category-list has-images">
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">crossfilter</h4>
                  <span class="menu-item-price"><a href="http://square.github.com/crossfilter/" target="_blank">Website</a> &middot; <a href="https://github.com/square/crossfilter" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Fast n-dimensional filtering and grouping of records.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/crossfilter.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">cube</h4>
                  <span class="menu-item-price"><a href="http://square.github.com/cube" target="_blank">Website</a> &middot; <a href="https://github.com/square/cube" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Cube: A system for time series visualization.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/cube.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">cubism</h4>
                  <span class="menu-item-price"><a href="http://square.github.com/cubism/" target="_blank">Website</a> &middot; <a href="https://github.com/square/cubism" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Cubism.js: A JavaScript library for time series visualization.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/cubism.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">es6-module-transpiler</h4>
                  <span class="menu-item-price"><a href="http://esnext.github.io/es6-module-transpiler/" target="_blank">Website</a> &middot; <a href="https://github.com/esnext/es6-module-transpiler" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Tomorrow’s JavaScript module syntax today</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/es6-module-transpiler.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">field-kit</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/field-kit" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">FieldKit lets you take control of your text fields.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/field-kit.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">lgtm</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/lgtm" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Simple object validation for JavaScript.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/lgtm.jpg" />
                </div>
              </li>
              </ol>
              <ol class="menu-category-list">
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">js-jose</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/js-jose" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">JavaScript library to encrypt/decrypt data in JSON Web Encryption (JWE) format and to sign/verify data in JSON Web Signature (JWS) format. Leverages Browser&#x27;s native WebCrypto API.</p>
                </div>
              </li>
              </ol>
            </div>
            <div id="kotlin" class="menu-category">
              <h3 class="menu-category-name">Kotlin</h3>
              <ol class="menu-category-list has-images">
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">kotlinpoet</h4>
                  <span class="menu-item-price"><a href="https://square.github.io/kotlinpoet/" target="_blank">Website</a> &middot; <a href="https://github.com/square/kotlinpoet" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">A Kotlin API for generating .kt source files.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/kotlinpoet.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">leakcanary</h4>
                  <span class="menu-item-price"><a href="https://square.github.io/leakcanary" target="_blank">Website</a> &middot; <a href="https://github.com/square/leakcanary" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">LeakCanary is a memory leak detection library for Android.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/leakcanary.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">okhttp</h4>
                  <span class="menu-item-price"><a href="http://square.github.io/okhttp/" target="_blank">Website</a> &middot; <a href="https://github.com/square/okhttp" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">An HTTP client for Android, Kotlin, and Java.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/okhttp.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">okio</h4>
                  <span class="menu-item-price"><a href="https://square.github.io/okio/" target="_blank">Website</a> &middot; <a href="https://github.com/square/okio" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">A modern I/O library for Android, Kotlin, and Java.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/okio.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">retrofit</h4>
                  <span class="menu-item-price"><a href="http://square.github.io/retrofit/" target="_blank">Website</a> &middot; <a href="https://github.com/square/retrofit" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Type-safe HTTP client for Android and Java by Square, Inc.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/retrofit.jpg" />
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">wire</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/wire" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Clean, lightweight protocol buffers for Android and Java.</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/wire.jpg" />
                </div>
              </li>
              </ol>
              <ol class="menu-category-list">
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">sqldelight</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/sqldelight" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Generates typesafe Kotlin APIs from SQL</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">workflow</h4>
                  <span class="menu-item-price"><a href="https://square.github.io/workflow" target="_blank">Website</a> &middot; <a href="https://github.com/square/workflow" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">A library for making composable state machines, and UIs driven by those state machines.</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">anvil</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/anvil" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">A Kotlin compiler plugin to make dependency injection with Dagger 2 easier.</p>
                </div>
              </li>
              </ol>
            </div>
            <div id="ruby" class="menu-category">
              <h3 class="menu-category-name">Ruby</h3>
              <ol class="menu-category-list">
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">border_patrol</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/border_patrol" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">BorderPatrol lets you import a KML file and then check if points are inside or outside the polygons the file defines.</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">cane</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/cane" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Code quality threshold checking as part of your build</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">ETL</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/ETL" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Extract, Transform, and Load data with Ruby</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">fdoc</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/fdoc" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Documentation format and verification</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">jetpack</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/jetpack" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">jet.pack: package your JRuby rack app for Jetty.</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">rails-auth</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/rails-auth" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Modular resource-based authentication and authorization for Rails/Rack</p>
                </div>
              </li>
              </ol>
            </div>
            <div id="other" class="menu-category">
              <h3 class="menu-category-name">Other</h3>
              <ol class="menu-category-list has-images">
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">shuttle</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/shuttle" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">String extraction, translation and export tools for the 21st century. &quot;Moving strings around so you don&#x27;t have to&quot;</p>
                </div>
                <div class="menu-item-image has-meta-content">
                  <img src="/repo_images/shuttle.jpg" />
                </div>
              </li>
              </ol>
              <ol class="menu-category-list">
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">jirafy</h4>
                  <span class="menu-item-price"><a href="https://chrome.google.com/webstore/detail/npldkpkhkmpnfhpmeoahhakbgcldplbj" target="_blank">Website</a> &middot; <a href="https://github.com/square/jirafy" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Chrome extension that linkifies JIRA ticket numbers on select pages.</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">p2</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/p2" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Platypus Platform: Tools for Scalable Deployment</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">shift</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/shift" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">shift is an application that helps you run schema migrations on MySQL databases</p>
                </div>
              </li>
              <li class="menu-item">
                <div class="menu-item-info">
                  <h4 class="menu-item-name">toggle</h4>
                  <span class="menu-item-price"><a href="https://github.com/square/toggle" target="_blank">GitHub</a></span>
                  <p class="menu-item-description">Simple, flexible and lightweight configuration switching.</p>
                </div>
              </li>
              </ol>
            </div>

            <a id="btn-view-full-menu" class="btn-view-full-menu" href="http://github.com/square">View full list of repositories</a>
          </article>

          <section class="profile-modules" id="modules">
            <ul class='twitter-columns'>
              <li class="profile-module module-twitter">
                <h2 class="module-name">Tweets</h2>
                <a class="twitter-timeline" href="https://twitter.com/SquareEng" data-widget-id="281462446621851648" data-screen-name="SquareEng" data-chrome="none" data-link-color="#50a9ca" data-heading-style="color:#2d3c48;font-size:22px;font-weight:300;line-height:17px;font-family:'SQMarket', 'Helvetica Neue',sans-serif;" height="635" width="100%"></a>
                <script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src="//platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>
              </li>
              <li class="profile-module">
                <h2 class="module-name">Join us</h2>
                <ul class="module-list">
                  <li><a href="https://developer.squareup.com/blog/">Engineering Blog</a> &ndash; developer.squareup.com/blog</li>
                  <li><a href="https://squareup.com/careers">Careers Page</a> &ndash; squareup.com/careers</li>
                  <li class="module-social">
                    <a href="https://twitter.com/SquareEng" target="_blank"><i class="icon-twitter"></i></a>
                  </li>
                </ul>
              </li>
            </ul>
          </section>
        </section>
      </div>
    </div>

    <footer class="footer">
      <nav class="footer-navigation">
        <i class="icon-square-footer"></i>
        <ul class="footer-navigation-list">
          <li class="footer-navigation-item"><a href="https://squareup.com/developers">Square Developer</a></li>
          <li class="footer-navigation-item"><a href="https://github.com/cashapp">Cash App</a></li>
          <li class="footer-navigation-item"><a href="https://squareup.com/security">Security</a></li>
          <li class="footer-navigation-item"><a href="https://squareup.com/legal/privacy">Privacy</a></li>
          <li class="footer-navigation-item"><a href="https://squareup.com/help" class="track">Help Center</a></li>
        </ul>
        <p class="copyright">© 2009–2020 Square, Inc. All rights reserved.</p>
      </nav>
    </footer>

    <script type="text/javascript">
      if(window == window.top) document.body.style.display = "block"; else window.top.location = window.location;

      var _gaq = _gaq || [];
      _gaq.push(['_setAccount', 'UA-40704740-1']);
      _gaq.push(['_trackPageview']);

      (function() {
        var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
        ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
        var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
      })();

    </script>
  </body>
</html>
