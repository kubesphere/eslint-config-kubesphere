# eslint-config-kubesphere

## Install

```sh
npx install-peerdeps --dev eslint-config-kubesphere
```

## Usage

In your `.eslintrc.js`:

```tsx
module.exports = {
  extends: ['kubesphere'],
  parserOptions: {
    project: './tsconfig.json',
  },
};
```

## License

MIT
