# FAQ

## Developer Preview
### Dev Torture Service
5 Keys are gifted every 6 hours https://asset.party/get/developer/preview

### Key Applications
Reply with a creative application that shows your interest

https://forum.facepunch.com/t/s-box-key-application-megathread/256711

## Game Information
### What engine does the game use?
S&Box uses a modified version of Source 2, based on the Half-Life: Alyx branch of the engine.

Early development was done in Unreal Engine 4, but this has been discontinued.

### VR Support
S&Box currently has basic VR support, but it's up to each individual game in terms of the actual implementation for this.

### How does the multiplayer work?
Multiplayer by default is done through Steam Networking and supports both listen and dedicated servers.

Alternative, if you provide your own solution with Websockets

[Find out more](../interactivity/programming/networking)

### Mounthing Source based Games
Mounting other Source-based games is neither possible nor planned.

## Content Creation
### Providing interactivity
To make the game interactive for players and vice verse, S&Box utilizes C#, supporting the latest [.NET 7](https://learn.microsoft.com/en-gb/dotnet/core/whats-new/dotnet-7) and the [C# Language Feature - 11](https://learn.microsoft.com/en-us/dotnet/csharp/whats-new/csharp-11)

### Providing UIs
Templating is done with [Razor](https://learn.microsoft.com/en-us/aspnet/core/mvc/views/razor?view=aspnetcore-7.0)

Which itself supports HTML and CSS, interactivity still is done with C#.

### Porting Source 1 Content
There are third-party tools you can use to port over Source 1 content, but no first-party support is currently available for porting.

:::tip

Only port over content that you have permission for!

:::