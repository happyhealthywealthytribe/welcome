# welcome
<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>| HHWT RESOURCES </title><style>
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
	border-radius: 3px;
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
	text-indent: -1.7em;
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
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
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
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
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

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
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
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-opaquegray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }

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
	
</style></head><body><article id="ff302bdd-b7d6-49db-9082-97990134fafe" class="page mono"><header><img class="page-cover-image" src="https://images.unsplash.com/photo-1568145675395-66a2eda0c6d7?ixlib=rb-4.0.3&amp;q=80&amp;fm=jpg&amp;crop=entropy&amp;cs=tinysrgb" style="object-position:center 50%"/><div class="page-header-icon page-header-icon-with-cover"><img class="icon" src="HHWT%20RESOURCES%20ff302bddb7d649db908297990134fafe/Untitled_design_(1).png"/></div><h1 class="page-title">| HHWT RESOURCES </h1></header><div class="page-body"><hr id="8d06b29d-833b-4550-bab7-8414c20b53db"/><div id="4b6a66ca-a48a-4137-ba95-f3d60829d58e" class="column-list"><div id="832b2529-382a-4acb-8632-c4dc831c6620" style="width:56.25%" class="column"><p id="47673897-dcbb-4cf7-9acf-46537e95bebe" class="block-color-blue_background">   |<strong>NAVIGATION/TABLE OF CONTENTS</strong></p><hr id="25d5347b-fb45-4a70-a9fe-e78a05f2d734"/><figure id="3b17fd09-9ebc-4eff-bab3-7288c4ca0070" class="link-to-page"><a href="https://www.notion.so/ONBOARDING-ACTION-CHECKLIST-3b17fd099ebc4effbab37288c4ca0070"><span class="icon">✅</span> | ONBOARDING ACTION CHECKLIST </a></figure><figure id="eb585a61-4fd2-4663-996d-b97e278f8a32" class="link-to-page"><a href="https://www.notion.so/DBS-DIGITAL-BUSINESS-SPECIALIST-eb585a614fd24663996db97e278f8a32"><span class="icon">✅</span>    |  DBS/ DIGITAL BUSINESS SPECIALIST</a></figure><figure id="dd8fdb92-9272-41e2-bfa4-afb84c404c8b" class="link-to-page"><a href="https://www.notion.so/SCRIPTS-COPY-dd8fdb92927241e2bfa4afb84c404c8b"><span class="icon">🗒️</span>| SCRIPTS &amp; COPY</a></figure><figure id="df2e0e47-5997-45d2-bee5-7e8b25c5abb1" class="link-to-page"><a href="https://www.notion.so/HUDDLE-TEAM-MEETINGS-df2e0e47599745d2bee57e8b25c5abb1"><span class="icon">🤝</span>  | HUDDLE/ TEAM MEETINGS</a></figure><figure id="eecde48f-a902-4b52-8382-2d5ee216c76b" class="link-to-page"><a href="https://www.notion.so/LIBRARY-Biz-Books-eecde48fa9024b5283822d5ee216c76b"><span class="icon">📒</span>|   LIBRARY-Biz Books</a></figure><p id="7b18955f-3b60-4d85-866f-a30ad74c534f" class="">🕰️ | <a href="https://dateful.com/time-zone-converter">TIME ZONE CONVERTER</a></p><p id="18e08231-0725-4836-abaa-b826872f290d" class="">✅ | <a href="https://drive.google.com/file/d/1f0Se9MtO9EexvlqHUWSqWstyuQPzITHI/view?usp=share_link">ACCESS YOUR SALES REPORT</a></p><figure id="363e3dcb-41d8-45ce-9c90-5f65f5c61f38" class="link-to-page"><a href="https://www.notion.so/WATER-FREQUENCY-363e3dcb41d845ce9c905f65f5c61f38"><span class="icon">💧</span> | WATER FREQUENCY</a></figure><figure id="c5d7cee0-a66d-4dd0-ac62-aa3c2c0b8cae" class="link-to-page"><a href="https://www.notion.so/SALE-TOOLS-c5d7cee0a66d4dd0ac62aa3c2c0b8cae"><span class="icon">🚀</span> | SALE TOOLS </a></figure><figure id="f21f6674-7ce1-403e-bb0e-61e096b8bb84" class="link-to-page"><a href="https://www.notion.so/OVERCOMING-OBJECTIONS-f21f66747ce1403ebb0e61e096b8bb84"><span class="icon">✅</span>|  OVERCOMING OBJECTIONS</a></figure><figure id="46c222f9-3669-4d72-9ed3-b348625bebfc" class="link-to-page"><a href="https://www.notion.so/MARKETING-VIDEOS-RESOURCES-46c222f936694d729ed3b348625bebfc"><span class="icon">📔</span> | MARKETING VIDEOS &amp; RESOURCES</a></figure><p id="1a0db609-2953-448c-b67a-fe76ae5f3288" class="">
</p><p id="ddb77a74-a762-4645-ae33-bc81cabc0c77" class="block-color-blue_background">  | <strong>ENAGIC</strong></p><hr id="48722f78-7a92-473a-91f8-d3f3754ba7d6"/><figure id="5fadcf11-3259-418b-b4ca-bd0991e204f5" class="link-to-page"><a href="https://www.notion.so/OFFICE-AND-DEPARTMENT-CONTACT-INFO-5fadcf113259418bb4cabd0991e204f5"><span class="icon">📍</span>| OFFICE AND DEPARTMENT CONTACT INFO</a></figure><figure id="8d74cf15-1417-4368-9aed-6cdfe071952b" class="link-to-page"><a href="https://www.notion.so/PAPERWORK-PROCESS-FORMS-8d74cf15141743689aed6cdfe071952b"><span class="icon">📎</span> | PAPERWORK PROCESS &amp; FORMS</a></figure><figure id="026ad7c4-6f02-4fa6-ad5c-3e6c94a0df28" class="link-to-page"><a href="https://www.notion.so/FINANCING-026ad7c46f024fa6ad5c3e6c94a0df28"><span class="icon">🏦</span>  | FINANCING </a></figure><p id="4f624c94-a78f-4666-95d1-d5b20eebf947" class="block-color-blue_background">  <strong> | MARKETING RESOURCES</strong></p><hr id="265f0ad9-f8cb-4ce5-b816-4b07508302d7"/><figure id="6c1de114-8e69-4d5a-b5d3-b6adf4a4d41d" class="link-to-page"><a href="https://www.notion.so/PRODUCTS-6c1de1148e694d5ab5d3b6adf4a4d41d"><span class="icon">📦</span> | PRODUCTS</a></figure><figure id="6ee22191-ea8d-4c76-be31-38acebaf9ffb" class="link-to-page"><a href="https://www.notion.so/COMMISSION-COMPENSATION-PLAN-6ee22191ea8d4c76be3138acebaf9ffb"><span class="icon">🤝</span>|  COMMISSION  &amp; COMPENSATION PLAN</a></figure><figure id="e9f499a0-890f-4f4a-b61d-06b62d9831d1" class="link-to-page"><a href="https://www.notion.so/LAUNCHES-e9f499a0890f4f4ab61d06b62d9831d1"><span class="icon">🚀</span>|  LAUNCHES</a></figure></div><div id="fb2b60a6-fdf8-4df3-80ec-1de577713d1a" style="width:43.75%" class="column"><p id="794241f6-f1fa-4141-8592-fb7fde5aa4c8" class="block-color-teal_background">   | <strong>COMMUNITY GROUPS to JOIN</strong></p><hr id="dae143ab-05c1-42ea-bf77-fb075b1960ed"/><figure id="99f4a872-fbbe-4ac5-89ea-45f4045ba193" class="link-to-page"><a href="https://www.notion.so/Join-GROUPS-CHATPODS-99f4a872fbbe4ac589ea45f4045ba193"><span class="icon">😀</span>Join GROUPS &amp; CHATPODS </a></figure><p id="5a9e6a6f-c9c0-4f1e-9064-d8214ff99896" class="block-color-blue_background">   | <strong>Facebook Groups</strong></p><p id="57a44486-e2dd-4351-acf0-8db06d43e876" class="">   | <a href="https://www.facebook.com/groups/happyhealthywealthytribe">HHWT FB Group</a></p><p id="8285b883-bb10-4dfa-a94b-780714b55184" class="">   | <a href="https://www.facebook.com/groups/thefreedomera/">The Freedom Era Academy FB </a></p><p id="eac70937-2326-4d4d-b21d-b73853393721" class="">   | <a href="https://www.facebook.com/groups/happyhealthywealthytribe">Freedom Era Community FB Page</a>     </p><p id="adf2539f-b142-4a53-9a4c-8539dfd9e550" class="">   | <a href="https://www.facebook.com/groups/ElixirOfLifebyGPM">GPM Elixer of Life FB Group</a></p><p id="cd49e61f-ce5b-4db0-b25b-4ce60b23dcd1" class="">   |<a href="https://www.facebook.com/groups/915634295278629/"> Race to 6A2 FB Group</a></p><p id="bcc8e9eb-1fe9-4ea8-a011-1284e46dd198" class="">
</p><p id="dd69c22a-ba43-4263-8e8d-7d8c7bde280e" class="block-color-pink_background">   | <strong>Instagram Chatpod</strong></p><p id="b95c4c7f-2a09-4a2f-8a6f-54d2ca2c93f5" class="">   |<a href="https://www.instagram.com/visionary_lifestyle_guide/"> Instagram Chatpod -HHWT-message Magdalena on IG @visionary_lifestyle_guide</a></p><p id="16098fb9-3ff1-414a-a4e2-c7b704b6dfe1" class=""><strong> </strong></p><p id="fbda25c6-3d1a-4a0f-9623-5d035d94fde6" class="block-color-blue_background">   | <strong>Telegram Group </strong></p><p id="90dd96f5-fe1f-4642-af85-7e38507f963b" class="">   | <a href="https://t.me/+iNq7M5TYjxM0N2Ex"> HHWT Telegram Chatpod </a></p><p id="aa8dd2a2-2cb3-4e29-bb69-974de64660a2" class="">   </p><p id="b0c06e09-dc2e-48f2-a887-a04923a74c2c" class="">
</p></div></div><figure id="1dbf2b6c-053e-4ee3-8ef4-5d4a5ffc9be1" class="block-color-orange_background link-to-page"><a href="https://www.notion.so/TRAINING-MENTORSHIP-1dbf2b6c053e4ee38ef45d4a5ffc9be1"><span class="icon">📔</span>  | TRAINING &amp; MENTORSHIP </a></figure><hr id="ec9b3a54-8b07-4037-b4ec-5da273e5a205"/><p id="8862ebf0-8bf3-43ba-9924-cd6b452c3603" class="">✅ | <a href="https://www.facebook.com/gaby.kowalski.3/videos/1848193105315334/">GABBY QUANTUM GLOBAL HEALING SUMMIT</a></p><figure id="6ecbd0fb-5216-479c-b6d0-18b3c3b9c643" class="link-to-page"><a href="https://www.notion.so/FREEDOM-FREQUENCY-MENTORSHIP-6ecbd0fb5216479cb6d018b3c3b9c643"><span class="icon">🤝</span> | FREEDOM FREQUENCY MENTORSHIP</a></figure><figure id="b444b11a-ed83-4ead-b9d7-958c145c6077" class="link-to-page"><a href="https://www.notion.so/RISE-AND-THRIVE-MENTORSHIP-b444b11aed834eadb9d7958c145c6077"><span class="icon">❤️</span>| RISE AND THRIVE MENTORSHIP</a></figure><figure id="ec8a8f10-6eee-4db4-a9a6-0037eed8545f" class="link-to-page"><a href="https://www.notion.so/SOLUTION-SUMMIT-MENTORSHIP-ec8a8f106eee4db4a9a60037eed8545f"><span class="icon">✅</span>| SOLUTION SUMMIT MENTORSHIP </a></figure><figure id="fab85f66-0432-4299-b349-49c49142b9e0" class="link-to-page"><a href="https://www.notion.so/ATTRACTING-MARKETING-MANIFESTO-fab85f6604324299b34949c49142b9e0"><span class="icon">✅</span>|   ATTRACTING MARKETING MANIFESTO</a></figure><figure id="28ae8b1f-91ae-4e07-977c-4bdd35e639e5" class="link-to-page"><a href="https://www.notion.so/TEASER-AND-LAUNCH-POST-28ae8b1f91ae4e07977c4bdd35e639e5"><span class="icon">🚀</span>| TEASER AND LAUNCH POST</a></figure><figure id="a1dc9a87-2c92-4cd2-b81a-ec35ffc7e1aa" class="link-to-page"><a href="https://www.notion.so/YOUR-NEXT-90-DAYS-TRAINING-a1dc9a872c924cd2b81aec35ffc7e1aa"><span class="icon">🏑</span>| YOUR NEXT 90 DAYS  TRAINING</a></figure><figure id="67fde493-6665-4b22-b437-c0da52e1308f" class="link-to-page"><a href="https://www.notion.so/LAUNCH-YOUR-BUSINESS-67fde49366654b22b437c0da52e1308f"><span class="icon">🚀</span>|  LAUNCH YOUR BUSINESS</a></figure><figure id="a4f75ebd-9dfb-4c94-ab05-7260773ccdd0" class="link-to-page"><a href="https://www.notion.so/IKIGAI-LIFE-PURPOSE-a4f75ebd9dfb4c94ab057260773ccdd0"><span class="icon">💧</span>   | IKIGAI &amp; LIFE PURPOSE</a></figure><figure id="2bbcc74a-a64a-4b34-ada8-a2d17b6a0909" class="link-to-page"><a href="https://www.notion.so/SALES-PROCESS-TRAINING-BY-MAGDALENA-2bbcc74aa64a4b34ada8a2d17b6a0909"><span class="icon">💰</span>| SALES PROCESS TRAINING BY MAGDALENA</a></figure><figure id="9c16ae1d-ca01-4f39-8949-fee47ae4e055" class="link-to-page"><a href="https://www.notion.so/MINDSET-9c16ae1dca014f398949fee47ae4e055"><span class="icon">🧘🏻‍♀️</span>|  MINDSET</a></figure><figure id="194618a4-3593-45df-bed8-1d6fb1ee03a9" class="link-to-page"><a href="https://www.notion.so/ABUNDANCE-TOOLS-194618a4359345dfbed81d6fb1ee03a9"><span class="icon">💙</span>| ABUNDANCE TOOLS</a></figure><figure id="6b6441ed-8e46-4e61-b97f-b494b6f6a4dc" class="link-to-page"><a href="https://www.notion.so/TFE-RESOURCES-6b6441ed8e464e61b97fb494b6f6a4dc"><span class="icon">📔</span>| TFE RESOURCES</a></figure><figure id="fef0c894-e1e7-476e-98cc-ecf529f81ebc" class="link-to-page"><a href="https://www.notion.so/SOCIAL-MEDIA-ADS-fef0c894e1e7476e98ccecf529f81ebc"><span class="icon">✅</span>| SOCIAL MEDIA ADS</a></figure><figure id="78b78b18-c2dd-4cf1-ade5-ba4bee495ee0" class="link-to-page"><a href="https://www.notion.so/ABUNDANCE-TOOLS-78b78b18c2dd4cf1ade5ba4bee495ee0"><span class="icon">✅</span>|  ABUNDANCE TOOLS</a></figure><figure id="e77d60d9-ed31-4a6c-995e-700577139826" class="link-to-page"><a href="https://www.notion.so/SOCIAL-MEDIA-TRAINING-e77d60d9ed314a6c995e700577139826"><span class="icon">✅</span>|  SOCIAL MEDIA TRAINING</a></figure><figure id="89685317-22fd-42ee-82d9-943e9349e1b3" class="link-to-page"><a href="https://www.notion.so/UKON-STRATEGY-8968531722fd42ee82d9943e9349e1b3"><span class="icon">✅</span>|  UKON STRATEGY</a></figure><figure id="e8c7378f-991c-40b2-b335-5158e4682569" class="link-to-page"><a href="https://www.notion.so/HHWT-FB-GROUP-GUIDES-FREE-RESOURCES-e8c7378f991c40b2b3355158e4682569"><span class="icon">✅</span>   |  HHWT FB GROUP GUIDES FREE RESOURCES:  </a></figure><p id="a0baa55e-0914-4380-87dc-5505be8890af" class="">✅ | <a href="https://www.facebook.com/groups/277674025918999/permalink/974145609605167/">GABBY KOWALSKI TRAINING 1</a> </p><p id="c0377f0e-3752-4847-be9d-0d68ff70666f" class="">✅ |<a href="https://gabykowalskiglobal.com/clint-kristie-mdm-recording?fbclid=IwAR0XjuvrKC7UgDBFnQlro4pWzGjyPGkJQFJWEQPMKz8Uh1m48cr5n-i9ado"> GABBY KOWALSKI TRAINING 2</a></p><p id="b0d4ec63-8490-4aa3-9637-c37c711c3e46" class="">✅ |<strong> </strong><a href="https://www.youtube.com/watch?v=A2NephRMpMU">4A IN 90 DAYS STRATEGIES</a></p><p id="bf1662fb-a8b5-44b9-9a4a-35f0ce4ab691" class="">✅ | <a href="https://us02web.zoom.us/rec/play/WQLOFKeRtGYF4MCDS6xng04a846jkcVOoU7mn5ygxlKbxlhMJcppjU5fpSHmfO8slGUOeYX1FPEx6Oq0.VZjbgltRC-0WUfCp?continueMode=true">INSPIRATION: CHARLOTTE HUDDLE REPLAY  - MAKING THIS BIZ YOUR OWN</a></p><p id="3ac473d4-880d-41c1-ae23-98a0745b7d4b" class="">✅ | <a href="https://martinkangenwaterman.wistia.com/medias/y7xoq01boo?wtime=0?wtime=0">COMPLIANCE TRAINING</a></p><figure id="2fcf6051-ce4a-4a35-928f-004093679225" class="link-to-page"><a href="https://www.notion.so/REBEKA-S-LAUNCH-TRAINING-2fcf6051ce4a4a35928f004093679225"><span class="icon">✅</span>| REBEKA&#x27;S LAUNCH TRAINING</a></figure><p id="527f4688-0ea4-4d3e-bcf2-94ca61e3efdd" class="">✅ | <a href="https://drive.google.com/file/d/1Ao422X0t3ryLavWchmQ-DnDGeLD_jhEO/view?usp=drivesdk">TRELLO LEADS TRAINING FROM SABRE</a></p><p id="d6767df1-70ec-4049-9913-673e9ff6d6c4" class="">📽️ | <a href="https://perfectwebinarsecrets.com/get-instant-access-1?affiliate_id=513513&amp;cf_affiliate_id=513513&amp;wcid=16996963581&amp;wickedid=594244926127&amp;wickedsource=google&amp;wv=4">PERFECT WEBINAR SECRET - WHEN YOU&#x27;RE READY TO DO YOUR OWN </a></p><p id="21554b62-f20a-4492-af75-eab0b07393d4" class="">🚀 | <a href="https://www.youtube.com/channel/UCkCdnC-SSMctVjOAMZP4vBA/videos">PH ALLIANCE TRAINING VIDEOS</a></p><p id="6de48c44-b068-4199-9781-5e5b4c7e390a" class="">
</p></div></article></body></html>
