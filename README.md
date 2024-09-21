<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet"
            href="website.css">
    </head>
    <head>
        <script language ="javascript">

        </script>
    </head>
    <body>
        <style>
            body{
                font-family: system-ui;
                background-color: #45474B;
                text-align: center;
            }
            .image {
                width: 512px;
                height: 288px;
            }
            h1{
               color: #F5F7F8; 
            }
            h2{
               color: #F5F7F8; 
            }
            h3{
               color: #F5F7F8; 
            }
            .lubes{
                color: #F5F7F8;
            }
            .setup{
                color: #F5F7F8;
            }

        </style>
        
        <img src="https://i.ytimg.com/vi/4caN6ks_cR0/maxresdefault.jpg" class="image">
        
        <h1>
           CubeFlow
        </h1>
        <h2>
            Your best cubes setup by us, for you to use
        </h2>
        <h3>
            Pick a cube for us to set up
        </h3>
        <select name="cube_broad">
            <option value="2x2">2x2</option>
            <option value="3x3">3x3</option>
            <option value="4x4">4x4</option>
            <option value="5x5">5x5</option>
            <option value="6x6">6x6</option>
            <option value="7x7">7x7</option>
            <option value="Pyraminx">Pyraminx</option>
            <option value="SQ-1">Square1</option>
            <option value="Megaminx">Megaminx</option>
            <option value="yourown">Your Own</option>
        </select>
        <select name="cube_narrow">
            <option value="M2">Mgc 2</option>
            <option value="M3">Mgc 3</option>
            <option value="M4">Mgc 4</option>
            <option value="M5">Mgc 5</option>
            <option value="M6">Mgc 6</option>
            <option value="M7">Mgc 7</option>
            <option value="MSQ">Mgc SQ1</option>
            <option value="My2E">Moyu Rs2M Evolution</option>
            <option value="My32">Moyu Rs3M 2020</option>
            <option value="My3Sv5">Moyu Rs3M Super v5</option>
            <option value="MyWRMv9">Moyu WRM v9</option>
            <option value="MyWRMv10">Moyu WRM v10</option>
            <option value="My4v7">Moyu 4x4 v7</option>
            <option value="My5v5">Moyu Aoshuang v5</option>
            <option value="My6WRM">Moyu Aoshi WRM</option>
            <option value="My7WRM">Moyu Aofu WRM</option>
            <option value="Mei7v2M">Meilong 7x7 v2 M</option>
            <option value="G251P">Gan 251 Pro</option>
            <option value="G312M">Gan 12 Maglev</option>
            <option value="G5">Gan 5x5</option>
            <option value="Tv4">Tornado v4</option>
            <option value="MyWP">Moyu Weilong Pyraminx</option>
            <option value="YLMP">Yuxin Little Magic Pyraminx</option>
            <option value="XVv2">X-Man Volt V2</option>
            <option value="MMv2">YJ Yuhu v2</option>
            <option value="DM">Dayan Megaminx</option>
        </select>
        <h3>
            pick which lubes you would like
        </h3>
        <p>
            <div class="lubes">
                <input type="checkbox" name="lube" class="lunar"/>Lunar (Fast)<br>
                <input type="checkbox" name="lube" class="stardust"/>Stardust (Very Fast)<br>
                <input type="checkbox" name="lube" class="martian"/>Martian (Speedy)<br>
                <input type="checkbox" name="lube" class="comet"/>Comet (Speedy)<br>
                <input type="checkbox" name="lube" class="cosmos"/>Cosmos (Very Slow)<br>
                <input type="checkbox" name="lube" class="nebula"/>Nebula (Slow)<br>
                <input type="checkbox" name="lube" class="galaxy"/>Galaxy (Slow)<br>
                <input type="checkbox" name="lube" class="vortex"/>Vortex (Fast)<br>
                <input type="checkbox" name="lube" class="dnm37"/>Dnm37 (Very Fast)<br>
                <input type="checkbox" name="lube" class="mystic"/>Mystic (Fast)<br>
                <input type="checkbox" name="lube" class="a_dignitas"/>Angstrom Dignitas (Slow)<br>
                <input type="checkbox" name="lube" class="a_gravitas"/>Angstrom Gravitas (Very Slow)<br>
                <input type="checkbox" name="lube" class="silk"/>Silk (Slow)<br>
                <input type="checkbox" name="lube" class="speedy"/>Speedy (Fast)<br>
                <input type="checkbox" name="lube" class="w5"/>Weight 5 (Slow)<br>
                <input type="checkbox" name="lube" class="w1"/>Weight 1 (Speedy)<br>
            </div>
        <h3>
           Or find one of our setups 
        </h3>
        <div class="setup">
        <input type="radio" name="setup" class="jperm"/>Jperm (Weight1+Lunar)<br>
            <br>
        <input type="radio" name="setup" class="cubehead"/>CubeHead (Weight5+Angstrom Dignitas+Mystic+Dnm37)<br>
            <br>
        <input type="radio" name="setup" class="angstrom"/>Angstrom (Vortex+Angstrom Dignitas+Angstrom Gravitas+Dnm37)<br>
            <br>
        <input type="radio" name="setup" class="mystic"/>Mystic (Weight5+Mystic+Dnm37)<br>
            <br>
        <input type="radio" name="setup" class="cosmic"/>Cosmic (Weight5+Nebula+Martian)<br>
            <br>
        <input type="radio" name="setup" class="supernova"/>Supernova (Lunar+Stardust+Vortex)<br>
            <br>
        </div>
            <h3>
            Address
        </h3>
            <input type="text" name="address" class="address"/><br>
        <br>
        <div class="lube_image">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT4fwOVnFl1jVqXoII9sUtUfb7m5fVi2tbSIg&s">
            </div>
        </p>
        </body>
</html>
