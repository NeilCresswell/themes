Dark Room IDE Themes
====================

These are dark themes, primarily aimed at web development.

Personally, I use them daily with WebStorm, Sublime Text, and Aptana Studio, but they are suited for other IDEs too.

Many similar themes I've tried in the past had several issues, which I've tried to address here:

1. If the theme had a black background, typically the foreground colors were too bright, and tired my eyes in a dark environment.
2. If the theme had an off-black background to subdue the foreground colors, this was typically way too bright for my taste.
3. Almost all themes relegated comments to fainter colors, to accentuate code more than comments.
   I actually like to do the opposite, and make comments stand out, since I try to have meaningful comments.
   That being said, I didn't want comments to overwhelm the code, so hopefully you'll find a good compromise here.

All themes have been tested with the following file types:

* CSS/CSS3
* HTML/HTML5
* JavaScript (inline and .js)
* JSON
* PHP (inline and js)
* SQL
* XML

If you have any suggestions or feedback, please feel free to chime in:
https://github.com/NeilCresswell/themes/issues

I'd love to come up with a Visual Studio theme based off of these, but don't have the time right now.

Neil Cresswell.

---

Textmate Themes
---------------

*Suitable for **Sublime Text** and **Eclipse**-based IDEs such as **Aptana Studio**.*

* Developed with Aptana Studio 3.
* Tested against Aptana Studio 3 and Sublime Text 3.
* Comes in two flavours: Dark Room (Normal) and Dark Room (Contrast):
--* Dark Room (Normal) has a slightly off-black background so the colors are more subdued.
--* Dark Room (Contrast) has a full black (#000) background for use on laptops, etc.

---

JetBrains Theme
---------------

*Suitable for **WebStorm**.*

* Developed and tested with **WebStorm 9**.
* Probably works with other JetBrains products such as **PHPStorm**. *(Feedback appreciated.)*
* Uses the Dark Room Texmate theme colors as a starting point, but with additional refinements.

How to install:

1. File / Import Settings / {point to DarkRoomNormal.jar file and click OK}
2. File / Settings / Colors & Fonts / {select Dark Room - Normal and click OK}

There is no higher contrast version since in WebStorm, this can be achieved with a single change:

1. File / Settings / Colors & Fonts / General / Default text / {click on background colour}
2. Enter **000000** into the # box.

Other IDE settings for an optimal experience:

1. File / Settings / Appearance & Behaviour / Appearance:
--* Theme: **Darcula** (this is a dark theme for the IDE wrapper, including menu bar.)
--* Override default fonts by **Segoe UI**, (if available,) size 14px.
2. File / Settings / Editor / Colors & Fonts / Font:
--* Show only monospaced fonts.
--* Primary font: **Source Code Pro**, size 14, line spacing 1.0.
--* You can find Source Code Pro in the /fonts folder of this project.
