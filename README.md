# Basic-Spring-MVC
<img src="https://github.com/Eaaon/Basic-Spring-MVC/blob/master/Spring%20MVC.JPG">
<p>1、用户端的请求通过HTTP协议到达前端控制器，前端控制器了解这个请求应当被谁来处理，所以请求代理给了具体的控制器。</p>
<p>2、控制器了解业务逻辑的细节，因此调用业务逻辑，生成了业务数据，并将这个业务数据返回给了前端控制器。</p>
<p>3、此时，前端控制器再将业务数据分发给你业务视图，由业务视图来呈现追踪到用户页面，再将呈现好的用户页面返还给前端控制器并追踪，将这个页面返还给浏览器端。</p>

## MVC(Model-View-Controller)

* View（视图层，为用户提供UI，重点关注数据的呈现）
     
* Model（模型层，业务数据的信息表示，关注支撑业务的信息构成，通常是多个业务实体的组成）
    
* Controller（控制层，调用业务逻辑产生合适的数据（Mode）传递数据给视图层用于呈现）        

### [Spring MVC起步视频](http://www.imooc.com/learn/47)
