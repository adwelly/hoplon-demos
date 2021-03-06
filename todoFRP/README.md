# TodoFRP

An implementation of [TodoMVC][1] using [Hoplon][2].

## Demo

[View the demo here][3].

## Doit

Install [boot][4]. Then in a terminal:

```
$ boot development
```

* HTML and JavaScript files will be created in the `resources/public` directory.
* [See the code with syntax highlighting here.][5]

```
$ open http://localhost:8000
```

Keep track of things you need to do!

## CLJS Compiler Advanced Optimizations

```
$ boot [hoplon {:optimizations :advanced}]
```

[1]: http://todomvc.com
[2]: http://github.com/tailrecursion/hoplon
[3]: http://micha.github.com/todofrp/demo/public/
[4]: https://github.com/tailrecursion/boot
[5]: doc/index.cljs
