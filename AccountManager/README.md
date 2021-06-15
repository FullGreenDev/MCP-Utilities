# Session Changer
Login to your Minecraft account inside of IDEA

Only work for mojang account

## How to use
Online Mode
```java
SessionChanger.getInstance().setUser("e-mail", "password");
```
Offline Mode
```java
SessionChanger.getInstance().setUserOffline("username");
```
## Notes
You will get a error when you paste this class in. I am not going to spoon feed you, but look at the hints your IDEA gives you! It will tell you exactly what the issue is. Hint: It is with Minecraft.getMinecraft().session variable
