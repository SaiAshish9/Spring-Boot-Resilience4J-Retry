```
resilience4j.retry:
  instances:
    orderService:
      maxRetryAttempts: 3
      waitDuration: 11000
      
3 times it's going to retry and 11000 is fixed duration between 2 consecutive attempts

```
