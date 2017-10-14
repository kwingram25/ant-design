---
order: 0
title:
  zh-CN: 基本
  en-US: Minimum Width
---

## zh-CN

最简单的用法。

## en-US

Apply only with a minimum target width.

````jsx
import { Affix, Button } from 'antd';

ReactDOM.render(
  <div>
    <Affix minWidth={1000}>
      <Button type="primary">Affix if window > 1000px</Button>
    </Affix>
  </div>,
  mountNode
);
````
