Static HTML Fragments for Scenario Explorer Pages
=================================================

This repository contains a set of HTML-fragments to customize an instance of an ixmp
Scenario Explorer.

The HTML pages can be edited directly in the github user interface by selecting the
page and editing it in the browser. Of course cloning the repo and pushing local
changes works as well.

Whenever changes to the HTML-fragements are committed to the **master** branch (default
when editing in the github user interface) they are automatically deployed to the
corresponding scenario explorer instance.

**IMPORTANT**: the changes are **not** immediately visible. It typically takes between a
few seconds and a few minutes for the changes to take effect. If the changes are not visible 
after a considerable amount of time it could be that you need to delete the site specific 
cookies and cached files to force your browser to actually reload the page. 

Step by Step Guide for editing directly in GitHub
=================================================

As an example we edit the contents of the `<h2>` (headline level 2) tag in the About page 
so that it shows the correct Scenario Explorer name.

1. Select the `About.html` file
2. This opens the file in view mode. On the right side of the header there is a small pen icon. 
Selecting this opens the file in edit mode.
3. In edit mode change, for example, the heading `<h2>` from `<h2>IIASA ixmp Scenario Explorer</h2>`
to `<h2>{Your project name} Scenario Explorer</h2>`
4. Once the neccessary changes have been made, scroll to the bottom of the page and select 
`Commit changes`. For better traceability it might be good idea to add a short description of what
has been changed to the commit box. 
5. **Important**: As mentioned above, it might take up to a few minutes for the changes to be visible
in your Scenario Explorer instance. 
