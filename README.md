<H3>Here  my learning Update about python and javascript</H3>
<H4>That I referenced  book 'learning python the hardway '</h4>
<h4>Javascript I referenced 'Eloquent Javascript'</h4>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Learn Python the Hard Way - Exercise 10</title>
  <style>
    body {
      font-family: monospace;
      background-color: #f4f4f4;
      padding: 20px;
    }
    pre {
      background-color: #272822;
      color: #f8f8f2;
      padding: 15px;
      border-radius: 5px;
      overflow-x: auto;
    }
    .comment {
      color: #75715e;
    }
    .string {
      color: #e6db74;
    }
    .code-line {
      display: block;
    }
  </style>
</head>
<body>

<h1>Learn Python the Hard Way - Exercise 10</h1>
<h2>Escape Sequences in Strings</h2>

<pre><code>
<span class="comment"># Escape sequence in string that tells which double quote is part of string and which ends it</span>
<span class="code-line"><span class="string">"I am 6'2\" tall."</span></span>
<span class="comment"># Escape double quote inside string</span>
<span class="code-line"><span class="string">'I am 6\'2\" tall.'</span></span>
<span class="comment"># Escape single quote inside string</span>

<span class="code-line">tabby_cat = <span class="string">"\tI'm tabbed in."</span> <span class="comment"># \t used for tab before string</span></span>
<span class="code-line">persian_cat = <span class="string">"I'm split\non a line."</span> <span class="comment"># \n used to create new line</span></span>
<span class="code-line">backslash_cat = <span class="string">"I'm\\a\\cat."</span> <span class="comment"># \\ used to print backslashes</span></span>

<span class="code-line">fat_cat = <span class="string">"""</span></span>
<span class="string">I'll do a list:</span>
<span class="string">\t* Cat food</span>
<span class="string">\t* Fishies</span>
<span class="string">\t* Catnip\n\t* Grass</span>
<span class="string">"""</span>
</code></pre>

</body>
</html>

$print(tabby_cat)
$print(persian_cat)
$print(backslash_cat)
$print(fat_cat)
