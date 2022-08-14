.bg-image {
  background-image: url("pawel-czerwinski-yXIKZ5PMqn4-unsplash.jpg");
  filter: blur(8px);
  -webkit-filter: blur(8px);
  height:100%;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

body, html {
  background-image: url("pawel-czerwinski-yXIKZ5PMqn4-unsplash.jpg");
  height: 100%;
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

/* navbar */
.topnav {
  overflow: hidden;
  list-style-type: none;
  height: 60px;
  background-color: #333;
}

.logo-image{
  width: 46px;
  height: 46px;
  overflow: hidden;
  margin-top: -6px;
}

.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #003d27;
  color: white;
}

.topnav a.active {
  background-color: #04AA6D;
  color: white;
}

.topnav-right {
  color: #f2f2f2;
  text-align: center;
  padding: 5px 16px;
  text-decoration: none;
  font-size: 17px;
  float: right;
}

/* introduction background image */
.bgimage {
  height:100vh;
  background: url('pawel-czerwinski-yXIKZ5PMqn4-unsplash.jpg');
  background-size:cover;
  position:relative;
}

.intro_title {
  font-size: 4.5rem;
}
.intro_desc {
  font-size: 2rem;
}
.intro-text {
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
}

/* About Section */
.column-2 {
  float: left;
  width: 35%;
  padding: 40px;
  padding-left:60px;
  padding-right: 60px;
  height: 475px;
  margin:30px;
  margin-right:30px;
  margin-bottom: 50px;
  background-color: #00fe48;
  line-height:2.5;
}

.large-profile {
  background: url("lorenzesalas.png");
  background-size: cover;
  background-position: center;
}

/* Education Section */
.column-3 {
  float: right;
  width: 35%;
  padding: 40px;
  padding-left:60px;
  padding-right: 60px;
  height: 475px;
  margin:30px;
  margin-right:30px;
  margin-bottom: 50px;
  background-color: #11fe00c7;
  line-height:2.5;
}

/* Footer Section */

.footer-content-right {
    position: relative;
    padding-right:60px;
    margin-top:40px;
    float:right;
  }
  .icon-style {
    height:40px;
    margin-left:20px;
    margin-top:5px;
  }

  .icon-style:hover {
    background-color:rgb(47, 203, 0);
    padding:5px;
  }
