# FerretDB

[![Go Reference](https://pkg.go.dev/badge/github.com/FerretDB/FerretDB/ferretdb.svg)](https://pkg.go.dev/github.com/FerretDB/FerretDB/ferretdb)

[![Go](https://github.com/FerretDB/FerretDB/actions/workflows/go.yml/badge.svg?branch=main)](https://github.com/FerretDB/FerretDB/actions/workflows/go.yml)
[![codecov](https://codecov.io/gh/FerretDB/FerretDB/branch/main/graph/badge.svg?token=JZ56XFT3DM)](https://codecov.io/gh/FerretDB/FerretDB)

[![Security](https://github.com/FerretDB/FerretDB/actions/workflows/security.yml/badge.svg?branch=main)](https://github.com/FerretDB/FerretDB/actions/workflows/security.yml)
[![Packages](https://github.com/FerretDB/FerretDB/actions/workflows/packages.yml/badge.svg?branch=main)](https://github.com/FerretDB/FerretDB/actions/workflows/packages.yml)
[![Docs](https://github.com/FerretDB/FerretDB/actions/workflows/docs.yml/badge.svg?branch=main)](https://github.com/FerretDB/FerretDB/actions/workflows/docs.yml)

 
<p dir="auto"><a href="https://pkg.go.dev/github.com/FerretDB/FerretDB/ferretdb" rel="nofollow"><img src="https://camo.githubusercontent.com/c35132b3a1253fd7f9a9dcf8fa5aad6cdb24a0d43d2c327b0c0c8dbda0078a22/68747470733a2f2f706b672e676f2e6465762f62616467652f6769746875622e636f6d2f46657272657444422f46657272657444422f66657272657464622e737667" alt="去参考" data-canonical-src="https://pkg.go.dev/badge/github.com/FerretDB/FerretDB/ferretdb.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://github.com/FerretDB/FerretDB/actions/workflows/go.yml"><img src="https://github.com/FerretDB/FerretDB/actions/workflows/go.yml/badge.svg?branch=main" alt="去" style="max-width: 100%;"></a>
<a href="https://codecov.io/gh/FerretDB/FerretDB" rel="nofollow"><img src="https://camo.githubusercontent.com/edbb6891780e9bf019a0bce7f20abec676e4022a6de7dc83a282f9ff8b2df036/68747470733a2f2f636f6465636f762e696f2f67682f46657272657444422f46657272657444422f6272616e63682f6d61696e2f67726170682f62616467652e7376673f746f6b656e3d4a5a353658465433444d" alt="代码科夫" data-canonical-src="https://codecov.io/gh/FerretDB/FerretDB/branch/main/graph/badge.svg?token=JZ56XFT3DM" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://github.com/FerretDB/FerretDB/actions/workflows/security.yml"><img src="https://github.com/FerretDB/FerretDB/actions/workflows/security.yml/badge.svg?branch=main" alt="安全" style="max-width: 100%;"></a>
<a href="https://github.com/FerretDB/FerretDB/actions/workflows/packages.yml"><img src="https://github.com/FerretDB/FerretDB/actions/workflows/packages.yml/badge.svg?branch=main" alt="套餐" style="max-width: 100%;"></a>
<a href="https://github.com/FerretDB/FerretDB/actions/workflows/docs.yml"><img src="https://github.com/FerretDB/FerretDB/actions/workflows/docs.yml/badge.svg?branch=main" alt="文档" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FerretDB 的成立是为了成为 MongoDB 事实上的开源替代品。 FerretDB 是一个开源代理，使用 PostgreSQL 或 SQLite 作为数据库引擎，将 MongoDB 5.0+ 有线协议查询转换为 SQL。</font></font></p>
<section class="js-render-needs-enrichment render-needs-enrichment position-relative" data-identity="304f277b-708c-4bfa-a19d-8527a73ee434" data-host="https://viewscreen.githubusercontent.com" data-src="https://viewscreen.githubusercontent.com/markdown/mermaid?docs_host=https%3A%2F%2Fdocs.github.com" data-type="mermaid" aria-label="美人鱼渲染的输出容器">
  <div class="js-render-enrichment-target" data-json="{&quot;data&quot;:&quot;flowchart LR\n  A[\&quot;Any application\\nAny MongoDB driver\&quot;]\n  F{{FerretDB}}\n  P[(PostgreSQL)]\n  S[(\&quot;SQLite\&quot;)]\n\n  A -- \&quot;MongoDB protocol\\nBSON\&quot; --&amp;gt; F\n  F -- \&quot;PostgreSQL protocol\\nSQL\&quot; --&amp;gt; P\n  F -. \&quot;SQLite library\\nSQL\&quot; .-&amp;gt; S\n&quot;}" data-plain="flowchart LR
  A[&quot;Any application\nAny MongoDB driver&quot;]
  F{{FerretDB}}
  P[(PostgreSQL)]
  S[(&quot;SQLite&quot;)]

  A -- &quot;MongoDB protocol\nBSON&quot; --> F
  F -- &quot;PostgreSQL protocol\nSQL&quot; --> P
  F -. &quot;SQLite library\nSQL&quot; .-> S
" dir="auto"><!----><!----><div class="position-absolute top-0 pr-2 width-full d-flex flex-justify-end flex-items-center">
    
    <details class="details-reset details-overlay details-overlay-dark" style="display: contents">
      <summary role="button" aria-label="打开对话框" class="btn my-2 mr-2 p-0 d-inline-flex" aria-haspopup="dialog">
        <svg width="16" height="16" viewBox="0 0 16 16" fill="currentColor" class="octicon m-2">
          <path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 1.06L2.56 7h10.88l-2.22-2.22a.75.75 0 011.06-1.06l3.5 3.5a.75.75 0 010 1.06l-3.5 3.5a.75.75 0 11-1.06-1.06l2.22-2.22H2.56l2.22 2.22a.75.75 0 11-1.06 1.06l-3.5-3.5a.75.75 0 010-1.06l3.5-3.5z"></path>
        </svg>
      </summary>
      <details-dialog class="Box Box--overlay render-full-screen d-flex flex-column anim-fade-in fast" aria-label="mermaid rendered container" role="dialog" aria-modal="true">
        <div>
          <button aria-label="Close dialog" data-close-dialog="" type="button" data-view-component="true" class="Link--muted btn-link position-absolute render-full-screen-close">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor" style="display:inline-block;vertical-align:text-bottom" class="octicon octicon-x">
              <path fill-rule="evenodd" d="M5.72 5.72a.75.75 0 011.06 0L12 10.94l5.22-5.22a.75.75 0 111.06 1.06L13.06 12l5.22 5.22a.75.75 0 11-1.06 1.06L12 13.06l-5.22 5.22a.75.75 0 01-1.06-1.06L10.94 12 5.72 6.78a.75.75 0 010-1.06z"></path>
            </svg>
          </button>
          <div class="Box-body border-0" role="presentation"></div>
        </div>
      </details-dialog>
    </details>
  <!----><clipboard-copy class="btn my-2 js-clipboard-copy p-0 d-inline-flex tooltipped-no-delay" role="button" data-copy-feedback="Copied!" data-tooltip-direction="s" aria-label="复制美人鱼代码" value="flowchart LR
  A[&quot;Any application\nAny MongoDB driver&quot;]
  F{{FerretDB}}
  P[(PostgreSQL)]
  S[(&quot;SQLite&quot;)]

  A -- &quot;MongoDB protocol\nBSON&quot; --> F
  F -- &quot;PostgreSQL protocol\nSQL&quot; --> P
  F -. &quot;SQLite library\nSQL&quot; .-> S
" tabindex="0">
    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" class="octicon octicon-copy js-clipboard-copy-icon m-2">
      <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path>
      <path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
    </svg>
    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
      <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
    </svg>
  </clipboard-copy>
  </div><!---->
    <div class="render-container color-bg-transparent js-render-target p-0 is-render-automatic is-render-requested is-render-ready" data-identity="304f277b-708c-4bfa-a19d-8527a73ee434" data-host="https://viewscreen.githubusercontent.com" data-type="mermaid" style="height: 180px;">
      <iframe role="presentation" class="render-viewer" sandbox="allow-scripts allow-same-origin allow-top-navigation allow-popups" src="https://viewscreen.githubusercontent.com/markdown/mermaid?docs_host=https%3A%2F%2Fdocs.github.com&amp;color_mode=light#304f277b-708c-4bfa-a19d-8527a73ee434" name="304f277b-708c-4bfa-a19d-8527a73ee434" data-content="{&quot;data&quot;:&quot;flowchart LR\n  A[\&quot;Any application\\nAny MongoDB driver\&quot;]\n  F{{FerretDB}}\n  P[(PostgreSQL)]\n  S[(\&quot;SQLite\&quot;)]\n\n  A -- \&quot;MongoDB protocol\\nBSON\&quot; --&amp;gt; F\n  F -- \&quot;PostgreSQL protocol\\nSQL\&quot; --&amp;gt; P\n  F -. \&quot;SQLite library\\nSQL\&quot; .-&amp;gt; S\n&quot;}">
      </iframe>
    </div>
  <!----><!----></div>
  <span class="js-render-enrichment-loader d-flex flex-justify-center flex-items-center width-full" style="min-height:100px" role="presentation" hidden="">
    <svg style="box-sizing: content-box; color: var(--color-icon-primary);" width="16" height="16" viewBox="0 0 16 16" fill="none" data-view-component="true" class="octospinner mx-auto anim-rotate">
  <circle cx="8" cy="8" r="7" stroke="currentColor" stroke-opacity="0.25" stroke-width="2" vector-effect="non-scaling-stroke" fill="none"></circle>
  <path d="M15 8a7.002 7.002 0 00-7-7" stroke="currentColor" stroke-width="2" stroke-linecap="round" vector-effect="non-scaling-stroke"></path>
</svg>
  </span>
<div class="js-render-enrichment-fallback"><div class="render-plaintext-hidden" dir="auto">
      <pre lang="mermaid" aria-label="Raw mermaid code">flowchart LR<font></font>
  A["Any application\nAny MongoDB driver"]<font></font>
  F{{FerretDB}}<font></font>
  P[(PostgreSQL)]<font></font>
  S[("SQLite")]<font></font>
<font></font>
  A -- "MongoDB protocol\nBSON" --&gt; F<font></font>
  F -- "PostgreSQL protocol\nSQL" --&gt; P<font></font>
  F -. "SQLite library\nSQL" .-&gt; S<font></font>
</pre>
    </div></div></section>

<h2 tabindex="-1" dir="auto"><a id="user-content-why-do-we-need-ferretdb" class="anchor" aria-hidden="true" tabindex="-1" href="#why-do-we-need-ferretdb"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为什么我们需要 FerretDB？</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MongoDB 最初对于我们许多开发人员来说是一项令人大开眼界的技术，它使我们能够比使用关系数据库更快地构建应用程序。在早期，其易于使用且文档齐全的驱动程序使 MongoDB 成为最简单的数据库解决方案之一。然而，随着时间的推移，MongoDB 放弃了其开源根源；将许可证更改为</font></font><a href="https://www.mongodb.com/licensing/server-side-public-license" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SSPL</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 使其无法用于许多开源和早期商业项目。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">大多数 MongoDB 用户不需要 MongoDB 提供的任何高级功能；然而，他们需要一个易于使用的开源文档数据库解决方案。认识到这一点，FerretDB 就来填补这一空白。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-scope-and-current-state" class="anchor" aria-hidden="true" tabindex="-1" href="#scope-and-current-state"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围和现状</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FerretDB 与 MongoDB 驱动程序和流行的 MongoDB 工具兼容。在许多情况下，它可以作为 MongoDB 5.0+ 的直接替代品。不断添加功能以进一步提高兼容性和性能。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们欢迎所有贡献者。请参阅我们的</font></font><a href="https://github.com/orgs/FerretDB/projects/2/views/1"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公共路线图、</font></font></a><font style="vertical-align: inherit;"></font><a href="https://docs.ferretdb.io/diff/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与 MongoDB 的已知差异</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">列表</font><font style="vertical-align: inherit;">以及</font></font><a href="/FerretDB/FerretDB/blob/main/CONTRIBUTING.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-quickstart" class="anchor" aria-hidden="true" tabindex="-1" href="#quickstart"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速开始</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行以下命令以启动带有 PostgreSQL 后端的 FerretDB：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker run -d --rm --name ferretdb -p 27017:27017 ghcr.io/ferretdb/all-in-one</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker run -d --rm --name ferretdb -p 27017:27017 ghcr.io/ferretdb/all-in-one" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者，运行以下命令以使用 SQLite 后端启动 FerretDB：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker run -d --rm --name ferretdb -p 27017:27017 -e FERRETDB_HANDLER=sqlite ghcr.io/ferretdb/all-in-one</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker run -d --rm --name ferretdb -p 27017:27017 -e FERRETDB_HANDLER=sqlite ghcr.io/ferretdb/all-in-one" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此命令将启动一个包含 FerretDB、PostgreSQL/SQLite 和 MongoDB Shell 的容器，以进行快速测试和实验。但是，它不适合生产用例，因为它将所有数据保留在内部并在关闭时丢失。请参阅我们的</font></font><a href="https://docs.ferretdb.io/quickstart-guide/docker/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker 快速入门指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，了解不存在这些问题的说明。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当该容器运行时，您可以：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 MongoDB URI 通过任何 MongoDB 客户端应用程序连接到它</font></font><code>mongodb://127.0.0.1:27017/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">只需运行 即可使用 MongoDB Shell 连接到它</font></font><code>mongosh</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。如果本地没有安装，可以运行</font></font><code>docker exec -it ferretdb mongosh</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于 PostgreSQL 后端，通过运行连接到它</font></font><code>docker exec -it ferretdb psql -U username ferretdb</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。 FerretDB 对 MongoDB 数据库使用 PostgreSQL 模式。因此，如果您</font></font><code>test</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用任何 MongoDB 客户端在数据库中创建了一些集合，您可以通过运行查询切换到它</font></font><code>SET search_path = 'test';</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，并通过运行命令查看 PostgreSQL 表的列表</font></font><code>\d</code> <code>psql</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于 SQLite 后端，通过运行连接到它</font></font><code>docker exec -it ferretdb sqlite3 /state/&lt;database&gt;.sqlite</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。因此，如果您</font></font><code>test</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用任何 MongoDB 客户端在数据库中创建了一些集合，请</font></font><code>docker exec -it ferretdb sqlite3 /state/test.sqlite</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
通过运行命令来运行并查看 SQLite 表的列表</font></font><code>.tables</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用 停止容器</font></font><code>docker stop ferretdb</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们还提供适用于各种 Linux 发行版的二进制文件和软件包，以及将 FerretDB 嵌入到您的应用程序中的</font></font><a href="https://pkg.go.dev/github.com/FerretDB/FerretDB/ferretdb" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Go 库软件包</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。请参阅</font></font><a href="https://docs.ferretdb.io/quickstart-guide/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解更多详细信息。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-building-and-packaging" class="anchor" aria-hidden="true" tabindex="-1" href="#building-and-packaging"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建筑和包装</font></font></h2>

<div class="markdown-alert markdown-alert-note" dir="auto"><p class="markdown-alert-title" dir="auto"><svg class="octicon octicon-info mr-2" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8Zm8-6.5a6.5 6.5 0 1 0 0 13 6.5 6.5 0 0 0 0-13ZM6.5 7.75A.75.75 0 0 1 7.25 7h1a.75.75 0 0 1 .75.75v2.75h.25a.75.75 0 0 1 0 1.5h-2a.75.75 0 0 1 0-1.5h.25v-2h-.25a.75.75 0 0 1-.75-.75ZM8 6a1 1 0 1 1 0-2 1 1 0 0 1 0 2Z"></path></svg><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">笔记</font></font></p><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们强烈建议用户不要自己构建 FerretDB。相反，请使用我们提供的二进制文件、Docker 映像或包。</font></font></p>
</div>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FerretDB 可以像任何其他 Go 程序一样构建，但一些生成的文件和构建标签可能会影响它。请参阅</font></font><a href="https://pkg.go.dev/github.com/FerretDB/FerretDB/build/version" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解更多详细信息。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-managed-ferretdb-at-cloud-providers" class="anchor" aria-hidden="true" tabindex="-1" href="#managed-ferretdb-at-cloud-providers"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在云提供商处托管 FerretDB</font></font></h2>
<ul dir="auto">
<li><a href="https://www.civo.com/marketplace/FerretDB" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">西沃</font></font></a></li>
<li><a href="https://www.scaleway.com/en/managed-document-database/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">斯卡威</font></font></a></li>
<li><a href="https://www.vultr.com/products/managed-databases/ferretdb/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">乌尔特尔</font></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-documentation" class="anchor" aria-hidden="true" tabindex="-1" href="#documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></h2>
<ul dir="auto">
<li><a href="https://docs.ferretdb.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为用户提供的文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><a href="https://pkg.go.dev/github.com/FerretDB/FerretDB/ferretdb" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为 Go 开发人员提供的有关嵌入式 FerretDB 的文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-community" class="anchor" aria-hidden="true" tabindex="-1" href="#community"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">社区</font></font></h2>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网站和博客： https: </font></font><a href="https://www.ferretdb.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">//www.ferretdb.com/</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推特：</font></font><a href="https://twitter.com/ferret_db" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">@ferret_db</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">乳齿象：</font></font><a href="https://techhub.social/@ferretdb" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">@ferretdb@techhub.social</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><a href="https://join.slack.com/t/ferretdb/shared_invite/zt-zqe9hj8g-ZcMG3~5Cs5u9uuOPnZB8~A" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Slack 聊天</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可快速提问。</font></font></li>
<li><a href="https://github.com/FerretDB/FerretDB/discussions"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">较长主题的</font><a href="https://github.com/FerretDB/FerretDB/discussions"><font style="vertical-align: inherit;">GitHub 讨论。</font></a></font></li>
<li><a href="https://github.com/FerretDB/FerretDB/issues"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关错误和缺失功能的</font><a href="https://github.com/FerretDB/FerretDB/issues"><font style="vertical-align: inherit;">GitHub 问题。</font></a></font></li>
<li><a href="https://calendar.google.com/event?action=TEMPLATE&amp;tmeid=NjNkdTkyN3VoNW5zdHRiaHZybXFtb2l1OWtfMjAyMTEyMTNUMTgwMDAwWiBjX24zN3RxdW9yZWlsOWIwMm0wNzQwMDA3MjQ0QGc&amp;tmsrc=c_n37tquoreil9b02m0740007244%40group.calendar.google.com&amp;scp=ALL" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
每周一 18:00 UTC 在</font></font><a href="https://meet.google.com/mcb-arhw-qbq" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Google Meet举行</font></font></a><font style="vertical-align: inherit;"><a href="https://calendar.google.com/event?action=TEMPLATE&amp;tmeid=NjNkdTkyN3VoNW5zdHRiaHZybXFtb2l1OWtfMjAyMTEyMTNUMTgwMDAwWiBjX24zN3RxdW9yZWlsOWIwMm0wNzQwMDA3MjQ0QGc&amp;tmsrc=c_n37tquoreil9b02m0740007244%40group.calendar.google.com&amp;scp=ALL" rel="nofollow"><font style="vertical-align: inherit;">的开放办公时间会议</font></a><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想联系 FerretDB Inc.，请使用</font></font><a href="https://www.ferretdb.com/contact/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此表格</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</article></div>
