# custom_layout_samples
> 云端合流自定义布局示例

使用拍乐云RESTful API请求[云端录制](https://developer.pano.video/restful/recording/)和[CDN推流](https://developer.pano.video/restful/pushcdn/)，用户可以自定义[合流布局](https://developer.pano.video/details/layout/)，灵活地指定用户画面的大小和位置。custom_layout_samples为默认布局提供了自定义布局的实现，用户在定制自己的布局时，可以参考这里的示例。

## 演讲者模式

演讲者模式示例文件命名格式speaker_*width*x*height*_*align*.txt，width和height是视频画布宽高，默认展示的是720p，align是小画面的对齐模式。文件里会列出在此布局下，不同人数对应的自定义布局参数。

