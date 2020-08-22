# steemscript

An open JSON standard for Steem based apps.

### Account json_metadata

- `name`: max. length 20 chars.
- `about`: max. length 160 chars.
- `location`: max. length 30 chars.
- `website`: valid `https://` URL with max. length 100 chars.
- `profile_image`: avatar image URL, preferably square-cropped with a minimum size of 230 x 230 pixels.
- `cover_image`: cover image URL.

```json
{
  "profile": {
    "name": "Bilal Haider",
    "about": "Founder at Voilk",
    "location": "Islamabad",
    "website": "https://voilk.com/",
    "profile_image": "",
    "cover_image": ""
  }
}
```
