### **Краткая шпаргалка по Java для подготовки к собеседованию**

---

## [**1. Java Core**](/docs/1_JavaCore.md)
- **Основы**: переменные, операторы, циклы, условия.
- **ООП**: классы, объекты, наследование, полиморфизм, инкапсуляция, абстракция.
- **Исключения**: `try-catch-finally`, `throws`, кастомные исключения.
- **Интерфейсы и абстрактные классы**: отличие, `default`-методы, `static`-методы.
- **Generics**: обобщённые классы и методы (`List<T>`).
- **Stream API**: `map`, `filter`, `reduce`, `collect`.
- **Функциональные интерфейсы**: `Predicate`, `Function`, `Consumer`, `Supplier`.
- **Модульность (Java 9+)**: `module-info.java`.

---

## [**2. Collections**](/docs/2_JavaCollections.md)
- **Интерфейсы**:
    - `List` (`ArrayList`, `LinkedList`) – упорядоченные, допускают дубликаты.
    - `Set` (`HashSet`, `TreeSet`) – уникальные элементы.
    - `Queue` (`LinkedList`, `PriorityQueue`) – FIFO/LIFO.
    - `Map` (`HashMap`, `TreeMap`) – пары ключ-значение.
- **Сравнение**:
    - `ArrayList` vs `LinkedList` – доступ по индексу vs вставка/удаление.
    - `HashMap` vs `TreeMap` – хэш-таблица vs сортировка по ключу.
- **Итерация**: `for-each`, `Iterator`, `forEach()`.

---

## [**3. Concurrency (Многопоточность)**](/docs/3_JavaConcurrency.md)
- **Потоки**: `Thread`, `Runnable`, `Callable`.
- **Синхронизация**: `synchronized`, `Lock`, `volatile`.
- **Пул потоков**: `ExecutorService`, `ThreadPoolExecutor`.
- **Коллекции**: `ConcurrentHashMap`, `CopyOnWriteArrayList`.
- **Атомарные операции**: `AtomicInteger`, `AtomicReference`.
- **Проблемы**: deadlock, race condition, livelock.

---

## [**4. JVM (Java Virtual Machine)**](/docs/4_JVM.md)
- **Состав**:
    - **ClassLoader** – загрузка классов.
    - **Runtime Data Areas** – Heap, Stack, Method Area.
    - **Garbage Collector** – сборка мусора (Serial, Parallel, G1, ZGC).
- **Оптимизация**:
    - JIT-компиляция.
    - Настройка памяти (`-Xms`, `-Xmx`).
- **Профилирование**: `jconsole`, `VisualVM`, `Java Flight Recorder`.

---

## [**5. Spring Framework**](/docs/5_SpringFramework.md)
- **Core**: IoC (Inversion of Control), DI (Dependency Injection).
- **Spring Boot**: автоконфигурация, `@SpringBootApplication`.
- **Spring MVC**: `@Controller`, `@RestController`, `@RequestMapping`.
- **Spring Data JPA**: `@Repository`, `JpaRepository`.
- **Spring Security**: аутентификация, авторизация, JWT.
- **Spring Cloud**: микросервисы, `Eureka`, `Zuul`, `Feign`.

---

## [**6. Hibernate (ORM)**](/docs/6_Hibernate.md)
- **Сущности**: `@Entity`, `@Table`, `@Id`.
- **Связи**: `@OneToMany`, `@ManyToOne`, `@ManyToMany`.
- **Запросы**:
    - HQL (Hibernate Query Language).
    - Criteria API.
    - `@NamedQuery`.
- **Кэширование**: 1st Level (сессия), 2nd Level (`Ehcache`).

---

## [**7. Популярные библиотеки**](/docs/7_ПопулярныеБиблиотеки.md)
- **Логирование**: `Log4j2`, `SLF4J`.
- **JSON**: `Jackson`, `Gson`.
- **Тестирование**: `JUnit 5`, `Mockito`, `TestContainers`.
- **Утилиты**: `Lombok`, `Guava`, `Apache Commons`.

---

## [**8. Базы данных**](/docs/8_DataBase.md)
- **SQL**: `SELECT`, `JOIN`, `GROUP BY`, индексы, транзакции (ACID).
- **NoSQL**: MongoDB (документы), Redis (ключ-значение).
- **JDBC**: `Connection`, `Statement`, `PreparedStatement`.
- **Миграции**: `Flyway`, `Liquibase`.

---

## [**9. Теория и SQL**](/docs/9_ТеорияБДиSQL.md)
- **Нормальные формы БД** (1NF, 2NF, 3NF).
- **Типы JOIN**: `INNER`, `LEFT`, `RIGHT`, `FULL`.
- **Оптимизация запросов**: индексы, `EXPLAIN`.

---

## [**10. Разработка ПО**](/docs/10_РазработкаПО.md)
- **SOLID**:
    - Single Responsibility
    - Open-Closed
    - Liskov Substitution
    - Interface Segregation
    - Dependency Inversion
- **Паттерны**:
    - **Creational**: Singleton, Factory, Builder.
    - **Structural**: Adapter, Proxy, Decorator.
    - **Behavioral**: Observer, Strategy, Command.
- **Практики**:
    - **DRY** (Don't Repeat Yourself).
    - **KISS** (Keep It Simple, Stupid).
    - **YAGNI** (You Aren't Gonna Need It).

---

## [**11. Микросервисы**](/docs/11_Микросервисы.md)
- **Архитектура**: REST/gRPC, API Gateway, Service Discovery.
- **Spring Cloud**: `Eureka`, `Zuul`, `Feign`, `Hystrix`.
- **Docker + Kubernetes**: контейнеризация, оркестрация.

---

## [**12. Сопровождение и эксплуатация**](/docs/12_Соровождение_и_эксплуатация.md)
- **Логирование**: централизованное (ELK, Grafana Loki).
- **Мониторинг**: Prometheus, Grafana.
- **CI/CD**: Jenkins, GitLab CI, GitHub Actions.
- **DevOps**: Docker, Kubernetes, Terraform.

---