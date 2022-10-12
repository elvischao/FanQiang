# FanQiang-2020 科学上网方法入门备忘
2020最新科学上网方法整理—翻墙-梯子-vpn-v2ray-trojan-ssr 小白新手
<a target="_blank" rel="noopener noreferrer" href="https://github.com/elvischao/FanQiang/blob/master/img/pinterest.png"><img src="https://github.com/elvischao/FanQiang/blob/master/img/pinterest.png" alt="" style="max-width:100%;"></a>
<p>这是一份简明的科学上网（翻墙）指南，只为学习国外先进科学技术，提升工作效率，方便查找资料使用。</p>
<br>
<br>
<p><strong>遵守中国互联网法，做一个遵纪守法的好公民。</strong></p>
<br>
<br>
<br>
<h2><a id="user-content-前言" class="anchor" aria-hidden="true" href="#前言"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>前言</h2>
<p><strong>翻墙</strong>（又叫 <strong>科学上网</strong>），它决定着我们很多人的网络生活质量，Gmail 的邮件能不能回，能不能正常使用 Google 搜索引擎精确查找问题，能不能看特朗普的动态，能不能在社交媒体上跟踪自己感兴趣的群组，能不能看国外的公开课视频，Netflix、HBO上的新剧能不能追，都取决于我们能否访问外网。</p>
<p>科学上网的原理：通过 VPN、ss、ssr、v2ray 等这些技术对上网流量、数据加密，以此躲避 GFW 防火墙检测实现自由上网，也被用于数据传输安全、网络匿名、隐私保护等。</p>
<p><strong>注：</strong> 网络不是法外之地，我们的目的是学习国外先进科学技术，切莫在网络发表不当言论。
<br>
<br>
<br></p>
<h2><a id="user-content-目录" class="anchor" aria-hidden="true" href="#目录"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>目录</h2>
<hr>
<ul>
<li><a href="#1"><strong>小白入门 —— 使用 VPN</strong></a></li>
<li><a href="#2"><strong>SS、SSR、V2ray 机场</strong></a></li>
</ul>

<ul>
<li><a href="#3"><strong>搭建自己的科学上网服务器</strong></a></li>
</ul>
<br>
<br>
<br>
<br>
<h2><a id="user-content-一小白入门--使用-vpn" class="anchor" aria-hidden="true" href="#一小白入门--使用-vpn"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-1">一、小白入门 —— 使用 VPN</span></h2>
<br>
<br>
<h2><a id="user-content-二ssssrv2ray-机场" class="anchor" aria-hidden="true" href="#二ssssrv2ray-机场"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-2">二、SS、SSR、V2ray 机场</span></h2>
<p><a target="_blank" rel="noopener noreferrer" href="https://github.com/elvischao/FanQiang/blob/master/img/jcdq.png"><img src="https://github.com/elvischao/FanQiang/blob/master/img/jcdq.png" alt="" style="max-width:100%;"></a></p>
<p><strong>机场是老司机和小白皆可的一种方案，性价比高，省事省心，稳定性与速度兼顾。</strong></p>
<br>
<br>
<ul>
<li>
<h3><a id="user-content-推荐机场-just-my-socks-详细图文教程" class="anchor" aria-hidden="true" href="#推荐机场-just-my-socks-详细图文教程"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-4"><a href="https://dwz.afunv.top/3" rel="nofollow">推荐机场 阿凡梯 详细图文教程</a></span></h3>
</li>
</ul>
<p>（备用链接：<a href="https://dwz.afunv.top/3" rel="nofollow">https://dwz.afunv.top/3</a></p>
<ul>
<li>
<h3><a id="user-content-套餐大全" class="anchor" aria-hidden="true" href="#套餐大全"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><a href="https://dwz.afunv.top/3" rel="nofollow">套餐大全</a></h3>
</li>
</ul>
<br>
<p><strong>AFunVPN阿凡梯 优势：</strong></p>
<ul>
<li>免去个人搭建代理流程，降低科学上网门槛，更适合 初级/小白用户。</li>
<li>高性价比，服务好，支持远程技术支持</li>
<li>保证可以用，省事省心。</li>
</ul>
<p>(备用链接：<a href="https://dwz.afunv.top/3" rel="nofollow">https://dwz.afunv.top/3</a>)</p>
<br>
<br>
<br>
<hr>
<p><strong>如果您是 Github 用户欢迎 star 和 Fork，有任何问题</strong></p>
</article>
</div>
