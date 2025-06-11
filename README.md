# 🌱 Spring Boot Application

## 1. Introduction to Spring Boot Framework

* What is Spring Boot
* What problems it solves
* Features and advantages

---

## 2. How to Create a Spring Boot Project

* **Layered Architecture:**

  ```
  Controller → Service → DAO → Model → Entity
  ```

---

## 3. Understanding Maven Project (`pom.xml`)

* Basics of Maven
* Purpose of `pom.xml`
* Managing dependencies and plugins

---

## 4. Spring Boot Annotations

### Core Annotations

* `@SpringBootApplication`
* `@EnableAutoConfiguration`
* `@ComponentScan`
* `@Configuration`
* `@Value`

### Web Layer

* `@Controller`
* `@RestController`
* `@RequestMapping`
* `@GetMapping`
* `@PostMapping`
* `@PutMapping`
* `@DeleteMapping`

### Component & Service

* `@Component`
* `@Autowired`
* `@Service`
* `@Repository`
* `@Primary`
* `@Qualifier`

### JPA & Database

* `@Entity`
* `@Id`
* `@Column`
* `@Table`
* `@Transactional`

### Scheduling

* `@EnableScheduling`

---

## 5. Dependency Injection

* Understanding how Spring manages dependencies using `@Autowired` and `@Qualifier`

---

## 6. Beans

* Defining and managing Spring Beans
* Bean scopes and lifecycle

---

## 7. Spring Boot Data Access

* Spring JPA
* Spring JDBC
* `JpaRepository`
* Creating REST APIs for data access

---

## 8. Spring Boot Security

* Authentication and Authorization
* Role-based Authorization
