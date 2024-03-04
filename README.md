# Milestone-Project-1
<!DOCTYPE HTML>
<HTML lang="en">
  <Head>
    <style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, inital-scale=1.0">
    <Title>Art Block/Home Page</Title>
      </Head>
     <!--the background of the home page will be an art picture-->
  
      body {
          display: flex;
          flex-wrap: wrap;
          background-image: url('img_art_picture.jpg');
          padding: 0 300px;
        }
    <!-- css coding of images that will be displayed on the bottom of the home page. 
        img{
        flex: 1 800px;
        width: 400px;
        height: 400px;
        object-fit: cover;
        }
      <!-- the header 1 will display the title of the home page -->
      <h1> Creative Minds</h1>
  <!-- nav bar css styles -->
      ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
      overflow: hidden;
      background-color:#color;
      }
    li {
      float: center;
      }
    li a {
      display: block;
      color: white;
      text-align: center;
      padding: 400px 400px;
      text-decoration: none;
      }
    li a:hover {
      background-color: #pink;
      }
      </style>
    
  <!-- This where the nav bar will be at the top of the web page that includes css styles -->
       <body>
    <ul>
    <li><a class="active" href="home">home</a></li>
        <li><a href="#about">about</a></li>
        <li><a href="#contact">contact</a></li>
        </ul>

         <!-- home page with images and art content -->
   <img scr="image_1.jpg">
   <img scr="image_2.jpg">
   <img scr="image_3.jpg">
   <img scr="image_4.jpg">

   <p>More Art Content Here</p>
   </body>
      
  
</HTML>
