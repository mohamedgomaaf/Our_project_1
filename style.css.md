# Our_project_1
/* Start Variables */
:root {}

/* End Variables */
/* Start Global Rules */
* {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: "Open Sans", sans-serif;
}

ul {
    list-style: none;
}

a {
    text-decoration: none;
    color: inherit;
}

.container {
    padding-left: 15px;
    padding-right: 15px;
    margin-left: auto;
    margin-right: auto;
}

/* Small */
@media (min-width: 768px) {
    .container {
        width: 750px;
    }
}

/* Medium */
@media (min-width: 992px) {
    .container {
        width: 970px;
    }
}

/* Large */
@media (min-width: 1200px) {
    .container {
        width: 1170px;
    }
}

/* End Global Rules */
/* start header */
.header {
    margin-top: 41px;
}

.header .container {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

@media (max-width: 992px) {
    .header .container {
        flex-direction: column;
        gap: 28px;
    }
}

.header .container ul {
    display: flex;
    gap: 24px;
    flex-wrap: wrap;
}

@media (max-width: 992px) {
    .header .container ul {
        font-size: 13px;
    }
}

.header ul li a:hover:not(.icons a) {
    color: #3cc7c6;
}

.header .container ul .icons {
    display: flex;
}

.header .icons a {
    padding-right: 25px;
}

.header .icons li:not(.not_1):after {
    content: "";
    border-right: #e4e4e6 2px solid;
    margin-right: 21px;
}

/* end header */
/* start text_cart */
.text_cart {
    margin-top: 41px;
    display: flex;
    height: 80px;
    background-color: #f5f5f5;
}

.text_cart .container {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

@media (max-width:767px) {
.text_cart .container {
    flex-direction: column;
     padding: 10px;
    }
}

.text_cart .container ul {
    display: flex;
}

.text_cart .container ul li {
    padding: 0 10px;
}

.text_cart .container a:nth-child(2) {
    border-right: 1px solid black;
}

.text_cart ul a:hover {
    color: #3cc7c6;
}

/* end text_cart */
/* start text_cart */
.text_border {
    margin: 74px 0;
}

.text_border p {
    border: 1px solid #f5f5f5;
    padding: 20px;
}

/*  */
.border .container{
    margin-top: 41px
}
.border .container p{
    border: 2px solid #ececec;;
    height: 3rem;
    display: flex; 
    align-items: center;
    color: #5e5e5e;
    text-shadow: 0 1px 0 #fff;
    border-radius: 4px;
    background-color: #fff;
    padding: 16px 16px 16px 56px;
}
.border .container p a:hover{
    color: #3cc7c6;
}
.title .container h2{
    color: #444444;
    margin-top: 16px;
        
}
.boxform .container form .user{
    display: flex;
    flex-wrap: wrap;
}
form .user .inputbox{
    width:calc(100% /3 - 50px);
}
form .user .inputbox span{
    color: #999999;
}
form .user .inputbox input{
    height: 30px;
    width: 90%;
}

.boxform .container form .select{
    width: 300px;
    margin-bottom: 20px;
}
.boxform .container form .formbli input{
    width: 300px;
    height: 30px;
    margin-bottom: 20px;
}
.boxform .container form .formbli label{
    color: #999999;
}
/* table */
.yourorder{
    line-height: 25px;
    font-size: 20px;
    text-align: center;
    color: #999999;
}
.table-box{
    margin: 50px auto;
}
.table-row{
    display: table;
    width: 80%;
    margin: 10px auto;
    font-family: sans-serif;
    background: transparent;
    padding: 12px 0;
    color: #555;
    font-size: 13px;
    box-shadow: 0 1px 4px 0 rgba(0, 0, 50, 0.3);
}
.table-pro{
    display:table-cell; 
    width: 30%;
    text-align: center;
    padding: 4px 0;
}
.btn{
    width: 90px;
    height: 2rem;
    float: right;
    outline: none;
    border: none;
    background-color: #3cc7c6;
    color: white;
    cursor: pointer;
}
.btn:hover{
    color: #3cc7c6;
    background-color: #e4e4e6;
    border-radius: 5px;
    
}


/* end table */
