s document has been created with Marked.app <http://markedapp.com>, Copyright 2011 Brett Terpstra
Please leave this notice in place, along with any additional credits below.
---------------------------------------------------------------
Title: Avenue
Author: Bram de Haan <http://atelierbramdehaan.nl>
Description: modern retro
 */

* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, img, ins, kbd, q, s, samp, small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li, fieldset, form, label, legend, table, caption, tbody, tfoot, thead, tr, th, td, article, aside, canvas, details, embed, figure, figcaption, footer, header, hgroup, menu, nav, output, ruby, section, summary, time, mark, audio, video {
  margin: 0;
  padding: 0;
  border: 0;
  font: inherit;
  font-size: 100%;
  vertical-align: baseline;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
caption, th, td {
  text-align: left;
  font-weight: normal;
  vertical-align: middle;
}
q, blockquote {
  quotes: none;
}
q:before, q:after, blockquote:before, blockquote:after {
  content: "";
  content: none;
}
a img {
  border: none;
}
article, aside, details, figcaption, figure, footer, header, hgroup, menu, nav, section, summary {
  display: block;
}
button, input {
  line-height: normal;
}
button, input, select, textarea {
  font-size: 100%;
  margin: 0;
  vertical-align: baseline;
  /* vertical-align: middle; */
}
button, input[type="button"], input[type="reset"], input[type="submit"] {
  cursor: pointer;
  /* overflow: visible; */
}
button::-moz-focus-inner, input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
  vertical-align: top;
  resize: vertical;
}
body {
  -webkit-font-smoothing: antialiased;
  padding: 0 !important;
}
#wrapper {
  margin-bottom: 0;
}
#wrapper img {
  max-width: 100%;
  height: auto;
}
#wrapper dd {
  margin-bottom: 1em;
}
#wrapper li > p:first-child {
  margin: 0;
}
#wrapper caption, #wrapper col, #wrapper colgroup, #wrapper table, #wrapper tbody, #wrapper td, #wrapper tfoot, #wrapper th, #wrapper thead, #wrapper tr {
  border-spacing: 0;
}
#wrapper table {
  border: 1px solid rgba(0, 0, 0, 0.25);
  border-collapse: collapse;
  display: table;
  empty-cells: hide;
  margin: -1px 0 23px;
  padding: 0;
  table-layout: fixed;
  width: 100%;
}
#wrapper caption {
  display: table-caption;
  font-weight: 700;
}
#wrapper col {
  display: table-column;
}
#wrapper colgroup {
  display: table-column-group;
}
#wrapper tbody {
  display: table-row-group;
}
#wrapper tfoot {
  display: table-footer-group;
}
#wrapper thead {
  display: table-header-group;
  border-bottom: solid 1px #999;
}
#wrapper td, #wrapper th {
  display: table-cell;
}
#wrapper tr {
  display: table-row;
}
#wrapper table th, #wrapper table td {
  font-size: 1.1rem;
  line-height: 1.5;
  padding: 0 1em;
}
#wrapper dt, #wrapper th {
  font-weight: 700;
}
#wrapper dd {
  padding-left: 1.4em;
}
#wrapper table tr:nth-child(even) {
  background: rgba(200, 200, 200, 0.25);
}
#wrapper figure {
  display: inline-block;
  position: relative;
  margin: 1em 0 2em;
}
#wrapper figcaption {
  font-family: AvenirNext-Italic, AvenirNext-Regular, Futura, "Century Gothic", AppleGothic, Corbel, "Myriad Pro", "Lucida Grande", "Trebuchet Ms", sans-serif;
  font-style: italic;
  text-align: center;
}
#wrapper figure:hover > figcaption {
  /* background: rgba(0,0,0,1) */
} 
#wrapper pre {
  display: block;
  margin: 1.4em auto;
  background: #FAF8F5;
  padding: 15px 10px 10px;
  -webkit-border-radius: 8px;
  -moz-border-radius: 8px;
  -ms-border-radius: 8px;
  -o-border-radius: 8px;
  border-radius: 8px;
  border: solid 1px #ddd;
  font-family: Consolas, Menlo, Monaco, monospace !important;
  font-size: .875rem;
  max-width: 90%;
}
.poetry #wrapper pre {
  display: block;
  font-family: Georgia, Garamond, serif !important;
  font-size: 110% !important;
  font-style: italic;
  line-height: 1.6;
  margin-left: 1em;
}
.poetry #wrapper pre code {
  font-family: Georgia, Garamond, serif !important;

}
#wrapper sup, #wrapper sub, #wrapper a.footnote {
  font-size: 1.4ex;
  height: 0;
  line-height: 1;
  position: relative;
  vertical-align: super;
}
#wrapper sub {
  vertical-align: sub;
  top: -1px;
}
#wrapper .footnote {
  font-size: .8rem;
  vertical-align: super;
}
#wrapper .footnotes p {
  font-size: 1.9ex;
}
#wrapper ul ul {
  margin-left: 1em;
}

@media print {
  body {
    overflow: auto;
  }

  img, pre, blockquote, table, figure, p {
    page-break-inside: avoid;
  }

  #wrapper {
    background: #fff;
    color: #111;
    font-size: 85%;
    padding: 10px;
    position: relative;
    text-indent: 0;
  }
}

@media screen {
  .inverted #wrapper, .inverted {
    background: #222;
  }

  .inverted hr {
    border-color: #999 !important;
  }

  .inverted p, .inverted td, .inverted li, .inverted h1, .inverted h2, .inverted h3, .inverted h4, .inverted h5, .inverted h6, .inverted pre, .inverted code, .inverted th, .inverted .math, .inverted caption, .inverted dd, .inverted dt {
    color: #eee !important;
  }

  .inverted table tr:nth-child(odd), .inverted table th:nth-child(odd), .inverted table td:nth-child(odd) {
    background: none;
  }

  .inverted a {
    color: #ff5778;
  }
}
.max-width {
  max-width: 100%;
  height: auto;
}
/* ::Base styles Almost exclusively single element selectors */
/* ------------------------------------------------------------ */
html {
  font-size: 100%;
}
body {
  font: 100%/1.388 AvenirNext-Regular, Futura, "Century Gothic", AppleGothic, Corbel, "Myriad Pro", "Lucida Grande", "Trebuchet Ms", sans-serif;
  color: #111;
  padding: 0 5% 1rem !important;
}
a {
  color: crimson;
}
a:hover, a:focus, a:active {
  color: #ff2450;
}
h1, h2, h3, h4, h5, h6 {
  font-family: AvenirNextCondensed-DemiBold, AvenirNext-Regular, Futura, "Century Gothic", AppleGothic, Corbel, "Myriad Pro", "Lucida Grande", "Trebuchet Ms", sans-serif;
  /* margin: 0; */
  padding: .5em 0 0;
}
h2, h3, h4, h5 {
  border-bottom: 1px solid #777;
}
h1 {
  font-size: 2.25rem;
  line-height: 1.11111;
}
h2 {
  font-size: 1.875rem;
  line-height: 1.33333;
}
h3 {
  font-size: 1.375rem;
  line-height: 1.45455;
}
h4 {
  font-size: 1.25rem;
  line-height: 1.2;
}
h5 {
  font-size: 1.125rem;
  line-height: 1.33333;
}
h6 {
  font-size: 1rem;
  line-height: 1.5;
}
pre, label {
  font-size: 1rem;
  line-height: 1.5;
}
p {
  font-size: 1.388rem;
  line-height: 1.33333;
  /* margin: 0; */
  padding: .5em 0;
  max-width: 30em;
}
h2 + p,
h3 + p,
h4 + p,
h5 + p {
  padding-top: 0;
  margin-top: 1px;
  border-top: 1px solid #999;
}
ol, ul {
  font-size: 1rem;
  line-height: 1.5;
  margin: 0 0 2em 0;
}
li {
  line-height: auto;
}
ul {
  list-style-position: outside;
  list-style-type: square;
}
ol {
  list-style-position: outside;
  list-style-type: decimal;
}
strong, b {
  font-family: AvenirNext-Bold, AvenirNextCondensed-DemiBold, AvenirNext-Regular, Futura, "Century Gothic", AppleGothic, Corbel, "Myriad Pro", "Lucida Grande", "Trebuchet Ms", sans-serif;
  font-weight: 600;
}
em, i, q {
  font-family: AvenirNext-BoldItalic, AvenirNext-Italic, AvenirNext-Regular, Futura, "Century Gothic", AppleGothic, Corbel, "Myriad Pro", "Lucida Grande", "Trebuchet Ms", sans-serif;
  font-style: italic;
}
blockquote {
  padding-left: 1em;
  border-left: 0.3125em solid #c0c0c0;
  line-height: normal;
  /* margin: 0; */
}
blockquote p {
  font-family: AvenirNext-Italic, AvenirNext-Regular, Futura, "Century Gothic", AppleGothic, Corbel, "Myriad Pro", "Lucida Grande", "Trebuchet Ms", sans-serif;
  font-style: italic;
  /* margin: 0; */
  font-size: 1.25rem;
  line-height: 1.2;
  margin: 1.2em 0 1.2em 0;
}

@media screen and (max-width: 750px) {
  -webkit-text-size-adjust: none;
}

