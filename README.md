# Syntaxe Markdown

Le language Markdwon est à base de caractères spéciaux(#'~...).
Une fois compilé, il retourne des balises HTML.
Il sert à présenter du texte de manière éfficiente (Blog, documentation, etc...).
Quelques caractères et leur correspondance :


## Heading 

* Level 1

```<h1>Heading level 1</h1>```

* Level 2

```<h2>Heading level 2</h2>```

* Etc ...


## Text formatting

* Bold text

                I just love **bold text**.
                or I just love <strong>bold text</strong>.

If you want your page to validate under XHTML 1.0 Strict,
you've got to put paragraph tags in your blockquotes:

<pre><code>&lt;blockquote&gt;
        &lt;p&gt;For example.&lt;/p&gt;
&lt;/blockquote&gt;
</code></pre>

### blockquote

* Small blockquote

<pre><code>
> Dorothy followed her through many of the beautiful rooms in her castle.
</code></pre>

* Large blockquote
<pre><code>&lt;blockquote&gt;
    &lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas aliquet, velit ut placerat tristique, purus metus accumsan ante, sit amet eleifend quam nisl nec lorem. Aliquam erat volutpat. Quisque feugiat commodo sodales. Maecenas suscipit nulla neque, sit amet commodo metus vulputate in. Phasellus nec vulputate turpis. Donec eleifend condimentum porttitor.&lt;/p&gt;
&lt;/blockquote&gt;</code></pre>

preview
<blockquote>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas aliquet, velit ut placerat tristique, purus metus accumsan ante, sit amet eleifend quam nisl nec lorem. Aliquam erat volutpat. Quisque feugiat commodo sodales. Maecenas suscipit nulla neque, sit amet commodo metus vulputate in. Phasellus nec vulputate turpis. Donec eleifend condimentum porttitor.</p>
</blockquote>


1. First item

2. Second item

3. Third item

4. Fourth item

* IMAGES 

<pre><code>![alt text](/path/to/img.jpg "Title")</code></pre>

![alt text](/path/to/img.jpg "Title")

<pre><code>![alt text][id]
[id]: /path/to/img.jpg "Title"</code></pre>

[id]: /path/to/img.jpg "Title"

                <img src="/path/to/img.jpg" alt="alt text" title="Title" />
<img src="/path/to/img.jpg" alt="alt text" title="Title" />

<ol>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
    <li>Fourth item</li>
</ol>

<p>If you want your page to validate under XHTML 1.0 Strict,
you've got to put paragraph tags in your blockquotes:</p>


<pre><code>&lt;blockquote&gt;
    &lt;p&gt;For example.&lt;/p&gt;
&lt;/blockquote&gt;
</code></pre>
