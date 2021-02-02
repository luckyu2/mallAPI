# supermall接口
- 商城项目地址：[SuperMall](https://github.com/luckyu2/supermall)
- 个人博客：[余的blog](https://luckyu.xyz/)

 ### 使用步骤

   - 安装依赖环境，默认命令 npm start

   - 后台默认端口是 localhost:3000

   - 修改src/network/request.js 文件中的数据接口baseURL

   - baseURL为http://localhost:3000

     ```
     const instance = axios.create({
         baseURL: "修改为你的数据接口",
         timeout: 5000
       })
     ```

  ### 数据库

    数据库已经导出，放在了spider文件夹下。   

 - app.js里面的路由配置，基本上和coderwhy老师提供的api接口路径是一致的，
   有兴趣可以在其基础上添加更多的东西，如果觉得麻烦，可以加coderwhy老师wx获取

