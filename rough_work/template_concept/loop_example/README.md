## Loop statement concept in ansible templating

- ansible.cgf and hosts inventory files used here, are same as tomcat example.
- Below is code block for loop construct in jinja format,

```
{% for each in list_of_values %}
statement to be iterated
we can use value of {{ each }} as well
{% endfor %}
```

