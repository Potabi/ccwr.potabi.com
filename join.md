Joining the CCWR is actually simple. You have to agree to the terms of the web ring, add the logo, and link to the CCWR website. Being a CCWR member project

## TERMS
Being a CCWR member you agree:
- To work on projects with no intent to harm others
- To be kind and respectful with other projects you compete with
- To be kind and respectful with other CCWR projects
- To cooperate with fair requests from competition
  - This does NOT mean you have to do everything they request, just be kind when saying no.
- To accept critisism of your project
- To openly or privately give contructive crtitisism
- To be objective, fair, and honest when using problems with a project as a "selling point"
- To have good sportsmanship with other projects when they pass milestones

## REQUESTS
Being a CCWR member, we request (optional):
- To be tranperant with income, funding, and ownership of funding
- To give back to other CCWR members
- To have some way to donate to your project
- To be open source (we accept proprietary software projects to the CCWR)

## JOINING
To become a CCWR member is simple. You need to add the CCWR logo to your website, and have it linked back to the CCWR website.

![CCWR Logo Alt](https://raw.githubusercontent.com/Potabi/ccwr.potabi.com/gh-pages/image/logo.png)

Once you have done that, email [ccwr@potabi.com](mailto:ccwr@potabi.com) with the subject "CCWR MEMBER" and in the body include the URL to your project, and member contact email.

> We have provided some examples on how to add it to your website/project in multiple languages and frameworks!

HTML:
```html
<a href="https://ccwr.potabi.com">
    <img src="https://raw.githubusercontent.com/Potabi/ccwr.potabi.com/gh-pages/image/logo.png" alt="CCWR Logo">
</a>
```

Markdown:
```md
![CCWR Logo Alt](https://raw.githubusercontent.com/Potabi/ccwr.potabi.com/gh-pages/image/logo.png)
```

MEML:
```lisp
(a href="https://ccwr.potabi.com"
    (img src="https://raw.githubusercontent.com/Potabi/ccwr.potabi.com/gh-pages/image/logo.png" alt="CCWR Logo"))
```

PugJS
```js
img(src="img(src='https://raw.githubusercontent.com/Potabi/ccwr.potabi.com/gh-pages/image/logo.png')")
```

NextJS
```jsx
import ccwr from 'https://raw.githubusercontent.com/Potabi/ccwr.potabi.com/gh-pages/image/logo.png';

export default function home {
    return (
        <>
            <!-- Rest of Website -->
            <Image src={ccwr} alt="CCWR logo" />
        </>
    )
}
```