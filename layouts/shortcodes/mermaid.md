<div class="container">
  <pre class="mermaid">
      {{- .Inner | safeHTML }}
  </pre>
</div>
{{ .Page.Store.Set "hasMermaid" true }}