# Product Watcher

It's a simple script that use Discord.js library to send webhooks in a discord server when Creatina from Growth Suplementos is available.

## Compatibility

- Linux
- Mac

## Installing

Rename ```example.env``` to ```.env``` and add your webhook link in ***DISCORD_WEBHOOK_URI***. To a guide for knowing how to get the webhook link. [Click Here](https://github.com/JVmano/product-watcher/wiki/How-to-get-a-webhook-link).


Using NPM:

```npm install```

Using YARN:

```yarn```

## Usage

To edit the product list you'll need to edit the ```ìndex.js``` file and for each product link that will be monitored you 'll need to call the function ```getProducts```.

Finally just execute the command the start command to initiate the monitor:

```yarn start```

or

```npm run start```

## Contributing

1. Fork the repository
2. Create a new branch like feat/feature_name
3. Execute a push in the branch
4. Create a pull request
