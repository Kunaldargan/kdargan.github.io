## Welcome to GitHub Pages
<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />
<title>mordFacerecTrainer</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>

<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}
audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}
audio:not([controls]) {
  display: none;
  height: 0;
}
[hidden],
template {
  display: none;
}
a {
  background-color: transparent;
}
a:active,
a:hover {
  outline: 0;
}
abbr[title] {
  border-bottom: 1px dotted;
}
b,
strong {
  font-weight: bold;
}
dfn {
  font-style: italic;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
mark {
  background: #ff0;
  color: #000;
}
small {
  font-size: 80%;
}
sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sup {
  top: -0.5em;
}
sub {
  bottom: -0.25em;
}
img {
  border: 0;
}
svg:not(:root) {
  overflow: hidden;
}
figure {
  margin: 1em 40px;
}
hr {
  box-sizing: content-box;
  height: 0;
}
pre {
  overflow: auto;
}
code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}
button {
  overflow: visible;
}
button,
select {
  text-transform: none;
}
button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
button[disabled],
html input[disabled] {
  cursor: default;
}
button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
input {
  line-height: normal;
}
input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}
legend {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
}
optgroup {
  font-weight: bold;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
td,
th {
  padding: 0;
}
/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    color: #000 !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
@font-face {
  font-family: 'Glyphicons Halflings';
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot');
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular') format('svg');
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-asterisk:before {
  content: "\002a";
}
.glyphicon-plus:before {
  content: "\002b";
}
.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}
.glyphicon-minus:before {
  content: "\2212";
}
.glyphicon-cloud:before {
  content: "\2601";
}
.glyphicon-envelope:before {
  content: "\2709";
}
.glyphicon-pencil:before {
  content: "\270f";
}
.glyphicon-glass:before {
  content: "\e001";
}
.glyphicon-music:before {
  content: "\e002";
}
.glyphicon-search:before {
  content: "\e003";
}
.glyphicon-heart:before {
  content: "\e005";
}
.glyphicon-star:before {
  content: "\e006";
}
.glyphicon-star-empty:before {
  content: "\e007";
}
.glyphicon-user:before {
  content: "\e008";
}
.glyphicon-film:before {
  content: "\e009";
}
.glyphicon-th-large:before {
  content: "\e010";
}
.glyphicon-th:before {
  content: "\e011";
}
.glyphicon-th-list:before {
  content: "\e012";
}
.glyphicon-ok:before {
  content: "\e013";
}
.glyphicon-remove:before {
  content: "\e014";
}
.glyphicon-zoom-in:before {
  content: "\e015";
}
.glyphicon-zoom-out:before {
  content: "\e016";
}
.glyphicon-off:before {
  content: "\e017";
}
.glyphicon-signal:before {
  content: "\e018";
}
.glyphicon-cog:before {
  content: "\e019";
}
.glyphicon-trash:before {
  content: "\e020";
}
.glyphicon-home:before {
  content: "\e021";
}
.glyphicon-file:before {
  content: "\e022";
}
.glyphicon-time:before {
  content: "\e023";
}
.glyphicon-road:before {
  content: "\e024";
}
.glyphicon-download-alt:before {
  content: "\e025";
}
.glyphicon-download:before {
  content: "\e026";
}
.glyphicon-upload:before {
  content: "\e027";
}
.glyphicon-inbox:before {
  content: "\e028";
}
.glyphicon-play-circle:before {
  content: "\e029";
}
.glyphicon-repeat:before {
  content: "\e030";
}
.glyphicon-refresh:before {
  content: "\e031";
}
.glyphicon-list-alt:before {
  content: "\e032";
}
.glyphicon-lock:before {
  content: "\e033";
}
.glyphicon-flag:before {
  content: "\e034";
}
.glyphicon-headphones:before {
  content: "\e035";
}
.glyphicon-volume-off:before {
  content: "\e036";
}
.glyphicon-volume-down:before {
  content: "\e037";
}
.glyphicon-volume-up:before {
  content: "\e038";
}
.glyphicon-qrcode:before {
  content: "\e039";
}
.glyphicon-barcode:before {
  content: "\e040";
}
.glyphicon-tag:before {
  content: "\e041";
}
.glyphicon-tags:before {
  content: "\e042";
}
.glyphicon-book:before {
  content: "\e043";
}
.glyphicon-bookmark:before {
  content: "\e044";
}
.glyphicon-print:before {
  content: "\e045";
}
.glyphicon-camera:before {
  content: "\e046";
}
.glyphicon-font:before {
  content: "\e047";
}
.glyphicon-bold:before {
  content: "\e048";
}
.glyphicon-italic:before {
  content: "\e049";
}
.glyphicon-text-height:before {
  content: "\e050";
}
.glyphicon-text-width:before {
  content: "\e051";
}
.glyphicon-align-left:before {
  content: "\e052";
}
.glyphicon-align-center:before {
  content: "\e053";
}
.glyphicon-align-right:before {
  content: "\e054";
}
.glyphicon-align-justify:before {
  content: "\e055";
}
.glyphicon-list:before {
  content: "\e056";
}
.glyphicon-indent-left:before {
  content: "\e057";
}
.glyphicon-indent-right:before {
  content: "\e058";
}
.glyphicon-facetime-video:before {
  content: "\e059";
}
.glyphicon-picture:before {
  content: "\e060";
}
.glyphicon-map-marker:before {
  content: "\e062";
}
.glyphicon-adjust:before {
  content: "\e063";
}
.glyphicon-tint:before {
  content: "\e064";
}
.glyphicon-edit:before {
  content: "\e065";
}
.glyphicon-share:before {
  content: "\e066";
}
.glyphicon-check:before {
  content: "\e067";
}
.glyphicon-move:before {
  content: "\e068";
}
.glyphicon-step-backward:before {
  content: "\e069";
}
.glyphicon-fast-backward:before {
  content: "\e070";
}
.glyphicon-backward:before {
  content: "\e071";
}
.glyphicon-play:before {
  content: "\e072";
}
.glyphicon-pause:before {
  content: "\e073";
}
.glyphicon-stop:before {
  content: "\e074";
}
.glyphicon-forward:before {
  content: "\e075";
}
.glyphicon-fast-forward:before {
  content: "\e076";
}
.glyphicon-step-forward:before {
  content: "\e077";
}
.glyphicon-eject:before {
  content: "\e078";
}
.glyphicon-chevron-left:before {
  content: "\e079";
}
.glyphicon-chevron-right:before {
  content: "\e080";
}
.glyphicon-plus-sign:before {
  content: "\e081";
}
.glyphicon-minus-sign:before {
  content: "\e082";
}
.glyphicon-remove-sign:before {
  content: "\e083";
}
.glyphicon-ok-sign:before {
  content: "\e084";
}
.glyphicon-question-sign:before {
  content: "\e085";
}
.glyphicon-info-sign:before {
  content: "\e086";
}
.glyphicon-screenshot:before {
  content: "\e087";
}
.glyphicon-remove-circle:before {
  content: "\e088";
}
.glyphicon-ok-circle:before {
  content: "\e089";
}
.glyphicon-ban-circle:before {
  content: "\e090";
}
.glyphicon-arrow-left:before {
  content: "\e091";
}
.glyphicon-arrow-right:before {
  content: "\e092";
}
.glyphicon-arrow-up:before {
  content: "\e093";
}
.glyphicon-arrow-down:before {
  content: "\e094";
}
.glyphicon-share-alt:before {
  content: "\e095";
}
.glyphicon-resize-full:before {
  content: "\e096";
}
.glyphicon-resize-small:before {
  content: "\e097";
}
.glyphicon-exclamation-sign:before {
  content: "\e101";
}
.glyphicon-gift:before {
  content: "\e102";
}
.glyphicon-leaf:before {
  content: "\e103";
}
.glyphicon-fire:before {
  content: "\e104";
}
.glyphicon-eye-open:before {
  content: "\e105";
}
.glyphicon-eye-close:before {
  content: "\e106";
}
.glyphicon-warning-sign:before {
  content: "\e107";
}
.glyphicon-plane:before {
  content: "\e108";
}
.glyphicon-calendar:before {
  content: "\e109";
}
.glyphicon-random:before {
  content: "\e110";
}
.glyphicon-comment:before {
  content: "\e111";
}
.glyphicon-magnet:before {
  content: "\e112";
}
.glyphicon-chevron-up:before {
  content: "\e113";
}
.glyphicon-chevron-down:before {
  content: "\e114";
}
.glyphicon-retweet:before {
  content: "\e115";
}
.glyphicon-shopping-cart:before {
  content: "\e116";
}
.glyphicon-folder-close:before {
  content: "\e117";
}
.glyphicon-folder-open:before {
  content: "\e118";
}
.glyphicon-resize-vertical:before {
  content: "\e119";
}
.glyphicon-resize-horizontal:before {
  content: "\e120";
}
.glyphicon-hdd:before {
  content: "\e121";
}
.glyphicon-bullhorn:before {
  content: "\e122";
}
.glyphicon-bell:before {
  content: "\e123";
}
.glyphicon-certificate:before {
  content: "\e124";
}
.glyphicon-thumbs-up:before {
  content: "\e125";
}
.glyphicon-thumbs-down:before {
  content: "\e126";
}
.glyphicon-hand-right:before {
  content: "\e127";
}
.glyphicon-hand-left:before {
  content: "\e128";
}
.glyphicon-hand-up:before {
  content: "\e129";
}
.glyphicon-hand-down:before {
  content: "\e130";
}
.glyphicon-circle-arrow-right:before {
  content: "\e131";
}
.glyphicon-circle-arrow-left:before {
  content: "\e132";
}
.glyphicon-circle-arrow-up:before {
  content: "\e133";
}
.glyphicon-circle-arrow-down:before {
  content: "\e134";
}
.glyphicon-globe:before {
  content: "\e135";
}
.glyphicon-wrench:before {
  content: "\e136";
}
.glyphicon-tasks:before {
  content: "\e137";
}
.glyphicon-filter:before {
  content: "\e138";
}
.glyphicon-briefcase:before {
  content: "\e139";
}
.glyphicon-fullscreen:before {
  content: "\e140";
}
.glyphicon-dashboard:before {
  content: "\e141";
}
.glyphicon-paperclip:before {
  content: "\e142";
}
.glyphicon-heart-empty:before {
  content: "\e143";
}
.glyphicon-link:before {
  content: "\e144";
}
.glyphicon-phone:before {
  content: "\e145";
}
.glyphicon-pushpin:before {
  content: "\e146";
}
.glyphicon-usd:before {
  content: "\e148";
}
.glyphicon-gbp:before {
  content: "\e149";
}
.glyphicon-sort:before {
  content: "\e150";
}
.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}
.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}
.glyphicon-sort-by-order:before {
  content: "\e153";
}
.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}
.glyphicon-sort-by-attributes:before {
  content: "\e155";
}
.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}
.glyphicon-unchecked:before {
  content: "\e157";
}
.glyphicon-expand:before {
  content: "\e158";
}
.glyphicon-collapse-down:before {
  content: "\e159";
}
.glyphicon-collapse-up:before {
  content: "\e160";
}
.glyphicon-log-in:before {
  content: "\e161";
}
.glyphicon-flash:before {
  content: "\e162";
}
.glyphicon-log-out:before {
  content: "\e163";
}
.glyphicon-new-window:before {
  content: "\e164";
}
.glyphicon-record:before {
  content: "\e165";
}
.glyphicon-save:before {
  content: "\e166";
}
.glyphicon-open:before {
  content: "\e167";
}
.glyphicon-saved:before {
  content: "\e168";
}
.glyphicon-import:before {
  content: "\e169";
}
.glyphicon-export:before {
  content: "\e170";
}
.glyphicon-send:before {
  content: "\e171";
}
.glyphicon-floppy-disk:before {
  content: "\e172";
}
.glyphicon-floppy-saved:before {
  content: "\e173";
}
.glyphicon-floppy-remove:before {
  content: "\e174";
}
.glyphicon-floppy-save:before {
  content: "\e175";
}
.glyphicon-floppy-open:before {
  content: "\e176";
}
.glyphicon-credit-card:before {
  content: "\e177";
}
.glyphicon-transfer:before {
  content: "\e178";
}
.glyphicon-cutlery:before {
  content: "\e179";
}
.glyphicon-header:before {
  content: "\e180";
}
.glyphicon-compressed:before {
  content: "\e181";
}
.glyphicon-earphone:before {
  content: "\e182";
}
.glyphicon-phone-alt:before {
  content: "\e183";
}
.glyphicon-tower:before {
  content: "\e184";
}
.glyphicon-stats:before {
  content: "\e185";
}
.glyphicon-sd-video:before {
  content: "\e186";
}
.glyphicon-hd-video:before {
  content: "\e187";
}
.glyphicon-subtitles:before {
  content: "\e188";
}
.glyphicon-sound-stereo:before {
  content: "\e189";
}
.glyphicon-sound-dolby:before {
  content: "\e190";
}
.glyphicon-sound-5-1:before {
  content: "\e191";
}
.glyphicon-sound-6-1:before {
  content: "\e192";
}
.glyphicon-sound-7-1:before {
  content: "\e193";
}
.glyphicon-copyright-mark:before {
  content: "\e194";
}
.glyphicon-registration-mark:before {
  content: "\e195";
}
.glyphicon-cloud-download:before {
  content: "\e197";
}
.glyphicon-cloud-upload:before {
  content: "\e198";
}
.glyphicon-tree-conifer:before {
  content: "\e199";
}
.glyphicon-tree-deciduous:before {
  content: "\e200";
}
.glyphicon-cd:before {
  content: "\e201";
}
.glyphicon-save-file:before {
  content: "\e202";
}
.glyphicon-open-file:before {
  content: "\e203";
}
.glyphicon-level-up:before {
  content: "\e204";
}
.glyphicon-copy:before {
  content: "\e205";
}
.glyphicon-paste:before {
  content: "\e206";
}
.glyphicon-alert:before {
  content: "\e209";
}
.glyphicon-equalizer:before {
  content: "\e210";
}
.glyphicon-king:before {
  content: "\e211";
}
.glyphicon-queen:before {
  content: "\e212";
}
.glyphicon-pawn:before {
  content: "\e213";
}
.glyphicon-bishop:before {
  content: "\e214";
}
.glyphicon-knight:before {
  content: "\e215";
}
.glyphicon-baby-formula:before {
  content: "\e216";
}
.glyphicon-tent:before {
  content: "\26fa";
}
.glyphicon-blackboard:before {
  content: "\e218";
}
.glyphicon-bed:before {
  content: "\e219";
}
.glyphicon-apple:before {
  content: "\f8ff";
}
.glyphicon-erase:before {
  content: "\e221";
}
.glyphicon-hourglass:before {
  content: "\231b";
}
.glyphicon-lamp:before {
  content: "\e223";
}
.glyphicon-duplicate:before {
  content: "\e224";
}
.glyphicon-piggy-bank:before {
  content: "\e225";
}
.glyphicon-scissors:before {
  content: "\e226";
}
.glyphicon-bitcoin:before {
  content: "\e227";
}
.glyphicon-btc:before {
  content: "\e227";
}
.glyphicon-xbt:before {
  content: "\e227";
}
.glyphicon-yen:before {
  content: "\00a5";
}
.glyphicon-jpy:before {
  content: "\00a5";
}
.glyphicon-ruble:before {
  content: "\20bd";
}
.glyphicon-rub:before {
  content: "\20bd";
}
.glyphicon-scale:before {
  content: "\e230";
}
.glyphicon-ice-lolly:before {
  content: "\e231";
}
.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}
.glyphicon-education:before {
  content: "\e233";
}
.glyphicon-option-horizontal:before {
  content: "\e234";
}
.glyphicon-option-vertical:before {
  content: "\e235";
}
.glyphicon-menu-hamburger:before {
  content: "\e236";
}
.glyphicon-modal-window:before {
  content: "\e237";
}
.glyphicon-oil:before {
  content: "\e238";
}
.glyphicon-grain:before {
  content: "\e239";
}
.glyphicon-sunglasses:before {
  content: "\e240";
}
.glyphicon-text-size:before {
  content: "\e241";
}
.glyphicon-text-color:before {
  content: "\e242";
}
.glyphicon-text-background:before {
  content: "\e243";
}
.glyphicon-object-align-top:before {
  content: "\e244";
}
.glyphicon-object-align-bottom:before {
  content: "\e245";
}
.glyphicon-object-align-horizontal:before {
  content: "\e246";
}
.glyphicon-object-align-left:before {
  content: "\e247";
}
.glyphicon-object-align-vertical:before {
  content: "\e248";
}
.glyphicon-object-align-right:before {
  content: "\e249";
}
.glyphicon-triangle-right:before {
  content: "\e250";
}
.glyphicon-triangle-left:before {
  content: "\e251";
}
.glyphicon-triangle-bottom:before {
  content: "\e252";
}
.glyphicon-triangle-top:before {
  content: "\e253";
}
.glyphicon-console:before {
  content: "\e254";
}
.glyphicon-superscript:before {
  content: "\e255";
}
.glyphicon-subscript:before {
  content: "\e256";
}
.glyphicon-menu-left:before {
  content: "\e257";
}
.glyphicon-menu-right:before {
  content: "\e258";
}
.glyphicon-menu-down:before {
  content: "\e259";
}
.glyphicon-menu-up:before {
  content: "\e260";
}
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 10px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 1.42857143;
  color: #000;
  background-color: #fff;
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #337ab7;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #23527c;
  text-decoration: underline;
}
a:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
figure {
  margin: 0;
}
img {
  vertical-align: middle;
}
.img-responsive,
.thumbnail > img,
.thumbnail a > img,
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
}
.img-rounded {
  border-radius: 3px;
}
.img-thumbnail {
  padding: 4px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}
.img-circle {
  border-radius: 50%;
}
hr {
  margin-top: 18px;
  margin-bottom: 18px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
[role="button"] {
  cursor: pointer;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #777777;
}
h1,
.h1,
h2,
.h2,
h3,
.h3 {
  margin-top: 18px;
  margin-bottom: 9px;
}
h1 small,
.h1 small,
h2 small,
.h2 small,
h3 small,
.h3 small,
h1 .small,
.h1 .small,
h2 .small,
.h2 .small,
h3 .small,
.h3 .small {
  font-size: 65%;
}
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  margin-top: 9px;
  margin-bottom: 9px;
}
h4 small,
.h4 small,
h5 small,
.h5 small,
h6 small,
.h6 small,
h4 .small,
.h4 .small,
h5 .small,
.h5 .small,
h6 .small,
.h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 33px;
}
h2,
.h2 {
  font-size: 27px;
}
h3,
.h3 {
  font-size: 23px;
}
h4,
.h4 {
  font-size: 17px;
}
h5,
.h5 {
  font-size: 13px;
}
h6,
.h6 {
  font-size: 12px;
}
p {
  margin: 0 0 9px;
}
.lead {
  margin-bottom: 18px;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 19.5px;
  }
}
small,
.small {
  font-size: 92%;
}
mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.text-justify {
  text-align: justify;
}
.text-nowrap {
  white-space: nowrap;
}
.text-lowercase {
  text-transform: lowercase;
}
.text-uppercase {
  text-transform: uppercase;
}
.text-capitalize {
  text-transform: capitalize;
}
.text-muted {
  color: #777777;
}
.text-primary {
  color: #337ab7;
}
a.text-primary:hover,
a.text-primary:focus {
  color: #286090;
}
.text-success {
  color: #3c763d;
}
a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}
.text-info {
  color: #31708f;
}
a.text-info:hover,
a.text-info:focus {
  color: #245269;
}
.text-warning {
  color: #8a6d3b;
}
a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}
.text-danger {
  color: #a94442;
}
a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}
.bg-primary {
  color: #fff;
  background-color: #337ab7;
}
a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #286090;
}
.bg-success {
  background-color: #dff0d8;
}
a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}
.bg-info {
  background-color: #d9edf7;
}
a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}
.bg-warning {
  background-color: #fcf8e3;
}
a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}
.bg-danger {
  background-color: #f2dede;
}
a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}
.page-header {
  padding-bottom: 8px;
  margin: 36px 0 18px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 9px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
dl {
  margin-top: 0;
  margin-bottom: 18px;
}
dt,
dd {
  line-height: 1.42857143;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 541px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #777777;
}
.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 9px 18px;
  margin: 0 0 18px;
  font-size: inherit;
  border-left: 5px solid #eeeeee;
}
blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}
blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.42857143;
  color: #777777;
}
blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}
.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
  text-align: right;
}
.blockquote-reverse footer:before,
blockquote.pull-right footer:before,
.blockquote-reverse small:before,
blockquote.pull-right small:before,
.blockquote-reverse .small:before,
blockquote.pull-right .small:before {
  content: '';
}
.blockquote-reverse footer:after,
blockquote.pull-right footer:after,
.blockquote-reverse small:after,
blockquote.pull-right small:after,
.blockquote-reverse .small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
address {
  margin-bottom: 18px;
  font-style: normal;
  line-height: 1.42857143;
}
code,
kbd,
pre,
samp {
  font-family: monospace;
}
code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 2px;
}
kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #888;
  background-color: transparent;
  border-radius: 1px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}
kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}
pre {
  display: block;
  padding: 8.5px;
  margin: 0 0 9px;
  font-size: 12px;
  line-height: 1.42857143;
  word-break: break-all;
  word-wrap: break-word;
  color: #333333;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border-radius: 2px;
}
pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}
.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
@media (min-width: 768px) {
  .container {
    width: 768px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 940px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1140px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
.row {
  margin-left: 0px;
  margin-right: 0px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 0px;
  padding-right: 0px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 18px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #ddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #ddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #ddd;
}
.table .table {
  background-color: #fff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 13.5px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #ddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 18px;
  font-size: 19.5px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
}
.form-control {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.form-control::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.form-control:-ms-input-placeholder {
  color: #999;
}
.form-control::-webkit-input-placeholder {
  color: #999;
}
.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}
.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 32px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 45px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 18px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 31px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 30px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-lg {
  height: 45px;
  line-height: 45px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.form-group-lg select.form-control {
  height: 45px;
  line-height: 45px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 45px;
  min-height: 35px;
  padding: 11px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 40px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 32px;
  height: 32px;
  line-height: 32px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 45px;
  height: 45px;
  line-height: 45px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}
.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #3c763d;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 23px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #404040;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 25px;
}
.form-horizontal .form-group {
  margin-left: 0px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 17px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  border-radius: 2px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.btn:focus,
.btn:active:focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn.active.focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
.btn:hover,
.btn:focus,
.btn.focus {
  color: #333;
  text-decoration: none;
}
.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}
a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}
.btn-default {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.btn-default:focus,
.btn-default.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.btn-default:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus {
  background-color: #fff;
  border-color: #ccc;
}
.btn-default .badge {
  color: #fff;
  background-color: #333;
}
.btn-primary {
  color: #fff;
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary:focus,
.btn-primary.focus {
  color: #fff;
  background-color: #286090;
  border-color: #122b40;
}
.btn-primary:hover {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active:hover,
.btn-primary.active:hover,
.open > .dropdown-toggle.btn-primary:hover,
.btn-primary:active:focus,
.btn-primary.active:focus,
.open > .dropdown-toggle.btn-primary:focus,
.btn-primary:active.focus,
.btn-primary.active.focus,
.open > .dropdown-toggle.btn-primary.focus {
  color: #fff;
  background-color: #204d74;
  border-color: #122b40;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary .badge {
  color: #337ab7;
  background-color: #fff;
}
.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success:focus,
.btn-success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.btn-success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active:hover,
.btn-success.active:hover,
.open > .dropdown-toggle.btn-success:hover,
.btn-success:active:focus,
.btn-success.active:focus,
.open > .dropdown-toggle.btn-success:focus,
.btn-success:active.focus,
.btn-success.active.focus,
.open > .dropdown-toggle.btn-success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  background-image: none;
}
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info:focus,
.btn-info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.btn-info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active:hover,
.btn-info.active:hover,
.open > .dropdown-toggle.btn-info:hover,
.btn-info:active:focus,
.btn-info.active:focus,
.open > .dropdown-toggle.btn-info:focus,
.btn-info:active.focus,
.btn-info.active.focus,
.open > .dropdown-toggle.btn-info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  background-image: none;
}
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.btn-warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning:focus,
.btn-warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.btn-warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active:hover,
.btn-warning.active:hover,
.open > .dropdown-toggle.btn-warning:hover,
.btn-warning:active:focus,
.btn-warning.active:focus,
.open > .dropdown-toggle.btn-warning:focus,
.btn-warning:active.focus,
.btn-warning.active.focus,
.open > .dropdown-toggle.btn-warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  background-image: none;
}
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger:focus,
.btn-danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.btn-danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active:hover,
.btn-danger.active:hover,
.open > .dropdown-toggle.btn-danger:hover,
.btn-danger:active:focus,
.btn-danger.active:focus,
.open > .dropdown-toggle.btn-danger:focus,
.btn-danger:active.focus,
.btn-danger.active.focus,
.open > .dropdown-toggle.btn-danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  background-image: none;
}
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger .badge {
  color: #d9534f;
  background-color: #fff;
}
.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0;
}
.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}
.btn-link:hover,
.btn-link:focus {
  color: #23527c;
  text-decoration: underline;
  background-color: transparent;
}
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:focus {
  color: #777777;
  text-decoration: none;
}
.btn-lg,
.btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.btn-sm,
.btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-xs,
.btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-block {
  display: block;
  width: 100%;
}
.btn-block + .btn-block {
  margin-top: 5px;
}
input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 13px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 2px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #fff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 541px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}
.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}
.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover,
.btn-group > .btn:focus,
.btn-group-vertical > .btn:focus,
.btn-group > .btn:active,
.btn-group-vertical > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}
.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}
.btn-toolbar {
  margin-left: -5px;
}
.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}
.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}
.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}
.btn-group > .btn:first-child {
  margin-left: 0;
}
.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group > .btn-group {
  float: left;
}
.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}
.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}
.btn-group > .btn-lg + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn .caret {
  margin-left: 0;
}
.btn-lg .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}
.dropup .btn-lg .caret {
  border-width: 0 5px 5px;
}
.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}
.btn-group-vertical > .btn-group > .btn {
  float: none;
}
.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}
.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}
.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}
.btn-group-justified > .btn-group .btn {
  width: 100%;
}
.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}
[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}
.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}
.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}
.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}
.input-group .form-control:focus {
  z-index: 3;
}
.input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-group-lg > .form-control,
select.input-group-lg > .input-group-addon,
select.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  line-height: 45px;
}
textarea.input-group-lg > .form-control,
textarea.input-group-lg > .input-group-addon,
textarea.input-group-lg > .input-group-btn > .btn,
select[multiple].input-group-lg > .form-control,
select[multiple].input-group-lg > .input-group-addon,
select[multiple].input-group-lg > .input-group-btn > .btn {
  height: auto;
}
.input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-group-sm > .form-control,
select.input-group-sm > .input-group-addon,
select.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  line-height: 30px;
}
textarea.input-group-sm > .form-control,
textarea.input-group-sm > .input-group-addon,
textarea.input-group-sm > .input-group-btn > .btn,
select[multiple].input-group-sm > .form-control,
select[multiple].input-group-sm > .input-group-addon,
select[multiple].input-group-sm > .input-group-btn > .btn {
  height: auto;
}
.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}
.input-group-addon {
  padding: 6px 12px;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  border-radius: 2px;
}
.input-group-addon.input-sm {
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 1px;
}
.input-group-addon.input-lg {
  padding: 10px 16px;
  font-size: 17px;
  border-radius: 3px;
}
.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}
.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.input-group-addon:first-child {
  border-right: 0;
}
.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.input-group-addon:last-child {
  border-left: 0;
}
.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}
.input-group-btn > .btn {
  position: relative;
}
.input-group-btn > .btn + .btn {
  margin-left: -1px;
}
.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #ddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 2px 2px 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #ddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #fff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 2px;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #fff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 30px;
  margin-bottom: 18px;
  border: 1px solid transparent;
}
@media (min-width: 541px) {
  .navbar {
    border-radius: 2px;
  }
}
@media (min-width: 541px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 0px;
  padding-left: 0px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 541px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 540px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: 0px;
  margin-left: 0px;
}
@media (min-width: 541px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 541px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 541px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 6px 0px;
  font-size: 17px;
  line-height: 18px;
  height: 30px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 541px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: 0px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 0px;
  padding: 9px 10px;
  margin-top: -2px;
  margin-bottom: -2px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 2px;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 541px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 3px 0px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 18px;
}
@media (max-width: 540px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 18px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 541px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 6px;
    padding-bottom: 6px;
  }
}
.navbar-form {
  margin-left: 0px;
  margin-right: 0px;
  padding: 10px 0px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -1px;
  margin-bottom: -1px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 540px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 541px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: -1px;
  margin-bottom: -1px;
}
.navbar-btn.btn-sm {
  margin-top: 0px;
  margin-bottom: 0px;
}
.navbar-btn.btn-xs {
  margin-top: 4px;
  margin-bottom: 4px;
}
.navbar-text {
  margin-top: 6px;
  margin-bottom: 6px;
}
@media (min-width: 541px) {
  .navbar-text {
    float: left;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 541px) {
  .navbar-left {
    float: left !important;
    float: left;
  }
  .navbar-right {
    float: right !important;
    float: right;
    margin-right: 0px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777;
}
.navbar-default .navbar-nav > li > a {
  color: #777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #ddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #ddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555;
}
@media (max-width: 540px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #ccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777;
}
.navbar-default .navbar-link:hover {
  color: #333;
}
.navbar-default .btn-link {
  color: #777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #ccc;
}
.navbar-inverse {
  background-color: #222;
  border-color: #080808;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #fff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #fff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #fff;
}
@media (max-width: 540px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #fff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #fff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #fff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #fff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444;
}
.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 18px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 2px;
}
.breadcrumb > li {
  display: inline-block;
}
.breadcrumb > li + li:before {
  content: "/\00a0";
  padding: 0 5px;
  color: #5e5e5e;
}
.breadcrumb > .active {
  color: #777777;
}
.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 18px 0;
  border-radius: 2px;
}
.pagination > li {
  display: inline;
}
.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 6px 12px;
  line-height: 1.42857143;
  text-decoration: none;
  color: #337ab7;
  background-color: #fff;
  border: 1px solid #ddd;
  margin-left: -1px;
}
.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 2px;
  border-top-right-radius: 2px;
}
.pagination > li > a:hover,
.pagination > li > span:hover,
.pagination > li > a:focus,
.pagination > li > span:focus {
  z-index: 2;
  color: #23527c;
  background-color: #eeeeee;
  border-color: #ddd;
}
.pagination > .active > a,
.pagination > .active > span,
.pagination > .active > a:hover,
.pagination > .active > span:hover,
.pagination > .active > a:focus,
.pagination > .active > span:focus {
  z-index: 3;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
  cursor: default;
}
.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: #777777;
  background-color: #fff;
  border-color: #ddd;
  cursor: not-allowed;
}
.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}
.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}
.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 1px;
  border-top-left-radius: 1px;
}
.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 1px;
  border-top-right-radius: 1px;
}
.pager {
  padding-left: 0;
  margin: 18px 0;
  list-style: none;
  text-align: center;
}
.pager li {
  display: inline;
}
.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 15px;
}
.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.pager .next > a,
.pager .next > span {
  float: right;
}
.pager .previous > a,
.pager .previous > span {
  float: left;
}
.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #777777;
  background-color: #fff;
  cursor: not-allowed;
}
.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}
a.label:hover,
a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.label:empty {
  display: none;
}
.btn .label {
  position: relative;
  top: -1px;
}
.label-default {
  background-color: #777777;
}
.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #5e5e5e;
}
.label-primary {
  background-color: #337ab7;
}
.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #286090;
}
.label-success {
  background-color: #5cb85c;
}
.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}
.label-info {
  background-color: #5bc0de;
}
.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}
.label-warning {
  background-color: #f0ad4e;
}
.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #ec971f;
}
.label-danger {
  background-color: #d9534f;
}
.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}
.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px;
}
.badge:empty {
  display: none;
}
.btn .badge {
  position: relative;
  top: -1px;
}
.btn-xs .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}
a.badge:hover,
a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #337ab7;
  background-color: #fff;
}
.list-group-item > .badge {
  float: right;
}
.list-group-item > .badge + .badge {
  margin-right: 5px;
}
.nav-pills > li > a > .badge {
  margin-left: 3px;
}
.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee;
}
.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}
.jumbotron p {
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 200;
}
.jumbotron > hr {
  border-top-color: #d5d5d5;
}
.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 3px;
  padding-left: 0px;
  padding-right: 0px;
}
.jumbotron .container {
  max-width: 100%;
}
@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 59px;
  }
}
.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 18px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}
.thumbnail > img,
.thumbnail a > img {
  margin-left: auto;
  margin-right: auto;
}
a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7;
}
.thumbnail .caption {
  padding: 9px;
  color: #000;
}
.alert {
  padding: 15px;
  margin-bottom: 18px;
  border: 1px solid transparent;
  border-radius: 2px;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
.progress {
  overflow: hidden;
  height: 18px;
  margin-bottom: 18px;
  background-color: #f5f5f5;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}
.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 18px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}
.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}
.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar-success {
  background-color: #5cb85c;
}
.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-info {
  background-color: #5bc0de;
}
.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-warning {
  background-color: #f0ad4e;
}
.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-danger {
  background-color: #d9534f;
}
.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.media {
  margin-top: 15px;
}
.media:first-child {
  margin-top: 0;
}
.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}
.media-body {
  width: 10000px;
}
.media-object {
  display: block;
}
.media-object.img-thumbnail {
  max-width: none;
}
.media-right,
.media > .pull-right {
  padding-left: 10px;
}
.media-left,
.media > .pull-left {
  padding-right: 10px;
}
.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}
.media-middle {
  vertical-align: middle;
}
.media-bottom {
  vertical-align: bottom;
}
.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.media-list {
  padding-left: 0;
  list-style: none;
}
.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}
.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd;
}
.list-group-item:first-child {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
}
.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
a.list-group-item,
button.list-group-item {
  color: #555;
}
a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333;
}
a.list-group-item:hover,
button.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:focus {
  text-decoration: none;
  color: #555;
  background-color: #f5f5f5;
}
button.list-group-item {
  width: 100%;
  text-align: left;
}
.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed;
}
.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}
.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: #777777;
}
.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.list-group-item.active .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}
.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #c7ddef;
}
.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}
a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}
a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}
a.list-group-item-success:hover,
button.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}
a.list-group-item-success.active,
button.list-group-item-success.active,
a.list-group-item-success.active:hover,
button.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}
.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}
a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}
a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}
a.list-group-item-info:hover,
button.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}
a.list-group-item-info.active,
button.list-group-item-info.active,
a.list-group-item-info.active:hover,
button.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}
.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}
a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}
a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}
a.list-group-item-warning:hover,
button.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}
a.list-group-item-warning.active,
button.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}
.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}
a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}
a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}
a.list-group-item-danger:hover,
button.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}
a.list-group-item-danger.active,
button.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}
.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}
.panel {
  margin-bottom: 18px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}
.panel-body {
  padding: 15px;
}
.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}
.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 15px;
  color: inherit;
}
.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}
.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}
.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}
.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}
.list-group + .panel-footer {
  border-top-width: 0;
}
.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}
.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}
.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: 1px;
  border-top-right-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: 1px;
}
.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: 1px;
  border-bottom-right-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: 1px;
}
.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd;
}
.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}
.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}
.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}
.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}
.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}
.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}
.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}
.panel-group {
  margin-bottom: 18px;
}
.panel-group .panel {
  margin-bottom: 0;
  border-radius: 2px;
}
.panel-group .panel + .panel {
  margin-top: 5px;
}
.panel-group .panel-heading {
  border-bottom: 0;
}
.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #ddd;
}
.panel-group .panel-footer {
  border-top: 0;
}
.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #ddd;
}
.panel-default {
  border-color: #ddd;
}
.panel-default > .panel-heading {
  color: #333333;
  background-color: #f5f5f5;
  border-color: #ddd;
}
.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ddd;
}
.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: #333333;
}
.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ddd;
}
.panel-primary {
  border-color: #337ab7;
}
.panel-primary > .panel-heading {
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #337ab7;
}
.panel-primary > .panel-heading .badge {
  color: #337ab7;
  background-color: #fff;
}
.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #337ab7;
}
.panel-success {
  border-color: #d6e9c6;
}
.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}
.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}
.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}
.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}
.panel-info {
  border-color: #bce8f1;
}
.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}
.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}
.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}
.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}
.panel-warning {
  border-color: #faebcc;
}
.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}
.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}
.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}
.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}
.panel-danger {
  border-color: #ebccd1;
}
.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}
.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}
.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}
.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}
.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}
.well-lg {
  padding: 24px;
  border-radius: 3px;
}
.well-sm {
  padding: 9px;
  border-radius: 1px;
}
.close {
  float: right;
  font-size: 19.5px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000;
}
.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0);
}
.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 2px;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 13px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 13px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 2px 2px 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #fff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #fff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #fff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #fff;
  bottom: -10px;
}
.carousel {
  position: relative;
}
.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}
.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  line-height: 1;
}
@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}
.carousel-inner > .active {
  left: 0;
}
.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}
.carousel-inner > .next {
  left: 100%;
}
.carousel-inner > .prev {
  left: -100%;
}
.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}
.carousel-inner > .active.left {
  left: -100%;
}
.carousel-inner > .active.right {
  left: 100%;
}
.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: rgba(0, 0, 0, 0);
}
.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}
.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}
.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #fff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}
.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}
.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}
.carousel-control .icon-prev:before {
  content: '\2039';
}
.carousel-control .icon-next:before {
  content: '\203a';
}
.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}
.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: rgba(0, 0, 0, 0);
}
.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
}
.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}
.carousel-caption .btn {
  text-shadow: none;
}
@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}
.clearfix:before,
.clearfix:after,
.dl-horizontal dd:before,
.dl-horizontal dd:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.btn-toolbar:before,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.pager:before,
.pager:after,
.panel-body:before,
.panel-body:after,
.modal-header:before,
.modal-header:after,
.modal-footer:before,
.modal-footer:after,
.item_buttons:before,
.item_buttons:after {
  content: " ";
  display: table;
}
.clearfix:after,
.dl-horizontal dd:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.pager:after,
.panel-body:after,
.modal-header:after,
.modal-footer:after,
.item_buttons:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/*!
*
* Font Awesome
*
*/
/*!
 *  Font Awesome 4.2.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.2.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.2.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.2.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.2.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.2.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}
.fa-2x {
  font-size: 2em;
}
.fa-3x {
  font-size: 3em;
}
.fa-4x {
  font-size: 4em;
}
.fa-5x {
  font-size: 5em;
}
.fa-fw {
  width: 1.28571429em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.85714286em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eee;
  border-radius: .1em;
}
.pull-right {
  float: right;
}
.pull-left {
  float: left;
}
.fa.pull-left {
  margin-right: .3em;
}
.fa.pull-right {
  margin-left: .3em;
}
.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}
@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=1);
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2);
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=3);
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1);
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1);
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}
.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}
.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}
.fa-stack-1x {
  line-height: inherit;
}
.fa-stack-2x {
  font-size: 2em;
}
.fa-inverse {
  color: #fff;
}
/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}
.fa-music:before {
  content: "\f001";
}
.fa-search:before {
  content: "\f002";
}
.fa-envelope-o:before {
  content: "\f003";
}
.fa-heart:before {
  content: "\f004";
}
.fa-star:before {
  content: "\f005";
}
.fa-star-o:before {
  content: "\f006";
}
.fa-user:before {
  content: "\f007";
}
.fa-film:before {
  content: "\f008";
}
.fa-th-large:before {
  content: "\f009";
}
.fa-th:before {
  content: "\f00a";
}
.fa-th-list:before {
  content: "\f00b";
}
.fa-check:before {
  content: "\f00c";
}
.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}
.fa-search-plus:before {
  content: "\f00e";
}
.fa-search-minus:before {
  content: "\f010";
}
.fa-power-off:before {
  content: "\f011";
}
.fa-signal:before {
  content: "\f012";
}
.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}
.fa-trash-o:before {
  content: "\f014";
}
.fa-home:before {
  content: "\f015";
}
.fa-file-o:before {
  content: "\f016";
}
.fa-clock-o:before {
  content: "\f017";
}
.fa-road:before {
  content: "\f018";
}
.fa-download:before {
  content: "\f019";
}
.fa-arrow-circle-o-down:before {
  content: "\f01a";
}
.fa-arrow-circle-o-up:before {
  content: "\f01b";
}
.fa-inbox:before {
  content: "\f01c";
}
.fa-play-circle-o:before {
  content: "\f01d";
}
.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}
.fa-refresh:before {
  content: "\f021";
}
.fa-list-alt:before {
  content: "\f022";
}
.fa-lock:before {
  content: "\f023";
}
.fa-flag:before {
  content: "\f024";
}
.fa-headphones:before {
  content: "\f025";
}
.fa-volume-off:before {
  content: "\f026";
}
.fa-volume-down:before {
  content: "\f027";
}
.fa-volume-up:before {
  content: "\f028";
}
.fa-qrcode:before {
  content: "\f029";
}
.fa-barcode:before {
  content: "\f02a";
}
.fa-tag:before {
  content: "\f02b";
}
.fa-tags:before {
  content: "\f02c";
}
.fa-book:before {
  content: "\f02d";
}
.fa-bookmark:before {
  content: "\f02e";
}
.fa-print:before {
  content: "\f02f";
}
.fa-camera:before {
  content: "\f030";
}
.fa-font:before {
  content: "\f031";
}
.fa-bold:before {
  content: "\f032";
}
.fa-italic:before {
  content: "\f033";
}
.fa-text-height:before {
  content: "\f034";
}
.fa-text-width:before {
  content: "\f035";
}
.fa-align-left:before {
  content: "\f036";
}
.fa-align-center:before {
  content: "\f037";
}
.fa-align-right:before {
  content: "\f038";
}
.fa-align-justify:before {
  content: "\f039";
}
.fa-list:before {
  content: "\f03a";
}
.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}
.fa-indent:before {
  content: "\f03c";
}
.fa-video-camera:before {
  content: "\f03d";
}
.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}
.fa-pencil:before {
  content: "\f040";
}
.fa-map-marker:before {
  content: "\f041";
}
.fa-adjust:before {
  content: "\f042";
}
.fa-tint:before {
  content: "\f043";
}
.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}
.fa-share-square-o:before {
  content: "\f045";
}
.fa-check-square-o:before {
  content: "\f046";
}
.fa-arrows:before {
  content: "\f047";
}
.fa-step-backward:before {
  content: "\f048";
}
.fa-fast-backward:before {
  content: "\f049";
}
.fa-backward:before {
  content: "\f04a";
}
.fa-play:before {
  content: "\f04b";
}
.fa-pause:before {
  content: "\f04c";
}
.fa-stop:before {
  content: "\f04d";
}
.fa-forward:before {
  content: "\f04e";
}
.fa-fast-forward:before {
  content: "\f050";
}
.fa-step-forward:before {
  content: "\f051";
}
.fa-eject:before {
  content: "\f052";
}
.fa-chevron-left:before {
  content: "\f053";
}
.fa-chevron-right:before {
  content: "\f054";
}
.fa-plus-circle:before {
  content: "\f055";
}
.fa-minus-circle:before {
  content: "\f056";
}
.fa-times-circle:before {
  content: "\f057";
}
.fa-check-circle:before {
  content: "\f058";
}
.fa-question-circle:before {
  content: "\f059";
}
.fa-info-circle:before {
  content: "\f05a";
}
.fa-crosshairs:before {
  content: "\f05b";
}
.fa-times-circle-o:before {
  content: "\f05c";
}
.fa-check-circle-o:before {
  content: "\f05d";
}
.fa-ban:before {
  content: "\f05e";
}
.fa-arrow-left:before {
  content: "\f060";
}
.fa-arrow-right:before {
  content: "\f061";
}
.fa-arrow-up:before {
  content: "\f062";
}
.fa-arrow-down:before {
  content: "\f063";
}
.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}
.fa-expand:before {
  content: "\f065";
}
.fa-compress:before {
  content: "\f066";
}
.fa-plus:before {
  content: "\f067";
}
.fa-minus:before {
  content: "\f068";
}
.fa-asterisk:before {
  content: "\f069";
}
.fa-exclamation-circle:before {
  content: "\f06a";
}
.fa-gift:before {
  content: "\f06b";
}
.fa-leaf:before {
  content: "\f06c";
}
.fa-fire:before {
  content: "\f06d";
}
.fa-eye:before {
  content: "\f06e";
}
.fa-eye-slash:before {
  content: "\f070";
}
.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}
.fa-plane:before {
  content: "\f072";
}
.fa-calendar:before {
  content: "\f073";
}
.fa-random:before {
  content: "\f074";
}
.fa-comment:before {
  content: "\f075";
}
.fa-magnet:before {
  content: "\f076";
}
.fa-chevron-up:before {
  content: "\f077";
}
.fa-chevron-down:before {
  content: "\f078";
}
.fa-retweet:before {
  content: "\f079";
}
.fa-shopping-cart:before {
  content: "\f07a";
}
.fa-folder:before {
  content: "\f07b";
}
.fa-folder-open:before {
  content: "\f07c";
}
.fa-arrows-v:before {
  content: "\f07d";
}
.fa-arrows-h:before {
  content: "\f07e";
}
.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}
.fa-twitter-square:before {
  content: "\f081";
}
.fa-facebook-square:before {
  content: "\f082";
}
.fa-camera-retro:before {
  content: "\f083";
}
.fa-key:before {
  content: "\f084";
}
.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}
.fa-comments:before {
  content: "\f086";
}
.fa-thumbs-o-up:before {
  content: "\f087";
}
.fa-thumbs-o-down:before {
  content: "\f088";
}
.fa-star-half:before {
  content: "\f089";
}
.fa-heart-o:before {
  content: "\f08a";
}
.fa-sign-out:before {
  content: "\f08b";
}
.fa-linkedin-square:before {
  content: "\f08c";
}
.fa-thumb-tack:before {
  content: "\f08d";
}
.fa-external-link:before {
  content: "\f08e";
}
.fa-sign-in:before {
  content: "\f090";
}
.fa-trophy:before {
  content: "\f091";
}
.fa-github-square:before {
  content: "\f092";
}
.fa-upload:before {
  content: "\f093";
}
.fa-lemon-o:before {
  content: "\f094";
}
.fa-phone:before {
  content: "\f095";
}
.fa-square-o:before {
  content: "\f096";
}
.fa-bookmark-o:before {
  content: "\f097";
}
.fa-phone-square:before {
  content: "\f098";
}
.fa-twitter:before {
  content: "\f099";
}
.fa-facebook:before {
  content: "\f09a";
}
.fa-github:before {
  content: "\f09b";
}
.fa-unlock:before {
  content: "\f09c";
}
.fa-credit-card:before {
  content: "\f09d";
}
.fa-rss:before {
  content: "\f09e";
}
.fa-hdd-o:before {
  content: "\f0a0";
}
.fa-bullhorn:before {
  content: "\f0a1";
}
.fa-bell:before {
  content: "\f0f3";
}
.fa-certificate:before {
  content: "\f0a3";
}
.fa-hand-o-right:before {
  content: "\f0a4";
}
.fa-hand-o-left:before {
  content: "\f0a5";
}
.fa-hand-o-up:before {
  content: "\f0a6";
}
.fa-hand-o-down:before {
  content: "\f0a7";
}
.fa-arrow-circle-left:before {
  content: "\f0a8";
}
.fa-arrow-circle-right:before {
  content: "\f0a9";
}
.fa-arrow-circle-up:before {
  content: "\f0aa";
}
.fa-arrow-circle-down:before {
  content: "\f0ab";
}
.fa-globe:before {
  content: "\f0ac";
}
.fa-wrench:before {
  content: "\f0ad";
}
.fa-tasks:before {
  content: "\f0ae";
}
.fa-filter:before {
  content: "\f0b0";
}
.fa-briefcase:before {
  content: "\f0b1";
}
.fa-arrows-alt:before {
  content: "\f0b2";
}
.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}
.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}
.fa-cloud:before {
  content: "\f0c2";
}
.fa-flask:before {
  content: "\f0c3";
}
.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}
.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}
.fa-paperclip:before {
  content: "\f0c6";
}
.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}
.fa-square:before {
  content: "\f0c8";
}
.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}
.fa-list-ul:before {
  content: "\f0ca";
}
.fa-list-ol:before {
  content: "\f0cb";
}
.fa-strikethrough:before {
  content: "\f0cc";
}
.fa-underline:before {
  content: "\f0cd";
}
.fa-table:before {
  content: "\f0ce";
}
.fa-magic:before {
  content: "\f0d0";
}
.fa-truck:before {
  content: "\f0d1";
}
.fa-pinterest:before {
  content: "\f0d2";
}
.fa-pinterest-square:before {
  content: "\f0d3";
}
.fa-google-plus-square:before {
  content: "\f0d4";
}
.fa-google-plus:before {
  content: "\f0d5";
}
.fa-money:before {
  content: "\f0d6";
}
.fa-caret-down:before {
  content: "\f0d7";
}
.fa-caret-up:before {
  content: "\f0d8";
}
.fa-caret-left:before {
  content: "\f0d9";
}
.fa-caret-right:before {
  content: "\f0da";
}
.fa-columns:before {
  content: "\f0db";
}
.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}
.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}
.fa-envelope:before {
  content: "\f0e0";
}
.fa-linkedin:before {
  content: "\f0e1";
}
.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}
.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}
.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}
.fa-comment-o:before {
  content: "\f0e5";
}
.fa-comments-o:before {
  content: "\f0e6";
}
.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}
.fa-sitemap:before {
  content: "\f0e8";
}
.fa-umbrella:before {
  content: "\f0e9";
}
.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}
.fa-lightbulb-o:before {
  content: "\f0eb";
}
.fa-exchange:before {
  content: "\f0ec";
}
.fa-cloud-download:before {
  content: "\f0ed";
}
.fa-cloud-upload:before {
  content: "\f0ee";
}
.fa-user-md:before {
  content: "\f0f0";
}
.fa-stethoscope:before {
  content: "\f0f1";
}
.fa-suitcase:before {
  content: "\f0f2";
}
.fa-bell-o:before {
  content: "\f0a2";
}
.fa-coffee:before {
  content: "\f0f4";
}
.fa-cutlery:before {
  content: "\f0f5";
}
.fa-file-text-o:before {
  content: "\f0f6";
}
.fa-building-o:before {
  content: "\f0f7";
}
.fa-hospital-o:before {
  content: "\f0f8";
}
.fa-ambulance:before {
  content: "\f0f9";
}
.fa-medkit:before {
  content: "\f0fa";
}
.fa-fighter-jet:before {
  content: "\f0fb";
}
.fa-beer:before {
  content: "\f0fc";
}
.fa-h-square:before {
  content: "\f0fd";
}
.fa-plus-square:before {
  content: "\f0fe";
}
.fa-angle-double-left:before {
  content: "\f100";
}
.fa-angle-double-right:before {
  content: "\f101";
}
.fa-angle-double-up:before {
  content: "\f102";
}
.fa-angle-double-down:before {
  content: "\f103";
}
.fa-angle-left:before {
  content: "\f104";
}
.fa-angle-right:before {
  content: "\f105";
}
.fa-angle-up:before {
  content: "\f106";
}
.fa-angle-down:before {
  content: "\f107";
}
.fa-desktop:before {
  content: "\f108";
}
.fa-laptop:before {
  content: "\f109";
}
.fa-tablet:before {
  content: "\f10a";
}
.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}
.fa-circle-o:before {
  content: "\f10c";
}
.fa-quote-left:before {
  content: "\f10d";
}
.fa-quote-right:before {
  content: "\f10e";
}
.fa-spinner:before {
  content: "\f110";
}
.fa-circle:before {
  content: "\f111";
}
.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}
.fa-github-alt:before {
  content: "\f113";
}
.fa-folder-o:before {
  content: "\f114";
}
.fa-folder-open-o:before {
  content: "\f115";
}
.fa-smile-o:before {
  content: "\f118";
}
.fa-frown-o:before {
  content: "\f119";
}
.fa-meh-o:before {
  content: "\f11a";
}
.fa-gamepad:before {
  content: "\f11b";
}
.fa-keyboard-o:before {
  content: "\f11c";
}
.fa-flag-o:before {
  content: "\f11d";
}
.fa-flag-checkered:before {
  content: "\f11e";
}
.fa-terminal:before {
  content: "\f120";
}
.fa-code:before {
  content: "\f121";
}
.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}
.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}
.fa-location-arrow:before {
  content: "\f124";
}
.fa-crop:before {
  content: "\f125";
}
.fa-code-fork:before {
  content: "\f126";
}
.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}
.fa-question:before {
  content: "\f128";
}
.fa-info:before {
  content: "\f129";
}
.fa-exclamation:before {
  content: "\f12a";
}
.fa-superscript:before {
  content: "\f12b";
}
.fa-subscript:before {
  content: "\f12c";
}
.fa-eraser:before {
  content: "\f12d";
}
.fa-puzzle-piece:before {
  content: "\f12e";
}
.fa-microphone:before {
  content: "\f130";
}
.fa-microphone-slash:before {
  content: "\f131";
}
.fa-shield:before {
  content: "\f132";
}
.fa-calendar-o:before {
  content: "\f133";
}
.fa-fire-extinguisher:before {
  content: "\f134";
}
.fa-rocket:before {
  content: "\f135";
}
.fa-maxcdn:before {
  content: "\f136";
}
.fa-chevron-circle-left:before {
  content: "\f137";
}
.fa-chevron-circle-right:before {
  content: "\f138";
}
.fa-chevron-circle-up:before {
  content: "\f139";
}
.fa-chevron-circle-down:before {
  content: "\f13a";
}
.fa-html5:before {
  content: "\f13b";
}
.fa-css3:before {
  content: "\f13c";
}
.fa-anchor:before {
  content: "\f13d";
}
.fa-unlock-alt:before {
  content: "\f13e";
}
.fa-bullseye:before {
  content: "\f140";
}
.fa-ellipsis-h:before {
  content: "\f141";
}
.fa-ellipsis-v:before {
  content: "\f142";
}
.fa-rss-square:before {
  content: "\f143";
}
.fa-play-circle:before {
  content: "\f144";
}
.fa-ticket:before {
  content: "\f145";
}
.fa-minus-square:before {
  content: "\f146";
}
.fa-minus-square-o:before {
  content: "\f147";
}
.fa-level-up:before {
  content: "\f148";
}
.fa-level-down:before {
  content: "\f149";
}
.fa-check-square:before {
  content: "\f14a";
}
.fa-pencil-square:before {
  content: "\f14b";
}
.fa-external-link-square:before {
  content: "\f14c";
}
.fa-share-square:before {
  content: "\f14d";
}
.fa-compass:before {
  content: "\f14e";
}
.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}
.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}
.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}
.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}
.fa-gbp:before {
  content: "\f154";
}
.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}
.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}
.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}
.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}
.fa-won:before,
.fa-krw:before {
  content: "\f159";
}
.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}
.fa-file:before {
  content: "\f15b";
}
.fa-file-text:before {
  content: "\f15c";
}
.fa-sort-alpha-asc:before {
  content: "\f15d";
}
.fa-sort-alpha-desc:before {
  content: "\f15e";
}
.fa-sort-amount-asc:before {
  content: "\f160";
}
.fa-sort-amount-desc:before {
  content: "\f161";
}
.fa-sort-numeric-asc:before {
  content: "\f162";
}
.fa-sort-numeric-desc:before {
  content: "\f163";
}
.fa-thumbs-up:before {
  content: "\f164";
}
.fa-thumbs-down:before {
  content: "\f165";
}
.fa-youtube-square:before {
  content: "\f166";
}
.fa-youtube:before {
  content: "\f167";
}
.fa-xing:before {
  content: "\f168";
}
.fa-xing-square:before {
  content: "\f169";
}
.fa-youtube-play:before {
  content: "\f16a";
}
.fa-dropbox:before {
  content: "\f16b";
}
.fa-stack-overflow:before {
  content: "\f16c";
}
.fa-instagram:before {
  content: "\f16d";
}
.fa-flickr:before {
  content: "\f16e";
}
.fa-adn:before {
  content: "\f170";
}
.fa-bitbucket:before {
  content: "\f171";
}
.fa-bitbucket-square:before {
  content: "\f172";
}
.fa-tumblr:before {
  content: "\f173";
}
.fa-tumblr-square:before {
  content: "\f174";
}
.fa-long-arrow-down:before {
  content: "\f175";
}
.fa-long-arrow-up:before {
  content: "\f176";
}
.fa-long-arrow-left:before {
  content: "\f177";
}
.fa-long-arrow-right:before {
  content: "\f178";
}
.fa-apple:before {
  content: "\f179";
}
.fa-windows:before {
  content: "\f17a";
}
.fa-android:before {
  content: "\f17b";
}
.fa-linux:before {
  content: "\f17c";
}
.fa-dribbble:before {
  content: "\f17d";
}
.fa-skype:before {
  content: "\f17e";
}
.fa-foursquare:before {
  content: "\f180";
}
.fa-trello:before {
  content: "\f181";
}
.fa-female:before {
  content: "\f182";
}
.fa-male:before {
  content: "\f183";
}
.fa-gittip:before {
  content: "\f184";
}
.fa-sun-o:before {
  content: "\f185";
}
.fa-moon-o:before {
  content: "\f186";
}
.fa-archive:before {
  content: "\f187";
}
.fa-bug:before {
  content: "\f188";
}
.fa-vk:before {
  content: "\f189";
}
.fa-weibo:before {
  content: "\f18a";
}
.fa-renren:before {
  content: "\f18b";
}
.fa-pagelines:before {
  content: "\f18c";
}
.fa-stack-exchange:before {
  content: "\f18d";
}
.fa-arrow-circle-o-right:before {
  content: "\f18e";
}
.fa-arrow-circle-o-left:before {
  content: "\f190";
}
.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}
.fa-dot-circle-o:before {
  content: "\f192";
}
.fa-wheelchair:before {
  content: "\f193";
}
.fa-vimeo-square:before {
  content: "\f194";
}
.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
.fa-space-shuttle:before {
  content: "\f197";
}
.fa-slack:before {
  content: "\f198";
}
.fa-envelope-square:before {
  content: "\f199";
}
.fa-wordpress:before {
  content: "\f19a";
}
.fa-openid:before {
  content: "\f19b";
}
.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}
.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}
.fa-yahoo:before {
  content: "\f19e";
}
.fa-google:before {
  content: "\f1a0";
}
.fa-reddit:before {
  content: "\f1a1";
}
.fa-reddit-square:before {
  content: "\f1a2";
}
.fa-stumbleupon-circle:before {
  content: "\f1a3";
}
.fa-stumbleupon:before {
  content: "\f1a4";
}
.fa-delicious:before {
  content: "\f1a5";
}
.fa-digg:before {
  content: "\f1a6";
}
.fa-pied-piper:before {
  content: "\f1a7";
}
.fa-pied-piper-alt:before {
  content: "\f1a8";
}
.fa-drupal:before {
  content: "\f1a9";
}
.fa-joomla:before {
  content: "\f1aa";
}
.fa-language:before {
  content: "\f1ab";
}
.fa-fax:before {
  content: "\f1ac";
}
.fa-building:before {
  content: "\f1ad";
}
.fa-child:before {
  content: "\f1ae";
}
.fa-paw:before {
  content: "\f1b0";
}
.fa-spoon:before {
  content: "\f1b1";
}
.fa-cube:before {
  content: "\f1b2";
}
.fa-cubes:before {
  content: "\f1b3";
}
.fa-behance:before {
  content: "\f1b4";
}
.fa-behance-square:before {
  content: "\f1b5";
}
.fa-steam:before {
  content: "\f1b6";
}
.fa-steam-square:before {
  content: "\f1b7";
}
.fa-recycle:before {
  content: "\f1b8";
}
.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}
.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}
.fa-tree:before {
  content: "\f1bb";
}
.fa-spotify:before {
  content: "\f1bc";
}
.fa-deviantart:before {
  content: "\f1bd";
}
.fa-soundcloud:before {
  content: "\f1be";
}
.fa-database:before {
  content: "\f1c0";
}
.fa-file-pdf-o:before {
  content: "\f1c1";
}
.fa-file-word-o:before {
  content: "\f1c2";
}
.fa-file-excel-o:before {
  content: "\f1c3";
}
.fa-file-powerpoint-o:before {
  content: "\f1c4";
}
.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}
.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}
.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}
.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}
.fa-file-code-o:before {
  content: "\f1c9";
}
.fa-vine:before {
  content: "\f1ca";
}
.fa-codepen:before {
  content: "\f1cb";
}
.fa-jsfiddle:before {
  content: "\f1cc";
}
.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}
.fa-circle-o-notch:before {
  content: "\f1ce";
}
.fa-ra:before,
.fa-rebel:before {
  content: "\f1d0";
}
.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}
.fa-git-square:before {
  content: "\f1d2";
}
.fa-git:before {
  content: "\f1d3";
}
.fa-hacker-news:before {
  content: "\f1d4";
}
.fa-tencent-weibo:before {
  content: "\f1d5";
}
.fa-qq:before {
  content: "\f1d6";
}
.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}
.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}
.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}
.fa-history:before {
  content: "\f1da";
}
.fa-circle-thin:before {
  content: "\f1db";
}
.fa-header:before {
  content: "\f1dc";
}
.fa-paragraph:before {
  content: "\f1dd";
}
.fa-sliders:before {
  content: "\f1de";
}
.fa-share-alt:before {
  content: "\f1e0";
}
.fa-share-alt-square:before {
  content: "\f1e1";
}
.fa-bomb:before {
  content: "\f1e2";
}
.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}
.fa-tty:before {
  content: "\f1e4";
}
.fa-binoculars:before {
  content: "\f1e5";
}
.fa-plug:before {
  content: "\f1e6";
}
.fa-slideshare:before {
  content: "\f1e7";
}
.fa-twitch:before {
  content: "\f1e8";
}
.fa-yelp:before {
  content: "\f1e9";
}
.fa-newspaper-o:before {
  content: "\f1ea";
}
.fa-wifi:before {
  content: "\f1eb";
}
.fa-calculator:before {
  content: "\f1ec";
}
.fa-paypal:before {
  content: "\f1ed";
}
.fa-google-wallet:before {
  content: "\f1ee";
}
.fa-cc-visa:before {
  content: "\f1f0";
}
.fa-cc-mastercard:before {
  content: "\f1f1";
}
.fa-cc-discover:before {
  content: "\f1f2";
}
.fa-cc-amex:before {
  content: "\f1f3";
}
.fa-cc-paypal:before {
  content: "\f1f4";
}
.fa-cc-stripe:before {
  content: "\f1f5";
}
.fa-bell-slash:before {
  content: "\f1f6";
}
.fa-bell-slash-o:before {
  content: "\f1f7";
}
.fa-trash:before {
  content: "\f1f8";
}
.fa-copyright:before {
  content: "\f1f9";
}
.fa-at:before {
  content: "\f1fa";
}
.fa-eyedropper:before {
  content: "\f1fb";
}
.fa-paint-brush:before {
  content: "\f1fc";
}
.fa-birthday-cake:before {
  content: "\f1fd";
}
.fa-area-chart:before {
  content: "\f1fe";
}
.fa-pie-chart:before {
  content: "\f200";
}
.fa-line-chart:before {
  content: "\f201";
}
.fa-lastfm:before {
  content: "\f202";
}
.fa-lastfm-square:before {
  content: "\f203";
}
.fa-toggle-off:before {
  content: "\f204";
}
.fa-toggle-on:before {
  content: "\f205";
}
.fa-bicycle:before {
  content: "\f206";
}
.fa-bus:before {
  content: "\f207";
}
.fa-ioxhost:before {
  content: "\f208";
}
.fa-angellist:before {
  content: "\f209";
}
.fa-cc:before {
  content: "\f20a";
}
.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}
.fa-meanpath:before {
  content: "\f20c";
}
/*!
*
* IPython base
*
*/
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
code {
  color: #000;
}
pre {
  font-size: inherit;
  line-height: inherit;
}
label {
  font-weight: normal;
}
/* Make the page background atleast 100% the height of the view port */
/* Make the page itself atleast 70% the height of the view port */
.border-box-sizing {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.corner-all {
  border-radius: 2px;
}
.no-padding {
  padding: 0px;
}
/* Flexible box model classes */
/* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */
/* This file is a compatability layer.  It allows the usage of flexible box 
model layouts accross multiple browsers, including older browsers.  The newest,
universal implementation of the flexible box model is used when available (see
`Modern browsers` comments below).  Browsers that are known to implement this 
new spec completely include:

    Firefox 28.0+
    Chrome 29.0+
    Internet Explorer 11+ 
    Opera 17.0+

Browsers not listed, including Safari, are supported via the styling under the
`Old browsers` comments below.
*/
.hbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
.hbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.vbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
.vbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.hbox.reverse,
.vbox.reverse,
.reverse {
  /* Old browsers */
  -webkit-box-direction: reverse;
  -moz-box-direction: reverse;
  box-direction: reverse;
  /* Modern browsers */
  flex-direction: row-reverse;
}
.hbox.box-flex0,
.vbox.box-flex0,
.box-flex0 {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  width: auto;
}
.hbox.box-flex1,
.vbox.box-flex1,
.box-flex1 {
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex,
.vbox.box-flex,
.box-flex {
  /* Old browsers */
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex2,
.vbox.box-flex2,
.box-flex2 {
  /* Old browsers */
  -webkit-box-flex: 2;
  -moz-box-flex: 2;
  box-flex: 2;
  /* Modern browsers */
  flex: 2;
}
.box-group1 {
  /*  Deprecated */
  -webkit-box-flex-group: 1;
  -moz-box-flex-group: 1;
  box-flex-group: 1;
}
.box-group2 {
  /* Deprecated */
  -webkit-box-flex-group: 2;
  -moz-box-flex-group: 2;
  box-flex-group: 2;
}
.hbox.start,
.vbox.start,
.start {
  /* Old browsers */
  -webkit-box-pack: start;
  -moz-box-pack: start;
  box-pack: start;
  /* Modern browsers */
  justify-content: flex-start;
}
.hbox.end,
.vbox.end,
.end {
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
}
.hbox.center,
.vbox.center,
.center {
  /* Old browsers */
  -webkit-box-pack: center;
  -moz-box-pack: center;
  box-pack: center;
  /* Modern browsers */
  justify-content: center;
}
.hbox.baseline,
.vbox.baseline,
.baseline {
  /* Old browsers */
  -webkit-box-pack: baseline;
  -moz-box-pack: baseline;
  box-pack: baseline;
  /* Modern browsers */
  justify-content: baseline;
}
.hbox.stretch,
.vbox.stretch,
.stretch {
  /* Old browsers */
  -webkit-box-pack: stretch;
  -moz-box-pack: stretch;
  box-pack: stretch;
  /* Modern browsers */
  justify-content: stretch;
}
.hbox.align-start,
.vbox.align-start,
.align-start {
  /* Old browsers */
  -webkit-box-align: start;
  -moz-box-align: start;
  box-align: start;
  /* Modern browsers */
  align-items: flex-start;
}
.hbox.align-end,
.vbox.align-end,
.align-end {
  /* Old browsers */
  -webkit-box-align: end;
  -moz-box-align: end;
  box-align: end;
  /* Modern browsers */
  align-items: flex-end;
}
.hbox.align-center,
.vbox.align-center,
.align-center {
  /* Old browsers */
  -webkit-box-align: center;
  -moz-box-align: center;
  box-align: center;
  /* Modern browsers */
  align-items: center;
}
.hbox.align-baseline,
.vbox.align-baseline,
.align-baseline {
  /* Old browsers */
  -webkit-box-align: baseline;
  -moz-box-align: baseline;
  box-align: baseline;
  /* Modern browsers */
  align-items: baseline;
}
.hbox.align-stretch,
.vbox.align-stretch,
.align-stretch {
  /* Old browsers */
  -webkit-box-align: stretch;
  -moz-box-align: stretch;
  box-align: stretch;
  /* Modern browsers */
  align-items: stretch;
}
div.error {
  margin: 2em;
  text-align: center;
}
div.error > h1 {
  font-size: 500%;
  line-height: normal;
}
div.error > p {
  font-size: 200%;
  line-height: normal;
}
div.traceback-wrapper {
  text-align: left;
  max-width: 800px;
  margin: auto;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
body {
  background-color: #fff;
  /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  overflow: visible;
}
body > #header {
  /* Initially hidden to prevent FLOUC */
  display: none;
  background-color: #fff;
  /* Display over codemirror */
  position: relative;
  z-index: 100;
}
body > #header #header-container {
  padding-bottom: 5px;
  padding-top: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
body > #header .header-bar {
  width: 100%;
  height: 1px;
  background: #e7e7e7;
  margin-bottom: -1px;
}
@media print {
  body > #header {
    display: none !important;
  }
}
#header-spacer {
  width: 100%;
  visibility: hidden;
}
@media print {
  #header-spacer {
    display: none;
  }
}
#ipython_notebook {
  padding-left: 0px;
  padding-top: 1px;
  padding-bottom: 1px;
}
@media (max-width: 991px) {
  #ipython_notebook {
    margin-left: 10px;
  }
}
[dir="rtl"] #ipython_notebook {
  float: right !important;
}
#noscript {
  width: auto;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
  font-size: 22px;
  color: red;
  font-weight: bold;
}
#ipython_notebook img {
  height: 28px;
}
#site {
  width: 100%;
  display: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  overflow: auto;
}
@media print {
  #site {
    height: auto !important;
  }
}
/* Smaller buttons */
.ui-button .ui-button-text {
  padding: 0.2em 0.8em;
  font-size: 77%;
}
input.ui-button {
  padding: 0.3em 0.9em;
}
span#login_widget {
  float: right;
}
span#login_widget > .button,
#logout {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button:focus,
#logout:focus,
span#login_widget > .button.focus,
#logout.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
span#login_widget > .button:hover,
#logout:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active:hover,
#logout:active:hover,
span#login_widget > .button.active:hover,
#logout.active:hover,
.open > .dropdown-togglespan#login_widget > .button:hover,
.open > .dropdown-toggle#logout:hover,
span#login_widget > .button:active:focus,
#logout:active:focus,
span#login_widget > .button.active:focus,
#logout.active:focus,
.open > .dropdown-togglespan#login_widget > .button:focus,
.open > .dropdown-toggle#logout:focus,
span#login_widget > .button:active.focus,
#logout:active.focus,
span#login_widget > .button.active.focus,
#logout.active.focus,
.open > .dropdown-togglespan#login_widget > .button.focus,
.open > .dropdown-toggle#logout.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  background-image: none;
}
span#login_widget > .button.disabled:hover,
#logout.disabled:hover,
span#login_widget > .button[disabled]:hover,
#logout[disabled]:hover,
fieldset[disabled] span#login_widget > .button:hover,
fieldset[disabled] #logout:hover,
span#login_widget > .button.disabled:focus,
#logout.disabled:focus,
span#login_widget > .button[disabled]:focus,
#logout[disabled]:focus,
fieldset[disabled] span#login_widget > .button:focus,
fieldset[disabled] #logout:focus,
span#login_widget > .button.disabled.focus,
#logout.disabled.focus,
span#login_widget > .button[disabled].focus,
#logout[disabled].focus,
fieldset[disabled] span#login_widget > .button.focus,
fieldset[disabled] #logout.focus {
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button .badge,
#logout .badge {
  color: #fff;
  background-color: #333;
}
.nav-header {
  text-transform: none;
}
#header > span {
  margin-top: 10px;
}
.modal_stretch .modal-dialog {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  min-height: 80vh;
}
.modal_stretch .modal-dialog .modal-body {
  max-height: calc(100vh - 200px);
  overflow: auto;
  flex: 1;
}
@media (min-width: 768px) {
  .modal .modal-dialog {
    width: 700px;
  }
}
@media (min-width: 768px) {
  select.form-control {
    margin-left: 12px;
    margin-right: 12px;
  }
}
/*!
*
* IPython auth
*
*/
.center-nav {
  display: inline-block;
  margin-bottom: -4px;
}
/*!
*
* IPython tree view
*
*/
/* We need an invisible input field on top of the sentense*/
/* "Drag file onto the list ..." */
.alternate_upload {
  background-color: none;
  display: inline;
}
.alternate_upload.form {
  padding: 0;
  margin: 0;
}
.alternate_upload input.fileinput {
  text-align: center;
  vertical-align: middle;
  display: inline;
  opacity: 0;
  z-index: 2;
  width: 12ex;
  margin-right: -12ex;
}
.alternate_upload .btn-upload {
  height: 22px;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
[dir="rtl"] #tabs li {
  float: right;
}
ul#tabs {
  margin-bottom: 4px;
}
[dir="rtl"] ul#tabs {
  margin-right: 0px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
ul.breadcrumb a:focus,
ul.breadcrumb a:hover {
  text-decoration: none;
}
ul.breadcrumb i.icon-home {
  font-size: 16px;
  margin-right: 4px;
}
ul.breadcrumb span {
  color: #5e5e5e;
}
.list_toolbar {
  padding: 4px 0 4px 0;
  vertical-align: middle;
}
.list_toolbar .tree-buttons {
  padding-top: 1px;
}
[dir="rtl"] .list_toolbar .tree-buttons {
  float: left !important;
}
[dir="rtl"] .list_toolbar .pull-right {
  padding-top: 1px;
  float: left !important;
}
[dir="rtl"] .list_toolbar .pull-left {
  float: right !important;
}
.dynamic-buttons {
  padding-top: 3px;
  display: inline-block;
}
.list_toolbar [class*="span"] {
  min-height: 24px;
}
.list_header {
  font-weight: bold;
  background-color: #EEE;
}
.list_placeholder {
  font-weight: bold;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
}
.list_container {
  margin-top: 4px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  border-radius: 2px;
}
.list_container > div {
  border-bottom: 1px solid #ddd;
}
.list_container > div:hover .list-item {
  background-color: red;
}
.list_container > div:last-child {
  border: none;
}
.list_item:hover .list_item {
  background-color: #ddd;
}
.list_item a {
  text-decoration: none;
}
.list_item:hover {
  background-color: #fafafa;
}
.list_header > div,
.list_item > div {
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
.list_header > div input,
.list_item > div input {
  margin-right: 7px;
  margin-left: 14px;
  vertical-align: baseline;
  line-height: 22px;
  position: relative;
  top: -1px;
}
.list_header > div .item_link,
.list_item > div .item_link {
  margin-left: -1px;
  vertical-align: baseline;
  line-height: 22px;
}
.new-file input[type=checkbox] {
  visibility: hidden;
}
.item_name {
  line-height: 22px;
  height: 24px;
}
.item_icon {
  font-size: 14px;
  color: #5e5e5e;
  margin-right: 7px;
  margin-left: 7px;
  line-height: 22px;
  vertical-align: baseline;
}
.item_buttons {
  line-height: 1em;
  margin-left: -5px;
}
.item_buttons .btn,
.item_buttons .btn-group,
.item_buttons .input-group {
  float: left;
}
.item_buttons > .btn,
.item_buttons > .btn-group,
.item_buttons > .input-group {
  margin-left: 5px;
}
.item_buttons .btn {
  min-width: 13ex;
}
.item_buttons .running-indicator {
  padding-top: 4px;
  color: #5cb85c;
}
.item_buttons .kernel-name {
  padding-top: 4px;
  color: #5bc0de;
  margin-right: 7px;
  float: left;
}
.toolbar_info {
  height: 24px;
  line-height: 24px;
}
.list_item input:not([type=checkbox]) {
  padding-top: 3px;
  padding-bottom: 3px;
  height: 22px;
  line-height: 14px;
  margin: 0px;
}
.highlight_text {
  color: blue;
}
#project_name {
  display: inline-block;
  padding-left: 7px;
  margin-left: -2px;
}
#project_name > .breadcrumb {
  padding: 0px;
  margin-bottom: 0px;
  background-color: transparent;
  font-weight: bold;
}
#tree-selector {
  padding-right: 0px;
}
[dir="rtl"] #tree-selector a {
  float: right;
}
#button-select-all {
  min-width: 50px;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
}
.menu_icon {
  margin-right: 2px;
}
.tab-content .row {
  margin-left: 0px;
  margin-right: 0px;
}
.folder_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f114";
}
.folder_icon:before.pull-left {
  margin-right: .3em;
}
.folder_icon:before.pull-right {
  margin-left: .3em;
}
.notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
}
.notebook_icon:before.pull-left {
  margin-right: .3em;
}
.notebook_icon:before.pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
  color: #5cb85c;
}
.running_notebook_icon:before.pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.pull-right {
  margin-left: .3em;
}
.file_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f016";
  position: relative;
  top: -2px;
}
.file_icon:before.pull-left {
  margin-right: .3em;
}
.file_icon:before.pull-right {
  margin-left: .3em;
}
#notebook_toolbar .pull-right {
  padding-top: 0px;
  margin-right: -1px;
}
ul#new-menu {
  left: auto;
  right: 0;
}
[dir="rtl"] #new-menu {
  text-align: right;
}
.kernel-menu-icon {
  padding-right: 12px;
  width: 24px;
  content: "\f096";
}
.kernel-menu-icon:before {
  content: "\f096";
}
.kernel-menu-icon-current:before {
  content: "\f00c";
}
#tab_content {
  padding-top: 20px;
}
#running .panel-group .panel {
  margin-top: 3px;
  margin-bottom: 1em;
}
#running .panel-group .panel .panel-heading {
  background-color: #EEE;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
#running .panel-group .panel .panel-heading a:focus,
#running .panel-group .panel .panel-heading a:hover {
  text-decoration: none;
}
#running .panel-group .panel .panel-body {
  padding: 0px;
}
#running .panel-group .panel .panel-body .list_container {
  margin-top: 0px;
  margin-bottom: 0px;
  border: 0px;
  border-radius: 0px;
}
#running .panel-group .panel .panel-body .list_container .list_item {
  border-bottom: 1px solid #ddd;
}
#running .panel-group .panel .panel-body .list_container .list_item:last-child {
  border-bottom: 0px;
}
[dir="rtl"] #running .col-sm-8 {
  float: right !important;
}
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.shutdown-button {
  display: none;
}
.dynamic-instructions {
  display: inline-block;
  padding-top: 4px;
}
/*!
*
* IPython text editor webapp
*
*/
.selected-keymap i.fa {
  padding: 0px 5px;
}
.selected-keymap i.fa:before {
  content: "\f00c";
}
#mode-menu {
  overflow: auto;
  max-height: 20em;
}
.edit_app #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.edit_app #menubar .navbar {
  /* Use a negative 1 bottom margin, so the border overlaps the border of the
    header */
  margin-bottom: -1px;
}
.dirty-indicator {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator.pull-left {
  margin-right: .3em;
}
.dirty-indicator.pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-dirty.pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-clean.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f00c";
}
.dirty-indicator-clean:before.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.pull-right {
  margin-left: .3em;
}
#filename {
  font-size: 16pt;
  display: table;
  padding: 0px 5px;
}
#current-mode {
  padding-left: 5px;
  padding-right: 5px;
}
#texteditor-backdrop {
  padding-top: 20px;
  padding-bottom: 20px;
}
@media not print {
  #texteditor-backdrop {
    background-color: #EEE;
  }
}
@media print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container {
    padding: 0px;
    background-color: #fff;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI colors. */
.ansibold {
  font-weight: bold;
}
/* use dark versions for foreground, to improve visibility */
.ansiblack {
  color: black;
}
.ansired {
  color: darkred;
}
.ansigreen {
  color: darkgreen;
}
.ansiyellow {
  color: #c4a000;
}
.ansiblue {
  color: darkblue;
}
.ansipurple {
  color: darkviolet;
}
.ansicyan {
  color: steelblue;
}
.ansigray {
  color: gray;
}
/* and light for background, for the same reason */
.ansibgblack {
  background-color: black;
}
.ansibgred {
  background-color: red;
}
.ansibggreen {
  background-color: green;
}
.ansibgyellow {
  background-color: yellow;
}
.ansibgblue {
  background-color: blue;
}
.ansibgpurple {
  background-color: magenta;
}
.ansibgcyan {
  background-color: cyan;
}
.ansibggray {
  background-color: gray;
}
div.cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-radius: 2px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  border-width: 1px;
  border-style: solid;
  border-color: transparent;
  width: 100%;
  padding: 5px;
  /* This acts as a spacer between cells, that is outside the border */
  margin: 0px;
  outline: none;
  border-left-width: 1px;
  padding-left: 5px;
  background: linear-gradient(to right, transparent -40px, transparent 1px, transparent 1px, transparent 100%);
}
div.cell.jupyter-soft-selected {
  border-left-color: #90CAF9;
  border-left-color: #E3F2FD;
  border-left-width: 1px;
  padding-left: 5px;
  border-right-color: #E3F2FD;
  border-right-width: 1px;
  background: #E3F2FD;
}
@media print {
  div.cell.jupyter-soft-selected {
    border-color: transparent;
  }
}
div.cell.selected {
  border-color: #ababab;
  border-left-width: 0px;
  padding-left: 6px;
  background: linear-gradient(to right, #42A5F5 -40px, #42A5F5 5px, transparent 5px, transparent 100%);
}
@media print {
  div.cell.selected {
    border-color: transparent;
  }
}
div.cell.selected.jupyter-soft-selected {
  border-left-width: 0;
  padding-left: 6px;
  background: linear-gradient(to right, #42A5F5 -40px, #42A5F5 7px, #E3F2FD 7px, #E3F2FD 100%);
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
  border-left-width: 0px;
  padding-left: 6px;
  background: linear-gradient(to right, #66BB6A -40px, #66BB6A 5px, transparent 5px, transparent 100%);
}
@media print {
  .edit_mode div.cell.selected {
    border-color: transparent;
  }
}
.prompt {
  /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
  min-width: 14ex;
  /* This padding is tuned to match the padding on the CodeMirror editor. */
  padding: 0.4em;
  margin: 0px;
  font-family: monospace;
  text-align: right;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
  /* Don't highlight prompt number selection */
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* Use default cursor */
  cursor: default;
}
@media (max-width: 540px) {
  .prompt {
    text-align: left;
  }
}
div.inner_cell {
  min-width: 0;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_area {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
}
/* This is needed so that empty prompt areas can collapse to zero height when there
   is no content in the output_subarea and the prompt. The main purpose of this is
   to make sure that empty JavaScript output_subareas have no height. */
div.prompt:empty {
  padding-top: 0;
  padding-bottom: 0;
}
div.unrecognized_cell {
  padding: 5px 5px 5px 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.unrecognized_cell .inner_cell {
  border-radius: 2px;
  padding: 5px;
  font-weight: bold;
  color: red;
  border: 1px solid #cfcfcf;
  background: #eaeaea;
}
div.unrecognized_cell .inner_cell a {
  color: inherit;
  text-decoration: none;
}
div.unrecognized_cell .inner_cell a:hover {
  color: inherit;
  text-decoration: none;
}
@media (max-width: 540px) {
  div.unrecognized_cell > div.prompt {
    display: none;
  }
}
div.code_cell {
  /* avoid page breaking on code cells when printing */
}
@media print {
  div.code_cell {
    page-break-inside: avoid;
  }
}
/* any special styling for code cells that are currently running goes here */
div.input {
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.input {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_prompt {
  color: #303F9F;
  border-top: 1px solid transparent;
}
div.input_area > div.highlight {
  margin: 0.4em;
  border: none;
  padding: 0px;
  background-color: transparent;
}
div.input_area > div.highlight > pre {
  margin: 0px;
  border: none;
  padding: 0px;
  background-color: transparent;
}
/* The following gets added to the <head> if it is detected that the user has a
 * monospace font with inconsistent normal/bold/italic height.  See
 * notebookmain.js.  Such fonts will have keywords vertically offset with
 * respect to the rest of the text.  The user should select a better font.
 * See: https://github.com/ipython/ipython/issues/1503
 *
 * .CodeMirror span {
 *      vertical-align: bottom;
 * }
 */
.CodeMirror {
  line-height: 1.21429em;
  /* Changed from 1em to our global default */
  font-size: 14px;
  height: auto;
  /* Changed to auto to autogrow */
  background: none;
  /* Changed from white to allow our bg to show through */
}
.CodeMirror-scroll {
  /*  The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/
  /*  We have found that if it is visible, vertical scrollbars appear with font size changes.*/
  overflow-y: hidden;
  overflow-x: auto;
}
.CodeMirror-lines {
  /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */
  /* we have set a different line-height and want this to scale with that. */
  padding: 0.4em;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. We need the 0 value because of how we size */
  /* .CodeMirror-lines */
  padding: 0;
  border: 0;
  border-radius: 0;
}
/*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
.highlight-base {
  color: #000;
}
.highlight-variable {
  color: #000;
}
.highlight-variable-2 {
  color: #1a1a1a;
}
.highlight-variable-3 {
  color: #333333;
}
.highlight-string {
  color: #BA2121;
}
.highlight-comment {
  color: #408080;
  font-style: italic;
}
.highlight-number {
  color: #080;
}
.highlight-atom {
  color: #88F;
}
.highlight-keyword {
  color: #008000;
  font-weight: bold;
}
.highlight-builtin {
  color: #008000;
}
.highlight-error {
  color: #f00;
}
.highlight-operator {
  color: #AA22FF;
  font-weight: bold;
}
.highlight-meta {
  color: #AA22FF;
}
/* previously not defined, copying from default codemirror */
.highlight-def {
  color: #00f;
}
.highlight-string-2 {
  color: #f50;
}
.highlight-qualifier {
  color: #555;
}
.highlight-bracket {
  color: #997;
}
.highlight-tag {
  color: #170;
}
.highlight-attribute {
  color: #00c;
}
.highlight-header {
  color: blue;
}
.highlight-quote {
  color: #090;
}
.highlight-link {
  color: #00c;
}
/* apply the same style to codemirror */
.cm-s-ipython span.cm-keyword {
  color: #008000;
  font-weight: bold;
}
.cm-s-ipython span.cm-atom {
  color: #88F;
}
.cm-s-ipython span.cm-number {
  color: #080;
}
.cm-s-ipython span.cm-def {
  color: #00f;
}
.cm-s-ipython span.cm-variable {
  color: #000;
}
.cm-s-ipython span.cm-operator {
  color: #AA22FF;
  font-weight: bold;
}
.cm-s-ipython span.cm-variable-2 {
  color: #1a1a1a;
}
.cm-s-ipython span.cm-variable-3 {
  color: #333333;
}
.cm-s-ipython span.cm-comment {
  color: #408080;
  font-style: italic;
}
.cm-s-ipython span.cm-string {
  color: #BA2121;
}
.cm-s-ipython span.cm-string-2 {
  color: #f50;
}
.cm-s-ipython span.cm-meta {
  color: #AA22FF;
}
.cm-s-ipython span.cm-qualifier {
  color: #555;
}
.cm-s-ipython span.cm-builtin {
  color: #008000;
}
.cm-s-ipython span.cm-bracket {
  color: #997;
}
.cm-s-ipython span.cm-tag {
  color: #170;
}
.cm-s-ipython span.cm-attribute {
  color: #00c;
}
.cm-s-ipython span.cm-header {
  color: blue;
}
.cm-s-ipython span.cm-quote {
  color: #090;
}
.cm-s-ipython span.cm-link {
  color: #00c;
}
.cm-s-ipython span.cm-error {
  color: #f00;
}
.cm-s-ipython span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}
div.output_wrapper {
  /* this position must be relative to enable descendents to be absolute within it */
  position: relative;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  z-index: 1;
}
/* class for the output area when it should be height-limited */
div.output_scroll {
  /* ideally, this would be max-height, but FF barfs all over that */
  height: 24em;
  /* FF needs this *and the wrapper* to specify full width, or it will shrinkwrap */
  width: 100%;
  overflow: auto;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  display: block;
}
/* output div while it is collapsed */
div.output_collapsed {
  margin: 0px;
  padding: 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
div.out_prompt_overlay {
  height: 100%;
  padding: 0px 0.4em;
  position: absolute;
  border-radius: 2px;
}
div.out_prompt_overlay:hover {
  /* use inner shadow to get border that is computed the same on WebKit/FF */
  -webkit-box-shadow: inset 0 0 1px #000;
  box-shadow: inset 0 0 1px #000;
  background: rgba(240, 240, 240, 0.5);
}
div.output_prompt {
  color: #D84315;
}
/* This class is the outer container of all output sections. */
div.output_area {
  padding: 0px;
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.output_area .MathJax_Display {
  text-align: left !important;
}
div.output_area .rendered_html table {
  margin-left: 0;
  margin-right: 0;
}
div.output_area .rendered_html img {
  margin-left: 0;
  margin-right: 0;
}
div.output_area img,
div.output_area svg {
  max-width: 100%;
  height: auto;
}
div.output_area img.unconfined,
div.output_area svg.unconfined {
  max-width: none;
}
/* This is needed to protect the pre formating from global settings such
   as that of bootstrap */
.output {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.output_area {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
div.output_area pre {
  margin: 0;
  padding: 0;
  border: 0;
  vertical-align: baseline;
  color: black;
  background-color: transparent;
  border-radius: 0;
}
/* This class is for the output subarea inside the output_area and after
   the prompt div. */
div.output_subarea {
  overflow-x: auto;
  padding: 0.4em;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
  max-width: calc(100% - 14ex);
}
div.output_scroll div.output_subarea {
  overflow-x: visible;
}
/* The rest of the output_* classes are for special styling of the different
   output types */
/* all text output has this class: */
div.output_text {
  text-align: left;
  color: #000;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
}
/* stdout/stderr are 'text' as well as 'stream', but execute_result/error are *not* streams */
div.output_stderr {
  background: #fdd;
  /* very light red background for stderr */
}
div.output_latex {
  text-align: left;
}
/* Empty output_javascript divs should have no height */
div.output_javascript:empty {
  padding: 0;
}
.js-error {
  color: darkred;
}
/* raw_input styles */
div.raw_input_container {
  line-height: 1.21429em;
  padding-top: 5px;
}
pre.raw_input_prompt {
  /* nothing needed here. */
}
input.raw_input {
  font-family: monospace;
  font-size: inherit;
  color: inherit;
  width: auto;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
}
input.raw_input:focus {
  box-shadow: none;
}
p.p-space {
  margin-bottom: 10px;
}
div.output_unrecognized {
  padding: 5px;
  font-weight: bold;
  color: red;
}
div.output_unrecognized a {
  color: inherit;
  text-decoration: none;
}
div.output_unrecognized a:hover {
  color: inherit;
  text-decoration: none;
}
.rendered_html {
  color: #000;
  /* any extras will just be numbers: */
}
.rendered_html em {
  font-style: italic;
}
.rendered_html strong {
  font-weight: bold;
}
.rendered_html u {
  text-decoration: underline;
}
.rendered_html :link {
  text-decoration: underline;
}
.rendered_html :visited {
  text-decoration: underline;
}
.rendered_html h1 {
  font-size: 185.7%;
  margin: 1.08em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h2 {
  font-size: 157.1%;
  margin: 1.27em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h3 {
  font-size: 128.6%;
  margin: 1.55em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h4 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h5 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h6 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h1:first-child {
  margin-top: 0.538em;
}
.rendered_html h2:first-child {
  margin-top: 0.636em;
}
.rendered_html h3:first-child {
  margin-top: 0.777em;
}
.rendered_html h4:first-child {
  margin-top: 1em;
}
.rendered_html h5:first-child {
  margin-top: 1em;
}
.rendered_html h6:first-child {
  margin-top: 1em;
}
.rendered_html ul {
  list-style: disc;
  margin: 0em 2em;
  padding-left: 0px;
}
.rendered_html ul ul {
  list-style: square;
  margin: 0em 2em;
}
.rendered_html ul ul ul {
  list-style: circle;
  margin: 0em 2em;
}
.rendered_html ol {
  list-style: decimal;
  margin: 0em 2em;
  padding-left: 0px;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin: 0em 2em;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
  margin: 0em 2em;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
  margin: 0em 2em;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
  margin: 0em 2em;
}
.rendered_html * + ul {
  margin-top: 1em;
}
.rendered_html * + ol {
  margin-top: 1em;
}
.rendered_html hr {
  color: black;
  background-color: black;
}
.rendered_html pre {
  margin: 1em 2em;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  background-color: #fff;
  color: #000;
  font-size: 100%;
  padding: 0px;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: 1px solid black;
  border-collapse: collapse;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  border: 1px solid black;
  border-collapse: collapse;
  margin: 1em 2em;
}
.rendered_html td,
.rendered_html th {
  text-align: left;
  vertical-align: middle;
  padding: 4px;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html * + table {
  margin-top: 1em;
}
.rendered_html p {
  text-align: left;
}
.rendered_html * + p {
  margin-top: 1em;
}
.rendered_html img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.rendered_html * + img {
  margin-top: 1em;
}
.rendered_html img,
.rendered_html svg {
  max-width: 100%;
  height: auto;
}
.rendered_html img.unconfined,
.rendered_html svg.unconfined {
  max-width: none;
}
div.text_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.text_cell > div.prompt {
    display: none;
  }
}
div.text_cell_render {
  /*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;*/
  outline: none;
  resize: none;
  width: inherit;
  border-style: none;
  padding: 0.5em 0.5em 0.5em 0.4em;
  color: #000;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
a.anchor-link:link {
  text-decoration: none;
  padding: 0px 20px;
  visibility: hidden;
}
h1:hover .anchor-link,
h2:hover .anchor-link,
h3:hover .anchor-link,
h4:hover .anchor-link,
h5:hover .anchor-link,
h6:hover .anchor-link {
  visibility: visible;
}
.text_cell.rendered .input_area {
  display: none;
}
.text_cell.rendered .rendered_html {
  overflow-x: auto;
  overflow-y: hidden;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.cm-header-1,
.cm-header-2,
.cm-header-3,
.cm-header-4,
.cm-header-5,
.cm-header-6 {
  font-weight: bold;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.cm-header-1 {
  font-size: 185.7%;
}
.cm-header-2 {
  font-size: 157.1%;
}
.cm-header-3 {
  font-size: 128.6%;
}
.cm-header-4 {
  font-size: 110%;
}
.cm-header-5 {
  font-size: 100%;
  font-style: italic;
}
.cm-header-6 {
  font-size: 100%;
  font-style: italic;
}
/*!
*
* IPython notebook webapp
*
*/
@media (max-width: 767px) {
  .notebook_app {
    padding-left: 0px;
    padding-right: 0px;
  }
}
#ipython-main-app {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook_panel {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook {
  font-size: 14px;
  line-height: 20px;
  overflow-y: hidden;
  overflow-x: auto;
  width: 100%;
  /* This spaces the page away from the edge of the notebook area */
  padding-top: 20px;
  margin: 0px;
  outline: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  min-height: 100%;
}
@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #fff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
@media print {
  #notebook-container {
    width: 100%;
  }
}
div.ui-widget-content {
  border: 1px solid #ababab;
  outline: none;
}
pre.dialog {
  background-color: #f7f7f7;
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 0.4em;
  padding-left: 2em;
}
p.dialog {
  padding: 0.2em;
}
/* Word-wrap output correctly.  This is the CSS3 spelling, though Firefox seems
   to not honor it correctly.  Webkit browsers (Chrome, rekonq, Safari) do.
 */
pre,
code,
kbd,
samp {
  white-space: pre-wrap;
}
#fonttest {
  font-family: monospace;
}
p {
  margin-bottom: 0;
}
.end_space {
  min-height: 100px;
  transition: height .2s ease;
}
.notebook_app > #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
@media not print {
  .notebook_app {
    background-color: #EEE;
  }
}
kbd {
  border-style: solid;
  border-width: 1px;
  box-shadow: none;
  margin: 2px;
  padding-left: 2px;
  padding-right: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
/* CSS for the cell toolbar */
.celltoolbar {
  border: thin solid #CFCFCF;
  border-bottom: none;
  background: #EEE;
  border-radius: 2px 2px 0px 0px;
  width: 100%;
  height: 29px;
  padding-right: 4px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
  display: -webkit-flex;
}
@media print {
  .celltoolbar {
    display: none;
  }
}
.ctb_hideshow {
  display: none;
  vertical-align: bottom;
}
/* ctb_show is added to the ctb_hideshow div to show the cell toolbar.
   Cell toolbars are only shown when the ctb_global_show class is also set.
*/
.ctb_global_show .ctb_show.ctb_hideshow {
  display: block;
}
.ctb_global_show .ctb_show + .input_area,
.ctb_global_show .ctb_show + div.text_cell_input,
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border: 1px solid #cfcfcf;
}
.celltoolbar {
  font-size: 87%;
  padding-top: 3px;
}
.celltoolbar select {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  width: inherit;
  font-size: inherit;
  height: 22px;
  padding: 0px;
  display: inline-block;
}
.celltoolbar select:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.celltoolbar select::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.celltoolbar select:-ms-input-placeholder {
  color: #999;
}
.celltoolbar select::-webkit-input-placeholder {
  color: #999;
}
.celltoolbar select::-ms-expand {
  border: 0;
  background-color: transparent;
}
.celltoolbar select[disabled],
.celltoolbar select[readonly],
fieldset[disabled] .celltoolbar select {
  background-color: #eeeeee;
  opacity: 1;
}
.celltoolbar select[disabled],
fieldset[disabled] .celltoolbar select {
  cursor: not-allowed;
}
textarea.celltoolbar select {
  height: auto;
}
select.celltoolbar select {
  height: 30px;
  line-height: 30px;
}
textarea.celltoolbar select,
select[multiple].celltoolbar select {
  height: auto;
}
.celltoolbar label {
  margin-left: 5px;
  margin-right: 5px;
}
.completions {
  position: absolute;
  z-index: 110;
  overflow: hidden;
  border: 1px solid #ababab;
  border-radius: 2px;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  line-height: 1;
}
.completions select {
  background: white;
  outline: none;
  border: none;
  padding: 0px;
  margin: 0px;
  overflow: auto;
  font-family: monospace;
  font-size: 110%;
  color: #000;
  width: auto;
}
.completions select option.context {
  color: #286090;
}
#kernel_logo_widget {
  float: right !important;
  float: right;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
#menubar {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin-top: 1px;
}
#menubar .navbar {
  border-top: 1px;
  border-radius: 0px 0px 2px 2px;
  margin-bottom: 0px;
}
#menubar .navbar-toggle {
  float: left;
  padding-top: 7px;
  padding-bottom: 7px;
  border: none;
}
#menubar .navbar-collapse {
  clear: left;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
}
.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}
.dropdown-submenu > a:after {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  content: "\f0da";
  float: right;
  color: #333333;
  margin-top: 2px;
  margin-right: -10px;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
.dropdown-submenu:hover > a:after {
  color: #262626;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
}
#notification_area {
  float: right !important;
  float: right;
  z-index: 10;
}
.indicator_area {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
#kernel_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  border-left: 1px solid;
}
#kernel_indicator .kernel_indicator_name {
  padding-left: 5px;
  padding-right: 5px;
}
#modal_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
#readonly-indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  display: none;
}
.modal_indicator:before {
  width: 1.28571429em;
  text-align: center;
}
.edit_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f040";
}
.edit_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: ' ';
}
.command_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f10c";
}
.kernel_idle_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f111";
}
.kernel_busy_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f1e2";
}
.kernel_dead_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f127";
}
.kernel_disconnected_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.pull-right {
  margin-left: .3em;
}
.notification_widget {
  color: #777;
  z-index: 10;
  background: rgba(240, 240, 240, 0.5);
  margin-right: 4px;
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget:focus,
.notification_widget.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.notification_widget:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active:hover,
.notification_widget.active:hover,
.open > .dropdown-toggle.notification_widget:hover,
.notification_widget:active:focus,
.notification_widget.active:focus,
.open > .dropdown-toggle.notification_widget:focus,
.notification_widget:active.focus,
.notification_widget.active.focus,
.open > .dropdown-toggle.notification_widget.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  background-image: none;
}
.notification_widget.disabled:hover,
.notification_widget[disabled]:hover,
fieldset[disabled] .notification_widget:hover,
.notification_widget.disabled:focus,
.notification_widget[disabled]:focus,
fieldset[disabled] .notification_widget:focus,
.notification_widget.disabled.focus,
.notification_widget[disabled].focus,
fieldset[disabled] .notification_widget.focus {
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget .badge {
  color: #fff;
  background-color: #333;
}
.notification_widget.warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning:focus,
.notification_widget.warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.notification_widget.warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active:hover,
.notification_widget.warning.active:hover,
.open > .dropdown-toggle.notification_widget.warning:hover,
.notification_widget.warning:active:focus,
.notification_widget.warning.active:focus,
.open > .dropdown-toggle.notification_widget.warning:focus,
.notification_widget.warning:active.focus,
.notification_widget.warning.active.focus,
.open > .dropdown-toggle.notification_widget.warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  background-image: none;
}
.notification_widget.warning.disabled:hover,
.notification_widget.warning[disabled]:hover,
fieldset[disabled] .notification_widget.warning:hover,
.notification_widget.warning.disabled:focus,
.notification_widget.warning[disabled]:focus,
fieldset[disabled] .notification_widget.warning:focus,
.notification_widget.warning.disabled.focus,
.notification_widget.warning[disabled].focus,
fieldset[disabled] .notification_widget.warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.notification_widget.success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success:focus,
.notification_widget.success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.notification_widget.success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active:hover,
.notification_widget.success.active:hover,
.open > .dropdown-toggle.notification_widget.success:hover,
.notification_widget.success:active:focus,
.notification_widget.success.active:focus,
.open > .dropdown-toggle.notification_widget.success:focus,
.notification_widget.success:active.focus,
.notification_widget.success.active.focus,
.open > .dropdown-toggle.notification_widget.success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  background-image: none;
}
.notification_widget.success.disabled:hover,
.notification_widget.success[disabled]:hover,
fieldset[disabled] .notification_widget.success:hover,
.notification_widget.success.disabled:focus,
.notification_widget.success[disabled]:focus,
fieldset[disabled] .notification_widget.success:focus,
.notification_widget.success.disabled.focus,
.notification_widget.success[disabled].focus,
fieldset[disabled] .notification_widget.success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.notification_widget.info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info:focus,
.notification_widget.info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.notification_widget.info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active:hover,
.notification_widget.info.active:hover,
.open > .dropdown-toggle.notification_widget.info:hover,
.notification_widget.info:active:focus,
.notification_widget.info.active:focus,
.open > .dropdown-toggle.notification_widget.info:focus,
.notification_widget.info:active.focus,
.notification_widget.info.active.focus,
.open > .dropdown-toggle.notification_widget.info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  background-image: none;
}
.notification_widget.info.disabled:hover,
.notification_widget.info[disabled]:hover,
fieldset[disabled] .notification_widget.info:hover,
.notification_widget.info.disabled:focus,
.notification_widget.info[disabled]:focus,
fieldset[disabled] .notification_widget.info:focus,
.notification_widget.info.disabled.focus,
.notification_widget.info[disabled].focus,
fieldset[disabled] .notification_widget.info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.notification_widget.danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger:focus,
.notification_widget.danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.notification_widget.danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active:hover,
.notification_widget.danger.active:hover,
.open > .dropdown-toggle.notification_widget.danger:hover,
.notification_widget.danger:active:focus,
.notification_widget.danger.active:focus,
.open > .dropdown-toggle.notification_widget.danger:focus,
.notification_widget.danger:active.focus,
.notification_widget.danger.active.focus,
.open > .dropdown-toggle.notification_widget.danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  background-image: none;
}
.notification_widget.danger.disabled:hover,
.notification_widget.danger[disabled]:hover,
fieldset[disabled] .notification_widget.danger:hover,
.notification_widget.danger.disabled:focus,
.notification_widget.danger[disabled]:focus,
fieldset[disabled] .notification_widget.danger:focus,
.notification_widget.danger.disabled.focus,
.notification_widget.danger[disabled].focus,
fieldset[disabled] .notification_widget.danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger .badge {
  color: #d9534f;
  background-color: #fff;
}
div#pager {
  background-color: #fff;
  font-size: 14px;
  line-height: 20px;
  overflow: hidden;
  display: none;
  position: fixed;
  bottom: 0px;
  width: 100%;
  max-height: 50%;
  padding-top: 8px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  /* Display over codemirror */
  z-index: 100;
  /* Hack which prevents jquery ui resizable from changing top. */
  top: auto !important;
}
div#pager pre {
  line-height: 1.21429em;
  color: #000;
  background-color: #f7f7f7;
  padding: 0.4em;
}
div#pager #pager-button-area {
  position: absolute;
  top: 8px;
  right: 20px;
}
div#pager #pager-contents {
  position: relative;
  overflow: auto;
  width: 100%;
  height: 100%;
}
div#pager #pager-contents #pager-container {
  position: relative;
  padding: 15px 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
div#pager .ui-resizable-handle {
  top: 0px;
  height: 8px;
  background: #f7f7f7;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  /* This injects handle bars (a short, wide = symbol) for 
        the resize handle. */
}
div#pager .ui-resizable-handle::after {
  content: '';
  top: 2px;
  left: 50%;
  height: 3px;
  width: 30px;
  margin-left: -15px;
  position: absolute;
  border-top: 1px solid #cfcfcf;
}
.quickhelp {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  line-height: 1.8em;
}
.shortcut_key {
  display: inline-block;
  width: 21ex;
  text-align: right;
  font-family: monospace;
}
.shortcut_descr {
  display: inline-block;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
span.save_widget {
  margin-top: 6px;
}
span.save_widget span.filename {
  height: 1em;
  line-height: 1em;
  padding: 3px;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
  }
  span.checkpoint_status,
  span.autosave_status {
    display: none;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  span.checkpoint_status {
    display: none;
  }
  span.autosave_status {
    font-size: x-small;
  }
}
.toolbar {
  padding: 0px;
  margin-left: -5px;
  margin-top: 2px;
  margin-bottom: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.toolbar select,
.toolbar label {
  width: auto;
  vertical-align: middle;
  margin-right: 2px;
  margin-bottom: 0px;
  display: inline;
  font-size: 92%;
  margin-left: 0.3em;
  margin-right: 0.3em;
  padding: 0px;
  padding-top: 3px;
}
.toolbar .btn {
  padding: 2px 8px;
}
.toolbar .btn-group {
  margin-top: 0px;
  margin-left: 5px;
}
#maintoolbar {
  margin-bottom: -3px;
  margin-top: -8px;
  border: 0px;
  min-height: 27px;
  margin-left: 0px;
  padding-top: 11px;
  padding-bottom: 3px;
}
#maintoolbar .navbar-text {
  float: none;
  vertical-align: middle;
  text-align: right;
  margin-left: 5px;
  margin-right: 0px;
  margin-top: 0px;
}
.select-xs {
  height: 24px;
}
.pulse,
.dropdown-menu > li > a.pulse,
li.pulse > a.dropdown-toggle,
li.pulse.open > a.dropdown-toggle {
  background-color: #F37626;
  color: white;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
/** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot
 * of chance of beeing generated from the ../less/[samename].less file, you can
 * try to get back the less file by reverting somme commit in history
 **/
/*
 * We'll try to get something pretty, so we
 * have some strange css to have the scroll bar on
 * the left with fix button on the top right of the tooltip
 */
@-moz-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-webkit-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/*properties of tooltip after "expand"*/
.bigtooltip {
  overflow: auto;
  height: 200px;
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
}
/*properties of tooltip before "expand"*/
.smalltooltip {
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
  text-overflow: ellipsis;
  overflow: hidden;
  height: 80px;
}
.tooltipbuttons {
  position: absolute;
  padding-right: 15px;
  top: 0px;
  right: 0px;
}
.tooltiptext {
  /*avoid the button to overlap on some docstring*/
  padding-right: 30px;
}
.ipython_tooltip {
  max-width: 700px;
  /*fade-in animation when inserted*/
  -webkit-animation: fadeOut 400ms;
  -moz-animation: fadeOut 400ms;
  animation: fadeOut 400ms;
  -webkit-animation: fadeIn 400ms;
  -moz-animation: fadeIn 400ms;
  animation: fadeIn 400ms;
  vertical-align: middle;
  background-color: #f7f7f7;
  overflow: visible;
  border: #ababab 1px solid;
  outline: none;
  padding: 3px;
  margin: 0px;
  padding-left: 7px;
  font-family: monospace;
  min-height: 50px;
  -moz-box-shadow: 0px 6px 10px -1px #adadad;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  border-radius: 2px;
  position: absolute;
  z-index: 1000;
}
.ipython_tooltip a {
  float: right;
}
.ipython_tooltip .tooltiptext pre {
  border: 0;
  border-radius: 0;
  font-size: 100%;
  background-color: #f7f7f7;
}
.pretooltiparrow {
  left: 0px;
  margin: 0px;
  top: -16px;
  width: 40px;
  height: 16px;
  overflow: hidden;
  position: absolute;
}
.pretooltiparrow:before {
  background-color: #f7f7f7;
  border: 1px #ababab solid;
  z-index: 11;
  content: "";
  position: absolute;
  left: 15px;
  top: 10px;
  width: 25px;
  height: 25px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
}
ul.typeahead-list i {
  margin-left: -10px;
  width: 18px;
}
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
}
.cmd-palette .modal-body {
  padding: 7px;
}
.cmd-palette form {
  background: white;
}
.cmd-palette input {
  outline: none;
}
.no-shortcut {
  display: none;
}
.command-shortcut:before {
  content: "(command)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .match {
  background-color: #FFCDD2;
  border-color: #EF9A9A;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .insert {
  background-color: #C8E6C9;
  border-color: #A5D6A7;
  border-radius: 0px;
}
#find-and-replace #replace-preview {
  max-height: 60vh;
  overflow: auto;
}
#find-and-replace #replace-preview pre {
  padding: 5px 10px;
}
.terminal-app {
  background: #EEE;
}
.terminal-app #header {
  background: #fff;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.terminal-app .terminal {
  width: 100%;
  float: left;
  font-family: monospace;
  color: white;
  background: black;
  padding: 0.4em;
  border-radius: 2px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
}
.terminal-app .terminal,
.terminal-app .terminal dummy-screen {
  line-height: 1em;
  font-size: 14px;
}
.terminal-app .terminal .xterm-rows {
  padding: 10px;
}
.terminal-app .terminal-cursor {
  color: black;
  background: white;
}
.terminal-app #terminado-container {
  margin-top: 20px;
}
/*# sourceMappingURL=style.min.css.map */
    </style>
<style type="text/css">
    .highlight .hll { background-color: #ffffcc }
.highlight  { background: #f8f8f8; }
.highlight .c { color: #408080; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #008000; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #BC7A00 } /* Comment.Preproc */
.highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */
.highlight .cs { color: #408080; font-style: italic } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #008000 } /* Keyword.Pseudo */
.highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #B00040 } /* Keyword.Type */
.highlight .m { color: #666666 } /* Literal.Number */
.highlight .s { color: #BA2121 } /* Literal.String */
.highlight .na { color: #7D9029 } /* Name.Attribute */
.highlight .nb { color: #008000 } /* Name.Builtin */
.highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */
.highlight .no { color: #880000 } /* Name.Constant */
.highlight .nd { color: #AA22FF } /* Name.Decorator */
.highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */
.highlight .nf { color: #0000FF } /* Name.Function */
.highlight .nl { color: #A0A000 } /* Name.Label */
.highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #19177C } /* Name.Variable */
.highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #666666 } /* Literal.Number.Bin */
.highlight .mf { color: #666666 } /* Literal.Number.Float */
.highlight .mh { color: #666666 } /* Literal.Number.Hex */
.highlight .mi { color: #666666 } /* Literal.Number.Integer */
.highlight .mo { color: #666666 } /* Literal.Number.Oct */
.highlight .sa { color: #BA2121 } /* Literal.String.Affix */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */
.highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */
.highlight .sx { color: #008000 } /* Literal.String.Other */
.highlight .sr { color: #BB6688 } /* Literal.String.Regex */
.highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.highlight .ss { color: #19177C } /* Literal.String.Symbol */
.highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.highlight .fm { color: #0000FF } /* Name.Function.Magic */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .vm { color: #19177C } /* Name.Variable.Magic */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
    </style>
<style type="text/css">
    
/* Temporary definitions which will become obsolete with Notebook release 5.0 */
.ansi-black-fg { color: #3E424D; }
.ansi-black-bg { background-color: #3E424D; }
.ansi-black-intense-fg { color: #282C36; }
.ansi-black-intense-bg { background-color: #282C36; }
.ansi-red-fg { color: #E75C58; }
.ansi-red-bg { background-color: #E75C58; }
.ansi-red-intense-fg { color: #B22B31; }
.ansi-red-intense-bg { background-color: #B22B31; }
.ansi-green-fg { color: #00A250; }
.ansi-green-bg { background-color: #00A250; }
.ansi-green-intense-fg { color: #007427; }
.ansi-green-intense-bg { background-color: #007427; }
.ansi-yellow-fg { color: #DDB62B; }
.ansi-yellow-bg { background-color: #DDB62B; }
.ansi-yellow-intense-fg { color: #B27D12; }
.ansi-yellow-intense-bg { background-color: #B27D12; }
.ansi-blue-fg { color: #208FFB; }
.ansi-blue-bg { background-color: #208FFB; }
.ansi-blue-intense-fg { color: #0065CA; }
.ansi-blue-intense-bg { background-color: #0065CA; }
.ansi-magenta-fg { color: #D160C4; }
.ansi-magenta-bg { background-color: #D160C4; }
.ansi-magenta-intense-fg { color: #A03196; }
.ansi-magenta-intense-bg { background-color: #A03196; }
.ansi-cyan-fg { color: #60C6C8; }
.ansi-cyan-bg { background-color: #60C6C8; }
.ansi-cyan-intense-fg { color: #258F8F; }
.ansi-cyan-intense-bg { background-color: #258F8F; }
.ansi-white-fg { color: #C5C1B4; }
.ansi-white-bg { background-color: #C5C1B4; }
.ansi-white-intense-fg { color: #A1A6B2; }
.ansi-white-intense-bg { background-color: #A1A6B2; }

.ansi-bold { font-weight: bold; }

    </style>


<style type="text/css">
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}@media print {
  div.cell {
    display: block;
    page-break-inside: avoid;
  } 
  div.output_wrapper { 
    display: block;
    page-break-inside: avoid; 
  }
  div.output { 
    display: block;
    page-break-inside: avoid; 
  }
}
</style>

<!-- Custom stylesheet, it must be in the same directory as the html file -->
<link rel="stylesheet" href="custom.css">

<!-- Loading mathjax macro -->
<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-AMS_HTML"></script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
        tex2jax: {
            inlineMath: [ ['$','$'], ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
            processEscapes: true,
            processEnvironments: true
        },
        // Center justify equations in code and markdown cells. Elsewhere
        // we use CSS to left justify single line equations in code cells.
        displayAlign: 'center',
        "HTML-CSS": {
            styles: {'.MathJax_Display': {"margin": 0}},
            linebreaks: { automatic: true }
        }
    });
    </script>
    <!-- End of mathjax configuration --></head>
<body>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[8]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">math</span> <span class="k">import</span> <span class="n">sqrt</span>
<span class="kn">from</span> <span class="nn">sklearn</span> <span class="k">import</span> <span class="n">neighbors</span>
<span class="kn">from</span> <span class="nn">os</span> <span class="k">import</span> <span class="n">listdir</span>
<span class="kn">from</span> <span class="nn">os.path</span> <span class="k">import</span> <span class="n">isdir</span><span class="p">,</span> <span class="n">join</span><span class="p">,</span> <span class="n">isfile</span><span class="p">,</span> <span class="n">splitext</span>
<span class="kn">import</span>  <span class="nn">pickle</span>
<span class="kn">from</span> <span class="nn">PIL</span> <span class="k">import</span> <span class="n">Image</span><span class="p">,</span> <span class="n">ImageFont</span><span class="p">,</span> <span class="n">ImageDraw</span><span class="p">,</span> <span class="n">ImageEnhance</span>
<span class="kn">import</span> <span class="nn">face_recognition</span>
<span class="kn">from</span> <span class="nn">face_recognition</span> <span class="k">import</span> <span class="n">face_locations</span>
<span class="kn">from</span> <span class="nn">face_recognition.cli</span> <span class="k">import</span> <span class="n">image_files_in_folder</span>
<span class="kn">import</span> <span class="nn">cv2</span>
<span class="kn">import</span> <span class="nn">sys</span>
<span class="kn">import</span> <span class="nn">time</span>
<span class="kn">from</span> <span class="nn">sklearn.neighbors</span> <span class="k">import</span> <span class="n">KNeighborsClassifier</span>
<span class="kn">from</span> <span class="nn">sklearn.model_selection</span> <span class="k">import</span> <span class="n">GridSearchCV</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">from</span> <span class="nn">sklearn</span> <span class="k">import</span> <span class="n">preprocessing</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">from</span> <span class="nn">sklearn.decomposition</span> <span class="k">import</span> <span class="n">PCA</span>

<span class="n">train_data_path</span> <span class="o">=</span><span class="s2">&quot;/home/kunaldargan/AitoeLabs/faceRecognition/augmentedTeacher/teachers&quot;</span>
<span class="n">model_save_path</span> <span class="o">=</span><span class="s2">&quot;/home/kunaldargan/AitoeLabs/faceRecognition/mordAugmentedTeachers.Model&quot;</span>
<span class="n">knn_algo</span> <span class="o">=</span> <span class="s1">&#39;ball_tree&#39;</span>

<span class="n">X</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">y</span> <span class="o">=</span> <span class="p">[]</span>

<span class="k">for</span> <span class="n">class_dir</span> <span class="ow">in</span> <span class="n">listdir</span><span class="p">(</span><span class="n">train_data_path</span><span class="p">):</span>
    <span class="k">if</span> <span class="ow">not</span> <span class="n">isdir</span><span class="p">(</span><span class="n">join</span><span class="p">(</span><span class="n">train_data_path</span><span class="p">,</span> <span class="n">class_dir</span><span class="p">)):</span>
        <span class="k">continue</span>
    <span class="k">for</span> <span class="n">img_path</span> <span class="ow">in</span> <span class="n">image_files_in_folder</span><span class="p">(</span><span class="n">join</span><span class="p">(</span><span class="n">train_data_path</span><span class="p">,</span> <span class="n">class_dir</span><span class="p">)):</span>
        <span class="n">image</span> <span class="o">=</span> <span class="n">face_recognition</span><span class="o">.</span><span class="n">load_image_file</span><span class="p">(</span><span class="n">img_path</span><span class="p">)</span>
        <span class="n">image</span> <span class="o">=</span> <span class="n">cv2</span><span class="o">.</span><span class="n">resize</span><span class="p">(</span><span class="n">image</span><span class="p">,</span> <span class="p">(</span><span class="mi">100</span><span class="p">,</span><span class="mi">100</span><span class="p">))</span>
        <span class="c1">#faces_bboxes = face_locations(image,2)</span>
        <span class="n">width</span><span class="p">,</span> <span class="n">height</span> <span class="o">=</span> <span class="n">image</span><span class="o">.</span><span class="n">shape</span><span class="p">[:</span><span class="mi">2</span><span class="p">]</span>
        <span class="n">faces_bboxes</span> <span class="o">=</span> <span class="p">[(</span><span class="nb">int</span><span class="p">(</span><span class="mi">0</span><span class="p">),</span><span class="nb">int</span><span class="p">(</span><span class="n">height</span><span class="p">),</span><span class="nb">int</span><span class="p">(</span><span class="n">width</span><span class="p">),</span><span class="nb">int</span><span class="p">(</span><span class="mi">0</span><span class="p">))]</span> <span class="c1">#((int(0), (int(endX) - int(startX)), (int(endY) - int(startY)),int(0))) </span>
        <span class="k">if</span> <span class="nb">len</span><span class="p">(</span><span class="n">faces_bboxes</span><span class="p">)</span> <span class="o">!=</span> <span class="mi">1</span><span class="p">:</span>
            <span class="k">continue</span>
        <span class="n">X</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">face_recognition</span><span class="o">.</span><span class="n">face_encodings</span><span class="p">(</span><span class="n">image</span><span class="p">,</span> <span class="n">known_face_locations</span><span class="o">=</span><span class="n">faces_bboxes</span><span class="p">)[</span><span class="mi">0</span><span class="p">])</span>
        <span class="n">y</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">class_dir</span><span class="p">)</span>

    <span class="n">n_neighbors</span> <span class="o">=</span> <span class="nb">int</span><span class="p">(</span><span class="nb">round</span><span class="p">(</span><span class="n">sqrt</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">X</span><span class="p">))))</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Neighbors : &quot;</span><span class="p">,</span> <span class="n">n_neighbors</span><span class="p">)</span>
    <span class="n">knn_clf</span> <span class="o">=</span> <span class="n">neighbors</span><span class="o">.</span><span class="n">KNeighborsClassifier</span><span class="p">(</span><span class="n">n_neighbors</span><span class="o">=</span><span class="n">n_neighbors</span><span class="p">,</span> <span class="n">algorithm</span><span class="o">=</span><span class="n">knn_algo</span><span class="p">,</span> <span class="n">weights</span><span class="o">=</span><span class="s1">&#39;distance&#39;</span><span class="p">)</span>
    <span class="c1">#x = preprocessing.normalize(X, norm = &#39;l2&#39;)</span>
    <span class="c1">#print(&quot; X : &quot;, x)</span>
    <span class="n">knn_clf</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">X</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>
    <span class="c1">#param_grid2 = {&#39;n_neighbors&#39;: [1,2,3,4,5,6,7], &#39;algorithm&#39; : [&#39;auto&#39;, &#39;ball_tree&#39;, &#39;kd_tree&#39;,&#39;brute&#39;], &#39;leaf_size&#39; : [20,30,40,50,60]}</span>
    <span class="c1">#knn_clf = GridSearchCV(KNeighborsClassifier(),param_grid2)</span>
    <span class="c1">#knn_clf.fit(X, y)</span>
    
    <span class="c1">#print(&quot;Best estimator found by grid search for knn:&quot;)</span>
    <span class="c1">#print(knn_clf.best_estimator_)</span>
    <span class="k">with</span> <span class="nb">open</span><span class="p">(</span><span class="n">model_save_path</span><span class="p">,</span> <span class="s1">&#39;wb&#39;</span><span class="p">)</span> <span class="k">as</span> <span class="n">f</span><span class="p">:</span>
        <span class="n">pickle</span><span class="o">.</span><span class="n">dump</span><span class="p">(</span><span class="n">knn_clf</span><span class="p">,</span> <span class="n">f</span><span class="p">)</span> <span class="c1">#protocol = 2 for python 2</span>
        
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Neighbors :  14
Neighbors :  20
Neighbors :  24
Neighbors :  28
Neighbors :  32
Neighbors :  35
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[9]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">classList</span><span class="p">(</span><span class="n">projected</span><span class="p">,</span><span class="n">y</span><span class="p">):</span>
    <span class="n">dictionary</span> <span class="o">=</span> <span class="p">{}</span>
    <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">projected</span><span class="p">)):</span>
        <span class="k">if</span> <span class="n">y</span><span class="p">[</span><span class="n">i</span><span class="p">]</span> <span class="ow">not</span> <span class="ow">in</span> <span class="n">dictionary</span><span class="p">:</span>
            <span class="n">dictionary</span><span class="p">[</span><span class="n">y</span><span class="p">[</span><span class="n">i</span><span class="p">]]</span> <span class="o">=</span> <span class="p">[</span><span class="nb">list</span><span class="p">(</span><span class="n">projected</span><span class="p">[</span><span class="n">i</span><span class="p">])]</span>
        <span class="k">else</span><span class="p">:</span>
            <span class="n">dictionary</span><span class="p">[</span><span class="n">y</span><span class="p">[</span><span class="n">i</span><span class="p">]]</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="nb">list</span><span class="p">(</span><span class="n">projected</span><span class="p">[</span><span class="n">i</span><span class="p">]))</span>
    <span class="k">return</span> <span class="n">dictionary</span>

<span class="n">pca</span> <span class="o">=</span> <span class="n">PCA</span><span class="p">(</span><span class="n">n_components</span><span class="o">=</span><span class="mi">2</span><span class="p">)</span>
<span class="n">projected</span> <span class="o">=</span> <span class="n">pca</span><span class="o">.</span><span class="n">fit_transform</span><span class="p">(</span><span class="n">X</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="nb">type</span><span class="p">(</span><span class="n">projected</span><span class="p">))</span>
<span class="nb">print</span><span class="p">(</span><span class="nb">type</span><span class="p">(</span><span class="n">projected</span><span class="p">[</span><span class="mi">0</span><span class="p">]))</span>
<span class="nb">print</span><span class="p">(</span><span class="n">pca</span><span class="o">.</span><span class="n">explained_variance_</span><span class="p">)</span>
<span class="n">fig</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">8</span><span class="p">,</span><span class="mi">8</span><span class="p">))</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">fig</span><span class="o">.</span><span class="n">add_subplot</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_xlabel</span><span class="p">(</span><span class="s1">&#39;Principal Component 1&#39;</span><span class="p">,</span> <span class="n">fontsize</span> <span class="o">=</span> <span class="mi">15</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_ylabel</span><span class="p">(</span><span class="s1">&#39;Principal Component 2&#39;</span><span class="p">,</span> <span class="n">fontsize</span> <span class="o">=</span> <span class="mi">15</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s1">&#39;2 component PCA&#39;</span><span class="p">,</span> <span class="n">fontsize</span> <span class="o">=</span> <span class="mi">20</span><span class="p">)</span>

<span class="n">projectedDict</span> <span class="o">=</span> <span class="n">classList</span><span class="p">(</span><span class="n">projected</span><span class="p">,</span><span class="n">y</span><span class="p">)</span>
<span class="n">counter</span> <span class="o">=</span> <span class="mi">0</span>
<span class="n">colors</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;blue&quot;</span><span class="p">,</span><span class="s2">&quot;green&quot;</span><span class="p">,</span><span class="s2">&quot;red&quot;</span><span class="p">,</span><span class="s2">&quot;cyan&quot;</span><span class="p">,</span><span class="s2">&quot;magenta&quot;</span><span class="p">,</span><span class="s2">&quot;yellow&quot;</span><span class="p">]</span>
<span class="nb">print</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">colors</span><span class="p">))</span>
<span class="k">for</span> <span class="n">j</span><span class="p">,</span> <span class="n">target</span> <span class="ow">in</span> <span class="nb">enumerate</span><span class="p">(</span><span class="nb">set</span><span class="p">(</span><span class="n">y</span><span class="p">)):</span>
    <span class="n">color</span> <span class="o">=</span> <span class="n">colors</span><span class="p">[</span><span class="n">j</span><span class="p">]</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="mf">0.2</span><span class="p">,</span><span class="n">color</span><span class="p">,</span> <span class="n">label</span><span class="o">=</span><span class="n">target</span><span class="p">)</span>
    <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">projectedDict</span><span class="p">[</span><span class="n">target</span><span class="p">])):</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">projectedDict</span><span class="p">[</span><span class="n">target</span><span class="p">][</span><span class="n">i</span><span class="p">][</span><span class="mi">0</span><span class="p">]</span>
                   <span class="p">,</span><span class="n">projectedDict</span><span class="p">[</span><span class="n">target</span><span class="p">][</span><span class="n">i</span><span class="p">][</span><span class="mi">1</span><span class="p">]</span>
                   <span class="p">,</span> <span class="n">c</span> <span class="o">=</span> <span class="n">color</span>
                   <span class="p">,</span> <span class="n">s</span> <span class="o">=</span> <span class="mi">50</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">loc</span><span class="o">=</span><span class="s1">&#39;center left&#39;</span><span class="p">,</span> <span class="n">bbox_to_anchor</span><span class="o">=</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mf">0.5</span><span class="p">))</span>
<span class="n">ax</span><span class="o">.</span><span class="n">grid</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>&lt;class &#39;numpy.ndarray&#39;&gt;
&lt;class &#39;numpy.ndarray&#39;&gt;
[0.04219696 0.01871465]
</pre>
</div>
</div>

<div class="output_area">

<div class="prompt"></div>





<div id="1545de16-8453-4564-a7d3-dbb9b6df1a6f"></div>
<div class="output_subarea output_javascript ">
<script type="text/javascript">
var element = $('#1545de16-8453-4564-a7d3-dbb9b6df1a6f');
/* Put everything inside the global mpl namespace */
window.mpl = {};


mpl.get_websocket_type = function() {
    if (typeof(WebSocket) !== 'undefined') {
        return WebSocket;
    } else if (typeof(MozWebSocket) !== 'undefined') {
        return MozWebSocket;
    } else {
        alert('Your browser does not have WebSocket support.' +
              'Please try Chrome, Safari or Firefox ≥ 6. ' +
              'Firefox 4 and 5 are also supported but you ' +
              'have to enable WebSockets in about:config.');
    };
}

mpl.figure = function(figure_id, websocket, ondownload, parent_element) {
    this.id = figure_id;

    this.ws = websocket;

    this.supports_binary = (this.ws.binaryType != undefined);

    if (!this.supports_binary) {
        var warnings = document.getElementById("mpl-warnings");
        if (warnings) {
            warnings.style.display = 'block';
            warnings.textContent = (
                "This browser does not support binary websocket messages. " +
                    "Performance may be slow.");
        }
    }

    this.imageObj = new Image();

    this.context = undefined;
    this.message = undefined;
    this.canvas = undefined;
    this.rubberband_canvas = undefined;
    this.rubberband_context = undefined;
    this.format_dropdown = undefined;

    this.image_mode = 'full';

    this.root = $('<div/>');
    this._root_extra_style(this.root)
    this.root.attr('style', 'display: inline-block');

    $(parent_element).append(this.root);

    this._init_header(this);
    this._init_canvas(this);
    this._init_toolbar(this);

    var fig = this;

    this.waiting = false;

    this.ws.onopen =  function () {
            fig.send_message("supports_binary", {value: fig.supports_binary});
            fig.send_message("send_image_mode", {});
            if (mpl.ratio != 1) {
                fig.send_message("set_dpi_ratio", {'dpi_ratio': mpl.ratio});
            }
            fig.send_message("refresh", {});
        }

    this.imageObj.onload = function() {
            if (fig.image_mode == 'full') {
                // Full images could contain transparency (where diff images
                // almost always do), so we need to clear the canvas so that
                // there is no ghosting.
                fig.context.clearRect(0, 0, fig.canvas.width, fig.canvas.height);
            }
            fig.context.drawImage(fig.imageObj, 0, 0);
        };

    this.imageObj.onunload = function() {
        fig.ws.close();
    }

    this.ws.onmessage = this._make_on_message_function(this);

    this.ondownload = ondownload;
}

mpl.figure.prototype._init_header = function() {
    var titlebar = $(
        '<div class="ui-dialog-titlebar ui-widget-header ui-corner-all ' +
        'ui-helper-clearfix"/>');
    var titletext = $(
        '<div class="ui-dialog-title" style="width: 100%; ' +
        'text-align: center; padding: 3px;"/>');
    titlebar.append(titletext)
    this.root.append(titlebar);
    this.header = titletext[0];
}



mpl.figure.prototype._canvas_extra_style = function(canvas_div) {

}


mpl.figure.prototype._root_extra_style = function(canvas_div) {

}

mpl.figure.prototype._init_canvas = function() {
    var fig = this;

    var canvas_div = $('<div/>');

    canvas_div.attr('style', 'position: relative; clear: both; outline: 0');

    function canvas_keyboard_event(event) {
        return fig.key_event(event, event['data']);
    }

    canvas_div.keydown('key_press', canvas_keyboard_event);
    canvas_div.keyup('key_release', canvas_keyboard_event);
    this.canvas_div = canvas_div
    this._canvas_extra_style(canvas_div)
    this.root.append(canvas_div);

    var canvas = $('<canvas/>');
    canvas.addClass('mpl-canvas');
    canvas.attr('style', "left: 0; top: 0; z-index: 0; outline: 0")

    this.canvas = canvas[0];
    this.context = canvas[0].getContext("2d");

    var backingStore = this.context.backingStorePixelRatio ||
	this.context.webkitBackingStorePixelRatio ||
	this.context.mozBackingStorePixelRatio ||
	this.context.msBackingStorePixelRatio ||
	this.context.oBackingStorePixelRatio ||
	this.context.backingStorePixelRatio || 1;

    mpl.ratio = (window.devicePixelRatio || 1) / backingStore;

    var rubberband = $('<canvas/>');
    rubberband.attr('style', "position: absolute; left: 0; top: 0; z-index: 1;")

    var pass_mouse_events = true;

    canvas_div.resizable({
        start: function(event, ui) {
            pass_mouse_events = false;
        },
        resize: function(event, ui) {
            fig.request_resize(ui.size.width, ui.size.height);
        },
        stop: function(event, ui) {
            pass_mouse_events = true;
            fig.request_resize(ui.size.width, ui.size.height);
        },
    });

    function mouse_event_fn(event) {
        if (pass_mouse_events)
            return fig.mouse_event(event, event['data']);
    }

    rubberband.mousedown('button_press', mouse_event_fn);
    rubberband.mouseup('button_release', mouse_event_fn);
    // Throttle sequential mouse events to 1 every 20ms.
    rubberband.mousemove('motion_notify', mouse_event_fn);

    rubberband.mouseenter('figure_enter', mouse_event_fn);
    rubberband.mouseleave('figure_leave', mouse_event_fn);

    canvas_div.on("wheel", function (event) {
        event = event.originalEvent;
        event['data'] = 'scroll'
        if (event.deltaY < 0) {
            event.step = 1;
        } else {
            event.step = -1;
        }
        mouse_event_fn(event);
    });

    canvas_div.append(canvas);
    canvas_div.append(rubberband);

    this.rubberband = rubberband;
    this.rubberband_canvas = rubberband[0];
    this.rubberband_context = rubberband[0].getContext("2d");
    this.rubberband_context.strokeStyle = "#000000";

    this._resize_canvas = function(width, height) {
        // Keep the size of the canvas, canvas container, and rubber band
        // canvas in synch.
        canvas_div.css('width', width)
        canvas_div.css('height', height)

        canvas.attr('width', width * mpl.ratio);
        canvas.attr('height', height * mpl.ratio);
        canvas.attr('style', 'width: ' + width + 'px; height: ' + height + 'px;');

        rubberband.attr('width', width);
        rubberband.attr('height', height);
    }

    // Set the figure to an initial 600x600px, this will subsequently be updated
    // upon first draw.
    this._resize_canvas(600, 600);

    // Disable right mouse context menu.
    $(this.rubberband_canvas).bind("contextmenu",function(e){
        return false;
    });

    function set_focus () {
        canvas.focus();
        canvas_div.focus();
    }

    window.setTimeout(set_focus, 100);
}

mpl.figure.prototype._init_toolbar = function() {
    var fig = this;

    var nav_element = $('<div/>')
    nav_element.attr('style', 'width: 100%');
    this.root.append(nav_element);

    // Define a callback function for later on.
    function toolbar_event(event) {
        return fig.toolbar_button_onclick(event['data']);
    }
    function toolbar_mouse_event(event) {
        return fig.toolbar_button_onmouseover(event['data']);
    }

    for(var toolbar_ind in mpl.toolbar_items) {
        var name = mpl.toolbar_items[toolbar_ind][0];
        var tooltip = mpl.toolbar_items[toolbar_ind][1];
        var image = mpl.toolbar_items[toolbar_ind][2];
        var method_name = mpl.toolbar_items[toolbar_ind][3];

        if (!name) {
            // put a spacer in here.
            continue;
        }
        var button = $('<button/>');
        button.addClass('ui-button ui-widget ui-state-default ui-corner-all ' +
                        'ui-button-icon-only');
        button.attr('role', 'button');
        button.attr('aria-disabled', 'false');
        button.click(method_name, toolbar_event);
        button.mouseover(tooltip, toolbar_mouse_event);

        var icon_img = $('<span/>');
        icon_img.addClass('ui-button-icon-primary ui-icon');
        icon_img.addClass(image);
        icon_img.addClass('ui-corner-all');

        var tooltip_span = $('<span/>');
        tooltip_span.addClass('ui-button-text');
        tooltip_span.html(tooltip);

        button.append(icon_img);
        button.append(tooltip_span);

        nav_element.append(button);
    }

    var fmt_picker_span = $('<span/>');

    var fmt_picker = $('<select/>');
    fmt_picker.addClass('mpl-toolbar-option ui-widget ui-widget-content');
    fmt_picker_span.append(fmt_picker);
    nav_element.append(fmt_picker_span);
    this.format_dropdown = fmt_picker[0];

    for (var ind in mpl.extensions) {
        var fmt = mpl.extensions[ind];
        var option = $(
            '<option/>', {selected: fmt === mpl.default_extension}).html(fmt);
        fmt_picker.append(option)
    }

    // Add hover states to the ui-buttons
    $( ".ui-button" ).hover(
        function() { $(this).addClass("ui-state-hover");},
        function() { $(this).removeClass("ui-state-hover");}
    );

    var status_bar = $('<span class="mpl-message"/>');
    nav_element.append(status_bar);
    this.message = status_bar[0];
}

mpl.figure.prototype.request_resize = function(x_pixels, y_pixels) {
    // Request matplotlib to resize the figure. Matplotlib will then trigger a resize in the client,
    // which will in turn request a refresh of the image.
    this.send_message('resize', {'width': x_pixels, 'height': y_pixels});
}

mpl.figure.prototype.send_message = function(type, properties) {
    properties['type'] = type;
    properties['figure_id'] = this.id;
    this.ws.send(JSON.stringify(properties));
}

mpl.figure.prototype.send_draw_message = function() {
    if (!this.waiting) {
        this.waiting = true;
        this.ws.send(JSON.stringify({type: "draw", figure_id: this.id}));
    }
}


mpl.figure.prototype.handle_save = function(fig, msg) {
    var format_dropdown = fig.format_dropdown;
    var format = format_dropdown.options[format_dropdown.selectedIndex].value;
    fig.ondownload(fig, format);
}


mpl.figure.prototype.handle_resize = function(fig, msg) {
    var size = msg['size'];
    if (size[0] != fig.canvas.width || size[1] != fig.canvas.height) {
        fig._resize_canvas(size[0], size[1]);
        fig.send_message("refresh", {});
    };
}

mpl.figure.prototype.handle_rubberband = function(fig, msg) {
    var x0 = msg['x0'] / mpl.ratio;
    var y0 = (fig.canvas.height - msg['y0']) / mpl.ratio;
    var x1 = msg['x1'] / mpl.ratio;
    var y1 = (fig.canvas.height - msg['y1']) / mpl.ratio;
    x0 = Math.floor(x0) + 0.5;
    y0 = Math.floor(y0) + 0.5;
    x1 = Math.floor(x1) + 0.5;
    y1 = Math.floor(y1) + 0.5;
    var min_x = Math.min(x0, x1);
    var min_y = Math.min(y0, y1);
    var width = Math.abs(x1 - x0);
    var height = Math.abs(y1 - y0);

    fig.rubberband_context.clearRect(
        0, 0, fig.canvas.width, fig.canvas.height);

    fig.rubberband_context.strokeRect(min_x, min_y, width, height);
}

mpl.figure.prototype.handle_figure_label = function(fig, msg) {
    // Updates the figure title.
    fig.header.textContent = msg['label'];
}

mpl.figure.prototype.handle_cursor = function(fig, msg) {
    var cursor = msg['cursor'];
    switch(cursor)
    {
    case 0:
        cursor = 'pointer';
        break;
    case 1:
        cursor = 'default';
        break;
    case 2:
        cursor = 'crosshair';
        break;
    case 3:
        cursor = 'move';
        break;
    }
    fig.rubberband_canvas.style.cursor = cursor;
}

mpl.figure.prototype.handle_message = function(fig, msg) {
    fig.message.textContent = msg['message'];
}

mpl.figure.prototype.handle_draw = function(fig, msg) {
    // Request the server to send over a new figure.
    fig.send_draw_message();
}

mpl.figure.prototype.handle_image_mode = function(fig, msg) {
    fig.image_mode = msg['mode'];
}

mpl.figure.prototype.updated_canvas_event = function() {
    // Called whenever the canvas gets updated.
    this.send_message("ack", {});
}

// A function to construct a web socket function for onmessage handling.
// Called in the figure constructor.
mpl.figure.prototype._make_on_message_function = function(fig) {
    return function socket_on_message(evt) {
        if (evt.data instanceof Blob) {
            /* FIXME: We get "Resource interpreted as Image but
             * transferred with MIME type text/plain:" errors on
             * Chrome.  But how to set the MIME type?  It doesn't seem
             * to be part of the websocket stream */
            evt.data.type = "image/png";

            /* Free the memory for the previous frames */
            if (fig.imageObj.src) {
                (window.URL || window.webkitURL).revokeObjectURL(
                    fig.imageObj.src);
            }

            fig.imageObj.src = (window.URL || window.webkitURL).createObjectURL(
                evt.data);
            fig.updated_canvas_event();
            fig.waiting = false;
            return;
        }
        else if (typeof evt.data === 'string' && evt.data.slice(0, 21) == "data:image/png;base64") {
            fig.imageObj.src = evt.data;
            fig.updated_canvas_event();
            fig.waiting = false;
            return;
        }

        var msg = JSON.parse(evt.data);
        var msg_type = msg['type'];

        // Call the  "handle_{type}" callback, which takes
        // the figure and JSON message as its only arguments.
        try {
            var callback = fig["handle_" + msg_type];
        } catch (e) {
            console.log("No handler for the '" + msg_type + "' message type: ", msg);
            return;
        }

        if (callback) {
            try {
                // console.log("Handling '" + msg_type + "' message: ", msg);
                callback(fig, msg);
            } catch (e) {
                console.log("Exception inside the 'handler_" + msg_type + "' callback:", e, e.stack, msg);
            }
        }
    };
}

// from http://stackoverflow.com/questions/1114465/getting-mouse-location-in-canvas
mpl.findpos = function(e) {
    //this section is from http://www.quirksmode.org/js/events_properties.html
    var targ;
    if (!e)
        e = window.event;
    if (e.target)
        targ = e.target;
    else if (e.srcElement)
        targ = e.srcElement;
    if (targ.nodeType == 3) // defeat Safari bug
        targ = targ.parentNode;

    // jQuery normalizes the pageX and pageY
    // pageX,Y are the mouse positions relative to the document
    // offset() returns the position of the element relative to the document
    var x = e.pageX - $(targ).offset().left;
    var y = e.pageY - $(targ).offset().top;

    return {"x": x, "y": y};
};

/*
 * return a copy of an object with only non-object keys
 * we need this to avoid circular references
 * http://stackoverflow.com/a/24161582/3208463
 */
function simpleKeys (original) {
  return Object.keys(original).reduce(function (obj, key) {
    if (typeof original[key] !== 'object')
        obj[key] = original[key]
    return obj;
  }, {});
}

mpl.figure.prototype.mouse_event = function(event, name) {
    var canvas_pos = mpl.findpos(event)

    if (name === 'button_press')
    {
        this.canvas.focus();
        this.canvas_div.focus();
    }

    var x = canvas_pos.x * mpl.ratio;
    var y = canvas_pos.y * mpl.ratio;

    this.send_message(name, {x: x, y: y, button: event.button,
                             step: event.step,
                             guiEvent: simpleKeys(event)});

    /* This prevents the web browser from automatically changing to
     * the text insertion cursor when the button is pressed.  We want
     * to control all of the cursor setting manually through the
     * 'cursor' event from matplotlib */
    event.preventDefault();
    return false;
}

mpl.figure.prototype._key_event_extra = function(event, name) {
    // Handle any extra behaviour associated with a key event
}

mpl.figure.prototype.key_event = function(event, name) {

    // Prevent repeat events
    if (name == 'key_press')
    {
        if (event.which === this._key)
            return;
        else
            this._key = event.which;
    }
    if (name == 'key_release')
        this._key = null;

    var value = '';
    if (event.ctrlKey && event.which != 17)
        value += "ctrl+";
    if (event.altKey && event.which != 18)
        value += "alt+";
    if (event.shiftKey && event.which != 16)
        value += "shift+";

    value += 'k';
    value += event.which.toString();

    this._key_event_extra(event, name);

    this.send_message(name, {key: value,
                             guiEvent: simpleKeys(event)});
    return false;
}

mpl.figure.prototype.toolbar_button_onclick = function(name) {
    if (name == 'download') {
        this.handle_save(this, null);
    } else {
        this.send_message("toolbar_button", {name: name});
    }
};

mpl.figure.prototype.toolbar_button_onmouseover = function(tooltip) {
    this.message.textContent = tooltip;
};
mpl.toolbar_items = [["Home", "Reset original view", "fa fa-home icon-home", "home"], ["Back", "Back to  previous view", "fa fa-arrow-left icon-arrow-left", "back"], ["Forward", "Forward to next view", "fa fa-arrow-right icon-arrow-right", "forward"], ["", "", "", ""], ["Pan", "Pan axes with left mouse, zoom with right", "fa fa-arrows icon-move", "pan"], ["Zoom", "Zoom to rectangle", "fa fa-square-o icon-check-empty", "zoom"], ["", "", "", ""], ["Download", "Download plot", "fa fa-floppy-o icon-save", "download"]];

mpl.extensions = ["eps", "jpeg", "pdf", "png", "ps", "raw", "svg", "tif"];

mpl.default_extension = "png";var comm_websocket_adapter = function(comm) {
    // Create a "websocket"-like object which calls the given IPython comm
    // object with the appropriate methods. Currently this is a non binary
    // socket, so there is still some room for performance tuning.
    var ws = {};

    ws.close = function() {
        comm.close()
    };
    ws.send = function(m) {
        //console.log('sending', m);
        comm.send(m);
    };
    // Register the callback with on_msg.
    comm.on_msg(function(msg) {
        //console.log('receiving', msg['content']['data'], msg);
        // Pass the mpl event to the overridden (by mpl) onmessage function.
        ws.onmessage(msg['content']['data'])
    });
    return ws;
}

mpl.mpl_figure_comm = function(comm, msg) {
    // This is the function which gets called when the mpl process
    // starts-up an IPython Comm through the "matplotlib" channel.

    var id = msg.content.data.id;
    // Get hold of the div created by the display call when the Comm
    // socket was opened in Python.
    var element = $("#" + id);
    var ws_proxy = comm_websocket_adapter(comm)

    function ondownload(figure, format) {
        window.open(figure.imageObj.src);
    }

    var fig = new mpl.figure(id, ws_proxy,
                           ondownload,
                           element.get(0));

    // Call onopen now - mpl needs it, as it is assuming we've passed it a real
    // web socket which is closed, not our websocket->open comm proxy.
    ws_proxy.onopen();

    fig.parent_element = element.get(0);
    fig.cell_info = mpl.find_output_cell("<div id='" + id + "'></div>");
    if (!fig.cell_info) {
        console.error("Failed to find cell for figure", id, fig);
        return;
    }

    var output_index = fig.cell_info[2]
    var cell = fig.cell_info[0];

};

mpl.figure.prototype.handle_close = function(fig, msg) {
    var width = fig.canvas.width/mpl.ratio
    fig.root.unbind('remove')

    // Update the output cell to use the data from the current canvas.
    fig.push_to_output();
    var dataURL = fig.canvas.toDataURL();
    // Re-enable the keyboard manager in IPython - without this line, in FF,
    // the notebook keyboard shortcuts fail.
    IPython.keyboard_manager.enable()
    $(fig.parent_element).html('<img src="' + dataURL + '" width="' + width + '">');
    fig.close_ws(fig, msg);
}

mpl.figure.prototype.close_ws = function(fig, msg){
    fig.send_message('closing', msg);
    // fig.ws.close()
}

mpl.figure.prototype.push_to_output = function(remove_interactive) {
    // Turn the data on the canvas into data in the output cell.
    var width = this.canvas.width/mpl.ratio
    var dataURL = this.canvas.toDataURL();
    this.cell_info[1]['text/html'] = '<img src="' + dataURL + '" width="' + width + '">';
}

mpl.figure.prototype.updated_canvas_event = function() {
    // Tell IPython that the notebook contents must change.
    IPython.notebook.set_dirty(true);
    this.send_message("ack", {});
    var fig = this;
    // Wait a second, then push the new image to the DOM so
    // that it is saved nicely (might be nice to debounce this).
    setTimeout(function () { fig.push_to_output() }, 1000);
}

mpl.figure.prototype._init_toolbar = function() {
    var fig = this;

    var nav_element = $('<div/>')
    nav_element.attr('style', 'width: 100%');
    this.root.append(nav_element);

    // Define a callback function for later on.
    function toolbar_event(event) {
        return fig.toolbar_button_onclick(event['data']);
    }
    function toolbar_mouse_event(event) {
        return fig.toolbar_button_onmouseover(event['data']);
    }

    for(var toolbar_ind in mpl.toolbar_items){
        var name = mpl.toolbar_items[toolbar_ind][0];
        var tooltip = mpl.toolbar_items[toolbar_ind][1];
        var image = mpl.toolbar_items[toolbar_ind][2];
        var method_name = mpl.toolbar_items[toolbar_ind][3];

        if (!name) { continue; };

        var button = $('<button class="btn btn-default" href="#" title="' + name + '"><i class="fa ' + image + ' fa-lg"></i></button>');
        button.click(method_name, toolbar_event);
        button.mouseover(tooltip, toolbar_mouse_event);
        nav_element.append(button);
    }

    // Add the status bar.
    var status_bar = $('<span class="mpl-message" style="text-align:right; float: right;"/>');
    nav_element.append(status_bar);
    this.message = status_bar[0];

    // Add the close button to the window.
    var buttongrp = $('<div class="btn-group inline pull-right"></div>');
    var button = $('<button class="btn btn-mini btn-primary" href="#" title="Stop Interaction"><i class="fa fa-power-off icon-remove icon-large"></i></button>');
    button.click(function (evt) { fig.handle_close(fig, {}); } );
    button.mouseover('Stop Interaction', toolbar_mouse_event);
    buttongrp.append(button);
    var titlebar = this.root.find($('.ui-dialog-titlebar'));
    titlebar.prepend(buttongrp);
}

mpl.figure.prototype._root_extra_style = function(el){
    var fig = this
    el.on("remove", function(){
	fig.close_ws(fig, {});
    });
}

mpl.figure.prototype._canvas_extra_style = function(el){
    // this is important to make the div 'focusable
    el.attr('tabindex', 0)
    // reach out to IPython and tell the keyboard manager to turn it's self
    // off when our div gets focus

    // location in version 3
    if (IPython.notebook.keyboard_manager) {
        IPython.notebook.keyboard_manager.register_events(el);
    }
    else {
        // location in version 2
        IPython.keyboard_manager.register_events(el);
    }

}

mpl.figure.prototype._key_event_extra = function(event, name) {
    var manager = IPython.notebook.keyboard_manager;
    if (!manager)
        manager = IPython.keyboard_manager;

    // Check for shift+enter
    if (event.shiftKey && event.which == 13) {
        this.canvas_div.blur();
        event.shiftKey = false;
        // Send a "J" for go to next cell
        event.which = 74;
        event.keyCode = 74;
        manager.command_mode();
        manager.handle_keydown(event);
    }
}

mpl.figure.prototype.handle_save = function(fig, msg) {
    fig.ondownload(fig, null);
}


mpl.find_output_cell = function(html_output) {
    // Return the cell and output element which can be found *uniquely* in the notebook.
    // Note - this is a bit hacky, but it is done because the "notebook_saving.Notebook"
    // IPython event is triggered only after the cells have been serialised, which for
    // our purposes (turning an active figure into a static one), is too late.
    var cells = IPython.notebook.get_cells();
    var ncells = cells.length;
    for (var i=0; i<ncells; i++) {
        var cell = cells[i];
        if (cell.cell_type === 'code'){
            for (var j=0; j<cell.output_area.outputs.length; j++) {
                var data = cell.output_area.outputs[j];
                if (data.data) {
                    // IPython >= 3 moved mimebundle to data attribute of output
                    data = data.data;
                }
                if (data['text/html'] == html_output) {
                    return [cell, data, j];
                }
            }
        }
    }
}

// Register the function which deals with the matplotlib target/channel.
// The kernel may be null if the page has been refreshed.
if (IPython.notebook.kernel != null) {
    IPython.notebook.kernel.comm_manager.register_target('matplotlib', mpl.mpl_figure_comm);
}

</script>
</div>

</div>

<div class="output_area">

<div class="prompt"></div>



<div class="output_html rendered_html output_subarea ">
<img src="data:image/png;base64,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" width="799.4999761730439">
</div>

</div>

<div class="output_area">

<div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>6
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[5]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">######## Non Augmented extracted teacher&#39;s face features ##############</span>

<span class="n">train_data_path</span> <span class="o">=</span><span class="s2">&quot;/home/kunaldargan/AitoeLabs/faceRecognition/MORD/teachers&quot;</span>
<span class="n">model_save_path</span> <span class="o">=</span><span class="s2">&quot;/home/kunaldargan/AitoeLabs/faceRecognition/mordNONAugmentedTeachers.Model&quot;</span>
<span class="n">knn_algo</span> <span class="o">=</span> <span class="s1">&#39;ball_tree&#39;</span>

<span class="n">X</span> <span class="o">=</span> <span class="p">[]</span>
<span class="n">y</span> <span class="o">=</span> <span class="p">[]</span>

<span class="k">for</span> <span class="n">class_dir</span> <span class="ow">in</span> <span class="n">listdir</span><span class="p">(</span><span class="n">train_data_path</span><span class="p">):</span>
    <span class="k">if</span> <span class="ow">not</span> <span class="n">isdir</span><span class="p">(</span><span class="n">join</span><span class="p">(</span><span class="n">train_data_path</span><span class="p">,</span> <span class="n">class_dir</span><span class="p">)):</span>
        <span class="k">continue</span>
    <span class="k">for</span> <span class="n">img_path</span> <span class="ow">in</span> <span class="n">image_files_in_folder</span><span class="p">(</span><span class="n">join</span><span class="p">(</span><span class="n">train_data_path</span><span class="p">,</span> <span class="n">class_dir</span><span class="p">)):</span>
        <span class="n">image</span> <span class="o">=</span> <span class="n">face_recognition</span><span class="o">.</span><span class="n">load_image_file</span><span class="p">(</span><span class="n">img_path</span><span class="p">)</span>
        <span class="n">image</span> <span class="o">=</span> <span class="n">cv2</span><span class="o">.</span><span class="n">resize</span><span class="p">(</span><span class="n">image</span><span class="p">,</span> <span class="p">(</span><span class="mi">100</span><span class="p">,</span><span class="mi">100</span><span class="p">))</span>
        <span class="c1">#faces_bboxes = face_locations(image,2)</span>
        <span class="n">width</span><span class="p">,</span> <span class="n">height</span> <span class="o">=</span> <span class="n">image</span><span class="o">.</span><span class="n">shape</span><span class="p">[:</span><span class="mi">2</span><span class="p">]</span>
        <span class="n">faces_bboxes</span> <span class="o">=</span> <span class="p">[(</span><span class="nb">int</span><span class="p">(</span><span class="mi">0</span><span class="p">),</span><span class="nb">int</span><span class="p">(</span><span class="n">height</span><span class="p">),</span><span class="nb">int</span><span class="p">(</span><span class="n">width</span><span class="p">),</span><span class="nb">int</span><span class="p">(</span><span class="mi">0</span><span class="p">))]</span> <span class="c1">#((int(0), (int(endX) - int(startX)), (int(endY) - int(startY)),int(0))) </span>
        <span class="k">if</span> <span class="nb">len</span><span class="p">(</span><span class="n">faces_bboxes</span><span class="p">)</span> <span class="o">!=</span> <span class="mi">1</span><span class="p">:</span>
            <span class="k">continue</span>
        <span class="n">X</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">face_recognition</span><span class="o">.</span><span class="n">face_encodings</span><span class="p">(</span><span class="n">image</span><span class="p">,</span> <span class="n">known_face_locations</span><span class="o">=</span><span class="n">faces_bboxes</span><span class="p">)[</span><span class="mi">0</span><span class="p">])</span>
        <span class="n">y</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">class_dir</span><span class="p">)</span>

    <span class="n">n_neighbors</span> <span class="o">=</span> <span class="nb">int</span><span class="p">(</span><span class="nb">round</span><span class="p">(</span><span class="n">sqrt</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">X</span><span class="p">))))</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Neighbors : &quot;</span><span class="p">,</span> <span class="n">n_neighbors</span><span class="p">)</span>
    <span class="n">knn_clf</span> <span class="o">=</span> <span class="n">neighbors</span><span class="o">.</span><span class="n">KNeighborsClassifier</span><span class="p">(</span><span class="n">n_neighbors</span><span class="o">=</span><span class="n">n_neighbors</span><span class="p">,</span> <span class="n">algorithm</span><span class="o">=</span><span class="n">knn_algo</span><span class="p">,</span> <span class="n">weights</span><span class="o">=</span><span class="s1">&#39;distance&#39;</span><span class="p">)</span>
    <span class="c1">#x = preprocessing.normalize(X, norm = &#39;l2&#39;)</span>
    <span class="c1">#print(&quot; X : &quot;, x)</span>
    <span class="n">knn_clf</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">X</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>
    <span class="c1">#param_grid2 = {&#39;n_neighbors&#39;: [1,2,3,4,5,6,7], &#39;algorithm&#39; : [&#39;auto&#39;, &#39;ball_tree&#39;, &#39;kd_tree&#39;,&#39;brute&#39;], &#39;leaf_size&#39; : [20,30,40,50,60]}</span>
    <span class="c1">#knn_clf = GridSearchCV(KNeighborsClassifier(),param_grid2)</span>
    <span class="c1">#knn_clf.fit(X, y)</span>
    
    <span class="c1">#print(&quot;Best estimator found by grid search for knn:&quot;)</span>
    <span class="c1">#print(knn_clf.best_estimator_)</span>
    <span class="k">with</span> <span class="nb">open</span><span class="p">(</span><span class="n">model_save_path</span><span class="p">,</span> <span class="s1">&#39;wb&#39;</span><span class="p">)</span> <span class="k">as</span> <span class="n">f</span><span class="p">:</span>
        <span class="n">pickle</span><span class="o">.</span><span class="n">dump</span><span class="p">(</span><span class="n">knn_clf</span><span class="p">,</span> <span class="n">f</span><span class="p">)</span> <span class="c1">#protocol = 2 for python 2</span>
        
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Neighbors :  8
Neighbors :  12
Neighbors :  14
Neighbors :  17
Neighbors :  18
Neighbors :  20
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[7]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">classList</span><span class="p">(</span><span class="n">projected</span><span class="p">,</span><span class="n">y</span><span class="p">):</span>
    <span class="n">dictionary</span> <span class="o">=</span> <span class="p">{}</span>
    <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">projected</span><span class="p">)):</span>
        <span class="k">if</span> <span class="n">y</span><span class="p">[</span><span class="n">i</span><span class="p">]</span> <span class="ow">not</span> <span class="ow">in</span> <span class="n">dictionary</span><span class="p">:</span>
            <span class="n">dictionary</span><span class="p">[</span><span class="n">y</span><span class="p">[</span><span class="n">i</span><span class="p">]]</span> <span class="o">=</span> <span class="p">[</span><span class="nb">list</span><span class="p">(</span><span class="n">projected</span><span class="p">[</span><span class="n">i</span><span class="p">])]</span>
        <span class="k">else</span><span class="p">:</span>
            <span class="n">dictionary</span><span class="p">[</span><span class="n">y</span><span class="p">[</span><span class="n">i</span><span class="p">]]</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="nb">list</span><span class="p">(</span><span class="n">projected</span><span class="p">[</span><span class="n">i</span><span class="p">]))</span>
    <span class="k">return</span> <span class="n">dictionary</span>

<span class="n">pca</span> <span class="o">=</span> <span class="n">PCA</span><span class="p">(</span><span class="n">n_components</span><span class="o">=</span><span class="mi">2</span><span class="p">)</span>
<span class="n">projected</span> <span class="o">=</span> <span class="n">pca</span><span class="o">.</span><span class="n">fit_transform</span><span class="p">(</span><span class="n">X</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="nb">type</span><span class="p">(</span><span class="n">projected</span><span class="p">))</span>
<span class="nb">print</span><span class="p">(</span><span class="nb">type</span><span class="p">(</span><span class="n">projected</span><span class="p">[</span><span class="mi">0</span><span class="p">]))</span>
<span class="nb">print</span><span class="p">(</span><span class="n">pca</span><span class="o">.</span><span class="n">explained_variance_</span><span class="p">)</span>
<span class="n">fig</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">8</span><span class="p">,</span><span class="mi">8</span><span class="p">))</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">fig</span><span class="o">.</span><span class="n">add_subplot</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_xlabel</span><span class="p">(</span><span class="s1">&#39;Principal Component 1&#39;</span><span class="p">,</span> <span class="n">fontsize</span> <span class="o">=</span> <span class="mi">15</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_ylabel</span><span class="p">(</span><span class="s1">&#39;Principal Component 2&#39;</span><span class="p">,</span> <span class="n">fontsize</span> <span class="o">=</span> <span class="mi">15</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s1">&#39;2 component PCA&#39;</span><span class="p">,</span> <span class="n">fontsize</span> <span class="o">=</span> <span class="mi">20</span><span class="p">)</span>

<span class="n">projectedDict</span> <span class="o">=</span> <span class="n">classList</span><span class="p">(</span><span class="n">projected</span><span class="p">,</span><span class="n">y</span><span class="p">)</span>
<span class="n">counter</span> <span class="o">=</span> <span class="mi">0</span>
<span class="n">colors</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;blue&quot;</span><span class="p">,</span><span class="s2">&quot;green&quot;</span><span class="p">,</span><span class="s2">&quot;red&quot;</span><span class="p">,</span><span class="s2">&quot;cyan&quot;</span><span class="p">,</span><span class="s2">&quot;magenta&quot;</span><span class="p">,</span><span class="s2">&quot;yellow&quot;</span><span class="p">]</span>
<span class="nb">print</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">colors</span><span class="p">))</span>
<span class="k">for</span> <span class="n">j</span><span class="p">,</span> <span class="n">target</span> <span class="ow">in</span> <span class="nb">enumerate</span><span class="p">(</span><span class="nb">set</span><span class="p">(</span><span class="n">y</span><span class="p">)):</span>
    <span class="n">color</span> <span class="o">=</span> <span class="n">colors</span><span class="p">[</span><span class="n">j</span><span class="p">]</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="mf">0.2</span><span class="p">,</span><span class="n">color</span><span class="p">,</span> <span class="n">label</span><span class="o">=</span><span class="n">target</span><span class="p">)</span>
    <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">projectedDict</span><span class="p">[</span><span class="n">target</span><span class="p">])):</span>
        <span class="n">ax</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">projectedDict</span><span class="p">[</span><span class="n">target</span><span class="p">][</span><span class="n">i</span><span class="p">][</span><span class="mi">0</span><span class="p">]</span>
                   <span class="p">,</span><span class="n">projectedDict</span><span class="p">[</span><span class="n">target</span><span class="p">][</span><span class="n">i</span><span class="p">][</span><span class="mi">1</span><span class="p">]</span>
                   <span class="p">,</span> <span class="n">c</span> <span class="o">=</span> <span class="n">color</span>
                   <span class="p">,</span> <span class="n">s</span> <span class="o">=</span> <span class="mi">50</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">loc</span><span class="o">=</span><span class="s1">&#39;center left&#39;</span><span class="p">,</span> <span class="n">bbox_to_anchor</span><span class="o">=</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mf">0.5</span><span class="p">))</span>
<span class="n">ax</span><span class="o">.</span><span class="n">grid</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>&lt;class &#39;numpy.ndarray&#39;&gt;
&lt;class &#39;numpy.ndarray&#39;&gt;
[0.04275966 0.01956499]
</pre>
</div>
</div>

<div class="output_area">

<div class="prompt"></div>





<div id="13a9d19c-7ff2-42f6-a048-de1b71b3243a"></div>
<div class="output_subarea output_javascript ">
<script type="text/javascript">
var element = $('#13a9d19c-7ff2-42f6-a048-de1b71b3243a');
/* Put everything inside the global mpl namespace */
window.mpl = {};


mpl.get_websocket_type = function() {
    if (typeof(WebSocket) !== 'undefined') {
        return WebSocket;
    } else if (typeof(MozWebSocket) !== 'undefined') {
        return MozWebSocket;
    } else {
        alert('Your browser does not have WebSocket support.' +
              'Please try Chrome, Safari or Firefox ≥ 6. ' +
              'Firefox 4 and 5 are also supported but you ' +
              'have to enable WebSockets in about:config.');
    };
}

mpl.figure = function(figure_id, websocket, ondownload, parent_element) {
    this.id = figure_id;

    this.ws = websocket;

    this.supports_binary = (this.ws.binaryType != undefined);

    if (!this.supports_binary) {
        var warnings = document.getElementById("mpl-warnings");
        if (warnings) {
            warnings.style.display = 'block';
            warnings.textContent = (
                "This browser does not support binary websocket messages. " +
                    "Performance may be slow.");
        }
    }

    this.imageObj = new Image();

    this.context = undefined;
    this.message = undefined;
    this.canvas = undefined;
    this.rubberband_canvas = undefined;
    this.rubberband_context = undefined;
    this.format_dropdown = undefined;

    this.image_mode = 'full';

    this.root = $('<div/>');
    this._root_extra_style(this.root)
    this.root.attr('style', 'display: inline-block');

    $(parent_element).append(this.root);

    this._init_header(this);
    this._init_canvas(this);
    this._init_toolbar(this);

    var fig = this;

    this.waiting = false;

    this.ws.onopen =  function () {
            fig.send_message("supports_binary", {value: fig.supports_binary});
            fig.send_message("send_image_mode", {});
            if (mpl.ratio != 1) {
                fig.send_message("set_dpi_ratio", {'dpi_ratio': mpl.ratio});
            }
            fig.send_message("refresh", {});
        }

    this.imageObj.onload = function() {
            if (fig.image_mode == 'full') {
                // Full images could contain transparency (where diff images
                // almost always do), so we need to clear the canvas so that
                // there is no ghosting.
                fig.context.clearRect(0, 0, fig.canvas.width, fig.canvas.height);
            }
            fig.context.drawImage(fig.imageObj, 0, 0);
        };

    this.imageObj.onunload = function() {
        fig.ws.close();
    }

    this.ws.onmessage = this._make_on_message_function(this);

    this.ondownload = ondownload;
}

mpl.figure.prototype._init_header = function() {
    var titlebar = $(
        '<div class="ui-dialog-titlebar ui-widget-header ui-corner-all ' +
        'ui-helper-clearfix"/>');
    var titletext = $(
        '<div class="ui-dialog-title" style="width: 100%; ' +
        'text-align: center; padding: 3px;"/>');
    titlebar.append(titletext)
    this.root.append(titlebar);
    this.header = titletext[0];
}



mpl.figure.prototype._canvas_extra_style = function(canvas_div) {

}


mpl.figure.prototype._root_extra_style = function(canvas_div) {

}

mpl.figure.prototype._init_canvas = function() {
    var fig = this;

    var canvas_div = $('<div/>');

    canvas_div.attr('style', 'position: relative; clear: both; outline: 0');

    function canvas_keyboard_event(event) {
        return fig.key_event(event, event['data']);
    }

    canvas_div.keydown('key_press', canvas_keyboard_event);
    canvas_div.keyup('key_release', canvas_keyboard_event);
    this.canvas_div = canvas_div
    this._canvas_extra_style(canvas_div)
    this.root.append(canvas_div);

    var canvas = $('<canvas/>');
    canvas.addClass('mpl-canvas');
    canvas.attr('style', "left: 0; top: 0; z-index: 0; outline: 0")

    this.canvas = canvas[0];
    this.context = canvas[0].getContext("2d");

    var backingStore = this.context.backingStorePixelRatio ||
	this.context.webkitBackingStorePixelRatio ||
	this.context.mozBackingStorePixelRatio ||
	this.context.msBackingStorePixelRatio ||
	this.context.oBackingStorePixelRatio ||
	this.context.backingStorePixelRatio || 1;

    mpl.ratio = (window.devicePixelRatio || 1) / backingStore;

    var rubberband = $('<canvas/>');
    rubberband.attr('style', "position: absolute; left: 0; top: 0; z-index: 1;")

    var pass_mouse_events = true;

    canvas_div.resizable({
        start: function(event, ui) {
            pass_mouse_events = false;
        },
        resize: function(event, ui) {
            fig.request_resize(ui.size.width, ui.size.height);
        },
        stop: function(event, ui) {
            pass_mouse_events = true;
            fig.request_resize(ui.size.width, ui.size.height);
        },
    });

    function mouse_event_fn(event) {
        if (pass_mouse_events)
            return fig.mouse_event(event, event['data']);
    }

    rubberband.mousedown('button_press', mouse_event_fn);
    rubberband.mouseup('button_release', mouse_event_fn);
    // Throttle sequential mouse events to 1 every 20ms.
    rubberband.mousemove('motion_notify', mouse_event_fn);

    rubberband.mouseenter('figure_enter', mouse_event_fn);
    rubberband.mouseleave('figure_leave', mouse_event_fn);

    canvas_div.on("wheel", function (event) {
        event = event.originalEvent;
        event['data'] = 'scroll'
        if (event.deltaY < 0) {
            event.step = 1;
        } else {
            event.step = -1;
        }
        mouse_event_fn(event);
    });

    canvas_div.append(canvas);
    canvas_div.append(rubberband);

    this.rubberband = rubberband;
    this.rubberband_canvas = rubberband[0];
    this.rubberband_context = rubberband[0].getContext("2d");
    this.rubberband_context.strokeStyle = "#000000";

    this._resize_canvas = function(width, height) {
        // Keep the size of the canvas, canvas container, and rubber band
        // canvas in synch.
        canvas_div.css('width', width)
        canvas_div.css('height', height)

        canvas.attr('width', width * mpl.ratio);
        canvas.attr('height', height * mpl.ratio);
        canvas.attr('style', 'width: ' + width + 'px; height: ' + height + 'px;');

        rubberband.attr('width', width);
        rubberband.attr('height', height);
    }

    // Set the figure to an initial 600x600px, this will subsequently be updated
    // upon first draw.
    this._resize_canvas(600, 600);

    // Disable right mouse context menu.
    $(this.rubberband_canvas).bind("contextmenu",function(e){
        return false;
    });

    function set_focus () {
        canvas.focus();
        canvas_div.focus();
    }

    window.setTimeout(set_focus, 100);
}

mpl.figure.prototype._init_toolbar = function() {
    var fig = this;

    var nav_element = $('<div/>')
    nav_element.attr('style', 'width: 100%');
    this.root.append(nav_element);

    // Define a callback function for later on.
    function toolbar_event(event) {
        return fig.toolbar_button_onclick(event['data']);
    }
    function toolbar_mouse_event(event) {
        return fig.toolbar_button_onmouseover(event['data']);
    }

    for(var toolbar_ind in mpl.toolbar_items) {
        var name = mpl.toolbar_items[toolbar_ind][0];
        var tooltip = mpl.toolbar_items[toolbar_ind][1];
        var image = mpl.toolbar_items[toolbar_ind][2];
        var method_name = mpl.toolbar_items[toolbar_ind][3];

        if (!name) {
            // put a spacer in here.
            continue;
        }
        var button = $('<button/>');
        button.addClass('ui-button ui-widget ui-state-default ui-corner-all ' +
                        'ui-button-icon-only');
        button.attr('role', 'button');
        button.attr('aria-disabled', 'false');
        button.click(method_name, toolbar_event);
        button.mouseover(tooltip, toolbar_mouse_event);

        var icon_img = $('<span/>');
        icon_img.addClass('ui-button-icon-primary ui-icon');
        icon_img.addClass(image);
        icon_img.addClass('ui-corner-all');

        var tooltip_span = $('<span/>');
        tooltip_span.addClass('ui-button-text');
        tooltip_span.html(tooltip);

        button.append(icon_img);
        button.append(tooltip_span);

        nav_element.append(button);
    }

    var fmt_picker_span = $('<span/>');

    var fmt_picker = $('<select/>');
    fmt_picker.addClass('mpl-toolbar-option ui-widget ui-widget-content');
    fmt_picker_span.append(fmt_picker);
    nav_element.append(fmt_picker_span);
    this.format_dropdown = fmt_picker[0];

    for (var ind in mpl.extensions) {
        var fmt = mpl.extensions[ind];
        var option = $(
            '<option/>', {selected: fmt === mpl.default_extension}).html(fmt);
        fmt_picker.append(option)
    }

    // Add hover states to the ui-buttons
    $( ".ui-button" ).hover(
        function() { $(this).addClass("ui-state-hover");},
        function() { $(this).removeClass("ui-state-hover");}
    );

    var status_bar = $('<span class="mpl-message"/>');
    nav_element.append(status_bar);
    this.message = status_bar[0];
}

mpl.figure.prototype.request_resize = function(x_pixels, y_pixels) {
    // Request matplotlib to resize the figure. Matplotlib will then trigger a resize in the client,
    // which will in turn request a refresh of the image.
    this.send_message('resize', {'width': x_pixels, 'height': y_pixels});
}

mpl.figure.prototype.send_message = function(type, properties) {
    properties['type'] = type;
    properties['figure_id'] = this.id;
    this.ws.send(JSON.stringify(properties));
}

mpl.figure.prototype.send_draw_message = function() {
    if (!this.waiting) {
        this.waiting = true;
        this.ws.send(JSON.stringify({type: "draw", figure_id: this.id}));
    }
}


mpl.figure.prototype.handle_save = function(fig, msg) {
    var format_dropdown = fig.format_dropdown;
    var format = format_dropdown.options[format_dropdown.selectedIndex].value;
    fig.ondownload(fig, format);
}


mpl.figure.prototype.handle_resize = function(fig, msg) {
    var size = msg['size'];
    if (size[0] != fig.canvas.width || size[1] != fig.canvas.height) {
        fig._resize_canvas(size[0], size[1]);
        fig.send_message("refresh", {});
    };
}

mpl.figure.prototype.handle_rubberband = function(fig, msg) {
    var x0 = msg['x0'] / mpl.ratio;
    var y0 = (fig.canvas.height - msg['y0']) / mpl.ratio;
    var x1 = msg['x1'] / mpl.ratio;
    var y1 = (fig.canvas.height - msg['y1']) / mpl.ratio;
    x0 = Math.floor(x0) + 0.5;
    y0 = Math.floor(y0) + 0.5;
    x1 = Math.floor(x1) + 0.5;
    y1 = Math.floor(y1) + 0.5;
    var min_x = Math.min(x0, x1);
    var min_y = Math.min(y0, y1);
    var width = Math.abs(x1 - x0);
    var height = Math.abs(y1 - y0);

    fig.rubberband_context.clearRect(
        0, 0, fig.canvas.width, fig.canvas.height);

    fig.rubberband_context.strokeRect(min_x, min_y, width, height);
}

mpl.figure.prototype.handle_figure_label = function(fig, msg) {
    // Updates the figure title.
    fig.header.textContent = msg['label'];
}

mpl.figure.prototype.handle_cursor = function(fig, msg) {
    var cursor = msg['cursor'];
    switch(cursor)
    {
    case 0:
        cursor = 'pointer';
        break;
    case 1:
        cursor = 'default';
        break;
    case 2:
        cursor = 'crosshair';
        break;
    case 3:
        cursor = 'move';
        break;
    }
    fig.rubberband_canvas.style.cursor = cursor;
}

mpl.figure.prototype.handle_message = function(fig, msg) {
    fig.message.textContent = msg['message'];
}

mpl.figure.prototype.handle_draw = function(fig, msg) {
    // Request the server to send over a new figure.
    fig.send_draw_message();
}

mpl.figure.prototype.handle_image_mode = function(fig, msg) {
    fig.image_mode = msg['mode'];
}

mpl.figure.prototype.updated_canvas_event = function() {
    // Called whenever the canvas gets updated.
    this.send_message("ack", {});
}

// A function to construct a web socket function for onmessage handling.
// Called in the figure constructor.
mpl.figure.prototype._make_on_message_function = function(fig) {
    return function socket_on_message(evt) {
        if (evt.data instanceof Blob) {
            /* FIXME: We get "Resource interpreted as Image but
             * transferred with MIME type text/plain:" errors on
             * Chrome.  But how to set the MIME type?  It doesn't seem
             * to be part of the websocket stream */
            evt.data.type = "image/png";

            /* Free the memory for the previous frames */
            if (fig.imageObj.src) {
                (window.URL || window.webkitURL).revokeObjectURL(
                    fig.imageObj.src);
            }

            fig.imageObj.src = (window.URL || window.webkitURL).createObjectURL(
                evt.data);
            fig.updated_canvas_event();
            fig.waiting = false;
            return;
        }
        else if (typeof evt.data === 'string' && evt.data.slice(0, 21) == "data:image/png;base64") {
            fig.imageObj.src = evt.data;
            fig.updated_canvas_event();
            fig.waiting = false;
            return;
        }

        var msg = JSON.parse(evt.data);
        var msg_type = msg['type'];

        // Call the  "handle_{type}" callback, which takes
        // the figure and JSON message as its only arguments.
        try {
            var callback = fig["handle_" + msg_type];
        } catch (e) {
            console.log("No handler for the '" + msg_type + "' message type: ", msg);
            return;
        }

        if (callback) {
            try {
                // console.log("Handling '" + msg_type + "' message: ", msg);
                callback(fig, msg);
            } catch (e) {
                console.log("Exception inside the 'handler_" + msg_type + "' callback:", e, e.stack, msg);
            }
        }
    };
}

// from http://stackoverflow.com/questions/1114465/getting-mouse-location-in-canvas
mpl.findpos = function(e) {
    //this section is from http://www.quirksmode.org/js/events_properties.html
    var targ;
    if (!e)
        e = window.event;
    if (e.target)
        targ = e.target;
    else if (e.srcElement)
        targ = e.srcElement;
    if (targ.nodeType == 3) // defeat Safari bug
        targ = targ.parentNode;

    // jQuery normalizes the pageX and pageY
    // pageX,Y are the mouse positions relative to the document
    // offset() returns the position of the element relative to the document
    var x = e.pageX - $(targ).offset().left;
    var y = e.pageY - $(targ).offset().top;

    return {"x": x, "y": y};
};

/*
 * return a copy of an object with only non-object keys
 * we need this to avoid circular references
 * http://stackoverflow.com/a/24161582/3208463
 */
function simpleKeys (original) {
  return Object.keys(original).reduce(function (obj, key) {
    if (typeof original[key] !== 'object')
        obj[key] = original[key]
    return obj;
  }, {});
}

mpl.figure.prototype.mouse_event = function(event, name) {
    var canvas_pos = mpl.findpos(event)

    if (name === 'button_press')
    {
        this.canvas.focus();
        this.canvas_div.focus();
    }

    var x = canvas_pos.x * mpl.ratio;
    var y = canvas_pos.y * mpl.ratio;

    this.send_message(name, {x: x, y: y, button: event.button,
                             step: event.step,
                             guiEvent: simpleKeys(event)});

    /* This prevents the web browser from automatically changing to
     * the text insertion cursor when the button is pressed.  We want
     * to control all of the cursor setting manually through the
     * 'cursor' event from matplotlib */
    event.preventDefault();
    return false;
}

mpl.figure.prototype._key_event_extra = function(event, name) {
    // Handle any extra behaviour associated with a key event
}

mpl.figure.prototype.key_event = function(event, name) {

    // Prevent repeat events
    if (name == 'key_press')
    {
        if (event.which === this._key)
            return;
        else
            this._key = event.which;
    }
    if (name == 'key_release')
        this._key = null;

    var value = '';
    if (event.ctrlKey && event.which != 17)
        value += "ctrl+";
    if (event.altKey && event.which != 18)
        value += "alt+";
    if (event.shiftKey && event.which != 16)
        value += "shift+";

    value += 'k';
    value += event.which.toString();

    this._key_event_extra(event, name);

    this.send_message(name, {key: value,
                             guiEvent: simpleKeys(event)});
    return false;
}

mpl.figure.prototype.toolbar_button_onclick = function(name) {
    if (name == 'download') {
        this.handle_save(this, null);
    } else {
        this.send_message("toolbar_button", {name: name});
    }
};

mpl.figure.prototype.toolbar_button_onmouseover = function(tooltip) {
    this.message.textContent = tooltip;
};
mpl.toolbar_items = [["Home", "Reset original view", "fa fa-home icon-home", "home"], ["Back", "Back to  previous view", "fa fa-arrow-left icon-arrow-left", "back"], ["Forward", "Forward to next view", "fa fa-arrow-right icon-arrow-right", "forward"], ["", "", "", ""], ["Pan", "Pan axes with left mouse, zoom with right", "fa fa-arrows icon-move", "pan"], ["Zoom", "Zoom to rectangle", "fa fa-square-o icon-check-empty", "zoom"], ["", "", "", ""], ["Download", "Download plot", "fa fa-floppy-o icon-save", "download"]];

mpl.extensions = ["eps", "jpeg", "pdf", "png", "ps", "raw", "svg", "tif"];

mpl.default_extension = "png";var comm_websocket_adapter = function(comm) {
    // Create a "websocket"-like object which calls the given IPython comm
    // object with the appropriate methods. Currently this is a non binary
    // socket, so there is still some room for performance tuning.
    var ws = {};

    ws.close = function() {
        comm.close()
    };
    ws.send = function(m) {
        //console.log('sending', m);
        comm.send(m);
    };
    // Register the callback with on_msg.
    comm.on_msg(function(msg) {
        //console.log('receiving', msg['content']['data'], msg);
        // Pass the mpl event to the overridden (by mpl) onmessage function.
        ws.onmessage(msg['content']['data'])
    });
    return ws;
}

mpl.mpl_figure_comm = function(comm, msg) {
    // This is the function which gets called when the mpl process
    // starts-up an IPython Comm through the "matplotlib" channel.

    var id = msg.content.data.id;
    // Get hold of the div created by the display call when the Comm
    // socket was opened in Python.
    var element = $("#" + id);
    var ws_proxy = comm_websocket_adapter(comm)

    function ondownload(figure, format) {
        window.open(figure.imageObj.src);
    }

    var fig = new mpl.figure(id, ws_proxy,
                           ondownload,
                           element.get(0));

    // Call onopen now - mpl needs it, as it is assuming we've passed it a real
    // web socket which is closed, not our websocket->open comm proxy.
    ws_proxy.onopen();

    fig.parent_element = element.get(0);
    fig.cell_info = mpl.find_output_cell("<div id='" + id + "'></div>");
    if (!fig.cell_info) {
        console.error("Failed to find cell for figure", id, fig);
        return;
    }

    var output_index = fig.cell_info[2]
    var cell = fig.cell_info[0];

};

mpl.figure.prototype.handle_close = function(fig, msg) {
    var width = fig.canvas.width/mpl.ratio
    fig.root.unbind('remove')

    // Update the output cell to use the data from the current canvas.
    fig.push_to_output();
    var dataURL = fig.canvas.toDataURL();
    // Re-enable the keyboard manager in IPython - without this line, in FF,
    // the notebook keyboard shortcuts fail.
    IPython.keyboard_manager.enable()
    $(fig.parent_element).html('<img src="' + dataURL + '" width="' + width + '">');
    fig.close_ws(fig, msg);
}

mpl.figure.prototype.close_ws = function(fig, msg){
    fig.send_message('closing', msg);
    // fig.ws.close()
}

mpl.figure.prototype.push_to_output = function(remove_interactive) {
    // Turn the data on the canvas into data in the output cell.
    var width = this.canvas.width/mpl.ratio
    var dataURL = this.canvas.toDataURL();
    this.cell_info[1]['text/html'] = '<img src="' + dataURL + '" width="' + width + '">';
}

mpl.figure.prototype.updated_canvas_event = function() {
    // Tell IPython that the notebook contents must change.
    IPython.notebook.set_dirty(true);
    this.send_message("ack", {});
    var fig = this;
    // Wait a second, then push the new image to the DOM so
    // that it is saved nicely (might be nice to debounce this).
    setTimeout(function () { fig.push_to_output() }, 1000);
}

mpl.figure.prototype._init_toolbar = function() {
    var fig = this;

    var nav_element = $('<div/>')
    nav_element.attr('style', 'width: 100%');
    this.root.append(nav_element);

    // Define a callback function for later on.
    function toolbar_event(event) {
        return fig.toolbar_button_onclick(event['data']);
    }
    function toolbar_mouse_event(event) {
        return fig.toolbar_button_onmouseover(event['data']);
    }

    for(var toolbar_ind in mpl.toolbar_items){
        var name = mpl.toolbar_items[toolbar_ind][0];
        var tooltip = mpl.toolbar_items[toolbar_ind][1];
        var image = mpl.toolbar_items[toolbar_ind][2];
        var method_name = mpl.toolbar_items[toolbar_ind][3];

        if (!name) { continue; };

        var button = $('<button class="btn btn-default" href="#" title="' + name + '"><i class="fa ' + image + ' fa-lg"></i></button>');
        button.click(method_name, toolbar_event);
        button.mouseover(tooltip, toolbar_mouse_event);
        nav_element.append(button);
    }

    // Add the status bar.
    var status_bar = $('<span class="mpl-message" style="text-align:right; float: right;"/>');
    nav_element.append(status_bar);
    this.message = status_bar[0];

    // Add the close button to the window.
    var buttongrp = $('<div class="btn-group inline pull-right"></div>');
    var button = $('<button class="btn btn-mini btn-primary" href="#" title="Stop Interaction"><i class="fa fa-power-off icon-remove icon-large"></i></button>');
    button.click(function (evt) { fig.handle_close(fig, {}); } );
    button.mouseover('Stop Interaction', toolbar_mouse_event);
    buttongrp.append(button);
    var titlebar = this.root.find($('.ui-dialog-titlebar'));
    titlebar.prepend(buttongrp);
}

mpl.figure.prototype._root_extra_style = function(el){
    var fig = this
    el.on("remove", function(){
	fig.close_ws(fig, {});
    });
}

mpl.figure.prototype._canvas_extra_style = function(el){
    // this is important to make the div 'focusable
    el.attr('tabindex', 0)
    // reach out to IPython and tell the keyboard manager to turn it's self
    // off when our div gets focus

    // location in version 3
    if (IPython.notebook.keyboard_manager) {
        IPython.notebook.keyboard_manager.register_events(el);
    }
    else {
        // location in version 2
        IPython.keyboard_manager.register_events(el);
    }

}

mpl.figure.prototype._key_event_extra = function(event, name) {
    var manager = IPython.notebook.keyboard_manager;
    if (!manager)
        manager = IPython.keyboard_manager;

    // Check for shift+enter
    if (event.shiftKey && event.which == 13) {
        this.canvas_div.blur();
        event.shiftKey = false;
        // Send a "J" for go to next cell
        event.which = 74;
        event.keyCode = 74;
        manager.command_mode();
        manager.handle_keydown(event);
    }
}

mpl.figure.prototype.handle_save = function(fig, msg) {
    fig.ondownload(fig, null);
}


mpl.find_output_cell = function(html_output) {
    // Return the cell and output element which can be found *uniquely* in the notebook.
    // Note - this is a bit hacky, but it is done because the "notebook_saving.Notebook"
    // IPython event is triggered only after the cells have been serialised, which for
    // our purposes (turning an active figure into a static one), is too late.
    var cells = IPython.notebook.get_cells();
    var ncells = cells.length;
    for (var i=0; i<ncells; i++) {
        var cell = cells[i];
        if (cell.cell_type === 'code'){
            for (var j=0; j<cell.output_area.outputs.length; j++) {
                var data = cell.output_area.outputs[j];
                if (data.data) {
                    // IPython >= 3 moved mimebundle to data attribute of output
                    data = data.data;
                }
                if (data['text/html'] == html_output) {
                    return [cell, data, j];
                }
            }
        }
    }
}

// Register the function which deals with the matplotlib target/channel.
// The kernel may be null if the page has been refreshed.
if (IPython.notebook.kernel != null) {
    IPython.notebook.kernel.comm_manager.register_target('matplotlib', mpl.mpl_figure_comm);
}

</script>
</div>

</div>

<div class="output_area">

<div class="prompt"></div>



<div class="output_html rendered_html output_subarea ">
<img src="data:image/png;base64,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/+KLLxxyss022zih9f/+97+4/fbbcffdd2OHHXbA0UcfDSICt956a2consLsdKUm/v33398hSOedd54zkZEMyif57ne/i5deeskhQXRRXsnw4cOdCZBC+AcffLAz+d1xxx0oLS3Fiy++CCInbtn/8z//g/fff98ZI028JI8mehrXzJkzO/Gj5QQiDvSFTlEAwowm60cffdRZavrrX/+Kc845p7M9EYh99tnH0aG2thbf+973QLYh3ffee28HXyIlqaWHiy66CGPGjMHYsWM7ZdB9uS4/UvHaa6+BMKM8CRob+cHIkSNx6qmnOripXB999JGDy5VXXumQNfKT3Xff3cnbIYLBFyOwpSDApGJLsSTrYRQBClNTuJqiBGeeeaZQNk2UFCKn0DdNlu6LyAVNfHSdfvrpoLV7mpRockpd9NVOX+T0R5MxXSlSQUl9tE6f+uJvbm52JiSKctAEPGXKlE45qRA7Ld/QBO+e+GmCpsmRCE/qoigFTWz01UzRE7omTJiA3//+97juuuvwv//7v51tKZmRJmCaWGlsbtkUmaAJ3h3FoLERWSKyQaF+um677TYn6pCpP0UJjjnmGIewEPFKESIaM/1RXoM7+ZKiLTRBP/300xg9enTaWHRzKghPuiingoge5U0QCSN8aSksNfZbbrkFF198sdAn3A2uvvpqB093ZOLII4/E22+/DSIc3bt3V5LHjRmBuCLApCKuluFxRYZAasI6/vjjHWJBk1quiyIRtIRBkzVNin4XkQtaRiCSQLtO3BdNqjTx0sRGyxhEQlKkgiZ9GpP7ovX6f//732kTNv1OYyHyQRPizTffnDbZ0o4W2uXivtavX++MnUjKW2+95fxEkQtavqGxEFlwXz/84Q/x3HPPOb9RPkEqCkJ5Bvfff39a20ceecTJSSGyRXkJdFGUhqIuREAyr8cff9yJ3riJAmFPUZP58+enNadcGJJFE/3555+fpqcuqcgcD+XZ/PrXv3b+6CJScNVVVzlEicYpe1F0hnYU0TIKkaPUlcrP+L//+z9nGYovRmBLQIBJxZZgRdbBGAKUA0D5CvRVTGF72g0iul5++WVQ+J++wGknid+1fPlyZx2eJhCaSDIv+ndaJqF2tKSRIhV///vf8bOf/SytOUVP7rnnHmcrI22BdF80EdPvFGWhKzXxUw4G5SFkXrS8QDkDFAGhi5IM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" width="799.4999761730439">
</div>

</div>

<div class="output_area">

<div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>6
</pre>
</div>
</div>

</div>
</div>

</div>
    </div>
  </div>
</body>

</html>


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Kunaldargan/kdargan.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
