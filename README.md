# CSS3 Transitions

CSS3 transitions allow you to transition an element from one state to another. 
 

div {
    width: 100px;
    height: 100px;
    background: red;
    -webkit-transition: width 2s; /* Safari */
    transition: width 2s;
    
    /* transition: all 2.0s ease; */ 


   /* add a transform 
    -webkit-transition: width 2s, -webkit-transform 2s; /* Safari */
    transition: width 2s, transform 2x;
  */ 

}

div:hover {
    width: 300px;
    -webkit-transform: rotate(180deg); /* Safari */
    transform: rotate(180deg);
}

 

 
There are two parts to this example :  

1. adding a transition element to the actual div itself,  and
2. adding an :hover selector to trigger the actual effect ( the 'destination' ) . 

 





