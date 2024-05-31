<!-- This is comment -->

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

## PARAGRAPH
<!-- just the text -->
<!-- next line - 2 spaces,br tag -->
This is line 1  
This is line 2</br>
This is line 3  
This is line 4

## LISTS

### Unordered Lists
<!-- we can also use +,- instead of * -->
* List 1  
* List 2  
* List 3

### Ordered Lists
<!-- It gives order of items on it's own  -->
1. Item 1  
1. Item 2  
1. Item 3

### Unordered Nested Lists
<!-- UnorderedList : 2 space indentation -->
* List 1
  * Nested Item 1  
  * Nested Item 2  
* List 2
  1. Nested Item 1  
  2. Nested Item 2
* List 3

### Ordered Nested Lists
<!-- OrderedList : 3 space indentation -->
1. Item 1
   * Nested Item 1  
   * Nested Item 2
2. Item 2
   1. Nested Item 1  
   2. Nested Item 2
3. Item 3

## Backticks  
<!-- inline text is written as it is even with tags -->
`<p>Heading</p>`  
`<h1>Heading</h1>`  
`##heading1`

## Links

[google](https://google.com "text on hover")  
[js mdn](https://developer.mozilla.org/en-US/docs/Learn/JavaScript "js guide")

## Images

![Javascript image](./javascript.png "js")  

## Clickable Image

[![Javascript image](./javascript.png "js")](https://developer.mozilla.org/en-US/docs/Learn/JavaScript "js guide")  

## Block Quote

>This is Blockquote  
>This is Blockquote  
>This is Blockquote  
>
> 1. Item 1
> 2. Item 2
>
>> This is nested block quote
>>
>> * Item 1
>> * Item 2
>>
>Hey there again

## Table
<!-- create manually -->
|First Name | Last Name |  
| :-------: | :-------: |  
|  Anushka  | Murade    |
|  Adiraj   | Murade    |
|  Ajit     | Murade    |

<!-- shortcut : search "markdown table generator" on google -->
[Markdown Table Generator](https://www.tablesgenerator.com/markdown_tables "table generator")

| First Name | Last Name |
|:----------:|:---------:|
|  Anushka   |   Murade  |
|   Adiraj   |   Murade  |

## Escape characters using \

\# Hey there
\- List Item

## Code

```javascript
const add=(a,b)=>{
    return (a+b);
}
console.log(add(4,5));
 ```

## Commands used to convert markdown to html

1.npm install -g markdown-it  
2.markdown-it filename.md -o filename.html  
or  
markdown-it filename.md
then Copy the html code from terminal n paste it into the new html file  
