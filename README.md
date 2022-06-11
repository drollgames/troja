# Troja SDK (JS)

### Troja Api (JS)

```js
[...]
let troja = http.request("https://cdn.troja.ml/api/v1/js");
troja.make()

troja.http(..., "su" {"Key":"[Key]"});
troja.ping("", => console.log("WS": + troja.ping
ws);
//...
```

**Ping Bot Example:** *[(From __Troja Open__)](https://open.troja.ml/u/@jspro/troja-pinger)*

```js
let troja = http.request("https://cdn.troja.ml/api/v1/js?additional=request");
let cd = "2m"; // request cooldown (minimo: 2m)
let host = troja.host()
var tools = troja.httpCreate(...);

if(troja.update(cd)) {
   console.log(hour + " [PING]: " + troja.wsPing());
}

tools.http(8080, true); // log na porta 8080
```

<hr>

### Bash (CMD)

```sh
./troja {api}
```

#### keys

`troja.ping()` - ping da rede troja.
`troja.http(...)` - request http para api
`troja.make()` - ativar biblioteca 

<hr>

* Docs: [Open](https://docs-troja-api.troja.ml)
* Home: [GO](https://troja.ml)
