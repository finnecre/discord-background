# discord-background

this is a css file for a custom discord theme that can be used in any application that supports discord modifications, such as betterdiscord, vencord, etc.
unlike other themes, there are zero altercations to the discord ui. all fonts, colours, opacities, and modals remain the same.
however, there is a server column option.

**you are going to want to look for the file titled _custombackground.theme.css_**

to customize the code, there is a section titled "customize here".

you will have to replace the words WALLPAPER-LINK with the link to your desired image.
example:
--wallpaper: url('WALLPAPER-LINK');
to 
--wallpaper: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS8whETZXv77tmCH5zpBLT1UGYir2E1WhxmlR-yQ9s2E9vucJUW_OULxg&s=10');

to add server columns, find the line that says --columns: 0; and replace the 0 with the desired number of columns. it is located shortly after the wallpaper line
example: 
--columns: 0;
to
--columns: 3;

this code works in both light and dark mode, so choose whichever theme matches your background colour the best.
