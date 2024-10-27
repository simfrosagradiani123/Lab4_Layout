    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout Sederhana</title>
    <style>
        /* Import Google Fonts */
        @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600;700;800&display=swap');

        /* Reset CSS */
        * {
            margin: 0;
            padding: 0;
        }

        body {
            line-height: 1;
            font-size: 100%;
            font-family: 'Open Sans', sans-serif;
            color: #5a5a5a;
        }

        #container {
            width: 980px;
            margin: 0 auto;
            box-shadow: 0 0 1em #cccccc;
        }

        /* Header */
        header {
            padding: 20px;
        }
        header h1 {
            margin: 20px 10px;
            color: #b5b5b5;
        }

        /* Navigation */
        nav {
            display: block;
            background-color: #1f5faa;
        }
        nav a {
            padding: 15px 30px;
            display: inline-block;
            color: #ffffff;
            font-size: 14px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a.active,
        nav a:hover {
            background-color: #2b83ea;
        }

        /* Hero Panel */
        #hero {
            background-color: #e4e4e5;
            padding: 50px 20px;
            margin-bottom: 20px;
        }
        #hero h1 {
            margin-bottom: 20px;
            font-size: 35px;
        }
        #hero p {
            margin-bottom: 20px;
            font-size: 18px;
            line-height: 25px;
        }

        /* Wrapper Layout */
        #wrapper {
            margin: 0;
        }
        #main {
            float: left;
            width: 640px;
            padding: 20px;
        }
        #sidebar {
            float: left;
            width: 260px;
            padding: 20px;
        }

        /* Sidebar Widget */
        .widget-box {
            border: 1px solid #eee;
            margin-bottom: 20px;
        }
        .widget-box .title {
            padding: 10px 16px;
            background-color: #428bca;
            color: #fff;
        }
        .widget-box ul {
            list-style-type: none;
        }
        .widget-box li {
            border-bottom: 1px solid #eee;
        }
        .widget-box li a {
            padding: 10px 16px;
            color: #333;
            display: block;
            text-decoration: none;
        }
        .widget-box li:hover a {
            background-color: #eee;
        }
        .widget-box p {
            padding: 15px;
            line-height: 25px;
        }

        /* Footer */
        footer {
            clear: both;
            background-color: #1d1d1d;
            padding: 20px;
            color: #eee;
        }

        /* Main Content Boxes */
        .box {
            display: block;
            float: left;
            width: 33.333%;
            box-sizing: border-box;
            padding: 0 10px;
            text-align: center;
        }
        .box h3 {
            margin: 15px 0;
        }
        .box p {
            line-height: 20px;
            font-size: 14px;
            margin-bottom: 15px;
        }
        .image-circle {
            border-radius: 50%;
        }

        /* Row */
        .row {
            margin: 0 -10px;
            box-sizing: border-box;
        }
        .row:after {
            content: '';
            display: table;
            clear: both;
        }

        /* Divider */
        .divider {
            border: 0;
            border-top: 1px solid #eeeeee;
            margin: 40px 0;
        }

        /* Entry */
        .entry {
            margin: 15px 0;
        }
        .entry h2 {
            margin-bottom: 20px;
        }
        .entry p {
            line-height: 25px;
        }
        .entry img {
            float: left;
            border-radius: 5px;
            margin-right: 15px;
        }
        .entry .right-img {
            float: right;
        }
    </style>
    </head>
    <body>
    <div id="container">
        <header>
            <h1>Layout Sederhana</h1>
        </header>
![praktikum4 gambar Tampilan Kerangka Layout](https://github.com/user-attachments/assets/b48e96c8-78f6-490d-882d-140de56f9460)
        
        <nav>
            <a href="home.html" class="active">Home</a>
            <a href="artikel.html">Artikel</a>
            <a href="about.html">About</a>
            <a href="kontak.html">Kontak</a>
        </nav>
![gambar](https://github.com/user-attachments/assets/742c02b2-8d90-40cd-b380-9e1a83626a61)

        <section id="hero">
            <h1>Hello World!</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi 
            porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
            <a href="home.html" class="btn btn-large">Learn more &raquo;</a>
        </section>
![pratikum4 gambar tampilan hero panel](https://github.com/user-attachments/assets/2db17a7f-38cc-4bdc-84d3-2085c11246b2)

        <section id="wrapper">
            <section id="main">
                <div class="row">
                    <div class="box">
                        <img src="https://dummyimage.com/120/db7d25/fff.png" alt="" class="image-circle">
                        <h3>Heading</h3>
                        <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                        <a href="#" class="btn btn-default">View detail</a>
                    </div>
                    <div class="box">
                        <img src="https://dummyimage.com/120/3e73e6/fff.png" alt="" class="image-circle">
                        <h3>Heading</h3>
                        <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                        <a href="#" class="btn btn-default">View detail</a>
                    </div>
                    <div class="box">
                        <img src="https://dummyimage.com/120/71e6d4/fff.png" alt="" class="image-circle">
                        <h3>Heading</h3>
                        <p>Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                        <a href="#" class="btn btn-default">View detail</a>
                    </div>
                </div>
![pratikum4](https://github.com/user-attachments/assets/f0ebda3e-b7f4-4edf-8edc-dec3324f69b0)

                <hr class="divider" />

                <article class="entry">
                    <h2>First featurette heading.</h2>
                    <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
                </article>

                <hr class="divider" />

                <article class="entry">
                    <h2>Second featurette heading.</h2>
                    <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="" class="right-img">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
                </article>
            </section>
![praktikum4 tampilan artikel](https://github.com/user-attachments/assets/29519b01-831a-44e6-bb58-4df5d3289044)

            <aside id="sidebar">
                <div class="widget-box">
                    <h3 class="title">Widget Header</h3>
                    <ul>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                    </ul>
                </div>
                <div class="widget-box">
                    <h3 class="title">Widget Text</h3>
                    <p>Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est 
                    nunc, nec pretium nunc pretium ac.</p>
                </div>
            </aside>
        </section>
![praktikum 4 gambar Tampilan Sidebar Widget](https://github.com/user-attachments/assets/551c6f07-0951-4c4f-8f45-de04232aaedb)

        <footer>
            <p>&copy; 2024- Universitas Pelita Bangsa</p>
        </footer>
    </div>
    </body>
    </html>
![screenshot](https://github.com/user-attachments/assets/510c6b54-43d3-4bec-8406-d31f62507963)

