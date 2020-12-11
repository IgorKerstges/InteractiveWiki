# Title

<div id="builder">

Domain: <input v-model="domain" placeholder="www.example.com"><br>
IP-Address: <input v-model="ipaddress" placeholder="127.0.0.1"><br>

Your domain is: <span style="color: red;">{{ domain }}</span><br>
Your IP-Adress is: <span style="color: red;">{{ ipaddress }}</span><br>

**Note:** Markdown codeblocks do not support Vue interactivity

```
curl {{ domain }}
```

**Fix:** Use HTML tags to render codeblocks instead

<pre><code>testing in codeblock, domain entered: {{ domain }}</code></pre>

</div>
