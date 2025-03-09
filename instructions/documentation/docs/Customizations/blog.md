---
sidebar_position: 7
---

# Blog Section

Go to `./src/data/blog.json` file, and open it.

## Changing Blog Text

Change the text in the file and the preview text in the template will be changed.

```json
{
  "title": "section title",
  "description": "section short description"
}
```

![portfolio](./img/blog/edit-blog-1.jpg)

## Changing Blog Posts

```json
{
  "posts": [
    {
      "to": "link to the blog post page",
      "title": "blog title",
      "date": "released date",
      "category": "category text"
    },
    ...
  ]
}
```

![blog](./img/blog/edit-blog-2.jpg)

## Single Blog

By default we directed every blog post to `/single-blog` page, you can change the content of this page by going to `./pages/blog/single-blog/index.tsx` and change the content of it.

![blog](./img/blog/edit-blog-3.jpg)

You can Add Pages By adding more routes (in case you want to have more than one blog page).

Go to `./src/app/routes.tsx` and add more routes according to the blog pages you have.

![blog](./img/blog/edit-blog-4.jpg)
