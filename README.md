# Announcement-Bar

An announcement bar allows merchants to display custom updates and promote discounts. When added to a theme, this static section will be displayed on the homepage.

Steps to install

1) Create a new file within the sections folder of your theme, and paste the code below into this file. Save as announcement-bar.liquid.
2) On the theme.liquid file add {% section 'announcement-bar' %} in the position where you would like it to appear (eg. within the main page wrapper container, above the {{ content_for_layout }} Liquid object). 
