# Website

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

## Documentation style guide

- Use headings appropriately! E.g. #, ## and ###
- Input examples shall be typed in quotes, e.g.:

    ```
    1) Fill in "Foo Bar"
    ```

    Becomes:
    
    1) Fill in "Foo Bar"

- Actionable pointers, without inputs, shall be made bold, e.g.:

    ```
    1) Click **Foo Bar**
    ```

    Becomes:
    
    1) Click **Foo Bar**

- So shall references, e.g.:

    ```
    1) Take note of **Foo Bar**
    ```

    Becomes:
    
    1) Take note of **Foo Bar**

- Ordered list items shall be prepended with `1)`, as they're automatically numbered and allow for re-ordering, e.g.:

    ```
    1) Foo

    1) Bar

    1) Baz
    ```

    Becomes:

    1) Foo

    1) Bar

    1) Baz

- Figures shall be annotated in the format:

  ```
  *Figure 1: Description*
  ```

  Becomes:

  *Figure 1: Description*

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

All pushes to **main** trigger a deployment. Remember, with great power comes great responsibility...
