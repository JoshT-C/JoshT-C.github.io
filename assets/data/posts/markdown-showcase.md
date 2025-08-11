---
title: GitHub Markdown Showcase
slug: markdown-showcase
excerpt: A comprehensive showcase of GitHub-flavored markdown features including code highlighting, tables, task lists, and more.
author: Joshua T-C
publishedDate: 2024-01-16
tags: ["markdown", "github", "showcase", "demo"]
category: Documentation
featured: true
---

# GitHub Markdown Showcase :rocket:

This document demonstrates all the GitHub-flavored markdown features supported by our new markdown interpreter.

## Text Formatting

You can make text **bold** or *italic* or ~~strikethrough~~.

You can also use subscript H~2~O and superscript E=mc^2^.

## Headers

# H1 Header
## H2 Header  
### H3 Header
#### H4 Header
##### H5 Header
###### H6 Header

## Links and References

- [External link](https://github.com)
- [Internal link](./other-post)
- Mention someone like @username
- Reference an issue like #123

## Code Examples

### Inline Code

Use `console.log()` to output to the console.

### Code Blocks

```javascript
// JavaScript with syntax highlighting
function fibonacci(n) {
  if (n <= 1) return n;
  return fibonacci(n - 1) + fibonacci(n - 2);
}

console.log(fibonacci(10)); // 55
```

```typescript
// TypeScript example
interface User {
  id: number;
  name: string;
  email?: string;
}

const users: User[] = [
  { id: 1, name: "John Doe", email: "john@example.com" },
  { id: 2, name: "Jane Smith" }
];
```

```css
/* CSS Styling */
.github-markdown-body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  line-height: 1.5;
  color: #1f2328;
}

.code-block {
  background: #f6f8fa;
  border-radius: 6px;
  padding: 16px;
}
```

```bash
# Shell commands
npm install prismjs
git add .
git commit -m "Add markdown showcase"
git push origin main
```

```json
{
  "name": "markdown-showcase",
  "version": "1.0.0",
  "dependencies": {
    "prismjs": "^1.30.0",
    "marked": "^13.0.3"
  }
}
```

## Lists

### Unordered Lists

- First item
- Second item
  - Nested item
  - Another nested item
- Third item

### Ordered Lists

1. First step
2. Second step
   1. Substep A
   2. Substep B
3. Final step

### Task Lists

- [x] Completed task
- [x] Another completed task  
- [ ] Incomplete task
- [ ] Another incomplete task
  - [x] Nested completed task
  - [ ] Nested incomplete task

## Tables

| Feature | Status | Priority |
|---------|--------|----------|
| Syntax highlighting | :white_check_mark: | High |
| Tables | :white_check_mark: | Medium |
| Task lists | :white_check_mark: | Medium |
| Emojis | :white_check_mark: | Low |

## Blockquotes

> This is a blockquote with GitHub-style formatting.
> 
> It can span multiple lines and paragraphs.
>
> > Nested blockquotes are also supported.

## GitHub Alerts

> [!NOTE]
> This is a note alert with useful information.

> [!TIP]  
> This is a tip to help users.

> [!IMPORTANT]
> This highlights important information.

> [!WARNING]
> This is a warning about potential issues.

> [!CAUTION]
> This indicates dangerous or risky actions.

## Images

![Sample Image](https://via.placeholder.com/400x200?text=Sample+Markdown+Image)

## Horizontal Rules

---

## Emojis

GitHub supports emojis! :tada: :rocket: :computer: :heart:

Some programming emojis:
- :bug: for bugs
- :sparkles: for new features  
- :fire: for performance improvements
- :lock: for security fixes
- :construction: for work in progress

## Mathematical Expressions

Simple math expressions can be written inline or in blocks.

The quadratic formula: ax² + bx + c = 0

## Diff Highlighting

```diff
  function add(a, b) {
-   return a + b + 1; // Bug: adding extra 1
+   return a + b;     // Fixed: correct addition
  }
```

## Complex Example

Here's a more complex example showing multiple features together:

### :gear: Configuration Setup

1. **Install dependencies:**
   ```bash
   npm install marked prismjs
   ```

2. **Configure the service:**
   ```typescript
   import { GitHubMarkdownService } from './github-markdown.service';
   
   @Component({
     // Component configuration
   })
   export class MyComponent {
     constructor(private markdown: GitHubMarkdownService) {}
     
     parseContent(content: string): string {
       return this.markdown.parse(content);
     }
   }
   ```

3. **Add styles:**
   ```css
   @import 'app/styles/github-markdown.css';
   @import 'prismjs/themes/prism.css';
   ```

### :white_check_mark: Features Checklist

- [x] Headers with proper spacing
- [x] Code syntax highlighting
- [x] GitHub-style tables  
- [x] Task lists with checkboxes
- [x] Emoji support :smile:
- [x] Blockquotes and alerts
- [x] Proper link handling
- [x] Image responsive display
- [x] List indentation
- [x] Text formatting

---

That's a comprehensive overview of our GitHub-flavored markdown implementation! :rocket: