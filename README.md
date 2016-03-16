## Test:

<p>
<input type="checkbox" onclick="onChecboxClick(event)"/> Checkbox 1
<input type="checkbox" onclick="onChecboxClick(event)"checked/> Checkbox 2
<input type="checkbox" onclick="onChecboxClick(event)"/> Checkbox 3
<input type="checkbox" onclick="onChecboxClick(event)"/> Checkbox 4
</p>

<p>
<input type="checkbox" onclick="onChecboxClick(event)"/> Checkbox 1<br>
<input type="checkbox" onclick="onChecboxClick(event)"checked/> Checkbox 2<br>
<input type="checkbox" onclick="onChecboxClick(event)"/> Checkbox 3<br>
<input type="checkbox" onclick="onChecboxClick(event)"/> Checkbox 4<br>
</p>


# wysiwyg-e
<!-- [![Build Status](https://travis-ci.org/miztroh/wysiwyg-e.svg?branch=master)](https://travis-ci.org/miztroh/wysiwyg-e) -->

> /wɪziwɪɡi/

> A what-you-see-is-what-you-get editor created with Polymer.  Under the hood, it provides undo / redo history management, selection management, and a toolbar that accepts child elements to provide editing capabilities.  All the included tools (see below for list) are accessible via both the toolbar buttons and keyboard shortcuts.

## Included Tools (opt-in)
* Bold
* Italic
* Underline
* Strikethrough
* Remove Format
* Link
* Image
* List (numbered / bulleted)
* Indent / Outdent
* Heading (H1 - H6)
* Blockquote
* Undo / Redo

## Usage
```
<wysiwyg-e>
  <wysiwyg-tool-bold class="wysiwyg-tool"></wysiwyg-tool-bold>
  <wysiwyg-tool-italic class="wysiwyg-tool"></wysiwyg-tool-italic>
  <wysiwyg-tool-underline class="wysiwyg-tool"></wysiwyg-tool-underline>
  <wysiwyg-tool-strike-through class="wysiwyg-tool"></wysiwyg-tool-strike-through>
  <wysiwyg-tool-remove-format class="wysiwyg-tool"></wysiwyg-tool-remove-format>
  <wysiwyg-tool-create-link-and-unlink class="wysiwyg-tool"></wysiwyg-tool-create-link-and-unlink>
  <wysiwyg-tool-insert-image class="wysiwyg-tool"></wysiwyg-tool-insert-image>
  <wysiwyg-tool-insert-list class="wysiwyg-tool"></wysiwyg-tool-insert-list>
  <wysiwyg-tool-indent class="wysiwyg-tool"></wysiwyg-tool-indent>
  <wysiwyg-tool-outdent class="wysiwyg-tool"></wysiwyg-tool-outdent>
  <wysiwyg-tool-heading class="wysiwyg-tool" h1 h2 h3 h4 h5 h6></wysiwyg-tool-heading>
  <wysiwyg-tool-blockquote class="wysiwyg-tool"></wysiwyg-tool-blockquote>
  <wysiwyg-tool-undo class="wysiwyg-tool"></wysiwyg-tool-undo>
  <wysiwyg-tool-redo class="wysiwyg-tool"></wysiwyg-tool-redo>
</wysiwyg-e>
```

## Demo
https://miztroh.github.io/bower_components/wysiwyg-e/demo/

## Installation
``bower install wysiwyg-e``
