<script>
</script>


<template>
    <div id="jumbotron-container">
        <div id="jumbotron-header">
            <span>Jumbotron Example</span>
            <hr>
        </div>
        <div id="jumbotron-inner-box-1">
            <h2>Custom jumbotron component</h2>
            <p>Using a series of utilities, you can create this jumbotron, just like the one in previous versions of
                Bootstrap.
                Check out the examples below for how you can remix and restyle it to your liking.</p>
            <BUtton>Example</BUtton>
        </div>
        <div id="jumbotron-lower-box">
            <div id="jumbotron-container-void" class="box-left">
                <h2>Custom jumbotron component</h2>
                <p>Swap the background-color utility and add a `.text-*` color utility to mix up the jumbotron look. Then,
                    mix and match with additional component themes and more.</p>
                <div class="BUttonAlternative-1">Example</div>

            </div>
            <div class="box-right" id="jumbotron-inner-box-2">
                <h2>Add borders</h2>
                <p>Or, keep it light and add a border for some added definition to the boundaries of your content. Be sure
                    to look under the hood at the source HTML here as we've adjusted the alignment and sizing of both
                    column's content for equal-height.</p>
                <div class="BUttonAlternative-2">Example</div>
            </div>
        </div>
        <hr>
        <span>© 2024</span>
    </div>
</template>

<style>
span {
    font-size: 1.3rem;
    font-weight: bold;
    color: #ffffff;

}

h2 {
    font-size: 2rem;
    font-weight: bold;
}

p {
    font-size: 1.2rem;
    font-weight: bold;
}

#jumbotron-container {
    margin: auto;
}

#jumbotron-inner-box-1 {
    background-color: #2b3035;
    padding: 4rem;
    border-radius: 0.3rem;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

#jumbotron-inner-box-2 {
    border: 1px solid #6d747d;
    background-color: #2b3035;
    padding: 2rem;
    border-radius: 0.3rem;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

#jumbotron-container-void {
    padding: 2rem;
}

#jumbotron-lower-box {
    display: flex;
    margin-top: 2rem;
}



.box-left {
    width: 50%;

    margin-right: 1rem;
}

.box-right {
    width: 50%;
    margin-left: 1rem;

}

hr {
    border: 0;
    height: 1px;
    background: #333;
    margin: 1rem 0;
}

.BUttonAlternative-1 {
    border: 1px solid #4CAF50;
    color: #4CAF50;
    padding: 12px 22px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 1.2rem;
    font-weight: bold;
    margin: 4px 2px;
    cursor: pointer;
    border-radius: 0.4rem;
}

.BUttonAlternative-2 {
    border: 1px solid #6d747d;
    color: #6d747d;
    padding: 12px 22px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 1.2rem;
    font-weight: bold;
    margin: 4px 2px;
    cursor: pointer;
    border-radius: 0.4rem;
}
</style>