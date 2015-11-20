# CoinChrome

Chrome extension to show the latest bitcoin price and your Coinbase portfolio's 24h change on Chrome's new tab.

Build using [Coinbase API](https://developers.coinbase.com/api/v2) and [Coinbase Connect (OAuth2)](https://developers.coinbase.com/docs/wallet/coinbase-connect).

## Development

If you want to run a development build, you need to create your own OAuth application on Coinbase because OAuth2 redirect URI is dependent on the Chrome extension ID which will be given to your application. Once you have created your own application, change `CLIENT_ID`, `CLIENT_SECRET` and `REDIRECT_URI` in `newtab.js`.

## License

MIT