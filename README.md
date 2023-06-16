# MC

Esse repositório contêm minhas configurações compartilhadas entre os projetos


## PHPStan

Para usar as configurações instale os pacotes abaixo:

### Instalando o PHPStan

#### [PHPStan e libs oficiais](https://github.com/phpstan)
```shell
composer require --dev phpstan/phpstan
composer require --dev phpstan/extension-installer
composer require --dev phpstan/phpstan-deprecation-rules
composer require --dev phpstan/phpstan-strict-rules
```

### Libs da comunidade

[Disallowed calls for PHPStan](https://github.com/spaze/phpstan-disallowed-calls)
```shell
composer require --dev spaze/phpstan-disallowed-calls
```

[Symplify Rules](https://github.com/symplify/phpstan-rules)

```shell
composer require --dev symplify/phpstan-rules
```

[TheCodingMachine's Rules](https://github.com/thecodingmachine/phpstan-strict-rules)

```shell
composer require --dev thecodingmachine/phpstan-strict-rules
```

### Para projetos Laravel

#### [Larastan](https://github.com/nunomaduro/larastan)
```shell
composer require nunomaduro/larastan:^2.0 --dev
```

## PHP CodSniffer

### Instalando o PHP_CodeSniffer

```shell
composer require --dev squizlabs/php_codesniffer
```

### Lib da comunidade


[PHP_CodeSniffer Standards Composer Installer Plugin](https://github.com/PHPCSStandards/composer-installer)
```shell
composer require --dev dealerdirect/phpcodesniffer-composer-installer
```

[Slevomat Coding Standard](https://github.com/slevomat/coding-standard#installation)

```shell
composer require --dev slevomat/coding-standard
```

[PHPCSExtra](https://github.com/PHPCSStandards/PHPCSExtra)

```shell
composer require --dev phpcsstandards/phpcsextra:"^1.0"
```
## Prettier

### Instalando o Prettier

[Prettier](https://prettier.io/docs/en/install.html)

```shell
npm install --save-dev --save-exact prettier
```

## Eslint

### Instalando o Eslint
[Eslint](https://eslint.org/docs/latest/use/getting-started)

```shell
npm install --save-dev eslint
```

### Libs para projetos VueJS

[eslint-plugin-vue](https://eslint.vuejs.org/user-guide/)

```shell
npm install --save-dev eslint-plugin-vue
```

[@vue/eslint-config-typescript](https://www.npmjs.com/package/@vue/eslint-config-typescript)
```shell
npm add --dev @vue/eslint-config-typescript @rushstack/eslint-patch
```

### Com CyberPress
[Cypress ESLint Plugin](https://www.npmjs.com/package/eslint-plugin-cypress)
```shell
npm install eslint-plugin-cypress --save-dev
```

### Integração com o Prettier
[@vue/eslint-config-prettier](https://www.npmjs.com/package/@vue/eslint-config-prettier)
```shell
npm add --dev @vue/eslint-config-prettier @rushstack/eslint-patch
```


