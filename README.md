# Customizing ASP.NET Core 5.0

<a href="https://www.packtpub.com/product/customizing-asp-net-core-5-0/9781801077866"><img src="https://static.packt-cdn.com/products/9781801077866/cover/smaller" alt="Book Name" height="256px" align="right"></a>

This is the code repository for [Customizing ASP.NET Core 5.0](https://www.packtpub.com/product/customizing-asp-net-core-5-0/9781801077866), published by Packt.

**Turn the right screws in ASP.NET Core to get the most out of this framework**

## What is this book about?
ASP.NET Core is the most powerful web framework by Microsoft. Although it’s full of rich features, sometimes the default configurations can be a bottleneck and need to be customized to suit the nature and scale of your app. If you’re an intermediate-level .NET developer who wants to extend .NET Core to multiple use cases, it's important to customize the features so that the framework works for you effectively.

This book covers the following exciting features: 
* Explore various application configurations and providers in ASP.NET Core 5
* Understand dependency injection in .NET and learn how to add third-party DI containers
* Discover the concept of middleware and write your own middleware for ASP.NET Core apps
* Create various API output formats in your API-driven project
* Get familiar with different hosting models for your ASP.NET Core app

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/180107786X) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter01.

The code will look like the following:
```
public class Program
{
    public static void Main(string[] args)
    {
        CreateWebHostBuilder(args).Build().Run();
    }

    public static IWebHostBuilder CreateWebHostBuilder(string[] args) =>
        WebHost.CreateDefaultBuilder(args)
            .UseStartup<Startup>();
}

```

**Following is what you need for this book:**
This .NET 5 book is for .NET developers who need to change the default behaviors of the framework to help improve the performance of their applications. You should have basic knowledge of ASP.NET Core and C# before getting started with the bookCopy and paste the Audience section from the EPIC.

With the following software and hardware list you can run all code files present in the book (Chapter 1-13).

### Software and Hardware List

| Chapter  | Software required                   | OS required                        |
| -------- | ------------------------------------| -----------------------------------|
| 1-13     | .NET 5.0                            | Windows, Mac OS X, and Linux (Any) |
| 1-13     | .NET 3.1                            | Windows, Mac OS X, and Linux (Any) |
| 1-13     | Visual Studio code                  | Windows, Mac OS X, and Linux (Any) |
| 12       | Nginx or Apache webserver           | Linux                              |


### Related products <Other books you may enjoy>
* An Atypical ASP.NET Core 5 Design Patterns Guide [[Packt]](https://www.packtpub.com/product/an-atypical-asp-net-core-5-design-patterns-guide/9781789346091) [[Amazon]](https://www.amazon.com/dp/1789346096)

* ASP.NET Core 5 and React, Second Edition [[Packt]](https://www.packtpub.com/product/asp-net-core-5-and-react-second-edition/9781800206168) [[Amazon]](https://www.amazon.com/dp/180020616X)

## Get to Know the Author
**Jürgen Gutsch**
 is a .NET addicted web developer, working with ASP.NET since 2002. He is a Microsoft MVP for Developer Technologies, the leader of a .NET user group in Basel and of the INETA Germany. He works as a software developer, consultant, and trainer at YOO AG in Basel. Along with his family and job, he is presenting technical talks, writes articles for .NET magazines, and posts in his blog, titled ASP.NET Hacker.


### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781801077866">https://packt.link/free-ebook/9781801077866 </a> </p>