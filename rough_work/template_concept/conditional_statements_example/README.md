## Conditional statements concept in ansible templating

- ansible.cgf and hosts inventory files used here, are same as tomcat example.
- Below is code block for if conditional statement in jinja format,

```
{% if condition %}
steps to perform if condition is true
{% endif %}
```

- Below is code block for if-else conditional statement in jinja format,

```
{% if condition %}
steps to perform if condition is true
{% else %}
stpes to perform if condition is false
{% endif %}
```

- Below is code block for if-elif-else conditional statement in jinja format,

```
{% if condition %}
steps to perform if condition is true
{% elif condition %}
steps to perform if second condition is true
{% else %}
steps to perform if all ablve conditions are false
{% endif %}
```

- Similarly, we can include as many conditions as we desire to evaluate using if-elif-else construct.

