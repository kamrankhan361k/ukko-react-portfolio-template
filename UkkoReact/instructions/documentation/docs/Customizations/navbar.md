---
sidebar_position: 2
---

# Navigation Bar

We will learn how to edit navbar links, add and delete links too.

## Edit Links

To edit links text all you need to do is go to the data folder ./src/data and open navbar.json file.

When you open this file you will find three large items,

- **home link** --> _which is the main link to home page_
- **nav links** --> _Links that scroll to sections_
- **footer links** --> _footer social links_

![navbar](./img/navbar/main-data.jpg)

Each link has the following values

```json
{
  "to": "section id to scroll to",
  "text": "text preview of the link"
}
```

![navbar links](./img/navbar/nav-1.jpg)

You can change footer links too and add your social media profile links to "`"to"`" attribute.
![navbar footer links](./img/navbar/nav-footer-links.jpg)

## Add Links

To add links for example to nav links, you need to add another object and give it the given values.

![add navlink](./img/navbar/add-nav-link.jpg)

You can also add footer link by the same steps.

![add footer link](./img/navbar/add-nav-foor-link.jpg)

## Delete Link

To delete a link you need to remove the object of the link you want to remove, for example, you can delete the links we added from the previous step.
