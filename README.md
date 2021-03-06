<h1>网易-Mini项目实战：Ego社区</h1>
<h3>项目介绍</h3>
<p>网站类型：二次元社区</p>
<ul>
	<li>项目首页：轮播图展示作品、明日之星关注、用户注册、用户登录</li>
	<li>作品列表页：分页器展示 登录用户个人的作品列表、可坐编辑、删除操作、根据生日计算用户星座并显示。</li>
	<li>作品创建页：设置作品名称、标签、分类、权限、上传作品图片（支持批量上传、拖拽上传，限制单次上传图片的数量和大小）</li>
</ul>
<h3>终端命令</h3>
<ul>
	<li><code>npm install nei -g</code> 若未安装nei脚手架，先全局安装nei</li>
	<li><code>nei server</code> 在项目根目录下，启动 本地项目服务器</li>
</ul>
<h3>WebStorm Run/Debug配置</h3>
<p>如要使用 WebStorm Run/Debug 来运行项目，配置如下：</p>
<ul>
    <li>
        方案1：Add New Configuration > npm > Command 为 test
    </li>
    <li>
        方案2：Add New Configuration > Node.js > JavaScirpt file 为 WebStorm_run_nei.js 
    </li>
</ul>
<h3>页面地址</h3>
<ul>
	<li>项目首页：<a href="http://localhost:8002/index" target="_blank">http://localhost:8002/index</a></li>
	<li>作品列表页：<a href="http://localhost:8002/works" target="_blank">http://localhost:8002/works</a></li>
	<li>作品创建页：<a href="http://localhost:8002/works/create" target="_blank">http://localhost:8002/works/create</a></li>
</ul>
<h3>线上Demo地址</h3>
<p>因为线上Demo 是无后台的mock数据，所以只支持部分项目功能。完整版，还需在本地环境，通过nei服务器体验</p>
<ul>
	<li>项目首页：<a href="https://yibay.github.io/Web-netease-Ego/" target="_blank">https://yibay.github.io/Web-netease-Ego/</a></li>
	<li>作品列表页：<a href="https://yibay.github.io/Web-netease-Ego/html/works/list.html" target="_blank">https://yibay.github.io/Web-netease-Ego/html/works/list.html</a></li>
	<li>作品创建页：<a href="https://yibay.github.io/Web-netease-Ego/html/works/create.html" target="_blank">https://yibay.github.io/Web-netease-Ego/html/works/create.html</a></li>
</ul>
<h3>项目展示</h3>
<table>
	<tr style="text-align:center;">
		<th>首页</th>
		<th>登录框</th>
		<th>注册框</th>
		<th>作品页</th>
		<th>编辑页</th>
	</tr>
	<tr>
		<td><a href="./README_Img/index.jpg" target="_blank"><img src="./README_Img/index_sm.jpg" /></a></td>
		<td><a href="./README_Img/login.png" target="_blank"><img src="./README_Img/login_sm.jpg" /></a></td>
		<td><a href="./README_Img/register.png" target="_blank"><img src="./README_Img/register_sm.jpg" /></a></td>
		<td><a href="./README_Img/list.png" target="_blank"><img src="./README_Img/list_sm.jpg" /></a></td>
		<td><a href="./README_Img/create.png" target="_blank"><img src="./README_Img/create_sm.jpg" /></a></td>
	</tr>
</table>