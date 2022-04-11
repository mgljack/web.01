*{
                        
      list-style: none;
      text-decoration: none;
      border-collapse: collapse;
      margin: 0px;
      padding: 0px;
      color: #000;
}

h1{
      font-size:48px;
      font-weight:100;
}
.contents1{
      font-size: 20px;
      font-weight:lighter;
}

.intro_bg{
      background-image:url("jack/intro.png");
      width: 100%;
      height: 718px;
}

.header{
      display:flex;
      width:1280px;
      margin:auto;
      height:86px;
}
.searchArea{
      width:300px;
      height:40px;
      background:rgba(0,0,0,5);
      border-radius: 5px;
      margin-top:24px;
}
.searchArea > form > input{
      border:none;
      width:250px;
      height:40px;
      background:rgba(0,0,0,0);
      color:#fff;
      padding-left:10px;
}
.searchArea > form > span{
      width:50px;
      color:#fff;
      font-weight:bold;
      cursor:pointer;
}
.nav{
      display:flex;
      justify-content: flex-end;
      line-height: 86px;
      width:calc(1280px - 300px);
     
}


.nav > li{
      margin-left:84px;
}

.nav > li > a{
color: white;
}

.amount{
      position:relative;
      top:-66px;
      display:flex;
      width:1280px;
      background:red;
      margin:auto;
}
.amount > li{
      flex:1;
      height:132px;
      background:skyblue;
}
.amount > li > div{
      text-align:center;
      background:green;
      margin-top:37px;
      height:57px;
}

.amount > li > div:not(:last-child) > div{
      border-right:1px solid gray;
}

.intro_text{
      width:100%;
      margin:231px auto 231px auto;
      text-align:center; /*dadada8*/

}

.intro_text > h1,
.intro_text > h4{
      color:#fff;

}
