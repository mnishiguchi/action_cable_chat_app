# action_cable_chat_app

 [https://www.learnenough.com/action-cable-tutorial](https://www.learnenough.com/action-cable-tutorial)

## To get started:

```
bundle
rails db:migrate
rails db:seed
rails test
```

## Some info

#### HTTP vs WS

```
HTTP       - half-duplex communication between client and server
Web socket - full-duplex communication between client and server
```

#### Web socket(ws)
- HTTP + polling (pulling in any changes every few seconds.) works fine but:
  + ws is even better as long as it is not too hard
  + ws scales better with multiple users

#### Action cable
- Allows us to implement web socket easily
- Gives up the best of both worlds:
  + real-time, full-duplex communications with WebSockets
  + all the convenience and flexibility of Rails
