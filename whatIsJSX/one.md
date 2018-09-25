<h1 style = 'text-align: center; color: #020557'>
    What is JSX
</h1>

<section
    style = 'text-align: center; background-color: #D5D8DC'
>
    <h2 
        style =  'text-align: center; color: #196F3D'
    >
        NOTE
    </h2>
    <p>In order to reap the benefits of ES6 today, we have to do a few things to get it to work in as many browsers as we can:</p>
    <ol>
        <li>
            We have to transpile our code.
        </li>
        <li>
            We have to include a polyfill.
        </li>
    </ol>
</section>

<h2
    style =  'text-align: center; color: #196F3D'
>
    JSX
</h2>

<p>
    JSX produces React 'elements'. JSX, is a react extension that allows us to write javascript that looks like HTML. The JSX is translated to reqular JavaScript at runtime. While JSX looks like HTML, it is actually just a terser way to write a React.createElement() declaration.
</p>

<p>
    When a component renders, it outputs a tree of React elements or a virtual representation of the HTML elements this component outputs. React will then determine what changes to make to the actual DOM based on this React element representation.
</p>

<p>
    Because JSX is JavaScript, we can't use JavaScript reserved words. This includes words like class and for.
</p>

<p>
    You can put any valid JavaScript expression inside the curly braces in JSX.
</p>

<h2
    style =  'text-align: center; color: #196F3D'
>
    Specifying Attributes whith JSX
</h2>

<ol>
    <li>
            You may use quotes to specify string literals as attributes
    </li>
    <li>
         You may also use curly braces to embed a JavaScript expression in an attribute
    </li>
</ol>

<h1
    style = 'text-align: center; color: red'
>
    JSX Prevents Injection Attacks, It is safe to embed user input in JSX
</h1>