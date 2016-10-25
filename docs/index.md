---
assignees:
- adonese
- mj

---
<style>
h2, h3, h4 {
  border-bottom: 0px !important;
}
.colContainer {
  padding-top:2px;
  padding-left: 2px;
  overflow: auto;
}
#samples a {
  color: #000;
}
.col3rd {
  display: block;
  width: 250px;
  float: left;
  margin-right: 30px;
  margin-bottom: 30px;
  overflow: hidden;
}
.col3rd h3, .col2nd h3 {
  margin-bottom: 0px !important;
}
.col3rd .button, .col2nd .button {
  margin-top: 20px;
  border-radius: 2px;
}
.col3rd p, .col2nd p {
  margin-left: 2px;
}
.col2nd {
  display: block;
  width: 400px;
  float: left;
  margin-right: 30px;
  margin-bottom: 30px;
  overflow: hidden;
}
.shadowbox {
  display: inline;
  float: left;
  text-transform: none;
  font-weight: bold;
  text-align: center;
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
  line-height: 24px;
  position: relative;
  display: block;
  cursor: pointer;
  box-shadow: 0 2px 2px rgba(0,0,0,.24),0 0 2px rgba(0,0,0,.12);
  border-radius: 10px;
  background: #fff;
  transition: all .3s;
  padding: 16px;
  margin: 0 16px 16px 0;
  text-decoration: none;
  letter-spacing: .01em;
}
.shadowbox img {
    min-width: 150px;
    max-width: 150px;
    max-height: 50px;
}
</style>
<div class="colContainer">
  <div class="col3rd">
    <h3>What is GeoidApp?</h3>
    <p>GeoidApp is software application for working with various geoid components e.g. <i>geoid height</i>, <i>geoid disturbance</i>, and others to be added very soon.</p>
    <a href="/docs/whatisgeoidapp/" class="button">Read the Overview</a>
  </div>
  <div class="col3rd">
    <h3>GeoidApp Interactive Tutorial</h3>
    <p>Ideally we would like to have an interactive web application to let users try the application before the buy it. If you want to contribute the source code, this is definitely the best place to start from. You just need to have some experience with working with JS.</p>
    <a href="/docs/tutorials/geoidapp-basics/" class="button">Try the Interactive Tutorials</a>
  </div>
  <div class="col3rd">
    <h3>Installing GeoidApp</h3>
    <p>As of this version GeoidApp version 0.9b it is still a command line tool. From me I really like working with command line interface, and I see it to be very productive compared to GUI. But I also consider the case that there are some people born with a natural hating for that scary blackboard with some cursor blinking. About the installation, for Linux users, we assume they have more knowledge of command line compared to Windows or Mac OS users, but even in Linux we will have some pre-packaged version for Ubuntu for instance. Installation on Windows or Mac OS machines will be very simple. This is not yet implemented but hopefully we will have some Amazon AWS instance so that you can run the whole application in the cloud.</p>
    <a href="/docs/getting-started-guides/geoidapp/" class="button">Install GeoidApp</a>
  </div>
  <div class="col3rd">
    <h3>Technical details</h3>
    <p>We encourage our users to know every detail about this software, specially the underlying math and physics, and the derivation of the formulas that we use in GeoidApp. The mathematical concepts behind this software can't be treated as a black box. You really have to know what is going on.</p>
    <a href="/docs/user-guide/math-physics-concepts/" class="button">Some mathematical background</a>
  </div>
</div>



<p>&nbsp;</p>
<p>&nbsp;</p>

<div class="colContainer">
  <div class="col2nd">
  <h3>Contribute to Our Docs</h3>
  <p>This is not a free software why on earth should I contribute to? There are a few things to highlight first. A free software doesn't mean free of charges, it solely means to freedom to have access to the source code, and to modify it, and to redistribute it. Another thing, this is actually an open source version of our application, and it's totally driven by the community. The license does allow you to redistribute it if you like. I don't want to take advantages of your contributions and use some ideas in our paid version.</p>
  <a href="/docs/contribute/create-pull-request/" class="button">Write Docs for GeoidApp</a>
  </div>
  <div class="col2nd">
  <h3>Need Help?</h3>
  <p>The community of GeoidApp is really a cool place to start finding a solution to your problem.
  </div>
</div>
