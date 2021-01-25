andy-ta.github.io
---------

My minimal and formal résumé (CV) website for print, mobile, and desktop. 
The proportions are the same on the screen and paper. Created from [Universal Resume Template](https://github.com/WebPraktikos/universal-resume).

How to run it
---------

Navigate to the base directory:

Install the dependencies:

```
yarn install
```

Start the development server:

```
yarn serve
```

Only generate CSS that is used on the page which results in a much smaller file size:

```
yarn build
```

A4 Size Variant
---------

Change the default (letter) size to A4:

**1.** Inside `docs/index.html`, replace every `-letter` with `-a4`.

**2.** Inside `tailwind.config.js`, uncomment code block below `/* For A4 size */` and then comment code block below `/* For Letter size */`

**3.** Inside `tailwind.css`, comment code below `/* For Letter size */` and uncomment code below `/* For A4 size */`

Printing
---------

### Chrome

Right-click → Print.  
Also, choose the **Save as PDF** option if needed.

By expanding **More Settings**, change **Page Size** to A4 or Letter.

### Firefox

File → Print.

Choose A4 or Letter size by navigating to **Properties → Advanced → Paper Size**.

### Adobe Acrobat Reader

File → Print.

By clicking on the **Page Setup** button, you are taken to the window with A4 and Letter options.

License
---------

NonCommercial-ShareAlike 1.0 Generic (CC-BY-NC-SA-1.0)  
https://creativecommons.org/licenses/nc-sa/1.0/
