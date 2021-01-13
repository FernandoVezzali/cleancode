## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/FernandoVezzali/dotnetcleancode.github.io/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/FernandoVezzali/dotnetcleancode.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

# Clean Code .NET

## Naming

<details>
  <summary><b>Avoid using bad names</b></summary>
A good name allows the code to be used by many developers. The name should reflect what it does and give context.

**Bad:**

```csharp
int d;
```

**Good:**

```csharp
int daySinceModification;
```
</details>

<details>
  <summary><b>Avoid Misleading Names</b></summary>

Name the variable to reflect what it is used for.

**Bad:**

```csharp
var dataFromDb = db.GetFromService().ToList();
```

**Good:**

```csharp
var listOfEmployee = _employeeService.GetEmployees().ToList();
```
