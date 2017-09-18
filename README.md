# dynamicform
a client-side dynamic form generator

This library enables adding forms with a custom HTML tag '<dynamicform>'. This tag needs an 'id' attribute and 'data-json' attribute includes path of related form JSON file. There is an example HTML file in repo.

### There is an example usage below:
```
<dynamicform id="form1" data-json="../forms/form1.json"></dynamicform>
```

This JSON file includes the structure of the related form. There is an example JSON file in repo.

There are two versions of this library:
1) JQuery version
2) Pure JavaScript version

* Minified files are also available

## Contributing
Any contribution, suggestion or comment is more than welcome.

## Author
* **Halil Can Ozcelik** - *Initial work* - [hcoz](https://github.com/hcoz)

## License
This project is licensed under the Apache License - see the [LICENSE.md](LICENSE.md) file for details
