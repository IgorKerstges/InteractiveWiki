# Title

<div id="builder">

Domain: <input v-model="domain" placeholder="www.example.com">

Your domain is: <span style="color: red;">{{ domain }}</span>

**Note:** Markdown codeblocks do not support Vue interactivity

```
curl {{ domain }}
```

**Fix:** Use HTML tags to render codeblocks instead

<pre><code>curl {{ domain }}</code></pre>

</div>
