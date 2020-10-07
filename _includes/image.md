{%capture asset_url%}{{site.baseurl}}/assets{{page.id}}/{%endcapture%}

[![{{include.alt}}]({{asset_url | append: include.src}})]({{asset_url | append: include.src}})
