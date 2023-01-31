```
resilience4j.retry:
  instances:
    orderService:
      maxRetryAttempts: 3
      waitDuration: 11000
      
3 times it's going to retry and 11000 is fixed duration within which 3 attempts will be triggered
```

<img width="733" alt="Screenshot 2023-01-19 at 4 03 17 AM" src="https://user-images.githubusercontent.com/43849911/213310138-27c5c442-9d7a-4a75-addd-922a0d792633.png">

<img width="1224" alt="Screenshot 2023-01-19 at 4 02 53 AM" src="https://user-images.githubusercontent.com/43849911/213310115-247c25d8-d0c6-4018-86e8-a733ff440d94.png">
