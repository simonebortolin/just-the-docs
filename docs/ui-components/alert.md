---
layout: default
title: Alert
parent: UI Components
nav_order: 8
---

# Alert

<div class="code-example" markdown="1">
{% include alert.html alert="Danger" content="The content" icon="svg-warning" color="yellow" %}
{% include alert.html alert="Warning" content="The content" icon="svg-warning" color="red"  %}
{% include alert.html alert="Info" content="The content" icon="svg-info" color="blue"  %}
{% include alert.html alert="N.B." content="The content" icon="svg-info" color="purple" %}
{% include alert.html alert="Good" content="The content" icon="svg-success" color="green"  %}
</div>
{% raw %}
```markdown
{% include alert.html alert="Danger" content="The content" icon="svg-warning" color="yellow" %}
{% include alert.html alert="Warning" content="The content" icon="svg-warning" color="red"  %}
{% include alert.html alert="Info" content="The content" icon="svg-info" color="blue"  %}
{% include alert.html alert="N.B." content="The content" icon="svg-info" color="purple" %}
{% include alert.html alert="Good" content="The content" icon="svg-success" color="green"  %}
```
{% endraw %}