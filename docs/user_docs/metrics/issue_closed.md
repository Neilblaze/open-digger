# 已关闭的问题

![From](https://img.shields.io/badge/来自-CHAOSS-blue) ![For](https://img.shields.io/badge/用于-仓库-blue)

## 定义

已关闭的问题（Issues Closed）是由 [CHAOSS 社区](https://chaoss.community) 定义的一个指标。有关此指标的详细定义，请参考 [CHAOSS 指标 - 已关闭的问题](https://chaoss.community/zh-CN/kb/metric-issues-closed)。

此指标跟踪在某个时期内关闭的问题数量。关闭的问题是那些在某个时期内状态变为“关闭”的问题。在某些情况或某些项目中，有其他状态或标签可以被视为“关闭”。例如，在某些项目中，他们使用状态或标签“已修复”来表示问题已关闭，即使它需要一些正式的关闭操作。

> 已关闭的问题指标提供了项目中处理问题的数量的洞察。关闭的问题是项目活动的一种形式，通过计算与代码相关的关闭问题数量，可以了解项目中完成问题工作的总体活动情况。当然，这个指标不是唯一用于跟踪编码活动量的指标。

## 数据

**链接：** `https://oss.x-lab.info/open_digger/{platform}/{owner}/{repo}/issues_closed.json`

要获取某个仓库的数据，请将 `{platform}`、`{owner}` 和 `{repo}` 替换为实际名称。更多信息请参考此 [示例](https://oss.x-lab.info/open_digger/github/X-lab2017/open-digger/issues_closed.json)。

## 代码

这是 [**实现代码**](https://github.com/X-lab2017/open-digger/blob/master/src/metrics/chaoss.ts#L193)。

## CodePen 演示

<iframe height="600" scrolling="no" title="OpenDigger - [CHAOSS] Issues Status" src="https://codepen.io/frank-zsy/embed/mdjaZMw?default-tab=js%2Cresult&editable=true" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/frank-zsy/pen/mdjaZMw">
  OpenDigger - [CHAOSS] Issues Status</a> by Frank Zhao (<a href="https://codepen.io/frank-zsy">@frank-zsy</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>