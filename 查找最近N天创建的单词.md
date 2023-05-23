```sql
select * from blocks where hpath like "/%" and type="d" and created > strftime('%Y%m%d%H%M%S', datetime('now', '-1 day')) and content not regexp '[一-龟]' and content not regexp '[A-Z]' limit 1000;
```



{: custom-type="query-code" }

<iframe src="/widgets/Query" data-src="/widgets/Query" data-subtype="widget" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>
{: custom-type="query-widget"}

