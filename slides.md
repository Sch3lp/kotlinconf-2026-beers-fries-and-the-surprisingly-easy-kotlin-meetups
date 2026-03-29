---
highlighter: shiki
theme: kotlin
transition: view-transition
---

# Kotlin Conf 2026

## Beers, Fries and the surprisingly easy Kotlin Meetups

`github.com/sch3lp/kotlinconf-2026-beers-fries-and-the-surprisingly-easy-kotlin-meetups`

<br>

- Simon Vergauwen
- Tim Schraepen

---
kodee:
  variant: greeting
  size: large
  position: featured
---


# Welcome

Thanks for coming to our session!

---
kodee:
variant: greeting
size: small
position: corner
---


# Simon

<img src="/simon.png" class="absolute bottom-4 right-4 w-1/2" />

---
kodee:
variant: greeting
size: small
position: corner
---


# Tim

<img src="/tim.png" class="absolute bottom-4 right-4 w-1/2" />

---
kodee:
variant: greeting
size: small
position: corner
---


# Context Parameters

````md magic-move
```kotlin
context(builder: PromptBuilder)
operator fun Content.unaryPlus(): Unit = TODO()
```

```kotlin
context(builder: PromptBuilder)
operator fun Content.unaryPlus(): Unit = TODO()

val builder = PromptBuilderImpl()

context(builder) { // context(PromptBuilder) () -> A
    +Content(...)
}
```

```kotlin
context(builder: PromptBuilder)
operator fun Content.unaryPlus(): Unit = TODO()

prompt { // context(PromptBuilder) () -> A
    Content(...).unaryPlus()
    +Content(...)
}
```
````

<div v-click="3">
<ul>
<li><code lang="kotlin">prompt { }</code> enforces scope. I.e. calculate final result, react on exception, etc.</li>
</ul>
</div>

---
kodee:
  variant: greeting
  size: small
  position: corner
---


---

# Thank you!

- Questions?
