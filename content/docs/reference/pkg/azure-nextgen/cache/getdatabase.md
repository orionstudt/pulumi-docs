
---
title: "GetDatabase"
title_tag: "Function GetDatabase | Module cache | Package Azure NextGen"
meta_desc: "Explore the GetDatabase function of the cache module, including examples, input properties, output properties, and supporting types. "
---



<!-- WARNING: this file was generated by Pulumi Docs Generator. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->




## Using GetDatabase {#using}

{{< chooser language "typescript,python,go,csharp" / >}}


{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">function </span>getDatabase<span class="p">(</span><span class="nx">args</span><span class="p">:</span> <span class="nx">GetDatabaseArgs</span><span class="p">, </span><span class="nx">opts</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#InvokeOptions">InvokeOptions</a></span><span class="p">): Promise&lt;<span class="nx">GetDatabaseResult</span>></span></code></pre></div>
{{% /choosable %}}


{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span>get_database(</span><span class="nx">cluster_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">database_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">resource_group_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">opts</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/python/pulumi/#pulumi.InvokeOptions">Optional[InvokeOptions]</a></span> = None<span class="p">) -&gt;</span> GetDatabaseResult</code></pre></div>
{{% /choosable %}}


{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>LookupDatabase<span class="p">(</span><span class="nx">ctx</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">args</span><span class="p"> *</span><span class="nx">LookupDatabaseArgs</span><span class="p">, </span><span class="nx">opts</span><span class="p"> ...</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#InvokeOption">InvokeOption</a></span><span class="p">) (*<span class="nx">LookupDatabaseResult</span>, error)</span></code></pre></div>

> Note: This function is named `LookupDatabase` in the Go SDK.

{{% /choosable %}}


{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static class </span><span class="nx">GetDatabase </span><span class="p">{</span><span class="k">
    public static </span>Task&lt;<span class="nx">GetDatabaseResult</span>> <span class="p">InvokeAsync(</span><span class="nx">GetDatabaseArgs</span><span class="p"> </span><span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.InvokeOptions.html">InvokeOptions</a></span><span class="p">? </span><span class="nx">opts = null<span class="p">)</span><span class="p">
}</span></code></pre></div>
{{% /choosable %}}



The following arguments are supported:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="clustername_csharp">
<a href="#clustername_csharp" style="color: inherit; text-decoration: inherit;">Cluster<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the RedisEnterprise cluster.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="databasename_csharp">
<a href="#databasename_csharp" style="color: inherit; text-decoration: inherit;">Database<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the database.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="resourcegroupname_csharp">
<a href="#resourcegroupname_csharp" style="color: inherit; text-decoration: inherit;">Resource<wbr>Group<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the resource group.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="clustername_go">
<a href="#clustername_go" style="color: inherit; text-decoration: inherit;">Cluster<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the RedisEnterprise cluster.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="databasename_go">
<a href="#databasename_go" style="color: inherit; text-decoration: inherit;">Database<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the database.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="resourcegroupname_go">
<a href="#resourcegroupname_go" style="color: inherit; text-decoration: inherit;">Resource<wbr>Group<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the resource group.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="clustername_nodejs">
<a href="#clustername_nodejs" style="color: inherit; text-decoration: inherit;">cluster<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the RedisEnterprise cluster.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="databasename_nodejs">
<a href="#databasename_nodejs" style="color: inherit; text-decoration: inherit;">database<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the database.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="resourcegroupname_nodejs">
<a href="#resourcegroupname_nodejs" style="color: inherit; text-decoration: inherit;">resource<wbr>Group<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the resource group.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="cluster_name_python">
<a href="#cluster_name_python" style="color: inherit; text-decoration: inherit;">cluster_<wbr>name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The name of the RedisEnterprise cluster.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="database_name_python">
<a href="#database_name_python" style="color: inherit; text-decoration: inherit;">database_<wbr>name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The name of the database.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="resource_group_name_python">
<a href="#resource_group_name_python" style="color: inherit; text-decoration: inherit;">resource_<wbr>group_<wbr>name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The name of the resource group.{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## GetDatabase Result {#result}

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="name_csharp">
<a href="#name_csharp" style="color: inherit; text-decoration: inherit;">Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the resource{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="provisioningstate_csharp">
<a href="#provisioningstate_csharp" style="color: inherit; text-decoration: inherit;">Provisioning<wbr>State</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Current provisioning status of the database{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="resourcestate_csharp">
<a href="#resourcestate_csharp" style="color: inherit; text-decoration: inherit;">Resource<wbr>State</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Current resource status of the database{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="type_csharp">
<a href="#type_csharp" style="color: inherit; text-decoration: inherit;">Type</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The type of the resource. E.g. "Microsoft.Compute/virtualMachines" or "Microsoft.Storage/storageAccounts"{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="clientprotocol_csharp">
<a href="#clientprotocol_csharp" style="color: inherit; text-decoration: inherit;">Client<wbr>Protocol</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies whether redis clients can connect using TLS-encrypted or plaintext redis protocols. Default is TLS-encrypted.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="clusteringpolicy_csharp">
<a href="#clusteringpolicy_csharp" style="color: inherit; text-decoration: inherit;">Clustering<wbr>Policy</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Clustering policy - default is OSSCluster. Specified at create time.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="evictionpolicy_csharp">
<a href="#evictionpolicy_csharp" style="color: inherit; text-decoration: inherit;">Eviction<wbr>Policy</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Redis eviction policy - default is VolatileLRU{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="modules_csharp">
<a href="#modules_csharp" style="color: inherit; text-decoration: inherit;">Modules</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#moduleresponse">List&lt;Pulumi.<wbr>Azure<wbr>Next<wbr>Gen.<wbr>Cache.<wbr>Outputs.<wbr>Module<wbr>Response&gt;</a></span>
    </dt>
    <dd>{{% md %}}Optional set of redis modules to enable in this database - modules can only be added at creation time.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="port_csharp">
<a href="#port_csharp" style="color: inherit; text-decoration: inherit;">Port</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}TCP port of the database endpoint. Specified at create time. Defaults to an available port.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="name_go">
<a href="#name_go" style="color: inherit; text-decoration: inherit;">Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the resource{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="provisioningstate_go">
<a href="#provisioningstate_go" style="color: inherit; text-decoration: inherit;">Provisioning<wbr>State</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Current provisioning status of the database{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="resourcestate_go">
<a href="#resourcestate_go" style="color: inherit; text-decoration: inherit;">Resource<wbr>State</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Current resource status of the database{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="type_go">
<a href="#type_go" style="color: inherit; text-decoration: inherit;">Type</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The type of the resource. E.g. "Microsoft.Compute/virtualMachines" or "Microsoft.Storage/storageAccounts"{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="clientprotocol_go">
<a href="#clientprotocol_go" style="color: inherit; text-decoration: inherit;">Client<wbr>Protocol</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies whether redis clients can connect using TLS-encrypted or plaintext redis protocols. Default is TLS-encrypted.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="clusteringpolicy_go">
<a href="#clusteringpolicy_go" style="color: inherit; text-decoration: inherit;">Clustering<wbr>Policy</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Clustering policy - default is OSSCluster. Specified at create time.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="evictionpolicy_go">
<a href="#evictionpolicy_go" style="color: inherit; text-decoration: inherit;">Eviction<wbr>Policy</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Redis eviction policy - default is VolatileLRU{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="modules_go">
<a href="#modules_go" style="color: inherit; text-decoration: inherit;">Modules</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#moduleresponse">[]Module<wbr>Response</a></span>
    </dt>
    <dd>{{% md %}}Optional set of redis modules to enable in this database - modules can only be added at creation time.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="port_go">
<a href="#port_go" style="color: inherit; text-decoration: inherit;">Port</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}TCP port of the database endpoint. Specified at create time. Defaults to an available port.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="name_nodejs">
<a href="#name_nodejs" style="color: inherit; text-decoration: inherit;">name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the resource{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="provisioningstate_nodejs">
<a href="#provisioningstate_nodejs" style="color: inherit; text-decoration: inherit;">provisioning<wbr>State</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Current provisioning status of the database{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="resourcestate_nodejs">
<a href="#resourcestate_nodejs" style="color: inherit; text-decoration: inherit;">resource<wbr>State</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Current resource status of the database{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="type_nodejs">
<a href="#type_nodejs" style="color: inherit; text-decoration: inherit;">type</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The type of the resource. E.g. "Microsoft.Compute/virtualMachines" or "Microsoft.Storage/storageAccounts"{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="clientprotocol_nodejs">
<a href="#clientprotocol_nodejs" style="color: inherit; text-decoration: inherit;">client<wbr>Protocol</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies whether redis clients can connect using TLS-encrypted or plaintext redis protocols. Default is TLS-encrypted.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="clusteringpolicy_nodejs">
<a href="#clusteringpolicy_nodejs" style="color: inherit; text-decoration: inherit;">clustering<wbr>Policy</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Clustering policy - default is OSSCluster. Specified at create time.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="evictionpolicy_nodejs">
<a href="#evictionpolicy_nodejs" style="color: inherit; text-decoration: inherit;">eviction<wbr>Policy</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Redis eviction policy - default is VolatileLRU{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="modules_nodejs">
<a href="#modules_nodejs" style="color: inherit; text-decoration: inherit;">modules</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#moduleresponse">Module<wbr>Response[]</a></span>
    </dt>
    <dd>{{% md %}}Optional set of redis modules to enable in this database - modules can only be added at creation time.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="port_nodejs">
<a href="#port_nodejs" style="color: inherit; text-decoration: inherit;">port</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}TCP port of the database endpoint. Specified at create time. Defaults to an available port.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="name_python">
<a href="#name_python" style="color: inherit; text-decoration: inherit;">name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The name of the resource{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="provisioning_state_python">
<a href="#provisioning_state_python" style="color: inherit; text-decoration: inherit;">provisioning_<wbr>state</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Current provisioning status of the database{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="resource_state_python">
<a href="#resource_state_python" style="color: inherit; text-decoration: inherit;">resource_<wbr>state</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Current resource status of the database{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="type_python">
<a href="#type_python" style="color: inherit; text-decoration: inherit;">type</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The type of the resource. E.g. "Microsoft.Compute/virtualMachines" or "Microsoft.Storage/storageAccounts"{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="client_protocol_python">
<a href="#client_protocol_python" style="color: inherit; text-decoration: inherit;">client_<wbr>protocol</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Specifies whether redis clients can connect using TLS-encrypted or plaintext redis protocols. Default is TLS-encrypted.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="clustering_policy_python">
<a href="#clustering_policy_python" style="color: inherit; text-decoration: inherit;">clustering_<wbr>policy</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Clustering policy - default is OSSCluster. Specified at create time.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="eviction_policy_python">
<a href="#eviction_policy_python" style="color: inherit; text-decoration: inherit;">eviction_<wbr>policy</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Redis eviction policy - default is VolatileLRU{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="modules_python">
<a href="#modules_python" style="color: inherit; text-decoration: inherit;">modules</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#moduleresponse">Sequence[Module<wbr>Response]</a></span>
    </dt>
    <dd>{{% md %}}Optional set of redis modules to enable in this database - modules can only be added at creation time.{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="port_python">
<a href="#port_python" style="color: inherit; text-decoration: inherit;">port</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">int</a></span>
    </dt>
    <dd>{{% md %}}TCP port of the database endpoint. Specified at create time. Defaults to an available port.{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Supporting Types


<h4 id="moduleresponse">Module<wbr>Response</h4>







{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="name_csharp">
<a href="#name_csharp" style="color: inherit; text-decoration: inherit;">Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the module, e.g. 'RedisBloom', 'RediSearch', 'RedisTimeSeries'{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="version_csharp">
<a href="#version_csharp" style="color: inherit; text-decoration: inherit;">Version</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The version of the module, e.g. '1.0'.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="args_csharp">
<a href="#args_csharp" style="color: inherit; text-decoration: inherit;">Args</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Configuration options for the module, e.g. 'ERROR_RATE 0.00 INITIAL_SIZE 400'.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="name_go">
<a href="#name_go" style="color: inherit; text-decoration: inherit;">Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the module, e.g. 'RedisBloom', 'RediSearch', 'RedisTimeSeries'{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="version_go">
<a href="#version_go" style="color: inherit; text-decoration: inherit;">Version</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The version of the module, e.g. '1.0'.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="args_go">
<a href="#args_go" style="color: inherit; text-decoration: inherit;">Args</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Configuration options for the module, e.g. 'ERROR_RATE 0.00 INITIAL_SIZE 400'.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="name_nodejs">
<a href="#name_nodejs" style="color: inherit; text-decoration: inherit;">name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the module, e.g. 'RedisBloom', 'RediSearch', 'RedisTimeSeries'{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="version_nodejs">
<a href="#version_nodejs" style="color: inherit; text-decoration: inherit;">version</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The version of the module, e.g. '1.0'.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="args_nodejs">
<a href="#args_nodejs" style="color: inherit; text-decoration: inherit;">args</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Configuration options for the module, e.g. 'ERROR_RATE 0.00 INITIAL_SIZE 400'.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="name_python">
<a href="#name_python" style="color: inherit; text-decoration: inherit;">name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The name of the module, e.g. 'RedisBloom', 'RediSearch', 'RedisTimeSeries'{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="version_python">
<a href="#version_python" style="color: inherit; text-decoration: inherit;">version</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The version of the module, e.g. '1.0'.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="args_python">
<a href="#args_python" style="color: inherit; text-decoration: inherit;">args</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Configuration options for the module, e.g. 'ERROR_RATE 0.00 INITIAL_SIZE 400'.{{% /md %}}</dd>

</dl>
{{% /choosable %}}









<h2 id="package-details">Package Details</h2>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-azure-nextgen">https://github.com/pulumi/pulumi-azure-nextgen</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
</dl>
