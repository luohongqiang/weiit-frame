# weiit-frame
经典模块化Java快速开发轻量级框架，基于Spring+SpringMVC+Mybatis框架，解决java快速开发问题。去实体化快速开发、模块化开发、集成shiro安全框架、微信公众号开发集成、微信小程序开发集成、微信支付集成、微信第三方开发平台集成与一体的开源解决方案。

一、WEIIT框架目前围绕解决的企业开发问题：
1、框架前景问题：

框架基于Spring+SpringMVC+Mybatis主流开发框架，但需要提高SSM开发时的效率问题，并且要考虑SpringBoot、Springcloud以后要成为主流的问题。

2、提高开发效率，去实体化快速开发，统一参数FormMap与返回E对象，常规方法省略不写：

框架技术SSM的开发标准的同时，将传统的entity（bean、dto）、dao（mapper）、service、impl，controller层，去掉了实体层entity（bean、dto），同时层与层之间的参数传递时采用统一的FormMap进行，返回结果采用统一的E对象进行存储，让Java开发者不用去关注参数与返回值，并且常规方法统一省略不写，以实现自关注特殊业务的编写的原则，从而实现快速开发。

3、模块化开发：

企业在开发项目中，为了解决某些业务模块可以重复利用，框架同时也提供了对模块化的开发设计与支持，比如系统管理（管理员管理、权限管理、菜单管理）这个一个模块，被复用性比较高的，可以打包成jar支持，其他的项目依赖即可热插进去。


4、集成shiro安全框架：

企业账户登录问题，常常需要采用security、shiro这类框架，我们已经整合了Shiro作为框架校验框架作为登录支持。


5、定时任务中央集权管控：

Java人员经常在开发的时候，会遇到一个企业项目中经常需要使用定时任务的需求，传统的开发都是使用Spring自带的quartz 注解或者注入进行业务展开，但是当发现一个企业管理多个项目，多定时任务时，很难管理好这些定时任务的配置，并且定时任务如果按照Spring自带的，往往改了配置还需要重启应用的问题。针对这种问题，像华为当时设计了一种中央集权的定时任务设计，即专门用一个项目专门管理所有项目的定时任务，并可以监控，还不需要重启。WEIIT同样提供了定时任务中央集权的设计思路。


6、微信公众号开发集成：

4年前的公众号已经被得到商业运用，相信开发过的人都知道其重要性，而WEIIT团队是真正从事了微信产品开发建设多年的团队，现在WEIIT框架也已经可以完美集成所有微信公众号的api的集成与运用。


7、微信小程序开发集成：

小程序一定是未来的趋势，针对小程序WEIIT框架同样进行了完美的整合，并可以提供各种商用解决方案。


8、微信支付集成：

微信生态中最重要的微信支付，WEIIT也是整合的，无论是小程序的微信支付对接支持、公众号的微信支付对接支持，都是可以支持。记住，小程序的微信支付、公众号的微信支付，这里会牵扯出各种配置的问题，以及微信支付绑定应用appid等各种问题，不懂的人还真觉得两者就是一个对接方式。


9、微信第三方开发平台集成：

   微信第三方开发平台，是微信为了方便企业同时服务多方企业提供解决方案而设计的一种对接支持，即企业的权利先委托给第三方，今后由第三方代替其调用API,往往被用于saas服务产品建设中,WEIIT框架同样可以提供支持。

二、技术交流方式
QQ群：321771500

三、版本说明：
本项目马上将会发布，请期待。
