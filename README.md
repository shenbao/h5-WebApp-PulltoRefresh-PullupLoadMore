
# h5-WebApp-pulltoRefresh-PullupLoadMore

DOME列表


<br />
[PullupLoadMore v1 iscroll 5.x](https://github.com/shenbao/h5-WebApp-pulltoRefresh-PullupLoadMore/tree/master/PullupLoadMore%20v1%20iscroll%205.x)
<br />
[iscroll_demo](https://github.com/shenbao/h5-WebApp-pulltoRefresh-PullupLoadMore/tree/master/iscroll_demo)
<br />
[pulltoRefresh-PullupLoadMore v1 iscroll 4.x](https://github.com/shenbao/h5-WebApp-pulltoRefresh-PullupLoadMore/tree/master/pullupRefresh-PullupLoadMore%20v1%20iscroll%204.x)
<br />
[pulltoRefresh-PullupLoadMore v2 iscroll 5.x](https://github.com/shenbao/h5-WebApp-pulltoRefresh-PullupLoadMore/tree/master/pullupRefresh-PullupLoadMore%20v2%20iscroll%205.x)
<br />
[pulltoRefresh-PullupLoadMore v3 iscroll 5.x](https://github.com/shenbao/h5-WebApp-pulltoRefresh-PullupLoadMore/tree/master/pullupRefresh-PullupLoadMore%20v3%20iscroll%205.x)
<br />
[pulltoRefresh-PullupLoadMore v4 iscroll 5.x](https://github.com/shenbao/h5-WebApp-pulltoRefresh-PullupLoadMore/tree/master/pullupRefresh-PullupLoadMore%20v4%20iscroll%205.x)
<br />
[pulltoRefresh-downpullRefresh iscroll 4.x](https://github.com/shenbao/h5-WebApp-pulltoRefresh-PullupLoadMore/tree/master/pullupRefresh-downpullRefresh%20%20iscroll%204.x)
<br />


一款基于iscroll5的下拉刷新，上拉加载的的插件。

## 使用 （PS:各个dome用法略有不同，详细看dome示例用法）
```html
  <script src="../iscroll-probe.js"></script>
  <script src="../jquery.js"</script>
  <script scr="../pulltofresh.js"></script>
  <script>
    $("#wrapper").pulltofresh();
  </script>
```


## 参数

```js
  delector: { //选择器
      container: '#wrapper', //iscroller的盒子
      headBox: '.head',   //头部更新盒子
      footBox: '.foot' //上拉刷新盒子
  },
  scrollSettings: { //给scroll传入的参数
      probeType: 3,
      mouseWheel: true
  },
  loadUrl: 'img/ajax-loader.gif', //加载图片的url
  arrowUrl: 'img/arrow.png',  //下拉刷新图片的url
  initScroll: -100,   //初始滚动大小
  pulltoload: null, // 上拉加载的ajax函数
  refresh: null //下拉刷新的ajax函数
};
```


