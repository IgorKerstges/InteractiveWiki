# Title

<div id="builder">

Domain: <input v-model="domain" placeholder="www.example.com"><br>
IP-Address: <input v-model="ipaddress" placeholder="127.0.0.1"><br>

Your domain is: {{ domain }} <br>
Your IP-Adress is: {{ ipaddress }} <br>

**Note:** Markdown codeblocks do not support Vue interactivity

```
curl {{ domain }}
```

**Fix:** Use HTML tags to render codeblocks instead

<pre><code>testing in codeblock, domain entered: {{ domain }}</code></pre>

</div>
