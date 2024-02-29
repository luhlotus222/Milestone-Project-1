# Milestone-Project-1
<!DOCTYPE HTML>
<HTML>
  <Head>
    <Style>
    <Title>Art Block/Home Page</Title>
     <!--the background of the home page will be an art picture-->
      body {
          display: flex;
          flex-wrap: wrap;
          background-image: url('img_art_picture.jpg');
          padding: 0 300px;
        }
        img{
        flex: 1 800px;
        width: 400px;
        height: 400px;
        object-fit: cover;
        }
      <!-- the header 1 will display the title of the home page -->
      <h1> Start Your Creative Art Path </h1>
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
      padding: #px #px;
      text-decoration: none;
      }
    li a:hover {
      background-color: #color;
      }
      </style>
  </Head>
  <!-- This where the nav bar will be that includes css styles -->
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
