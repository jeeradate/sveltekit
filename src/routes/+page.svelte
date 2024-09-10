<!DOCTYPE html>

	<body>
		<div class="container">
            <div class="box" id="box1">1</div>
            <div class="box" id="box2">2</div>
            <div class="box" id="box3">3</div>
            <div class="box" id="box4">4</div>
            <div class="box" id="box1">5</div>
            <div class="box" id="box2">6</div>
            <div class="box" id="box3">7</div>
            <div class="box" id="box4">8</div>
        </div>
        
	</body>


<style>
    .container {
        display: flex;
        border-style: dashed;
        justify-content: space-evenly;
        height: 50vh;
        align-items: center;
        flex-wrap: wrap;
    }
    .box {
        width: 150px;
        height: 150px;
        font-size: 8em;
        color:white;
        text-align: center;
        border-radius: 15px;
    }
    #box1{
        background-color: rgb(219, 24, 24);

    }

    #box2{
        background-color: rgb(210, 223, 34);

    }
   
    #box3{
        background-color: rgb(15, 217, 83);

    }

    #box4{
        background-color: rgb(24, 65, 216);

    }

</style>
