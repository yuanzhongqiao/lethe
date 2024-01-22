# Lethe

![Lethe](logo/logo_black.png?raw=true)

[![CI-Debug](https://github.com/lethe-cfd/lethe/actions/workflows/main_debug.yml/badge.svg)](https://github.com/lethe-cfd/lethe/actions/workflows/main_debug.yml)
[![CI-Release](https://github.com/lethe-cfd/lethe/actions/workflows/main_release.yml/badge.svg)](https://github.com/lethe-cfd/lethe/actions/workflows/main_release.yml)
[![CI-Warnings](https://github.com/lethe-cfd/lethe/actions/workflows/main_warnings.yml/badge.svg)](https://github.com/lethe-cfd/lethe/actions/workflows/main_warnings.yml)
[![CI-Examples](https://github.com/lethe-cfd/lethe/actions/workflows/main_parameter_files.yml/badge.svg)](https://github.com/lethe-cfd/lethe/actions/workflows/main_parameter_files.yml)
[![Documentation](https://github.com/lethe-cfd/lethe/actions/workflows/doc-github-pages.yml/badge.svg)](https://github.com/lethe-cfd/lethe/actions/workflows/doc-github-pages.yml)
[![Docker Image](https://github.com/lethe-cfd/lethe/actions/workflows/docker.yml/badge.svg)](https://github.com/lethe-cfd/lethe/actions/workflows/docker.yml)

<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><h1 tabindex="-1" dir="auto"><a id="user-content-lethe" class="anchor" aria-hidden="true" tabindex="-1" href="#lethe"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">忘川</font></font></h1>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/lethe-cfd/lethe/blob/master/logo/logo_black.png?raw=true"><img src="/lethe-cfd/lethe/raw/master/logo/logo_black.png?raw=true" alt="忘川" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://github.com/lethe-cfd/lethe/actions/workflows/main_debug.yml"><img src="https://github.com/lethe-cfd/lethe/actions/workflows/main_debug.yml/badge.svg" alt="CI调试" style="max-width: 100%;"></a>
<a href="https://github.com/lethe-cfd/lethe/actions/workflows/main_release.yml"><img src="https://github.com/lethe-cfd/lethe/actions/workflows/main_release.yml/badge.svg" alt="CI-发布" style="max-width: 100%;"></a>
<a href="https://github.com/lethe-cfd/lethe/actions/workflows/main_warnings.yml"><img src="https://github.com/lethe-cfd/lethe/actions/workflows/main_warnings.yml/badge.svg" alt="CI-警告" style="max-width: 100%;"></a>
<a href="https://github.com/lethe-cfd/lethe/actions/workflows/main_parameter_files.yml"><img src="https://github.com/lethe-cfd/lethe/actions/workflows/main_parameter_files.yml/badge.svg" alt="CI-示例" style="max-width: 100%;"></a>
<a href="https://github.com/lethe-cfd/lethe/actions/workflows/doc-github-pages.yml"><img src="https://github.com/lethe-cfd/lethe/actions/workflows/doc-github-pages.yml/badge.svg" alt="文档" style="max-width: 100%;"></a>
<a href="https://github.com/lethe-cfd/lethe/actions/workflows/docker.yml"><img src="https://github.com/lethe-cfd/lethe/actions/workflows/docker.yml/badge.svg" alt="Docker 镜像" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Lethe（发音为/ˈliːθiː/）是一款开源计算流体动力学 (CFD)、离散元方法 (DEM) 和耦合 CFD-DEM 软件，它使用高阶连续伽辽金公式来模拟单相流和多相流。</font><font style="vertical-align: inherit;">Lethe 包含一系列基于
</font></font><a href="https://www.dealii.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">deal.II（</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有限元库）的求解器。</font><font style="vertical-align: inherit;">通过 deal.II，Lethe 使用</font></font><a href="https://trilinos.github.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Trilinos</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来实现稀疏线性代数例程，</font></font><a href="https://www.p4est.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 p4est</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
来实现分布式自适应四叉树和八叉树。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">忘川（Lethe）以遗忘之河命名，根据
</font></font><a href="https://en.wikipedia.org/wiki/Lethe" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维基百科</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，这条河：</font></font></p>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是希腊地下世界的五条河流之一[，]另外四条[是] Acheron（悲伤之河）、Cocytus（哀悼之河）、Phlegethon（火之河）和 Styx（分隔地球的河流）和地狱）。</font><font style="vertical-align: inherit;">......死者的灵魂需要喝忘川之水才能忘记他们的尘世生活。</font></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://doi.org/10.1016/j.softx.2020.100579" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这里</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述的是忘川</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">它最初只是一个周末项目，但慢慢发展成为实际研究中使用的 CFD、DEM 和 CFD-DEM 软件。</font><font style="vertical-align: inherit;">Lethe 正在积极开发中。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注：如果没有 deal.II 作者的辛勤工作，Lethe 就不会存在。</font><font style="vertical-align: inherit;">Lethe 的作者想强调，如果没有 deal.II，像 Lethe 这样的专用求解器就不可能存在。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-documentation" class="anchor" aria-hidden="true" tabindex="-1" href="#documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://lethe-cfd.github.io/lethe/documentation/index.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">找到文档、教程等
</font><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><a href="https://lethe-cfd.github.io/lethe/doxygen/index.html" rel="nofollow"><font style="vertical-align: inherit;">可以在此处</font></a><font style="vertical-align: inherit;">找到基于 Doxygen 的开发人员文档
</font></font><a href="https://lethe-cfd.github.io/lethe/doxygen/index.html" rel="nofollow"><font style="vertical-align: inherit;"></font></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-installation" class="anchor" aria-hidden="true" tabindex="-1" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://lethe-cfd.github.io/lethe/documentation/installation/installation.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请按照文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中的说明进行操作
</font><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-authors" class="anchor" aria-hidden="true" tabindex="-1" href="#authors"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">作者</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主要开发商：</font></font></p>
<ul dir="auto">
<li><a href="https://www.polymtl.ca/expertises/en/blais-bruno" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">布鲁诺·布莱斯</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献者（按字母顺序排列）：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阿米什加·阿尔弗尼乌斯</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安托万·阿夫里特</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">卢卡·巴尔博</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">瓦莱丽·比博</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">比安卡·布若</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">奥黛丽·科拉德-戴尼奥</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">卡罗尔·安妮·多奈斯</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">托尼·埃尔·盖塔尼</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">奥利维尔·加博里奥</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">西蒙·高文</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">沙哈卜·戈尔山</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">奥利维尔·盖夫雷蒙</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">马里恩·汉尼</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">珍妮·约阿希姆</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">拉杰什瓦里·坎布尔</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">马丁·克朗比希勒</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">马克西姆·兰德里</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">皮埃尔·劳伦坦</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查尔斯·勒帕勒</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">奥瑞斯特侯爵</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">嘉扎拉·米拉霍里</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">托马斯·莫纳特</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">彼得·蒙克</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维克托·奥利维拉·费雷拉</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">海伦·帕皮永-拉罗什</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">保罗·佩兴斯</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">劳拉·普列托·萨维德拉</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">凯瑟琳·雷德伯恩</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">菲利普·里维斯特</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">米凯尔·威兰特</font></font></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-license" class="anchor" aria-hidden="true" tabindex="-1" href="#license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该项目根据</font></font><a href="/lethe-cfd/lethe/blob/master/LICENSE"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LGPL-2.1 许可证</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获得许可。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">除非您另有明确说明，否则您有意提交的包含在本项目中的任何贡献均应按上述方式获得许可，无任何附加条款或条件。</font></font></p>
</article></div>
## License

This project is licensed under the [LGPL-2.1 license](LICENSE).

Unless you explicitly state otherwise, any contribution intentionally
submitted by you for inclusion in this project shall be licensed as
above, without any additional terms or conditions.
