# ClashRlue_Backup
Clash 自用规则备份

**以下教程来自于@cutethotw （抱歉实在不会引用）**
原作者项目仓库：https://github.com/cutethotw/ClashRule

**1.选择订阅转换**

  服务器用别人搭建好的（因为前端一般不支持自定义后端故以下仅作前端推荐）
  
  - 肥羊： https://sub.v1.mk/
  
  - acl4ssr https://acl4ssr-sub.github.io/
  
**2.远程配置**

分流配置，可以选择给定的也可以输入URL自定义分流规则（注意必须是直链才行），自用clash分流规则直链地址:https://raw.githubusercontent.com/PANGPANGDigital/ClashRlue_Backup/main/PANGPANGDigital.ini
  
  PS.此配置国家节点 检测策略均使用 **fallback模式**
  
 **分流规则常用引用仓库**
 
- ACL4SSR https://github.com/ACL4SSR/ACL4SSR/tree/master/Clash
    
- blackmatrix7 https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash
    
- **排序**
  - 分流规则的匹配是按照至上而下收录，匹配到了就停止不再往下，比如YouTube规则要放在国外媒体前面，而完整的国外媒体规则包含了YouTube, Netflix, Pornhub等等，所以分流规则较大要放在YouTube小分流规则后面

 - **排序原则**
  
   - 重要直连分流规则 > 去广告规则 > 小分流 > 国内外大分流 > 补充规则
  
- 更多选项（右下角）
       
  - Emoji 默认开启
       
  - 启动UDP 推荐开启
      
  - 启动TFO 推荐开启

**3.参考示例**

![Image text](https://github.com/PANGPANGDigital/ClashRlue_Backup/blob/main/images/%E8%82%A5%E7%BE%8A%E8%AE%A2%E9%98%85%E8%BD%AC%E6%8D%A2.png)

![Image text](https://github.com/PANGPANGDigital/ClashRlue_Backup/blob/main/images/%E5%88%86%E6%B5%81%E5%9B%BE.png)
