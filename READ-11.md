# read 11

## EJS PARTIALS

is a way to weite a code and we use it when  you want to reuse the same HTML across multiple views. Think of partials as functions, they make large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in. Instead, you define that reusable bundle of code in a file andinclude it wherever you need it.

JavaScript or non-HTML syntax you include in your templates is always surrounded by <% %> delimiters 

Including a partial in EJS is quite straightforward. You use <%- include( PARTIAL_FILE ) %> where the partial file is relative to the template you use it in.

# thank you