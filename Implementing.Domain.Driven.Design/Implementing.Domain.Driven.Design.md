
Implementing Domain-Driven Design
======


關鍵字
 * tactical
 * Strategic
 * Ubiquitous Language


---
## Summary of Chapters ###############

### Chapter 1: Getting Started with DDD
### Chapter 2: Domains, Subdomains, and Bounded Contexts
### Chapter 3: Context Maps
### Chapter 4: Architecture
### Chapter 5: Entities
### Chapter 6: Value Objects
### Chapter 7: Services
### Chapter 8: Domain Events
### Chapter 9: Modules
### Chapter 10: Aggregates
### Chapter 11: Factories
### Chapter 12: Repositories
### Chapter 13: Integrating Bounded Contexts
### Chapter 14: Application
### Appendix A: Aggregates and Event Sourcing: A+ES




---
如果你真的對ddd很陌生，  
下面這一節會幫助你這些pattern是怎麼一起作業的，同時也告訴你怎麼利用本書來盡快的上手。那麼，繼續吧。

* Big-Picture View of DDD
* Strategic Modeling
* Architecture
* Tactical Modeling


---
# Chapter 1: Getting Started with DDD

## How DDD Helps  
(824 of Kindle)

DDD有三個主要的方向：
1. DDD結合領域專家與軟體開發者，使雙方共同生產出核心的業務模型。
2. 業務的策略抉擇能利用DDD矛定。
3. DDD 結合了真實的軟體的技術條件，藉由戰術設計模型工具，來分析並開發可運作的交付軟件。

## Grappling with the Complexity of Your Domain

要切割出
* Core Domain
* Supporting Subdomains

```
Use DDD to Simplify, Not to Complicate
Use DDD to model a complex domain in the simplest possible way. Never use DDD to make your ssolution more complex.
```

每個業務個案面對的複雜度都不一樣，是沒有一致的評估方式的，所以與其關心複雜度，倒不如測定哪些是不尋常的東西。那麼你的團隊/管理者就能決定哪些事物是值得投入DDD開發了。

## DDD Scorecard ##########
 這裡有個7*4 的table (Table 1.1)，用來計分並評估 Project是否值得使用DDD。

---
#往下探討了 貧血模型 ###############


## Determine Your Domain Model Health History ###########
這裡的Table 1.2 評估自己的 Domain Model 是否是 Anomic Domain Model 貧血模型。 有兩個檢定用的問題。

```
Should I Be Concerned about Using Object-Relational Mappers with DDD?
The preceding critique of Hibernate is from a historical perspective. For quite a while now Hibername has supported the use of hidden getters and setters, and even direct field access. I demonstrate in later chapters how to avoid amenia in your models when using Hibername and other persistence mechanisms. So, don't sweat it.
```
---
從一個能除存任何狀況的 saveCustomer() 挖掘出了三個大問題。  

1. 這個方法只展現了一點意圖。
2. 這個實做隱藏了複雜度。
3. Customer 領域物件，並不完整。他只是個資料持有者。

這樣的現象，我們稱呼他為
```anemia-induced memory loss```


```
Hold On a Minute!


```

---

# How to Do DDD

這時DDD最有力量的特性要亮相了。
 * Ubiquitous Language.
 * Bounded Context.
 * 
 * 