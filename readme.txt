The <strong>simpleCombo</strong> plugin is a jQuery-based combo box widget that is
<ul>
	<li>simple</li>
	<li>lightweight</li>
	<li>consistent with native widget look and feel</li>
</ul>

<p>with simpleCombo, you can turn select lists into combo boxes like this:</p>

<div class="codeblock"><code>$(</code><em>selector</em><code>).simpleCombo();</code></div>

<p>Simple combo boxes are normal select lists with one extra feature: you can type
directly into the combo box to add an extra option, which is automatically
selected.</p>

<p>Since these combo boxes are actually just select lists plus JavaScript, they
look exactly like regular select lists. They can be styled, resized, etc.
with no visual glitches.</p>

<h3>Example</h3>

<p>Add combo box functionality to all select lists with the "allow-edit" class.</p>

<div class="codeblock"><code>$('select.allow-edit').simpleCombo();</code></div>

<h3>Notes</h3>

<ul>
	<li>On Safari, characters cannot be entered when the combo is expanded.</li>
	<li>Only regular ascii characters can be entered: no accented letters or non-Latin characters.</li>
</ul>
