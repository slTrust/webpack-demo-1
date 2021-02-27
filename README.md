# 安装依赖

```
yarn install
```

## 运行代码

```
# 普通运行
node -r ts-node/register xxx.ts

# 浏览器调试,打开浏览器控制台出现 node.js图标
node -r ts-node/register --inspect-brk xxx.ts
```