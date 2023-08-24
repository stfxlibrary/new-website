# new-website

## fulltrysearch.html 

Current search box, uses lots of js but tabs can be added and removed easier using the Resource class.

## hours.html 

The simple javascript from the springshare widget with the libcal javascript for today's hours Todays hours information can be found [here](https://ask.springshare.com/libcal/faq/1275#daily). Libguide content box widget code information can be found [here](https://ask.springshare.com/libguides/faq/848#link-widget).

## landing-links.html 

Fetches the children of the current page from the menu, and displays them as horizonal links

## libguide-dropdown.html 

Uses the subject dropdown widget from springshare, removes the subject searches, and styles to match

**Widget Configuration:**

Look & Feel
- Output format: Simple List - \<ul\>, \<li\> tags
    - Embed Type: JavaScript Code
    - Link target: New window
- List Format: Drop-down menu with links
- Hierarchy: Unchecked

Search
- Status: Only subjects with published guides
- Associations: Include Guide titles with link

## livechat.html 

The livehcat to be inline with hours. margaret has the original livechat code, although i think i only added the new script below the html, and fixed the live chat hours link

## quicklinks.html 

Hardcoded quick links for library home page

## search.html 

Older version of search box with hardcoded html

## stfx-searvices-quick.html 

Current service list code with styling for quicklinks

## stfx-services.html 

Link list taking from first and second level menu items without quick links
