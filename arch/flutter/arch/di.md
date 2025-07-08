# 依赖注入框架 (Dependency Injection)

用于解耦和管理类之间的依赖关系。

-   **get_it**: Flutter社区最流行的服务定位器（Service Locator）。它并非严格意义上的依赖注入容器，但以其轻量、快速、简单易用的特性，在实践中被广泛用于依赖管理。
-   **injectable**: 一个基于`get_it`的代码生成器。通过注解的方式，它可以自动生成所有依赖注册的模板代码，减少了手动注册的工作量，并保证了类型安全，特别适合大型项目。
-   **Riverpod / Provider**: 这两个状态管理框架本身也具备强大的依赖注入能力。通过它们的`Provider`，可以方便地将服务（如Repository、ApiService）注入到Widget树中，供子Widget消费。
