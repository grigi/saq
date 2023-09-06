---
sd_hide_title: true
---
# Overview

```{toctree}
:hidden:

getting_started
usage
comparison
changelog
contribute
```

## SAQ (Simple Async Queue) documentation

SAQ (Simple Async Queue) is a simple and performant job queueing framework built on top of asyncio and redis. It can be used for processing background jobs with workers. For example, you could use SAQ to schedule emails, execute long queries, or do expensive data analysis.

It uses [redis-py](https://github.com/redis/redis-py) >= 4.2.

It is similar to [RQ](https://github.com/rq/rq) and heavily inspired by [ARQ](https://github.com/samuelcolvin/arq). Unlike RQ, it is async and thus [significantly faster](#comparison) if your jobs are async. Even if they are not, SAQ is still considerably faster due to lower overhead.


::::{grid} 2
:gutter: 3
:margin: 1

:::{grid-item-card}
:link: getting_started
:link-type: doc
:text-align: center
:class-header: secondary
**Getting Started**
^^^
Getting started with SAQ?
:::

:::{grid-item-card}
:link: usage
:link-type: doc
:text-align: center
**Usage**
^^^
Guides on how to use SAQ
:::

:::{grid-item-card}
:link: monitoring
:link-type: doc
:text-align: center
**Monitoring**
^^^
SAQ provides a simple UI for monitor workers and jobs.
:::

:::{grid-item-card}
:link: testing
:link-type: doc
:text-align: center
**Testing**
^^^
SAQ provides a basic test double that can make writing your tests a bit more convenient.
:::

:::{grid-item-card}
:link: autoapi/index
:link-type: doc
:text-align: center
**API Reference**
^^^
The API Reference for advanced users.
:::

:::{grid-item-card}
:link: changelog
:link-type: doc
:text-align: center
**Changelog**
^^^
See the recent changes, and upgrade instuctions if needed.
:::
::::


## Indices and tables

* <project:#genindex>
* <project:#modindex>
