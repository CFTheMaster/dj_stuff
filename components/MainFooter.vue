<template>
    <footer class="footer">
      <div class="footer__addr">
        <h1 class="footer__logo">computerfreaker</h1>
      </div>
      <ul class="footer__nav">
        <li class="nav__item">
          <ul class="nav__ul">
            <li>
              <router-link :to="{ name: 'index' }">Home</router-link>
            </li>
            <li>
              <router-link :to="{ name: 'about' }">About</router-link>
            </li>
            <li>
              <router-link :to="{ name: 'genres' }">Genres</router-link>
            </li>
          </ul>
        </li>
      </ul>
      <ul class="footer__nav">
        <li class="nav__item">
          <ul class="nav__ul">
            <li>
              <a href="https://computerfreaker.com">Main Page</a>
            </li>
            <li>
              <a href="https://github.com/CFTheMaster">Other Projects (Not Music Related)</a>
            </li>
          </ul>
        </li>
      </ul>
  
      <div class="legal">
        <p>&copy; 2024 computerfreaker. All rights reserved.</p>
  
        <div class="legal__links">
          <span>Made with <span class="heart">♥</span> from computerfreaker</span>
        </div>
      </div>
    </footer>
  </template>
  
  <style>
  .footer {
    display: flex;
    flex-flow: wrap;
    padding: 30px 30px 20px 30px;
    color: #2f2f2f;
    background-color: #6600cc;
    border-top: 1px solid #e5e5e5;
  }
  .footer > * {
    flex: 1 100%;
  }
  
  .footer__addr {
    margin-right: 1.25em;
    margin-bottom: 2em;
    color: #fff;
  }
  
  .footer__logo {
    font-family: 'Pacifico', cursive;
    font-weight: 400;
    text-transform: lowercase;
    font-size: 1.5rem;
  }
  
  .footer__addr h2 {
    margin-top: 1.3em;
    font-size: 15px;
    font-weight: 400;
  }
  
  .nav__title {
    font-weight: 400;
    font-size: 15px;
  }
  
  .footer address {
    font-style: normal;
    color: #999;
  }
  
  .footer__btn {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 36px;
    max-width: max-content;
    background-color: rgb(33, 33, 33, 0.07);
    border-radius: 100px;
    color: #2f2f2f;
    line-height: 0;
    margin: 0.6em 0;
    font-size: 1rem;
    padding: 0 1.3em;
  }
  
  .footer ul {
    list-style: none;
    padding-left: 0;
  }
  
  .footer li {
    line-height: 2em;
  }
  
  .footer a {
    text-decoration: none;
  }
  
  .footer__nav {
    display: flex;
    flex-flow: row wrap;
  }
  
  .footer__nav > * {
    flex: 1 50%;
    margin-right: 1.25em;
  }
  
  .nav__ul a {
    color: #999;
  }
  
  .nav__ul--extra {
    column-count: 2;
    column-gap: 1.25em;
  }
  
  .legal {
    display: flex;
    flex-wrap: wrap;
    color: #999;
  }
  
  .legal__links {
    display: flex;
    align-items: center;
  }
  
  .heart {
    color: #2f2f2f;
  }
  
  @media screen and (min-width: 24.375em) {
    .legal .legal__links {
      margin-left: auto;
    }
  }
  
  @media screen and (min-width: 40.375em) {
    .footer__nav > * {
      flex: 1;
    }
  
    .nav__item--extra {
      flex-grow: 2;
    }
  
    .footer__addr {
      flex: 1 0px;
    }
  
    .footer__nav {
      flex: 2 0px;
    }
  }
  </style>
  