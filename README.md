# readme engine

### Events

Event    | Description
:------------- | :-------------
connect  | emits when a connection is established to the Redis server.
ready    | emits when `CLUSTER INFO` reporting the cluster is able to receive commands (if `enableReadyCheck` is `true`) or immediately after `connect` event (if `enableReadyCheck` is false).
error    | emits when an error occurs while connecting with a property of `lastNodeError` representing the last node error received. This event is emitted silently (only emitting if there's at least one listener).
close    | emits when an established Redis server connection has closed.
reconnecting | emits after `close` when a reconnection will be made. The argument of the event is the time (in ms) before reconnecting.
end     | emits after `close` when no more reconnections will be made.
+node   | emits when a new node is connected.
-node   | emits when a node is disconnected.
node error | emits when an error occurs when connecting to a node


# Contributors
<table>
 <tr>
    <td width="20%"><a href="https://github.com/"><img src="https://avatars3.githubusercontent.com/u/5814507?v=4" /></a><p align="center">code</p></td>
    <td width="20%"><a href="https://github.com/"><img src="https://avatars3.githubusercontent.com/u/5814507?v=4" /></a><p align="center">code</p></td>
    <td width="20%"><a href="https://github.com/"><img src="https://avatars3.githubusercontent.com/u/5814507?v=4" /></a><p align="center">code</p></td>
    <td width="20%"><a href="https://github.com/"><img src="https://avatars3.githubusercontent.com/u/5814507?v=4" /></a><p align="center">code</p></td>
    <td width="20%"><a href="https://github.com/"><img src="https://avatars3.githubusercontent.com/u/5814507?v=4" /></a><p align="center">code</p></td>
  </tr>
  <tr>
    <td width="20%"><a href="https://github.com/"><img src="https://avatars3.githubusercontent.com/u/5814507?v=4" /></a><p align="center">code</p></td>
    <td width="20%"><a href="https://github.com/"><img src="https://avatars3.githubusercontent.com/u/5814507?v=4" /></a><p align="center">code</p></td>
    <td width="20%"><a href="https://github.com/"><img src="https://avatars3.githubusercontent.com/u/5814507?v=4" /></a><p align="center">code</p></td>
    <td width="20%"><a href="https://github.com/"><img src="https://avatars3.githubusercontent.com/u/5814507?v=4" /></a><p align="center">code</p></td>
    <td width="20%"><a href="https://github.com/"><img src="https://avatars3.githubusercontent.com/u/5814507?v=4" /></a><p align="center">code</p></td>
  </tr>
</table>
