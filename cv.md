# rsschool-cv
***
## Nikita Sobolev
****
### Contacts:
- Email: n.sobolev94@gmail.com
- GitHub: [nsobolev](https://github.com/nsobolev/)
- Telegram: [@nikitasobolev](https://t.me/@nikitasobolev)
- Discord: [n.sobolev](https://discordapp.com/users/500927356785917954)

### About myself
Frontend engineer with experience in developing of dynamic websites built with latest JavaScript ecosystem tools. I have worked in companies such as TradeSoft, BidFox. I like to learn new things in frontend development.

Nice to meet you.

### My skills
- Responsive HTML5, CSS3 from PSD/Sketch/any other format including statics.
- JavaScript (ES2015/ESNext), React, Redux, TypeScript, Mobx.
- CSS: BEM, Styled-components, Preprocessors (Less/SASS), Bootstrap, Mobile-first.
- Code style: StyleLint/ESLint.
- Other: Git, Webpack, Gulp, SVG, Storybook.

### Code example
The tooltip initialization function. I was making a wrapper over the plugin `tippy.js`.
```
function initDsPopover() {
    const popoverElements = document.querySelectorAll( DS_POPOVER_SELECTOR );
    if ( popoverElements.length ) {
        for ( const popoverElement of popoverElements ) {
            try {
                const content = getPopoverContent( popoverElement );
                const placement = getPopoverPlacement( popoverElement );
                addPopover( popoverElement, content, placement );
            }
            catch ( error ) {
                console.error( `${ DS_POPOVER_PREFIX_MESSAGE } - ${error.message}` );
            }
        }
    }
    else {
        const errorMessage = 'Вы забыли указать data-атрибут для ds-popover';
        const attributeName = DS_POPOVER_SELECTOR.slice( 1, -1 );
        console.warn( `${ DS_POPOVER_PREFIX_MESSAGE } - ${ errorMessage } - ${ attributeName }.` );
    }
}
```

### Projects
- [Hate Auditor](https://auditor.hate.agency/) - React, Mobx, Less.
- [Bidfox](https://bidfox.ru/) - React, Mobx, Typescript, Styled-Components.
- [Base CutSew](https://base.cutsew.ru/) - NextJS, Redux, Typescript, UI Library.

### Courses
- Frontend Development on React (Ivan Kleshnin)
- HTML and CSS. Professional website layout (HTMLAcademy)
- HTML and CSS. Adaptive layout and automation (HTMLAcademy)
- JavaScript. Professional development of web interfaces (HTMLAcademy)
- React + Redux - Professional Development (Juriy Bura)
- Competent feedback (Education Reg.ru)
- and other

### Languages
- Russian — Native
- English — A1 — Elementary