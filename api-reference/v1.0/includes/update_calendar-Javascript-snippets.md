
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const calendar = {
  name: "Social events"
};

let res = await client.api('/me/calendar')
	.update({calendar : calendar});

```