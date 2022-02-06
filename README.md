# Horiseon Website
An Updated Version with Semantics and Accessibility Standards.

## Description:
This project's goal was to update this Website to meet the modern standards of Accessibility as well as organize its index structure to match the conventional best practices of Web Development.

### 1-Project Record - List of items rectified during the process:

### 1.1.Semantics:

        * The Website Title was rectified from “Website Title” to  “Horiseon”

        * Description Comments were added to each of the following sections 
            -Header/Menu
            -Content
            -Benefit Brand
            -Footer
        ## “Div” tags were adapted to the following standard tags
            -header
            -footer
            -nav
            -main
            -Aside
        * Synthesized the CSS Classes
                -Search Engine; Online Reputation; Social Media;
                    -Into Class= “Services”
                -Aside div Classes
                    -Into one single Class=“benefit”
                -Changed .Benefit class to
                    -Aside (tag)
### 1.2.Accessibility

        * The “alt” attributes were included to every image
            -Hero Section
            -3 Images on the main section
            -3 images on the aside section


##### Notes:
* While adding the “alt” attribute into the Hero section the following problem was found: 
    If the hero section image for some reason doesn't load the Image description inherited from the “alt” attribute would not appear to replace the “image”.
    This problem was solved by inserting an “Image Element” containing the “Background-Image” inside the div tags and erasing the Background-Image from the styles.css--kept as a comment.
    If needed, designs can be adjusted.

###### Requirements:

* Desktop Browsers for Viewing Content
    -Internet Explorer 11
    -Microsoft Edge (latest version)
    -Google Chrome (latest version)
    -Firefox (latest version)
    -Safari (latest version)
* Mobile Browsers for Viewing Content
    -Safari in Apple iOS 12 or later
    -Google Chrome (latest version) in Apple iOS 12 or later
    -Google Chrome (latest version) in Android OS 6 or later
* Required Browser Settings for Viewing Content
    -JavaScript must be enabled
    -Font downloads must be enabled
    -Turn off Compatibility View in Internet Explorer
* Screen Readers for Viewing Content
    -JAWS (latest version)
    -NVDA (latest version)
    -VoiceOver (latest version)
    -TalkBack (latest version)

### List of Files:
    -index.html
    -readme.txt
    -assets folder
        -css folder
            -styles.css
        -images folder
                -brand-awareness.png
                -cost-management.png
                -digital-marketing-meeting.jpg
                -lead-generation.png
                -online-reputation-management.jpg
                -search-engine-optimization.jpg
                -social-media-marketing.jpg
# Credits
	    Alan Anibal De Souza Ramos