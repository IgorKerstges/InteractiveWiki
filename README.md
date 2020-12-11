# Title

<div id="builder">

Domain: <input v-model="domain" placeholder="www.example.com">
IP-Address: <input v-model="ip" placeholder="127.0.0.1">

Your domain is: <span style="color: red;">{{ domain }}</span>
Your IP-Adress is: <span style="color: red;">{{ ip }}</span>

**Note:** Markdown codeblocks do not support Vue interactivity

```
curl {{ domain }}
```

**Fix:** Use HTML tags to render codeblocks instead

<pre><code>testing in codeblock, domain entered: {{ domain }}</code></pre>

</div>
