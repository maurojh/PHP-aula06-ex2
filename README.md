<!DOCTYPE html>
<html>
<head>
<!-- 2019-09-23 seg 19:00 -->
<meta http-equiv="Content-Type" content="text/html;charset=utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>&lrm;</title>
<meta name="generator" content="Org mode" />
<link href="https://fonts.googleapis.com/css?family=Noto+Sans|Source+Sans+Pro&display=swap" rel="stylesheet">
<style type="text/css">
 <!--/*--><![CDATA[/*><!--*/
  body { font-family: 'Noto Sans', sans-serif; }
  .title  { text-align: center;
             margin-bottom: .2em; }
  .subtitle { text-align: center;
              font-size: medium;
              font-weight: bold;
              margin-top:0; }
  .todo   { font-family: monospace; color: red; }
  .done   { font-family: monospace; color: green; }
  .priority { font-family: monospace; color: orange; }
  .tag    { background-color: #eee; font-family: monospace;
            padding: 2px; font-size: 80%; font-weight: normal; }
  .timestamp { color: #bebebe; }
  .timestamp-kwd { color: #5f9ea0; }
  .org-right  { margin-left: auto; margin-right: 0px;  text-align: right; }
  .org-left   { margin-left: 0px;  margin-right: auto; text-align: left; }
  .org-center { margin-left: auto; margin-right: auto; text-align: center; }
  .underline { text-decoration: underline; }
  #postamble p, #preamble p { font-size: 90%; margin: .2em; }
  p.verse { margin-left: 3%; }
  pre {
    border: 1px solid #ccc;
    box-shadow: 3px 3px 3px #eee;
    padding: 8pt;
    font-family: monospace;
    overflow: auto;
    margin: 1.2em;
  }
  pre.src {
    position: relative;
    overflow: visible;
    padding-top: 1.2em;
  }
  pre.src:before {
    display: none;
    position: absolute;
    background-color: white;
    top: -10px;
    right: 10px;
    padding: 3px;
    border: 1px solid black;
  }
  pre.src:hover:before { display: inline;}
  /* Languages per Org manual */
  pre.src-asymptote:before { content: 'Asymptote'; }
  pre.src-awk:before { content: 'Awk'; }
  pre.src-C:before { content: 'C'; }
  /* pre.src-C++ doesn't work in CSS */
  pre.src-clojure:before { content: 'Clojure'; }
  pre.src-css:before { content: 'CSS'; }
  pre.src-D:before { content: 'D'; }
  pre.src-ditaa:before { content: 'ditaa'; }
  pre.src-dot:before { content: 'Graphviz'; }
  pre.src-calc:before { content: 'Emacs Calc'; }
  pre.src-emacs-lisp:before { content: 'Emacs Lisp'; }
  pre.src-fortran:before { content: 'Fortran'; }
  pre.src-gnuplot:before { content: 'gnuplot'; }
  pre.src-haskell:before { content: 'Haskell'; }
  pre.src-hledger:before { content: 'hledger'; }
  pre.src-java:before { content: 'Java'; }
  pre.src-js:before { content: 'Javascript'; }
  pre.src-latex:before { content: 'LaTeX'; }
  pre.src-ledger:before { content: 'Ledger'; }
  pre.src-lisp:before { content: 'Lisp'; }
  pre.src-lilypond:before { content: 'Lilypond'; }
  pre.src-lua:before { content: 'Lua'; }
  pre.src-matlab:before { content: 'MATLAB'; }
  pre.src-mscgen:before { content: 'Mscgen'; }
  pre.src-ocaml:before { content: 'Objective Caml'; }
  pre.src-octave:before { content: 'Octave'; }
  pre.src-org:before { content: 'Org mode'; }
  pre.src-oz:before { content: 'OZ'; }
  pre.src-plantuml:before { content: 'Plantuml'; }
  pre.src-processing:before { content: 'Processing.js'; }
  pre.src-python:before { content: 'Python'; }
  pre.src-R:before { content: 'R'; }
  pre.src-ruby:before { content: 'Ruby'; }
  pre.src-sass:before { content: 'Sass'; }
  pre.src-scheme:before { content: 'Scheme'; }
  pre.src-screen:before { content: 'Gnu Screen'; }
  pre.src-sed:before { content: 'Sed'; }
  pre.src-sh:before { content: 'shell'; }
  pre.src-sql:before { content: 'SQL'; }
  pre.src-sqlite:before { content: 'SQLite'; }
  /* additional languages in org.el's org-babel-load-languages alist */
  pre.src-forth:before { content: 'Forth'; }
  pre.src-io:before { content: 'IO'; }
  pre.src-J:before { content: 'J'; }
  pre.src-makefile:before { content: 'Makefile'; }
  pre.src-maxima:before { content: 'Maxima'; }
  pre.src-perl:before { content: 'Perl'; }
  pre.src-picolisp:before { content: 'Pico Lisp'; }
  pre.src-scala:before { content: 'Scala'; }
  pre.src-shell:before { content: 'Shell Script'; }
  pre.src-ebnf2ps:before { content: 'ebfn2ps'; }
  /* additional language identifiers per "defun org-babel-execute"
       in ob-*.el */
  pre.src-cpp:before  { content: 'C++'; }
  pre.src-abc:before  { content: 'ABC'; }
  pre.src-coq:before  { content: 'Coq'; }
  pre.src-groovy:before  { content: 'Groovy'; }
  /* additional language identifiers from org-babel-shell-names in
     ob-shell.el: ob-shell is the only babel language using a lambda to put
     the execution function name together. */
  pre.src-bash:before  { content: 'bash'; }
  pre.src-csh:before  { content: 'csh'; }
  pre.src-ash:before  { content: 'ash'; }
  pre.src-dash:before  { content: 'dash'; }
  pre.src-ksh:before  { content: 'ksh'; }
  pre.src-mksh:before  { content: 'mksh'; }
  pre.src-posh:before  { content: 'posh'; }
  /* Additional Emacs modes also supported by the LaTeX listings package */
  pre.src-ada:before { content: 'Ada'; }
  pre.src-asm:before { content: 'Assembler'; }
  pre.src-caml:before { content: 'Caml'; }
  pre.src-delphi:before { content: 'Delphi'; }
  pre.src-html:before { content: 'HTML'; }
  pre.src-idl:before { content: 'IDL'; }
  pre.src-mercury:before { content: 'Mercury'; }
  pre.src-metapost:before { content: 'MetaPost'; }
  pre.src-modula-2:before { content: 'Modula-2'; }
  pre.src-pascal:before { content: 'Pascal'; }
  pre.src-ps:before { content: 'PostScript'; }
  pre.src-prolog:before { content: 'Prolog'; }
  pre.src-simula:before { content: 'Simula'; }
  pre.src-tcl:before { content: 'tcl'; }
  pre.src-tex:before { content: 'TeX'; }
  pre.src-plain-tex:before { content: 'Plain TeX'; }
  pre.src-verilog:before { content: 'Verilog'; }
  pre.src-vhdl:before { content: 'VHDL'; }
  pre.src-xml:before { content: 'XML'; }
  pre.src-nxml:before { content: 'XML'; }
  /* add a generic configuration mode; LaTeX export needs an additional
     (add-to-list 'org-latex-listings-langs '(conf " ")) in .emacs */
  pre.src-conf:before { content: 'Configuration File'; }

  table { border-collapse:collapse; }
  caption.t-above { caption-side: top; }
  caption.t-bottom { caption-side: bottom; }
  td, th { vertical-align:top;  }
  th.org-right  { text-align: center;  }
  th.org-left   { text-align: center;   }
  th.org-center { text-align: center; }
  td.org-right  { text-align: right;  }
  td.org-left   { text-align: left;   }
  td.org-center { text-align: center; }
  dt { font-weight: bold; }
  .footpara { display: inline; }
  .footdef  { margin-bottom: 1em; }
  .figure { padding: 1em; }
  .figure p { text-align: center; }
  .inlinetask {
    padding: 10px;
    border: 2px solid gray;
    margin: 10px;
    background: #ffffcc;
  }
  #org-div-home-and-up
   { text-align: right; font-size: 70%; white-space: nowrap; }
  textarea { overflow-x: auto; }
  .linenr { font-size: smaller }
  .code-highlighted { background-color: #ffff00; }
  .org-info-js_info-navigation { border-style: none; }
  #org-info-js_console-label
    { font-size: 10px; font-weight: bold; white-space: nowrap; }
  .org-info-js_search-highlight
    { background-color: #ffff00; color: #000000; font-weight: bold; }
  .org-svg { width: 90%; }
  pre, code   body { font-family: 'Noto Sans', sans-serif; }
  /*]]>*/-->
</style>
<script type="text/javascript">
/*
@licstart  The following is the entire license notice for the
JavaScript code in this tag.

Copyright (C) 2012-2019 Free Software Foundation, Inc.

The JavaScript code in this tag is free software: you can
redistribute it and/or modify it under the terms of the GNU
General Public License (GNU GPL) as published by the Free Software
Foundation, either version 3 of the License, or (at your option)
any later version.  The code is distributed WITHOUT ANY WARRANTY;
without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE.  See the GNU GPL for more details.

As additional permission under GNU GPL version 3 section 7, you
may distribute non-source (e.g., minimized or compacted) forms of
that code without the copy of the GNU GPL normally required by
section 4, provided you include this license notice and a URL
through which recipients can access the Corresponding Source.


@licend  The above is the entire license notice
for the JavaScript code in this tag.
*/
<!--/*--><![CDATA[/*><!--*/
 function CodeHighlightOn(elem, id)
 {
   var target = document.getElementById(id);
   if(null != target) {
     elem.cacheClassElem = elem.className;
     elem.cacheClassTarget = target.className;
     target.className = "code-highlighted";
     elem.className   = "code-highlighted";
   }
 }
 function CodeHighlightOff(elem, id)
 {
   var target = document.getElementById(id);
   if(elem.cacheClassElem)
     elem.className = elem.cacheClassElem;
   if(elem.cacheClassTarget)
     target.className = elem.cacheClassTarget;
 }
/*]]>*///-->
</script>
</head>
<body>
<div id="content">
<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#orga149d4f">1. Conexão com banco de dados</a>
<ul>
<li><a href="#org741742d">1.1. Abrindo a conexão</a></li>
<li><a href="#org8d2b226">1.2. Fechar a conexão</a></li>
<li><a href="#orgae4dd31">1.3. Exercício 1</a></li>
<li><a href="#orgd7cd520">1.4. Criando banco de dados MySQL</a></li>
<li><a href="#org9596e0a">1.5. Exercício 2</a></li>
</ul>
</li>
</ul>
</div>
</div>
<div id="outline-container-orga149d4f" class="outline-2">
<h2 id="orga149d4f"><span class="section-number-2">1</span> Conexão com banco de dados</h2>
<div class="outline-text-2" id="text-1">
<p>
PHP possui três formas de trabalhar com MySQL:
</p>

<ul class="org-ul">
<li>MySQLi (orientado à objeto)</li>
<li>MySQLi (procedural)</li>
<li>PDO</li>
</ul>

<p>
PDO trabalha com 12 sistemas de banco de dados diferentes.
</p>

<p>
MySQLi trabalha apenas com banco de dados MySQL.
</p>
</div>

<div id="outline-container-org741742d" class="outline-3">
<h3 id="org741742d"><span class="section-number-3">1.1</span> Abrindo a conexão</h3>
<div class="outline-text-3" id="text-1-1">
<p>
Antes de acessar os dados em um banco de dados MySQL, você precisa se conectar ao servidor:
</p>

<pre class="example">
&lt;?php

$servidor = "localhost";
$usuario = "root";
$senha = "toor";

// Cria a conexão:
$conexao = mysqli_connect($servidor, $usuario, $senha);

// Verifica a conexão
if( $conexao == false ) {
   die("A conexão falhou: " . mysqli_connect_error());
}

echo "Conexão realizada com sucesso!";
?&gt;
</pre>
</div>
</div>

<div id="outline-container-org8d2b226" class="outline-3">
<h3 id="org8d2b226"><span class="section-number-3">1.2</span> Fechar a conexão</h3>
<div class="outline-text-3" id="text-1-2">
<p>
Quando o script termina a conexão com o banco de dados é fechada automaticamente. Mas podemos fechá-la antes:
</p>

<pre class="example">
mysqli_close($conexao);
</pre>
</div>
</div>

<div id="outline-container-orgae4dd31" class="outline-3">
<h3 id="orgae4dd31"><span class="section-number-3">1.3</span> Exercício 1</h3>
<div class="outline-text-3" id="text-1-3">
<p>
Crie uma página php chamada (teste.php) que verifica se a conexão com o servidor de banco de dados está sendo feita corretamente.
</p>
</div>
</div>

<div id="outline-container-orgd7cd520" class="outline-3">
<h3 id="orgd7cd520"><span class="section-number-3">1.4</span> Criando banco de dados MySQL</h3>
<div class="outline-text-3" id="text-1-4">
<p>
Um banco de dados é composto de várias tabelas.
</p>

<p>
Para criar o banco em PHP você efetua uma consulta (query) com o comando de criação:
</p>

<pre class="example">
mysqli_query($conexao, "CREATE DATABASE banco");
</pre>

<p>
A página completa deve:
</p>

<ul class="org-ul">
<li>criar a conexão com o servidor de banco de dados</li>
<li>efetuar a consulta</li>
<li>fechar a conexão</li>
</ul>

<pre class="example">
&lt;?php

$servidor = "localhost";
$usuario = "root";
$senha = "toor";

// Cria a conexão:
$conexao = mysqli_connect($servidor, $usuario, $senha);

// Verifica a conexão
if( $conexao == false ) {
   die("A conexão falhou: " . mysqli_connect_error());
}

echo "Conexão realizada com sucesso!&lt;br&gt;";

// Cria o banco de dados
$sql = "CREATE DATABASE bdEscola";
if (mysqli_query($conexao, $sql)) {
    echo "Banco de dados criado com sucesso!&lt;br&gt;";
} else {
    echo "Erro na criação do banco de dados: " . mysqli_error($conexao);
}

mysqli_close($conexao);
?&gt;
</pre>
</div>
</div>

<div id="outline-container-org9596e0a" class="outline-3">
<h3 id="org9596e0a"><span class="section-number-3">1.5</span> Exercício 2</h3>
<div class="outline-text-3" id="text-1-5">
<p>
Escreva uma página em php (cria.php) que cria um banco de dados chamado: bdLoja.
</p>
</div>
</div>
</div>
</div>
<div id="postamble" class="status">
<p class="date">Created: 2019-09-23 seg 19:00</p>
<p class="validation"><a href="http://validator.w3.org/check?uri=referer">Validate</a></p>
</div>
</body>
</html>
