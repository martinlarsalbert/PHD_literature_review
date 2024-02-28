---
category: literaturenote
tags: {% if allTags %}{{allTags}}{% endif %}
citekey: {{citekey}}
status: unread
dateread:
---

> [!Cite]
> {{bibliography}}

>[!Synth]
>**Contribution**:: 
>
>**Related**:: {% for relation in relations | selectattr("citekey") %} [[@{{relation.citekey}}]]{% if not loop.last %}, {% endif%} {% endfor %}
>

>[!md]
{% for type, creators in creators | groupby("creatorType") -%}
{%- for creator in creators -%}
> **{{"First" if loop.first}}{{type | capitalize}}**::
{%- if creator.name %} {{creator.name}}  
{%- else %} {{creator.lastName}}, {{creator.firstName}}  
{%- endif %}  
{% endfor %}~ 
{%- endfor %}    
> **Title**:: {{title}}  
> **Year**:: {{date | format("YYYY")}}  
> **Date**:: {{date | format("YYYY-MM-DD")}}  
> **Citekey**:: {{citekey}} {%- if itemType %}  
> **itemType**:: {{itemType}}{%- endif %}{%- if itemType == "journalArticle" %}  
> **Journal**:: *{{publicationTitle}}* {%- endif %}{%- if volume %}  
> **Volume**:: {{volume}} {%- endif %}{%- if issue %}  
> **Issue**:: {{issue}} {%- endif %}{%- if itemType == "bookSection" %}  
> **Book**:: {{publicationTitle}} {%- endif %}{%- if publisher %}  
> **Publisher**:: {{publisher}} {%- endif %}{%- if place %}  
> **Location**:: {{place}} {%- endif %}{%- if pages %}   
> **Pages**:: {{pages}} {%- endif %}{%- if DOI %}  
> **DOI**:: {{DOI}} {%- endif %}{%- if ISBN %}  
> **ISBN**:: {{ISBN}} {%- endif %}    

> [!link]-
> zotero_link:: {{pdfZoteroLink}}


> [!Abstract]
> {%- if abstractNote %}
> {{abstractNote}}
> {%- endif -%}.
> 
# Notes

| <mark class="hltr-grey">Highlight Color</mark> | Meaning                       |
| ---------------------------------------------- | ----------------------------- |
| <mark class="hltr-red">Red</mark>              | Disagree with Author          |
| <mark class="hltr-orange">Orange</mark>        | Important Point By Author     |
| <mark class="hltr-yellow">Yellow</mark>        | Interesting Point             |
| <mark class="hltr-green">Green</mark>          | Important To Me               |
| <mark class="hltr-blue">Blue</mark>            | Notes After Initial Iteration |
| <mark class="hltr-purple">Purple</mark>        | Literary Note To Lookup Later |

{% persist "notes" %}{% if isFirstImport %}
- First thing
- Second thing
things to add each time you import:
{% endif %}
{% endpersist %}

>{%- if markdownNotes %}
>{{markdownNotes}}{%- endif -%}.
 
 Annotations
{% for annotation in annotations -%}
    {%- if annotation.annotatedText -%} 
		- <mark class="hltr-{{annotation.colorCategory | lower}}">"{{annotation.annotatedText | escape}}”</mark> [Page {{annotation.page}}](zotero://open-pdf/library/items/{{annotation.attachment.itemKey}}?page={{annotation.page}}&annotation={{annotation.id}})
    {%- endif %} 
    {%- if annotation.imageRelativePath -%}
    ![[{{annotation.imageRelativePath}}]] {%- endif %} 
{% if annotation.comment %} 
	- {{annotation.comment}} 
{% endif %} 
{% endfor -%}