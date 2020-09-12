# postcss命令行使用方式
  1.安装postcss-cli 
  2.安装插件 autoprefixer ...
  3.执行命令 npx postcss src/*.css(被编译文件) --use autoprefixer(使用插件) -d build/(输出文件夹)

# 配置autoprefixer
  1.package.json配置  添加browserslist字段  "browserslist": ["chrome>8","ios>9","Android>6"]
  2.配置.browserslistrc文件 (在不同的前端工具之间共用目标浏览器/node版本的配置工具) npx browserslist 查看筛选出的浏览器版本