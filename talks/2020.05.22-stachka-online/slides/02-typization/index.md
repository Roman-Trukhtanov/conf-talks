# Typization

-----

- 2) Излагаем идею
  - Graphql строго типизированный, JS тоже может быть строготипизированным, а значит... (можно генерить тайпинги из graphql запросов)
  - Это круто и защищает нас от ошибок
  - Но это куча импортов, а хороший программист -- ленивый программист. Так что пусть машина пишет код за нас
  - Показать пример с обычным apollo-хуком
  - Делаем вывод о том, что когда мы используем автотипизацию и обычные хуки мы постоянно делаем одно и то же, поэтому пусть за нас это делает инструмент
  - И этот инструмент: graphql-code-generator