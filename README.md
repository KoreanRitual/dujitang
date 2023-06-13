# 毒鸡汤

二次修改 By KoreanRitual
原项目:
[egotong/nows][nows]
[gogobody/dujitang][nows]

访问地址：<https://gogobody.github.io/dujitang/>

## 语录参考链接

- <https://www.zhihu.com/question/43340253>

## API
js 方式：
```javascript
<script id="djtang" src="https://cdn.jsdelivr.net/gh/gogobody/dujitang/api.min.js" data-tag="span" defer></script>
```

其他：

发起 get 请求：

https://cdn.jsdelivr.net/gh/gogobody/dujitang/data/soul_xx.json

这里 xx 为 0~2019 随机数字，返回值：
```json
{
    file_num: 0,
    data: [
        {
        id: 1,
        content: "我从曾经的一无所有，到现在的身无分文。"
        }
    ]
}
```
