- [Home](/)
- :globe_with_meridians: Language 
    - [:uk: English](/en)
    - [:cn: 简体中文](/zh-cn/)
- [Github](https://github.com/becoze)
- [Theme]()
  - <div class="demo-theme-preview"> <a data-theme="vue">Light</a>
  - <a data-theme="dark">Dark</a>
</div>

<style>
  .demo-theme-preview a:hover {
    cursor: pointer;
    text-decoration: underline;
  }
</style>

<script>
  const preview = Docsify.dom.find('.demo-theme-preview');
  const themes = Docsify.dom.findAll('[rel="stylesheet"]');

  preview.onclick = function (e) {
    const title = e.target.getAttribute('data-theme');

    themes.forEach(theme => {
      theme.disabled = theme.title !== title;
    });
  };
</script>
