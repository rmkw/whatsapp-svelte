# whatsapp-svelte
![svelte.gif](https://github.com/anhsirk0/whatsapp-svelte/blob/master/screenshot/screenshot.gif)

This is a WhatsApp Mockup window that you can use to create fake welcome/notification messages.

## Usage
Use Sidebar to update/delete messages/users  

OR  

There are 2 components `ReceivedMessage` and `SentMessage`  
You can create You message via `<ReceivedMessage text="Hi there" time="3:14 PM" />`  
Add `first={true}` if it is the first message (it will display a trianglular shape at one corner of the chat bubble)  


## Running the server
Once you've installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev
```

