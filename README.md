# Goal Diggers Website

This website is a plattform for our fans and partners to get familiar with our team. It's also a plattform for veteran tournaments to be able to invite the team to their upcoming events.

Visit our website [here](https://simonjellvert.github.io/goal-diggers/)!

![Mock up of resposive design on different screen sizes](/docs/gd_mock-up.png)
*Note that the mock up doesn't look exactly like the real product on each platform.*

---

## Features

### **Navbar**

All three pages has a navbar in which you can browse through the pages. I added a logo on the top left which links to "Home"-page. The menu has a hover effect which highlights hovered element with the same color as the gold-part (#d4a53e) of our apparels, with an active 2px line showing the user which page is active.

![Screenshot of navbar](/docs/gd_navbar.png)

### **Footer**

In the footer I've added a link to our Instagram page with a hover affect that turns the icon into the golden color of our apparels (#d4a53e). I've also added a copyright text.

![Screenshot of footer](/docs/gd_footer.png)

### **Home page**

The landing page informs the user who the Goal Diggers are and how they came around. It describes the passion the players have for the game and why they keep on doing this.
The design of having a short text on one side and an image on the other was to have a minimalistic design since the team doesn't have a lot of content to apply in this early stage of life. The team have different kinds of logo types but design wise I think that the black and white version suits this minimalistic design the best and was easiest to create a redline throughout the site.

![Screenshot of home page](/docs/gd_home-page.png)

### **Partners page**

On the Partners page whe team shows gratitude for their partners/sponsors who have made it possible to create this hockey team.
It also have a link that sets up an e-mail to our general manager if the user is interested in becoming a partner to the team.
On the right hand side we have an image of our apparel that shows the user how the teams jersey look.

I hold on to the minimalistic design on this page aswell to keep it simple for the user to find information. The apparell image is not the coolest image to use but the idea is to visualize for potential partners how they can expose their brand together with the team.

![Screenshot of partners page](/docs/gd_partner-page.png)

Below this section we have a gallery of logotypes of the teams current sponsors, each one with a direct link to their own websites. To highlight the hovered logotype I added an increasing effect.

![Screenshot of sponsors logotypes on the partners page](/docs/gd_partner-logos.png)

### **Contact page**

On the contact page the user gets familiar on who they can contact if they e.g wants to invite the team to a tournament or have any other questions they want to ask. Via a link in the main text the user can also choose to leave their contact info by filling out a form.

I've added som styling to the images and a link to an e-mail within the envelope icon, which is turning in to the golden color (#d4a53e) when hovered. The link to contact form is also turning gold (#d4a53e) when hovered.

I also added a map for the user to see where the team play their games so it's easy for the user to navigate if they want to come see the team.

![Screenshot of contact page](/docs/gd_contact-page.png)

### **Contact form**

On the contact page the user can click on a link to fill in their contact info, so that the team can contact the user. The user is required to fill out their email address and phone number, and hit "SEND". The page is styled as the rest of the website with the gold (#d4a53e) and white colors and black(ish) (#2a2d2c) font. The "SEND" button is styled with a hovering effect that turns the button from black (#2a2d2c) to gold (#d4a53e).

Note: The form is a mock up.

![Screenshot of contact-form](/docs/gd_contact-form.png)

### **Response message**

When the user hit the "SEND" button they get a response message thanking them for reaching out and informing that the team will get back to them as soon as possible. The user can head back to the original page via links in the menu or clicking on the text which says "HOME PAGE". The "HOME PAGE" is a link and turns gold (#d4a53e) when hovered.

![Screenshot of response message](/docs/gd_response-massage.png)

### **404 Error page**

Sometimes things go wrong, so to make it easy to the user to navigate back to the main page I a
created a 404 error page which informs the user that something is wrong and how to turn around and head the right direction again. In the error message I have a link to the home page and they can also use the navbar to head back to the page they where looking for. The link in the text turns gold (#d4a53e) when hovered.

![Screenshot of 404 error page](/docs/gd_error-page.png)

---

## **Features for the future**

Here are some of the features that will be added in the future:

- Player videos/highlights will be added when content is available. Because of the teams short time of life such content is not available at this time.
- Turn the mock up contact form in to a real one.
- Updated sponsors page with new/more logotypes (when the team gets more sponsors).
- Webshop page with Goal Diggers merchandise.
- Tournaments page (when the team has participated in more than one) with statistics.
- Roster page with information and statistcs of the players.

---

## Testing

The website has been tested several times on W3 Validator during the development
with good result along the way.
Testing has been done using different platforms devtools by myself and general manager and marketing director of the team to get second opinions.

All features works as I want them to on different plattforms.

The **navbar** is decreasing evenly when decreasing the screensize. The menu moves
down below the logotype on small screens.
The hover and active effekt on the menu is tested on multipal computers.
When testing this on different plattform  I dicovered some bugs  with the background color not covering the whole upper area, specially on the iPhone. I also discovered that the logo and menu didn't look so good when it wasn't centered and it sometimes divided the menu into two columns which was not good looking. So when I centered the logo and menu the issue was fixed and I haven't experinced it again since.

The **footer** is positioned relative at the bottom of the page and works well across all pages
of the website and on different plattforms. Testing has been done several times to get in the right spot relative
to the other content on each page.

The content of **Home**, **Partners** and **Contact** page is divided into sections
using flexbox and was tricky to make it look good and behave the way I wanted when decreasing
the screen size. Testing have been done using DevTools and the platforms I have access to to find the right properties
and values.

Since I've learned a lot more about using flex since this code was written I would have done the coding differently today. Since thoose methods where not included in the LMS I choose not to use it in this stage. when I get access to the code again after resubmitting and assessment I'm going to make thoose changes.to make it easier for ather developers and myself to read and change to code.

### **Validator Testing**

#### HTML

- The **Home page** code is tested in W3 Validator and passed with no warnings.

![Screenshot of W3 validator](/docs/gd_html-val_home-page.png)

- The **Partners page** code is tested in W3 Validator and passed with no warnings.

![Screenshot of W3 validator](/docs/gd_html-val_sponsors-page.png)

- The **Contacts page** code is tested in W3 Validator and passed with no warnings.

![Screenshot of W3 validator](/docs/gd_html-val_contact-page.png)

- The **Contact form** code is tested in W3 Validator and passed with no warnings.

![Screenshot of W3 validator](/docs/gd_html-val_contact-form.png)

- The **Response message page** code is tested in W3 Validator and passed with no warnings.

![Screenshot of W3 validator](/docs/gd_html-val_response-page.png)

- The **404 Error page** code is tested in W3 Validator and passed with no warnings.

*Result:*
![Screenshot of W3 validator](/docs/gd_html-val_404-page.png)

#### CSS

The **CSS** code is tested in Jigsaw Validator and passed with only one warning about the import of Google fonts:

*Result:*
![Screenshot of result from Jigsaw CSS Validator](/docs/gd_css-val.png)

*Warning*
![Screenshot of warning from Jigsaw CSS Validator](/docs/gd_css-val_warning.png)

### **Bugs**

Bugs detected during testing:

- Menu and logo not filling the upper area of a small screen, tested on Iphone (now fixed).
- Menu was divided into two columns when the logo and menu wasn't centered on the screen. Fixed that by using media queires.

---

## **Deployment**

The site was deployed to GitHub pages in following steps:

- In the GitHub repository I navigated to Settings and then Pages.
- From the source section drop-down menu, I selected Main Branch and clicked Save.
- After a few minuted the link to live URL was provided.

The live link can be found here: [Goal Diggers Website](https://simonjellvert.github.io/goal-diggers/)

---

## **Credits**

Inspiration to the websites lay out comes from Love Punning project combined with [Kapena's Website](www.kapena.se).
I've used parts of Love Runnings code on the navbar and on the images on the contact page.
I've used the idea of Kapena's lay out with the separeted page where the text content
is on one side and an image on the other.

- Fonts where imported from Google Fonts
- Icons where imported from Font Awesome
- Logotypes on Partners page where gathered from each website:
  - [Kapena](https://www.kapena.se)
  - [Fiskarhedenvillan](https://www.fiskarhedenvillan.se)
  - [Kamtech](https://www.kamtech.se)
  - [Kinnaprs](https://www.kinnars.se)
  - [Renta](https://www.resta.se)
  - [Örebro Sotarn](https://www.orebrosotarn.se)
  - [Stadium](https://www.stadium.se)
  - [VentPartner](https://www.ventpartner.se)
  - [Affärsconsult](https://www.affarsconsult.se)
  - [FlexiblaHem](https://www.flexiblahem.se)
- Images on contact page where gathered from:
  - [Kapena](https://www.kapena.se/kontakt)
  - [Fiskarhedenvillan](https://www.fiskarhedenvillan.se/kontor/orebro/)
- Colors generated from:
  - [ImageColorPicker](https://imagecolorpicker.com/)
- Favicon generated from:
  - [Favicon](https://favicon.io/)

---

Thank you for visiting our website and we hope you enjoyed it!

Feel free to take a look at the code and feedback us on improvements!

Link to repository: [Simon Jellverts GitHub](https://github.com/simonjellvert/goal-diggers).

Have a nice day!
