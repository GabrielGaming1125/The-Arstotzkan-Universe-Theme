# The-Arstotzkan-Universe-Theme
The Custom Wikidot Theme for The Arstotzkan Unierse WIki since 2021

@charset "utf-8";
 
@import url('https://fonts.googleapis.com/css?family=Exo+2');
@import url('https://fonts.googleapis.com/css?family=Michroma');
@import url('http://fonts.googleapis.com/earlyaccess/nanumgothic.css');
@import url('http://fonts.googleapis.com/earlyaccess/nanumgothiccoding.css');
@import url('http://maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css');
 
:root {
/* PALLET SHEET */
 
--basic-border: 1px solid #000;
--basic-border-color: #000;
--dashed-border: 1px dashed #000;
--thick-border: 2px solid #000;
 
--element-border-radius: 2px;
 
--primary-background: #1d2022;
--secondary-background: rgba(0,0,0,0.15);
--background-3: #191b1d;
--background-4: #1f2125;
 
--content-bar-background: #24272a;
 
--primary-text-color: #3e6aa3;
 
--nav-hover-background: #2d4975;
 
/* BASE COLORS */
 
/* General Elements */
--text-color: #000;
--unmargined-color: var(--primary-text-color);
--horizontal-rule-background: var(--basic-border-color);
--horizontal-rule-secondary-background: #000; /* color of horizontal rules when they are inside of content panels and stuff */
--action-area-border: var(--dashed-border);
--alert-info-border: var(--dashed-border);
--owindow-border: var(--basic-border);
--tags-border: var(--basic-border);
--error-color: #f54242; 
--content-box-shadow-color: #191919;
--content-box-shadow: 1px 1px 1px 1px var(--content-box-shadow-color);
--show-changes-del-background: rgba(255,123,123,0.47);
--show-changes-ins-background: rgba(140,255,129,0.47);
 
/* Body */
--body-background: #fff;
 
/* Footer */
--footer-background: var(--primary-background);
--footer-color: var(--text-color);
 
/* Page Content */
--page-background: none;
--page-padding: none;
--page-border: none;
--page-border-radius: 0;
 
/* Page Title */
--page-title-color: #000;
--page-title-border: #000;
 
/* Generic Buttons */
--button-border: 1px solid #2c3340;
--button-background: #181d22;
--button-hover-border: 1px solid #27415c;
--button-hover-background: #27415c;
--button-hover-color: #fff;
--button-current-background: var(--primary-background);
 
/* Header Icon */
--header-icon: url(http://arstotzkanuniverse.wdfiles.com/local--files/this-universe/Arstotzkan-Universe_logo.png);
--header-icon-adv: left 1.2em top 1rem no-repeat;
--header-icon-size: auto calc(9.5rem - 2.125rem);
 
/* Header Background */
--header-background: url(http://arstotzkanuniverse.wdfiles.com/local--files/this-universe/New-theme2728.png);
 
/* Set to hidden to enable custom text */
--header-text-visibility: visible;
 
/* Primary Header Text */
--header-font-weight: bold;
--header-font: default;
--header-color: #fff;
--header-font-size: 180%;
--header-mobile-font-size: 85%;
 
/* Header Tagline Text */
--header-tagline-font-weight: bold;
--header-tagline-font-size: 150%;
--header-tagline-font: default;
--header-tagline-color: #fff;
--header-custom-text: '';
--header-tagline-custom-text: '';
--header-tagline-top: unset;
--header-tagline-bottom: unset;
--header-tagline-left: unset;
--header-tagline-right: unset;
--header-tagline-text-shadow: unset;
--header-mobile-tagline-font-size: 75%;
 
/* Search Bar */
--search-button-background: #003366;
--search-button-border: 3px solid #fff;
--search-button-hover-background: #364E4D;
--search-button-hover-border: 1px solid #fff;
--search-input-hover-border: 1px solid #fff;
--search-input-hover-color: #fff;
--search-input-color: #003366;
--search-input-hover: #2d3668;
--search-input-border: 2px solid #fff;
 
/* Sidebar */
--sidebar-divider-color: var(--basic-border-color);
--sidebar-header-color: var(--primary-text-color);
--sidebar-hover-background: var(--nav-hover-background);
--sidebar-hover-color: #fff;
--sidebar-color: var(--text-color);
--sidebar-mobile-open-menu-color: var(--basic-border-color);
--sidebar-mobile-open-menu-border: 3px solid var(--basic-border-color);
--sidebar-mobile-open-menu-background: var(--primary-background);
--sidebar-mobile-background: var(--primary-background);
--sidebar-crit-corner-color: #b5d6ff;
 
/* Topbar */
--topbar-text-color: #aaa;
--topbar-dropdown-background: var(--body-background);
--topbar-hover-background: var(--nav-hover-background);
--topbar-divider: 1px solid var(--topbar-hover-background);
--topbar-dropdown-border-color: var(--basic-border-color);
--topbar-hover-color: #fff;
--topbar-dropdown-color: var(--text-color);
 
/* Link Colors */
--link-color: #5295e1;
--link-hover-color: #84b7f5;
--new-page-color: #626eb2;
--external-graphic-color: var(--star-rating-hue);
 
/* Wikidot Tables */
--table-header-background: var(--content-bar-background);
--table-header-background-alt: var(--background-3);
--table-header-color: var(--text-color);
--table-cell-color: var(--text-color);
--table-cell-background: var(--primary-background);
--table-border: 1px solid #333;
--table-box-shadow: var(--content-box-shadow);
 
/* Footnotes */
--footnote-border: var(--basic-border);
--footnote-background: var(--primary-background);
 
/* Table of Contents */
--toc-border: none;
--toc-background: var(--primary-background);
--toc-box-shadow: var(--content-box-shadow);
 
/* Content Panels */
--content-panel-border-radius: var(--element-border-radius);
--content-panel-background: var(--primary-background);
--content-panel-border: none;
--content-panel-padding: 10px 20px;
--content-panel-box-shadow: var(--content-box-shadow);
--content-bar-color: #777;
--news-block-body-panel-background-even: #1a1c1e;
--content-block-border: none;
--content-box-border-color: #808080;
--nested-content-border: 1px solid #333; /* border of content when inside other content elements (blockquotes, tabview, content-panels, etc.) */
 
/* Quotes */
--blockquote-background: #ccc;
--blockquote-border: #000;
--blockquote-border-radius: #000;
--blockquote-padding: 1px 1px;
--blockquote-box-shadow: none;
 
/* Image Blocks */
--image-block-caption-background: var(--content-bar-background);
--image-block-border: none;
--image-block-background: var(--primary-background);
--image-block-box-shadow: var(--content-box-shadow);
 
/* Rating Modules */
--star-rating-background: var(--primary-background);
--star-rating-border: none;
--star-rating-reading-background: #364E4D;
--star-rating-decimal-color: var(--text-color);
--binary-rating-background: var(--primary-background);
--binary-rating-border: none;
--star-rating-hue: 0deg;
--star-rating-filter: hue-rotate(calc(var(--star-rating-hue) + 350deg)) invert(1) saturate(0.4) brightness(1.3);
--star-rating-border-radius: 0px;
--star-rating-box-shadow: none;
--star-rating-stars-box-shadow: none;
--star-rating-cell-background: var(--content-bar-background);
--nested-star-rating-border: 1px solid var(--star-rating-cell-background);
 
/* Text Inputs */
--text-box-form-background: #181d22;
--text-box-form-border: 1px solid #2c3340;
 
/* Forum Threads */
--forum-thread-background: rgba(0,0,0,0.21);
--forum-thread-border: none;
--forum-thread-border-radius: 5px;
--forum-thread-box-shadow: none;
 
/* Forum Categories */
--forum-category-background-even: #1a1c1e;
--forum-category-background-odd: var(--primary-background);
 
/* Code Blocks */
--code-background: #ccc;
--code-border: #ccc;
 
/* Account Options */
--account-options-background: #fff;
--account-options-border: #fff;
 
/* Template Block */
--template-block-border: 2px solid #666;
--template-block-background: #14141a;
 
/* Pop-Up Boxes */
--modal-body-background: rgba(27,33,37,0.34);
--modal-header-background: #14141a;
 
/* Sidenotes */
--sidenote-open-background: #1c2431;
--sidenote-closed-background: var(--content-bar-background);
--sidenote-box-shadow: var(--content-box-shadow);
--sidenote-background: var(--primary-background);
--sidenote-contents-border: 1px dashed #333;
--sidenote-figure-border: 1px solid #333;
--sidenote-contents-open-color: var(--text-color);
--sidenote-figure-open-color: var(--text-color);
--sidenote-contents-closed-color: var(--text-color);
--sidenote-figure-closed-color: var(--text-color);
 
/* Variables Specific to Black Theme */
--BT-open-themes-border: 2px solid #aaa;
--BT-open-themes-background: #fff;
--BT-open-themes-color: #000;
--BT-open-themes-hover-color: #07f;
--BT-open-themes-hover-border: solid 2px #5295e1;
--BT-scrollbar-background: var(--primary-background);
--BT-scrollbar-thumb-background: #273b5a;
--BT-scrollbar-thumb-hover-background: #283649;
--BT-resizer-background: #191919;
}
 
/* Sidebar */
#side-bar {
    position: absolute;
}
 
#side-bar .side-block {
    padding-right: calc(8.1em - 1px);
    margin-right: -8.5em;
    margin-bottom: 30px;
}
 
#side-bar .heading {
    font-size: 1.2em;
    margin: 1em calc(-1em + 2px) 0.5em 0;
    font-weight: bold;
    color: var(--sidebar-header-color);
}
 
#side-bar hr {
    background-color: var(--sidebar-divider-color);
    width: 220px;
}
 
#side-bar div.menu-item a {
    transition: all 0.1s ease-in-out;
    display: block;
    margin: 0 calc(-1em - 1px) 0 -0.5em;
    padding: 0.4em 1em 0.4em 0.5em;
    font-size: 12.8px;
    color: var(--sidebar-color);
    width: 220px;
}
 
#side-bar div.menu-item a:hover {
    background-color: var(--sidebar-hover-background);
    color: var(--sidebar-hover-color);
    text-decoration: none;
}
 
#side-bar div.menu-item p {
    margin: 0;
}
 
#side-bar .menu-item a[href="/rpc-series"]::after {
    font-size: 80%;
    opacity: 0.7;
    margin-left: 0.5em;
    content: "(001-999)"
}
 
#side-bar .menu-item.discord a::before {
    content: url('http://rpcauthority.wdfiles.com/local--files/nav%3Aside/discord.png');
    position: absolute;
    left: 15em;
}
 
#side-bar .menu-item.lore a::before {
    content: url('http://www.rpc-wiki.net/local--files/nav:side/lore.png');
    position: absolute;
    left: 15em;
}
 
#side-bar .menu-item.reddit a::before {
    content: url('http://rpcauthority.wdfiles.com/local--files/nav%3Aside/reddit.png');
    position: absolute;
    left: 15em;
}
 
#side-bar .menu-item.steam a::before {
    content: url('http://rpcauthority.wdfiles.com/local--files/nav%3Aside/steam.png');
    position: absolute;
    left: 15em;
}
 
#side-bar .menu-item.twitter a::before {
    content: url('http://rpcauthority.wdfiles.com/local--files/nav%3Aside/twitter.png');
    position: absolute;
    left: 15em;
}
 
#side-bar .menu-item.redbubble a::before {
    content: url('http://rpcauthority.wdfiles.com/local--files/nav%3Aside/redbubble.png');
    position: absolute;
    left: 15em;
}
 
#main-content {
    margin: 0 2em 0 21em;
    padding: 2em 2em calc(14em - 1px) 3em;
}
 
li, p {
    line-height: 141%;
    word-wrap: break-word;
}
 
/* Horizontal Rules */
hr {
    background: var(--horizontal-rule-background);
    Margin: 1em 0;
}
 
/* Links */
a {
    color: var(--link-color);
    text-decoration: none;
    background: transparent;
    transition: color 0.5s ease;
}
 
a.newpage {
    color: var(--new-page-color);
    text-decoration: none;
    background: transparent;
}
 
a:hover {
    text-decoration: underline;
    background-color: transparent;
    color: var(--link-hover-color);
}
 
a::after {
  filter: hue-rotate(var(--external-graphic-color));
}
 
.form-control {
    width: 95%;
}
 
/* Global Width */
#header, #top-bar {
    width: 90%;
    max-width: 980px;
    margin: 0 auto;
}
 
/* Header Elements */
div#container-wrap {
    background: var(--header-background) top left repeat-x;
}
 
#header {
    position: relative;
    z-index: 10;
    padding-bottom: 22px;
    background: var(--header-icon) var(--header-icon-adv);
    background-size: var(--header-icon-size);
    height: 144px;
}
 
#search-top-box {
    position: absolute;
    top: 79px;
    right: 9px;
    width: 250px;
    text-align: right;
    height: 16px;
}
 
#search-top-box-input {
    transition: background-color 0.5s ease;
    border: var(--search-input-border);
    border-radius: 0;
    color: var(--text-color);
    background-color: var(--search-input-color);
    height: 20px;
    box-sizing: border-box;
    vertical-align: bottom;
}
 
#search-top-box-input:hover,
#search-top-box-input:focus {
    border: var(--search-input-hover-border);
    color: var(--search-input-hover-color);
    background-color: var(--search-input-hover);
}
 
#search-top-box-form input[type=submit] {
    transition: background,border,color 0.5s ease;
    border: var(--search-button-border);
    border-radius: 0;
    padding: 2px 5px;
    font-size: 90%;
    font-weight: bold;
    color: var(--text-color);
    background: var(--search-button-background);
    cursor: pointer;
    position: relative;
    height: 20px;
}
 
#search-top-box-form input[type=submit]:hover,
#search-top-box-form input[type=submit]:focus {
    border: var(--search-button-hover-border);
    color: #fff;
    text-shadow: 0 0 1px rgba(255,255,255,.25);
    background: var(--search-button-hover-background);
}
 
#header h1 {
    margin-left: 120px;
    padding: 0;
    float: left;
    max-height: 95px;
    margin-top: 0;
    font-weight: var(--header-font-weight);
}
 
#header h2::before {
    content: var(--header-tagline-custom-text);
    font-weight: var(--header-tagline-font-weight);
    color: var(--header-tagline-color);
    font-family: var(--header-tagline-font);
}
 
#header h1 a::before {
    content: var(--header-custom-text);
}
 
#header h2 {
    margin-left: 120px;
    padding: 0;
    clear: left;
    float: left;
    font-size: var(--header-tagline-font-size);
    max-height: 38px;
    letter-spacing: 1px;
    position: relative;
    top: var(--header-tagline-top);
    bottom: var(--header-tagline-bottom);
    left: var(--header-tagline-left);
    right: var(--header-tagline-right);
    text-shadow: var(--header-tagline-text-shadow);
}
 
#header h1 a {
    display: block;
    margin: 0;
    padding: 80px 0 25px;
    margin-left: -3em;
    padding-left: 3em;
    line-height: 0px;
    max-height: 0px;
    color: var(--header-color);
    background: transparent;
    font-family: var(--header-font);
    text-decoration: none;
    letter-spacing: 0.9px;
    font-size: var(--header-font-size);
}
 
#header h1 a span {
    visibility: var(--header-text-visibility);
}
 
#header h2 span {
    display: block;
    margin: 0;
    padding: 19px 0;
    line-height: 0px;
    max-height: 0px;
    font-weight: var(--header-tagline-font-weight);
    color: var(--header-tagline-color);
    font-family: var(--header-tagline-font);
    visibility: var(--header-text-visibility);
}
 
/* Topbar */
#top-bar {
    width: 100%;
    margin: 0 auto;
}
 
.mobile-top-bar {
    display: none;
    position: absolute;
    left: 1em;
    bottom: 0px;
    z-index: 0;
}
 
#top-bar {
    position: absolute;
    z-index: 50;
    top: 140px;
    height: 21px;
    line-height: 18px;
    padding: 0;
    z-index: 20;
    font-size: 90%;
}
 
#top-bar ul {
    float: right;
}
 
#top-bar li {
    margin: 0;
}
 
#top-bar a {
    color: var(--topbar-text-color);
    background: transparent;
    transition: none;
}
 
#top-bar ul li {
    border: 0;
    position: relative;
}
 
#top-bar ul li ul {
    border: solid 1px var(--topbar-dropdown-border-color);
    box-shadow: 0 2px 6px rgba(0,0,0,.5);
    border-top: 0;
}
 
#top-bar ul li a {
    border-left: solid 1px rgba(64,64,64,.1);
    border-right: solid 1px rgba(64,64,64,.1);
    text-decoration: none;
    padding-top: 10px;
    padding-bottom: 10px;
    line-height: 1px;
    max-height: 1px;
    overflow: hidden;
}
 
#top-bar ul li.sfhover a,
#top-bar ul li:hover a {
    background: var(--topbar-dropdown-background);
    color: var(--topbar-hover-color);
    border-left: var(--topbar-divider);
    border-right: var(--topbar-divider);
}
 
#top-bar ul li.sfhover ul li a,
#top-bar ul li:hover ul li a {
    border-width: 0;
    width: 150px;
    line-height: 160%;
    height: auto;
    max-height: none;
    padding-top: 0;
    padding-bottom: 0;
    color: var(--topbar-dropdown-color);
}
 
#top-bar ul li.sfhover a:hover,
#top-bar ul li:hover a:hover {
    background: var(--topbar-hover-background);
    color: var(--topbar-hover-color);
    text-decoration: none;
}
 
#top-bar ul li:hover>a {
    background: var(--topbar-hover-background);
    color: var(--topbar-hover-color);
}
 
#top-bar ul li ul {
    border-width: 0 1px 1px 1px;
    width: auto;
}
 
#top-bar ul li ul li, #top-bar ul li ul li.sfhover,
#top-bar ul li ul li, #top-bar ul li ul li:hover {
    border-width: 0;
}
 
#top-bar ul li ul li a {
    border-width: 0;
    color: #fff;
}
 
.top-bar ul li:last-of-type ul {
    right: 0;
}
 
#top-bar ul {
    margin-top: 5px;
}
 
/* Content */
#main-content {
    margin: 0 2em 0 22em;
    padding: 1em;
    position: relative;
}
 
/* Parented Pages Block */
#breadcrumbs {
    margin: -1em 0 1em;
    font-weight: 85%;
}
 
 /*Tabs*/
--selected-tab: #007a99;
--hover-tab: #fff;
--inactive-tab: #007a99;
 
/*SETTINGS HORIZONTAL LINE*/
.yui-navset .yui-nav,
.yui-navset .yui-navset-top .yui-nav {
    border:solid #000; /* color of the horizontal line between tab list and selected content */
    border-width:0 0 5px; /*thickness of the horizontal line between tab list and content */
}
.yui-navset .yui-nav li,
.yui-navset .yui-navset-top .yui-nav li {
    margin:0 2px 0 0; /* space between tabs */
}
.yui-navset .yui-nav .selected,
.yui-navset .yui-navset-top .yui-nav .selected {
    margin:0 1px -1px 0; /* for overlap */
}
/* SETTINGS FOR UNSELECTED TABS */
.yui-navset .yui-nav a,
.yui-navset .yui-navset-top .yui-nav a {
    background:#007a99 url(http://themes.wikidot.com/local--files/rainbow-base/tabcolor.png) repeat-x -3px;
    border-top:solid #000 1px;
    border-left:solid #000 1px;
    border-right:solid #000 1px;
    font-weight:none;
    font-family:Arial;
    font-size:140%;
    color:#000;/*tab text color*/
}
.yui-navset .yui-nav a em,
.yui-navset .yui-navset-top .yui-nav a em {
    border:solid #000 0px;
}
 
/*HOVER SETTINGS FOR UNSELECTED TABS*/
.yui-navset .yui-nav a:hover,
.yui-navset .yui-navset-top .yui-nav a:hover {
    background:#007a99
}
 
/* SETTINGS FOR SELECTED TABS */
.yui-navset .yui-nav .selected a,
.yui-navset .yui-nav .selected a:focus,
.yui-navset .yui-nav .selected a:hover {
    background:#007a99 url(http://themes.wikidot.com/local--files/rainbow-base/tabcolor.png) repeat-x -3px;
    color:#000;border:1px solid #000;font-weight:600
}
 
/* SETTINGS FOR SELECTED CONTENT */
.yui-navset .yui-content {
    background-color: #fff; /* content background color */
}
 
.yui-navset .yui-content,
.yui-navset .yui-navset-top .yui-content {
    border-color: #000; /* content border */
    border-top-color:#000; /* different border color */
}
 
.yui-navset-left .yui-content {
    border-color: #000; /* content border */
    border-left-color: #000; /* different border color */
}
 
.yui-navset-bottom .yui-content,
.yui-navset .yui-navset-bottom .yui-content {
    border-color: #000; /* content border */
    border-bottom-color: #000; /* different border color */
}
 
/*---BUTTON RECOLORING---*/
#h-perpage, .optionstd a, .new-post .btn {
    border: 1px solid #666!important;  
    background-color: #000!important;
    color: white!important;
}
 
#h-perpage:hover, .optionstd a:hover, .new-post .btn:hover {
    border: 1px solid #666!important;  
    background-color: #fff!important;
    color: #000!important;
    text-decoration: none!important;
}
 
/* Footer */
#footer {
    clear: both;
    font-size: 77%;
    background: var(--footer-background);
    color: var(--footer-color);
    margin-top: 15px;
    padding: 3px 10px;
}
 
#footer .options {
    visibility: visible;
    display: block;
    float: right;
    width: 50%;
    font-size: 100%;
    text-align: right;
}
 
#footer a {
    color: #fff;
    background: transparent;
}
 
/* Fix Overflow */
.page-source, blockquote {
    word-wrap: break-word;
}
 
/* Custom Page Content Classes */
#page-content {
    min-height: 1200px;
    background: var(--page-background);
    padding: var(--page-padding);
    Border: var(--page-border);
    border-radius: var(--page-border-radius);
}
 
.unmargined > p {
    margin: 0;
    line-height: 100%;
    color: var(--unmargined-color);
}
 
.content-panel {
    border-radius: var(--content-panel-border-radius);
    background: var(--content-panel-background);
    border: var(--content-panel-border);
    padding: var(--content-panel-padding);
    margin: 10px 20px 15px 20px;
    box-shadow: var(--content-panel-box-shadow);
}
 
.content-panel.centered {
    text-align: center;
}
 
.content-panel.dark {
    background: var(--secondary-background);
}
 
.info-block.left-column, .info-block.right-column, .featured-block.left-column, .featured-block.right-column {
    width: 48%;
    padding: 0;
}
 
.content-panel.content-toc {
    float: right;
    padding: 0 20px;
    white-space: nowrap;
    margin: 10px 0 15px 5px;
  }
 
.featured-title {
    font-weight: bold;
    height: 35px;
    font-size: 110%;
}
 
.news-block, .featured-block, .info-block {
    border: var(--content-block-border);
}
 
.news-block, .info-block {
    margin: 15px 0;
    box-shadow: var(--content-box-shadow);
}
 
.news-block .body-panel {
    background: var(--content-panel-background);
    padding: 10px;
}
 
.news-block .body-panel .news-date {
    color: #777;
    font-size: 80%;
}
 
.news-block .body-panel .news-content {
    margin: 10px 0px 10px 30px;
}
 
.info-block .body-panel {
    background: var(--content-panel-background);
    padding: 10px;
    font-size: 90%;
}
 
.info-block .body-panel.centered {
    text-align: center;
}
 
.header-panel {
    background: var(--content-bar-background);
    padding: 5px;
    font-weight: bold;
    font-size: 75%;
    color: var(--content-bar-color);
}
 
.footer-panel {
    background: var(--content-bar-background);
    padding: 5px;
    font-weight: bold;
    font-size: 75%;
    text-align: right;
    Color: var(--content-bar-color);
}
 
.news-block .footer-panel a {
    color: var(--primary-text-color);
}
 
.news-block .body-panel:nth-child(even) {
    background: var(--news-block-body-panel-background-even);
}
 
.featured-block {
    box-shadow: var(--content-box-shadow);
    margin: 15px 0;    
}
 
.featured-block .body-panel {
    background: var(--content-panel-background);
    text-align: left;
    padding: 10px;
    height: 100%;
    overflow-y: hidden;
}
 
.featured-block.left-column .body-panel, .featured-block.right-column .body-panel {
    height: 150px;
}
 
.featured-block .body-panel.short {
    height: auto;
}
 
.content-panel hr, .yui-content hr, .info-block hr, .news-block hr, .featured-block hr, blockquote hr {
    background: var(--horizontal-rule-secondary-background);
}
 
.clean hr {
    border: 2px dashed var(--content-bar-background);
    height: 0px;
    background: none;
    margin: auto -20px;
}
 
.content-box {
    border-radius: 0;
    border: 2px solid var(--content-box-border-color);
    padding: var(--content-panel-padding);
    margin: 10px 20px 15px 20px;
}
 
.content-box.dashed {
    border-style: dashed;    
}
 
.content-box.thin {
    border-width: 1px;
}
 
.content-box.round {
    border-radius: 20px;
}
 
.left-column {
    float: left;
    width: 40%;
    margin: 10px 0;
}
 
.right-column {
    float: right;
    width: 40%;
    margin: 10px 0;
}
 
/* Template Block (Original Formatting by Dr. Pierson) */
.templateBlock {
    background: var(--template-block-background);
    border: var(--template-block-border);
    width: 450px;
    margin: 0 auto 15px auto;
    text-align: center;
    padding: 0 15px;
    Max-width: 90%;
}
 
.templateBlock img {
    max-width: 100%;
}
 
.templateBlock.special {
  background: linear-gradient(#222e2e, #171f1f, #222e2e);;
}
 
/* Tags */
.page-tags span {
    border-top: var(--tags-border);
}
 
/* Multi-Line Tags Fix */
#main-content .page-tags {
    margin: 1em 0 0;
    padding: 0;
}
 
#main-content .page-tags span {
    display: inline-block;
    padding: 0;
    max-width: 60%;
}
 
#main-content .page-tags a {
    display: inline-block;
    white-space: nowrap;
}
 
/* Hide Hidden Tags */
#main-content .page-tags a[href^="/system:page-tags/tag/_"] {
    display: none;
}
 
/* Pop-Up Text Boxes */
.modal-body img {
    background: none!important;
}
 
.modal-body {
    background: var(--modal-body-background);
}
 
.modal-header, .owindow, .owindow .title {
    background: var(--modal-header-background)!important;    
}
 
.owindow {
    border: var(--owindow-border);
}
 
.owindow table.table a {
    word-break: break-word;
}
 
/* Ruby by Nanimono Demonai */
 
.ruby, ruby {
    display: inline-table;
    text-align: center;
    white-space: nowrap;
    line-height: 1;
    height: 1em;
    vertical-align: text-bottom;
}
 
.rt, rt {
    display: table-header-group;
    font-size: 0.6em;
    line-height: 1.1;
    text-align: center;
    white-space: nowrap;
}
 
/* Keycap */
.keycap {
    border: 1px solid;
    border-color: #ddd #bbb #bbb #ddd;
    border-bottom-width: 2px;
    -moz-border-radius: var(--element-border-radius);
    -webkit-border-radius: var(--element-border-radius);
    border-radius: var(--element-border-radius);
    background-color: #f9f9f9;
    padding: 1px 3px;
    font-family: inherit;
    font-size: 0.85em;
    white-space: nowrap;
}
 
/*
    2011-11-13 Minobe Hiroyuki @ Marguerite Site
    www.marguerite.jp/Nihongo/WWW/CSSTips/EmphasizeDots-CSS3.html
    Edited for the SCP Foundation by Nanimono_Demonai
*/
 
.emph {
    text-emphasis-style: dot ;
    -webkit-text-emphasis-style: dot ;
}
 
/* Account Options */
#login-status {
    font-size: 90%;
    z-index: 30;
}
 
#printuser {
    color: var(--text-color);
    background-color:transparent;
}
 
#login-status a {
    color: var(--text-color);
    background-color: transparent;
}
 
#login-status a:hover {
    color: var(--link-hover-color);
}
 
#account-options {
    background: var(--account-options-background);
    border: var(--account-options-border);
}
 
#account-options li a:hover {
    color: var(--link-hover-color);
}
 
#account-options a, a#account-topbutton {
    font-weight: normal;
    background-color: transparent;
}
 
#account-options #account-options, a#account-topbutton {
    background-color: transparent;
    border-style: none;
    color: var(--text-color);
}
 
sup {
    vertical-align: top;
    position: relative;
    top: -0.5em;
}
 
body {
    background: var(--body-background);
    color: var(--text-color);
    font-size: 0.80em;
  }
 
#content-wrap {
    position: relative;
    margin: 2em auto 0;
    max-width: 1040px;
    min-height:1500px;
    height: auto;
}
 
ul {
    list-style: square;
}
 
h3, h4, h5, h6, h7 {
    margin: 0.5em 0 0.4em;
    padding: 0;
    letter-spacing: 1px;
}
 
#page-title {
    color: var(--page-title-color);
    font-weight: bold;
    padding: 0 0 0.25em;
    margin: 0 0 0.6em;
    border-bottom: var(--page-title-border);
    word-wrap: break-word;
    position: relative;
    top: 1px;
}
 
blockquote {
    border: var(--blockquote-border);
    color: var(--text-color);
    background: var(--blockquote-background);
    border-radius: var(--blockquote-border-radius);
    padding: var(--blockquote-padding);
    box-shadow: var(--blockquote-box-shadow);
  }
 
/* Standard Image Block */
.image-block {
    border: var(--image-block-border);
    width: 300px;
    box-shadow: var(--image-block-box-shadow);
    background: var(--image-block-background);
}
 
.image-block.block-right {
    float: right;
    clear: right;
    margin: 0 2em 1em 2em;
}
 
.image-block.block-left {
    float: left;
    clear: left;
    margin: 0 2em 1em 0;
}
 
.image-block.block-center {
    margin-right: auto;
    margin-left: auto;
}
 
.image-block img {
    border: 0;
    width: 300px;
}
 
.image-block .image-caption {
    background: var(--image-block-caption-background);
    border-top: var(--image-block-border);
    padding: 2px 0;
    font-size: 80%;
    font-weight: bold;
    text-align: center;
    width: 300px;
}
 
.image-block > p {
    margin: 0;
}
 
.image-block .image-caption > p {
    margin: 0;
    padding: 0 10px;
}
 
.image-block img, .image-block, .image-caption {
    max-width: 100%;
}
 
/* Sidenotes */
 
.sidenoteImage.sidenoteType-text {
    display: none!important;
}
 
.sidenoteContent.sidenoteType-image {
    display: none!important;
}
 
.sidenoteIT.sidenoteImage-bottom {
    display: none!important;
}
 
.sidenoteIB.sidenoteImage-top {
    display: none!important;
}
 
.sidenoteC {
    border: var(--sidenote-contents-border);
    color: var(--sidenote-contents-closed-color);
    border-top: none;
    padding: 0.3em 0.7em;
}
 
.sidenoteI {
    padding: 1px;
}
 
.sidenoteH {
    background: var(--sidenote-closed-background);
    border: var(--sidenote-figure-border);
    color: var(--sidenote-figure-closed-color);
    text-align: center;
    padding: 0 15px 0 15px;
}
 
.sidenote {
    position: static;
}
 
.sidenoteContainer {
    width: 100%;
    clear: both;
    margin: 0px 0px 10px 0px;
    box-shadow: var(--sidenote-box-shadow);
    background: var(--sidenote-background);
}
 
.sidenoteAlign-right {
    width: 300px!important;
    float: right;
    margin: 0px 0px 10px 10px!important;
}
 
.sidenoteAlign-left {
    width: 300px!important;
    float: left;
    margin: 0px 10px 10px 0px!important;
}
 
@media (min-width: 1000px) {
    .sidenoteAlign-right.sidenoteAlign-true {
        margin: 0px 2em 10px 10px!important;
    }
 
    .sidenoteAlign-left.sidenoteAlign-true {
        margin: 0px 10px 10px 2em!important;
    }
 
    .sidenote.sidenoteLock-false:hover .sidenoteH {
        background: var(--sidenote-open-background);
        color: var(--sidenote-figure-open-color);
    }
 
    .sidenote.sidenoteLock-false .sidenoteC, .sidenote.sidenoteLock-false .sidenoteI {
        display: none;
        color: var(--sidenote-contents-open-color);
    }
 
    .sidenote.sidenoteLock-false:hover .sidenoteC, .sidenote.sidenoteLock-false:hover .sidenoteI {
        display: block;
    }
}
 
@media (max-width: 999px) {
    .sidenoteContainer {
        float: none;
        margin: 10px 0!important;
        width: 100%!important;
    }
    .sidenoteH {
        background: var(--sidenote-open-background);
        color: var(--sidenote-figure-open-color);        
    }
    .sidenoteC, .sidenoteI {
        color: var(--sidenote-contents-open-color);        
    }
}
 
.redaction {
    background: #111;
    color: transparent;
}
 
/* Hazards Component */
 
.hazardTypeText.hazardsType-properties,
.propertiesText.hazardsType-hazards,
.hazardTableText.hazardsType-none {
    display: none!important;
}
 
.hazardTableText {
width: 110px; 
vertical-align: top; 
position: relative; 
right: 2px; 
top: 10px; 
padding: 0;
}
 
.hazardTableText.hazardsType-properties {
    width: 160px;
}
 
.hazardImage {
margin-top: 1px;
width: 35px;
filter: invert(91%);
opacity: 1;
font-size: 80%;
font-weight: bold;
}
 
.hazardBlock {
  position: relative;
  display: inline-block;
}
 
.hazardBlock .hazardText {
  visibility: hidden;
  width: 120px;
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 5px 0;
  border-radius: 6px;
  width: 120px;
  bottom: 100%;
  left: 50%;
  margin-left: -60px;
  position: absolute;
  z-index: 1;
}
 
.hazardBlock:hover .hazardText {
  visibility: visible;
}
 
.hazardBlock .hazardText::after {
  content: " ";
  position: absolute;
  top: 100%;
  left: 50%;
  margin-left: -5px;
  border-width: 5px;
  border-style: solid;
  border-color: #333 transparent transparent transparent;
}
 
.hazardBlock .hazardText {
  opacity: 0;
  transition: all 0.2s ease-in-out;
}
 
.hazardBlock:hover .hazardText {
  opacity: 1;
}
 
table.hazardTable {
    padding-right: 5px!important;
}
 
@media (max-width: 768px) {
    table.hazardTable {
    padding-right: 20px!important;
    }
}
 
/* Wikidot Tables */
table.wiki-content-table {
    width: 100%;
    box-shadow: var(--table-box-shadow);
}
 
table.wiki-content-table th {
    background-color: var(--table-header-background);
    border: var(--table-border);
    color: var(--table-header-color);
    padding: 0.3em 0.7em;
}
 
table.wiki-content-table td {
    background-color: var(--table-cell-background);
    border: var(--table-border);
    padding: 0.3em 0.7em;
    color: var(--table-cell-color);
}
 
.wanted-pages-module th, .page-compare th {
    background-color: var(--table-header-background);
    border: var(--table-border)!important;
    color: var(--table-header-color);
}
 
.wanted-pages-module td, .page-compare td {
    background-color: var(--table-cell-background);
    border: var(--table-border)!important;
}
 
/* Footnotes */
.hovertip {
    border: var(--footnote-border)!important;
    background: var(--footnote-background)!important;
  }
 
/* Table of Contents */
#toc {
    color: var(--text-color);
    border: var(--toc-border);
    background: var(--toc-background);
    Box-shadow: var(--toc-box-shadow);
}
 
/* Module Rate Customization (Upvote / Downvote System) */
.page-rate-widget-box {
    display: inline-block;
    margin-bottom: 10px;
    margin-right: 2em;
    box-shadow: var(--content-box-shadow);
}
 
.page-rate-widget-box .rate-points {
    background-color: var(--binary-rating-background)!important;
    border: var(--binary-rating-border);
    color: var(--text-color)!important;
}
 
.page-rate-widget-box .rateup,
.page-rate-widget-box .ratedown {
    border-top: var(--binary-rating-border);
    border-bottom: var(--binary-rating-border);
}
 
.page-rate-widget-box .rateup a,
.page-rate-widget-box .ratedown a {
    background: var(--binary-rating-background);
    color: var(--link-color);
    font-weight: bold;
}
 
.page-rate-widget-box .rateup a:hover,
.page-rate-widget-box .ratedown a:hover {
    transition: background 0.5s ease;
    background: var(--text-color);
    color: var(--binary-rating-background);
    text-decoration: none;
}
 
.page-rate-widget-box .cancel {
    border: var(--binary-rating-border);
}
 
.page-rate-widget-box .cancel a {
    background: var(--binary-rating-background);
    color: var(--text-color);
    text-transform: uppercase;
    font-weight: bold;
}
 
.page-rate-widget-box .cancel a:hover {
    transition: background 0.5s ease;
    background: var(--text-color);
    color: var(--binary-rating-background);
    text-decoration: none;
}
 
 /* component:rate Customization (5 Star System) */
.rateContainer {
    width: 100%;
    height: 30px;
}
 
.ratingContainer {
    height: auto;
}
 
.tableStyle {
    background: var(--star-rating-background);
    margin-right: 2em;
    display: inline-block;
    border-collapse: collapse;
    border-spacing: 0px;
    border: var(--star-rating-border);
    box-shadow: var(--content-box-shadow);
    border-radius: var(--star-rating-border-radius);
}
 
.rateStyle {
    margin-right: 2em;
    box-shadow: var(--star-rating-box-shadow);
}
 
.starStyle {
    display: inline-block;
    padding: 2px 4px 0px 4px;
    margin: 0;
    background: var(--star-rating-background);
    box-shadow: var(--star-rating-stars-box-shadow);
}
 
.cellStyle {
    display: inline-block;
    padding: 1px 4px 0px 4px;
    background: var(--star-rating-cell-background);
    height: 20px;
    border: none;
}
 
.cellStyle p, .cellStyle div p {
    margin: 0;
}
 
.decimalStyle {
    background-color: var(--star-rating-background);
    padding-right: 6px;
    color: var(--star-rating-decimal-color);
}
 
.translationStyle {
    padding-left: 6px;
    padding-right: 6px;
    background-color: var(--star-rating-background);
}
 
.readingStyle {
    background: var(--star-rating-reading-background);
    padding: 0 3px 0 3px;
    border-left: var(--star-rating-border);
}
 
.cellStyle.votesRight-left, 
.cellStyle.votesLeft-right, 
.cellStyle.votesRight-none, 
.cellStyle.votesLeft-none {
    display: none;
}
 
.starStyle.votesRight-left, 
.starStyle.votesRight-none {
    text-align: center;
}
 
img[src$="/common--images/jquery-raty/star-on.png"] {
    filter: var(--star-rating-filter);
}
 
img[src$="/common--images/jquery-raty/star-half.png"] {
    filter: var(--star-rating-filter);
}
 
img[src$="/common--images/jquery-raty/star-off.png"] {
    filter: var(--star-rating-filter);
}
 
/* Generic Buttons */
#h-perpage,
.optionstd a,
.new-post .btn,
#history-form-1 .btn-sm,
.well .btn-sm,
.change-textarea-size a,
.buttons .btn-small,
.action-area .btn-default,
.action-area .btn-primary,
.col-lg-10 .form-control,
.form-actions .btn-danger,
.buttons .btn-default,
.target a,
.buttons .btn-danger,
#edit-cancel-button,
#edit-save-button,
.button-close-message,
.button-close-window,
.button-cancel,
.button-insert-code,
#wd-ed-codewizard-type,
#wd-ed-imagewizard-position,
#wd-ed-imagewizard-uri,
#wd-ed-imagewizard-byuri .button,
#wd-ed-imagewizard-flickr,
#wd-ed-imagewizard-byflickr .button,
.query-area .button,
.button-close,
.button-rename,
.button-no\,-cancel,
.button-yes\,-delete,
#file-upload-form .btn-primary,
.button-move,
#action-area .buttons .btn-primary,
#edit-page-form .buttons .btn-info,
#view-diff-div .button,
.button-yes\,-revert,
.modal-footer .btn-danger,
.modal-footer .btn-default,
.modal-footer .btn-primary,
#mba-apply,
.yui-content .button,
.btn-warning,
#edit-meta-newtag-form div .btn,
.new-page-box .button,
#page-templates,
#recent-posts-category,
.forum-recent-posts-box form .btn,
.owindow .button-bar .btn {
    border: var(--button-border)!important;  
    background: var(--button-background)!important;
    color: var(--text-color);    
}
 
#h-perpage:hover,
.optionstd a:hover,
.new-post .btn:hover,
#history-form-1 .btn-sm:hover,
.well .btn-sm:hover,
.change-textarea-size a:hover,
.buttons .btn-small:hover,
.action-area .btn-default:hover,
.action-area .btn-primary:hover,
.col-lg-10 .form-control:hover,
.form-actions .btn-danger:hover,
.buttons .btn-default:hover,
.target a:hover,
.buttons .btn-danger:hover,
#edit-cancel-button:hover,
#edit-save-button:hover,
.button-close-message:hover,
.button-close-window:hover,
.button-cancel:hover,
.button-insert-code:hover,
#wd-ed-codewizard-type:hover,
#wd-ed-imagewizard-position:hover,
#wd-ed-imagewizard-uri:hover,
#wd-ed-imagewizard-byuri .button:hover,
#wd-ed-imagewizard-flickr:hover,
#wd-ed-imagewizard-byflickr .button:hover,
.query-area .button:hover,
.button-close:hover,
.button-rename:hover,
.button-no\,-cancel:hover,
.button-yes\,-delete:hover,
#file-upload-form .btn-primary:hover,
.button-move:hover,
#action-area .buttons .btn-primary:hover,
#edit-page-form .buttons .btn-info:hover,
#view-diff-div .button:hover,
.button-yes\,-revert:hover,
.modal-footer .btn-danger:hover,
.modal-footer .btn-default:hover,
.modal-footer .btn-primary:hover,
#mba-apply:hover,
.yui-content .button:hover,
.btn-warning:hover,
#edit-meta-newtag-form div .btn:hover,
.new-page-box .button:hover,
#page-templates:hover,
#recent-posts-category:hover,
.forum-recent-posts-box form .btn:hover,
.owindow .button-bar .btn:hover {
    border: var(--button-hover-border)!important;  
    background: var(--button-hover-background)!important;
    color: var(--button-hover-color);    
    text-decoration: none;
}
 
.pager .current {
    background: var(--button-current-background);
    color: var(--text-color);
}
 
.pager {
    line-height: 25px;
}
 
#parent-page-name-list {
    color: #333;
}
 
#history-subarea a {
    text-transform: capitalize;
}
 
#history-subarea a:hover {
    background: none;
}
 
.highlight td {
    background-color: var(--body-background);
}
 
.post .active td {
    background: var(--body-background)!important;
    text-decoration: underline dashed;
}
 
#rev-type-new,
#rev-category,
#rev-perpage {
    outline: 0;
}
 
.btn-large,
#edit-meta-addbutton .btn-primary,
#rename-show-backlinks {
    padding: 5px;
}
 
a.action-area-close.btn.btn-danger {
    background: none;
}
 
.wd-editor-toolbar-panel {
    filter: brightness(80%);
}
 
/* Errors */
.error-inline {
    color: var(--error-color);
    border: none;
}
 
.error-inline::before {
    content: " ";
}
 
span.error-inline em {
    font-style: normal;
}
 
span.error-inline em::before {
    content: '"';
}
 
span.error-inline em::after {
    content: '"';
}  
 
.error-block {
    border: 1px dashed var(--error-color);
    color: var(--error-color);
}
 
/* Forum Stuff */
.forum-thread-box .description-block, .well {
    padding: .5em 1em;
    border-radius: var(--forum-thread-border-radius)!important;
    Border: var(--forum-thread-border)!important;
    background: var(--forum-thread-background)!important;
    color: var(--text-color);
    box-shadow: var(--forum-thread-box-shadow);
    margin: 1em;
}
 
.thread-container .post .head {
    padding: 0.5em 1em;
    background-color: rgba(0,0,0,0.21);
    box-shadow: inset 2px 3px 6px rgba(0,0,0,.15);
    border-radius: 5px 5px 0 0;
}
 
.folded .short {
    background: rgba(0,0,0,0.12)!important;
}
 
.head .description {
    word-wrap: break-word;
}
 
.long .content p {
    word-wrap: break-word;
}
 
.forum-group table td {
    background: none!important;
    border: none;
    padding: 5px 1px;
}
 
.forum-group table td.name .title {
    font-weight: bold;
    margin-left: 5px;
}
 
 .action-area {
    border: var(--action-area-border);
    background: none;
}
 
.thread-container .well {
    border: var(--forum-thread-border);
    background: var(--forum-thread-background);
}
 
.forum-category-box .table {
    border: none;
}
 
.forum-group table td.name .description {
    color: var(--text-color);
    font-size: 87%;
    margin-left: 5px;
}
 
.forum-category-box table td {
    padding: 5px 10px;
    border: none;
    background: none;
}
 
.collapsible-block {
    overflow-wrap: break-word;
}
 
/* Add some spacing below close collapsible links */
.collapsible-block-unfolded-link {
    margin-bottom: 10px;
}
 
/* Text Box Forms */
#thread-description,
#np-text,
#post-edit,
.field-header .form-wiki,
.field-content .form-wiki,
.text.form-control,
#file-comments,
.form .text,
#edit-meta-newtag-form .text,
.new-page-box .text,
#edit-page-textarea,
#edit-page-title,
#edit-page-comments,
.query-area .text,
#membership-by-apply-text,
.yui-content .text {
    background: var(--text-box-form-background);
    border: var(--text-box-form-border);
    color: var(--text-color);
}
 
input#page-tags-input.text {
    max-width: 330px;
}
 
.alert-info {
    background: none!important;
    border: var(--alert-info-border)!important;
}
 
.forum-start-box div.head {
    background-color: #192a44;    
    border: none;
}
 
.forum-start-box .head .title {
    text-align: center;
}
 
.head .title {
    color: rgb(181,181,181);
    word-wrap: break-word;
}
 
.head .description {
    color: rgb(181,181,181);
    text-align: center;
}
 
.forum-group table {
    border-collapse: collapse;
    border-spacing: 1px;
}
 
.forum-group .name .description {
    font-size: 0.9em;
    padding: 3px 0;
}
 
.forum-group .head .title {
    font-size: 1.1em;
}
 
.forum-category-box table {
    border-collapse: collapse;
}
 
.forum-category-box table .head td {
    background: #192a44!important;
    font-size: 1.1em;
    font-weight: bold;
}
 
.forum-category-box table tr:nth-child(even), .forum-group table tr:nth-child(even) {
     background: var(--forum-category-background-even);
}
 
.forum-category-box table tr:nth-child(odd), .forum-group table tr:nth-child(odd) {
    background: var(--forum-category-background-odd);
}
 
/* Retitle Forum Headers */
.forum-start-box .head td:nth-child(1) {
    font-size: 0px;
}
 
.forum-start-box .head td:nth-child(1)::after {
    font-size: 11px;
    content: "Category Name"
}
 
.forum-start-box .head td:nth-child(4) {
    font-size: 0px;
}
 
.forum-start-box .head td:nth-child(4)::after {
    font-size: 11px;
    content: "Last Post"
}
 
/* Add a space before "Jump!" links in the forum */
.forum-start-box td.last span.odate:after {
    content: " ";
}
 
.forum-category-box .head td:nth-child(1) {
    font-size: 0px;
}
 
.forum-category-box .head td:nth-child(1)::after {
    font-size: 11px;
    content: "Thread Name";
}
 
.forum-category-box .head td:nth-child(2) {
    font-size: 0px;
}
 
.forum-category-box .head td:nth-child(2)::after {
    font-size: 11px;
    content: "Original Poster";
}
 
.forum-category-box .head td:nth-child(4) {
    font-size: 0px;
}
 
.forum-category-box .head td:nth-child(4)::after {
    font-size: 11px;
    content: "Most Recent";
}
 
/* Hide Forum Signatures */
.signature {
    Display: none;
}
 
/* Show-Changes Highlights */
del {
    background: var(--show-changes-del-background)!important;
    text-decoration: none;
    white-space: normal!important;
}
 
ins {
    background: var(--show-changes-ins-background)!important;    
    white-space: normal!important;
}
 
ins::before, del::before {
    content: "+";
    position: absolute;
    left: 0.75em;
    font-size: 200%;
    color: transparent;
    width: 10px;
    height: 10px;
    border: 1px solid #000;
}
 
ins::before {
    border-radius: 10px;
    background: var(--show-changes-ins-background)!important;
}
 
del::before {
    background: var(--show-changes-del-background)!important;
}
 
/* Code Boxes */
.code {
    background: var(--code-background);
    border: var(--code-border);
    padding: 15px;
}
 
.code pre span {
    color: var(--text-color);
}
 
.code .hl-main pre {
    display: contents;
}
 
.revisions .active td {
    background: none;
}
 
.revisions td {
    padding: 2px;
}
 
.revisions .active {
    background-color: #3d3d3d;
}
 
#revision-list tr:nth-child(1) td {
    text-align: center;
    font-weight: bold;
}
 
.changes {
    color: var(--text-color);
}
 
.changes-list-item .comments {
    color: #a0a0a0;
}
 
.changes-list-item:hover {
    background: #333;
}
 
.statistics {
    color: var(--text-color);
}
 
.warning-block {
    background: #e2e25c;
}
 
.license-area {
    color: var(--text-color)!important;
}
 
#h-perpage {
    outline: none;
}
 
.list-pages-box table {
    padding-bottom: 0.5em;
}
 
.list-pages-box table.tableStyle {
    padding-bottom: 0;
}
 
.content-type-description-2 tr {
    background: none;
}
 
table.page-history tr td:nth-child(2)  {
    min-width: 50px;
}
 
/* Tooltip Localization */
.tooltip {
  position: relative;
  display: inline-block;
}
 
.tooltip .tooltiptext {
  visibility: hidden;
  width: 120px;
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 5px 0;
  border-radius: 6px;
  width: 120px;
  bottom: 100%;
  left: 50%;
  margin-left: -60px;
  position: absolute;
  z-index: 1;
}
 
.tooltip:hover .tooltiptext {
  visibility: visible;
}
 
.tooltip .tooltiptext::after {
  content: " ";
  position: absolute;
  top: 100%;
  left: 50%;
  margin-left: -5px;
  border-width: 5px;
  border-style: solid;
  border-color: #333 transparent transparent transparent;
}
 
.tooltip .tooltiptext {
  opacity: 0;
  transition: all 0.2s ease-in-out;
}
 
.tooltip:hover .tooltiptext {
  opacity: 1;
}
 
.tooltipblue {
  position: relative;
  display: inline-block;
}
 
.image-caption-top .tooltipblue img {
    filter: invert(91%) hue-rotate(150deg);
}
 
.tooltipblue .tooltiptextblue {
  visibility: hidden;
  width: 120px;
  background-color: #2476db;
  color: #fff;
  text-align: center;
  padding: 5px 0;
  border-radius: 6px;
   width: 120px;
  bottom: 100%;
  left: 50%;
  margin-left: -60px;
  position: absolute;
  z-index: 1;
}
 
.tooltipblue:hover .tooltiptextblue {
  visibility: visible;
}
 
.tooltipblue .tooltiptextblue::after {
  content: " ";
  position: absolute;
  top: 100%;
  left: 50%;
  margin-left: -5px;
  border-width: 5px;
  border-style: solid;
  border-color: #2476db transparent transparent transparent;
}
 
.tooltipblue .tooltiptextblue {
  opacity: 0;
  transition: all 0.2s ease-in-out;
}
 
.tooltipblue:hover .tooltiptextblue {
  opacity: 1;
}
 
/* Hide Preview and Page Version Popups */
#action-area-top .preview-message, #page-version-info {
    display: none;
}
 
/* Page Editing Form */
 
@media (min-width: 1200px) {
 
#edit-page-form {
    margin-left: -100px;
    margin-right: -65px;
}
 
}
 
#np-text {
  padding: 3px 5px;
}
 
#np-title {
  padding: 0 5px;
  margin: 5px 0;
}
 
/* Image Hover Enlarge */
@media (min-width: 769px) {
 
#edit-page-textarea {
    padding: 20px 30px;
    border: var(--thick-border);
}
 
.enlarge {
    transition: .05s;
    position: relative;
}
 
.enlarge:hover {
    transform: scale(1.5);
    transition: .05s;
    transition-delay: .2s;
    z-index: 2;
}
 
.mobileOnly {
    display: none;
}
 
.left-column hr, .right-column hr {
    border: none;
    height: 1px;
    Margin: 1em 0;
}
 
}
 
.open-themes a {
    position: absolute;
    bottom: 125px;
    right: -50px;
    z-index: 14;
    text-align: center;
    transition: all 0s ease 0s;
    width: 1em;
    height: 1em;
    font-size: 20px;
    padding: 2px;
}
 
.open-themes a:hover {
    text-decoration: none!important;
    transition: all 0s ease 0s;
}
 
@media (max-width: 768px) {
.open-themes a {
    width: 13px;
    height: 15px;
    padding: 0 2px 2px;
    bottom: 135px;
    right: -25px;
    font-size: 13px;
}
 
.open-themes-block {
    padding: 0;
    max-width: 100%;
    position: absolute;
    left: 1em;
    bottom: 0px;
    z-index: 0;
}
}
 
.open-themes p {
margin: 0;
}
 
/* Hide Banned Users */
.printuser a[href*="the-fozz-2"]:nth-child(1) {
    visibility: hidden;
}
 
.printuser a[href*="the-fozz-2"]:nth-child(2) {
    font-size: 0;
}
 
.printuser a[href*="the-fozz-2"]:nth-child(2)::before {
    content: "(account banned)";
    font-size: calc(0.8 * 16px);
    color: var(--text-color);
}
 
.modal-body img[src*="userid=6209186"] {
    display: none;
}
 
/* Viewport */
@viewport {
    width: device-width;
    zoom: 1.0;
}
 
/* Internet Explorer Viewport */
@-ms-viewport {
    width: device-width;
    zoom: 1.0;
}
 
/* Opera Viewport */
@-o-viewport {
    width: device-width;
    zoom: 1.0;
}
 
/* Google Chrome Viewport */
@-webkit-viewport {
    width: device-width;
    zoom: 1.0;
}
 
/* FireFox Viewport */
@-moz-viewport {
    width: device-width;
    zoom: 1.0;
}
 
/* Mobile Compatibility */
@media (max-width: 768px) {
 
.desktopOnly {
    display: none;
}
 
ins::before, del::before {
    left: 0.25em;
}
 
.content-panel.content-toc {
    float: none;
    border-radius: var(--element-border-radius);
    margin: 5px 0 5px 5px;
  }
 
.edit-page-bottomtable .alert-info {
    display: none;
}
 
.owindow {
    min-width: 80%;
    max-width: 99%;
}
 
.modal-body .table, .modal-body .table ~ div {
    float: left;
}
 
.owindow .button-bar {
    float: right;
}
 
.owindow div a.btn-primary {
    width: 100%;
    float: left;
}
 
#edit-page-form {
    margin-left: 10px;
    margin-right: 10px;
}
 
#header h2 {
    font-size: var(--header-mobile-tagline-font-size);
}
 
#top-bar {
    position: relative;
    top: 145px;
}
 
.side-block {
    margin-right: 0!important;
    padding-right: 0!important;
}
 
#side-bar .menu-item>a {
    padding-right: 0!important;
}
 
.mobile-top-bar ul li:last-of-type ul {
    right: 0;
}
 
/* Hide Search Button Input */
#search-top-box-input {
    display: none;
}
 
/* Relocate Search Button */
#header .button {
    position: relative;
    top: 27px;
    left: 18px;
}
 
#page-content {
    font-size: 0.9em;
}
 
#main-content {
    margin: 0;
}
 
#header, .mobile-top-bar {
    max-width: 100%;
}
 
#side-bar {
    width: 80%;
    position: relative;
}
 
.top-bar {
    display: none;
}
 
.mobile-top-bar {
    display: block;
    padding: 0;
}
 
.page-options-bottom a {
    padding: 0 4px;
}
 
#header h1 a {
    font-size: var(--header-mobile-font-size);
}
 
blockquote {
    margin: 1em 0;
}
 
#header {
    background-position: 0 5.5em;
    background-size: 60px;
}
 
#header h1, #header h2 {
    margin-left: 66px;
}
 
#header a span, #header a::before {
    position: relative;
    top: 10px;
}
 
table.form td, table.form th {
    float: left;
}
 
td.name {
    width: 15em;
}
 
table.form td, table.form th {
    padding: 0;
}
 
#edit-page-title {
    max-width: 90%;
}
 
.left-column, .right-column  {
    width: calc(100% - 40px);
    padding: 0 20px;
    float: left;
    margin: 10px 0;
}
 
#page-content div, #page-content div table {
    clear: both;
}
 
#page-content div.title {
    word-break: keep-all;
}
 
.page-history tbody tr td:last-child {
    width: 35%;
}
 
.page-history {
    font-size: 0.7em;
}
 
.yui-navset {
    z-index: 1;
}
 
.sideTabview .yui-nav li {
    font-size: 90%;
}
 
.sideTabview .yui-nav li a em {
    padding: 20px 10px!important;
}
 
#navi-bar, #navi-bar-shadow {
    display: none;
}
 
.sideTabview .yui-navset,
.sideTabview .yui-nav,
.sideTabview .yui-content,
.sideTabview .yui-content>div {
    max-height: 500px!important;
}
 
.open-menu a {
    position: fixed;
    top: 0.5em;
    left: 0.5em;
    z-index: 15;
    font-family: 'Nanum Gothic', san-serif;
    font-size: 30px;
    font-weight: 700;
    width: 30px;
    height: 30px;
    line-height: 0.9em;
    text-align: center;
    border: var(--sidebar-mobile-open-menu-border);
    background: var(--sidebar-mobile-open-menu-background)!important;
    border-radius: 0.3em;
    color: var(--sidebar-mobile-open-menu-color)!important;
    transition: all 0s ease 0s;
}
 
.open-menu a:hover {
    text-decoration: none!important;
    color: var(--link-color)!important;
    border: solid var(--link-color);
    transition: all 0s ease 0s;
}
 
#main-content {
    max-width: 90%;
    margin: 0 5%;
    padding: 0;
}
 
#side-bar {
    display: block;
    position: fixed;
    top: 0;
    left: -25em;
    width: 17em;
    height: 100%;
    background: var(--sidebar-mobile-background);
    overflow-y: auto;
    z-index: 10;
    padding: 1em 1em 0 1em;
    -webkit-transition: left 0.5s ease-in-out 0.1s;
    -moz-transition: left 0.5s ease-in-out 0.1s;
    -ms-transition: left 0.5s ease-in-out 0.1s;
    -o-transition: left 0.5s ease-in-out 0.1s;
    transition: left 0.5s ease-in-out 0.1s;
}
 
#side-bar::after {
    content: "";
    position: absolute;
    top: 0;
    width: 0;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.2);
 
}
 
#side-bar:target {
    display: block;
    left: 0;
    width: 17em;
    margin: 0;
    border: 1px solid #dedede;
    z-index: 10;
}
 
#side-bar:target + #main-content {
    left: 0;
}
 
#side-bar:target .close-menu {
    display: block;
    position: fixed;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    background: rgba(0,0,0,0.3) 1px 1px repeat;
    z-index: -1;
}
 
.image-block {
    Margin: 10px 0!important;
    float: none!important;
}
 
.image-block, .image-caption, .image-caption-top, .image-block img {
    width: 100%!important
}
 
.hazard-image-block .image-caption-top img {
    width: 35px!important;
}
 
.tableStyle {
    margin-right: 0;
}
 
.featured-block.left-column .body-panel, .featured-block.right-column .body-panel {
    height: 100%;
}
 
.featured-block.left-column, .featured-block.right-column {
    width: 100%;
}
 
.content-panel, .content-box {
Margin: 5px 0px;
}
 
#header h2::before {
    position: relative;
    top: 15px;
}
 
}
 
div.scpnet-interwiki-wrapper {
    width: 17em;
    margin-left: -5px;
}
 
iframe.scpnet-interwiki-frame {
    height: 325px;
    width: 17em;
    border: none;
}
 
@media (min-width: 768px) {
    iframe.scpnet-interwiki-frame {
        height: 325px;
        width: 18em;
    }
    div.scpnet-interwiki-wrapper {
        width: 18em;
    }
}
