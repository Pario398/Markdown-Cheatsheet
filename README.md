# Markdown Cheatsheet

Markdown is a lightweight markup language used for formatting text on the web. It's easy to learn and use. Here's a cheatsheet with examples of common Markdown elements:

# Table of contents
- [Text Formatting](#text-formatting)
  - [Headers](#headers)
  - [Emphasis](#emphasis)
  - [Lists](#lists)
- [Links and Images](#links-and-images)
  - [Links](#links)
  - [Images](#images)
- [Block Elements](#block-elements)
  - [Blockquote](#blockquote)
  - [Code Block](#code-block)
  - [Horizontal Rule](#horizontal-rule)
  - [Tables](#tables)
  - [Crossed Words](#crossed-words)
  - [Task List](#task-list)

## Text Formatting

### Headers

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

```Markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
### Emphasis

*Italic text*
**Bold text**
***Bold and italic text***

```Markdown
*Italic text*
**Bold text**
***Bold and italic text***
```

### Lists

#### Unordered List

- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2

```Markdown
- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2
```

#### Ordered List

1. First item
2. Second item
3. Third item

```Markdown
1. First item
2. Second item
3. Third item
```

## Links and Images

### Links

[Link text](https://www.example.com)

```Markdown
[Link text](https://www.example.com)
```

### Images

![Alt text](image.jpg)

```Markdown
![Alt text](image.jpg)
```

## Block Elements

### Blockquote

> This is a blockquote.
>> This is a nested blockquote.
```Markdown
> This is a blockquote.
>> This is a nested blockquote.
```

### Code Block

```python
def greet(name):
    print(f"Hello, {name}!")
```

```
    ```python
    def greet(name):
        print(f"Hello, {name}!")
    ```
```

### Horizontal Rule
---

***

- - - -

```Markdown
    ---

    ***

    - - - -
```
### Tables

#### Adding tables

Header1 | Header2
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

```Markdown
Header1 | Header2
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
```

#### Text aligned table

Left aligned Header | Right aligned Header | Center aligned Header
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell

```Markdown
Left aligned Header | Right aligned Header | Center aligned Header
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell
```
### Crossed words

~~Crossed words.~~

```Markdown
~~Crossed words.~~
```

### Task list

- [x] Task1
- [ ] Task2

```Markdown
- [x] Task1
- [ ] Task2
```
