# Title

<div id="builder">

Domain: <input v-model="domain" placeholder="www.example.com"><br>
IP-Address: <input v-model="ipaddress" placeholder="127.0.0.1"><br>
Port-Number: <input v-model="port" placeholder="80"><br>

You entered domain: {{ domain }} <br>
You entered IP-Adress: {{ ipaddress }} <br>
You entered Port-Number: {{ port }} <br>

**Note:** Markdown codeblocks do not support Vue interactivity

```
curl {{ domain }}
```

**Fix:** Use HTML tags to render codeblocks instead

<pre><code>testing in codeblock, domain entered: {{ domain }}</code></pre>

</div>
