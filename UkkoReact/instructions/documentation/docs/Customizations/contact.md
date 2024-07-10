---
sidebar_position: 9
---

# Contact Section

Go to `./src/data/contact.json` file, and open it.

## Changing Contact Text

Change the text in the file and the preview text in the template will be changed.

```json
{
  "title": "section title",
  "description": "section short description",
  "paragraphe": "some text"
}
```

![contact](./img/contact/edit-contant-1.jpg)

## Contact Form Activation

We used formspree API to receive messages via email, Make the following steps to activate the contact form and make messages sent to your email inbox.

- Goto [formspree](https://formspree.io/) and sign up with the email you want to receive messages on it.
- Activate your account and open your home page.
  ![contact](./img/contact/edit-contant-2.jpg)
- Create a new form endpoint.
  ![contact](./img/contact/edit-contant-3.jpg)
- Take Your endpoint from the website.
  ![contact](./img/contact/edit-contant-4.jpg)
- Put your endpoint in `contact.json` file.
  ![contact](./img/contact/edit-contant-5.jpg)
