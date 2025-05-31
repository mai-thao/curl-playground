# curl-playground
Learning about the [cURL](https://curl.se/) command line tool. 

"curl" is shortened for Client URL. It's used to transfer data to and from a server using protocols like HTTP/HTTPS (and more).

I will be using various free REST API for testing with curl:
* [Dog API](https://dog.ceo/dog-api/)
* [Cat Facts API](https://catfact.ninja/)
* [JSONPlaceholder API](https://jsonplaceholder.typicode.com/)
* [Random User API](https://randomuser.me/)

## Usages

`curl [options] [URL]`

## Methods
An HTTP method is a verb like GET, POST, or a noun like OPTIONS or HEAD that defines the operation you want to perform.

#### GET
An HTTP request used to retrieve data from a server.

* `curl https://randomuser.me/api/` with sample JSON response:
```
{"results":[{"gender":"female","name":{"title":"Ms","first":"Nezabudka","last":"Nakonechniy"},"location":{"street":{"number":270,"name":"Provulok Samokisha"},"city":"Nizhin","state":"Zakarpatska","country":"Ukraine","postcode":31156,"coordinates":{"latitude":"74.2505","longitude":"62.3857"},"timezone":{"offset":"+3:00","description":"Baghdad, Riyadh, Moscow, St. Petersburg"}},"email":"nezabudka.nakonechniy@example.com","login":{"uuid":"99f80b94-396c-4909-827c-d12db3f64ca9","username":"smallswan183","password":"ironman","salt":"JxWJaJbk","md5":"6e944874b0a72260b5d3119316512258","sha1":"e28b2589e986f088c08ac496c4fa47d860dbcf08","sha256":"8ad002cb469e5d75c6b50936195a66ae0fdf76e44ff90ddc93aa074cf8d07526"},"dob":{"date":"1953-12-03T19:11:25.175Z","age":71},"registered":{"date":"2019-10-07T19:09:36.136Z","age":5},"phone":"(067) Z42-7667","cell":"(068) A63-9076","id":{"name":"","value":null},"picture":{"large":"https://randomuser.me/api/portraits/women/67.jpg","medium":"https://randomuser.me/api/portraits/med/women/67.jpg","thumbnail":"https://randomuser.me/api/portraits/thumb/women/67.jpg"},"nat":"UA"}],"info":{"seed":"9118122ec55f7f84","results":1,"page":1,"version":"1.4"}}
```
