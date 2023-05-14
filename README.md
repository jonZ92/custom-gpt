

#### 使用rust开发chat-gpt接口
##### 第一阶段开发 Chat (including SSE streaming)功能
```
聊天
  curl \
	-u 'test:password01!' \
	-X POST '206.119.168.188:19002/chat' \
	-H 'Content-Type: application/json ' \
	-d '{ "msg":"你好" }'
```

```
  curl \
	-u 'test:password01!' \
	-X POST '206.119.168.188:19002/completion' \
	-H 'Content-Type: application/json ' \
	-d '{ "msg":"就算全世界离开你" }'

```

##### 后续准备开发🔂 Images、Completions (including SSE streaming)、Audio



