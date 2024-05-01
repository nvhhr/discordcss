### Collection of pretty simple css snippets, some having variables to modify.
I try to make the snippets work through discord updates and with any themes to some extent.  
You can hit me up on Vencord theme dev channel, or post issues or contributions here if you desire.  
Screenshots may not be exactly what you will see (depending on many factors) or may be slightly out of date.  
Recommended way to customize the variables is to use the snippets in Vencord online themes or imports, and adding the variables into quickcss and modifying them there.  
**The snippets are still in active development and I reserve the right to make breaking changes.**

**[actuallybasicbackground:](actuallybasicbackground.theme.css)**  
A pretty simple but highly targeted style to set a background image at the bottom and clear out backgrounds from certain elements in front.
<details> <summary>:sunrise_over_mountains:screenshot before</summary>
<img src="https://github.com/nvhhr/discordcss/assets/34724502/6d7c13e6-cabb-4329-88cc-d08c373a9e7d">
</details>
<details> <summary>:sunrise_over_mountains:screenshot after</summary>
<img src="https://github.com/nvhhr/discordcss/assets/34724502/f146b328-ddd5-48c2-ada9-6daeb2713f86">
</details>

**[betterusertags:](betterusertags.theme.css)**  
Nicer bot/staff tags + new user leaf replaced to match.
<details> <summary>:sunrise_over_mountains:screenshot</summary>
<img src="https://github.com/nvhhr/discordcss/assets/34724502/d0573ef8-8ed3-43cf-955b-7d5aa4bfa715">
</details>

**[bordercleanup:](bordercleanup.theme.css)**  
Clear out unnecessary borders and separators.  
Mostly intended for use with actuallybasicbackground but wanted to make it separate.

**[dashless-extended:](dashless-extended.theme.css)**  
Replaces all dashes (-) in channel names with a font with a blank glyph, and replaces all flag emojis with Twemoji-Mozilla font (because Windows mostly).
<details> <summary>:sunrise_over_mountains:screenshot</summary>
<img src="https://github.com/nvhhr/discordcss/assets/34724502/da4ddde8-1f46-4185-91b3-0a29b2b9749d">
</details>

**[fontreplace:](fontreplace.theme.css)**  
Change font and fontsize.
<details> <summary>:sunrise_over_mountains:screenshot</summary>
<img src="https://github.com/nvhhr/discordcss/assets/34724502/6fab5f33-abd3-48fe-82dd-0de8f852438f">
</details>

**[lowercaser:](lowercaser.theme.css)**  
Forces certain texts to lowercase, because lowercase is cuter.

**[modalsettings:](modalsettings.theme.css)**  
Settings and some other dialogs like audit log show up as a modal window.
<details> <summary>:sunrise_over_mountains:screenshot</summary>
<img src="https://github.com/nvhhr/discordcss/assets/34724502/46aa8ab9-4789-4ba2-bed5-042a6ec7a06f">
</details>

**[namebrightener:](namebrightener.theme.css)**  
Many users have unreadable dark usernames, janky fix for that
<details> <summary>:sunrise_over_mountains:more info and screenshot</summary>

This will alter the colors for everyone a bit by trying to achieve a somewhat uniform contrast and brightening a bit, then resaturating, maybe dialing in the values produces nicer results but it also depends on the theme/monitor/eyes you might have.  
Maybe some day `currentColor` works with relative colors like `hsl(from currentColor h s 50%)` or with `color-mix()` and this can be done proper.  

<img src="https://github.com/nvhhr/discordcss/assets/34724502/693b3827-85f3-4b3e-8405-fd24bd1428eb">
</details>

**[nocaption:](nocaption.theme.css)**  
Remove titlebar, adjust toolbar a bit and create a drag area under window buttons.
<details> <summary>:sunrise_over_mountains:screenshot</summary>
<img src="https://github.com/nvhhr/discordcss/assets/34724502/fc8ed5f0-4d3d-410e-8a52-725b61512ab5">
</details>

**[randomfixes:](randomfixes.theme.css)**  
A miscellaneous collection of random fixes that shouldn't be unwanted.

**[recute:](recute.theme.css)**  
Make vencord server cute again (not included with main theme).

**[shadows:](shadows.theme.css)**  
Add shadows to text and images.

**[squareicons:](squareicons.theme.css)**  
Reduces border-radii of avatars and servericons.

**[swaphomeicon:](swaphomeicon.theme.css)**  
Replace home icon/DM button with custom image.
<details> <summary>:sunrise_over_mountains:screenshot</summary>
<img src="https://github.com/nvhhr/discordcss/assets/34724502/95f6fa66-ab6b-40ed-b368-bd09970be277">
</details>


### Copypaste helper :D
<details>
<summary>Just the links (for vencord online themes)</summary>

```
https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/actuallybasicbackground.theme.css
https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/betterusertags.theme.css
https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/bordercleanup.theme.css
https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/dashless-extended.theme.css
https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/fontreplace.theme.css
https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/lowercaser.theme.css
https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/modalsettings.theme.css
https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/namebrightener.theme.css
https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/nocaption.theme.css
https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/randomfixes.theme.css
https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/recute.theme.css
https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/shadows.theme.css
https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/squareicons.theme.css
https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/swaphomeicon.theme.css
```
</details>
<details>
<summary>imports (for inserting to css)</summary>

```css
@import url("https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/actuallybasicbackground.theme.css");
@import url("https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/betterusertags.theme.css");
@import url("https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/bordercleanup.theme.css");
@import url("https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/dashless-extended.theme.css");
@import url("https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/fontreplace.theme.css");
@import url("https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/lowercaser.theme.css");
@import url("https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/modalsettings.theme.css");
@import url("https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/namebrightener.theme.css");
@import url("https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/nocaption.theme.css");
@import url("https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/randomfixes.theme.css");
@import url("https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/recute.theme.css");
@import url("https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/shadows.theme.css");
@import url("https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/squareicons.theme.css");
@import url("https://raw.githubusercontent.com/nvhhr/discordcss/main/snippets/swaphomeicon.theme.css");
```
</details>


