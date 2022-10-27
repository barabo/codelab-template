## Codelab Examples

### What You'll Learn
- How to trigger the special syntax of a codelab, as processed by the `claat` tool.
- What each special feature *looks like*.
  - What You'll Learn
  - Tables
  - Infoboxes
  - Surveys
  - Download Button
  - Embedded iframes
  - Frequently Asked Questions
  - What We've Covered

When you use the magic H3 heading `### What You'll Learn` - the following unordered list will be rendered using green checkboxes instead of the default bullet points.

#### `codelab markdown`
```html
### What You'll Learn
- hi
- there
```

### Tables

Your codelab can use very simple markdown (or HTML) tables.

#### HTML-based
<table>
  <tr><td>one</td><td>two</td><td>nine</td><td>thirteen</td></tr>
  <tr><td>three</td><td>four</td><td>ten</td></tr>
  <tr><td>five</td><td>six</td><td>eleven</td></tr>
  <tr><td>seven</td><td>eight</td><td>twelve</td></tr>
</table>

#### Markdown-based
| This  | Is    | A      | Table    |
|-------|-------|--------|----------|
| one   | two   | nine   | thirteen |
| three | four  | ten    |          |
| five  | six   | eleven |          |
| seven | eight | twelve |          |

#### `codelab markdown`

```html

#### HTML-based
<table>
  <tr><td>one</td><td>two</td><td>nine</td><td>thirteen</td></tr>
  <tr><td>three</td><td>four</td><td>ten</td></tr>
  <tr><td>five</td><td>six</td><td>eleven</td></tr>
  <tr><td>seven</td><td>eight</td><td>twelve</td></tr>
</table>

#### Markdown-based
|-------|-------|--------|----------|
| one   | two   | nine   | thirteen |
| three | four  | ten    |          |
| five  | six   | eleven |          |
| seven | eight | twelve |          |

```

### Infoboxes

You can highlight a section of code as either a positive or a negative infobox.

<dt>positive</dt>
<p>This is a positive infobox.</p>

<dt>negative</dt>
<p>This is a negative infobox.</p>

#### `codelab markdown`

```html
<dt>positive</dt>
<p>This is a positive infobox.</p>

<dt>negative</dt>
<p>This is a negative infobox.</p>
```

<!--- This is an example codelab survey  --->
### Surveys

You can include a survey in the codelab which will create Google Analytics variables, which will collect survey response totals.

<dl><dt style="background-color:#cfe2f3;">Survey</dt>
<dd>
  <li>Example item 1</li>
  <li>Example item 2</li>
</dd></dl>

#### `codelab markdown`
```html
<dl><dt style="background-color:#cfe2f3;">Survey</dt>
<dd>
  <li>Example item 1</li>
  <li>Example item 2</li>
</dd></dl>
```

#### IMPORTANT!
<dt>Negative</dt>
<p>Unfortunately, the background color value (`#cfe2f3`) is a *magic* attribute value.  Without this *exact* color value, the Survey object will not work as intended.</p>

### Download buttons

You can create a special button to Download something (like a tagged github repo).
[Download v3.0](https://github.com/microsoft-healthcare-madison/demo-auc-app/archive/v3.0.zip)

Negative
: This currently doesn't work with the `claat` tool!  Instead the 'button' is shown as a download link.

### Embedded iframes
You can embed an iframe in a codelab by setting the `alt` attribute of an `img` element.

#### Example: embedded `https://glitch.com/~howoldisit`

![https://glitch.com/embed/#!/embed/jewel-chevre?path=package.json&previewSize=100](Glitch iframe)

#### `codelab markdown`
```html
![https://glitch.com/embed/#!/embed/jewel-chevre?path=package.json&previewSize=100](Glitch iframe)
```

### Frequently Asked Questions
- <https://stackoverflow.com/questions/43001894/google-codelab-mistake>
- <https://developer.android.com/courses/fundamentals-training/toc-v2>

When linking to stack-overflow (and a few other google-specific URLs) - the link icon is automatically inserted into the link.

#### `codelab markdown`

```html
### Frequently Asked Questions
- <https://stackoverflow.com/questions/43001894/google-codelab-mistake>
- <https://developer.android.com/courses/fundamentals-training/toc-v2>
```

### What We've Covered
- How to trigger the special syntax of a codelab, as processed by the `claat` tool.
- What each special feature *looks like*.
  - What You'll Learn
  - Tables
  - Infoboxes
  - Surveys
  - Download Button
  - Embedded iframes
  - Frequently Asked Questions
  - What We've Covered

When you use the magic H3 heading `### What We've Covered` - the following unordered list will be rendered using green checkboxes instead of the default bullet points.

#### `codelab markdown`
```html
### What We've Covered
- good
- bye
```