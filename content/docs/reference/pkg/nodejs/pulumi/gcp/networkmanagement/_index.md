---
title: "Module networkmanagement"
title_tag: "Module networkmanagement | Package @pulumi/gcp | Node.js SDK"
linktitle: "networkmanagement"
meta_desc: "Explore members of the networkmanagement module in the @pulumi/gcp package."
git_sha: "2400b696ba8424ff5a3a419f75640293ac2f363b"
block_external_search_index: true
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

{{< resource-docs-alert "gcp" >}}




<h3>Resources</h3>
<ul class="api">
    <li><a href="#ConnectivityTest"><span class="symbol resource"></span>ConnectivityTest</a></li>
</ul>


<h3>Others</h3>
<ul class="api">
    <li><a href="#ConnectivityTestArgs"><span class="symbol api"></span>ConnectivityTestArgs</a></li>
    <li><a href="#ConnectivityTestState"><span class="symbol api"></span>ConnectivityTestState</a></li>
</ul>


<h2 id="resources">Resources</h2>
<h3 class="pdoc-module-header" id="ConnectivityTest" data-link-title="ConnectivityTest">
    <a href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L22">
        Resource <strong>ConnectivityTest</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>class</span> <span class='nx'>ConnectivityTest</span> <span class='kr'>extends</span> <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></code></pre>

A connectivity test are a static analysis of your resource configurations
that enables you to evaluate connectivity to and from Google Cloud
resources in your Virtual Private Cloud (VPC) network.

To get more information about ConnectivityTest, see:

* [API documentation](https://cloud.google.com/network-intelligence-center/docs/connectivity-tests/reference/networkmanagement/rest/v1/projects.locations.global.connectivityTests)
* How-to Guides
    * [Official Documentation](https://cloud.google.com/network-intelligence-center/docs)

#### Example Usage

<h4 class="pdoc-member-header" id="ConnectivityTest-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L117"> <b>constructor</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span><span class='kd'>new</span> ConnectivityTest(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args: <a href='#ConnectivityTestArgs'>ConnectivityTestArgs</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</code></pre>


Create a ConnectivityTest resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h4 class="pdoc-member-header" id="ConnectivityTest-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L32">method <b>get</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#ConnectivityTestState'>ConnectivityTestState</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#ConnectivityTest'>ConnectivityTest</a></code></pre>


Get an existing ConnectivityTest resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h4 class="pdoc-member-header" id="ConnectivityTest-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L22">method <b>getProvider</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ProviderResource'>ProviderResource</a> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></code></pre>

<h4 class="pdoc-member-header" id="ConnectivityTest-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L43">method <b>isInstance</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): obj is ConnectivityTest</code></pre>


Returns true if the given object is an instance of ConnectivityTest.  This is designed to work even
when multiple copies of the Pulumi SDK have been loaded into the same process.

<h4 class="pdoc-member-header" id="ConnectivityTest-description">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L54">property <b>description</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>description: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</code></pre>

The user-supplied description of the Connectivity Test.
Maximum of 512 characters.

<h4 class="pdoc-member-header" id="ConnectivityTest-destination">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L72">property <b>destination</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>destination: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/output/#ConnectivityTestDestination'>ConnectivityTestDestination</a>&gt;;</code></pre>

Required. Destination specification of the Connectivity Test.
You can use a combination of destination IP address, Compute
Engine VM instance, or VPC network to uniquely identify the
destination location.
Even if the destination IP address is not unique, the source IP
location is unique. Usually, the analysis can infer the destination
endpoint from route information.
If the destination you specify is a VM instance and the instance has
multiple network interfaces, then you must also specify either a
destination IP address or VPC network to identify the destination
interface.
A reachability analysis proceeds even if the destination location
is ambiguous. However, the result can include endpoints that you
don't intend to test.
Structure is documented below.

<h4 class="pdoc-member-header" id="ConnectivityTest-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L22">property <b>id</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</code></pre>

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h4 class="pdoc-member-header" id="ConnectivityTest-labels">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L76">property <b>labels</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>labels: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>} | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</code></pre>

Resource labels to represent user-provided metadata.

<h4 class="pdoc-member-header" id="ConnectivityTest-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L80">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>name: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Unique name for the connectivity test.

<h4 class="pdoc-member-header" id="ConnectivityTest-project">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L85">property <b>project</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>project: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h4 class="pdoc-member-header" id="ConnectivityTest-protocol">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L89">property <b>protocol</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>protocol: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</code></pre>

IP Protocol of the test. When not provided, "TCP" is assumed.

<h4 class="pdoc-member-header" id="ConnectivityTest-relatedProjects">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L95">property <b>relatedProjects</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>relatedProjects: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>[] | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</code></pre>

Other projects that may be relevant for reachability analysis.
This is applicable to scenarios where a test can cross project
boundaries.

<h4 class="pdoc-member-header" id="ConnectivityTest-source">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L117">property <b>source</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>source: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/output/#ConnectivityTestSource'>ConnectivityTestSource</a>&gt;;</code></pre>

Required. Source specification of the Connectivity Test.
You can use a combination of source IP address, virtual machine
(VM) instance, or Compute Engine network to uniquely identify the
source location.
Examples: If the source IP address is an internal IP address within
a Google Cloud Virtual Private Cloud (VPC) network, then you must
also specify the VPC network. Otherwise, specify the VM instance,
which already contains its internal IP address and VPC network
information.
If the source of the test is within an on-premises network, then
you must provide the destination VPC network.
If the source endpoint is a Compute Engine VM instance with multiple
network interfaces, the instance itself is not sufficient to
identify the endpoint. So, you must also specify the source IP
address or VPC network.
A reachability analysis proceeds even if the source location is
ambiguous. However, the test result may include endpoints that
you don't intend to test.
Structure is documented below.

<h4 class="pdoc-member-header" id="ConnectivityTest-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L22">property <b>urn</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>urn: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</code></pre>

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.



<h2 id="apis">Others</h2>
<h3 class="pdoc-module-header" id="ConnectivityTestArgs" data-link-title="ConnectivityTestArgs">
    <a href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L244">
        interface <strong>ConnectivityTestArgs</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>ConnectivityTestArgs</span></code></pre>

The set of arguments for constructing a ConnectivityTest resource.

<h4 class="pdoc-member-header" id="ConnectivityTestArgs-description">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L249">property <b>description</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>description?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The user-supplied description of the Connectivity Test.
Maximum of 512 characters.

<h4 class="pdoc-member-header" id="ConnectivityTestArgs-destination">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L267">property <b>destination</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>destination: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#ConnectivityTestDestination'>ConnectivityTestDestination</a>&gt;;</code></pre>

Required. Destination specification of the Connectivity Test.
You can use a combination of destination IP address, Compute
Engine VM instance, or VPC network to uniquely identify the
destination location.
Even if the destination IP address is not unique, the source IP
location is unique. Usually, the analysis can infer the destination
endpoint from route information.
If the destination you specify is a VM instance and the instance has
multiple network interfaces, then you must also specify either a
destination IP address or VPC network to identify the destination
interface.
A reachability analysis proceeds even if the destination location
is ambiguous. However, the result can include endpoints that you
don't intend to test.
Structure is documented below.

<h4 class="pdoc-member-header" id="ConnectivityTestArgs-labels">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L271">property <b>labels</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>labels?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;}&gt;;</code></pre>

Resource labels to represent user-provided metadata.

<h4 class="pdoc-member-header" id="ConnectivityTestArgs-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L275">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>name?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Unique name for the connectivity test.

<h4 class="pdoc-member-header" id="ConnectivityTestArgs-project">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L280">property <b>project</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>project?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h4 class="pdoc-member-header" id="ConnectivityTestArgs-protocol">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L284">property <b>protocol</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>protocol?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

IP Protocol of the test. When not provided, "TCP" is assumed.

<h4 class="pdoc-member-header" id="ConnectivityTestArgs-relatedProjects">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L290">property <b>relatedProjects</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>relatedProjects?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;[]&gt;;</code></pre>

Other projects that may be relevant for reachability analysis.
This is applicable to scenarios where a test can cross project
boundaries.

<h4 class="pdoc-member-header" id="ConnectivityTestArgs-source">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L312">property <b>source</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>source: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#ConnectivityTestSource'>ConnectivityTestSource</a>&gt;;</code></pre>

Required. Source specification of the Connectivity Test.
You can use a combination of source IP address, virtual machine
(VM) instance, or Compute Engine network to uniquely identify the
source location.
Examples: If the source IP address is an internal IP address within
a Google Cloud Virtual Private Cloud (VPC) network, then you must
also specify the VPC network. Otherwise, specify the VM instance,
which already contains its internal IP address and VPC network
information.
If the source of the test is within an on-premises network, then
you must provide the destination VPC network.
If the source endpoint is a Compute Engine VM instance with multiple
network interfaces, the instance itself is not sufficient to
identify the endpoint. So, you must also specify the source IP
address or VPC network.
A reachability analysis proceeds even if the source location is
ambiguous. However, the test result may include endpoints that
you don't intend to test.
Structure is documented below.

<h3 class="pdoc-module-header" id="ConnectivityTestState" data-link-title="ConnectivityTestState">
    <a href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L170">
        interface <strong>ConnectivityTestState</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>ConnectivityTestState</span></code></pre>

Input properties used for looking up and filtering ConnectivityTest resources.

<h4 class="pdoc-member-header" id="ConnectivityTestState-description">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L175">property <b>description</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>description?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The user-supplied description of the Connectivity Test.
Maximum of 512 characters.

<h4 class="pdoc-member-header" id="ConnectivityTestState-destination">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L193">property <b>destination</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>destination?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#ConnectivityTestDestination'>ConnectivityTestDestination</a>&gt;;</code></pre>

Required. Destination specification of the Connectivity Test.
You can use a combination of destination IP address, Compute
Engine VM instance, or VPC network to uniquely identify the
destination location.
Even if the destination IP address is not unique, the source IP
location is unique. Usually, the analysis can infer the destination
endpoint from route information.
If the destination you specify is a VM instance and the instance has
multiple network interfaces, then you must also specify either a
destination IP address or VPC network to identify the destination
interface.
A reachability analysis proceeds even if the destination location
is ambiguous. However, the result can include endpoints that you
don't intend to test.
Structure is documented below.

<h4 class="pdoc-member-header" id="ConnectivityTestState-labels">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L197">property <b>labels</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>labels?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;}&gt;;</code></pre>

Resource labels to represent user-provided metadata.

<h4 class="pdoc-member-header" id="ConnectivityTestState-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L201">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>name?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Unique name for the connectivity test.

<h4 class="pdoc-member-header" id="ConnectivityTestState-project">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L206">property <b>project</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>project?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h4 class="pdoc-member-header" id="ConnectivityTestState-protocol">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L210">property <b>protocol</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>protocol?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

IP Protocol of the test. When not provided, "TCP" is assumed.

<h4 class="pdoc-member-header" id="ConnectivityTestState-relatedProjects">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L216">property <b>relatedProjects</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>relatedProjects?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;[]&gt;;</code></pre>

Other projects that may be relevant for reachability analysis.
This is applicable to scenarios where a test can cross project
boundaries.

<h4 class="pdoc-member-header" id="ConnectivityTestState-source">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/2400b696ba8424ff5a3a419f75640293ac2f363b/sdk/nodejs/networkmanagement/connectivityTest.ts#L238">property <b>source</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>source?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#ConnectivityTestSource'>ConnectivityTestSource</a>&gt;;</code></pre>

Required. Source specification of the Connectivity Test.
You can use a combination of source IP address, virtual machine
(VM) instance, or Compute Engine network to uniquely identify the
source location.
Examples: If the source IP address is an internal IP address within
a Google Cloud Virtual Private Cloud (VPC) network, then you must
also specify the VPC network. Otherwise, specify the VM instance,
which already contains its internal IP address and VPC network
information.
If the source of the test is within an on-premises network, then
you must provide the destination VPC network.
If the source endpoint is a Compute Engine VM instance with multiple
network interfaces, the instance itself is not sufficient to
identify the endpoint. So, you must also specify the source IP
address or VPC network.
A reachability analysis proceeds even if the source location is
ambiguous. However, the test result may include endpoints that
you don't intend to test.
Structure is documented below.
