# Danish Translations for Admin-on-rest

Danish translations for [admin-on-rest](https://github.com/marmelab/admin-on-rest), the frontend framework for building admin applications on top of REST services.

![admin-on-rest demo](http://static.marmelab.com/admin-on-rest.gif)

## Installation

```sh
npm install --save aor-language-danish
```

## Usage

```js
import danishMessages from 'aor-language-danish';

const messages = {
    'da': danishMessages,
};

<Admin locale="da" messages={messages}>
  ...
</Admin>
```

## License

This translation is licensed under the [MIT Licence](LICENSE).
