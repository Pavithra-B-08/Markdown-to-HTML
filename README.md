# Markdown-to-HTML
This project aims to convert some basic markdown to html using lex and yacc integrated with C

This project presents a streamlined approach to converting Markdown to HTML using Lex and Yacc, combined 
with a default CSS styling file. The goal is to mimic the process commonly used by websites to manage and 
display Markdown content consistently. Using .lex and .yacc files, the Markdown syntax is parsed into HTML 
elements, while a style.css file provides cohesive, readable styling for key HTML elements such as headings, 
paragraphs, lists, blockquotes, and code blocks. This ensures that converted Markdown content is displayed in a 
structured and visually appealing manner, with minimal need for additional styling adjustments. 

## LEX AND YACC
- **Lex** is a lexical analyzer generator that processes Markdown input, transforming it into tokens. These tokens 
represent key Markdown elements like headers, lists, links, images, and other structural components. For 
instance, a line starting with # is tokenized by Lex as a “header” component, while * or - at the beginning of a 
line is tokenized as part of a list item. Lex identifies these Markdown syntax elements, creating tokens that the 
parser can interpret for conversion to HTML. 
- **Yacc** (Yet Another Compiler Compiler) is a parser generator that interprets the tokens produced by Lex 
according to predefined grammar rules for HTML structure. Yacc takes this stream of tokens and organizes 
them into a syntax tree based on HTML’s structural requirements, enabling the generator to create valid HTML 
output.


By combining Lex and Yacc in this project, we establish a streamlined process for translating Markdown syntax 
into syntactically correct HTML, with integrated CSS for styling.
