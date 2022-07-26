---
translation: false
---

{{<section howto>}}

{
    "@context": "http://schema.org/",
    "@type": "HowTo",
    "name": "{{name}}",
    "image": "{{image}}",
    "totalTime": "PT1M",
    "supply": [{ "@type": "HowToSupply", "name": "{{supply}}" }],
    "tool": [{ "@type": "HowToTool", "name": "{{tool}}" }],
    "step": [ 
        {{#steps}}
        {
            "@type": "HowToStep",
            "name": "{{name}}",
            "text": "{{text}}",
            "image": "{{image}}",
            "url": "{{url}}"
        },
        {{/steps}}
    ]
}

{{<section faq>}}