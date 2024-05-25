# HTMPL - Hypertext Markup Programming Language

Yes, you are reading that right, HTML as programming language.

Why? I just wanted to learn **Rust**, and as a web dev, HTML is close to my heart. So as you do, I decided to write a **compiler**.
*And also you can brag to your friends, that you program in HTML.*

_________________

## Specification

We need to declare a assign variables.
`<p id='x'>42</p>`
And just like this we have created a variable `x` and assigned it `42` as it's value.
But you could also just declare a variable `<p id='y' />` and assign it later `<p id="y">"Hello world"</p>`.

For printing to stdout use `<output> </output>` tags.
Example:
`<output>Life is meaningless, unless <p id='x' /></output>`
This will print out:
> Life is meaningless, unless 42.

The main function is written inside of `<body>` tag, and just like in HTML, it has to be closed `</body>`.


