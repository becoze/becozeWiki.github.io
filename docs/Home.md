# Hi~!

You can "Type to Search" on the top of the left-sidebar.





About me

Author: Liyuan Liang  (Nick)

Location: Sydney, NSW, Australia 

LinkedIn: 

My GitHub: 

Contact: 

- email: 
- Phone: 





Project

This Wiki on GitHub: 

Welcome to visit my other Blog: https://becoze.github.io/. 


<div class="demo-theme-preview"> 
<a data-theme="vue">Light</a>
<a data-theme="dark">Dark</a>
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