### Django MLogger

基于Django的日志管理系统，通过配置Settings使用。

#### 快速开始
```python
from django_mlogger.mloggger import MLogger

m_logger = MLogger(__name__, "test")


@m_logger.guard()
def test():
    pass

```

