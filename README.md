# 员工信息管理系统

----
## 技术：
   前端：vue,axios,Elementui
   后端：node.js(express,url,express-static,mysql)
   
## 测试地址：

#### 公网：[http://39.96.172.52:8080/vuetian.html](http://39.96.172.52:8080/vuetian.html)

## 员工信息数据接口

### 获取数据接口：
<hr>
#### 公网：http://39.96.172.52:8080/cx

#### 返回数据：json

#### 请求方式：get,http

#### 请求实例：http://39.96.172.52:8080/cx

#### 请求参数说明：无

#### 返回参数说明：
<table>
    <thead>
        <tr>
            <td>名称</td>
            <td>类型</td>
            <td>说明</td>
        </tr>
    </thead>
    <tbody>
         <tr>
            <td>ID</td>
            <td>int(5)</td>
            <td>员工编号</td>
        </tr>
        <tr>
            <td>name</td>
            <td>varchar</td>
            <td>员工姓名</td>
        </tr>
        <tr>
            <td>sex</td>
            <td>int(1)</td>
            <td>员工性别</td>
        </tr>
         <tr>
            <td>birthday</td>
            <td>date</td>
            <td>出生日期</td>
        </tr>
         <tr>
            <td>department</td>
            <td>varchar(255)</td>
            <td>部门</td>
        </tr>
         <tr>
            <td>status</td>
            <td>int(1)</td>
            <td>在职状态</td>
        </tr>
         <tr>
            <td>joinDate</td>
            <td>date</td>
            <td>离职日期</td>
        </tr>
         <tr>
            <td>leaveDate</td>
            <td>date</td>
            <td>在职日期</td>
        </tr>
         <tr>
            <td>salary</td>
            <td>int(10)</td>
            <td>薪资</td>
        </tr>
         <tr>
            <td>IDCard</td>
            <td>varchar(20)</td>
            <td>身份证号码</td>
        </tr>
         <tr>
            <td>number</td>
            <td>varchar(20)</td>
            <td>手机号码</td>
        </tr>
    </tbody>
</table>
### 删除数据接口：
<hr>
#### 公网：http://39.96.172.52:8080/del

#### 返回数据：string

#### 请求方式：get,http

#### 请求实例：http://39.96.172.52:8080/?ID=ID

#### 请求参数说明：被删除员工的ID

#### 返回参数说明：
<table>
    <thead>
        <tr>
            <td>名称</td>
            <td>类型</td>
            <td>说明</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>yes</td>
            <td>string</td>
            <td>删除成功</td>
        </tr>
         <tr>
            <td>no</td>
            <td>string</td>
            <td>删除失败</td>
        </tr>
    </tbody>
</table>
### 添加员工信息接口：
<hr>
#### 公网：http://39.96.172.52:8080/zc

#### 请求方式：get,http

#### 请求实例：http://39.96.172.52:8080/zc?

#### 请求参数说明：
<table>
    <thead>
        <tr>
            <td>名称</td>
            <td>类型</td>
            <td>说明</td>
        </tr>
    </thead>
    <tbody>
         <tr>
            <td>ID</td>
            <td>int(5)</td>
            <td>员工编号</td>
        </tr>
        <tr>
            <td>name</td>
            <td>varchar</td>
            <td>员工姓名</td>
        </tr>
        <tr>
            <td>sex</td>
            <td>int(1)</td>
            <td>员工性别</td>
        </tr>
         <tr>
            <td>birthday</td>
            <td>date</td>
            <td>出生日期</td>
        </tr>
         <tr>
            <td>department</td>
            <td>varchar(255)</td>
            <td>部门</td>
        </tr>
         <tr>
            <td>status</td>
            <td>int(1)</td>
            <td>在职状态</td>
        </tr>
         <tr>
            <td>joinDate</td>
            <td>date</td>
            <td>离职日期</td>
        </tr>
         <tr>
            <td>leaveDate</td>
            <td>date</td>
            <td>在职日期</td>
        </tr>
         <tr>
            <td>salary</td>
            <td>int(10)</td>
            <td>薪资</td>
        </tr>
         <tr>
            <td>IDCard</td>
            <td>varchar(20)</td>
            <td>身份证号码</td>
        </tr>
         <tr>
            <td>number</td>
            <td>varchar(20)</td>
            <td>手机号码</td>
        </tr>
    </tbody>
</table>

#### 返回参数说明：
<table>
    <thead>
        <tr>
            <td>名称</td>
            <td>类型</td>
            <td>说明</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>yes</td>
            <td>string</td>
            <td>删除成功</td>
        </tr>
         <tr>
            <td>no</td>
            <td>string</td>
            <td>删除失败</td>
        </tr>
    </tbody>
</table>
## 修改员工信息接口
<hr>
#### 公网：http://39.96.172.52:8080/xg

#### 请求方式：get,http

#### 请求实例：http://39.96.172.52:8080/xg?

#### 请求参数说明：
<table>
    <thead>
        <tr>
            <td>名称</td>
            <td>类型</td>
            <td>说明</td>
        </tr>
    </thead>
    <tbody>
         <tr>
            <td>ID</td>
            <td>int(5)</td>
            <td>员工编号</td>
        </tr>
        <tr>
            <td>name</td>
            <td>varchar</td>
            <td>员工姓名</td>
        </tr>
        <tr>
            <td>sex</td>
            <td>int(1)</td>
            <td>员工性别</td>
        </tr>
         <tr>
            <td>birthday</td>
            <td>date</td>
            <td>出生日期</td>
        </tr>
         <tr>
            <td>department</td>
            <td>varchar(255)</td>
            <td>部门</td>
        </tr>
         <tr>
            <td>status</td>
            <td>int(1)</td>
            <td>在职状态</td>
        </tr>
         <tr>
            <td>joinDate</td>
            <td>date</td>
            <td>离职日期</td>
        </tr>
         <tr>
            <td>leaveDate</td>
            <td>date</td>
            <td>在职日期</td>
        </tr>
         <tr>
            <td>salary</td>
            <td>int(10)</td>
            <td>薪资</td>
        </tr>
         <tr>
            <td>IDCard</td>
            <td>varchar(20)</td>
            <td>身份证号码</td>
        </tr>
         <tr>
            <td>number</td>
            <td>varchar(20)</td>
            <td>手机号码</td>
        </tr>
    </tbody>
</table>

#### 返回参数说明：
<table>
    <thead>
        <tr>
            <td>名称</td>
            <td>类型</td>
            <td>说明</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>yes</td>
            <td>string</td>
            <td>删除成功</td>
        </tr>
         <tr>
            <td>no</td>
            <td>string</td>
            <td>删除失败</td>
        </tr>
    </tbody>
</table>


