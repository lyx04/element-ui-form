# element-ui-form
element-ui form中如何写绑定动态的prop

其实在官网上文档写的非常清楚"传入 Form 组件的 model 中的字段",在el-form中:model="此处是变量形式的表单项"在el-form中添加完rules的验证规则后，最重要的就是在每一个el-form-item中绑定prop，最简单的说法就是，model.prop = 接下来输入框中的v-model,只要两者取值都是同样一个，就可以完成验证
