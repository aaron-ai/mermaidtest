## Test
```mermaid
graph TD
    A[Christmas] -->|Get money| B(Go shopping)
    B --> C{Let me think}
    C -->|One| D[Laptop]
    C -->|Two| E[iPhone]
    C -->|Three| F[fa:fa-car Car]
  
```

```mermaid
gantt
	dateFormat YYYY-MM-DD
	title RocketMQ Java SDK 规划
	
	section	开发
		Producer : done, name1, 2022-04-15, 2022-04-28
		PushConsumer : done, name2, 2022-03-15, 2022-06-01
		SimpleConsumer : active, name3, after name2, 14d
        异常管理 : active, name4, 2022-03-05, 2022-03-07
        日志梳理 : active, name5, 2022-03-05, 2022-03-07
	section 联调
		联系导师 : crit, name11, 2022-04-15, 2022-05-20
		申请院校 : active, name22, after name11, 30d
		清华大学 : active, name33, after name3, 1d
		南开大学 : done, name44, 2022-07-01, 2022-07-10
		中科院 : active, name55, 2022-07-20, 5d
		
	section 测试
    	修改简历 : crit, name111, 2022-04-05, 10d
    	简历投递 : done, name222, after name111, 20d
    	电话面试 : crit, name333, 2022-05-26, 30d
    	未来任务 : active, after name333, 10d
```