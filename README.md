# news-project

将资讯页面改成了自定义组件的形式，使用时需要注册一下资讯详情的路由（一共七个，路径位于component下的news文件夹里的news-detail里）。

例如：

```
pages: [
    'pages/index/index',
    'components/news/news-detail/news-detail1', 
    'components/news/news-detail/news-detail2',
    'components/news/news-detail/news-detail3',
    'components/news/news-detail/news-detail4',
    'components/news/news-detail/news-detail5',
    'components/news/news-detail/news-detail6',
    'components/news/news-detail/news-detail7'
  ]
```



使用的例子：

```vue
<template>
	<news> </news>
</template>

<script>
import news from '../../components/news/news.vue' 
export default{
  components: { news },
  methods:{}
} 
</script> 
```

