# Markdown + CSS

Foo Bar

<style>

#my_id {
    background: #00adff;
    color: #fff;
    padding: 0.5em;
    text-align: center
}

</style>

<p id="my_id"><strong>Blue</strong></p>

<div class="animate_this">DIV</div>

<style>

@keyframes example {
   from {background-color: red;}
   to {background-color: yellow;}
}

div.animate_this {
   width: 100px;
   height: 100px;
   background-color: red;
   animation-name: example;
   animation-duration: 4s;
}

</style>
