# JS_EVENTLOOP_TEST


JavaScript 비동기 처리 방법에 대한 실습 입니다.

## 🔗Result
"Start"와 "End"는 동기 코드로 실행되고, "Promise"와 "setTimeout"은 비동기적으로 실행되며, "Promise"는 "Microtask queue"에서 실행되고 "setTimeout"은 "Task queue"에서 실행됩니다. 따라서 우선순위 처리로 인해 이제 Promise Callback이 콘솔로 먼저 전송됩니다.

![image](https://github.com/YOON-CC/JS_EVENTLOOP_TEST/assets/87313979/70e5e06c-eb44-4926-b789-b828dd00e37e)


[블로그 바로가기](https://velog.io/@happycyc/JS%EB%8A%94-%EC%8B%B1%EA%B8%80%EC%8A%A4%EB%A0%88%EB%93%9C-%EC%96%B8%EC%96%B4%EC%9D%B8%EB%8D%B0-%EB%B9%84%EB%8F%99%EA%B8%B0%EB%A5%BC-%EC%B2%98%EB%A6%AC%EB%A5%BC-%EC%96%B4%EB%96%BB%EA%B2%8C-%ED%95%A0%EA%B9%8C)
