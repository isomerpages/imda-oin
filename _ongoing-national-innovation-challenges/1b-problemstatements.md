---
layout: leftnav-page-content
title: TCC
permalink: /nic-test/
breadcrumb: problem statements / test
collection_name: ongoing-national-innovation-challenges
second_nav_title: Problem Statements
---
<style>

.wrapper{
  margin: auto;
  width: 400px;
}

ul{
  list-style: none;
  margin: 0;
  padding: 0;
}
label:hover{
  background-color: darken(#E7131A, 10%);
  
}
label{
  display: block;
  cursor: pointer;
  padding: 10px;
  border: 1px solid #fff;
  border-bottom: none;
  background: #E7131A
  color:#ffffff;
}


label.last{
  border-bottom: 1px solid #fff;
}

ul ul li{
  list-style:none;
  padding: 10px;
  background: #ffffff;
}


input[type="checkbox"]{
  position: absolute;
  left: -9999px;
}

input[type="checkbox"] ~ ul{
  height: 0;
  transform: scaleY(0);
}

input[type="checkbox"]:checked ~ ul{
  height: 100%;
  transform-origin: top;
  transition: transform .2s ease-out;
  transform: scaleY(1); 
}

input[type="checkbox"]:checked + label{
  background: #E7131A;
  border-bottom: 1px solid #fff;
}




</style>

<div class="wrapper">
<ul>
  <li>
    <input type="checkbox" id="list-item-1">
    <label for="list-item-1" class="first">Automated Inspection of Shipping Containers at Container Depots</label>
    <ul>
      <li>Slabo</li>
      <li>Droid Serif</li>
      <li>Roboto Serif</li>
      <li>Lora</li>
      <li>Meriweather</li>
    </ul>
  </li>
  <li>
    <input type="checkbox" id="list-item-2">
    <label for="list-item-2">Seeking Collaborators to Disrupt Global Trade Financing via Blockchain</label>
    <ul>
      <li>Company Name</li>
      <li>Description:</li>
    </ul>
   </li>
  
  <li>
    <input type="checkbox" id="list-item-3">
    <label for="list-item-3" class="last">Third PS</label>
    <ul>
      <li>Inconsolata</li>
      <li>Source Code Pro</li>
      <li>Droid Sans Mono</li>
      <li>Ubuntu Mono</li>
      <li>Cousine</li>
    </ul>
  </li>
  
</ul>
</div>
