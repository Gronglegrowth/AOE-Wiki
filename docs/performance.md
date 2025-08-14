# Game Performance

## Game Settings

If your game is struggling, try:

- Turning down ==Render Distance==
- Look into ==JVM args== (see next section)
- Giving it some more ==RAM==——but not so much GC pauses noticeably lengthen.

## Java and the JVM

### Which Java to Use?

| AOE Pack | Minecraft version | Java version (tied to MC version) |
|:-:|:-:|-|
| ***Craftoria*** | 1.21 | Java21 |
| **AOF 7** | 1.20 | Java17 (runs better on Java21) |
| **AOF 6** | 1.19 | Java17 |
| **AOF 5** | 1.18 | Java17 |
| **AOF 4** | 1.17 | Java17 |
| **AOF 3** | 1.16 | Java8  |

### Java Args

#### For Clients

Around 6–8GB should work well for any AOE modpacks.

| AOE Mod Pack   | Java Args for Client           |
|:--------------:|--------------------------------|
| ***Craftoria***|`-XX:+UseZGC -XX:+ZGenerational`|
| **AOF 7**      |`-XX:+UseZGC -XX:+ZGenerational`, with Java21|

#### For Servers

On a server GC through-put may be more valuable than latency—which the default `G1GC` garbage-collector will deliver.

---