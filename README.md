<h1>AusFun.py</h1>
<p>给自己写的一个包</p>


<h2>功能</h2> 
<ul>
    <li>动态爬虫的基本函数: <br>默认状态下所有的请求header都是手机端</li>
</ul>

<table>
    <tr style="text-align: center;font-weight: bold;">
        <td>功能</td>
        <td>方法</td>
        <td>参数</td>
        <td>返回值</td>
    </tr>
    <tr>
        <td colspan="4" style="text-align: center;">V 0.0.0</td>
    </tr>
    <tr>
        <td>获取json数据</td>
        <td>getJson()</td>
        <td>url, cookies = {}</td>
        <td>dict/list</td>
    </tr>
    <tr>
        <td>获取json数据</td>
        <td>postJson()</td>
        <td>url, data, cookies = {}</td>
        <td>dict/list</td>
    </tr>
    <tr>
        <td>存储json数据</td>
        <td>saveJson()</td>
        <td>data, filePath</td>
        <td>file</td>
    </tr>
    <tr>
        <td>读取json数据</td>
        <td>readJson()</td>
        <td>filePath</td>
        <td>dict/list</td>
    </tr>
    <tr>
        <td>读取cookies文件</td>
        <td>getCookies()</td>
        <td>filePath</td>
        <td>cookies</td>
    </tr>
</table>
<br>
<small>Last Modified: 2017/07/16</small>



