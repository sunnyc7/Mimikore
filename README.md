# Mimikore
.NET 5 Single file Application . Mimikatz or any Base64 PE Loader.

## Shout out to Benjamin Delpy I just wrapped the package :)

Nothing says love like a 35mb Mimkatz Binary.

Loads - 2.2.0 20210709 Printnightmare rewrited

### Steps to Build

1. Install dotnet, .NET 5 + SDK
2. Create a project `dotnet new console`
3. Copy Program.cs into that path.
4. `dotnet run`  // To test
5. `dotnet build`
6. I used this as well
    = [Tiny dotnet core apps](https://www.hanselman.com/blog/making-a-tiny-net-core-30-entirely-selfcontained-single-executable)
7. Or `dotnet publish -r win-x64 -c Release /p:PublishSingleFile=true /p:PublishTrimmed=true`

Just some experiments.  

Have fun out there kids.

![Screen Shot 2021-07-14 at 6 11 55 PM](https://user-images.githubusercontent.com/83469949/125717465-b797be03-5b3d-4ba6-9889-390777d4deb9.png)

