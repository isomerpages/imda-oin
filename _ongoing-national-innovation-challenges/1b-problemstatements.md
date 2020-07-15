---
layout: leftnav-page-content
title: National Innovation Challenge
permalink: /nic-jtc-innovation-challenge-2020/
breadcrumb: National Innovation Challenges / JTC Innovation Challenge
collection_name: ongoing-national-innovation-challenges
second_nav_title: Ongoing Challenges
---
#### Trade & Connectivity Challenge 2020
<style>
.wrapper{
  margin: auto;
  width: 400px;
  color:#ffffff;
}

ul{
  list-style-type: none;
  margin: 0;
  padding: 0;
}


label{
  display: block;
  cursor: pointer;
  padding: 10px;
  border: 1px solid #fff;
  border-bottom: none;
  background: #E7131A
}


label.last{
  border-bottom: 1px solid #fff;
}

ul ul li{
  list-style-type: none;
  padding: 10px;
  color:#000000;
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
  border: 1px solid #fff;
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
    <label for="list-item-1" class="first">Problem Statement 1</label>
    <ul>
      <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</li>
    </ul>
  </li>
    <li>
    <input type="checkbox" id="list-item-2">
    <label for="list-item-2">Problem statement 2</label>
    <ul>
      <li>Open Sans</li>
      <li>Roboto</li>
      <li>Lato</li>
      <li>Stabo</li>
      <li>Oswald</li>
    </ul>
  </li>
  <li>
    <input type="checkbox" id="list-item-3">
    <label for="list-item-3" class="last">Problem statement 3</label>
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
