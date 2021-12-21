### Summary

---

Please make a carousel UI component which contains images by using assets provided in `/assets` folder.
The UI component should meet the requirements included in `spec` section.

### Spec

---

1. mockup

![mockup](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/7668f0dd-bd3b-4dfa-9b13-277703a99e6e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20211221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20211221T015147Z&X-Amz-Expires=86400&X-Amz-Signature=3527c5f62ce199165789872314d1577ec5ebea79d5e3eef7542ccdcd3aa77e22&X-Amz-SignedHeaders=host&response-content-disposition=filename+%3D%22Untitled.png%22&x-id=GetObject)

- There are 6 photos in this carousel
- Two arrow buttons on the left and right hand side respectively
- 6 bullets are placed under the image
  - Bullets have two state, default and active. For example, if the component is showing the first photo, the first bullet is in active state, and the rest stay in default state.
  - colors for bullets in different state
    - default: rgb(190, 192, 188)
    - active: white

Please note that we do not specify the detailed properties in the mockup above, for example, padding, margin...etc.
You can make the call on those detailed properties.

2. features

- When one of the arrow buttons is clicked:
  - Photo changes with sliding animation, please check the [reference](https://www.twreporter.org/photography).
  - The active bullet also changes corresponds to photo changes

Please note that infinite carousel is not included in requirement.
