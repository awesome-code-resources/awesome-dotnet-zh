如果您觉得这个项目对您有帮助，就请点右上角的**Star**按钮为它加星星✨✨ 其他TIOBE Top 20编程语言的中文翻译请看[awesome-code-resources](https://github.com/awesome-code-resources/awesome-code-resources)。
# 太棒了.NET核心[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

灵感来自[awesome](https://github.com/sindresorhus/awesome),[awesome-dotnet](https://github.com/quozd/awesome-dotnet),[awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs),[frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks)。

捐款总是受欢迎的!请看一下[contribution guidelines](https://github.com/thangchung/awesome-dotnet-core/blob/master/contributing.md)第一页。我们也接受专有和商业软件。

感谢所有[contributors](https://github.com/thangchung/awesome-dotnet-core/graphs/contributors),你Awesome ，没有你是不可能的!目标是建立一个分类的社区驱动的非常知名的资源集合。

查看我的[blog](https://medium.com/@thangchung)或者打个招呼[Twitter](https://twitter.com/thangchung)!

## 内容

* [概述](#概述)
* [框架、库和工具](#框架、库和工具)
  * [API](#API)
  * [应用程序框架](#应用程序框架)
  * [应用程序模板](#应用程序模板)
  * [身份验证和授权](#身份验证和授权)
  * [区块链](#区块链)
  * [Bot](#Bot)
  * [构建自动化](#构建自动化)
  * [捆绑和缩小](#捆绑和缩小)
  * [缓存](#缓存)
  * [CMS](#CMS)
  * [代码分析和度量](#代码分析和度量)
  * [压缩](#压缩)
  * [编译器、转译器和语言](#编译器、转译器和语言)
  * [密码学](#密码学)
  * [数据库](#数据库)
  * [数据库驱动程序](#数据库驱动程序)
  * [数据库工具和实用程序](#数据库工具和实用程序)
  * [日期和时间](#日期和时间)
  * [分布式计算](#分布式计算)
  * [电子商务和支付](#电子商务和支付)
  * [例外情况](#例外情况)
  * [函数式编程](#函数式编程)
  * [图形](#图形)
  * [图形用户界面](#图形用户界面)
  * [IDE](#IDE)
  * [国际化](#国际化)
  * [国际奥委会](#国际奥委会)
  * [日志记录](#日志记录)
  * [机器学习和数据科学](#机器学习和数据科学)
  * [邮件](#邮件)
  * [数学](#数学)
  * [媒体](#媒体)
  * [联网](#联网)
  * [杂类](#杂类)
  * [办公室](#办公室)
  * [ORM](#ORM)
  * [剖析](#剖析)
  * [队列和消息传递](#队列和消息传递)
  * [查询生成器](#查询生成器)
  * [调度程序和作业](#调度程序和作业)
  * [SDKs](#SDKs)
  * [安全](#安全)
  * [正在搜索](#正在搜索)
  * [序列化](#序列化)
  * [模板引擎](#模板引擎)
  * [测试](#测试)
  * [工具](#工具)
  * [Web框架](#Web框架)
  * [Web套接字](#Web套接字)
  * [Windows服务](#Windows服务)
  * [工作流](#工作流)
* [路线图](#路线图)
* [初学者工具包](#初学者工具包)
* [示例项目](#示例项目)
* [文章](#文章)
* [图书](#图书)
* [视频](#视频)
* [播客](#播客)
* [社区](#社区)
## 概述

* [ASP.NET Core Documentation](https://docs.asp.net/en/latest/)-官方ASP.NET Core文档站点。
* [.NET Core Documentation](https://docs.microsoft.com/en-us/dotnet/articles/welcome)-技术文档的主页。NET Core、C # 、F # 和Visual Basic，包括基本概念、入门说明、教程和示例。
* [.NET Core SDK](https://www.microsoft.com/net/core)-什么？-.NET Core SDK是由Microsoft和.NET社区上[GitHub](https://github.com/dotnet/core)。
* [.NET Platform Standard](https://github.com/dotnet/corefx/blob/1719a3fe2a5c81b67a4909787da4a02fb0d0d419/Documentation/architecture/net-platform-standard.md)-旧版本与新版本之间的差异。NET。
* [Introducing .NET Standard 2.0](https://blogs.msdn.microsoft.com/dotnet/2016/09/26/introducing-net-standard)-对将要发生的事情的描述。NET标准2.0和路线图的一些缺失部分的当前。NET标准。
* [Clean Code .NET/.NET Core](https://github.com/thangchung/clean-code-dotnet)-适用于干净的代码概念。净/。NET核心。
## 框架、库和工具

### API

* [autorest](https://github.com/Azure/autorest)-Swagger (OpenAPI) 规范代码生成器具有C # 和Razor模板。支持C #，Java，Node.js，TypeScript，Python和Ruby。
* [aspnet-api-versioning](https://github.com/Microsoft/aspnet-api-versioning)-一组库，这些库将服务API版本控制添加到ASP.NET Web API，带有ASP.NET Web API的OData和ASP.NET Core。
* [AspNetCoreRateLimit](https://github.com/stefanprodan/AspNetCoreRateLimit)-ASP.NET Core速率限制中间件。
* [CondenserDotNet](https://github.com/Drawaes/CondenserDotNet)-使用Kestrel和Consul的API冷凝器/反向代理，包括轻量级consul库。
* [Flurl](https://github.com/tmenier/Flurl)-流利的URL生成器和可测试的HTTP。净值[https://flurl.dev](https://flurl.dev)。
* GraphQL
  * [Dapper.GraphQL](https://github.com/landmarkhw/Dapper.GraphQL)-一个旨在集成Dapper和graphql-dotnet项目的库，以易于使用和性能为主要关注点。
  * [graphql-aspnetcore](https://github.com/JuergenGutsch/graphql-aspnetcore)-用于创建GraphQL端点的ASP.NET Core中间件。
  * [graphql-convention](https://github.com/graphql-dotnet/conventions)-此库是顶部的补充层，可让您自动包装。使用现有属性getter和方法作为字段解析器将NET类转换为GraphQL架构定义
  * [graphiql-dotnet](https://github.com/JosephWoodward/graphiql-dotnet)-用于ASP.NET Core的GraphiQL中间件。
  * [graphql-dotnetcore](https://github.com/mkmarek/graphql-dotnetcore)-GraphQL for.NET Core基于[https://github.com/graphql/graphql-js](https://github.com/graphql/graphql-js)。
  * [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet)-GraphQL for.NET。
  * [graphql-dotnet-server](https://github.com/graphql-dotnet/server)-GraphQL for.NET-订阅传输WebSockets。
  * [Hot Chocolate](https://github.com/ChilliCream/hotchocolate)-用于的GraphQL服务器。Net核心和。NET框架。
  * [FSharp.Data.GraphQL](https://github.com/fsprojects/FSharp.Data.GraphQL)-Facebook GraphQL查询语言的FSharp实现[https://fsprojects.github.io/FSharp.Data.GraphQL](https://fsprojects.github.io/FSharp.Data.GraphQL)。
  * [parser](https://github.com/graphql-dotnet/parser)-中的GraphQL的词法分析器和解析器。NET。
  * [tanka-graphql](https://github.com/pekkah/tanka-graphql)-GraphQL执行和服务器库，支持SignalR，Apollo，模式操作以及Apollo和graphql-js熟悉的其他功能
* [halcyon](https://github.com/visualeyes/halcyon)-ASP.NET的HAL实现。
* [JSON API .NET Core](https://github.com/Research-Institute/json-api-dotnet-core)-用于构建json的框架: 符合api的api，目标是消除RESTful样板。
* [LightNode](https://github.com/neuecc/LightNode)-基于OWIN构建的微RPC/REST框架[http://neuecc.github.io/LightNode](http://neuecc.github.io/LightNode)。
* [NetCoreStack.Proxy](https://github.com/NetCoreStack/Proxy)-的类型安全的分布式REST库。NET标准2.0 (NetCoreStack飞行代理)
* [NSwag](https://github.com/RSuter/NSwag)-Swagger/OpenAPI工具链。NET、Web API和TypeScript。[http://NSwag.org](http://NSwag.org)。
* [OData](https://github.com/OData/WebApi/tree/feature/netcore)-开放数据协议 (OData) 支持创建基于HTTP的数据服务，该服务允许使用统一资源标识符 (uri) 标识并在抽象数据模型中定义的资源由Web客户端使用简单的HTTP消息发布和编辑。
* [OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator)-OpenAPI Generator允许生成API客户端库 (例如C #，TypeScript等)，服务器存根 (ASP.NET Core，NancyFx等)，文档和配置自动给定OpenAPI规范 (v2，v3)。
* [refit](https://github.com/paulcbetts/refit)-Xamarin的自动类型安全REST库和.NET。
* [RestClient.Net](https://github.com/MelbourneDeveloper/RestClient.Net)-适用于所有C # 平台的跨平台REST客户端
* [RestEase](https://github.com/canton7/RestEase)-易于使用的类型安全REST API客户端库，简单且可定制。
* [RestLess](https://github.com/letsar/RestLess)-的自动类型安全无反射REST API客户端库。Net标准。
* [Restier](https://github.com/OData/RESTier)-RESTier是一个RESTful API开发框架，用于在.NET平台。
* [Restsharp](https://github.com/restsharp/RestSharp)-简单的REST和HTTP API客户端。净值
* [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)-无缝添加一个swagger到WebApi项目。
  * [MicroElements.Swashbuckle.FluentValidation](https://github.com/micro-elements/MicroElements.Swashbuckle.FluentValidation)-将FluentValidation规则添加到swagger。
  * [Swashbuckle.AspNetCore.Filters](https://github.com/mattfrear/Swashbuckle.AspNetCore.Filters)-一堆有用的过滤器的Swashbuckle.AspNetCore。
* [WebAnchor](https://github.com/mattiasnordqvist/Web-Anchor)-Web Anchor提供对web资源的类型安全，可测试且灵活的运行时生成的访问。
* [WebAPIContrib for ASP.NET CORE](https://github.com/WebApiContrib/WebAPIContrib.Core)-ASP.NET Core的社区贡献。
### 应用程序框架

* [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate)ASP.NET Boilerplate是一个通用的应用程序框架，专门为新的现代web应用程序设计。它使用已经熟悉的工具，并围绕它们实施最佳实践，为您提供可靠的开发体验。
* [Abp vNext](https://github.com/abpframework/abp)-Abp vNext是开源的下一代[ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate)框架。它是一个完整的体系结构和强大的基础设施，用于创建现代web应用程序!遵循最佳实践和惯例，为您提供坚实的开发体验。
* [AsyncEx](https://github.com/StephenCleary/AsyncEx)-async/await的帮助程序库。
* [Aeron.NET](https://github.com/AdaptiveConsulting/Aeron.NET)-高效可靠的UDP单播，UDP多播和IPC消息传输-。Aeron的净端口。
* [akka.net](https://github.com/akkadotnet/akka.net)-用于在上构建高度并发，分布式和容错的事件驱动应用程序的工具包和运行时。净和单声道。
* [Aggregates.NET](https://github.com/volak/Aggregates.NET)-Aggregates.NET是一个帮助开发人员将优秀的NServiceBus和EventStore库集成在一起的框架。
* [ASP.NET MVC](https://github.com/dotnet/aspnetcore/tree/master/src/Mvc)-模型视图控制器框架，用于构建动态网站，具有清晰的关注点分离，包括合并的MVC，web API和Web页面w/ Razor。
* [Butterfly Server .NET](https://github.com/firesharkstudios/butterfly-server-dotnet)-允许以最小的努力构建实时web应用程序和本机应用程序。定义可跨连接的客户端自动同步数据集的Web API和订阅API。
* [CAP](https://github.com/dotnetcore/CAP)-具有本地持久消息功能的EventBus，用于SOA或微服务架构中的系统集成。
* [Carter](https://github.com/CarterCommunity/Carter)-Carter是一个允许Nancy式路由与ASP.Net Core一起使用的库。
* [Chromely](https://github.com/mattkol/Chromely)-Electron.NET的轻量级替代品，Electron for.NET/.NET Core。
* [Cinchoo ETL](https://github.com/Cinchoo/ChoETL)-的ETL框架。NET (CSV，平面，Xml，JSON，键值格式文件的解析器/写入器)。
* [CQRSlite](https://github.com/gautema/CQRSlite)-轻量级框架，用于帮助在C # 中编写CQRS和Eventsourcing应用程序。
* [dataaccess_aspnetcore](https://github.com/digipolisantwerp/dataaccess_aspnetcore)-DataAccess工具箱包含ASP.NET Core中使用工作单元和存储库模式1.0的数据访问的基类。
* [DNTFrameworkCore](https://github.com/rabbal/DNTFrameworkCore)-轻量级和可扩展的基础设施，用于构建基于ASP.NET Core的高质量Web应用程序。
* [DotNetCorePlugins](https://github.com/natemcmaster/DotNetCorePlugins)-什么？-.NET Core库作为插件加载程序集。
* [DotnetSpider](https://github.com/dotnetcore/DotnetSpider)-DotnetSpider, a.NET标准网络抓取库类似于WebMagic和Scrapy。它是一个轻量级，高效和快速的高级web抓取和抓取框架。NET。
* [DotNetty](https://github.com/Azure/DotNetty)netty的端口，事件驱动的异步网络应用框架。
* [dotvvm](https://github.com/riganti/dotvvm)-用于Web应用程序的开源MVVM框架。
* [ElectronNET](https://github.com/ElectronNET/Electron.NET)-使用ASP.NET NET Core构建跨平台桌面应用程序。
* [EmbedIO](https://github.com/unosquare/embedio)-一个微小的，跨平台的，基于模块的web服务器。NET框架和.NET核心。
* [Ether.Network](https://github.com/aloisdg/Ether.Network)Ether.Network是一个开源网络库，允许开发人员通过TCP/IP协议创建简单，快速和可扩展的套接字服务器或客户端应用程序。
* [EventFlow](https://github.com/eventflow/EventFlow)-异步/等待第一个CQRS ES和DDD框架。NET。
* [ExcelDataReader](https://github.com/ExcelDataReader/ExcelDataReader)-用C # 编写的用于读取Microsoft Excel文件的轻量级和快速库。
* [ExtCore](https://github.com/ExtCore)-免费，开源和跨平台框架，用于基于ASP.NET Core 1.0创建模块化和可扩展的web应用程序。
* [Finbuckle.MultiTenant](https://github.com/Finbuckle/Finbuckle.MultiTenant)-Finbuckle多租户是a.NET标准库，用于为ASP.NET 2.0设计的多租户支持。它提供租户解析、每个租户应用配置和每个租户数据隔离的功能。
* [fission](https://github.com/fission/fission)-Kubernetes的快速无服务器功能。
* [grpc](https://github.com/grpc/grpc/tree/master/src/csharp)-远程过程调用 (rpc) 为构建分布式应用程序和服务提供了有用的抽象。此存储库中的库提供了gRPC协议的具体实现，在HTTP/2上分层。这些库允许使用支持的语言的任意组合在客户端和服务器之间进行通信。
* [Halibut](https://github.com/OctopusDeploy/Halibut)-一个安全的通信堆栈。NET使用json-rpc通过SSL。
* [MagicOnion](https://github.com/neuecc/MagicOnion)-基于gRPC的HTTP/2 RPC流框架。NET，。NET核心和统一。
* [MassTransit](https://github.com/MassTransit/MassTransit)-分布式应用程序框架。NET。
* [microdot](https://github.com/gigya/microdot)-一个开源的。NET微服务框架。
* [MoreLINQ](https://github.com/morelinq/MoreLINQ)-LINQ to Objects的扩展。
* [Nancy](https://github.com/NancyFx/Nancy)-轻量级，低仪式，用于构建基于HTTP的服务的框架。NET和Mono。
* [opencvsharp](https://github.com/shimat/opencvsharp)-什么？-.NET框架包装的OpenCV。
* [orleans](https://github.com/dotnet/orleans)-框架，它提供了一种直接的方法来构建分布式的大规模计算应用程序，而无需学习和应用复杂的并发或其他扩展模式。
* [Prism](https://github.com/PrismLibrary/Prism)Prism是一个框架，用于在WPF、Windows 10 UWP和Xamarin表单中构建松散耦合、可维护和可测试的XAML应用程序。
* [protoactor-dotnet](https://github.com/AsynkronIT/protoactor-dotnet)-用于Golang和C # 的超快速分布式演员[http://proto.actor](http://proto.actor)。
* [resin](https://github.com/kreeben/resin)-具有HTTP API和可插拔读/写管道的16位宽矢量空间搜索引擎。
* [RService.io](https://github.com/Stoom/RService.IO)-ASP.Net Core RESTful微服务框架，专注于速度和易用性。
* [ServiceStack](https://github.com/ServiceStack/ServiceStack)-周到的架构，淫秽的快速，彻底愉快的web服务为所有人[https://servicestack.net](https://servicestack.net)。
* [Steeltoe OSS](https://github.com/SteelToeOSS)-什么？-.NET toolkit，用于常见的微服务模式。
* [Strathweb.TypedRouting.AspNetCore](https://github.com/filipw/Strathweb.TypedRouting.AspNetCore)-在ASP.NET Core MVC项目中启用强类型路由的库。
* [surging](https://github.com/dotnetcore/surging)-Surcing是一个微服务引擎，它提供了一个轻量级，高性能，模块化的RPC请求管道。服务引擎支持http、TCP、WS、Mqtt、UDP和DNS协议。它使用ZooKeeper和Consul作为注册表，哈希算法，随机，轮询，压力最小优先级作为负载均衡算法，内置服务治理，以确保可靠的RPC通信。
* [Xer.Cqrs](https://github.com/jeyjeyemem/Xer.Cqrs)-一个简单的库，用于创建基于CQRS模式的应用程序，支持属性路由和托管处理程序。在C # 中开发的目标。NET标准1.0。
* [X.PagedList](https://github.com/dncuug/X.PagedList)-通过ASP.NET/ASP.NET Core中的任何IEnumerable/IQueryable轻松分页的库。
### 应用程序模板

* [.NET Boxed](https://github.com/Dotnet-Boxed/Templates)-包含电池的项目模板，提供让您前进所需的最少代码。包括ASP.NET Core API和GraphQL模板。
* [aspnet-core-react-template](https://github.com/bradymholt/aspnet-core-react-template)-ASP.NET Core 2.0 / React SPA模板应用程序。
* [AspNetCoreSpa](https://github.com/asadsahi/AspNetCoreSpa)-Asp.Net Core 2和Angular 6 SPA与Angular CLI功能齐全的应用程序。
* [ASP.NET-MVC-Template](https://github.com/NikolayIT/ASP.NET-MVC-Template)-用于ASP.NET MVC 5和ASP.NET Core的现成可用模板，其中包含存储库，服务，模型映射以及DI和StyleCop警告已修复。
* [AddFeatureFolders](https://github.com/OdeToCode/AddFeatureFolders)-为ASP.NET Core中的MVC控制器和视图启用功能文件夹。
* [Angular Visual Studio Webpack Starter](https://github.com/damienbod/AngularWebpackVisualStudio)-Webpack，Visual Studio，ASP.NET Core和Angular的模板。应用程序的客户端和服务器端都在一个ASP.NET Core项目中实现，这使其更易于部署。
* [CleanArchitecture](https://github.com/ardalis/CleanArchitecture)-使用ASP.NET Core的干净体系结构的起点。Clean Architecture只是一系列名称中的最新名称，用于相同的松散耦合，依赖倒置的体系结构。您还会发现它被命名为六角形，端口和适配器或洋葱体系结构。
* [CleanArchitecture (SPA)](https://github.com/JasonGT/CleanArchitecture)-使用Angular 8和ASP.NET Core 3创建单页应用程序 (SPA) 的解决方案模板，遵循清洁架构的原则
* [DNTFrameworkCoreTemplate](https://github.com/rabbal/DNTFrameworkCoreTemplate)-基于Boilerplate项目模板[DNTFrameworkCore](https://github.com/rabbal/DNTFrameworkCore)
* [dotnet new caju](https://github.com/ivanpaulovich/dotnet-new-caju)-dotnet新模板与Awesome 建筑风格!提高生产率，以基于六边形，干净或事件采购架构样式设计分层应用程序。它支持多个数据访问框架 (MongoDB，EntityFramework，Dapper或Kafka)，并且它是完全可测试的。
* [EISK](https://github.com/EISK/eisk.webapi)-提供具有简单用例的开发人员资源，以在之上构建可扩展的应用程序。NET Core与[architectural best practices](https://docs.microsoft.com/en-us/dotnet/standard/modern-web-apps-azure-architecture/common-web-application-architectures)(DDD，洋葱建筑等)
* [JavaScriptServices](https://github.com/aspnet/JavaScriptServices)-Microsoft ASP.NET Core JavaScript服务。
* [kendo-ui-core](https://github.com/telerik/kendo-ui-core)-一个HTML5，基于jQuery的小部件库，用于构建现代web应用程序。[http://www.telerik.com/kendo-ui](http://www.telerik.com/kendo-ui)。
* [QuickApp](https://github.com/emonney/QuickApp)-ASP.NET Core/Angular4启动项目模板，具有完整的登录，用户和角色管理。
* [Serenity](https://github.com/volkanceylan/Serenity)-Serenity是一个ASP.NET MVC/TypeScript应用程序平台，旨在通过基于服务的体系结构简化和缩短以数据为中心的业务应用程序的开发。
* [Toucan](https://github.com/mrellipse/toucan)-用于构建单页应用程序的样板。服务器是多项目的。Net核心解决方案围绕坚实原则设计。客户端是TypeScript 2，Vuejs 2，Vuex 2。
### 身份验证和授权

* [AspNet.Security.OpenIdConnect.Server](https://github.com/aspnet-contrib/AspNet.Security.OpenIdConnect.Server)-用于OWIN/Katana和ASP.NET Core的OpenID Connect/OAuth2服务器框架。
* [Auth0](https://github.com/auth0/auth0.net)-用于现代身份识别的企业级托管平台。
* [Casbin.NET](https://github.com/casbin-net/Casbin.NET)-授权库，支持C # 中的ACL，RBAC，ABAC等访问控制模型
* [Identity](https://github.com/aspnet/Identity)ASP.NET Core Identity是用于构建ASP.NET Core web应用程序的成员资格系统，包括成员资格、登录和用户数据。
* [IdentityServer](https://github.com/IdentityServer/IdentityServer4)-用于ASP.NET核心1.0和2.0的IdentityServer
  * [IdentityServer4.EntityFramework](https://github.com/IdentityServer/IdentityServer4.EntityFramework)-EntityFramework持久层
  * [IdentityServer4.MongoDB](https://github.com/diogodamiani/IdentityServer4.MongoDB)-MongoDB持久层
  * [IdentityServer4.EntityFrameworkCore](https://github.com/2020IP/TwentyTwenty.IdentityServer4.EntityFrameworkCore)-实体框架核心持久层
  * [IdentityServer4.Templates](https://github.com/IdentityServer/IdentityServer4.Templates)-Identityserver4的dotnet cli模板。
* [Okta](https://github.com/okta/okta-aspnet)-用于现代身份识别的企业级托管平台。
* [openiddict](https://github.com/openiddict/openiddict-core)-用于ASP.NET Core的易于使用的OpenID连接服务器。
  * [oidc-debugger](https://github.com/nbarbettini/oidc-debugger)-OAuth 2.0和OpenID连接调试工具。
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet)-构建[simple, secure web applications](https://github.com/stormpath/stormpath-aspnetcore)使用Stormpath和ASP.NET Core。
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet)-构建[simple, secure web applications](https://github.com/stormpath/stormpath-aspnetcore)使用Stormpath和ASP.NET Core。(已弃用: 加入OKTA后，它将在2017年3月更新)
* [stuntman](https://github.com/ritterim/stuntman)-用于在开发过程中利用ASP.NET身份模拟用户的库。
### 区块链

* [BTCPayServer](https://github.com/btcpayserver/btcpayserver)-与Bitpay API兼容的跨平台自托管服务器。
* [Meadow](https://github.com/MeadowSuite/Meadow)-一个集成的以太坊实现和工具套件，专注于Solidity测试和开发。
* [NBitcoin](https://github.com/MetacoSA/NBitcoin)-全面的比特币库。NET框架。
* [NBlockchain](https://github.com/danielgerlag/NBlockchain)-什么？-.NET标准库，用于构建支持区块链的应用程序
* [NBXplorer](https://github.com/dgarage/NBXplorer)-一个比特币和Altcoin轻量级块资源管理器。
* [NEO](https://github.com/neo-project/neo)-智能经济的开放网络。
* [Nethereum](https://github.com/Nethereum)-将对以太坊的热爱带入。NET。
* [Nethermind](https://github.com/NethermindEth/nethermind)-什么？-.NET Core以太坊客户端
* [StratisBitcoinFullNode](https://github.com/stratisproject/StratisBitcoinFullNode)-简单且经济实惠的端到端解决方案，用于开发，测试和部署本机C # 区块链应用程序。Net框架。
* [Trezor.Net](https://github.com/MelbourneDeveloper/Trezor.Net)-用于与Trezor Hardwarewallet交谈的跨平台C # 库
* [WalletWasabi](https://github.com/zkSNACKs/WalletWasabi)-注重隐私，ZeroLink兼容比特币钱包。
### Bot

* [BotSharp](https://github.com/SciSharp/BotSharp)-100% C # 中运行的开源AI聊天机器人平台构建器。NET Core与机器学习算法。
* [NadekoBot](https://github.com/Kwoth/NadekoBot)-用C # 编写的开源，通用的Discord聊天机器人。
* [Telegram.Bot](https://github.com/TelegramBots/Telegram.Bot)-C # 电报机器人API库。
* [Funogram](https://github.com/Dolfik1/Funogram)-F # 电报机器人Api库。
### 构建自动化

* [cake-build](https://github.com/cake-build/cake)-跨平台构建自动化系统。
* [CatLight](https://catlight.io)-状态通知器，用于监视项目中的构建和任务的开发人员。使用。净核和电子。
* [Colorful.Console](https://github.com/tomakita/Colorful.Console)-风格你的C # 控制台输出!
* [dotnet-docker](https://github.com/dotnet/dotnet-docker)-用于的基本Docker映像。NET Core和.NET Core工具。
* [Dockerize.NET](https://github.com/brthor/Dockerize.NET)-什么？-.NET Cli工具打包您的.NET Core应用程序转换为docker映像: 'dotnet dockerize'
* [FlubuCore](https://github.com/dotnetcore/FlubuCore)-跨平台构建和部署自动化系统，用于使用C # 代码构建项目和执行部署脚本。
* [GitInfo](https://github.com/kzu/GitInfo)-来自MSBuild，C # 和VB的Git和SemVer信息。
* [GitVersioning](https://github.com/AArnott/Nerdbank.GitVersioning)-使用来自单个简单version.txt文件的版本标记您的程序集和NuGet包，并包含git提交id用于非官方构建。
* [go-dotnet](https://github.com/matiasinsaurralde/go-dotnet)-去包装。NET Core运行时。
* [Image2Docker](https://github.com/docker/communitytools-image2docker-win)-PowerShell模块，该模块将现有的Windows应用程序工作负载移植到Docker。
* [LocalAppVeyor](https://github.com/joaope/LocalAppVeyor)-在本地运行appvayor构建。
* [msbuild](https://github.com/Microsoft/msbuild)-Microsoft Build Engine是用于构建应用程序的平台。
* [Nuke](https://github.com/nuke-build/nuke)-跨平台构建自动化系统。
* [Opserver](https://github.com/opserver/Opserver)-Stack Exchange的监控系统。
* [vsts-agent](https://github.com/Microsoft/vsts-agent/blob/master/README.md)-Visual Studio Team Services生成和发布代理。
### 捆绑和缩小

* [BundlerMinifier](https://github.com/madskristensen/BundlerMinifier)-Visual Studio扩展，让您配置捆绑和缩小JS，CSS和HTML文件。
* [JavaScriptViewEngine](https://github.com/pauldotknopf/JavaScriptViewEngine)-用于在JavaScript环境中呈现标记的ASP.NET MVC ViewEngine。React和Angular服务器端渲染的理想选择。
* [Smidge](https://github.com/Shazwazza/Smidge/)-用于ASP.NET Core的轻量级运行时CSS/JavaScript文件缩小，组合，压缩和管理库。
* [Web Markup Minifier](https://github.com/Taritsyn/WebMarkupMin)-。包含一组标记迷你符的NET库。该项目的目标是通过减少HTML，XHTML和XML代码的大小来提高web应用程序的性能。
### 缓存

* [CacheManager](https://github.com/MichaCo/CacheManager)-开源缓存抽象层。NET写在C #。它支持各种缓存提供程序并实现许多高级功能。[http://cachemanager.michaco.net](http://cachemanager.michaco.net)
* [EasyCaching](https://github.com/dotnetcore/EasyCaching)-开源缓存库，其中包含基本用法和一些高级缓存用法，可以帮助我们更轻松地处理缓存。
* [Faster](https://github.com/Microsoft/FASTER/tree/master/cs)-来自Microsoft Research的快速键值存储。
* [Foundatio](https://github.com/exceptionless/Foundatio)-用于构建分布式应用程序的可插拔基础块。
* [Microsoft Caching](https://github.com/aspnet/Caching)-用于内存缓存和分布式缓存的库。
* [Stack Exchange Redis](https://github.com/StackExchange/StackExchange.Redis)-高性能通用redis客户端。NET语言 (C # 等)。
### CMS

* [Awesome-CMS-Core](https://github.com/SaiGonSoftware/Awesome-CMS-Core)-Awesome CMS Core是使用ASP.Net Core和ReactJS构建的开源CMS，考虑到模块分离问题，并提供最新的技术趋势
* [Blogifier.Core](https://github.com/blogifierdotnet/Blogifier.Core)ASP.NET应用程序提供常用的博客功能。
* [Cofoundry](https://github.com/cofoundry-cms/cofoundry)-开源。NET Core CMS和模块化应用程序框架。代码优先，不显眼，可扩展。
* [CoreWiki](https://github.com/csharpfritz/CoreWiki)-简单的ASP.NET Core wiki，我们在实时编码流中工作。
* [dasblog-core](https://github.com/poppastring/dasblog-core)-用ASP.NET Core重新构想的原始DasBlog
* [Lynicon](https://github.com/jamesej/lyniconanc)-O/S ASP.Net Core/.Net Core CMS与付费模块: JSON内容，适用于各种数据存储，c # 内容类型
* [Miniblog](https://github.com/madskristensen/Miniblog.Core)-ASP.NET Core博客引擎。
* [Mixcore CMS](https://github.com/mixcore/mix.core)-由DotNet Core提供支持的开源CMS。Mixcore CMS是一个可扩展的开放平台，用于web内容管理和数字体验。Mixcore CMS在web上提供了深厚的功能和无限的灵活性。
* [NetCoreCMS](https://github.com/OnnoRokomSoftware/NetCoreCMS)-一个开源的ASP.NET Core 2.0 CMS。目前支持MySQL，计划实现MSSQL、SQLite和PostgreSQL。它也是一个模块化的CMS支持主题，皮肤，自定义布局，小部件，多语言 (En，BN)。
* [Orchard Core CMS](https://github.com/OrchardCMS/OrchardCore)-在模块化和可扩展的应用程序框架之上使用ASP.NET Core构建的开源内容管理系统。
* [Piranha CMS](https://github.com/piranhacms/piranha.core)-用于ASP.NET Core和Entity Framework Core的轻量级且不引人注目的开源CMS。
* [Platformus](https://github.com/Platformus)-基于ASP.NET Core 1.0和ExtCore框架的免费，开源和跨平台的CMS。
* [SimpleContent](https://github.com/joeaudette/cloudscribe.SimpleContent)-用于ASP.NET Core的简单而灵活的内容和博客引擎，可以使用或不使用数据库。
* [Squidex](https://github.com/Squidex/squidex)-无头CMS，基于MongoDB，CQRS和事件源。
* [Swastika I/O Core CMS](https://github.com/Swastika-IO/Swastika-IO-Core)-开源ASP.NET Core 2.x CMS。它目前支持MS SQL，并计划在不久的将来实现MSSQL，SQLite。它有许多内置的功能，如多语言支持，主题，模板...
* [Umbraco](https://github.com/umbraco/umbraco-cms)-一个可扩展且友好的开源ASP.NET Core CMS
* [Weapsy](https://github.com/Weapsy/Weapsy)-基于DDD和CQRS的开源ASP.NET Core CMS。它支持MSSQL，MySQL，SQLite和PostgreSQL开箱即用。
* [Wyam](https://github.com/Wyamio/Wyam)-模块化静态内容和静态站点生成器。
* [ZKEACMS](https://github.com/SeriaWei/ZKEACMS.Core)-视觉设计，通过拖放建立网站onlie。
### 代码分析和度量

* [awesome-static-analysis](https://github.com/mre/awesome-static-analysis)-各种编程语言的静态分析工具，短线和代码质量检查器的精选列表。
* 代码分析
  * [CodeFormatter](https://github.com/dotnet/codeformatter)-使用Roslyn自动重写源以遵循netfx编码样式的工具。[Nuget Package](https://www.nuget.org/packages/Dotnet.CodeFormatter.BuildTask.Fork)
  * [DevSkim](https://github.com/Microsoft/DevSkim)-一组提供安全 “linting” 功能的IDE插件和规则。
  * [RefactoringEssentials](https://github.com/icsharpcode/RefactoringEssentials)-Visual Studio的重构Essentials。
  * [roslyn-analyzers](https://github.com/dotnet/roslyn-analyzers)-什么？-.NET编译器平台 (“Roslyn”) 分析器。
  * [StyleCopAnalyzers](https://github.com/DotNetAnalyzers/StyleCopAnalyzers)-StyleCop规则使用.NET编译器平台。
* 指标
  * [AppMetrics](https://github.com/alhardy/AppMetrics)-App Metrics是一个开源和跨平台的。NET库，用于记录和报告应用程序中的指标并报告其运行状况。
  * [Audit.NET](https://github.com/thepirat000/Audit.NET)-审计的小框架。NET对象的变化。
  * [BenchmarkDotNet](https://github.com/dotnet/BenchmarkDotNet)-强大。用于基准测试的NET库。
  * [coverlet](https://github.com/tonerdo/coverlet)-跨平台代码覆盖库。NET核心。
  * [Foundatio](https://github.com/exceptionless/Foundatio#metrics)-与内存、redis、StatsD和Metrics.NET实现的通用接口。
  * [MiniCover](https://github.com/lucaslorentz/minicover)-极简主义代码覆盖工具。NET核心。
  * [NBench](https://github.com/petabridge/NBench)-性能基准测试和测试框架。NET应用程序。
  * [Nexogen.Libraries.Metrics](https://github.com/nexogen-international/Nexogen.Libraries.Metrics)-用于收集应用程序指标的库。NET并将其导出到Prometheus。
  * [OpenCover](https://github.com/OpenCover/opencover)-代码覆盖工具。NET 2及以上 (仅限WINDOWS操作系统)，支持32和64个进程，同时具有分支和序列点。
  * [PerformanceMonitor](https://github.com/dotnet-architecture/PerformanceMonitor)-什么？-.NET Core应用程序性能监视器。
  * [prometheus-net](https://github.com/prometheus-net/prometheus-net)-什么？-.NET客户端[https://prometheus.io](https://prometheus.io)。
  * [Prometheus.Client](https://github.com/PrometheusClientNet/Prometheus.Client)-什么？-.NET客户端[Prometheus](https://prometheus.io)。
  * [Prometheus.Client.MetricPusher](https://github.com/PrometheusClientNet/Prometheus.Client.MetricPusher)-将指标推送到Prometheus.Client的PushGateaway。
  * [Prometheus.Client.AspNetCore](https://github.com/PrometheusClientNet/Prometheus.Client.AspNetCore)-Prometheus.Client的中间件。
  * [Prometheus.Client.MetricServer](https://github.com/PrometheusClientNet/Prometheus.Client.MetricServer)-用于Prometheus.Client的MetricServer。
  * [Prometheus.Client.HttpRequestDurations](https://github.com/PrometheusClientNet/Prometheus.Client.HttpRequestDurations)-Prometheus.Client的请求持续时间的度量记录。
### 压缩

* [lz4net](https://github.com/MiloszKrajewski/K4os.Compression.LZ4)-所有的超快速压缩算法。NET平台。
* [sharpcompress](https://github.com/adamhathcock/sharpcompress)-完全托管的C # 库来处理许多压缩类型和格式。
### 编译器、转译器和语言

* [Fable](https://github.com/fable-compiler/Fable)-F # 到JavaScript编译器。
* [fparsec](https://github.com/stephan-tolksdorf/fparsec)-用于F # 和C # 的解析器组合库。
* [IL2C](https://github.com/kekyo/IL2C)-将CIL/MSIL ECMA-335为c语言的翻译器。
* [Mond](https://github.com/Rohansi/Mond)-用C # 编写的动态类型脚本语言，具有REPL，调试器和简单的嵌入API。
* [peachpie](https://github.com/peachpiecompiler/peachpie)开源PHP编译器.NET。
* [Pidgin](https://github.com/benjamin-hodgson/Pidgin)-一个轻量级，快速和灵活的C # 解析库，在Stack Overflow开发。
* [roslyn](https://github.com/dotnet/roslyn)-那个.NET编译器平台 (“Roslyn”) 提供了具有丰富代码分析api的开源C # 和Visual Basic编译器。
* [Sprache](https://github.com/sprache/Sprache)微小的C # Monadic解析器框架。
### 密码学

* [BCrypt.Net](https://github.com/BcryptNet/bcrypt.net)-带来更新到原来的bcrypt包。
* [BCrypt.NET-Core](https://github.com/neoKushan/BCrypt.Net-Core)-什么？-.用于安全存储密码的BCrypt.NET的.NET核心端口。
* [BouncyCastle PCL](https://github.com/onovotny/BouncyCastle-PCL)-充气城堡加密包是加密算法和协议的C # 实现。
* [multiformats](https://github.com/multiformats/cs-multihash)-通用散列库，但是用于编码/解码多散列的库，其是描述用什么散列算法计算摘要的 “容器”。
* [nsec](https://github.com/ektrah/nsec)-NSec是一个新的加密库。NET Core基于lib钠。
* [SecurityDriven.Inferno](github.com/sdrapkin/SecurityDriven.Inferno)-使用Hig级加密库。Net原语，已经过专业审核。
### 数据库

* [DBreeze](https://github.com/hhblaze/DBreeze)-C #。NET MONO NOSQL (键值存储嵌入式) ACID多范式数据库管理系统
* [JsonFlatFileDataStore](https://github.com/ttu/json-flatfile-datastore)-简单的JSON平面文件数据存储，支持类型化和动态数据。
* [LiteDB](https://github.com/mbdavid/LiteDB)-什么？-.NET NoSQL文档存储在单个数据文件中-[http://www.litedb.org](http://www.litedb.org)。
* [NoDb](https://github.com/joeaudette/NoDb)-“无数据库” 文件系统存储。NET Core/ASP.NET Core，因为不是每个项目都需要数据库。
* [marten](https://github.com/JasperFx/marten)-Postgresql作为的文档数据库和事件存储。NET应用程序[http://jasperfx.github.io/marten](http://jasperfx.github.io/marten)。
* [StringDB](https://github.com/SirJosh3917/StringDB)-StringDB是一个模块化的键/值对存档DB，旨在消耗* 微小的* ram和产品的数量* 微小的* 数据库。
* [yessql](https://github.com/sebastienros/yessql)-什么？-.NET文档数据库在任何RDBMS上工作。
### 数据库驱动程序

* [cassandra-csharp-driver](https://github.com/datastax/csharp-driver)-用于Apache Cassandra的DataStax C # 驱动程序。
* [confluent-kafka-dotnet](https://github.com/confluentinc/confluent-kafka-dotnet)-Confluent的Apache Kafka。NET客户端。
* [couchbase-lite-net](https://github.com/couchbase/couchbase-lite-net)-一个轻量级的，面向文档的 (NoSQL)，syncable数据库引擎。NET。
* [MongoDB.Driver](https://github.com/mongodb/mongo-csharp-driver)-什么？-.NET驱动程序的MongoDB。
* [MongoDB.Entities](https://github.com/dj-nitehawk/MongoDB.Entities)-MongoDB的数据访问库，具有优雅的api，LINQ支持和内置的实体关系管理
* MySQL
  * [mysql-connector-net](https://github.com/mysql/mysql-connector-net/tree/8.0)Connector/Net是MySQL的一个完全托管的ADO.NET驱动程序。
  * [MySqlConnector](https://github.com/mysql-net/MySqlConnector)-用于的异步MySQL连接器。NET和。NET核心。
* Neo4j
  * [neo4j-dotnet-driver](https://github.com/neo4j/neo4j-dotnet-driver)-Neo4j螺栓驱动器。NET。
  * [Neo4jClient](https://github.com/Readify/Neo4jClient)-什么？-.NET客户端绑定Neo4j。
* [npgsql](https://github.com/npgsql/npgsql)-什么？-.NET数据提供程序的PostgreSQL。它允许开发的任何程序。NET framework来访问PostgreSQL数据库服务器。它是用100% C # 代码实现的。PostgreSQL版本，因为9.1正式支持，其他可能工作。[http://www.npgsql.org](http://www.npgsql.org)
* [ravendb](https://github.com/ayende/ravendb/tree/v4.0)-为启用了Linq的文档数据库。NET。
* [RethinkDb.Driver](https://github.com/bchavez/RethinkDb.Driver)-具有100% ReQL API覆盖率的C #/.NET RethinkDB驱动程序。
* [progaudi.tarantool](https://github.com/progaudi/progaudi.tarantool)-什么？-.NET客户端的Tarantool NoSql数据库。
### 数据库工具和实用程序

* [DbUp](https://github.com/DbUp/DbUp)-什么？-.NET库，可帮助您将更改部署到SQL Server数据库。它跟踪已经运行的SQL脚本，并运行使数据库保持最新所需的更改脚本。
* [Evolve](https://github.com/lecaillon/Evolve)-使用纯SQL脚本的简单数据库迁移工具。受到Flyway的启发。
* [EFCorePowerTools](https://github.com/ErikEJ/EFCorePowerTools)-实体框架核心动力工具-EF Core的逆向工程，迁移和模型可视化。
* [fluentmigrator](https://github.com/fluentmigrator/fluentmigrator)-迁移框架。NET很像Ruby on Rails迁移。
* [monitor-table-change-with-sqltabledependency](https://github.com/christiandelbianco/monitor-table-change-with-sqltabledependency)-获取有关记录表更改的SQL Server通知。
* [NReco.PivotData](https://www.nuget.org/packages/NReco.PivotData)-具有OLAP操作和数据透视表数据模型的内存数据多维数据集。
* [roundhouse](https://github.com/chucknorris/roundhouse)-用于的数据库迁移实用程序。NET使用sql文件和基于源代码控制的版本控制。
* [SapphireDb](https://github.com/SapphireDb/SapphireDb)-SapphireDb的服务器实现，该框架可轻松开发具有实时数据同步的应用程序，并且是firebase实时数据库/firestore r asp.net核心和ef核心的自托管替代方案。查看文档了解更多详细信息:[Documentation](https://sapphire-db.com)
* [SharpRepository](https://github.com/SharpRepository/SharpRepository)-SharpRepository是用C # 编写的通用存储库，其中包括对各种关系，文档和对象数据库的支持，包括Entity Framework，RavenDB，MongoDb和Db4o。SharpRepository还包括Xml和InMemory存储库实现。
* [TrackableEntities.Core](https://github.com/TrackableEntities/TrackableEntities.Core)-跨服务边界的变更跟踪。NET核心。
* [Mongo.Migration](https://github.com/SRoddis/Mongo.Migration)-Mongo.Migration专为[MongoDB C# Driver](https://github.com/mongodb/mongo-csharp-driver)轻松地即时迁移您的文档。模式迁移不再停机。只需编写小而简单的迁移。[Link](https://github.com/SRoddis/Mongo.Migration)
* [EntityFrameworkCore.DataEncryption](https://github.com/Eastrall/EntityFrameworkCore.DataEncryption)-Microsoft.EntityFrameworkCore的插件，用于使用内置或自定义加密提供程序添加对加密字段的支持。
### 日期和时间

* [Exceptionless.DateTimeExtensions](https://github.com/exceptionless/Exceptionless.DateTimeExtensions)-DateTimeRange、Business Day和各种DateTime、DateTimeOffset、TimeSpan扩展方法。
* [FluentDateTime](https://github.com/FluentDateTime/FluentDateTime)-允许您编写更干净的日期时间表达式和操作。部分灵感来自Ruby DateTime扩展。
* [nodatime](https://github.com/nodatime/nodatime)-更好的日期和时间的API。净值[http://nodatime.org](http://nodatime.org)。
### 分布式计算

* [AspNetCore.Diagnostics.HealthChecks](https://github.com/xabaril/AspNetCore.Diagnostics.HealthChecks)-用于ASP.NET Core诊断包的企业运行状况检查
  - [BeatPulse](https://github.com/Xabaril/BeatPulse)-启用负载平衡器以montior部署的Web应用程序的状态
* [Foundatio](https://github.com/exceptionless/Foundatio)-用于构建分布式应用程序的可插拔基础块
* [jasper](https://github.com/JasperFx/jasper)-下一代应用程序开发框架。净值
* [Rafty](https://github.com/ThreeMammals/Rafty)-筏共识。净核
* [Obvs](https://github.com/christopherread/Obvs)-可观察的微服务总线。NET库，它将基础传输包装在简单的基于Rx的接口中
* [Ocelot](https://github.com/ThreeMammals/Ocelot)-使用创建的API网关。NET核心
* [OpenTracing](https://github.com/opentracing/opentracing-csharp)-用于分布式跟踪的供应商中立api和工具
* [Polly](https://github.com/App-vNext/Polly)-什么？-.NET 3.5 / 4.0 / 4.5/PCL库，允许开发人员以流畅的方式表达瞬态异常和故障处理策略，例如重试，永远重试，等待和重试或断路器
* [ProxyKit](https://github.com/damianh/ProxyKit)-在ASP.NET Core上创建代码优先的HTTP反向代理的工具包
### 电子商务和支付

* [nopCommerce](https://github.com/nopSolutions/nopCommerce)-免费的开源电子商务购物车 (ASP.NET MVC / ASP.NET Core MVC)，拥有庞大的社区和充满新功能，主题和插件的市场。
* [GrandNode](https://github.com/grandnode/grandnode)-基于ASP.NET Core 2.1和衍生自MongoDB的多平台，免费，开源电子商务购物车[nopCommerce](https://github.com/nopSolutions/nopCommerce)。
* [PayPal](https://github.com/paypal/PayPal-NET-SDK)-什么？-.NET SDK用于PayPal的RESTful api。
* [SimplCommerce](https://github.com/simplcommerce/SimplCommerce)-建立在超级简单的电子商务系统。NET核心。
* [Stripe](https://github.com/ServiceStack/Stripe)-打字。NET客户端来r stripe.com REST api。
### 例外情况

* [Demystifier](https://github.com/benaadams/Ben.Demystifier)-对堆栈跟踪的高性能理解 (使错误日志更有效率)。
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net)-没有例外.NET客户端
* [GlobalExceptionHandlerDotNet](https://github.com/JosephWoodward/GlobalExceptionHandlerDotNet)-GlobalExceptionHandlerDotNet允许您将异常处理配置为ASP.NET Core应用程序管道的约定，而不是在每个控制器操作中显式处理它们。
* [Sentry](https://github.com/getsentry/sentry-dotnet)-什么？-.NET SDK for Sentry，这是一种开源错误跟踪，可帮助开发人员实时监控和修复崩溃。
### 函数式编程

* [CSharpFunctionalExtensions](https://github.com/vkhorikov/CSharpFunctionalExtensions)-C # 的功能扩展。
* [DynamicData](https://github.com/RolandPheasant/DynamicData)-基于Rx.NET的反应性集合。
* [echo-process](https://github.com/louthy/echo-process)-Actor库C # 与支持持久化到Redis的附加模块，以及JS集成。
* [FsCheck](https://github.com/fscheck/FsCheck)-随机测试。NET。
* [Giraffe](https://github.com/dustinmoris/Giraffe)-面向F # 开发人员的本机功能ASP.NET Core web框架。
* [language-ext](https://github.com/louthy/language-ext)C # 功能语言扩展和 'erlanglike' 并发系统。
* [LaYumba.Functional](https://github.com/la-yumba/functional-csharp-code)-用于在C # 中进行功能编程的实用程序库。
* [NetMQ.ReactiveExtensions](https://github.com/NetMQ/NetMQ.ReactiveExtensions)-毫不费力地发送消息在网络上的任何地方使用反应性扩展 (RX)。传输协议是ZeroMQ。
* [Optional](https://github.com/nlkl/Optional)-C # 的一个强大的选项类型。
* [reactive-streams-dotnet](https://github.com/reactive-streams/reactive-streams-dotnet)-[Reactive Streams](http://www.reactive-streams.org/)为。NET。
* [ReactiveUI](https://github.com/reactiveui/ReactiveUI)-与的响应式扩展集成的MVVM框架。NET创建可在任何移动或桌面平台上运行的优雅，可测试的用户界面。
* [Rx.NET](https://github.com/Reactive-Extensions/Rx.NET)-The[Reactive Extensions](http://reactivex.io)为。NET。
* [Qactive](https://github.com/RxDave/Qactive)-反应式queryable observable框架。
* [sodium](https://github.com/SodiumFRP/sodium/tree/master/)函数式反应式编程 (FRP) 库。
### 图形

* [GLFWDotNet](https://github.com/smack0007/GLFWDotNet)-什么？-.NET绑定GLFW。
* [ImageProcessor](https://github.com/JimBobSquarePants/ImageProcessor)-一个流畅的包装在System.Drawing图像文件的处理[http://imageprocessor.org](http://imageprocessor.org)。
* [ImageSharp](https://github.com/SixLabors/ImageSharp)-跨平台库，用于处理用C # 编写的图像文件。
* [LibVLCSharp](https://github.com/videolan/libvlcsharp):。NET/Mono绑定libvlc，多媒体框架支持VideoLAN制作的VLC应用程序。
* [Magick.NET](https://github.com/dlemstra/Magick.NET)-那个.NET库的ImageMagick。
* [MagicScaler](https://github.com/saucecontrol/PhotoSauce)-MagicScaler高性能，高质量的图像处理管道。净值
* [QRCoder](https://github.com/codebude/QRCoder)一个纯C # 的开源QR码实现。
* [SharpBgfx](https://github.com/MikePopoloski/SharpBgfx)-bgfx图形库的C # 绑定。
* [Structure.Sketching](https://github.com/JaCraig/Structure.Sketching)图像处理库中使用。NET应用程序支持。NET核心。
* [veldrid](https://github.com/mellinoe/veldrid)-一个低级别的，硬件加速的3D图形库。NET。
* [ZXing.Net](https://github.com/micjahn/ZXing.Net/)-什么？-.Net端口的原始基于java的条形码阅读器和生成器库zxing。
### 图形用户界面

* [AdonisUI](https://github.com/benruehl/adonis-ui)-WPF应用程序的轻量级UI工具包，提供经典但增强的windows视觉效果。
* [Avalonia](https://github.com/AvaloniaUI/Avalonia)-多平台。NET UI框架 (以前称为Perspex)。
* [AvaloniaEdit](https://github.com/AvaloniaUI/AvaloniaEdit/)-基于Avalonia的文本编辑器组件[AvalonEdit](https://github.com/icsharpcode/AvalonEdit)[HandyControls](https://github.com/ghost1372/HandyControls)-包含一些简单和常用的WPF控件。
* [Lara](https://github.com/integrativesoft/lara)-Lara Web Engine是一个用于在C # 中开发Web用户界面的库
* [ShellProgressBar](https://github.com/Mpdreamz/shellprogressbar)-在控制台程序中创建进度条的库
* [Qml.Net](https://github.com/pauldotknopf/Qml.Net)-Mono/.NET Core的跨平台Qml/.NET集成。
* [WinApi](https://github.com/prasannavl/WinApi)-一个简单，直接，超薄的CLR库，用于高性能Win32本机互操作，具有自动化，窗口，DirectX，OpenGL和Skia helpers。
### IDE

* [Mono](https://github.com/mono/monodevelop)-Monodevelide使开发人员能够在Linux，Windows和Mac OS X上快速编写桌面和web应用程序。这也使开发人员易于移植。NET应用程序创建的Visual Studio到Linux和Mac OS X，为所有平台维护单个代码库。
* [rider](https://www.jetbrains.com/rider/)基于IntelliJ平台和ReSharper的跨平台C # IDE。
* [Omnisharp](http://www.omnisharp.net/)-开源项目家族，每个项目都有一个目标: 实现一个伟大的。NET经验在你选择的编辑器。
* [SharpDevelop](https://github.com/icsharpcode/SharpDevelop)-SharpDevelop是一个免费的集成开发环境 (IDE)，适用于C #，VB.NET，Boo，IronPython，IronRuby和F # 项目在Microsoft的。NET平台。它 (几乎) 完全用C # 编写，并带有您在IDE中期望的功能以及更多功能。
* [Visual Studio Code](https://github.com/Microsoft/vscode)-一种新型工具，将代码编辑器的简单性与开发人员对其核心编辑-构建-调试周期的需求相结合。代码提供全面的编辑和调试支持、可扩展性模型以及与现有工具的轻量级集成。
* [Visual Studio Community](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx)-适用于个人开发人员，开源项目，学术研究，教育和小型专业团队的免费编辑器。
### 国际化

* [Localization](https://github.com/aspnet/Localization)-ASP.NET Core应用程序的本地化抽象和实现。
* [NetCoreStack.Localization](https://github.com/NetCoreStack/Localization)-的数据库资源本地化。NET Core与实体框架和内存缓存
* [Westwind.Globalization](https://github.com/RickStrahl/Westwind.Globalization)-数据库驱动的资源本地化。NET应用程序。
### 国际奥委会

* [AutoDI](https://github.com/Keboo/AutoDI)-使用IL编织的超快速编译时依赖注入。
* [Autofac](https://github.com/autofac/Autofac)-上瘾了.NET IoC容器。
* [Castle.Windsor](https://github.com/castleproject/Windsor)温莎城堡是最好的品种，可用于控制容器的成熟反转。NET。
* [DryIoc](https://github.com/dadhi/DryIoc)-快速，小，功能齐全的IoC容器。NET。
* [Grace](https://github.com/ipjohnson/Grace)-Grace是一个功能丰富的依赖注入容器，设计时考虑了易用性和性能。
* [Inyector](https://github.com/davidrevoledo/Inyector)-AspNetCore的依赖注入自动化
* [Lamar](https://github.com/JasperFx/lamar)-快速反转控制工具和Roslyn Chicanery的各种物品。
* [LightInject](https://github.com/seesharper/LightInject)-超轻量级的IoC容器。
* [SimpleInjector](https://github.com/simpleinjector/SimpleInjector)-简单，灵活和快速的依赖注入库，促进最佳实践，引导开发人员走向成功的坑。
* [Stashbox](https://github.com/z4kn4fein/stashbox)-一个轻量级的，可移植的依赖注入框架。NET的解决方案。
* [Unity](https://github.com/unitycontainer/unity)-一个轻量级的、可扩展的依赖注入容器。
### 日志记录

* [common-logging](https://github.com/net-commons/common-logging)-便携式日志抽象。NET。
* [dnxcore-logging-logstash](https://github.com/jvandevelde/dnxcore-logging-logstash)-Logstash的日志记录扩展。NET Core应用程序与UDP和Redis传输。
* [ElmahCore](https://github.com/ElmahCore/ElmahCore)-错误日志库，包括错误过滤和从网页查看错误日志的功能。
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net)-没有例外.NET客户端
* [Foundatio](https://github.com/exceptionless/Foundatio#logging)-一个fluent logging api，可用于在整个应用程序中记录消息。
* [Karambolo.Extensions.Logging.File](https://github.com/adams85/filelogger)-一个轻量级的库，它实现了内置的文件记录。NET Core日志记录框架 (Microsoft.Extensions.logging)。
* [LibLog](https://github.com/damianh/LibLog)-单个文件，您可以通过nuget复制/粘贴或安装到您的库/框架/应用程序中，以提供日志记录抽象。
* [log4net](https://github.com/apache/logging-log4net)-log4net是优秀的Apache log4j的一个端口™框架到Microsoft®。NET运行时。
* [NLog](https://github.com/NLog/NLog)-先进的.NET、Silverlight和Xamarin日志记录，支持结构化和非结构化日志记录。
  * [NLog for ASP.NET and ASP.NET Core](https://github.com/NLog/NLog.Web)-ASP.NET和ASP.NET Core 1-3的NLog集成
  * [NLog.Extensions.Logging](https://github.com/NLog/NLog.Extensions.Logging)-NLog Provider for Microsoft.Extensions.Logging for.NET标准库和.NET Core应用程序
  * [NLog.Windows.Forms](https://github.com/NLog/NLog.Windows.Forms)-特定于Windows.Forms的NLog目标
  * [NLog.MailKit](https://github.com/NLog/NLog.MailKit)-使用using MailKit库的替代邮件目标
* [Q42.Logging.ApplicationInsights](https://github.com/Q42/Q42.Logging.ApplicationInsights)-用于在ASP.NET Core日志记录中生成的日志appender，用于将所有日志发送到Application Insights。
* [serilog](https://github.com/serilog/serilog)-很简单.NET日志记录与完全结构化的事件。
  * [serilog-aspnetcore](https://github.com/serilog/serilog-aspnetcore)-用于ASP.NET Core 2的Serilog集成。
  * [Serilog.Exceptions](https://github.com/RehanSaeed/Serilog.Exceptions)-Serilog.Exception是一个附加的[Serilog](https://serilog.net/)记录exception.ToString() 中未输出的异常详细信息和自定义属性。
  * [Serilog.Settings.Configuration](https://github.com/serilog/serilog-settings-configuration)-从Microsoft.Extensions.configuration读取的Serilog配置提供程序。
* [SEQ](https://getseq.net)-Seq通过HTTP收集数据，而您的应用程序则为您的平台使用最佳的结构化日志记录api。
### 机器学习和数据科学

* [Accord](https://github.com/accord-net/framework)-机器学习，计算机视觉，统计和一般科学计算。NET。
* [Catalyst](https://github.com/curiosity-ai/catalyst)受spaCy启发的跨平台自然语言处理 (NLP) 库，具有预先训练的模型，对训练word和文档嵌入的开箱即用支持以及灵活的实体识别模型。的一部分[SciSharp Stack](https://scisharp.github.io/SciSharp/)
* [ML.NET](https://github.com/dotnet/machinelearning)-跨平台的开源机器学习框架，使机器学习可访问。NET开发人员[http://dot.net/ml](http://dot.net/ml)。
* [Spreads](https://github.com/Spreads/Spreads/)-用于数据流的实时和探索性分析的系列和面板。
* [TensorFlowSharp](https://github.com/migueldeicaza/TensorFlowSharp)-用于的TensorFlow API。NET语言。
* [WaveFunctionCollapse](https://github.com/mxgmn/WaveFunctionCollapse)-itmap和tilemap在量子力学思想的帮助下从一个例子中生成。
* [SiaNet](https://github.com/SciSharp/SiaNet)-一个C # 深度学习库，人类友好，CUDA/OpenCL支持，结构良好，易于扩展
### 邮件

* [FluentEmail](https://github.com/lukencode/FluentEmail)-所有在一个电子邮件发件人。NET和。NET核心
* [MailBody](https://github.com/doxakis/MailBody)-使用流畅的界面 (.NET) 创建事务性电子邮件。
* [MailKit](https://github.com/jstedfast/MailKit)-跨平台。NET库，用于IMAP、POP3和SMTP。
* [MailMergeLib](https://github.com/axuno/MailMergeLib)-SMTP邮件客户端库，为文本，内联图像和附件提供舒适的邮件合并功能，以及发送邮件消息的良好吞吐量和容错能力。
* [MimeKit](https://github.com/jstedfast/MimeKit)-跨平台。NET MIME创建和解析器库，支持S/MIME、PGP、DKIM、TNEF和Unix mbox假脱机。
* [netDumbster](https://github.com/cmendible/netDumbster)-a.Net假SMTP服务器用于测试。流行哑巴的克隆。
* [Papercut](https://github.com/ChangemakerStudios/Papercut)-简单的桌面SMTP服务器
* [PreMailer.Net](https://github.com/milkshakesoftware/PreMailer.Net)-C # 库，将样式表移动到内联样式属性，以实现与电子邮件客户端的最大兼容性。
* [SendGrid Client](https://github.com/0xdeafcafe/sendgrid-dotnet)-SendGrid v3邮件终结点的C # 库。
* [SmtpServer](https://github.com/cosullivan/SmtpServer)-库来创建自己的SMTP服务器。
* [StrongGrid](https://github.com/Jericho/StrongGrid)-SendGrid的v3 API的客户端。不仅允许您发送电子邮件，还允许您批量导入联系人，管理列表和细分，为您的列表创建自定义字段等。还包括SendGrid Webhooks的解析器。
### 数学

* [UnitConversion](https://github.com/Stratajet/UnitConversion)-可扩展的单位转换库。NET核心和。NET框架。
* [AutoDiff](https://github.com/alexshtf/autodiff)-一个库，提供快速，准确和自动微分 (计算导数/梯度) 的数学函数。
### 媒体

* [MetadataExtractor](https://github.com/drewnoakes/metadata-extractor-dotnet)-使用简单易用的API从媒体 (图像，视频，音频) 中提取元数据。
### 杂类

* [AdvanceDLSupport](https://github.com/Firwood-Software/AdvanceDLSupport)-库，以改进P/Invoke-ing本机代码。与本机对象进行交互，就好像它们是第一类对象一样。
* [AngleSharp](https://github.com/AngleSharp/AngleSharp)-最终的尖括号解析器库。它解析HTML5，MathML，SVG和CSS，以基于官方W3C规范构建DOM。相当于python的beautifulsoup4。
* [AgileMapper](https://github.com/agileobjects/AgileMapper)-AgileMapper是一种零配置，高度可配置的对象-对象映射器，具有可查看的执行计划。
* [AspNetCore Extension Library](https://github.com/sgjsakura/AspNetCore)-ASP.NET Core扩展库。
* [AutoMapper](https://github.com/AutoMapper/AutoMapper)-基于约定的对象-对象映射器在NET。
* [Baget](https://github.com/loic-sharma/BaGet)-一个轻量级的NuGet服务器。
* [Bleak](https://github.com/Akaion/Bleak)-Windows本机DLL注入库。
* [Bullseye](https://github.com/adamralph/bullseye/)-A.NET包，用于描述和运行目标及其依赖项。
* [Castle.Core](https://github.com/castleproject/Core)-城堡核心，包括城堡动态代理、日志记录服务和字典适配器[http://www.castleproject.org](http://www.castleproject.org)。
* [Chessie](https://github.com/fsprojects/Chessie)-面向铁路的编程。净值[http://fsprojects.github.io/Chessie](http://fsprojects.github.io/Chessie)。
* [CliWrap](https://github.com/Tyrrrz/CliWrap)-命令行界面的包装。
* [commanddotnet](https://github.com/bilal-fazlani/commanddotnet)-在类中对命令行应用程序接口进行建模。
* [CommonMark.NET](https://github.com/Knagis/CommonMark.NET)-C # 中CommonMark规范的实现，用于将Markdown文档转换为HTML。
* [ConsoleTableExt](https://github.com/minhhungit/ConsoleTableExt)-Fluent library为创建表。NET控制台应用程序。
* [CoordinateSharp](https://github.com/Tronald/CoordinateSharp)-一个库，可以快速格式化和转换地理坐标，以及提供基于位置的太阳和月亮信息 (日落，日出，月亮照明等)。
* [datatables](https://github.com/ALMMa/datatables.aspnet/tree/dev)-Microsoft ASP.NET服务器端支持和jQuery数据表的帮助器。
* [DinkToPdf](https://github.com/rdvojmoc/DinkToPdf)-C #。NET Core包装器，用于使用Webkit引擎将HTML页面转换为PDF的wkhtmltopdf库。
* [dotnet-env](https://github.com/tonerdo/dotnet-env)-A.NET库加载环境变量。env文件。
* [DotNet.Glob](https://github.com/dazinator/DotNet.Glob)-一个快速的globbing库。净/。NETStandard应用程序。表现优于正则表达式。
* [Dotnet outdated](https://github.com/dotnet-outdated/dotnet-outdated)-A.NET Core全局工具在项目中显示和更新过时的NuGet包
* [Dotnet Script](https://github.com/filipw/dotnet-script)-从运行C # 脚本。NET CLI。
* [Dotnet Serve](https://github.com/natemcmaster/dotnet-serve)-简单的命令行HTTP服务器。NET Core CLI。
* [Downloader](https://github.com/bezzad/Downloader)-Downloader是一个现代，流畅，异步，可测试和便携式库。NET。这是一个具有异步进度事件的多部分下载器。
* [Eighty](https://github.com/benjamin-hodgson/Eighty)-一个简单的HTML生成库
* [Enums.NET](https://github.com/TylerBrinkley/Enums.NET)-Enums.NET是一种高性能的类型安全。NET枚举实用程序库
* [FastExpressionCompiler](https://github.com/dadhi/FastExpressionCompiler)-快速的ExpressionTree编译器委托。
* [FluentDocker](https://github.com/mariotoffia/FluentDocker)-用于docker，docker-compose和docker-machine，win/mac/linux和本机docker的命令，服务和流利的API。
* [FluentFTP](https://github.com/robinrodricks/FluentFTP/)-FTP和FTPS客户端，具有广泛的FTP命令，SSL/TLS连接，哈希/校验和等。
* [Fody](https://github.com/Fody/Fody)-可扩展的编织工具。net程序集
* [HdrHistogram.NET](https://github.com/HdrHistogram/HdrHistogram.NET)-高动态范围 (HDR) 直方图。
* [httpclient-interception](https://github.com/justeat/httpclient-interception)-什么？-.NET标准库，用于拦截服务器端HTTP依赖项。
* [Humanizer](https://github.com/Humanizr/Humanizer)-人性化满足你的所有。NET需要操作和显示字符串，枚举，日期，时间，时间跨度，数字和数量。
* [Humidifier](https://github.com/jakejscott/Humidifier)-使用C # 编写和维护AWS Cloudformation模板。
* [impromptu-interface](https://github.com/ekonbenefits/impromptu-interface)-静态接口的动态实现 (鸭铸造)。使用与Reflect.Emit结合的DLR。
* [JqueryDataTablesServerSide](https://github.com/fingers10/JqueryDataTablesServerSide)-ASP.NET Core服务器端处理库，用于Jquery数据表，具有Excel导出和TagHelper支持的数据库级别的多列过滤，排序和分页。
* [LibSass Host](https://github.com/Taritsyn/LibSassHost)-什么？-.NET包装周围的[libSass](http://sass-lang.com/libsass)能够支持虚拟文件系统的库。
* [markdig](https://github.com/lunet-io/markdig)-快速，强大，符合CommonMark标准，可扩展的Markdown处理器。NET。
* [NetCoreBeauty](https://github.com/nulastudio/NetCoreBeauty)-简单的库移动。NET Core应用程序运行时组件和依赖项到子目录中，并使其美丽。
* [NFlags](https://github.com/bartoszgolek/NFlags)-简单的库，使解析CLI参数变得容易。库还允许打印使用帮助 “开箱即用”。
* [NReco.LambdaParser](https://github.com/nreco/lambdaparser)-将字符串表达式 (公式，方法调用，条件) 解析为可以编译为lambda并进行评估的LINQ表达式树。
* [NuGet Trends](https://github.com/NuGetTrends/nuget-trends)-具有NuGet软件包下载计数统计信息的网站。
* [NYoutubeDL](https://gitlab.com/BrianAllred/NYoutubeDL)-一个简单的youtube-dl库为C #/.NET。
* [Otp.NET](https://github.com/kspearrin/Otp.NET)-在C # 中实现ttp RFC 6238和HOTP RFC 4226。
* [pose](https://github.com/tonerdo/pose)-替换任何。NET方法 (包括静态和非虚拟) 与委托
* [PuppeteerSharp](https://github.com/kblok/puppeteer-sharp)-木偶师Sharp是a.NET端口的官方Node.JS Puppeteer API。
* [readline](https://github.com/tsolarin/readline)-纯C # gnu-readline像库。NET/.NET Core。
* [ReflectionMagic](https://github.com/ReflectionMagic/ReflectionMagic)-框架大大简化您的私人反射代码使用C # 动态
* [Relinq](https://github.com/re-motion/Relinq)-使用re-linq，现在比以往任何时候都更容易创建功能齐全的linq提供程序。
* [Remote.Linq](https://github.com/6bee/Remote.Linq)-Remote Linq是一个小而易于使用-但非常强大-库转换LINQ表达式树强类型，可序列化的表达式树，反之亦然。
* [ReverseMarkdown](https://github.com/mysticmind/reversemarkdown-net)-Html到Markdown转换器库。
* [PdfReport.Core](https://github.com/VahidN/PdfReport.Core)-PdfReport.Core是一个代码优先报告引擎，它构建在iTextSharp.LGPLv2.Core和EPPlus.Core库之上。
* [Scientist](https://github.com/github/Scientist.net)-什么？-.NET库，用于仔细重构关键路径。它是GitHub的Ruby科学家库的一个端口。
* [Scrutor](https://github.com/khellang/Scrutor)-Microsoft.extensions.DependencyInjection的程序集扫描扩展。
* [Sheller](https://github.com/twitchax/Sheller)-A.NET库，使炮击命令超级容易和流畅。
* [SmartFormat.NET](https://github.com/scottrippey/SmartFormat.NET)-string.Format的可扩展替换。
* 股票
  * [Trady](https://github.com/lppkarl/Trady)-用于计算技术指标的便捷库，它的目标是成为一个自动交易系统，提供股票数据馈送，指标计算，策略构建和自动交易。
* [System.Linq.Dynamic.Core](https://github.com/StefH/System.Linq.Dynamic.Core)-那。NET标准 (.NET Core) 版本来自系统Linq动态功能。
* [UnitsNet](https://github.com/angularsen/UnitsNet)-Units.NET为您提供所有常见的度量单位以及它们之间的转换。
* 验证
  * [FluentValidation](https://github.com/JeremySkinner/FluentValidation)-小验证库。NET，它使用流畅的界面和lambda表达式来构建验证规则。
  * [FormHelper](https://github.com/SinanBozkus/FormHelper)-ASP.NET核心的表单和验证助手。表单助手可帮助您创建ajax表单和验证，而无需编写任何javascript代码。(与Fluent验证兼容)。
  * [Guard](https://github.com/safakgur/guard)-一个高性能、可扩展的参数验证库。
  * [Valit](https://github.com/valit-stack/Valit)-一个死的简单验证。NET核心。没有更多的if语句围绕你的代码。编写漂亮和干净流利的验证器来代替!
* [Vanara](https://github.com/dahall/Vanara)-一套.NET库实现对许多具有支持包装器的本机Windows api的PInvoke调用。
* [warden-stack](https://github.com/warden-stack)-对您的应用程序、资源和基础设施进行 “健康检查”。让你的典狱长值班。
* [WebEssentials.AspNetCore.ServiceWorker](https://github.com/madskristensen/WebEssentials.AspNetCore.ServiceWorker)-ASP.NET Core渐进式Web应用程序。
* [Xabe.FFmpeg](https://github.com/tomaszzmuda/Xabe.FFmpeg)-什么？-.NET标准包装FFmpeg。它允许在不知道FFmpeg如何工作的情况下处理媒体，并且可以用于从C # 应用程序将自定义参数传递给FFmpeg。
* [YoutubeExplode](https://github.com/Tyrrrz/YoutubeExplode)-用于提取元数据和下载Youtube视频和播放列表的终极库。
### 联网

* [AspNetCore.Proxy](https://github.com/twitchax/AspNetCore.Proxy)-ASP.NET Core代理变得容易。
* [CurlThin](https://github.com/stil/CurlThin)-用于C # 的轻量级cURL绑定库，通过curl_multi接口支持多个同时传输。
* [NETStandard.HttpListener](https://github.com/StefH/NETStandard.HttpListener)-的HttpListener。NET Core (NETStandard)。
* [Networker](https://github.com/MarkioE/Networker)一个简单的使用TCP和UDP的网络库。NET，旨在灵活，可扩展和快速。
* [SharpPcap](https://github.com/chmorgan/sharppcap)-完全托管，跨平台 (Windows，Mac，Linux)。NET库，用于从实时和基于文件的设备捕获数据包。
### 办公室

* [EPPlus](https://github.com/EPPlusSoftware/EPPlus)-使用创建高级Excel电子表格。NET。
* [npoi](https://github.com/tonyqus/npoi)-什么？-.NET库，可以在没有安装Microsoft Office的情况下读取/写入Office格式。没有COM，没有互操作。
* [Open-XML-SDK](https://github.com/OfficeDev/Open-XML-SDK)-Open XML SDK提供了用于处理Office Word、Excel和PowerPoint文档的工具。
### 操作系统

* [CosmosOS](https://github.com/CosmosOS/Cosmos)-Cosmos是一个操作系统 “建设工具包”。使用托管语言 (如C #，VB.NET等) 构建您自己的操作系统!
### ORM

* [Chloe](https://github.com/shuxinqin/Chloe)-一个轻量级和高性能的对象/关系映射 (ORM) 库。NET。
* [Entity Framework Core](https://github.com/aspnet/EntityFramework)-熟悉以前版本的EF的开发人员体验，包括LINQ，POCO和代码优先支持。
  * [EFCore.BulkExtensions](https://github.com/borisdj/EFCore.BulkExtensions)-用于插入更新删除读取 (CRUD) 操作的EntityFrameworkCore批量批处理扩展
  * [EntityFramework-Plus](https://github.com/zzzprojects/EntityFramework-Plus)-实体框架实用工具 | 批量操作 | 批量删除 | 批量更新 | 查询缓存 | 查询筛选器 | 查询将来 | 查询包含 | 审核。
  * [EntityFramework.Exceptions](https://github.com/Giorgi/EntityFramework.Exceptions)-当SQL查询违反SqlServer、MySql或PostgreSQL中的数据库约束时，对EntityFrameworkCore使用类型化异常。
  * [EntityFramework.Triggers](https://github.com/NickStrupat/EntityFramework.Triggers)-EF的触发事件。
  * [EntityFramework.Rx](https://github.com/NickStrupat/EntityFramework.Rx)-反应性** 热** 您的EF操作的可观察量。
  * [Npgsql.EntityFrameworkCore.PostgreSQL](https://github.com/npgsql/Npgsql.EntityFrameworkCore.PostgreSQL)-PostgreSQL的实体框架核心提供程序。
  * [EntityFramework.PrimaryKey](https://github.com/NickStrupat/EntityFramework.PrimaryKey)-轻松获取任何实体的主键 (包括组合键)。
  * [EntityFramework.TypedOriginalValues](https://github.com/NickStrupat/EntityFramework.TypedOriginalValues)-获取实体的原始值的代理对象 (对属性 (“...”).OriginalValue的类型化访问)。
  * [EntityFramework.VersionedProperties](https://github.com/NickStrupat/EntityFramework.VersionedProperties)-自动神奇地保留对指定属性的更改的审核历史记录的类。
  * [EntityFrameworkCore.SqlServer.SimpleBulks](https://github.com/phongnguyend/EntityFrameworkCore.SqlServer.SimpleBulks)-简单的库，可以帮助将内存中的大量记录同步到数据库中。支持Lambda表达式。
  * [LINQKit](https://github.com/scottksmith95/LINQKit)-LINQ to SQL和Entity Framework高级用户的免费扩展集。
  * [Pomelo.EntityFrameworkCore.MySql](https://github.com/PomeloFoundation/Pomelo.EntityFrameworkCore.MySql)-基于mysql-net/MySqlConnector构建的MySql实体框架核心提供程序。
  * [spectre.query](https://github.com/spectresystems/spectre.query)-实体框架核心的简单查询语言。
* [Dapper](https://github.com/StackExchange/Dapper)-简单的对象映射器。NET。
  * [Dapper-FluentMap](https://github.com/henkmollema/Dapper-FluentMap)-提供了一个简单的API，可以在使用Dapper时流畅地将POCO属性映射到数据库列。
  * [Dommel](https://github.com/henkmollema/Dommel)-Dapper的简单CRUD操作。
  * [MicroOrm.Dapper.Repositories](https://github.com/phnx47/MicroOrm.Dapper.Repositories)-对短小的人来说。
* [FreeSql](https://github.com/2881099/FreeSql)-dotnet中方便的ORM，支持Mysql，Postgresql，SqlServer，Oracle和Sqlite。
* [Limebean](https://nick-lucas.github.io/LimeBean/)-混合ORM，旨在简单易用，而不是完全隐藏SQL，同时拥有您期望从ORM获得的所有美好事物。受RedBeanPHP启发。
* [LINQ to DB (linq2db)](https://linq2db.github.io/)-最快的LINQ数据库访问库，在POCO对象和数据库之间提供简单，轻量级，快速和类型安全的层，用于10多个具有完整SQL支持的数据库引擎。
* [nhibernate-core](https://github.com/nhibernate/nhibernate-core)-NHibernate对象关系映射器。
* [NEventStore](https://github.com/NEventStore/NEventStore)-持久性库，用于在使用事件源作为存储机制时抽象不同的存储实现。该库是专门针对DDD/CQRS应用程序开发的。
* [NPoco](https://github.com/schotime/NPoco)-将查询结果映射到POCO对象的简单microORM。基于schetime的PetaPoco分支的项目。
* [NReco.Data](https://github.com/nreco/data)-轻量级提供程序独立的DAL，用于SQL命令生成，CRUD操作和简单的POCO映射。
* [PetaPoco](https://github.com/CollaboratingPlatypus/PetaPoco)-一个小小的orm-ish的东西为你的POCO的。
* [querybuilder](https://github.com/sqlkata/querybuilder)SqlKata查询生成器是用C # 编写的强大的Sql查询生成器。
* [RepoDb](https://github.com/mikependon/RepoDb)-一个混合ORM库。NET。
* [ServiceStack.OrmLite](https://github.com/ServiceStack/ServiceStack.OrmLite)-轻便，简单和快速的基于约定的POCO ORM。
* [SqlFu](https://github.com/sapiens/SqlFu)-快速和多功能的micro-orm。
* [SmartSql](https://github.com/Ahoo-Wang/SmartSql)-SmartSql = MyBatis缓存 (内存 | Redis) ZooKeeper R/W拆分动态仓库。...
* [SQLStreamStore](https://github.com/SQLStreamStore/SQLStreamStore)-针对基于SQL的实现的流存储库。NET。
### 剖析

* [Glimpse](https://github.com/Glimpse/Glimpse.Prototype)-轻量级，开源，实时诊断和见解分析器。NET。
* [MiniProfiler](https://github.com/MiniProfiler/dotnet)-一个简单但有效的ASP.NET网站迷你分析器。
### 查询生成器

* [SqlKata](https://github.com/sqlkata/querybuilder)-优雅的Sql查询生成器，支持复杂的查询，连接，子查询，嵌套where条件，供应商引擎目标等
### 队列和消息传递

* [emitter](https://emitter.io/)-免费的开源实时消息服务，连接所有设备。此发布-订阅消息传递API旨在提高速度和安全性。
* [EasyNetQ](https://github.com/EasyNetQ/EasyNetQ)-一个易于使用。NET API的RabbitMQ。
* [EventStore](https://github.com/EventStore/EventStore)-具有JavaScript复杂事件处理功能的开源数据库。
* [Foundatio](https://github.com/exceptionless/Foundatio#queues)-具有内存、redis和azure实现的通用接口。
* [MediatR](https://github.com/jbogard/MediatR)-简单、不雄心勃勃的调解人实施。NET。
* [MediatR.Extensions.Microsoft.DependencyInjection](https://github.com/jbogard/MediatR.Extensions.Microsoft.DependencyInjection)-Microsoft.extensions.DependencyInjection的MediatR扩展。
* [Mediator.Net](https://github.com/mayuanyang/Mediator.Net)-一个简单的调解人。Net用于发送命令，发布事件和支持管道的请求响应。
* [MicroBus](https://github.com/Lavinski/Enexure.MicroBus)-简单的进程中介。NET。
* [MQTTnet](https://github.com/chkr1011/MQTTnet)-MQTTnet是一个高性能。NET库进行基于MQTT的通信。
* [netmq](https://github.com/zeromq/netmq)-100% ZeroMQ for的原生C # 实现。NET。
* [OpenCQRS](https://github.com/OpenCQRS/OpenCQRS)-什么？-.NET Core库，用于与Azure服务总线集成的DDD、CQRS和事件源。命令和事件存储支持的数据库提供程序有: DocumentDB、MongoDB、SQL Server、MySQL、PostgreSQL和SQLite。
* [rabbitmq-dotnet-client](https://github.com/rabbitmq/rabbitmq-dotnet-client)-RabbitMQ.NET客户端[https://www.rabbitmq.com](https://www.rabbitmq.com)。
* [RawRabbit](https://github.com/pardahlman/RawRabbit)-很现代.NET框架，用于通过RabbitMq进行通信。
* [Rebus](https://github.com/rebus-org/Rebus)-简单和精益的服务总线实施。NET。
* [Restbus](http://restbus.org)-RabbitMq的消息库。
* [Silverback](https://github.com/BEagle1984/silverback)-构建事件驱动应用程序的框架 (支持Kafka，RabbitMQ，MQTT)。
* [Tossit](https://github.com/turgayozgur/tossit)-简单，易于使用的分布式作业/工人逻辑库。由内置的RabbitMQ实现处理的分布式消息。
### 报告

* [FastReport](https://github.com/FastReports/FastReport)-的开源报告生成器。NET Core 2.x/.Net Framework 4.x。FastReport可以在MVC，Web API应用程序中使用。
### 调度程序和作业

* [Chroniton.NetCore](https://github.com/leosperry/Chroniton)-轻量级的健壮库，用于按计划运行任务 (作业)。
* [Coravel](https://github.com/jamesmh/coravel)-什么？-.Net核心满足Laravel: 调度，排队等。
* [FluentScheduler](https://github.com/fluentscheduler/FluentScheduler)-具有流畅界面的自动作业调度程序。
* [Gofer.NET](https://github.com/brthor/Gofer.NET)-简单的C # API用于分布式后台任务/作业。NET核心。灵感来自芹菜的python。
* [HangfireIO](https://github.com/HangfireIO/Hangfire)-在ASP.NET应用程序中执行fire-and-forget，延迟和重复任务的简单方法[http://hangfire.io](http://hangfire.io)。
* [LiquidState](https://github.com/prasannavl/LiquidState)-高效的异步和同步状态机。NET。
* [NCrontab](https://github.com/atifaziz/NCrontab)-Crontab的。NET。
* [quartznet](https://github.com/quartznet/quartznet/)-Quartz企业调度程序。净值[http://www.quartz-scheduler.net](http://www.quartz-scheduler.net)。
* [stateless](https://github.com/dotnet-state-machine/stateless)-用于在C # 代码中创建状态机的简单库。
### SDKs

* [AWS SDK](https://github.com/aws/aws-sdk-net)-Amazon Web Services (AWS)。NET Core SDK组件。每个AWS服务都有自己的NuGet包。
* [azure-event-hubs-dotnet](https://github.com/azure/azure-event-hubs-dotnet)-什么？-.适用于Azure事件中心的NET标准客户端库。
* 区块链客户端
  * [Bittrex.Net](https://github.com/JKorf/Bittrex.Net)-C #。Net包装的Bittrex web API，包括所有功能易于访问和使用。
  * [Binance.Net](https://github.com/JKorf/Binance.Net)-什么？-.Net API包装器的Binance web API。
* [CakeMail.RestClient](https://github.com/Jericho/CakeMail.RestClient)-CakeMail的API的客户端。允许您发送事务性电子邮件，批量电子邮件，管理列表和联系人等。
* [consuldotnet](https://github.com/PlayFab/consuldotnet/tree/develop)-什么？-.NET API的领事。
* [csharp-nats](https://github.com/nats-io/csharp-nats)-C #。NET客户端的NATS消息传递系统。
* [DarkSkyCore](https://github.com/amweiss/dark-sky-core)-A.NET标准包装的[Dark Sky API](https://darksky.net/dev/docs)。
* [Docker.DotNet](https://github.com/Microsoft/Docker.DotNet)-什么？-.NET (C #) Docker API的客户端库。
* [firebase-admin-dotnet](https://github.com/firebase/firebase-admin-dotnet)-Firebase管理员。NET SDK
* [google-cloud-dotnet](https://github.com/GoogleCloudPlatform/google-cloud-dotnet)-Google Cloud客户端库。NET。
* [Manatee.Trello](https://github.com/gregsdennis/Manatee.Trello)-一个完全面向对象的。Net包装器，用于用C # 编写的Trello的RESTful API。
* [Microphone](https://github.com/rogeralsing/Microphone)-轻量级框架，用于使用Consul或ETCD集群的Web Api或NancyFx ontop运行自托管REST服务。
* [octokit.net](https://github.com/octokit/octokit.net)-的GitHub API客户端库。NET。
* [PreStorm](https://github.com/jshirota/PreStorm)-ArcGIS Server的并行REST客户端。
* [SendGrid-csharp](https://github.com/sendgrid/sendgrid-csharp)-C # 客户端库，用于使用完整的SendGrid API。
* [statsd-csharp-client](https://github.com/Pereingo/statsd-csharp-client)-什么？-.NET标准兼容的C # 客户端与Etsy的优秀接口[statsd](https://github.com/etsy/statsd)服务器。
* [tweetinvi](https://github.com/linvi/tweetinvi)-直观。NET C # 库来访问Twitter REST和STREAM API。
### 安全

* [aspnetcore-security-headers](https://github.com/juunas11/aspnetcore-security-headers)-用于向ASP.NET Core应用程序添加安全标头的中间件。
* [HtmlSanitizer](https://github.com/mganss/HtmlSanitizer)-清除HTML以避免XSS攻击。
* [jose-jwt](https://github.com/dvsekhvalnov/jose-jwt)-用于处理JOSE对象的库 (JWT，JWA，JWS和相关)。
* [Jwt.Net](https://github.com/jwt-dotnet/jwt)-Jwt.Net，的JWT (JSON Web令牌) 实现。NET。
* [JWT Simple Server](https://github.com/Xabaril/JWTSimpleServer)-用于ASP.NET Core的轻量级动态jwt服务器。
* [NWebsec](https://github.com/NWebsec/NWebsec)-ASP.NET的安全库[http://www.nwebsec.com](http://www.nwebsec.com)。
* [reCAPTCHA](https://github.com/PaulMiami/reCAPTCHA)-适用于ASP.NET Core的reCAPTCHA 2.0。
* [roslyn-security-guard](https://github.com/dotnet-security-guard/roslyn-security-guard)-Roslyn分析器，旨在帮助安全审计。NET应用程序。
* [OwaspHeaders](https://github.com/GaProgMan/OwaspHeaders.Core)-什么？-.NET Core中间件，用于注入Owasp推荐的HTTP标头以提高安全性。
* [Security](https://github.com/aspnet/Security)-用于web应用程序安全性和授权的中间件。
* [SecurityHeaders](https://github.com/andrewlock/NetEscapades.AspNetCore.SecurityHeaders)-允许向ASP.NET Core网站添加安全标头的小包。
### 正在搜索

* [Algolia.Search](https://github.com/algolia/algoliasearch-client-csharp)-官方Algolia的存储库。NET客户端。
* [AutoComplete](https://github.com/omerfarukz/autocomplete)-持久，简单，强大和便携式自动完成库。
* [Elasticsearch.Net & NEST](https://github.com/elastic/elasticsearch-net)-用于NEST和Elasticsearch.NET的存储库，这两个官方elasticsearch。NET客户端。
* [ElasticsearchCRUD](https://github.com/damienbod/ElasticsearchCRUD)-Elasticsearch.NET API。
* [SearchExtensions](https://github.com/ninjanye/SearchExtensions)-IQueryable接口的高级搜索功能，如实体框架查询。
* [SimMetrics.Net](https://github.com/StefH/SimMetrics.Net)-相似性度量库，例如从编辑距离 (Levenshtein，Gotoh，Jaro等) 到其他度量 (例如Soundex，Chapman)
* [SolrExpress](https://github.com/solr-express/solr-express)-简单和轻量级的查询。NET库的Solr，在一个受控的，可构建和失败的快速方式。
### 序列化

* [BinarySerializer](https://github.com/jefffhaynes/BinarySerializer)-自定义数据包和协议格式的序列化，支持位旋转。
* [bond](https://github.com/Microsoft/bond)-用于使用模式化数据的跨平台框架。它支持跨语言的de/serialization和强大的通用机制，可以有效地操作数据。Bond在Microsoft的大规模服务中广泛使用。
* [Channels](https://github.com/davidfowl/Channels)-基于推。NET流。
* [CsvHelper](https://github.com/JoshClose/CsvHelper)-库，以帮助读取和写入CSV文件。
* [Edi.Net](https://github.com/indice-co/EDI.Net)-EDI序列化器/反序列化器。支持EDIFact，X12和TRADACOMS格式。
* [ExtendedXmlSerializer](https://github.com/wojtpl2/ExtendedXmlSerializer)-扩展的Xml序列化程序。NET。
* [Jil](https://github.com/kevin-montrose/Jil)-快点.NET JSON (De) 序列化程序，基于Sigil构建。
* MessagePack
  * [msgpack-cli](https://github.com/msgpack/msgpack-cli)-用于公共语言基础设施的MessagePack实现/[msgpack.org](http://msgpack.org)。
  * [MessagePack-CSharp](https://github.com/neuecc/MessagePack-CSharp)-用于C #(.NET，.NET Core，Unity，Xamarin) 的非常快速的MessagePack序列化程序。
* [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json)-流行的高性能JSON框架。NET。
* [protobuf-net](https://github.com/mgravell/protobuf-net/)-用于惯用的协议缓冲区库。NET。
* [Schema.NET](https://github.com/RehanSaeed/Schema.NET)-Schema.org对象变成强类型的C # POCO类中使用。NET。所有类都可以序列化为JSON/json-ld和XML，通常用于在html页面的head部分表示结构化数据。
* [ServiceStack.Text](https://github.com/ServiceStack/ServiceStack.Text)-JSON，JSV和CSV文本序列化程序。
* [TinyCsvParser](https://github.com/bytefish/TinyCsvParser)-易于使用，易于扩展和用于CSV解析的高性能库。NET。
* [Wire](https://github.com/rogeralsing/Wire)-用于POCO对象的二进制序列化器
* [YamlDotNet](https://github.com/aaubry/YamlDotNet)-什么？-.净值
* [ZeroFormatter](https://github.com/neuecc/ZeroFormatter)-快速二进制 (de) 序列化器。NET
* [Utf8Json](https://github.com/neuecc/Utf8Json)-绝对最快和零分配JSON序列化为C #(NET，.NET Core，Unity，Xamarin)。
* [YAXLib](https://github.com/sinairv/YAXLib)-XML序列化库。NET框架和.NET核心。非常灵活和强大。
### 模板引擎

* [dotliquid](https://github.com/dotliquid/dotliquid)-什么？-.NET Port of Tobias l ü tke的Liquid模板语言。
* [fluid](https://github.com/sebastienros/fluid)-开源。NET模板引擎，它尽可能接近Liquid模板语言。
* [Portable.Xaml](https://github.com/cwensley/Portable.Xaml)-便携式的.NET库读取/写入xaml文件。
* [Razor](https://github.com/aspnet/Razor)-用于MVC web应用程序视图页面中使用的CSHTML文件的解析器和代码生成器。
* [RazorLight](https://github.com/toddams/RazorLight)-基于Microsoft的Razor解析引擎的模板引擎。NET核心。
* [Scriban](https://github.com/lunet-io/scriban)-一个快速，强大，安全和轻量级的文本模板语言和引擎。NET。
### 测试

* [Atata](https://github.com/atata-framework/atata)基于Selenium WebDriver的Web UI测试自动化全功能框架。[https://atata.io](https://atata.io)
* [Bogus](https://github.com/bchavez/Bogus)-简单和理智的假数据生成器为C #。基于并从著名的faker.js移植。
* [CoreBDD](https://github.com/stevenknox/CoreBDD)-用于r xUnit.net的BDD框架
* [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy)-简单的嘲笑库。NET。
* [FluentAssertions](https://github.com/fluentassertions/fluentassertions)-一套。NET扩展方法，使您可以更自然地指定TDD或BDD风格测试的预期结果。
* [GenFu](https://github.com/MisterJames/GenFu)-库，您可以使用生成现实的测试数据。
* [LightBDD](https://github.com/LightBDD/LightBDD)-BDD框架允许创建易于阅读和维护的测试。
* [mockhttp](https://github.com/richardszalay/mockhttp)-微软的HttpClient库的测试层。
* [moq.netcore](https://github.com/Moq/moq4)-最流行的和友好的嘲笑框架。NET。
* [MSpec](https://github.com/machine/machine.specifications)-用于编写BDD风格测试的流行测试框架。
* [MyTested.AspNetCore.Mvc](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc)-Fluent测试ASP.NET Core MVC框架。
* [Netling](https://github.com/hallatore/Netling)-负载测试器客户端，便于web测试。
* [NSpec](https://github.com/nspec/NSpec)-C # 的战斗强化测试框架，受到Mocha和RSpec的启发。
* [NSubstitute](https://github.com/nsubstitute/NSubstitute)-友好的替代品。NET嘲笑框架。
* [nunit](https://github.com/nunit/dotnet-test-nunit)-用于的NUnit测试运行程序。NET核心。
* [shouldly](https://github.com/shouldly/shouldly)-应该测试。NET-断言的方式* 应该* be![http://shouldly.readthedocs.org/en/latest](http://shouldly.readthedocs.org/en/latest)
* [SpecFlow](https://github.com/techtalk/SpecFlow)-实用的BDD解决方案。NET。它使用Gherkin规范语言并集成到Visual Studio。
* [Storyteller](https://github.com/storyteller/Storyteller)-可执行规范。净值[http://storyteller.github.io](http://storyteller.github.io)。
* [Stubbery](https://markvincze.github.io/Stubbery/)-一个用于在中创建和运行Api存根的简单库。NET。
* [Testavior](https://github.com/geeklearningio/Testavior)Testavior是一个轻量级的解决方案，可帮助您开发ASP.NET Core的行为测试。
* [TestStack.BDDfy](https://github.com/TestStack/TestStack.BDDfy)-有史以来最简单的BDD框架!
* [xBehave.net](https://github.com/xbehave/xbehave.net)-用于使用自然语言描述测试的n xUnit.net扩展。[http://xbehave.github.io](http://xbehave.github.io)
* [xUnit.net](https://github.com/xunit/xunit)-一个免费的，开源的，以社区为中心的单元测试工具。NET框架。
### 工具

* [CliFx](https://github.com/Tyrrrz/CliFx)-用于构建命令行接口的声明式框架。
* [CommandLineUtils](https://github.com/natemcmaster/CommandLineUtils)-命令行解析和实用程序。NET核心和。NET框架。
* [docfx](https://github.com/dotnet/docfx)-用于构建和发布API文档的工具。NET项目[http://dotnet.github.io/docfx](http://dotnet.github.io/docfx)
* [dotnetfiddle](https://dotnetfiddle.net)-什么？-.NET沙箱供开发人员快速试用代码和共享代码片段。
* [dotnet-tools](https://github.com/natemcmaster/dotnet-tools)-的工具扩展列表。NET Core命令行 (dotnet CLI)。
  * [LibMan CLI](https://github.com/aspnet/LibraryManager)-web应用程序的客户端内容管理器。
* [EntryPoint](https://github.com/Nick-Lucas/EntryPoint)-可组合的CLI (命令行) 参数解析器。Net核心 &。Net框架4.5。
* [Fake JSON Server](https://github.com/ttu/dotnet-fake-json-server)-用于原型设计或作为CRUD后端的假REST API。不需要定义类型，使用动态类型。数据存储到单个JSON文件中。具有身份验证，WebSocket通知，异步长时间运行的操作，随机生成错误/延迟和实验性GraphQL支持。
* [gitignore.io](https://github.com/joeblau/gitignore.io)-创建有用的。项目的gitignore文件[https://www.gitignore.io](https://www.gitignore.io)。
* [ICanHasDotnetCore](https://github.com/OctopusDeploy/ICanHasDotnetCore)-扫描上传的packages.config文件或GitHub存储库，并确定nuget包是否以.NET标准。
* [json2csharp](http://json2csharp.com)-从JSON生成C # 类。
* [letsencrypt-win-simple](https://github.com/Lone-Coder/letsencrypt-win-simple)-一个简单的Windows ACME客户端。
* [Linq_Faster](https://github.com/jackmott/LinqFaster)-类似于Linq的数组扩展函数，Span,和列表更快，分配更少。
* [mRemoteNG](https://github.com/mRemoteNG/mRemoteNG)-下一代mmremote，开源，选项卡式，多协议，远程连接管理器
* [NJsonSchema](https://github.com/RSuter/NJsonSchema)-NJsonSchema是一个.NET库来读取、生成和验证JSON架构草案v4架构。
* [NuKeeper](https://github.com/NuKeeperDotNet/NuKeeper)-自动更新中的nuget包。NET项目。
* [NuGetPackageExplorer](https://github.com/NuGetPackageExplorer/NuGetPackageExplorer)-使用GUI创建，更新和部署Nuget包。
* [NugetVisualizer](https://github.com/sepharg/NugetVisualizer)-为一组给定的git存储库或文件夹可视化所有nuget包及其相应的版本。
* [OctoLinker](https://github.com/OctoLinker/browser-extension)-通过导航使用适用于GitHub的OctoLinker浏览器扩展高效地处理文件。
* [posh-dotnet](https://github.com/bergmeister/posh-dotnet)-选项卡完成为[dotnet CLI](https://github.com/dotnet/cli)。
* [Rin](https://github.com/mayuki/Rin)-ASP.NET Core的请求/响应检查器中间件。像一瞥。
* [scoop](https://github.com/lukesampson/scoop)-Windows的命令行安装程序。
* [SerilogAnalyzer](https://github.com/Suchiman/SerilogAnalyzer)-使用Serilog日志记录库对代码进行基于Roslyn的分析。检查常见错误和使用问题。
* [SharpZipLib](https://github.com/icsharpcode/SharpZipLib)# ziplib是一个完全用C # 编写的Zip，GZip，Tar和BZip2库。NET平台。
* [ShareX](https://github.com/ShareX/ShareX)-免费的开源程序，让您捕获或记录屏幕的任何区域，并与一键共享。它还允许将图像，文本或其他类型的文件上传到您可以选择的80多个受支持的目的地。[https://getsharex.com](https://getsharex.com)
* [SharpLab](https://github.com/ashmind/SharpLab)-什么？-.NET代码游乐场，显示代码编译的中间步骤和结果。[https://sharplab.io](https://sharplab.io)
* [SmartCode](https://github.com/Ahoo-Wang/SmartCode)-SmartCode = IDataSource -> IBuildTask -> IOutput => 构建一切!(包括 [代码生成器])
* [sourcelink](https://github.com/dotnet/sourcelink)-SourceLink是一个与语言和源代码控制无关的系统，用于为二进制文件提供一流的源代码调试体验。
* [System.CommandLine](https://github.com/dotnet/command-line-api)-System.CommandLine，一组用于命令行解析、调用和呈现终端输出的库。
* [Typin](https://github.com/adambajguz/Typin)-简单易用的声明性框架，用于交互式CLI应用程序和命令行工具 (直接模式)，其根源在于CliFx。
* [X.Web.Sitemap](https://github.com/dncuug/X.Web.Sitemap)-简单的网站地图生成器。NET和。NET核心
* [X.Web.RSS](https://github.com/dncuug/X.Web.RSS)-简单的RSS提要生成器。NET和。NET核心
### Web框架

* WebAssembly
  * [Blazor](https://github.com/SteveSanderson/Blazor)-UI框架正在运行。NET在浏览器中通过WebAssembly。
  * [Awesome Blazor](https://github.com/AdrienTorris/awesome-blazor)-关于Blazor的Awesome 资源 (样品，组件，文章，视频等) 的集合。
  * [Blazor Redux](https://github.com/torhovland/blazor-redux)-将 “恢复状态” 存储与Blazor连接。
  * [Ooui](https://github.com/praeclarum/Ooui)-小型跨平台UI库，将本机UI开发的简单性带入web。
* [ReactJS.NET](https://github.com/reactjs/React.NET)-什么？-.NET库，用于JSX编译和React组件的服务器端渲染。
* [redux.NET](https://github.com/GuillaumeSalles/redux.NET)-可预测的状态容器。NET应用程序。灵感来自[https://github.com/reactjs/redux](https://github.com/reactjs/redux)。
### Web套接字

* [Fleck](https://github.com/statianzo/Fleck)-Fleck是C # 中的WebSocket服务器实现。Fleck不需要继承、容器或其他引用。
* [SignalR Server](https://github.com/aspnet/signalr)-web应用程序的实时web功能，包括服务器端推送。
* [SuperSocket](https://github.com/kerryjiang/SuperSocket)-重量轻，跨平台和可扩展的套接字服务器应用程序框架。
* [WampSharp](https://github.com/Code-Sharp/WampSharp)-C # 实现[The Web Application Messaging Protocol](http://wamp-proto.org/)-通过WebSockets提供远程过程调用和发布/订阅的消息传递模式的协议。
* [websocket-manager](https://github.com/radu-matei/websocket-manager)-ASP的实时库。NET核心。
### Windows服务

* [dotnet-win32-service](https://github.com/dasMulli/dotnet-win32-service)-直接从设置和运行Windows服务。NET核心。
* [Topshelf](https://github.com/Topshelf/Topshelf)-使用构建Windows服务的简易服务托管框架。NET。
### 工作流

* [CoreWF](https://github.com/dmetzgar/corewf/)-Windows Workflow Foundation (WF) 的端口到。NET核心。
* [workflow-core](https://github.com/danielgerlag/workflow-core)-轻量级的工作流引擎。NET标准。
* [WorkflowEngine.NET](https://github.com/optimajet/WorkflowEngine.NET)-在应用程序中添加工作流的组件。
* [Wexflow](https://github.com/aelassas/Wexflow)-高性能，可扩展，模块化和跨平台的工作流引擎。
## 路线图

* [ASP.NET Core Developer Roadmap](https://github.com/MoienTajik/AspNetCore-Developer-Roadmap)-成为ASP.NET Core开发人员2019年的路线图。
## 初学者工具包

* [Arch](https://github.com/Arch)-收藏。NET Core库，这些库是由软件架构师创建的，他们在.NET核心。
  * [AutoHistory](https://github.com/Arch/AutoHistory)-Microsoft.EntityFrameworkCore的插件，支持自动记录数据更改历史记录。
* [AspNetCore-Angular2-Universal](https://github.com/MarkPieszak/aspnetcore-angular2-universal)-跨平台-w/服务器端渲染SEO，Bootstrap，i18n国际化 (ngx-translate)，Webpack，TypeScript，单元测试w/ Karma，WebAPI REST设置，SignalR，Swagger文档等!
* [ASP.NET Core Starter Kit](https://github.com/kriasoft/aspnet-starter-kit)基于web开发的自以为是的样板。NET Core，Kestrel，GraphQL在后端，Babel，Webpack，React和前端。这个样板有C # 和F # 两种风格。
* [aspnetcore-spa generator](https://github.com/aspnet/JavaScriptServices)-Yeoman generator构建一个全新的ASP.NET Core单页应用程序，该应用程序在客户端上使用Angular 2/React与Redux/Knockout/Aurelia。
* [ASP.Net Core Vue Starter](https://github.com/MarkPieszak/aspnetcore-Vue-starter)-Asp.NETCore 2.0 Vue 2 (ES6) SPA入门套件，包含路由，Vuex等!
* [bitwarden-core](https://github.com/bitwarden/core)-核心基础架构后端 (API、数据库等)[https://bitwarden.com](https://bitwarden.com)。
* [dotNetify](https://github.com/dsuryd/dotNetify)-简单，轻量级，但强大的方式来构建实时HTML5/C #。NET web应用程序。
* [generator-aspnet](https://github.com/OmniSharp/generator-aspnet)-用于ASP.NET Core的yo生成器。
* [Nucleus](https://github.com/alirizaadiyahsi/Nucleus)-Vue启动应用程序模板，在后端使用ASP.NET Core API分层架构和基于JWT的身份验证
* [react-aspnet-boilerplate](https://github.com/pauldotknopf/react-aspnet-boilerplate)-使用ASP.NET Core 1构建同构React应用程序的起点，利用现有技术。
* [saaskit](https://github.com/saaskit/saaskit)-用于构建SaaS应用程序的开发人员工具包。
* [serverlessDotNetStarter](https://github.com/pharindoko/serverlessDotNetStarter)用于在基于无服务器框架的AWS云中开发和部署lambda函数的入门工具包。
## 示例项目

* 微服务和服务网格
  * [clean-architecture-dotnet](https://github.com/thangchung/clean-architecture-dotnet)-在电子商务示例业务域上应用ddd-lite，cqrs-lite和足够的云原生模式的最小干净架构
  * [coolstore-microservices ](https://github.com/vietnam-devs/coolstore-microservices)-一个基于Kubernetes的多语言微服务应用程序，带有Istio服务网格
  * [distributed-playground](https://github.com/jvandevelde/distributed-playground)-具有流浪，领事，Docker和ASP.NET Core的分布式服务游乐场。
  * [DNC-DShop](https://github.com/devmentors)-分发。NET Core项目和免费课程。说明: DDD，CQRS，RabbitMQ，MongoDB，Redis，监控，日志记录，CI，CD
  * [dotnetcore-microservices-poc](https://github.com/asc-lab/dotnetcore-microservices-poc)-简化了在微服务架构中使用的保险销售系统。NET Core (EF Core，MediatR，Marten，Eureka，Ocelot，RabbitMQ，Polly，ElasticSearch，Dapper) 与博客文章系列。
  * [eShopOnContainers](https://github.com/dotnet/eShopOnContainers)-基于微服务架构和容器的参考应用程序。
  * [InMemoryCQRSReplication](https://github.com/Aaronontheweb/InMemoryCQRSReplication)-Akka.NET参考架构-CQRS分片内存复制
  * [magazine-website](https://github.com/thangchung/magazine-website)-杂志网站 (使用.NET Core，ASP.NET Core，EF Core) 与DDD，CQRS，微服务，异步编程应用。
  * [microservices-in-dotnetcore](https://github.com/horsdal/microservices-in-dotnet-book-second-edition)-第二版的代码示例[Microservices in .NET Core](https://www.manning.com/books/microservices-in-net-core-second-edition)。
  * [practical-dapr](https://github.com/thangchung/practical-dapr)-全栈。NET微服务基于Dapr和Tye。
  * [ReactiveTraderCloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud)-实时交易平台演示，展示了在整个应用程序堆栈中应用的反应式编程原理。
* 整料
  * [AlbumViewerVNext](https://github.com/RickStrahl/AlbumViewerVNext)-西风相册查看器ASP.NET 5示例。
  * [allReady](https://github.com/HTBox/allReady)-开源解决方案，侧重于提高当地社区人道主义和救灾组织开展的备灾运动的认识、效率和影响。[http://www.htbox.org/projects/allready](http://www.htbox.org/projects/allready)
  * [AspNet5GeoElasticsearch](https://github.com/damienbod/AspNet5GeoElasticsearch)-ASP.NET Core MVC Geo Elasticsearch Swashbuckle Swagger.
  * [aspnet-servicediscovery-patterns](https://github.com/cecilphillip/aspnet-servicediscovery-patterns)-使用ASP.NET Core实现服务发现模式的示例。
  * [AspNetAuthorizationWorkshop](https://github.com/blowdart/AspNetAuthorizationWorkshop)-一个通过ASP.NET Core授权中的各种新片段的研讨会
  * [BikeSharing360 Suite of Apps from Microsoft](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/)12月Connect 2016会议，这是一组面向企业用户和消费者 (自行车骑手) 的可压缩互通应用程序:[Mobile Apps](https://github.com/Microsoft/BikeSharing360_MobileApps),[Backend Services](https://github.com/Microsoft/BikeSharing360_BackendServices),[Websites](https://github.com/Microsoft/BikeSharing360_Websites),[Single Container Apps](https://github.com/Microsoft/BikeSharing360_SingleContainer),[Multi Container Apps](https://github.com/Microsoft/BikeSharing360_MultiContainer),[Cognitive Services Kiosk App](https://github.com/Microsoft/BikeSharing360_CognitiveServicesKioskApp),[Azure Bot App](https://github.com/Microsoft/BikeSharing360_BotApps)。
  * [Clean Architecture Manga](https://github.com/ivanpaulovich/clean-architecture-manga)-干净的架构样本。NET Core 3.0和C #8。用例作为中央组织结构，完全可测试，与框架分离。
  * [cloudscribe](https://github.com/cloudscribe/cloudscribe)-ASP.NET Core多租户web应用程序基础。
  * [CoreCodeCamp](https://github.com/shawnwildermuth/CoreCodeCamp)-一个用于运行小型本地开发活动的开源网站。
  * [DotNetClub](https://github.com/scheshan/DotNetClub)-用ASP.NET Core编写的Tiny club。
  * [eShopOnWeb](https://github.com/dotnet-architecture/eShopOnWeb)-具有单片部署模型的分层应用程序体系结构。
  * [Entropy](https://github.com/aspnet/Entropy)-混沌实验游乐场的新功能和想法-检查这里的小而简单的样本为个别功能。
  * [EquinoxProject](https://github.com/EduardoPires/EquinoxProject)-具有DDD，CQRS和事件源的完整ASP.NET Core 2.0应用程序。
  * [GenVue](https://github.com/herbat73/GenVue)-一个可托管的web应用程序，允许机密用户上传和共享基于Vue.js，Vuetifyjs和NetCore WebAPI堆栈的私有文件
  * [guidance-identity-management-for-multitenant-apps](https://github.com/Azure-Samples/guidance-identity-management-for-multitenant-apps)-如何在Microsoft Azure上的多租户应用程序中管理用户身份，使用Azure Active Directory进行身份验证。
  * [JustA.ML](https://github.com/mustakimali/JustA.ML)-一个web应用程序，可让您在使用ASP.NET Core 2.0编写的设备之间共享文件/URL/文本。开源，住在[https://justa.ml](https://justa.ml)
  * [MegaMine](https://github.com/Nootus/MegaMine)-开源采矿解决方案，可帮助矿工提取黄金，石英，花岗岩等。此解决方案是使用ASP.NET Core和AngularJS以微服务的方式利用多个轻量级组件构建的。
  * [MusicStore](https://github.com/dotnet/aspnetcore/tree/master/src/MusicStore)-使用MVC和实体框架的示例MusicStore应用程序。
  * [NLayerAppV3](https://github.com/cesarcastrocuba/nlayerappv3)-NLayerAppV3 N层架构与NET Core Preview 2.
  * [NorthwindTraders](https://github.com/JasonGT/NorthwindTraders)Northwind Traders是一个使用ASP.NET Core和Entity Framework Core构建的示例应用程序。
  * [Orchard Core - Modular and Multi-tenant applications](https://github.com/OrchardCMS/OrchardCore.Samples)-使用Orchard核心框架创建模块化和多租户应用程序。
  * [PhotoGallery](https://github.com/chsakell/aspnet5-angular2-typescript)-使用ASP.NET Core，Angular 2和TypeScript的跨平台单页应用程序[http://wp.me/p3mRWu-11L](http://wp.me/p3mRWu-11L)。
  * [PokeR](https://github.com/halomademeapc/pokeR)-在ASP.NET Core的SPA托管中使用SignalR和Angular的实时scrum扑克。包括Docker支持。[Demo](https://planning.halomademeapc.com)
  * [Practical ASP.NET Core](https://github.com/dodyg/practical-aspnetcore)-每日更新的ASP.NET Core功能和设施的微样本。
  * [Sample .NET Core CQRS REST API](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api)-什么？-.NET Core REST API CQRS实现与原始SQL和DDD使用干净的架构。
  * [StarWars](https://github.com/JacekKosciesza/StarWars)-使用GraphQL for的GraphQL “星球大战” 示例。NET、ASP.NET Core、Entity Framework Core。
## 文章

* 基础知识
  * [Microsoft architectural overview of comprehensive BikeSharing360 suite of demo apps with related videos](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/)
  * [Porting a .NET Framework library to .NET Core](https://www.codeproject.com/Articles/1190475/Porting-a-NET-Framework-library-to-NET-Core)
  * [The 68 things the CLR does before executing a single line of your code](http://mattwarren.org/2017/02/07/The-68-things-the-CLR-does-before-executing-a-single-line-of-your-code/)
  * 之间的比较。NET Core和Nodejs在[here](https://manuel-rauber.com/2016/03/07/node-js-asp-net-core-1-0-a-usage-comparison/),[here](https://gist.github.com/ilyaigpetrov/f6df3e6f825ae1b5c7e2)和[here](https://github.com/thinktecture/nodejs-aspnetcore-webapi)
  * [Understanding ASP.NET Core Initialization](http://developer.telerik.com/featured/understanding-asp-net-core-initialization/)
  * [Why you should join .NET Core and ASP.NET Core train](https://codingblast.com/why-you-should-join-asp-net-core/)
* 云开发
  * [Configuring the AWS SDK in .NET Core](https://aws.amazon.com/blogs/developer/configuring-aws-sdk-with-net-core/)
  * [Serverless Architecture using C# and AWS Amazon Gateway Api/Lambda](https://www.codeproject.com/Articles/1178781/Serverless-Architecture-using-Csharp-and-AWS-Amazo)
  * [Using C# and .NET Core in Amazon Web Services (AWS) Lambda](https://aws.amazon.com/blogs/compute/announcing-c-sharp-support-for-aws-lambda/)
* 配置和部署
  * [.NET project structure](https://gist.github.com/davidfowl/ed7564297c61fe9ab814)
  * [Adding Travis CI builds to a .NET Core app](http://andrewlock.net/adding-travis-ci-to-a-net-core-app/)
  * [ASP.NET Core 1.0 - Configure ApplicationInsights](http://social.technet.microsoft.com/wiki/contents/articles/35918.asp-net-core-1-0-configure-applicationinsights.aspx)
  * [haproxy, nginx, Angular 2, ASP.NET Core, Redis and Docker](http://tattoocoder.azurewebsites.net/legion-of-heroes-haproxy-nginx-angular2-aspnetcore-redis-docker/)
  * [Project.json to MSBuild conversion guide](http://www.natemcmaster.com/blog/2017/01/19/project-json-to-csproj/)
  * [Publishing a .NET project with Appveyor and NuGet](https://few-lines-of-code.blogspot.com/2016/03/publishing-net-project-with-appveyor.html)
  * [The New Configuration Model in ASP.NET Core](http://developer.telerik.com/featured/new-configuration-model-asp-net-core/)
* 实体框架核心
  * [.NET Core Data Access](https://blogs.msdn.microsoft.com/dotnet/2016/11/09/net-core-data-access/)
  * [A very good example about EF Core](https://github.com/rowanmiller/Demo-EFCore)
  * [Connect to Postgres with EF Core](http://en.otomatikmuhendis.com/2017/05/05/connect-to-postgres-with-ef-core/)
* 奇迹
  * [Getting started with Orchard Core as a NuGet package](http://www.ideliverable.com/blog/getting-started-with-orchard-core-as-a-nuget-package)
  * [How to export HTML to PDF in ASP.NET Core](https://code.msdn.microsoft.com/How-to-export-HTML-to-PDF-c5afd0ce)
  * [Vue.js server side rendering with ASP.NET Core](http://mgyongyosi.com/2016/Vuejs-server-side-rendering-with-aspnet-core/)
* 安全
  * [.NET Continuous Delivery Microservices](http://stackshare.io/tomstaijen/net-continuous-delivery-microservices)
  * [ASP.NET Core 2.0 Authentication and Authorization System Demystified](https://digitalmccullough.com/posts/aspnetcore-auth-system-demystified.html)
  * [A walk-through for an ASP.NET Authorization Lab](https://github.com/blowdart/AspNetAuthorizationWorkshop)
  * [Authentication in ASP.NET Core](https://stormpath.com/blog/authentication-asp-net-core)
* 测试
  * [Selenium with .NET Core](http://www.dotnetcatch.com/2016/11/23/selenium-with-net-core/)
- [InfoQ .NET articles](https://www.infoq.com/dotnet)-最好的收藏。InfoQ网站上的NET文章
## 图书

* [.NET Core in Action](https://manning.com/books/dotnet-core-in-action)
* [ASP.NET Core Application Development: Building an application in four sprints (Developer Reference)](https://www.amazon.com/ASP-NET-Core-Application-Development-application/dp/1509304061)
* [ASP.NET Core in Action](https://www.manning.com/books/asp-net-core-in-action)
* [ASP.NET Core 1.0 High Performance](https://www.amazon.com/ASP-NET-Core-1-0-High-Performance/dp/1785881892)
* [Building Microservices with ASP.NET Core: Develop, Test, and Deploy Cross-Platform Services in the Cloud](https://www.amazon.com/Building-Microservices-ASP-NET-Core-Cross-Platform/dp/1491961732)
* [C# 6 and .NET Core 1.0: Modern Cross-Platform Development](https://www.amazon.com/NET-Core-1-0-Cross-Platform-Development/dp/1785285696)
* [C# in Depth 4](https://www.amazon.com/C-Depth-Jon-Skeet/dp/1617294535)
* [Dependency Injection in .NET Core, 2nd edition](https://www.manning.com/books/dependency-injection-in-dot-net-second-edition)
* [Essencial C# 7.0](https://www.amazon.com/Essential-7-0-Addison-Wesley-Microsoft-Technology/dp/1509303588)
* [Exploring .NET Core with Microservices, ASP.NET Core, and Entity Framework Core - free eBook sampler](https://www.manning.com/books/exploring-dot-net-core)
* [Microservices in .NET Core: with C#, the Nancy framework, and OWIN middleware](https://www.amazon.com/Microservices-NET-Core-framework-middleware/dp/1617293377)
* [Professional C# 6 and .NET Core 1.0](https://www.amazon.com/Professional-NET-Core-Christian-Nagel/dp/111909660X)
* [The little ASP.NET Core](https://www.recaffeinate.co/book)
## 视频

* [Channel9](https://channel9.msdn.com)-MSDN
* [Channel9](https://www.youtube.com/channel/UCsMica-v34Irf9KVTh6xx-g)-YouTube
* [Microsoft Learning Center](https://dotnet.microsoft.com/learn/aspnet)
* [ASP.NET Monsters](https://channel9.msdn.com/Series/aspnetmonsters)
* [Visual Studio](https://www.youtube.com/user/VisualStudio/channels)
## 播客

* [.NET Rocks](https://www.dotnetrocks.com)
* [Merge Conflict](http://www.mergeconflict.fm/)
* [The sound of .NET](http://thesoundof.net/?q=.NET+Core)
## 社区

* [.NET Foundation](http://forums.dotnetfoundation.org)
* [.NET Blog](https://devblogs.microsoft.com/dotnet/)
* [/r/CoolGithubProjects](https://www.reddit.com/r/coolgithubprojects)
* [ASP.NET](https://forums.asp.net)
* [Channel9](https://channel9.msdn.com)
* [Awesome .NET open source & community resources](https://discoverdot.net)
* [Slack](http://tattoocoder.com/aspnet-slack-sign-up)
* [BuiltWithDot.Net](https://builtwithdot.net)
* 堆栈溢出
  * [.NET Core](https://stackoverflow.com/questions/tagged/.net-core)
  * [CoreCLR](https://stackoverflow.com/questions/tagged/coreclr)
  * [ASP.NET Core](https://stackoverflow.com/questions/tagged/asp.net-core)
  * [ASP.NET Core MVC](https://stackoverflow.com/questions/tagged/asp.net-core-mvc)
  * [ASP.NET Core 1.0](https://stackoverflow.com/questions/tagged/asp.net-core-1.0)
  * [Entity Framework Core](https://stackoverflow.com/questions/tagged/entity-framework-core)
* [Trending .NET repositories on GitHub today](https://github.com/trending?l=csharp)
## 许可证

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，[thangchung](http://weblogs.asp.net/thangchung)已放弃本作品的所有版权和相关或邻接权。

