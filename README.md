# MyClashRule
MyClashRule

感谢  
不良林  
https://github.com/chinnsenn/ClashCustomRule  
提供方案  

ACL4SSR在线订阅转换  
https://acl4ssr-sub.github.io/  
orange订阅转换  
https://api.orangeapi.org/  
手搓地址  
https://raw.githubusercontent.com/ron777-777/MyClashRule/main/MyClashRule.ini  
Clash反dns泄露规则  
https://raw.githubusercontent.com/ron777-777/MyClashRule/main/ClashRule.ini  


神秘跳过规则包名:  
```
      //京东类
      com.jingdong.app.mall //京东o
      com.jd.jrapp //京东金融o
      com.jd.jdlite //京喜特价o
      com.jd.jxj //京粉o
      //阿里类
      com.alibaba.android.rimet //钉钉o
      com.taobao.idlefish //闲鱼o
      dkplugin.ppo.kfx //饿了么3o
      com.alimama.moon //淘宝联盟o
      {
        package_name: me.ele //饿了么o
        users:
        [
          0
          999
        ]
      }     
      {
        package_name: com.taobao.taobao //淘宝o
        users:
        [
          0
          999
        ]
      }
      {
        package_name: com.eg.android.AlipayGphone //支付宝o
        users:
        [
          0
          999
        ]
      }
      //银行政府类
      com.ccb.longjiLife //建行生活o
      com.chinamworld.main //中国建设银行o
      com.chinamworld.bocmbci //中国银行o
      com.unionpay //云闪付o
      cn.gov.pbc.dcep //数字人民币o
      com.tmri.app.main //交管12123o
      net.evecom.android.mztapp //闽政通o
      com.digitalchina.mobile.dfhfz1 //e福州o
      com.MobileTicket //铁路12306o
      //游戏类
      com.tencent.tmgp.pubgmhd //和平精英o
      com.ztgame.bob //球球大作战 o
      com.tencent.tmgp.sgame //王者荣耀o
      com.tencent.lolm //英雄联盟手游o
      com.tencent.pocket //腾讯桌球o
      com.netease.party //蛋仔派对o
      //多多类
      com.xunmeng.pinduoduo //拼多多o
      com.xunmeng.ddjinbao //多多进宝o
      //酷安
      com.coolapk.market /酷安o
      //字节跳动
      com.ss.android.ugc.aweme //抖音o     
      
      //测试生效
      {
        package_name: mark.via
        users:
        [
          999
        ]
      }
