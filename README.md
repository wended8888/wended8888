
wended8888/wended8888 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
/*******************************

*******************************/
var body=$response.body;
body = body.replace(/name\":"心向远方"/g,'name":"至简"');
body = body.replace(/asAuthorName\":"心向远方"/g,'asAuthorName":"至简"');
body = body.replace(/desc\":"首月特惠 · 成为会员无限畅听"/g,'desc":"至简主义"');
body = body.replace(/label\":"每天可获得 90 分钟免费时长"/g,'label":"尊贵Vip",');
body = body.replace(/remainSeconds\":\d+/g,'remainSeconds":0');
body = body.replace(/totalListenAlbumCount\":\d/g,'totalListenAlbumCount":1');
body = body.replace(/name\":"收听兑时长"/g,'name":"至简"');
body = body.replace(/desc\":"收听 60 分钟可获得免费时长"/g,'desc":"至简主义"');
body = body.replace(/isMember\":\d/g,'isMember":1');
body = body.replace(/startTime\":\d+/g,'startTime":52708342659');
body = body.replace(/endTime\":\d+/g,'endTime":52708342659');
body = body.replace(/expiresIn\":\d+/g,'expiresIn":52708342659');
body = body.replace(/subscriptionDesc\":"首月特惠 · 成为会员无限畅听"/g,'subscriptionDesc":"您已是会员"');
$done(body);
