# kmhm
昆明华美美莱mip改造


查询站内文章图片
SELECT dede_archives.title ,dede_archives.id,dede_addonarticle.body FROM dede_archives ,dede_addonarticle WHERE dede_archives.id= dede_addonarticle.aid AND  dede_archives.litpic!='' ORDER BY id desc;
