# Xiaohongshu MCP 本地跑通记录
#具体见master分支

## 1. 运行环境
- macOS (Apple Silicon)
- Node: v18+
- MCP Inspector
- xiaohongshu-mcp (binary)

## 2. 启动步骤
1. 启动 MCP Server
2. 使用 npx @modelcontextprotocol/inspector 连接
3. 执行 tools：
   - favorite_feed
   - publish_note
   - get_feed_detail

## 3. 测试结果
- 所有工具返回 200
- 图片使用 Unsplash download URL
- 发布成功 / 模拟成功

## 4. 关键日志
见 logs/mcp.log
