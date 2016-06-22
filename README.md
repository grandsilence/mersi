# Mersi Theme

Mersi is a very simple flat style theme for Sublime Text 3 Build 3062+.

Based Piatto Theme by samuelrafo - [https://github.com/samuelrafo/piatto](https://github.com/samuelrafo/piatto)
And Soda Theme by Ian Hill - [http://buymeasoda.com/](http://buymeasoda.com/)

# Recommendations
* Use font for code "Inconsolata LGC" - [https://github.com/DeLaGuardo/Inconsolata-LGC](https://github.com/DeLaGuardo/Inconsolata-LGC)
* Install plug-in "BracketHighlighter" (available in Package Control)

## Design

![Mersi Theme - Backend](https://raw.github.com/grandsilence/Mersi/master/images/mersi_backend.png)
![Mersi Theme - Frontend](https://raw.github.com/grandsilence/Mersi/master/images/mersi_frontend.png)

* Color Scheme created on website "Sublime Scheme Editor"
* File Type Icons based on Seti_UI - [https://github.com/ctf0/Seti_ST3](https://github.com/ctf0/Seti_ST3)

## Installation

Mersi theme is designed to work with the latest development builds of Sublime Text 3 [Sublime Text 3](https://www.sublimetext.com/3), Build 3062+.

### Using Sublime Package Control

If you are using Will Bond's excellent [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install Mersi Theme via the `Package Control: Install Package` menu item. The Mersi Theme package is listed as `Theme - Mersi` in the packages list.

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - Mersi`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

To configure Sublime Text to use the theme, follow the instructions.

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Mersi.sublime-theme",
"color_scheme": "Packages/Theme - Mersi/Mersi.tmTheme"`

**Example Sublime Text User Settings**

    {
        "theme": "Mersi.sublime-theme",
		"color_scheme": "Packages/Theme - Mersi/Mersi.tmTheme",
		"font_face": "Inconsolata LGC",
		// For Windows only, better smooth font
		"font_options":
		[
			"directwrite"
		],
		"always_show_minimap_viewport": true,
		"draw_shadows": false,
		"enable_tab_scrolling": false,
		"highlight_line": true,
    }