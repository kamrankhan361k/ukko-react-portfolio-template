---
sidebar_position: 4
---

# Services Section

Go to `./src/data/services.json` file, and open it.

## Changing Section Text

Change the text in the file and the preview text in the template will be changed.

```json
{
  "title": "section title",
  "description": "short description",
  "paragraphes": [
    "paragraphe 1",
    "paragraphe 2",
    ...
  ]
}
```

![services](./img/services/edit-services-1.jpg)

For paragraphs that existed in the array, you can add more paragraphs or reduce them as you need, and they will be added to the template.

In the paragraphs array, you can add links and bold text by using markdown standards in writing, just bold text and links are allowed: [add links](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#links), [add bold text](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#emphasis)

## Changing Services Links

You can change service links in the same way we used to change nav links in Navbar Customization, and you can add more links or delete one of them as you want.

```json
{
  "servicesLinks": [
    {
      "to": "direct link",
      "text": "text preview"
    },
    ...
  ],
}
```

![services](./img/services/edit-services-2.jpg)

## Services Boxes

```json
{
  "servicesBoxes": [
    {
      "imageAltText": "alt text of the service image",
      "servTitle": "service title",
      "servDesc": "service short description"
    },
    ...
  ]
}
```

![services](./img/services/edit-services-3.jpg)

### Adding Service

If you want to add a service all you need to do is to copy one service Object in `services.json` file and add it to the servicesBoxes array, and here is an example.

![services](./img/services/edit-services-4.jpg)

As you can see in the image, the new service appeared but the problem is that there is no image.

go to `./src/pages/landing/sections/services/index.tsx` and add the new image.

![services](./img/services/edit-services-6.jpg)

:::info
Number of services should be equal the number of images in images array.
:::
