---
title: "Module filestore"
linktitle: "filestore"
meta_desc: "Explore members of the filestore module in the @pulumi/gcp package."
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->


> This provider is a derived work of the [Terraform Provider](https://github.com/terraform-providers/terraform-provider-google)
> distributed under [MPL 2.0](https://www.mozilla.org/en-US/MPL/2.0/). If you encounter a bug or missing feature,
> first check the [`pulumi/pulumi-gcp` repo](https://github.com/pulumi/pulumi-gcp/issues); however, if that doesn't turn up anything,
> please consult the source [`terraform-providers/terraform-provider-google` repo](https://github.com/terraform-providers/terraform-provider-google/issues).





<h3>Resources</h3>
<ul class="api">
    <li><a href="#Instance"><span class="symbol resource"></span>Instance</a></li>
</ul>


<h3>Others</h3>
<ul class="api">
    <li><a href="#InstanceArgs"><span class="symbol api"></span>InstanceArgs</a></li>
    <li><a href="#InstanceState"><span class="symbol api"></span>InstanceState</a></li>
</ul>


<h2 id="resources">Resources</h2>
<h3 class="pdoc-module-header" id="Instance" data-link-title="Instance">
    <a href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L12">
        Resource <strong>Instance</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>class</span> <span class='nx'>Instance</span> <span class='kr'>extends</span> <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></code></pre>

> This content is derived from https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/filestore_instance.html.markdown.

<h4 class="pdoc-member-header" id="Instance-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L48"> <b>constructor</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span><span class='kd'>new</span> Instance(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args: <a href='#InstanceArgs'>InstanceArgs</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</code></pre>


Create a Instance resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h4 class="pdoc-member-header" id="Instance-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L21">method <b>get</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#InstanceState'>InstanceState</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#Instance'>Instance</a></code></pre>


Get an existing Instance resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h4 class="pdoc-member-header" id="Instance-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L12">method <b>getProvider</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ProviderResource'>ProviderResource</a> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></code></pre>

<h4 class="pdoc-member-header" id="Instance-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L32">method <b>isInstance</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></code></pre>


Returns true if the given object is an instance of Instance.  This is designed to work even
when multiple copies of the Pulumi SDK have been loaded into the same process.

<h4 class="pdoc-member-header" id="Instance-createTime">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L39">property <b>createTime</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>createTime: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Instance-description">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L40">property <b>description</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>description: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Instance-etag">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L41">property <b>etag</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>etag: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Instance-fileShares">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L42">property <b>fileShares</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>fileShares: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/output/#InstanceFileShares'>outputs.filestore.InstanceFileShares</a>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Instance-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L12">property <b>id</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</code></pre>

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h4 class="pdoc-member-header" id="Instance-labels">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L43">property <b>labels</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>labels: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>} | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Instance-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L44">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>name: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Instance-networks">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L45">property <b>networks</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>networks: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/output/#InstanceNetwork'>outputs.filestore.InstanceNetwork</a>[]&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Instance-project">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L46">property <b>project</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>project: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Instance-tier">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L47">property <b>tier</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>tier: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Instance-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L12">property <b>urn</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>urn: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</code></pre>

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h4 class="pdoc-member-header" id="Instance-zone">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L48">property <b>zone</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>zone: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>


<h2 id="apis">Others</h2>
<h3 class="pdoc-module-header" id="InstanceArgs" data-link-title="InstanceArgs">
    <a href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L127">
        interface <strong>InstanceArgs</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>InstanceArgs</span></code></pre>

The set of arguments for constructing a Instance resource.

<h4 class="pdoc-member-header" id="InstanceArgs-description">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L128">property <b>description</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>description?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="InstanceArgs-fileShares">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L129">property <b>fileShares</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>fileShares: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#InstanceFileShares'>inputs.filestore.InstanceFileShares</a>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="InstanceArgs-labels">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L130">property <b>labels</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>labels?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;}&gt;;</code></pre>
<h4 class="pdoc-member-header" id="InstanceArgs-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L131">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>name?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="InstanceArgs-networks">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L132">property <b>networks</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>networks: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#InstanceNetwork'>inputs.filestore.InstanceNetwork</a>&gt;[]&gt;;</code></pre>
<h4 class="pdoc-member-header" id="InstanceArgs-project">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L133">property <b>project</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>project?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="InstanceArgs-tier">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L134">property <b>tier</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>tier: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="InstanceArgs-zone">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L135">property <b>zone</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>zone: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h3 class="pdoc-module-header" id="InstanceState" data-link-title="InstanceState">
    <a href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L111">
        interface <strong>InstanceState</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>InstanceState</span></code></pre>

Input properties used for looking up and filtering Instance resources.

<h4 class="pdoc-member-header" id="InstanceState-createTime">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L112">property <b>createTime</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>createTime?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="InstanceState-description">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L113">property <b>description</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>description?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="InstanceState-etag">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L114">property <b>etag</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>etag?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="InstanceState-fileShares">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L115">property <b>fileShares</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>fileShares?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#InstanceFileShares'>inputs.filestore.InstanceFileShares</a>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="InstanceState-labels">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L116">property <b>labels</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>labels?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;}&gt;;</code></pre>
<h4 class="pdoc-member-header" id="InstanceState-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L117">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>name?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="InstanceState-networks">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L118">property <b>networks</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>networks?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#InstanceNetwork'>inputs.filestore.InstanceNetwork</a>&gt;[]&gt;;</code></pre>
<h4 class="pdoc-member-header" id="InstanceState-project">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L119">property <b>project</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>project?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="InstanceState-tier">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L120">property <b>tier</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>tier?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="InstanceState-zone">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2d7762322f1d9d9f2616c55cb6b530cbe91bc60f/sdk/nodejs/filestore/instance.ts#L121">property <b>zone</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>zone?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
