<h1>noctalia-shell user-template for kew</h1>
<h2>how to use it !</h2>
<li>
<ol>copy noctalia.theme to ~/.config/noctalia/templates if you dont have templates folder create it </ol>
  <ol>in ~/.config/noctalia/user-templates.toml add 
<pre>
[templates.myapp]
input_path = "~/.config/noctalia/templates/noctalia.theme"
output_path = "~/.config/kew/themes/noctalia.theme"
post_hook = "kew theme noctalia"
</pre></ol>
  <ol>now you just need to enable user-templates in noctalia settings </ol>
</li>
<h3>kew doesnt provide a way to reload it so you will need to lauch it again after theme change</h3>
