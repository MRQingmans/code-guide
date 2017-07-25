# 票务系统前端代码指南

------------

### HTML
- id和class命名方式: 小写英文单词,多个单词用-间隔,例如:cinema-list
- class命名方式遵循[BEM](http://getbem.com/ "BEM")规范
- html代码编推荐使用[emmet](https://docs.emmet.io/ "emmet")
- emmet和BEM可以配合[使用](http://www.w3cplus.com/preprocessor/pushing-bem-to-the-next-level-with-sass-3-4.html "使用")

### JS
- 变量命名方式: 小写英文单词,多个单词用_间隔,例如:get_user_data
- boolean属性的变量命名请用is或者has打头,例如is_open,has_name
- 开关类方法请用toggle打头,例如toggle_display_info
- ajax获取数据类方法请用get打头,例如get_user_list
- 修改类方法请用update打头,例如update_user
- 删除类方法请用delete打头,例如delete_user
- 添加类方法请用add打头,例如add_user
- 代码格式请参照vscode设置

### CSS
- 推荐使用SASS编写CSS
- 减少使用important
- 去掉小数点前面的0,例如 0.5 => .5
- 属性值'0'后面不要加单位, 例如 0px => 0

### VUE
- 组件文件命名方式:首字母大写英文单词,多个单词不需要间隔,例如:Page.vue,UserList.vue
- 组件标签命名方式:小写英文单词,多个单词用-间隔,例如:cinema-list
- Vuex操作数组和对象时,不要改变原数据
- ajax获取数据方法放在beforeMount周期

### 技术栈
- [ES6](http://es6.ruanyifeng.com/ "ES6")
- [SASS](http://sass-lang.com/ "SASS")
- [VUE](https://cn.vuejs.org/v2/guide/ "VUE")
- [vue-router](https://router.vuejs.org/zh-cn/ "vue-router")
- [Vuex](https://vuex.vuejs.org/zh-cn/ "Vuex")
- [Webpack](https://doc.webpack-china.org/ "Webpack")
- [Lodash](http://lodashjs.com/docs/ "Lodash")
- [axios](https://github.com/mzabriskie/axios "axios")