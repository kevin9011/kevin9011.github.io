---
layout: page
title: Create Github Page with Jekyll
description: it shows the process of how my personal github page is created and modified using jekyll and github
show_tile: false
permalink: _projects/Create_Github_Page_with_Jekyll.html
---
<!-- Main -->
<div id="main" class="alt">
<!-- One -->
    <section id="one">
	    <div class="inner">
		   <header class="major">
			   <h1>Create Github Page with Jekyll</h1>
		   </header>
            <h2>Introduction</h2>
            <p>
            Github page is service provided by Github which allow user to directly host website on the repository. It is easy to set up and edit which is good for static website. In order to make the github page look prettier, I also choose use Jekyll to develop the page. Github page fully support Jekyll package. It is very easy to use. In this page, I will explain the way of creating current github page.
            </p>
            <h2>Setup</h2>
            <h4>Create a github account and get familiar with github and git</h4>
            <p><a href="https://help.github.com/en/articles/set-up-git">
            Github & Git Guide
            </a>
            <br/>
            <a href="https://git-scm.com/docs">
            Git Documentation
            </a>
            </p>          
            <h4>Create initial Github Page</h4>
            <p>
            The github page theme that I choose to use is the following.<br/>
            <a href="https://github.com/andrewbanchich/forty-jekyll-theme"> Forty Jekyll Themes</a>
            <br/>
            <br/>            
            For using the theme, I first create an empty repository with name "[username].github.io", where [username] is my github user name (kevin9011). Then I clone the theme to local folder with following git bash comment
            <br/>
            <code>
            git clone https://github.com/andrewbanchich/forty-jekyll-theme
            </code>
            <br/>
            <br/>
            Then I set the current location to folder "forty-jekyll-theme" and run the git push with mirror option to the empty reposityor that I create above
            <br/>
            <code>
            cd forty-jekyll-theme
            <br/>
            git push --mirror https://github.com/[username]/[username].github.io
            </code>
            <br/>
            <br/>
            After this point, I have my github repository to host the github page with forty theme. I can now modify the page to make it become my own page.
            If you want to choose other theme, you can use following website to choose one you like
            <br/>
            <a href="https://jekyllthemes.io/">Jekyll Themes</a>
            </p>
            <h2>Customization</h2>
            <h4>Customize the Home page</h4>
            <p>
            The home page is a combinatin of following md and html
                <div>
                index.md<br/>
                home.html<br/>
                tiles.html<br/>
                </div>
            </p>
            <h4>Customize the Meanu</h4>
            <h4>Customize the Tiles</h4>
            </p>           
        </div>
    </section>
</div>



