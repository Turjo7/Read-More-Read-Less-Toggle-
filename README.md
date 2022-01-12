# Read-More-Read-Less-Toggle-
Read More Read Less Toggle


/** Read more toggle **/

body:not(.elementor-editor-active) .readmoretoggle .elementor-tab-title.elementor-active{
display: block !important;
}

.readmoretoggle .elementor-toggle .elementor-tab-title {
display: flex;
justify-content: center;
}

/* button styling below */
.readmoretoggle .elementor-tab-title.elementor-active::before, .elementor-tab-title a{
display:inline-block;
padding:0.4em 1.6em;
margin:0.14em 0 ;
border:0.16em solid rgba(0,0,0,0);
border-radius:2em;
font-weight:300;
color:rgba(255,255,255,0.9); /* button text color */
text-align:center;
background-color: rgba(23,84,62,.71); /* button color */
transition: all 0.34s ease;
}

/* hover button styling */
.readmoretoggle .elementor-tab-title.elementor-active:hover::before, .elementor-tab-title a:hover{
color:rgba(255,255,255,1); /* change color of text when hovering */
/*transform: scale(1.03); /* delete to remove the zoom in effect */
}

.readmoretoggle .elementor-tab-title.elementor-active::before {
content: 'Close';
font-family:rubik;
font-weight: 400;
font-size: 16px;
color: #FFFFFF;
}

.readmoretoggle .elementor-toggle-item {
display: -webkit-box;
display: -ms-flexbox;
display: flex;
flex-direction: column-reverse;
align-items: center;
}

.readmoretoggle .elementor-tab-title.elementor-active a{
display: none;
}
