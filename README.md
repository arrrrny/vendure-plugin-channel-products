<!-- ZURAFFA-LAUNCH-PROMO (valid until Dec 1, 2026) -->
## 🦒 [Zuraffa Browser](https://zuraffa.com) — now live

<div align="center">
  <a href="https://zuraffa.com"><img src="https://zuraffa.com/img/zuraffa-browser-home.jpg" alt="Zuraffa Browser — 10 Browsers. One window." width="800"></a>
</div>

**[Zuraffa Browser](https://zuraffa.com)** — the multi-tasking browser for AI agents & humans — is live on the [Mac App Store](https://apps.apple.com/app/id6811352058).

🎁 **Launch offer: 6 months free with code `ZURAFFA`** — no credit card, no subscription, no payment. Redeem in-app until **Dec 1, 2026**.

---

# Vendure plugin template

1. Copy this directory and rename to `vendure-plugin-YOUR-PLUGIN-NAME`
2. Update the `name` and `description` field in `package.json`
3. Update this Readme: What does the plugin do? How can someone use your plugin in their project?
4. Run `npm install` to install the dependencies
5. Run `npm run start` to start the server

The admin is now available at `http://localhost:3050/admin`. Login with _superadmin/superadmin_

The shop GraphQL `http://localhost:3050/shop-api`. Here you can test your custom GraphQL query:
```graphql
{
  exampleQuery
}
```

## Testing

1. Run `npm run test` to run the e2e test.
2. Don't forget to implement your own!

## Publishing to NPM

1. Make sure you are [logged in to NPM](https://docs.npmjs.com/cli/v9/commands/npm-login)
2. `npm run build`
3. `npm publish`

That's it!

(Maybe share your accomplishments in the [Vendure Discord](https://vendure.io/community)?

## Next steps

1. Check out [the docs](https://docs.vendure.io/guides/developer-guide/plugins/) to see the possibilities of a plugin
2. Check out [GraphQL codegen](https://the-guild.dev/graphql/codegen) to generate Typescript types for your custom GraphQL types
