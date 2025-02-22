---
title: Istio
description: 用于连接、保护、控制和观测服务。
---
<!-- these script blocks are only for the primary English home page -->
<script type="application/ld+json">
    {
        "@context": "http://schema.org",
        "@type": "Organization",
        "url": "https://istio.io",
        "logo": "https://istio.io/img/logo.png",
        "sameAs": [
            "https://twitter.com/IstioMesh",
            "https://discuss.istio.io/"
        ]
    }
</script>
<script type="application/ld+json">
    {
        "@context": "http://schema.org",
        "@type": "WebSite",
        "url": "https://istio.io/",
        "potentialAction": {
            "@type": "SearchAction",
            "target": "https://istio.io/search?q={search_term_string}",
            "query-input": "required name=search_term_string"
        }
    }
</script>

<main class="landing">
    <div id="banner">
        {{< inline_image "landing/istio-logo.svg" >}}
        <div id="hero-text">
            <h1 id="hero-label">Istio</h1>
            <h1 id="hero-lead">连接、保护、控制和观测服务。
        </div>
    </div>

    <div id="panels">
        <div id="panel1" class="panel">
            <a href="/zh/docs/concepts/traffic-management/">
                <div class="panel-img-top">
                    {{< inline_image "landing/routing-and-load-balancing.svg" >}}
                </div>
                <div class="panel-body">
                    <hr class="panel-line">
                    <h5 class="panel-title">连接</h5>
                    <hr class="panel-line">
                    <p class="panel-text">
                        智能控制服务之间的流量和 API 调用，进行一系列测试，并通过红/黑部署逐步升级。
                    </p>
                </div>
            </a>
        </div>

        <div id="panel2" class="panel">
            <a href="/zh/docs/concepts/security/">
                <div class="panel-img-top">
                    {{< inline_image "landing/resiliency.svg" >}}
                </div>
                <div class="panel-body">
                    <hr class="panel-line">
                    <h5 class="panel-title">保护</h5>
                    <hr class="panel-line">
                    <p class="panel-text">
                        通过托管身份验证、授权和服务之间通信加密自动保护您的服务。
                    </p>
                </div>
            </a>
        </div>

        <div id="panel3" class="panel">
            <a href="/zh/docs/reference/config/policy-and-telemetry/">
                <div class="panel-img-top">
                    {{< inline_image "landing/policy-enforcement.svg" >}}
                </div>
                <div class="panel-body">
                    <hr class="panel-line">
                    <h5 class="panel-title">Control</h5>
                    <hr class="panel-line">
                    <p class="panel-text">
                        应用策略并确保其执行，使得资源在消费者之间公平分配。
                    </p>
                </div>
            </a>
        </div>

        <div id="panel4" class="panel">
            <a href="/zh/docs/reference/config/policy-and-telemetry/">
                <div class="panel-img-top">
                    {{< inline_image "landing/telemetry-and-reporting.svg" >}}
                </div>
                <div class="panel-body">
                    <hr class="panel-line">
                    <h5 class="panel-title">观测</h5>
                    <hr class="panel-line">
                    <p class="panel-text">
                        对您的一切服务进行多样化、自动化的追踪、监控以及记录日志，以便实时了解正在发生的事情。
                   </p>
                </div>
            </a>
        </div>
    </div>

    <div id="buttons">
        <a title="在 Kubernetes 上安装 Istio。" class="btn" href="/zh/docs/setup/getting-started/">开始吧</a>
        <a title="深入了解 Istio 是什么以及它是如何工作的。" class="btn" href="/zh/docs/concepts/what-is-istio/">了解更多</a>
        <a title="下载最新版本。" class="btn" href="/zh/docs/setup/getting-started/#download">下载 {{< istio_release_name >}}</a>
    </div>