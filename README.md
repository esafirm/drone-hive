# drone-hive
> Hive with all of the android drones

Companion repository for [drone](https://github.com/cesarferreira/drone)

## How to contribute?
Use the [drone](https://github.com/cesarferreira/drone) tool.

> $ drone create

and/or

create a file with the **hive/`username/repository`/info.json**

file: **hive/`username/repository`/info.json**
```json
{
  "name": "username/repository",
  "dependency": "com.username.library:library",
  "compileType": "compile",
  "repository": {
    "server": "jcenter"
  }
}
```

------------

### Real life example for `retrofit`:

file: **hive/`square/retrofit`/info.json**
```json
{
  "name": "square/retrofit",
  "description": "A type-safe HTTP client for Android and Java",
  "homepage": "http://square.github.io/retrofit/",
  "dependency": "com.squareup.retrofit2:retrofit",
  "repository": {
    "server": "jcenter"
  }
}
```

## Created by
[Cesar Ferreira](https://cesarferreira.com)

## License
MIT © [Cesar Ferreira](http://cesarferreira.com)
