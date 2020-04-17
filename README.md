# vuetify-datatable-transitionClasses-issue

## Reproduction Steps

```bash
# install dependencies
$ npm install

# generate static site
$ npm run generate

# serve static site
$ npx serve dist
```

Open website now running on http://localhost:5000/ in Chrome. 

* Open Chrome DevTools
* Show device toolbar, and select iPhone 6/7/8.
* Refresh the page.

A data table will render, but the page will be unresponsive. 

![Rendered data table](https://github.com/jacothom/vuetify-datatable-transitionClasses-issue/blob/master/static/rendered_data_table.png)

The console will show the following errors

![Console errors](https://github.com/jacothom/vuetify-datatable-transitionClasses-issue/blob/master/static/error_message.png)

TypeError: Cannot read property '_transitionClasses' of undefined

DOMException: Failed to execute 'appendChild' on 'Node': This node type does not support this method.


