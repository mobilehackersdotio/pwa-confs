# pwa-confs

An open source community-curated list of PWA conferences around the world for mobile developers that bet on the web.

Adding a conference
-------------------

Just send a pull-request which edit a file of the [/conferences](https://github.com/mobilehackersio/pwa-confs/tree/master/conferences) directory. Your PR should include a new object representing the conference with the following structure :

```json
{
  "name": "",
  "url": "",
  "startDate": "YYYY-MM-DD",
  "endDate": "YYYY-MM-DD",
  "city": "",
  "country": "",
  "cfpUrl": "",
  "cfpEndDate": ""
}
```

Notes: 
- Do not include the location of the conference in the name but specify it through the country attribute.
- Cfp means "call for papers" and cfpUrl and cfPendDate are optional links, please do not include these attributes instead of leaving them blank.
- Please do not include regular meetups

You can also ping us on [twitter](https://twitter.com/mobilehackersio).


Contributors
-------------------
waiting for contributors ...


License
-------

All content is [MIT](https://github.com/mobilehackersio/pwa-confs/blob/master/LICENSE).
