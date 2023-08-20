## 1.GET/api​/v1​/Activities 

HTTP-метод:GET

Полный URL запроса:"https://fakerestapi.azurewebsites.net/api/v1/Activities" 

Заголовки запроса:-H  "accept: text/plain; v=1.0"

Тело запроса:отсутствует

Статус-код ответа:200

Тело ответа:
```
  [  
  {
    "id": 1,

    "title": "Activity 1",

    "dueDate": "2023-06-17T06:01:37.4107119+00:00",

    "completed": false
  },
```
## 2.PUT/api​/v1​/Activities​/{1}

HTTP-метод: PUT

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Activities/1

Заголовки запроса:-H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0"

Тело запроса:
```
{
  "id": 0,
  "title": "string",
  "dueDate": "2023-06-17T21:24:57.427Z",
  "completed": true
}
```

Статус-код ответа:200

Тело ответа:
```
{
  "id": 0,
  "title": "string",
  "dueDate": "2023-06-17T21:24:57.427Z",
  "completed": true
}
```
## 3.PUT/api​/v1​/Activities​/{56788907765443266890098665443223456799987654437777889}

 HTTP-метод:PUT

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Activities/56788907765443266890098665443223456799987654437777889

Заголовки запроса:-H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0"

Тело запроса:
```{
  "id": 0,
  "title": "string",
  "dueDate": "2023-06-17T21:24:57.427Z",
  "completed": true
}
```

Статус-код ответа:400

Тело ответа: 
```
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-049e77715864134b8cd77f590aebca6f-fb83bdb694fd1e4d-00",
  "errors": {
    "id": [
      "The value '56788907765443266890098665443223456799987654437777889' is not valid."
    ]
  }
}
```
## 4.POST/api​/v1​/Activities

HTTP-метод:POST
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Activities

Заголовки запроса:-H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0"

Тело запроса:
```{
  "id": 0,
  "title": "string",
  "dueDate": "2023-06-17T21:26:06.953Z",
  "completed": true
}
```
Статус-код ответа:200

Тело ответа:
```
{
  "id": 0,
  "title": "string",
  "dueDate": "2023-06-17T21:26:06.953Z",
  "completed": true
}
```
## 5.GET/api​/v1​/Activities​/{2}

HTTP-метод:GET

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Activities/2

Заголовки запроса: -H  "accept: text/plain; v=1.0"

Тело запроса:отсутствует

Статус-код ответа:200

Тело ответа:
```
{
  "id": 2,
  "title": "Activity 2",
  "dueDate": "2023-06-18T00:09:47.6340372+00:00",
  "completed": true
}
```
## 6.GET/api​/v1​/Activities​/{555555555555555555555555555555555555555555555}

HTTP-метод:GET

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Activities/555555555555555555555555555555555555555555555

Заголовки запроса:-H  "accept: text/plain; v=1.0"

Тело запроса:отсутствует

Статус-код ответа:400

Тело ответа:
```
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-f458c8c6cd31594ab4e6276424aee24b-36c2d1bd83280a47-00",
  "errors": {
    "id": [
      "The value '555555555555555555555555555555555555555555555' is not valid."
    ]
  }
}
```
## 7.DELETE/api​/v1​/Activities​/{3}

HTTP-метод:DELETE

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Activities/3

Заголовки запроса:-H  "accept: */*"

Тело запроса:отсутствует

Статус-код ответа:200

Тело ответа:
```
access-control-allow-origin: * 
 api-supported-versions: 1.0 
 content-length: 0 
 date: Sat17 Jun 2023 22:25:19 GMT 
 server: Kestrel 
 ```
 ## 8.DELETE/api​/v1​/Activities​/{88888888888888888888888888888888888888888888888888888}

 HTTP-метод:DELETE

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Activities/88888888888888888888888888888888888888888888888888888

Заголовки запроса:-H  "accept: */*"

Тело запроса:отсутствует

Статус-код ответа:400

Тело ответа:
```
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-9a347d413be6154fb9689a20456f49ff-f1728ddfc7fe3147-00",
  "errors": {
    "id": [
      "The value '88888888888888888888888888888888888888888888888888888' is not valid."
    ]
  }
}
```
## 9.GET/api​/v1​/Authors

HTTP-метод:GET

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Authors

Заголовки запроса:-H  "accept: text/plain; v=1.0"

Тело запроса:отсутствует

Статус-код ответа:200

Тело ответа:
```{
    "id": 1,
    "idBook": 1,
    "firstName": "First Name 1",
    "lastName": "Last Name 1"
  }
  ```

## 10.POST/api​/v1​/Authors

HTTP-метод:POST

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Authors

Заголовки запроса:-H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0" -d "

Тело запроса:
```
{
  "id": 0,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}
```
Статус-код ответа:200

Тело ответа:
```
{
  "id": 0,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}
```
## 11.GET/api​/v1​/Authors​/authors​/books​/{4}

HTTP-метод:GET

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Authors/authors/books/4

Заголовки запроса:-H  "accept: text/plain; v=1.0"

Тело запроса:oтсутствует

Статус-код ответа:200

Тело ответа:
```
 {
    "id": 10,
    "idBook": 4,
    "firstName": "First Name 10",
    "lastName": "Last Name 10"
  }
  ```

## 12.GET/api​/v1​/Authors​/authors​/books​/{4444444444444444444444444444444444444444444444444444}

HTTP-метод:GET

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Authors/authors/books/4444444444444444444444444444444444444444444444444444

Заголовки запроса:-H  "accept: text/plain; v=1.0"

Тело запроса:отсутствует

Статус-код ответа:400

Тело ответа:
```
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-0e3d3985ce84e247b6a4f02aa2cfb0ea-591f650bf2c3ca45-00",
  "errors": {
    "idBook": [
      "The value '4444444444444444444444444444444444444444444444444444' is not valid."
    ]
  }
}
```
## 13.GET/api​/v1​/Authors​/{5}

HTTP-метод:GET

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Authors/5

Заголовки запроса:-H  "accept: text/plain; v=1.0"

Тело запроса:отсутствует

Статус-код ответа:200

Тело ответа:
```
{
  "id": 5,
  "idBook": 2,
  "firstName": "First Name 5",
  "lastName": "Last Name 5"
}
```
## 14.GET/api​/v1​/Authors​/{5555555555555555555555555555555555555555555555555555555555555555555555}

HTTP-метод:GET

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Authors/5555555555555555555555555555555555555555555555555555555555555555555555

Заголовки запроса: -H  "accept: text/plain; v=1.0"

Тело запроса:отсутствует

Статус-код ответа:400

Тело ответа:
```
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-eaef683822726941af417b8e52051027-73834175a74d0f46-00",
  "errors": {
    "id": [
      "The value '5555555555555555555555555555555555555555555555555555555555555555555555' is not valid."
    ]
  }
}
```
## 15.PUT/api​/v1​/Authors​/{6}

HTTP-метод:PUT

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Authors/6

Заголовки запроса: -H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0" 

Тело запроса:
```
{
  "id": 0,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}
```
Статус-код ответа:200

Тело ответа:
```
{
  "id": 0,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}
```
## 16.PUT/api​/v1​/Authors​/{6666666666666666666666666666666666}

HTTP-метод:PUT

Полный URL запроса:

Заголовки запроса:https://fakerestapi.azurewebsites.net/api/v1/Authors/66666666666666666666666666666666666666666

Тело запроса:
```
{
  "id": 0,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}
```
Статус-код ответа:400

Тело ответа:
```
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-828a9ce97e66eb4cb670d97019ea249a-669a0abe9ca2b242-00",
  "errors": {
    "id": [
      "The value '66666666666666666666666666666666666666666' is not valid."
    ]
  }
}
```
## 17.DELETE/api​/v1​/Authors​/{7}

HTTP-метод:DELETE
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Authors/7

Заголовки запроса:-H  "accept: */*"

Тело запроса:отсутствует

Статус-код ответа:200

Тело ответа:
```
access-control-allow-origin: * 
 api-supported-versions: 1.0 
 content-length: 0 
 date: Sat17 Jun 2023 23:11:49 GMT 
 server: Kestrel 
 ```
## 18.DELETE/api​/v1​/Authors​/{7777777777777777777777777777777777777777777777777777777777}

HTTP-метод:DELETE
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Authors/7777777777777777777777777777777777777777777777777777777777

Заголовки запроса:-H  "accept: */*"

Тело запроса:отсутствует

Статус-код ответа:400

Тело ответа:
```
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-2b2c808ad5b3b24692ea829a1811468f-1032f7b68f524941-00",
  "errors": {
    "id": [
      "The value '7777777777777777777777777777777777777777777777777777777777' is not valid."
    ]
  }
}
```
## 19.GET/api​/v1​/Books

HTTP-метод:GET
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Books

Заголовки запроса:-H  "accept: text/plain; v=1.0"

Тело запроса:отсутствует

Статус-код ответа:200

Тело ответа:
```
{
    "id": 1,
    "title": "Book 1",
    "description": "Praesent takimata ut elit. Erat imperdiet voluptua accusam. Dolores ex sed kasd. Vel ea in dolor at sea est amet odio erat sit consetetur facer. Tation ipsum clita soluta erat dolor dolores no tincidunt nulla magna justo sed dolor accusam diam ex. Velit et amet duo aliquyam minim eu ut imperdiet sea erat dolores aliquyam labore takimata sed stet at. Dolor euismod sadipscing nibh voluptua aliquam clita at diam ipsum elitr erat vel at vel nonummy accusam invidunt velit. Justo eos ea ipsum sea eos voluptua dolor. Clita eos et nulla et soluta.\n",
    "pageCount": 100,
    "excerpt": "Exerci ea magna justo duis diam duo nonumy augue sed. Gubergren voluptua aliquip elitr elitr blandit tempor at erat eirmod. Ipsum et eu vero tempor amet sea ea eos. Et labore feugait consequat no ipsum volutpat et ea esse erat amet justo magna dolor tempor diam. Clita ipsum in enim est amet ea labore est at. Volutpat aliquyam et eirmod. Consetetur elitr gubergren vero et ea labore sed vel molestie et sea veniam. Imperdiet lorem facilisis ipsum vulputate tempor amet takimata vel duis et. Ut gubergren invidunt dolor aliquip sit takimata sed invidunt est dolores. Ut dolor commodo dolor et blandit. Ullamcorper sed ipsum dolor sit eirmod dolore eum. Sit eirmod dolor nonumy ipsum sed duo vero lorem sit dolores voluptua dolor accusam kasd placerat commodo erat takimata. Et congue at erat no elit labore facilisis eu sed gubergren aliquam labore.\nLorem consetetur eirmod adipiscing eirmod eum at dolor ut ut ipsum ex stet. Ipsum rebum no voluptua vero dolore et sit luptatum et cum. Dolor gubergren rebum tincidunt clita sadipscing autem te et eos delenit kasd takimata dolor te. Tempor doming facilisis magna sit elitr elitr kasd sit. Gubergren voluptua sed tempor diam. Sed nonumy takimata justo labore sed diam et. Dolore et elitr elit voluptua. Nulla sed ea. Est vulputate ut. Illum volutpat ipsum et eleifend kasd veniam eu aliquyam ipsum sed diam justo. Elitr praesent dolore ullamcorper sea. Lorem justo erat stet at consetetur lorem et stet duo eos gubergren vero suscipit autem ut magna. Tation nonumy sed consetetur sadipscing velit et tation lorem no lorem et commodo. Sit stet consetetur dolore lorem diam ea nisl. Autem cum sanctus ipsum dolores rebum sit no iusto consequat lorem ipsum erat et no vero erat et vel. Hendrerit dolores aliquyam dolores lorem at kasd. Et ut diam tempor sit accusam dolore sed rebum sed dolor. Lorem justo diam zzril praesent ut et nihil qui.\nSed stet voluptua nihil nonumy et voluptua nulla sea ipsum duis at eirmod iriure stet ipsum eum et. Stet aliquam eos sadipscing hendrerit accusam sed et praesent et kasd adipiscing kasd labore option tempor vero. Sadipscing iusto erat. Volutpat ad lorem eos. Diam justo ipsum.\nVeniam tempor invidunt et sadipscing et ut nonummy nonumy diam diam erat nihil sed ipsum sed. Ipsum nonumy vero diam nonumy duis at sanctus gubergren nonumy tempor. Dolor stet sed erat accumsan dolores elitr ipsum et labore ipsum nonumy et dolores vel sed sit et eu. Dignissim nobis vel zzril ipsum dolores justo sea clita sea eirmod. Feugiat ex eirmod gubergren ea ipsum et. Iriure consetetur eos ea invidunt justo dolore clita ea ea consetetur sadipscing tincidunt. At duo sed stet accusam. Volutpat ut invidunt sanctus vel lorem sea. Aliquyam erat magna tincidunt sadipscing consetetur vero sed erat sit sed erat rebum takimata. Zzril dolores aliquyam sadipscing rebum at et dolore dolore magna ut sanctus veniam takimata volutpat sit sit sea. Dolore kasd ut consequat sit no sadipscing et diam autem et elitr voluptua kasd sed hendrerit.\nSed consetetur sed consetetur ipsum at dolore in eirmod dolore dolor nibh. Duis amet sadipscing accumsan luptatum aliquyam. Aliquyam clita accusam sea congue suscipit duo vulputate sea iriure et justo at et. Labore kasd tation ut nisl lorem sed voluptua nulla ea id euismod et tincidunt labore lobortis.\n",
    "publishDate": "2023-06-17T03:47:07.4982834+00:00"
  }
  ```
## 20.POST/api​/v1​/Books

HTTP-метод:POST
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Books

Заголовки запроса: -H  "accept: */*" -H  "Content-Type: application/json; v=1.0"

Тело запроса:
```
{
  "id": 0,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-06-18T03:54:12.820Z"
}
```

Статус-код ответа:200

Тело ответа:
```
{
  "id": 0,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-06-18T03:54:12.82Z"
}
```
## 21.GET/api​/v1​/Books​/{8}

HTTP-метод:GET
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Books/8

Заголовки запроса:-H  "accept: text/plain; v=1.0"

Тело запроса:отсутствует

Статус-код ответа:200

Тело ответа:
```
{
  "id": 8,
  "title": "Book 8",
  "description": "Rebum no est et eu nostrud magna feugiat ut ut est no ut sanctus ad stet feugiat ipsum. Eum dolore stet eum adipiscing nonummy dolore sit magna ut consetetur no et. Et amet invidunt erat amet cum. Dolor gubergren justo stet accusam euismod ipsum lorem ut ipsum suscipit dolore kasd vero. Dolor amet dignissim facilisis. Lobortis et sea odio voluptua eirmod duis odio dolores tempor commodo. Erat elitr autem voluptua duis nonummy facilisis dolor et.\n",
  "pageCount": 800,
  "excerpt": "Magna lorem ipsum et magna gubergren sadipscing volutpat ullamcorper ut ipsum lobortis autem dolor dolor. Dolore erat sed qui clita. Voluptua sed justo clita magna velit dolor diam vero et sea tempor diam sit sed amet. Dolore vero in elitr dolore et ipsum duis et nulla no amet eos sanctus delenit et nulla. Et ipsum accumsan est eirmod labore wisi in justo eirmod kasd at enim no ut ipsum. Dolor odio sadipscing nostrud eum adipiscing amet nisl gubergren elitr amet ex diam. Est ea eos sea sit diam at odio et. Vulputate imperdiet et sit sit labore sit veniam voluptua vulputate lorem stet tempor nobis. Lorem ullamcorper sit consetetur sed magna eirmod sadipscing magna lorem in elitr amet takimata nibh at. Ipsum labore tempor ut. Ipsum sea no sed ut at stet facer elitr sed. Wisi sadipscing feugiat tincidunt veniam magna aliquip dolor blandit ea. Diam elitr amet est volutpat zzril ea ipsum ut quis nonumy nam veniam clita justo adipiscing. Sed placerat et rebum ea sit ex ipsum kasd aliquam sit et lorem ut ex sit.\nEt eos dolor clita liber voluptua nostrud vel voluptua euismod volutpat eirmod clita sadipscing kasd consequat sadipscing clita. Ea dolore diam invidunt facilisi odio magna dolor eos tempor sed exerci sanctus feugait. Ut amet at kasd ut vulputate tempor accusam at accusam clita placerat takimata lorem. Et eros diam dolor suscipit blandit voluptua eirmod.\nAt et rebum sed et et ipsum quis est feugait accusam sea diam. Mazim nonumy dolore et ipsum amet ea takimata dolores eum accusam duo et tempor est iusto. Sea illum elitr facilisis dolor sanctus lorem vero vel dolor sed. Dolor duis facilisis dolore sed sed diam tempor gubergren. Stet voluptua praesent sanctus blandit. Congue sit euismod feugait labore labore. Et ut luptatum sed laoreet labore takimata clita commodo clita diam magna dolor consetetur justo sadipscing sed diam lorem. Duo laoreet praesent clita amet eirmod rebum aliquyam vel eirmod. Praesent dolore vel qui lorem elit tempor aliquam lorem dolore diam dolore nonumy feugiat. Odio at erat takimata dolor diam delenit velit amet invidunt ut. Amet molestie lorem diam kasd consetetur dolore facer diam aliquyam.\nAdipiscing eos nonumy sit amet elitr. Diam soluta minim sit. Ut euismod invidunt vulputate justo consetetur sanctus volutpat dolor at quis eirmod. Consetetur ea vero sanctus tempor ut no sit et amet erat iriure vel. Sit erat dolore ipsum et labore invidunt nulla aliquip takimata gubergren erat blandit. Hendrerit sanctus nam clita dolor volutpat amet sed sit. Veniam eirmod elitr dolor consetetur. Takimata lorem diam dolor ipsum tempor elitr et vero est stet justo et et zzril. Accusam consequat sea vel eirmod dolores dolor diam in clita vel justo takimata consetetur elitr molestie. Labore duis sed ea ea magna possim eu illum. Sit lobortis ea diam praesent et rebum duo sed amet sadipscing eu et laoreet sanctus. Ullamcorper vero eos illum sed stet nihil et ea dolores eirmod justo est. Tempor tempor nonumy dolor doming aliquyam sed sit rebum ad elitr vero labore aliquyam at esse. Magna ipsum lobortis gubergren ea gubergren sit liber dolore gubergren nibh duis gubergren invidunt iriure sit takimata sed et. Euismod magna eos nonumy voluptua sea gubergren nulla et erat elitr commodo kasd sed dolores.\nEos eirmod voluptua nonumy gubergren duis erat et tempor magna eros magna. Sed ipsum ut ut ea nonumy aliquyam ea vel eirmod labore. Vel ipsum sit dolore clita takimata justo consetetur voluptua ea ipsum erat duo dolor. At gubergren justo erat ipsum kasd hendrerit sit consetetur stet. Amet consequat accusam est. Duo vero sit et suscipit diam ea dolor at. Clita dolore consetetur iriure nonumy ea rebum sit esse sanctus. Nulla magna ea sit ipsum sea dolor voluptua clita facer placerat hendrerit. In ut accusam vero erat et consetetur molestie lobortis eum sed ea diam labore vero stet magna iriure invidunt.\n",
  "publishDate": "2023-06-10T03:57:51.7954551+00:00"
}
```
## 22.GET/api​/v1​/Books​/{8888888888888888888888888888888888888888888888888888}

HTTP-метод:GET
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Books/8888888888888888888888888888888888888888888888888888

Заголовки запроса:-H  "accept: text/plain; v=1.0"

Тело запроса:отсутствует

Статус-код ответа:400

Тело ответа:
```
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-a13bbbbf499b1c48b5158cd242f0c234-10922630dd2d0642-00",
  "errors": {
    "id": [
      "The value '8888888888888888888888888888888888888888888888888888' is not valid."
    ]
  }
}
```
## 23.PUT/api​/v1​/Books​/{9}

HTTP-метод:PUT
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Books/9

Заголовки запроса:-H  "accept: */*" -H  "Content-Type: application/json; v=1.0" -d "

Тело запроса:
```
{
  "id": 0,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-06-18T04:06:57.141Z"
}
```
Статус-код ответа:200

Тело ответа:
```
{
  "id": 0,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-06-18T04:06:57.141Z"
}
```
## 24.PUT/api​/v1​/Books​/{999999999999999999999999999999999999999999999999999999999}

HTTP-метод:PUT
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Books/999999999999999999999999999999999999999999999999999999999

Заголовки запроса:-H  "accept: */*" -H  "Content-Type: application/json; v=1.0" -d "

Тело запроса:
```
{
  "id": 0,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-06-18T04:06:57.141Z"
}
```
Статус-код ответа:400

Тело ответа:
```
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-7d82f2f9d86a314db821daa27c8f7286-d29ddd2aad43eb42-00",
  "errors": {
    "id": [
      "The value '999999999999999999999999999999999999999999999999999999999' is not valid."
    ]
  }
}
```
## 25.DELETE/api​/v1​/Books​/{10}

HTTP-метод:DELETE
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Books/10

Заголовки запроса:-H  "accept: */*"

Тело запроса:отсутствует

Статус-код ответа:200

Тело ответа:
```
access-control-allow-origin: * 
 api-supported-versions: 1.0 
 content-length: 0 
 date: Sun18 Jun 2023 04:15:15 GMT 
 server: Kestrel 
 ```
 ## 26.DELETE/api​/v1​/Books​/{1000000000000000000000000000000000000}

 HTTP-метод:DELETE
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Books/1000000000000000000000000000000000000

Заголовки запроса:-H  "accept: */*"

Тело запроса:отсутствует

Статус-код ответа:400

Тело ответа:
```
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-d271a13f41c2cf4ab5640650c4348115-49d4a454a6890745-00",
  "errors": {
    "id": [
      "The value '1000000000000000000000000000000000000' is not valid."
    ]
  }
}
```
## 27.GET/api​/v1​/CoverPhotos

HTTP-метод:GET
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos

Заголовки запроса:-H  "accept: text/plain; v=1.0"

Тело запроса:отсутствует

Статус-код ответа:200

Тело ответа:
```
{
    "id": 1,
    "idBook": 1,
    "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 1&w=250&h=350"
  }

```

## 28.POST/api​/v1​/CoverPhotos

HTTP-метод:POST
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos

Заголовки запроса:-H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0"

Тело запроса:
```
{{
  "id": 0,
  "idBook": 0,
  "url": "string"
}
```
Статус-код ответа:200

Тело ответа:
```
{
  "id": 0,
  "idBook": 0,
  "url": "string"
}
```
## 29.GET/api​/v1​/CoverPhotos​/books​/covers​/{20}

HTTP-метод:GET
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/books/covers/20

Заголовки запроса:-H  "accept: text/plain; v=1.0"

Тело запроса:отсутствует

Статус-код ответа:200

Тело ответа:
```
{
    "id": 20,
    "idBook": 20,
    "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 20&w=250&h=350"
  }
```

## 30.GET/api​/v1​/CoverPhotos​/books​/covers​/{2000000000000000000000000000000000000000}

HTTP-метод:GET
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/books/covers/2000000000000000000000000000000000000000

Заголовки запроса:-H  "accept: text/plain; v=1.0"

Тело запроса:отсутствует

Статус-код ответа:400

Тело ответа:
```
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-676479f6c89ff24688fb45c1130fa6db-ae6e0dbaef14734f-00",
  "errors": {
    "idBook": [
      "The value '2000000000000000000000000000000000000000' is not valid."
    ]
  }
```
## 31.GET/api​/v1​/CoverPhotos​/{30}

HTTP-метод:GET
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/30

Заголовки запроса:-H  "accept: text/plain; v=1.0"

Тело запроса:отсутствует

Статус-код ответа:200

Тело ответа:
```
{
  "id": 30,
  "idBook": 30,
  "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 30&w=250&h=350"
}
```
## 32.GET
​/api​/v1​/CoverPhotos​/{3000000000000000000000000000000000000000000}

HTTP-метод:GET
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/3000000000000000000000000000000000000000000

Заголовки запроса:-H  "accept: text/plain; v=1.0"

Тело запроса:отсутствует

Статус-код ответа:400

Тело ответа:
```
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-d7fb1cc371c4ee49a12e6419412eb4f9-c112421fa8a2554b-00",
  "errors": {
    "id": [
      "The value '3000000000000000000000000000000000000000000' is not valid."
    ]
  }
}
```
## 33.PUT/api​/v1​/CoverPhotos​/{40}

HTTP-метод:PUT

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/40

Заголовки запроса:-H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0"

Тело запроса:
```
{
  "id": 0,
  "idBook": 0,
  "url": "string"
}
```
Статус-код ответа:200

Тело ответа:
```
{
  "id": 0,
  "idBook": 0,
  "url": "string"
}
```
## 34.PUT/api​/v1​/CoverPhotos​/{400000000000000000000000000000000000000000000}

HTTP-метод:PUT
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/400000000000000000000000000000000000000000000

Заголовки запроса:-H  "accept: text/plain; v=1.0" -H  "Content-Type: application/json; v=1.0"

Тело запроса:
```
{
  "id": 0,
  "idBook": 0,
  "url": "string"
}
```
Статус-код ответа:400

Тело ответа:
```
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-c5c60423fad826488b47fe7ccc4ef030-b9c43da611b4fa44-00",
  "errors": {
    "id": [
      "The value '400000000000000000000000000000000000000000000' is not valid."
    ]
  }
}
```
## 35.DELETE/api​/v1​/CoverPhotos​/{50}

HTTP-метод:DELETE
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/50

Заголовки запроса: -H  "accept: */*"

Тело запроса:отсутствует

Статус-код ответа:200

Тело ответа:
```
access-control-allow-origin: * 
 api-supported-versions: 1.0 
 content-length: 0 
 date: Sun18 Jun 2023 09:17:08 GMT 
 server: Kestrel 
```
## 36.DELETE/api​/v1​/CoverPhotos​/{5000000000000000000000000000000000000000}

HTTP-метод:DELETE
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/5000000000000000000000000000000000000000

Заголовки запроса:-H  "accept: */*"

Тело запроса:отсутствует

Статус-код ответа:400

Тело ответа:
```
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-3a9642527fcc6340a17648ccb8f9a910-dba94a775f74504c-00",
  "errors": {
    "id": [
      "The value '5000000000000000000000000000000000000000' is not valid."
    ]
  }
}
```
## 37.GET/api​/v1​/Users

HTTP-метод:GET
​
Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Users

Заголовки запроса:-H  "accept: text/plain; v=1.0"

Тело запроса:отсутствует

Статус-код ответа:200

Тело ответа:
```
{
    "id": 1,
    "userName": "User 1",
    "password": "Password1"
  }
```
## 38.POST/api​/v1​/Users

HTTP-метод:POST

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Users

Заголовки запроса:-H  "accept: */*" -H  "Content-Type: application/json; v=1.0"

Тело запроса:отсутствует

Статус-код ответа:200

Тело ответа:
```
{
  "id": 0,
  "userName": "string",
  "password": "string"
}
```
## 39.GET/api​/v1​/Users​/{1}

HTTP-метод:GET

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Users/1

Заголовки запроса: -H  "accept: */*"

Тело запроса:отсутствует

Статус-код ответа:200

Тело ответа:
```
{
  "id": 1,
  "userName": "User 1",
  "password": "Password1"
}
```
## 40.GET/api​/v1​/Users​/{60}

HTTP-метод:GET

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Users/60

Заголовки запроса:-H  "accept: */*"

Тело запроса:отсутствует

Статус-код ответа:404

Тело ответа:
```
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.4",
  "title": "Not Found",
  "status": 404,
  "traceId": "00-b6877dffc462444ab2cc93139c0ee9fa-d109738869849f43-00"
}
```
## 41.PUT/api​/v1​/Users​/{2}

HTTP-метод:PUT

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Users/2

Заголовки запроса:-H  "accept: */*" -H  "Content-Type: application/json; v=1.0"

Тело запроса:
```
{
  "id": 0,
  "userName": "string",
  "password": "string"
}
```

Статус-код ответа:200

Тело ответа:
```
{
  "id": 0,
  "userName": "string",
  "password": "string"
}
```
## 42.PUT/api​/v1​/Users​/{7000000000000000000000000000000000000000000000000}

HTTP-метод:PUT

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Users/7000000000000000000000000000000000000000000000000

Заголовки запроса:-H  "accept: */*" -H  "Content-Type: application/json; v=1.0"

Тело запроса:
```
{
  "id": 0,
  "userName": "string",
  "password": "string"
}
```
Статус-код ответа:400

Тело ответа:
```
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-e0e020a8f0aa4e49a76bed3dedbf3cd2-6a3ad82a79f3e94a-00",
  "errors": {
    "id": [
      "The value '7000000000000000000000000000000000000000000000000' is not valid."
    ]
  }
```
## 43.DELETE/api​/v1​/Users​/{3}

  HTTP-метод:DELETE

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Users/3

Заголовки запроса:-H  "accept: */*"

Тело запроса:отсутствует

Статус-код ответа:200

Тело ответа:
```
access-control-allow-origin: * 
 api-supported-versions: 1.0 
 content-length: 0 
 date: Sun18 Jun 2023 09:54:21 GMT 
 server: Kestrel 
```
## 44.DELETE/api​/v1​/Users​/{3666666666666666666666666666666666666666666}

 HTTP-метод:DELETE

Полный URL запроса:https://fakerestapi.azurewebsites.net/api/v1/Users/3666666666666666666666666666666666666666666

Заголовки запроса: -H  "accept: */*"

Тело запроса:отсутствует

Статус-код ответа:400

Тело ответа:
```
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-95f30a4b06219a47a1af98ae3ef92cbe-d0e0780a27e14c43-00",
  "errors": {
    "id": [
      "The value '3666666666666666666666666666666666666666666' is not valid."
    ]
  }
}
```




