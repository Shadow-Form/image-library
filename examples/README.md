# Usage

## Markdown

Inside this repo, use relative paths:

```markdown
![Logic Apps](../icons/cloud/azure/logic-apps/logic-apps.svg)
```

From another repo, use the raw URL:

```markdown
![Logic Apps](https://raw.githubusercontent.com/Shadow-Form/image-library/main/icons/cloud/azure/logic-apps/logic-apps.svg)
```

## HTML (for sizing)

Markdown can't set image size, so use `<img>`:

```html
<img src="https://raw.githubusercontent.com/Shadow-Form/image-library/main/icons/cloud/azure/logic-apps/logic-apps.svg" alt="Logic Apps" width="48" height="48">
```

## Icon table

```html
<table>
  <tr>
    <td align="center"><img src="../icons/cloud/azure/functions/functions.svg" width="48" alt="Functions"><br>Functions</td>
    <td align="center"><img src="../icons/cloud/azure/logic-apps/logic-apps.svg" width="48" alt="Logic Apps"><br>Logic Apps</td>
    <td align="center"><img src="../icons/cloud/azure/storage/storage.svg" width="48" alt="Storage"><br>Storage</td>
  </tr>
</table>
```

## Inline with text

```html
<img src="../icons/languages/python/python.svg" width="16" alt=""> Python
```
