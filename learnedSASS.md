# Web Developer Study
## 12 months web developer study. I decided to dedicate at least 12 months to learn web development.

![Begin Banner](/Documentation/top-1200x350.gif)

* Online courses, challenges and creation of my own projects.

## What I learned/used 
### SASS 
* Syntactically awesome style sheets (SASS) 
    * documente .extention
        * .sass
        * .scss (most commun)
    * config
        * live sass compiler
        * config sass
            * open setting JSON
                * "liveSassCompile.settings.formats": [
                    {
                        "format": "expanded",
                        "extensionName": ".css",
                        "savePath": "/dist",
                        "savePathReplacementPairs": null
                    }
                ]
    * Partials
        * folder global
            * _name.scss (start the name with _ ) -> _name.scss
            * @forward 'name';
    * variable
        * :root{}
        * sass modules
        * @use 'name' as 'abreviation'
    * Responsive 
        * <meta name="viewport" content="width=device-width, initial-scale=1.0">
    * SASS & BEM
    * setting widths
        * max-width
        * margin:
        * margin-inline => only affects left and right
            * margin-inline-start / margin-inline-end
        * min() =>  take 2 parameter and choose the small values between to.
            * width: min(100%, 1000px);
    * sass mixins and build-in modules
        * media query
        * sass map
    * order of media queries matter due to the cascade.
    

![End Banner](/Documentation/botton-1200x350.gif)