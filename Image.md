##### 现在的APP中，如果说什么事用到的最多的，毫无疑问，那只有图片了。
##### 所以，对图片的操作也是我们使用最频繁的，Github几乎都能够找到满足我们需求的图片处理的开源库。
##### 为了避免花费时间去Github一个一个去找，这里罗列一下

### 图片加载
#### 1、Android-Universal-Image-Loader
> Universal ImageLoader 是很早开源的图片缓存，在早期被很多应用使用。
> [项目地址：https://github.com/nostra13/Android-Universal-Image-Loader][1]

#### 2、Picasso
> Picasso 是 Square 开源的项目（Square出品，必属精品），而且他的主导者也是我们熟悉的Android大神JakeWharton，而且结合Square出品的其他框架，能够发挥最大的作用
> [项目地址：https://github.com/square/picasso][2]

#### 3、Glide
> Glide 是 Google 员工的开源项目， 是Picasso的克隆版本，在Picasso的基础上加了很多的扩展（比如gif等支持），Glide默认的Bitmap格式RGB_565，比   Picasso默认的ARGB_8888格式的内存开销要小一半；Picasso缓存的是全尺寸的(只缓存一种)，而Glide缓存的是跟ImageView尺寸相同的(即56*56和128*128是两个缓存) 
> [项目地址：https://github.com/bumptech/glide][3]

#### 4、Fresco
> Fresco 是 Facebook 推出的一款强大的android图片处理库,它能够从网络、本地存储和本地资源中加载图片。而且，为了节省数据和CPU，它拥有三级缓存。此外，Fresco在显示方面是用了Drawees，可以显示占位符，直到图片加载完成。而当图片从屏幕上消失时，会自动释放图片所占的内存
> [项目地址：https://github.com/facebook/fresco][4]

#### 5、Volley
> Volley是Google 2013 I/O 发布的一个开源库,它提供了一个新的控件NetworkImageView来代替传统的ImageView，可惜不能加载本地图片~
> [项目地址：https://github.com/mcxiaoke/android-volley][5]




  [1]: https://github.com/nostra13/Android-Universal-Image-Loader
  [2]: https://github.com/square/picasso
  [3]: https://github.com/bumptech/glide
  [4]: https://github.com/facebook/fresco
  [5]: https://github.com/mcxiaoke/android-volley