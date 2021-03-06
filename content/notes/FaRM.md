---
title: "FaRM (2015)"
date: 2020-03-20T22:36:50+08:00
draft: false
---

<style type="text/css" rel="stylesheet">
.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
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

.FaRM li > ol:first-child,
.FaRM li > ul:first-child {
	margin-block-start: 0.6em;
}

.FaRM ul > li {
	list-style: disc;
}

.FaRM ul.to-do-list {
	text-indent: -1.7em;
}

.FaRM ul.to-do-list > li {
	list-style: none;
}

.FaRM .to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

.FaRM ul.toggle > li {
	list-style: none;
}

.FaRM ul {
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

.FaRM .toggle {
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
	height: 30vh;
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

.bookmark-href {
	font-size: 0.75em;
	opacity: 0.5;
}

.sans { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: 'SFMono-Regular', Consolas, 'Liberation Mono', Menlo, Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, KaiTi, STKaiTi, '华文楷体', KaiTi_GB2312, '楷体_GB2312', serif; }
.mono { font-family: Nitti, 'Microsoft YaHei', '微软雅黑', monospace; }
.pdf .sans { font-family: Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC', 'Noto Sans CJK KR'; }

.pdf .code { font-family: Source Code Pro, 'SFMono-Regular', Consolas, 'Liberation Mono', Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC', 'Noto Sans Mono CJK KR'; }

.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, KaiTi, STKaiTi, '华文楷体', KaiTi_GB2312, '楷体_GB2312', serif, 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC', 'Noto Sans CJK KR'; }

.pdf .mono { font-family: PT Mono, Nitti, 'Microsoft YaHei', '微软雅黑', monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC', 'Noto Sans Mono CJK KR'; }

.highlight-default {
}
.highlight-gray {
	color: rgb(155,154,151);
}
.highlight-brown {
	color: rgb(100,71,58);
}
.highlight-orange {
	color: rgb(217,115,13);
}
.highlight-yellow {
	color: rgb(223,171,1);
}
.highlight-teal {
	color: rgb(15,123,108);
}
.highlight-blue {
	color: rgb(11,110,153);
}
.highlight-purple {
	color: rgb(105,64,165);
}
.highlight-pink {
	color: rgb(173,26,114);
}
.highlight-red {
	color: rgb(224,62,62);
}
.highlight-gray_background {
	background: rgb(235,236,237);
}
.highlight-brown_background {
	background: rgb(233,229,227);
}
.highlight-orange_background {
	background: rgb(250,235,221);
}
.highlight-yellow_background {
	background: rgb(251,243,219);
}
.highlight-teal_background {
	background: rgb(221,237,234);
}
.highlight-blue_background {
	background: rgb(221,235,241);
}
.highlight-purple_background {
	background: rgb(234,228,242);
}
.highlight-pink_background {
	background: rgb(244,223,235);
}
.highlight-red_background {
	background: rgb(251,228,228);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(55, 53, 47, 0.6);
	fill: rgba(55, 53, 47, 0.6);
}
.block-color-brown {
	color: rgb(100,71,58);
	fill: rgb(100,71,58);
}
.block-color-orange {
	color: rgb(217,115,13);
	fill: rgb(217,115,13);
}
.block-color-yellow {
	color: rgb(223,171,1);
	fill: rgb(223,171,1);
}
.block-color-teal {
	color: rgb(15,123,108);
	fill: rgb(15,123,108);
}
.block-color-blue {
	color: rgb(11,110,153);
	fill: rgb(11,110,153);
}
.block-color-purple {
	color: rgb(105,64,165);
	fill: rgb(105,64,165);
}
.block-color-pink {
	color: rgb(173,26,114);
	fill: rgb(173,26,114);
}
.block-color-red {
	color: rgb(224,62,62);
	fill: rgb(224,62,62);
}
.block-color-gray_background {
	background: rgb(235,236,237);
}
.block-color-brown_background {
	background: rgb(233,229,227);
}
.block-color-orange_background {
	background: rgb(250,235,221);
}
.block-color-yellow_background {
	background: rgb(251,243,219);
}
.block-color-teal_background {
	background: rgb(221,237,234);
}
.block-color-blue_background {
	background: rgb(221,235,241);
}
.block-color-purple_background {
	background: rgb(234,228,242);
}
.block-color-pink_background {
	background: rgb(244,223,235);
}
.block-color-red_background {
	background: rgb(251,228,228);
}

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
</style>

<body><article class='FaRM' id="a99bc84a-276c-4015-8cee-15cef1d80d54" class="page sans"><div class="page-body"><ul id="e11a9679-a9df-43e9-b09d-70d35bec1150" class="toggle"><li><details open=""><summary><strong>Background Reading</strong></summary><p id="200862fa-fc6f-4817-9f84-4bd380a3fd7d" class=""><a href="https://pdos.csail.mit.edu/6.824/notes/l-2pc.txt">https://pdos.csail.mit.edu/6.824/notes/l-2pc.txt</a></p><p id="d78fab06-155e-4871-b3ff-7cf241402cc4" class=""><a href="https://pdos.csail.mit.edu/6.824/papers/chapter9-faq.txt">https://pdos.csail.mit.edu/6.824/papers/chapter9-faq.txt</a></p></details></li></ul><ul id="1c04135b-2e33-4915-85b8-07bea4a212f1" class="toggle"><li><details open=""><summary><strong>Why are distributed transactions important</strong></summary><ul id="0f5efefb-713f-4dc2-840d-9330c2856ae3" class="bulleted-list"><li>distributed transactions are used in distributed databases</li></ul><ul id="af07c9a3-a4bc-4f0d-8e25-6cd2b578c3d8" class="bulleted-list"><li>they are an abstraction which simplify programming and reasoning:
<em>a single machine that never fails and executes one transaction at a time in an order that is consistent with real time</em></li></ul></details></li></ul><ul id="f8ab1d88-0c4b-470f-a84d-5c0bc13e5faa" class="toggle"><li><details open=""><summary><strong>What is FaRM for</strong></summary><ul id="0fc25406-1f8b-4883-be9c-6c5ee2e96ee4" class="bulleted-list"><li>FaRM is a distributed computing platform which provides distributed transactions</li></ul><ul id="1d97d081-7b24-42ae-a09e-763797221e89" class="bulleted-list"><li>objects are dsitributed across machines, in a datacenter</li></ul><ul id="1178d853-adb5-41e4-866d-651bf5867700" class="bulleted-list"><li>transactions can span any number of machines</li></ul></details></li></ul><ul id="5bd8ff56-f488-41be-b9a9-641364071e0e" class="toggle"><li><details open=""><summary><strong>How is this paper different from the original FaRM paper</strong></summary><ul id="d4f6e678-f260-432a-882f-e56c36f7542c" class="bulleted-list"><li>the authors make use of FaRM to provide distributed transactions that have the ACID properties, strict serializability, high peformance, availability and durability</li></ul><ul id="d8fd6fa6-a84d-4234-b158-de569f5c740d" class="bulleted-list"><li><em>distributed systems work best when nodes don’t need to talk, but when they do talk, make it fast</em></li></ul></details></li></ul><ul id="e254c784-fb2f-4fb1-89ee-147ee8ffd071" class="toggle"><li><details open=""><summary><strong>What durability guarantee does FaRM provide</strong></summary><ul id="a268115a-4ae0-4615-aa90-cb0381f0920d" class="bulleted-list"><li>all committed transactions are durable even if the entire cluster fails</li></ul><ul id="7066baeb-2246-4cff-a871-34e19cf682fe" class="bulleted-list"><li>this is enabled by primary backup replication</li></ul></details></li></ul><ul id="aa2699fe-4f0e-4312-821d-3c0994d95bde" class="toggle"><li><details open=""><summary><strong>How are the above attributes achieved</strong></summary><ul id="4ea33ebb-0dc4-4f81-9806-ce56b5064ba0" class="toggle"><li><details open=""><summary><strong>transaction and recovery protocols are designed to capitalize on datacenter hardware trends</strong></summary><ul id="c8008415-4384-4f56-a536-e4ecfb88b012" class="bulleted-list"><li>fast networking with RDMA</li></ul><ul id="5ac4bf95-070b-43d3-b4e8-a5696caf252e" class="toggle"><li><details open=""><summary><strong>low cost non-volatile memory</strong></summary><ul id="60530c04-a414-4cbd-b003-c6a0e60f5111" class="bulleted-list"><li>Batteries are placed in server racks as part of a distributed USP. In case of a failure, data in DRAM is written to SSDs which can then be subsequently recovered from.</li></ul><ul id="bd1e0352-a58e-44f7-9348-87aa47813cfa" class="bulleted-list"><li>Not all failures can be recovered from
eg. the OS still needs to be functional to write to SSD</li></ul></details></li></ul><ul id="4b9f58bd-52f3-42ec-9a0b-a09b9325eda3" class="toggle"><li><details open=""><summary><strong>plentiful memory</strong></summary><ul id="f7f3f5e2-d8bb-45d6-9a2e-a283523a4621" class="bulleted-list"><li>is used to hold entire application data in memory with no reads/writes to disk needed unless there is a failure</li></ul><ul id="33a16b76-3597-483e-96b9-a286cfd6ab54" class="bulleted-list"><li>this improves performance by avoiding synchronous writes to SSD</li></ul><ul id="2bba6e5a-fdde-4e07-af87-59d77c2f0751" class="bulleted-list"><li>additional benefit: it improves lifetime of the SSD by reducing writes</li></ul></details></li></ul></details></li></ul><ul id="36e206ca-7012-4b5c-b1bd-84d567eb9b41" class="toggle"><li><details open=""><summary><strong>this in turn exposes CPU bottlenecks which are mitigated by</strong></summary><ul id="c6387627-77fe-4c9f-bbac-d9746c5d7429" class="toggle"><li><details open=""><summary><strong>reducing message counts</strong></summary><ul id="0cac4cea-a246-4d9b-a3b2-f4b9fcea5ff4" class="toggle"><li><details open=""><summary><strong>primary-backup replication</strong></summary><ul id="b993634c-653a-4384-8757-24067d00fa83" class="bulleted-list"><li>much more efficient in terms of number of messages as compared to quorum based system</li></ul></details></li></ul><ul id="c91d0ef4-e629-4e6f-864d-5e639e55a871" class="toggle"><li><details open=""><summary>o<strong>ptimistic concurrency control</strong></summary><ul id="fbae0e57-fd5c-4f22-9df0-42e26453ad66" class="bulleted-list"><li>as many objects can be read as needed</li></ul><ul id="b988390d-3e7b-4206-ae11-a565e4a5e954" class="bulleted-list"><li>writes are buffered in memory until commit time</li></ul><ul id="840f6266-58ad-4481-981e-866240adfee6" class="bulleted-list"><li>access objects only on primaries</li></ul><ul id="69129e62-d3ed-4977-8f0d-49fe375b986e" class="bulleted-list"><li>avoids locking of objects at backups</li></ul><ul id="cb02f2ac-2f3f-4257-9a4c-b87a8ff5be79" class="bulleted-list"><li><strong>+ve</strong>: improved performance due to reduced number of messages required</li></ul><ul id="ce0c7285-ddc3-4b07-ba62-50c2597eadc0" class="bulleted-list"><li><strong>-ve</strong>: performance becomes poor as the number of conflicting transactions increase due to the transactions aborting</li></ul></details></li></ul></details></li></ul><ul id="463c3f31-5692-4466-963b-7c142e8f821e" class="bulleted-list"><li>using one-sided RDMA reads and writes (instead of messages eg. RPC)</li></ul><ul id="a7ec083b-9510-4510-a4ee-d898c30594a8" class="bulleted-list"><li>exploiting parallelism</li></ul></details></li></ul></details></li></ul><ul id="3041830d-6dcf-4279-b786-4b606ac7f838" class="toggle"><li><details open=""><summary><strong>By achieving those attributes, what application compromises can be eliminated</strong></summary><ul id="cec3c2ea-7e2f-45b5-9b06-f466c77663a6" class="bulleted-list"><li>not supporting transactions</li></ul><ul id="86632ee0-0b0d-4a0b-a316-26b22df65296" class="bulleted-list"><li>weak consistency guarantees</li></ul><ul id="633081a4-5419-4895-ba52-3427b32cc25f" class="bulleted-list"><li>providing transactions only when all necessary data resides within a single machine. This requires data partitioning and complicates correctness reasoning</li></ul></details></li></ul><ul id="89eea883-c1e3-422a-87ae-cb1207310848" class="toggle"><li><details open=""><summary><strong>How is it used</strong></summary><ul id="f428d058-bb88-4920-b6f0-f6607669dde5" class="bulleted-list"><li>An application thread can start a transaction which leads it to become the coordinator</li></ul><ul id="2f2f1d16-945e-4cb9-b690-fae094ad3daa" class="bulleted-list"><li>At the end of execution, FaRM can be invoked in order to commit the transaction</li></ul><ul id="407957dc-3926-450d-8379-393e3a2240c3" class="toggle"><li><details open=""><summary><strong>API</strong></summary><pre id="49d25709-0eb7-443e-9a78-38b794bbd1b7" class="code"><code>// create transaction
Tx* txCreate();

// allocate an object
void txAlloc(Tx *t, int size, Addr a, Cont *c);
void txFree(Tx *t, Addr a, Cont *c);
void txRead(Tx *t, Addr a, int size, Cont *c);
void txWrite(Tx *t, ObjBuf *old, ObjBuf *new);

// commit transaction
void txCommit(Tx *t, Cont *c);

// lock-free read
Lf* lockFreeStart();
void lockFreeRead(Lf* op,Addr a,int size,Cont *c);
void lockFreeEnd(Lf *op);

Incarnation objGetIncarnation(ObjBuf *o);
void objIncrementIncarnation(ObjBuf *o);
void msgRegisterHandler(MsgId i, Cont *c);
void msgSend(Addr a, MsgId i, Msg *m, Cont *c);</code></pre><p id="c0a5a2ba-2756-4447-b183-79124156596e" class="">
</p><ul id="14bbf074-c151-43d7-a88f-b3055ff31545" class="toggle"><li><details open=""><summary><strong>lock-free reads</strong></summary><p id="ad3dc864-9943-4544-b0ab-a92520268d11" class="">single-object read only transactions that are optimized</p></details></li></ul><ul id="eeb08164-ce6f-4243-859c-822c01aa6405" class="toggle"><li><details open=""><summary><strong>locality hints (by passing address)</strong></summary><p id="2017223e-346b-42d8-9869-fb257b265039" class="">these improve performance by allowing programmers to allocate related objects on the same machines</p></details></li></ul><ul id="e14f08c6-a65a-49e7-a477-7299252e0d27" class="toggle"><li><details open=""><summary><strong>function shipping</strong></summary><p id="b4d2f582-9d61-41bf-9063-2f5a1011b335" class="">the process of moving computational logic onto a different machine for minimizing communication or load balancing</p></details></li></ul></details></li></ul></details></li></ul><ul id="97a5b7ab-88d3-4956-9301-5b84f4cc2ea4" class="toggle"><li><details open=""><summary><strong>What phases does a transaction consist of</strong></summary><ul id="1c45212c-e2a6-4f7c-9e76-51ebeddcc70c" class="bulleted-list"><li>execution phase<p id="25ee4978-5c0b-4cdd-998d-0a3b89a07477" class="">involves operations on mutable state (read, write etc) as well as arbitrary logic</p></li></ul><ul id="3062d2df-0795-4e3c-9933-148bbe4ad341" class="bulleted-list"><li>commit phase</li></ul></details></li></ul><ul id="6e8ca816-8270-440d-b756-ff31ab1b336e" class="toggle"><li><details open=""><summary><strong>How can transactions fail</strong></summary><ul id="cfa65bc7-0e54-45c0-a16b-a8dd8e570404" class="bulleted-list"><li>failures in execution of the transaction</li></ul><ul id="6ead2e52-0b44-46d7-bdcc-11de6fbc2c3f" class="bulleted-list"><li>conflicts with concurrent transactions</li></ul></details></li></ul><ul id="f26c633c-4645-40b7-9d86-490e769f131a" class="toggle"><li><details open=""><summary><strong>Architecture</strong></summary><figure id="a77c3a1a-90ed-49ee-aafc-6df990c5e4bf" class="image"><a href="https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Farsalanc%2F2AOw2My9Q4?alt=media&amp;token=f5cd031c-91d9-48a8-b335-0372f03e60c3"><img src="https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Farsalanc%2F2AOw2My9Q4?alt=media&amp;token=f5cd031c-91d9-48a8-b335-0372f03e60c3"/></a></figure><p id="40f3f4ec-f072-4def-bdea-aa839ab5a4e0" class="">Each machine runs FaRM</p><p id="860b116e-c4a5-4e3e-bf25-8bd378deaa51" class="">
</p><ul id="2624c42d-4fd1-4337-b7d0-e17f15b48102" class="toggle"><li><details open=""><summary><strong>What is the role of the transaction coordinator</strong></summary><p id="b395030b-d5e2-44d0-b129-ff1ce661bde4" class="">it communicates directly with primaries and backups to commit a transaction
eg. writing records at primaries and backups, aborting a transaction etc</p></details></li></ul><ul id="29f5312d-b303-49ca-b6be-b9e303aa3514" class="toggle"><li><details open=""><summary><strong>Configuration</strong></summary><ul id="7ec5295f-6866-4d46-8a1b-ac5aaab026e2" class="toggle"><li><details open=""><summary><strong>What are the roles of the Configuration Manager (CM)</strong></summary><ul id="d8014e3c-994e-4216-abb7-ecf42d11699a" class="bulleted-list"><li>maintains a mapping of region ids to primary and backup machines</li></ul><ul id="d7bca987-5046-4bf1-bba2-f257205b0564" class="bulleted-list"><li>allocates a new region when contacted to do so by another machine</li></ul><ul id="fa0112aa-d8b6-4f40-9287-c269f4467b1f" class="bulleted-list"><li>detects failures, manages leases and coordinates recovery</li></ul><ul id="b44fe772-6a06-4114-90ca-d02927b7d522" class="bulleted-list"><li>invokes Zookeeper once per configuration change to update it</li></ul></details></li></ul><ul id="0735e7c3-55a2-42d9-ac64-791dca72a535" class="toggle"><li><details open=""><summary><strong>How is the FaRM configuration managed</strong></summary><p id="f4180f9a-12e2-426d-988a-ad736f5afcd3" class="">Zookeeper is used, only to store the current configuration and ensure machines agree on it. Other functions are done more efficiently by the CM instead
(managing leases, detecting failures, coordinate recovery)</p></details></li></ul><ul id="61943aaa-2c44-4fbf-8c4e-0a0c942c9a2a" class="toggle"><li><details open=""><summary><strong>How can the configuration change</strong></summary><ul id="5c3cb707-5bcb-4bb4-a76b-a89fb31d783c" class="bulleted-list"><li>failure of a machine</li></ul><ul id="f4373322-7b53-4714-98af-0a2fd3fa9e81" class="bulleted-list"><li>addition of a machine</li></ul></details></li></ul><ul id="45a0dc85-3fc7-417d-9546-7967e2ff2b9a" class="toggle"><li><details open=""><summary><strong>How are configuration changes performed</strong></summary><p id="c8301743-2a62-4907-8399-d1a27c89b3a9" class="">the CM invokes Zookeeper once per configuration change to update it</p></details></li></ul></details></li></ul><ul id="e1ab743b-f794-4d5b-93f6-4f7ee852a19a" class="toggle"><li><details open=""><summary><strong>Memory</strong></summary><ul id="64fa2bcf-3004-4c8f-bcb9-e0e0281f2d97" class="toggle"><li><details open=""><summary><strong>All data is stored in memory as non-volatile DRAM is used</strong></summary><ul id="eac48598-65d8-485d-8304-5f7f65037707" class="bulleted-list"><li><strong>+ve:</strong> access time is reduced</li></ul><ul id="956ddde1-d2d4-41c0-9cb7-bf44ded95d1e" class="bulleted-list"><li><strong>-ve</strong>: amount of data is limited to that which can fit in memory (petabytes)</li></ul></details></li></ul><ul id="1cf81b07-c121-4741-95ef-8de6d8fab4c5" class="toggle"><li><details open=""><summary><strong>Three-Tiered Allocation</strong></summary><ul id="c6505ee0-ba32-4f9e-a07a-6158ccb79307" class="bulleted-list"><li>slabs: used by threads for private allocation of small objects from blocks</li></ul><ul id="232ecd60-7f70-417b-8172-5b826f7ad3ec" class="bulleted-list"><li>blocks: 1 mb blocks of memory, across a machine</li></ul><ul id="4035e663-89f0-451c-b4e3-6539eb46a7c2" class="toggle"><li><details open=""><summary><strong>regions</strong></summary><ul id="94c0f36c-3a57-43d9-8ab9-75f67badbd40" class="bulleted-list"><li>contiguous 2GB blocks of memory, distributed across the cluster</li></ul><ul id="3301b3f9-7259-4008-a008-b6e937e99f66" class="bulleted-list"><li>used to store objects</li></ul><ul id="d950f9d8-7954-4a30-be03-ddfe737a0a11" class="bulleted-list"><li>must be registered with Network Interface Controller in order to be available for remote access</li></ul></details></li></ul></details></li></ul><ul id="2e46c4c3-977d-4f14-9eb9-ee9c238f0213" class="toggle"><li><details open=""><summary><strong>How are memory regions allocated</strong></summary><p id="4b2f95b7-e20f-4175-8ff8-5472257763b9" class="">machines contact the CM. The CM selects replicas such that the number of regions stored on each machine is balanced, each replica is in a different failure domain and adheres to any locality constraints specified by the application</p></details></li></ul><ul id="13bd94e4-33d9-437a-8a16-49d3c9d70f25" class="toggle"><li><details open=""><summary>c<strong>ircular buffer queues</strong></summary><ul id="c4cd64f4-c63c-4772-a6cb-3ecbe2ae47e7" class="bulleted-list"><li>persistent (due to non-volatile DRAM used)</li></ul><ul id="8d1d7ed0-99af-4755-9606-2dd7d41b781e" class="bulleted-list"><li>serve as store for transactional logs (write-ahead) as well as write operations</li></ul><ul id="daf476af-9417-4bdb-b8bb-6d8063fd9f76" class="bulleted-list"><li>senders append records at the tail of the receiver&#x27;s log without involving its CPU (one-sided RDMA). The receiver periodically polls the head of the log to process them and lazily updates senders when truncating the log</li></ul></details></li></ul><ul id="875482de-271e-4ae1-b244-be02a2e7a5c6" class="toggle"><li><details open=""><summary><strong>How are objects read</strong></summary><ul id="590ae20e-430d-44fa-b8aa-93bda72a5a60" class="bulleted-list"><li>objects are always read from a region&#x27;s primary copy</li></ul><ul id="037a8b82-5fe8-4660-8ac8-4de8833fe313" class="bulleted-list"><li>using either local memory access or one-sided RDMA depending on where the object is located</li></ul></details></li></ul><ul id="f58e6885-ae0d-431f-a580-253e3d76f784" class="toggle"><li><details open=""><summary><strong>What is guaranteed for object reads (during transaction execution)</strong></summary><ul id="eb873081-b7eb-4179-b56c-2c0b6287e4f8" class="bulleted-list"><li>atomicity for individual object reads</li></ul><ul id="e0b900c9-641d-4051-995c-5b5eea8143ed" class="bulleted-list"><li>only committed data is read</li></ul><ul id="41961605-8b0f-4ae9-bd6f-3c7a34ba0119" class="bulleted-list"><li>successive reads of the same object return the same data</li></ul><ul id="235019dd-4bf4-498a-9ce1-d2ee71a516d2" class="bulleted-list"><li>the latest value is returned</li></ul></details></li></ul><ul id="8aee655e-2166-45c4-b738-88102c64ed3e" class="toggle"><li><details open=""><summary><strong>What isn&#x27;t guaranteed for object reads</strong></summary><ul id="b807d3e4-45cc-40ba-80eb-ef1f63c4ff3c" class="bulleted-list"><li>atomicity of reads across different objects</li></ul><ul id="566301c6-de32-450f-a28f-2cdb55a1a9be" class="bulleted-list"><li><strong>+ve </strong>: consistency checks can be deferred until commit time</li></ul><ul id="e60d158f-53c2-48d8-9f3c-aed81df170d5" class="bulleted-list"><li><strong>-ve </strong>: applications must handle temporary inconsistencies</li></ul></details></li></ul></details></li></ul><ul id="6d0eb524-f514-4b4d-af59-7771876c7e54" class="toggle"><li><details open=""><summary><strong>Communication</strong></summary><ul id="8a5a59ca-8cfa-4b99-9922-81caf66a22b2" class="bulleted-list"><li>one-sided RDMA operations is used to bypass TCP/IP for efficient messaging</li></ul><ul id="56800021-9471-4c97-bf97-184b864810ce" class="toggle"><li><details open=""><summary><strong>Network Interface Controller (NIC)</strong></summary><ul id="e8f50a7a-c102-44c4-aa1c-7f69f9eac196" class="bulleted-list"><li>has a message rate bottleneck<p id="390421d7-7c92-4ca0-8513-468adee2f619" class="">this is solved by using two Infiniband (56 Gbps) NICs</p></li></ul><ul id="9a00b00c-8a0b-4069-a1c3-de433458f4e3" class="bulleted-list"><li>its page table is too small<p id="a8ccbf67-408f-4d53-8a6e-0b15128f94ee" class="">this is solved by using 2GB regions in memory</p></li></ul></details></li></ul><ul id="de873692-6377-4069-828c-7c356b8b687e" class="toggle"><li><details open=""><summary><strong>read operations </strong></summary><figure id="237fdddf-ac63-416c-83ff-84383d678ac5" class="image"><a href="https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Farsalanc%2F_tl-RHXyc7?alt=media&amp;token=101edfd4-a1fb-479b-a596-0cc39f57dcc9"><img src="https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Farsalanc%2F_tl-RHXyc7?alt=media&amp;token=101edfd4-a1fb-479b-a596-0cc39f57dcc9"/></a></figure><ul id="1f0648f7-c5d0-45e7-aff3-db882d087969" class="bulleted-list"><li>received by NIC</li></ul><ul id="76480fdb-7eba-4980-bbfc-5f562917b0c8" class="bulleted-list"><li>2x improvement as half as many network packets required</li></ul><ul id="0b6a907b-80fa-456b-9a52-b810167469bc" class="bulleted-list"><li>data is fetched from memory without the CPU being involved</li></ul></details></li></ul><ul id="1696b006-f373-475b-8c3d-dc4bda1eb03a" class="toggle"><li><details open=""><summary><strong>write operations</strong></summary><figure id="2d7a82f8-f646-4f12-91f1-9ae226705925" class="image"><a href="https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Farsalanc%2FvTTuPbB8yn?alt=media&amp;token=aaa8b0b0-5474-4377-bf74-4c9285cb634c"><img src="https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Farsalanc%2FvTTuPbB8yn?alt=media&amp;token=aaa8b0b0-5474-4377-bf74-4c9285cb634c"/></a></figure><ul id="c910ae76-ae78-41ed-9b12-c447407d8899" class="bulleted-list"><li>NIC issues DMA to circular buffer to write the data at its tail</li></ul><ul id="2bd3c465-e639-4b4a-a86f-d31a94cc24c4" class="bulleted-list"><li>sender receives ACK from NIC without having to wait for CPU</li></ul><ul id="ec313130-6a66-4318-bb37-de9bf498bfcd" class="bulleted-list"><li>CPU polls buffer in order to process messages</li></ul></details></li></ul></details></li></ul></details></li></ul><ul id="de675f79-1f99-40ce-aaec-3e8f657642ed" class="toggle"><li><details open=""><summary><strong>Protocols</strong></summary><ul id="b507b48a-8e01-4bac-8212-d17e4945baca" class="toggle"><li><details open=""><summary><strong>Commit</strong></summary><ul id="2eeab811-38d3-41fe-b433-52e1280749ed" class="toggle"><li><details open=""><summary><strong>four-phased, does not use two-phase commit, unlike the original FaRM paper</strong></summary><figure id="498a24be-8bfa-46e8-b7f1-f7b34a12a236" class="image"><a href="https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Farsalanc%2FWkItOU7cpI?alt=media&amp;token=d0f62d6a-c19a-4ce3-94f3-845470075d46"><img src="https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Farsalanc%2FWkItOU7cpI?alt=media&amp;token=d0f62d6a-c19a-4ce3-94f3-845470075d46"/></a></figure><p id="a87878ce-1aa6-4408-a7dd-49dae10e0628" class=""><em>four phase commit protocol (this paper)</em></p><p id="1d6c40ac-fb32-4d7e-bdc9-67b706eaaaae" class=""><em>C: coordinator, P_: primary, B_: backup</em></p><p id="2eaa87d1-a7d2-4a7c-a8f8-089552dbf273" class=""><em>gears represent CPU processing</em></p><p id="cb39a989-3123-4b08-9727-22cdb92a2575" class="">
</p><figure id="7a4d48cf-857b-4313-9be4-717223430089" class="image"><a href="https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Farsalanc%2FBmbHG5Yv9E?alt=media&amp;token=cae8a968-aa1c-4e8a-a656-1b8faf1e6a3d"><img src="https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Farsalanc%2FBmbHG5Yv9E?alt=media&amp;token=cae8a968-aa1c-4e8a-a656-1b8faf1e6a3d"/></a></figure><p id="c37ce4e7-308b-427e-b2f1-7490074f1a44" class=""><em>two phase commit protocol</em></p><p id="f6aedd77-5b34-4ae7-a91a-0242eadb0a7b" class=""><em>C: coordinator, P_: primary, B_: backup</em></p><p id="d0e09567-dbe9-4534-ab65-1d362ec02147" class=""><em>gears represent CPU processing</em></p></details></li></ul><ul id="396f40e3-9327-4923-8a95-0101515f248b" class="toggle"><li><details open=""><summary><strong>How does the four phase protocol improve on the two phase protocol</strong></summary><ul id="28163814-4688-43b2-aec6-77e0f1920540" class="bulleted-list"><li>avoids the need for 2 roundtrips</li></ul><ul id="5cee2517-4e31-4e24-92a7-4766ed1c064f" class="bulleted-list"><li>reduces the number of messages required</li></ul><ul id="55c773e9-e7e7-4217-a7d8-0df7ab35bb2e" class="bulleted-list"><li>avoids cpu processing needed at both primaries and backups during both phases</li></ul></details></li></ul><ul id="57a7bad9-463d-4e3a-8fb5-328a7c7d79b3" class="toggle"><li><details open=""><summary><strong>Phases</strong></summary><ul id="06dc8028-48d3-4b25-8268-2be66cbb349a" class="toggle"><li><details open=""><summary><strong>What happens if any of the phases fail before the transaction is committed</strong></summary><p id="fcda0848-652d-4afc-87af-79fc4f44fd00" class="">the transaction is aborted</p></details></li></ul><ul id="2cf509ed-9de1-4415-8a8a-02a6ccc27f19" class="toggle"><li><details open=""><summary><strong>Lock</strong></summary><ul id="d8024b46-c934-4baa-b96c-fa3a2ed2b9ee" class="bulleted-list"><li>the coordinator writes a LOCK record to primaries containing versions and new values of all written objects</li></ul><ul id="43ae20c4-f173-45a8-8f34-2b59bffa1943" class="bulleted-list"><li>primaries attempt to lock the objects at a specified version</li></ul><ul id="d8060aa1-83f9-4951-aa09-77767839b248" class="bulleted-list"><li>primaries send back a message reporting whether locks were acquired</li></ul><ul id="681d45e0-ace1-42db-8031-7351a3079758" class="toggle"><li><details open=""><summary><strong>How can locking fail</strong></summary><ul id="ce51f452-06a7-4512-a064-fd78b18177d2" class="bulleted-list"><li>an object&#x27;s version changed since it was read by the transaction</li></ul><ul id="334ab3be-9b47-42c5-84a9-59c3a3af1c0d" class="bulleted-list"><li>the object is locked by another transaction</li></ul></details></li></ul></details></li></ul><ul id="7dddcff7-59be-4de0-b0d3-785d8a196a4f" class="toggle"><li><details open=""><summary><strong>Validate</strong></summary><p id="219a36e2-5b6b-4c5b-9cea-70a6de9f2740" class="">the coordinator obtains versions of all objects that were read (but not written) during the transaction, from primaries</p><ul id="6003943e-13cd-47c0-867d-1e5a1c8acd5c" class="toggle"><li><details open=""><summary><strong>How can validation fail</strong></summary><ul id="4f96ad67-0c90-4f1d-aaed-a91f36a77c07" class="bulleted-list"><li>if an object&#x27;s version has changed</li></ul></details></li></ul></details></li></ul><ul id="24344a53-ed0b-42e2-9e9e-b1c4e84ef48d" class="toggle"><li><details open=""><summary><strong>Commit backup</strong></summary><p id="a1d17733-a98e-4d00-b8a4-534a9eb70c88" class="">the coordinator writes a commit record to the logs at each backup
(it receives an ACK from the backup&#x27;s NIC without the backup&#x27;s CPU being involved)</p><ul id="3e81504d-f0d8-4a89-a432-81700708ceb9" class="toggle"><li><details open=""><summary><strong>How can commit backup fail</strong></summary><ul id="1f4bc38e-0238-423c-b95a-ea5434f09644" class="bulleted-list"><li>if any hardware failure occurs</li></ul></details></li></ul></details></li></ul><ul id="fe9cf7cc-0b25-44f5-ae22-b79771cb7f6c" class="toggle"><li><details open=""><summary><strong>Commit primary</strong></summary><ul id="44adff3f-bd7c-49de-b24e-b87cceff135c" class="bulleted-list"><li>after all commit backups have been ACKed, the coordinator writes a record to the logs at each primary</li></ul><ul id="21d10aaf-9c16-472b-bbf7-e43db5bae603" class="bulleted-list"><li>the coordinator reports completion to the application - at least one ACK for such a record was received (including itself)</li></ul><ul id="c039bc69-1260-4acc-ad4b-539da3dc53b8" class="bulleted-list"><li>primaries process the records by updating the objects in place, incrementing their versions and unlocking them. This exposes the writes committed by the transaction</li></ul></details></li></ul><ul id="ca731d20-a12e-44a9-a2a9-e65283b0d6bb" class="toggle"><li><details open=""><summary><strong>Truncate</strong></summary><ul id="b6d9e5b0-7ae2-4c50-bf01-8f652f3a0324" class="bulleted-list"><li>the coordinator lazily truncates logs at primaries and backups after receiving ACKs from all primaries</li></ul><ul id="61cd7ff4-1bf1-4a4d-9628-78364266ea6f" class="bulleted-list"><li>backups apply updates to their copies of the objects at truncation time</li></ul></details></li></ul></details></li></ul><ul id="e16b98f9-6171-41aa-88e1-d590b2cdff4a" class="toggle"><li><details open=""><summary><strong>Comparison with two phase commit protocol in Spanner</strong></summary><figure id="f6a819f9-bf97-4881-be62-447855d481bd" class="image"><a href="https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Farsalanc%2FMNeJxLbZyQ?alt=media&amp;token=6a2ecdaa-3c6e-455c-9266-5c6ffb9bcef7"><img src="https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Farsalanc%2FMNeJxLbZyQ?alt=media&amp;token=6a2ecdaa-3c6e-455c-9266-5c6ffb9bcef7"/></a></figure></details></li></ul></details></li></ul><ul id="f9c50aa1-9b7c-46f5-aede-ac4c4ffa46d2" class="toggle"><li><details open=""><summary><strong>Recovery</strong></summary><ul id="2a3027d2-1019-4665-a3b5-fe11e4ca7a75" class="toggle"><li><details open=""><summary><strong>What techniques are used to ensure high availability</strong></summary><ul id="2046656c-1364-4d81-b3da-c3c3623257b9" class="bulleted-list"><li><em>data</em> is available quickly by having a backup promoted to primary (after lock recovery). External clients do not have to wait while region replicas are brought up to date</li></ul><ul id="77212db3-3609-46eb-a1bb-d91379da0f5e" class="bulleted-list"><li><em>short failure detection time</em> (10 ms) is enabled by having short leases. This is achieved by a fast network and dedicated network queues, dedicated and highly prioritized thread for managing leases as well as memory pre-allocation</li></ul><ul id="35f64155-c34d-4fd0-8f98-76a499e75e03" class="toggle"><li><details open=""><summary><strong><em>parallelism</em></strong><strong> is used</strong></summary><ul id="330da69e-a422-4c90-ac80-1fde46a2e22b" class="bulleted-list"><li>new transactions (on unaffected regions) occur in parallel with:<ul id="87310031-8157-4667-bf10-38dbd16ad9fd" class="bulleted-list"><li>transaction recovery</li></ul><ul id="3aa62dfe-54a4-44dc-95c8-3e52120ffb1a" class="bulleted-list"><li>data recovery (occurs after transaction recovery)</li></ul></li></ul><ul id="b15d9ab3-d6ca-4fcb-ad1c-bbee53977b98" class="bulleted-list"><li>recovery is parallelized across regions, machines and threads</li></ul></details></li></ul><ul id="31461bbb-b31b-4f6c-b377-f1cf5586fcb4" class="bulleted-list"><li>work is minimized by only limiting it to transactions and regions that were affected by reconfiguration</li></ul></details></li></ul><ul id="bfb4be73-f681-4c3f-be13-28c2c9b62701" class="toggle"><li><details open=""><summary><strong>What is a </strong><em><strong>recovering transaction</strong></em><strong> </strong></summary><ul id="1a4ed2fb-a348-4381-890d-a82d81bf3978" class="bulleted-list"><li>one whose commit phase spans configuration changes and for which either one of the following has changed:<ul id="0f95d56c-81b6-478f-a9f0-831e31e2a562" class="bulleted-list"><li>replica of a written object</li></ul><ul id="12266099-7f0d-4284-8941-316060bc47b4" class="bulleted-list"><li>primary of a read object</li></ul><ul id="463982c5-cfe0-49ae-9b1d-c8e79c4e6e8f" class="bulleted-list"><li>coordinator</li></ul></li></ul><ul id="ae81f753-f489-4d39-a16d-170882647639" class="bulleted-list"><li>it must be agreed upon as such by all machines</li></ul></details></li></ul><ul id="eb6bc5cb-0c7e-4c92-941c-63c54cb21613" class="toggle"><li><details open=""><summary><strong>How is strict serializability ensured through the course of transaction recovery</strong></summary><ul id="5b566e00-706d-4dec-9e72-d5b0c38a6962" class="bulleted-list"><li>recovery preserves the outcome of transactions that were previously committed or aborted</li></ul><ul id="ab6fec9c-f5b1-4623-a8ab-b6e0af2897f7" class="bulleted-list"><li>if a recovering transaction was committed, its log record is guaranteed to be processed and accepted before the log draining step</li></ul></details></li></ul><ul id="10ea378c-7c37-4bac-af9e-2400bda4828c" class="toggle"><li><details open=""><summary><strong>Phases</strong></summary><ul id="6ea45525-7a80-4fc5-89ca-3035f3c0554a" class="toggle"><li><details open=""><summary><strong>Failure detection</strong></summary><ul id="cfba47cf-ed9f-47db-b273-df279b7f41ab" class="bulleted-list"><li>leases are granted using a 3-way handshake</li></ul><ul id="c79ce3b8-5f36-401f-851a-1b691c32480a" class="bulleted-list"><li>the expiry of a lease triggers failure recovery</li></ul><ul id="bf3d2969-f697-4ce2-992c-53f9dd3ce3dd" class="bulleted-list"><li>leases are prevented from expiring through heartbeat messages</li></ul></details></li></ul><ul id="aadfe1b8-7b92-40ca-afbc-b2b1ce884b65" class="toggle"><li><details open=""><summary><strong>Reconfiguration</strong></summary><figure id="6253557b-df85-4ff6-ab33-bc054efd4787" class="image"><a href="https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Farsalanc%2FBaSDRx7TAv?alt=media&amp;token=01a8beca-87d2-4ecc-8f76-14b1ddf5c686"><img src="https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Farsalanc%2FBaSDRx7TAv?alt=media&amp;token=01a8beca-87d2-4ecc-8f76-14b1ddf5c686"/></a></figure><ul id="185a84be-8ea2-49dd-b82a-2919fa0df1aa" class="bulleted-list"><li>initiated when lease expires</li></ul><ul id="47a0d9e1-289a-4589-a937-0acd46793dc2" class="bulleted-list"><li>the new CM remaps regions previously assigned to failed machines</li></ul><ul id="c41f32e7-0f7a-45e5-b476-6ecce16ed7ef" class="bulleted-list"><li>all external client requests are blocked when applying a new configuration and unblocked after it has been committed</li></ul><ul id="f66c4aec-5040-440e-a8b8-fcefb30a712f" class="toggle"><li><details open=""><summary><strong>If the CM is suspected of failure, how are simultaneous reconfiguration attempts prevented</strong></summary><p id="a31ddf75-f378-4782-95df-2daaedd50262" class="">the non-CM machine first requests a backup CM to initiate reconfiguration. Only if the configuration remains unchanged after a timeout does the non-CM machine attempt reconfiguration itself</p></details></li></ul><ul id="8e8a34ef-88c0-46b0-aa83-8e1ac869b244" class="toggle"><li><details open=""><summary><strong>In case of a partition, how is the CM ensured to be in the larger partition</strong></summary><p id="4608e8d0-6ab0-4a95-bc61-057f4d985fb8" class="">a new CM issues an RDMA read to all machines in the configuration (except the machine that is suspected of failure) and proceeds with reconfiguration only if it obtains a majority of responses</p></details></li></ul><ul id="7b5a660a-125a-4bb6-8b19-6580b5ff50a0" class="toggle"><li><details open=""><summary><strong>How can reconfiguration fail</strong></summary><ul id="7fba951f-2ed3-4ff9-9dae-91a005056917" class="bulleted-list"><li>if their exist regions that have lost all their replicas</li></ul><ul id="2f4e2096-7a05-42f4-93e1-2545a5f400b9" class="bulleted-list"><li>there is no space to re-replicate regions</li></ul></details></li></ul></details></li></ul><ul id="56bfa5f4-eb39-4330-9c77-9ed4afe93c12" class="toggle"><li><details open=""><summary><strong>Transaction recovery</strong></summary><ul id="8a460616-ea20-46ab-b184-023d02ef5ce3" class="bulleted-list"><li>if a primary fails, a backup is promoted to be the new primary</li></ul><ul id="016439e6-0a60-460c-a1eb-d415c50c9cc2" class="bulleted-list"><li>logs are drained to ensure all relevant records are processed. Following this, messages from the old configuration are no longer processed</li></ul><ul id="4c99d1e3-a02e-43ea-a1dd-cd6898c3242a" class="bulleted-list"><li>the primary of each region then builds the complete set of recovering transactions that affect the region</li></ul><ul id="f6dbedc8-985d-4ec4-a1c1-3cb77d205d6a" class="bulleted-list"><li>the transactions are sharded across threads in order to be recovered</li></ul><ul id="b08116a7-ec26-48d0-8e9b-74464c473354" class="bulleted-list"><li>locks are acquired for objects modified by recovering transactions. Following this, objects can be read and updates can be committed to this region in parallel with subsequent recovery steps</li></ul></details></li></ul><ul id="cc558c57-3564-400d-b90e-8bf015682a6f" class="toggle"><li><details open=""><summary><strong>Data recovery</strong></summary><ul id="0991e696-d6cf-4767-9b01-44c6431b49c4" class="bulleted-list"><li>replication for new backups in order to be able to tolerate f replica failures in the future</li></ul><ul id="ed335e05-d242-49b4-9184-d27c37377a4a" class="bulleted-list"><li>as it is not critical for normal operation, it is delayed in order to prioritize lock recovery which impacts latency</li></ul><ul id="8c44cdef-5b56-40de-80b7-6085f679a33c" class="bulleted-list"><li>each thread uses RDMA to read a block at a time from the primary</li></ul></details></li></ul></details></li></ul></details></li></ul></details></li></ul><ul id="0a83f39c-a610-4f52-aa61-e8228214a844" class="toggle"><li><details open=""><summary><strong>Further Questions</strong></summary><ul id="035a6567-d01a-4f26-adab-58dc647de85b" class="toggle"><li><details open=""><summary>Suppose there are two FaRM transactions that both increment the same object. They start at the same time and see the same initial value for the object. One transaction completely finishes committing (see Section 4 and Figure 4). Then the second transaction starts to commit. There are no failures. What is the evidence that FaRM will use to realize that it must abort the second transaction? At what point in the Section 4 / Figure 4 protocol will FaRM realize that it must abort?</summary><ul id="2c78f299-136e-49c5-8083-0cef08a13d30" class="bulleted-list"><li>FaRM will use the object&#x27;s version number as evidence. Since both of them will have read the same value initially and one of the transaction has incremented the object&#x27;s version (in the Commit primary phase), the other transaction will detect the changed version number in the Lock phase, after it receives the LOCK record from the coordinator. This will cause it to abort</li></ul></details></li></ul><ul id="2a8dd010-19f3-43c9-aa15-ffbb21d1f151" class="bulleted-list"><li>Why is RPC used instead of one-sided RDMA reads if the primary holds more than a certain number (4) of objects?</li></ul><ul id="2428566f-5144-46ef-b2ed-aedb5d6edc42" class="bulleted-list"><li>How does the centralized approach to region allocation provide more flexibilty to satisfy failure independence and locality constraints (compared with consistent hashing)?</li></ul><ul id="0f61e8c1-165d-4748-91bb-534543ff6ef5" class="bulleted-list"><li>Why is Zookeeper used for configuration consensus instead of vertical Paxos (as in the original FaRM paper)?</li></ul><ul id="f96735d5-229c-43d8-b113-bf71d7d4102e" class="bulleted-list"><li>In reconfiguration, how does <em>precise membership</em> prevent objects from being mutated until after lease expiry?</li></ul><ul id="916b40dc-8725-44c8-b243-435939f9119d" class="toggle"><li><details open=""><summary>Why are objects that are written not validated in the <em>validate</em> phase of a transaction commit?</summary><ul id="523a803b-fa0d-4b38-bc83-9ffd7810670e" class="bulleted-list"><li>they have already been validated in the Lock phase</li></ul></details></li></ul><ul id="c3d2d3ca-078e-4d23-bc11-68e7b1ff5999" class="bulleted-list"><li>Why is coordinator state not replicated?</li></ul></details></li></ul><ul id="28920fcb-61e1-47aa-b04b-0956c52bb61a" class="toggle"><li><details open=""><summary><strong>See Also</strong></summary><p id="3bb37270-d013-4c3e-9644-6fc28756cebe" class=""><a href="https://pdos.csail.mit.edu/6.824/notes/l-farm.txt">https://pdos.csail.mit.edu/6.824/notes/l-farm.txt</a></p><p id="35aacdcc-4893-47a1-84ee-5f9098e0a177" class=""><a href="https://pdos.csail.mit.edu/6.824/papers/farm-faq.txt">https://pdos.csail.mit.edu/6.824/papers/farm-faq.txt</a></p><p id="c7a93cfe-3d26-4334-b7bf-1a0207dcbdd2" class=""><a href="https://blog.acolyer.org/2016/01/14/no-compromises/">https://blog.acolyer.org/2016/01/14/no-compromises/</a></p><p id="593ef626-fb7c-4548-966e-96b58edda37d" class=""><em>Transaction Processing, Concepts and Techniques</em> (Gray, Reuter)</p></details></li></ul><ul id="8867f6b4-6698-4f0a-9e3b-5b4a257808c9" class="toggle"><li><details open=""><summary><strong>References</strong></summary><p id="8a6b166e-51b2-4343-b6e0-ddee99164b62" class=""><a href="https://pdos.csail.mit.edu/6.824/papers/farm-2015.pdf">https://pdos.csail.mit.edu/6.824/papers/farm-2015.pdf</a></p><p id="892a9036-ad0c-4d51-aa28-c84c01cc3e2f" class=""><a href="https://pdos.csail.mit.edu/6.824/questions.html?q=q-farm&amp;lec=14">https://pdos.csail.mit.edu/6.824/questions.html?q=q-farm&amp;lec=14</a></p><p id="19291a7d-cb19-427f-b023-e32545fca23c" class=""><a href="https://www.usenix.org/system/files/conference/nsdi14/nsdi14-paper-dragojevic.pdf">https://www.usenix.org/system/files/conference/nsdi14/nsdi14-paper-dragojevic.pdf</a></p><p id="d4d3ca24-2f41-4dc2-9878-bd54e183546a" class=""><a href="https://docs.oracle.com/cd/A87860_01/doc/appdev.817/a86030/adx16nt4.htm">https://docs.oracle.com/cd/A87860_01/doc/appdev.817/a86030/adx16nt4.htm</a></p><p id="a83b0e08-a811-41c7-906e-2331c82959a0" class=""><a href="https://www.youtube.com/watch?v=VtUpBtAOizc">https://www.youtube.com/watch?v=VtUpBtAOizc</a></p><p id="a98b27d3-fc2b-4dca-a14a-1e4ed809069f" class=""><a href="https://github.com/ooibc88/gam/tree/farm">https://github.com/ooibc88/gam/tree/farm</a></p></details></li></ul><p id="a41af47c-e76a-4675-899d-c297e0b53690" class="">
</p></div></article></body>