## Hi there 👋
<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Life OS</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 10px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.collection-content td {
	white-space: pre-wrap;
	word-break: break-word;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	padding-inline-start: 0;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.page-description {
	margin-bottom: 2em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-flex;
	align-items: center;
	justify-content: center;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.callout img.notion-static-icon {
	width: 1em;
	height: 1em;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

blockquote.quote-large {
	font-size: 1.25em;
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(44, 44, 43, 1);
}
.highlight-gray {
	color: rgba(128, 125, 120, 1);
	fill: rgba(128, 125, 120, 1);
}
.highlight-brown {
	color: rgba(159, 118, 90, 1);
	fill: rgba(159, 118, 90, 1);
}
.highlight-orange {
	color: rgba(204, 121, 47, 1);
	fill: rgba(204, 121, 47, 1);
}
.highlight-yellow {
	color: rgba(195, 148, 67, 1);
	fill: rgba(195, 148, 67, 1);
}
.highlight-teal {
	color: rgba(80, 148, 110, 1);
	fill: rgba(80, 148, 110, 1);
}
.highlight-blue {
	color: rgba(63, 126, 190, 1);
	fill: rgba(63, 126, 190, 1);
}
.highlight-purple {
	color: rgba(154, 107, 180, 1);
	fill: rgba(154, 107, 180, 1);
}
.highlight-pink {
	color: rgba(179, 84, 136, 1);
	fill: rgba(179, 84, 136, 1);
}
.highlight-red {
	color: rgba(201, 85, 73, 1);
	fill: rgba(201, 85, 73, 1);
}
.highlight-default_background {
	color: rgba(44, 44, 43, 1);
}
.highlight-gray_background {
	background: rgba(42, 28, 0, 0.07);
}
.highlight-brown_background {
	background: rgba(139, 46, 0, 0.086);
}
.highlight-orange_background {
	background: rgba(224, 101, 1, 0.129);
}
.highlight-yellow_background {
	background: rgba(211, 168, 0, 0.137);
}
.highlight-teal_background {
	background: rgba(0, 100, 45, 0.09);
}
.highlight-blue_background {
	background: rgba(0, 111, 200, 0.09);
}
.highlight-purple_background {
	background: rgba(102, 0, 178, 0.078);
}
.highlight-pink_background {
	background: rgba(197, 0, 93, 0.086);
}
.highlight-red_background {
	background: rgba(223, 22, 0, 0.094);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(128, 125, 120, 1);
	fill: rgba(128, 125, 120, 1);
}
.block-color-brown {
	color: rgba(159, 118, 90, 1);
	fill: rgba(159, 118, 90, 1);
}
.block-color-orange {
	color: rgba(204, 121, 47, 1);
	fill: rgba(204, 121, 47, 1);
}
.block-color-yellow {
	color: rgba(195, 148, 67, 1);
	fill: rgba(195, 148, 67, 1);
}
.block-color-teal {
	color: rgba(80, 148, 110, 1);
	fill: rgba(80, 148, 110, 1);
}
.block-color-blue {
	color: rgba(63, 126, 190, 1);
	fill: rgba(63, 126, 190, 1);
}
.block-color-purple {
	color: rgba(154, 107, 180, 1);
	fill: rgba(154, 107, 180, 1);
}
.block-color-pink {
	color: rgba(179, 84, 136, 1);
	fill: rgba(179, 84, 136, 1);
}
.block-color-red {
	color: rgba(201, 85, 73, 1);
	fill: rgba(201, 85, 73, 1);
}
.block-color-default_background {
	color: inherit;
	fill: inherit;
}
.block-color-gray_background {
	background: rgba(240, 239, 237, 1);
}
.block-color-brown_background {
	background: rgba(245, 237, 233, 1);
}
.block-color-orange_background {
	background: rgba(251, 235, 222, 1);
}
.block-color-yellow_background {
	background: rgba(249, 243, 220, 1);
}
.block-color-teal_background {
	background: rgba(232, 241, 236, 1);
}
.block-color-blue_background {
	background: rgba(232, 242, 250, 1);
}
.block-color-purple_background {
	background: rgba(243, 235, 249, 1);
}
.block-color-pink_background {
	background: rgba(250, 233, 241, 1);
}
.block-color-red_background {
	background: rgba(252, 233, 231, 1);
}
.select-value-color-default { background-color: rgba(42, 28, 0, 0.07); }
.select-value-color-gray { background-color: rgba(28, 19, 1, 0.11); }
.select-value-color-brown { background-color: rgba(127, 51, 0, 0.156); }
.select-value-color-orange { background-color: rgba(196, 88, 0, 0.203); }
.select-value-color-yellow { background-color: rgba(209, 156, 0, 0.282); }
.select-value-color-green { background-color: rgba(0, 96, 38, 0.156); }
.select-value-color-blue { background-color: rgba(0, 99, 174, 0.172); }
.select-value-color-purple { background-color: rgba(92, 0, 163, 0.141); }
.select-value-color-pink { background-color: rgba(183, 0, 78, 0.152); }
.select-value-color-red { background-color: rgba(206, 24, 0, 0.164); }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="15704299-dc9e-80ed-9270-f23168bf188f" class="page sans"><header><img class="page-cover-image" src="https://images.unsplash.com/photo-1472214103451-9374bd1c798e?ixlib=rb-4.0.3&amp;q=85&amp;fm=jpg&amp;crop=entropy&amp;cs=srgb" style="object-position:center 50%"/><div class="page-header-icon page-header-icon-with-cover"><img class="icon" src="2.png"/></div><h1 class="page-title">Life OS</h1><p class="page-description"></p></header><div class="page-body"><div id="15704299-dc9e-8147-9b1b-ceb16e722b2a" class="column-list"><div id="15704299-dc9e-8126-bd25-fc1f71cba054" style="width:43.75%" class="column"><figure id="15704299-dc9e-81c9-9c79-df3ca4cd998b"><div class="source"><a href="https://indify.co/widgets/live/button/8naOTjcFVnTGXeipJk26">https://indify.co/widgets/live/button/8naOTjcFVnTGXeipJk26</a></div></figure></div><div id="15704299-dc9e-8100-b99c-c49f096ce0e9" style="width:56.25%" class="column"><figure id="15704299-dc9e-812b-9e88-d19f65871d26"><div class="source"><a href="https://indify.co/widgets/live/progressBar/P9NLBc4JOfNjy4W5mhmN">https://indify.co/widgets/live/progressBar/P9NLBc4JOfNjy4W5mhmN</a></div></figure></div></div><h2 id="15704299-dc9e-8178-8166-ecdc519184eb" class="block-color-teal_background"><strong><span style="border-bottom:0.05em solid">Dashboard</span></strong></h2><hr id="15704299-dc9e-81b8-8fe8-e11059e80aad"/><div id="15704299-dc9e-8121-afe0-c2499c7fcfa7" class="column-list"><div id="15704299-dc9e-813a-83a4-f0f262de38c1" style="width:50%" class="column"><figure id="15704299-dc9e-8126-b532-f7eee37b95cd" class="link-to-page"><a href="https://www.notion.so/Goals-15704299dc9e8126b532f7eee37b95cd?pvs=21"><img class="icon notion-static-icon" src="https://www.notion.so/icons/bullseye_green.svg"/>Goals</a></figure><figure id="15704299-dc9e-81be-abef-d29d60e786a1" class="link-to-page"><a href="https://www.notion.so/Personal-Finance-15704299dc9e81beabefd29d60e786a1?pvs=21"><img class="icon notion-static-icon" src="https://www.notion.so/icons/currency_green.svg"/>Personal Finance</a></figure><figure id="15704299-dc9e-81e3-9e57-ddec19c698b2" class="link-to-page"><a href="https://www.notion.so/Mobile-Notes-15704299dc9e81e39e57ddec19c698b2?pvs=21"><img class="icon notion-static-icon" src="https://www.notion.so/icons/phone_green.svg"/>Mobile Notes</a></figure><figure id="15704299-dc9e-81ae-8797-c38c8c291918" class="link-to-page"><a href="https://www.notion.so/Books-To-Read-15704299dc9e81ae8797c38c8c291918?pvs=21"><img class="icon notion-static-icon" src="https://www.notion.so/icons/book-closed_green.svg"/>Books To Read</a></figure><figure id="15704299-dc9e-8150-8b47-c9e7f784e934" class="link-to-page"><a href="https://www.notion.so/Academics-15704299dc9e81508b47c9e7f784e934?pvs=21"><img class="icon notion-static-icon" src="https://www.notion.so/icons/graduate_green.svg"/>Academics</a></figure></div><div id="15704299-dc9e-810b-aae3-f2a9b873da60" style="width:50%" class="column"><figure id="15704299-dc9e-8127-8e62-c9678181ed0f" class="link-to-page"><a href="https://www.notion.so/Idea-Box-15704299dc9e81278e62c9678181ed0f?pvs=21"><img class="icon notion-static-icon" src="https://www.notion.so/icons/light-bulb_green.svg"/>Idea Box</a></figure><figure id="15704299-dc9e-81a8-b75b-ddce3fbc2d9c" class="link-to-page"><a href="https://www.notion.so/Skill-Tree-15704299dc9e81a8b75bddce3fbc2d9c?pvs=21"><img class="icon notion-static-icon" src="https://www.notion.so/icons/branch-create_green.svg"/>Skill Tree</a></figure><figure id="15704299-dc9e-81e6-9477-e1cd3213ad0d" class="link-to-page"><a href="https://www.notion.so/Bucket-List-15704299dc9e81e69477e1cd3213ad0d?pvs=21"><img class="icon notion-static-icon" src="https://www.notion.so/icons/couch_green.svg"/>Bucket List</a></figure><figure id="15704299-dc9e-814a-b489-df06c439069f" class="link-to-page"><a href="https://www.notion.so/Tasks-and-To-Do-15704299dc9e814ab489df06c439069f?pvs=21"><img class="icon notion-static-icon" src="https://www.notion.so/icons/chemistry_green.svg"/>Tasks and To-Do</a></figure></div></div><hr id="15704299-dc9e-810e-95e3-df630c611064"/><h2 id="15704299-dc9e-814d-a5cc-c05f742ba766" class="block-color-gray_background"><strong><span style="border-bottom:0.05em solid">Database</span></strong></h2><hr id="27704299-dc9e-8087-9a59-c2f6a524a948"/><figure id="27704299-dc9e-8018-80e5-e56ca5a57032" class="link-to-page"><a href="https://www.notion.so/27704299dc9e801880e5e56ca5a57032?pvs=21"><span class="icon">✅</span>task database</a></figure><figure class="block-color-gray callout" style="white-space:pre-wrap;display:flex" id="15704299-dc9e-8111-95d3-ea4e16fef634"><div style="font-size:1.5em;display:flex;align-items:center"><span class="icon">👝</span></div><div style="width:100%">Freshies<div id="15704299-dc9e-8124-8d50-e9fc6a73383b" class="collection-content"><h4 class="collection-title">freshies</h4><table class="collection-content"><thead><tr><th><span class="icon property-icon"><img src="https://www.notion.so/icons/font_gray.svg" style="width:14px;height:14px;display:block"/></span>Name</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/clock_gray.svg" style="width:14px;height:14px;display:block"/></span>Created</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/attachment_gray.svg" style="width:14px;height:14px;display:block"/></span>Files &amp; media</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/list_gray.svg" style="width:14px;height:14px;display:block"/></span>Tags</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/link_gray.svg" style="width:14px;height:14px;display:block"/></span>URL</th></tr></thead><tbody><tr id="15704299-dc9e-812f-bee2-f9a5e67ad63c"><td class="cell-title"><a href="https://www.notion.so/You-re-not-dumb-How-to-FIX-your-ATTENTION-SPAN-YouTube-15704299dc9e812fbee2f9a5e67ad63c?pvs=21">You&#x27;re not dumb: How to FIX your ATTENTION SPAN - YouTube</a></td><td class="cell-SRXr"><time>@December 9, 2024 8:22 PM</time></td><td class="cell-bp_Q"></td><td class="cell-SDfY"></td><td class="cell-@Iki"><a href="https://www.youtube.com/watch?v=rXDjiXK_Szg" class="url-value">https://www.youtube.com/watch?v=rXDjiXK_Szg</a></td></tr><tr id="15704299-dc9e-8152-8f22-c2e706d32601"><td class="cell-title"><a href="https://www.notion.so/5-Watch-this-and-They-Will-start-Respecting-You-YouTube-15704299dc9e81528f22c2e706d32601?pvs=21">(5) Watch this and They Will start Respecting You - YouTube</a></td><td class="cell-SRXr"><time>@December 9, 2024 8:22 PM</time></td><td class="cell-bp_Q"></td><td class="cell-SDfY"></td><td class="cell-@Iki"><a href="https://www.youtube.com/watch?v=dks39aU0D60" class="url-value">https://www.youtube.com/watch?v=dks39aU0D60</a></td></tr><tr id="15704299-dc9e-8150-a4d7-d1336d025471"><td class="cell-title"><a href="https://www.notion.so/How-to-make-your-Notion-dashboard-more-aesthetic-like-way-more-YouTube-15704299dc9e8150a4d7d1336d025471?pvs=21">How to make your Notion dashboard more aesthetic (like way more) - YouTube</a></td><td class="cell-SRXr"><time>@December 9, 2024 8:22 PM</time></td><td class="cell-bp_Q"></td><td class="cell-SDfY"></td><td class="cell-@Iki"><a href="https://www.youtube.com/watch?v=sSJvVLjBAaU&amp;t=227s" class="url-value">https://www.youtube.com/watch?v=sSJvVLjBAaU&amp;t=227s</a></td></tr><tr id="15704299-dc9e-81a7-9164-f5997909c11f"><td class="cell-title"><a href="https://www.notion.so/How-I-organize-My-Life-Simple-Notion-Workflow-YouTube-15704299dc9e81a79164f5997909c11f?pvs=21">How I organize My Life | Simple Notion Workflow - YouTube</a></td><td class="cell-SRXr"><time>@December 9, 2024 8:22 PM</time></td><td class="cell-bp_Q"></td><td class="cell-SDfY"></td><td class="cell-@Iki"><a href="https://www.youtube.com/watch?v=7fIVwa8EujU&amp;t=21s" class="url-value">https://www.youtube.com/watch?v=7fIVwa8EujU&amp;t=21s</a></td></tr><tr id="17704299-dc9e-811d-9cf9-e4573b8a3c2a"><td class="cell-title"><a href="https://www.notion.so/PIHARVA-2-Kg-Top-Load-Washing-Machine-Portable-Mini-Foldable-Washer-and-Spin-Dryer-Small-Foldable-17704299dc9e811d9cf9e4573b8a3c2a?pvs=21">PIHARVA 2 Kg Top Load Washing Machine - Portable Mini Foldable Washer and Spin Dryer, Small Foldable Bucket Washer for Camping, Rv, Travel, Small Spaces, Lightweight and Easy to Carry : Amazon.in: Home &amp; Kitchen</a></td><td class="cell-SRXr"><time>@January 10, 2025 7:32 PM</time></td><td class="cell-bp_Q"></td><td class="cell-SDfY"></td><td class="cell-@Iki"><a href="https://www.amazon.in/PIHARVA-Top-Load-Washing-Machine/dp/B0DPSLRNGJ/?_encoding=UTF8&amp;pd_rd_w=a4IGZ&amp;content-id=amzn1.sym.509965a2-791b-4055-b876-943397d37ed3%3Aamzn1.symc.fc11ad14-99c1-406b-aa77-051d0ba1aade&amp;pf_rd_p=509965a2-791b-4055-b876-943397d37ed3&amp;pf_rd_r=7YPYGH5MZ4BGZKKW2PTF&amp;pd_rd_wg=c7dXM&amp;pd_rd_r=c748efbe-f640-411f-bf1e-e363fdda4662&amp;ref_=pd_hp_d_atf_ci_mcx_mr_ca_hp_atf_d" class="url-value">https://www.amazon.in/PIHARVA-Top-Load-Washing-Machine/dp/B0DPSLRNGJ/?_encoding=UTF8&amp;pd_rd_w=a4IGZ&amp;content-id=amzn1.sym.509965a2-791b-4055-b876-943397d37ed3%3Aamzn1.symc.fc11ad14-99c1-406b-aa77-051d0ba1aade&amp;pf_rd_p=509965a2-791b-4055-b876-943397d37ed3&amp;pf_rd_r=7YPYGH5MZ4BGZKKW2PTF&amp;pd_rd_wg=c7dXM&amp;pd_rd_r=c748efbe-f640-411f-bf1e-e363fdda4662&amp;ref_=pd_hp_d_atf_ci_mcx_mr_ca_hp_atf_d</a></td></tr></tbody></table><br/><br/></div></div></figure><p id="15704299-dc9e-8100-9ba4-cb63f292a0fc" class="">
</p><hr id="15704299-dc9e-8103-aaaa-cfd8e6af0c76"/><p id="15704299-dc9e-81b2-b06a-da7a0143bec4" class="">
</p><p id="15704299-dc9e-81a2-9896-f5d14b096232" class="">
</p><figure class="block-color-default callout" style="white-space:pre-wrap;display:flex" id="15704299-dc9e-81b5-968f-c7dc89b79ec5"><div style="font-size:1.5em;display:flex;align-items:center"><span class="icon">🗓️</span></div><div style="width:100%">Calender</div></figure></div></article><span class="sans" style="font-size:14px;padding-top:2em"></span></body></html>
<!--
**Goat4204/Goat4204** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
