Be sure to add the secret file ...
## secret.json
```
{
	"api_key": "this is a long hash",
	"password": "this is a long hash",
	"url": "youshop.myshopify.com",
	"theme": "00000000",
	"production": "00000000"
}
```

* To get the api_key and password you need to make an app via theshop.myshopify.com/admin/apps/private/new
* To get the theme ID go to edit the theme via theshop.myshopify.com/admin/themes => customize this theme, in the url theshop.myshopify.com/admin/themes/xxxxxxxx/editor (x's are the theme id)

* Run npm install to get all the packages
* !ONLY! edit the liquid files inside of html/
