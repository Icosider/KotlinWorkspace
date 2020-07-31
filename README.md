# KotlinWorkspace 1.12.2 ![Build](https://github.com/Ivasik78/KotlinWorkspace/workflows/Build/badge.svg)
Полностью рабочая и готовая к разработке на kotlin работа-космос.

## Пояснение на счёт Mixin
Если у Вас возник вопрос почему в проекте написанном на Kotlin используются миксины написанные на Java, то отвечают.
Это связано с тем, что Kotlin не может разобрать все случаи при написании миксинов разработчиком мода, как при Java.
Разработчик миксинов настаивает на том, чтобы миксины писались исключительно на Java.
Вы можете использовать Kotlin/Scala для написания миксинов, но все последующие сложности, 
которые возникнут у Вас при написании миксинов, ложатся только на **Ваши** плечи!
Не надо писать разработчику в issue, что у Вас, что-то не работает при использовании миксинова с Kotlin/Scala,
подобные темы автоматически **игнорируются**!
