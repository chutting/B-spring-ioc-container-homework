主观题：@Component 已经可以支持声明一个 bean 了，为何还要再弄个 @Bean 出来？

答：

因为@Bean和@Configuration配合，可以用于注入不方便标注@Component的类（如第三方的类），自定义能力更强

