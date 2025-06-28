# AO3 Skins
Site skins for Archive of Our Own — ___By Ifk___


## Content
- [About](#about)
- [Skin versions](#skin-versions)
- [Guide](#guide)
  - [Desktop skin](#desktop-skin)
  - [Mobile and tablet skin](#mobile-and-tablet-skin)
- [Feedback and requests](#feedback-and-requests)
- [Crediting](#crediting)


---


## About
This repository is a collection of all the site skins that I have created for public use. If you're wondering what a site skin is, you can read AO3's official [Skins and Archive Interface FAQ](https://archiveofourown.org/faq/skins-and-archive-interface#whatisaskin) for this. The FAQ will also tell you how to create a site skin of your own. Since skins can no longer be made public on AO3, every user needs to make their own version of a skin if they want to use it. 


## Skin Versions
Site skins will have a standard (desktop) version and most will also have skins for mobile and tablet. The most accurate names to call them are "max-width: 42em" and "max-width: 62em", since these are the actual breakpoints that AO3 uses. 


## Guide
If there is only a desktop CSS file provided for a skin, you only need to create one skin. If there are also mobile and/or tablet files provided, you need to create additional skins for these, and then add them as a "parent" to the desktop version. 

Since each skin needs a unique name, I recommend using your own username as a prefix. For mobile and tablet, use the device as a suffix. For example, for my skin "Slytherin", I have the site skins "Ifk's Slytherin", "Ifk's Slytherin -- Mobile" and "Ifk's Slytherin -- Tablet". 

### Desktop skin
Go to "Dashboard" > Go to "Skins" page.

![Go to skins](https://github.com/Ifkyyy/AO3-skins/blob/main/images/Skins.png)

Click on "Create Site Skin."

![Create site skin](https://github.com/Ifkyyy/AO3-skins/blob/main/images/Create%20Site%20Skin.png)

Give it a unique name. Fill in description and preview image (optional). Copy the code for the site skin (on GitHub) and paste it into the "CSS" text area.

![Copy all the code](https://github.com/Ifkyyy/AO3-skins/blob/main/images/Copy%20all%20code.png)
![Fill in form](https://github.com/Ifkyyy/AO3-skins/blob/main/images/New%20Site%20Skin.png)


Click "Submit."



### Mobile and tablet skin
For mobile and tablet, do the same steps as for desktop, but before submitting the skin, do the following:

Show the "advanced" section. Click the "Parent only" checkbox (optional — ensures the skin can't be used on its own). For mobile, click the "only screen and (max-width: 42em)" checkbox. For tablet, click the "only screen and (max-width: 62em)" checkbox.

![Fill in the advanced options](https://github.com/Ifkyyy/AO3-skins/blob/main/images/Mobile%20and%20Tablet.png)

Click "Submit." Find the desktop skin and click "Edit."

Show the "advanced" section. Click "Add Parent Skin." In the bottom input, write the name of your **tablet** skin (the name should show up in the suggestions, but if not, just copy-paste the exact name). Click "Add Parent Skin" again. Do the same for the **mobile** skin. Add any other utility skins that you have (optional).

![Add parent skins](https://github.com/Ifkyyy/AO3-skins/blob/main/images/Add%20Parent%20Skin.png)

Click "Update."

And then the skin is ready, and you can click "Use" on it. If you want to make your own edits later and add new rules, remember to add the changes to the **bottom** of the file, to properly override the existing CSS rules. 


## Feedback and requests
I am open to feedback and requests (and pull requests), but reserve the rights to decline or ignore them. Contact me through my AO3 comment section (on the relevant site skin) or open an issue on GitHub. 


## Crediting
Feel free to fork the repository or otherwise make your own copies of skins. Any site skin that uses parts of my code should give me credits, either using my AO3 username or through a link to this GitHub repository. 
