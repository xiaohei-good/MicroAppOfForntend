参考：
https://www.linkedin.com/pulse/single-spa-root-config-microfrontend-using-rany-elhousieny-phd%E1%B4%AC%E1%B4%AE%E1%B4%B0/


在 single-spa 框架中有三种类型的微前端应用：

1.single-spa-application / parcel：微前端架构中的微应用，可以使用 vue、react、angular 等框架。
2.single-spa root config：创建微前端容器应用。
3.utility modules：公共模块应用，非渲染组件，用于跨应用共享 javascript 逻辑的微应用。

使用single-spa创建前两种类型的，并在root容器中访问single-spa-application