# curated-laravel

This repository mainly collects curated resources for Laravel.

这个仓库主要收集针对 Laravel 有策划的资源。

> The goal of the warehouse is to streamline and quality resources to help developers quickly find the right Laravel resource.
>
> 仓库的目标是简化且优质资源，帮助开发人员快速找到合适的 Laravel 资源。

- [Laravel 文档](#laravel-docs)
- [Laravel 教程](#laravel-tutorial)
- [Laravel 拓展包](#laravel-packages)
    - [Laravel 官方拓展包](#laravel-official-packages)

<a name="laravel-docs"></a>
## Laravel 文档

- `英文` [Laravel 官方文档](https://laravel.com/docs)
- `中文` [Laravel China - 中文文档（5.1 - 5.6）](https://laravel-china.org/docs/laravel)
- `中文` [Laravel 学院 - 5.5 中文文档](http://laravelacademy.org/laravel-docs-5_5)

<a name="laravel-tutorial"></a>
## Laravel 教程

- `付费` `中文` [Laravel 教程 - Web 开发实战入门 ( Laravel 5.5 )](https://laravel-china.org/courses/laravel-essential-training-5.5)

<a name="laravel-packages"></a>
## Laravel 拓展包

<a name="laravel-official-packages"></a>
### Laravel 官方拓展包

#### [Cashier 交易工具包](https://github.com/laravel/cashier)

Laravel Cashier 提供了直观、流畅的接口来接入 Stripe's 和 Braintree's 订阅付费服务。它可以处理几乎所有你写起来非常头疼付费订阅代码。除了提供基本的订阅管理之外，Cashier 还可以帮你处理优惠券，交换订阅、订阅“数量”、取消宽限期，甚至还可以生成 PDF 文档。

- `英文` [Laravel 官方 - Laravel 5.6 Cashier 交易工具包文档](https://laravel.com/docs/5.6/billing)
- `中文` [Laravel China - Laravel 5.5 Cashier 交易工具包中文文档](https://laravel-china.org/docs/laravel/5.5/billing)

#### [Envoy 部署工具](https://github.com/laravel/envoy)

Laravel Envoy 为定义在远程服务器上运行的通用任务提供了一种简洁、轻便的语法。它使用了 Blade 风格的语法，让你可以很方便的启动任务来进行项目部署、Artisan 命令运行等操作。目前，Envoy 只支持 Mac 及 Linux 操作系统。

- `英文` [Laravel 官方 - Laravel 5.6 Envoy 部署工具文档](https://laravel.com/docs/5.6/envoy)
- `中文` [Laravel China - Laravel 5.5 Envoy 部署工具中文文档](https://laravel-china.org/docs/laravel/5.5/envoy)

#### [Horizon](https://github.com/laravel/horizon)

Horizon 为 Laravel 官方出品的 Redis 队列提供了一个可以通过代码进行配置、并且非常漂亮的仪表盘，并且能够轻松监控队列的任务吞吐量、执行时间以及任务失败情况等关键指标。

队列执行者的所有配置项都存放在一个简单的配置文件中，所以团队可以通过版本控制进行协作维护。

- `英文` [Laravel 官方 - Laravel 5.6 Horizon 文档](https://laravel.com/docs/5.6/horizon)
- `中文` [Laravel China - Laravel 5.5 Horizon 中文文档](https://laravel-china.org/docs/laravel/5.5/horizon)

#### [Scout](https://github.com/laravel/scout)

Laravel Scout 为 Eloquent 模型 的全文搜索提供了一个简单的、基于驱动程序的解决方案。使用模型观察员，Scout 会自动同步你的搜索索引和 Eloquent 记录。

目前，Scout 自带了一个 Algolia 驱动；而编写自定义驱动程序很简单，你可以自由地使用自己的搜索实现来扩展 Scout。

- `英文` [Laravel 官方 - Laravel 5.6 Scout 文档](https://laravel.com/docs/5.6/scout)
- `中文` [Laravel China - Laravel 5.5 Scout 中文文档](https://laravel-china.org/docs/laravel/5.5/scout)
