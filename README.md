# ShadUI Stack

The Remix Stack with shadui setup.

📖 See the [Remix docs](https://remix.run/docs) and the [Remix Vite docs](https://remix.run/docs/en/main/guides/vite) for details on supported features.

## Development

Run the Express server with Vite dev middleware:

```shellscript
npm run dev
```

## Deployment

First, build your app for production:

```sh
npm run build
```

Then run the app in production mode:

```sh
npm start
```

Now you'll need to pick a host to deploy it to.

### DIY

If you're familiar with deploying Express applications you should be right at home. Just make sure to deploy the output of `npm run build`

- `build/server`
- `build/client`
