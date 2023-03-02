## 网易易盾
http://dun.163.com
## 接口说明

- 文件说明

```
.
├── TextCheckAPIDemo.java 文本在线检测接口演示
├── TextBatchCheckAPIDemo.java 文本批量在线检测接口演示
├── TextCallbackAPIDemo.java　文本离线结果获取接口演示
├── TextQueryByTaskIdsDemo.java　文本检测结果查询接口演示
├── TextSubmitAPIDemo.java　文本批量提交接口演示
├── ImageCheckAPIDemo.java　图片在线检测接口演示
├── ImageCallbackDemo.java 图片离线结果获取接口演示
├── ImageCallbackReceiveController.java 图片主动回调数据接收接口演示
├── ImageAsyncCheckAPIDemo.java　图片离线检测接口演示
├── ImageAsyncResultAPIDemo.java　图片离线检测结果获取接口演示
├── ImageFeedBackAPIDemo.java　图片结果反馈接口演示
├── ImageListSubmitAPIDemo.java 图片名单添加接口演示
├── ImageListQueryAPIDemo.java 图片名单查询接口演示
├── ImageListDeleteAPIDemo.java 图片名单删除接口演示
├── ImageListUpdateAPIDemo.java 图片名单更新接口演示
├── AudioActiveCallbackDemo.java 点播语音主动回调数据接受接口演示
├── AudioCallbackAPIDemo.java 点播语音检测结果获取接口演示
├── AudioCheckAPIDemo.java 点播语音在线检测接口演示
├── AudioFeedbackAPIDemo.java 点播语音反馈接口接口演示
├── AudioQuaryByTaskIdsDemo.java 点播语音taskId查询v3接口演示
├── AudioQuaryByTaskIdsV4Demo.java 点播语音taskId查询v4接口演示
├── AudioSubmitAPIDemo.java 点播语音在线检测提交接口演示
├── LiveAudioActiveCallbackDemo.java 直播语音主动回调数据接受接口演示
├── LiveAudioCallbackAPIDemo.java 直播语音检测结果获取接口演示
├── LiveAudioCheckAPIDemo.java 直播语音在线检测提交接口演示
├── LiveAudioFeedbackAPIDemo.java 直播语音信息更新接口演示
├── LiveAudioListCallbackAPIDemo.java 直播语音名单获取接口演示
├── LiveAudioQueryExtraAPIDemo.java 直播语音增值检测结果获取接口演示
├── LiveAudioQueryMonitorAPIDemo.java 直播语音人审操作记录获取接口演示
├── LiveAudioQueryTaskAPIDemo.java 直播语音片段离线结果获取接口演示
├── LiveVideoActiveCallbackDemo.java 直播视频主动回调数据接受接口演示
├── LiveVideoCallbackAPIDemo.java 直播流检测结果获取接口演示
├── LiveVideoFeedbackAPIDemo.java 直播视频信息更新接口演示
├── LiveVideoImageQueryDemo.java 直播视频截图查询接口演示
├── LiveVideoQueryByTaskIdsDemo.java 直播视频结果查询接口演示
├── LiveVideoSubmitAPIDemo.java　直播流信息提交接口演示
├── VideoActiveCallbackDemo.java 点播视频主动回调数据接受接口演示
├── VideoCallbackAPIDemo.java 视频点播检测结果获取接口演示
├── VideoImageQueryDemo.java 视频点播截图查询接口演示
├── VideoQueryByTaskIdsDemo.java 视频点播结果查询接口演示
├── VideoQueryByTaskIdsV4Demo.java 视频点播结果查询v4接口演示
├── VideoSubmitAPIDemo.java　视频点播信息提交接口演示
├── MediaSolutionSubmitV2APIDemo.java 融媒体解决方案检测提交接口演示
├── MediaSolutionCallbackV2APIDemo.java 融媒体解决方案获取结果-轮询模式接口演示
├── MediaSolutionQueryV2APIDemo.java 融媒体解决方案回调查询接口演示
├── DigitalBookSubmitV2APIDemo.java 数字阅读解决方案检测提交接口演示
├── DigitalBookCallbackV2APIDemo.java 数字阅读解决方案获取结果-轮询模式接口演示
├── DigitalBookQueryV2APIDemo.java 数字阅读解决方案回调查询接口演示
├── ReportSolutionSubmitAPIDemo.java 举报解决方案检测提交接口演示
├── ReportSolutionCallbackAPIDemo.java 举报方案获取结果-轮询模式接口演示
├── ReportSolutionQueryAPIDemo.java 举报解决方案回调查询接口演示
├── FileSubmitApiDemo.java 文档解决方案在线检测提交接口演示
├── FileCallbackApiDemo.java 文档解决方案检测结果获取接口演示
├── CrawlerSubmitAPIDemo.java 网站检测解决方案在线检测提交接口演示
├── CrawlerCallbackAPIDemo.java 网站检测解决方案检测结果获取接口演示
├── VideoSolutionActiveCallbackDemo.java 点播音视频解决方案结果获取接受接口演示
├── VideoSolutionCallbackAPIDemo.java 点播音视频解决方案检测结果获取接口演示
├── VideoSolutionFeedbackAPIDemo.java 点播音视频解决方案反馈接口演示
├── VideoSolutionQueryAPIDemo.java 点播音视频解决方案检测离线结果查询接口演示
├── VideoSolutionQueryV2APIDemo.java 点播音视频解决方案检测离线结果查询V2接口演示
├── VideoSolutionSubmitApiDemo.java 点播音视频解决方案在线检测提交接口演示
├── LiveVideoSolutionActiveCallbackDemo.java 直播音视频解决方案推送数据接口演示
├── LiveVideoSolutionCallbackAPIDemo.java 直播音视频解决方案检测结果获取接口演示
├── LiveVideoSolutionListCallbackAPIDemo.java 直播音视频解决方案名单获取接口演示
├── LiveVideoSolutionSubmitAPIDemo.java 直播音视频解决方案检测提交接口演示
├── LiveVideoSolutionQueryByTaskIdsDemo.java 直播音视频解决方案TaskId查询结果获取接口演示
├── LiveVideoSolutionQueryMonitorAPIDemo.java 直播音视频解决方案人审操作记录结果获取接口演示
├── LiveVideoSolutionQueryAudioAPIDemo.java 直播音视频解决方案音频片段结果获取接口演示
├── LiveVideoSolutionQueryImageAPIDemo.java 直播音视频解决方案视频截图结果获取接口演示
├── LiveVideoSolutionFeedbackAPIDemo.java 直播音视频解决方案信息更新接口演示
├── KeywordSubmitAPIDemo.java 敏感词提交接口演示
├── KeywordDeleteAPIDemo.java 敏感词删除接口演示
├── KeywordQueryAPIDemo.java 敏感词查询接口演示
├── ListSubmitAPIDemo.java 名单提交接口演示
├── ListUpdateAPIDemo.java 名单更新接口演示
├── ListDeleteAPIDemo.java 名单删除接口演示
├── ListQueryAPIDemo.java 名单查询接口演示
├── KeywordSubmitAPIDemo.java 敏感词提交接口演示
├── KeywordUpdateAPIDemo.java 敏感词更新接口演示
├── KeywordDeleteAPIDemo.java 敏感词删除接口演示
├── KeywordQueryAPIDemo.java 敏感词查询接口演示
├── PretreatmentAddAPIDemo.java 忽略词添加接口演示
├── PretreatmentUpdateAPIDemo.java 忽略词更新接口演示
├── PretreatmentDeleteAPIDemo.java 忽略词删除接口演示
├── PretreatmentQueryAPIDemo.java 忽略词查询接口演示
├── CallbackReceiveController.java 主动回调数据接收接口演示
├── HttpClient4Utils.java httpclient封装类
├── DemoConstants.java 公共常量
└── SignatureUtils.java 签名方法封装类
```
