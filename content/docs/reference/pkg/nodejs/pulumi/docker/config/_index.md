---
title: "Module config"
linktitle: "config"
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->


> This provider is a derived work of the [Terraform Provider](https://github.com/terraform-providers/terraform-provider-docker)
> distributed under [MPL 2.0](https://www.mozilla.org/en-US/MPL/2.0/). If you encounter a bug or missing feature,
> first check the [`pulumi/pulumi-docker` repo](https://github.com/pulumi/pulumi-docker/issues); however, if that doesn't turn up anything,
> please consult the source [`terraform-providers/terraform-provider-docker` repo](https://github.com/terraform-providers/terraform-provider-docker/issues).







<h3>APIs</h3>
<ul class="api">
    <li><a href="#caMaterial"><span class="symbol api"></span>caMaterial</a></li>
    <li><a href="#certMaterial"><span class="symbol api"></span>certMaterial</a></li>
    <li><a href="#certPath"><span class="symbol api"></span>certPath</a></li>
    <li><a href="#host"><span class="symbol api"></span>host</a></li>
    <li><a href="#keyMaterial"><span class="symbol api"></span>keyMaterial</a></li>
    <li><a href="#registryAuth"><span class="symbol api"></span>registryAuth</a></li>
</ul>




<h2 id="apis">APIs</h2>
<h3 class="pdoc-module-header" id="caMaterial" data-link-title="caMaterial">
    <a href="https://github.com/pulumi/pulumi-docker/blob/a404051a365811737e26a2b256d309ec34849988/sdk/nodejs/config/vars.ts#L12">
        let <strong>caMaterial</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> caMaterial: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;caMaterial&#34;) || utilities.getEnv(&#34;DOCKER_CA_MATERIAL&#34;)</span>;</code></pre>

PEM-encoded content of Docker host CA certificate

<h3 class="pdoc-module-header" id="certMaterial" data-link-title="certMaterial">
    <a href="https://github.com/pulumi/pulumi-docker/blob/a404051a365811737e26a2b256d309ec34849988/sdk/nodejs/config/vars.ts#L16">
        let <strong>certMaterial</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> certMaterial: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;certMaterial&#34;) || utilities.getEnv(&#34;DOCKER_CERT_MATERIAL&#34;)</span>;</code></pre>

PEM-encoded content of Docker client certificate

<h3 class="pdoc-module-header" id="certPath" data-link-title="certPath">
    <a href="https://github.com/pulumi/pulumi-docker/blob/a404051a365811737e26a2b256d309ec34849988/sdk/nodejs/config/vars.ts#L20">
        let <strong>certPath</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> certPath: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;certPath&#34;) || utilities.getEnv(&#34;DOCKER_CERT_PATH&#34;)</span>;</code></pre>

Path to directory with Docker TLS config

<h3 class="pdoc-module-header" id="host" data-link-title="host">
    <a href="https://github.com/pulumi/pulumi-docker/blob/a404051a365811737e26a2b256d309ec34849988/sdk/nodejs/config/vars.ts#L24">
        let <strong>host</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> host: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;host&#34;) || (utilities.getEnv(&#34;DOCKER_HOST&#34;) || &#34;unix:///var/run/docker.sock&#34;)</span>;</code></pre>

The Docker daemon address

<h3 class="pdoc-module-header" id="keyMaterial" data-link-title="keyMaterial">
    <a href="https://github.com/pulumi/pulumi-docker/blob/a404051a365811737e26a2b256d309ec34849988/sdk/nodejs/config/vars.ts#L28">
        let <strong>keyMaterial</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> keyMaterial: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;keyMaterial&#34;) || utilities.getEnv(&#34;DOCKER_KEY_MATERIAL&#34;)</span>;</code></pre>

PEM-encoded content of Docker client private key

<h3 class="pdoc-module-header" id="registryAuth" data-link-title="registryAuth">
    <a href="https://github.com/pulumi/pulumi-docker/blob/a404051a365811737e26a2b256d309ec34849988/sdk/nodejs/config/vars.ts#L29">
        let <strong>registryAuth</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> registryAuth: {
    address: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>;
    configFile: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>;
    password: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>;
    username: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>;
}[] | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.getObject&lt;{ address: string, configFile?: string, password?: string, username?: string }[]&gt;(&#34;registryAuth&#34;)</span>;</code></pre>
