<template>
    <nav>
        <ul class="bg-gradient-to-b from-blue-400 to-green-500">
            <li><a href="#">Home</a></li>
            <li><a href="#">Gallery</a></li>
            <li><a href="#">Contact Us</a></li>
        </ul>
    </nav>

    <div class="container mx-auto px-4">
        <div class="box-border h-32 w-100 p-2 bg-gradient-to-r from-blue-400 via-navy-500 to-green-500 ...">
            <h1 class="font-series text-3xl font-semibold tracking-widest ...">Ini Halaman Awal</h1>
        </div>
    </div>
</template>

<style>
 	* {
 		margin:0; 
 		padding:0;
 	}
 
	nav {
		margin:auto;
		text-align: center;
		width: 100%;
		font-family: arial;
	} 
	
	nav ul {
		background:#37988e;
		padding: 0 20px;
		list-style: none;
		position: relative;
		display: inline-table;
		width: 100%;
	 }

	nav ul li{
		float:left;
	}

	nav ul li:hover{
		background:#d68d9a;
	}

	nav ul li:hover a{
	 	color:#000;
	}

	nav ul li a{
	 	display: block;
	 	padding: 25px;
	 	color: #fff;
	 	text-decoration: none;
	}
	</style>