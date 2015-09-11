# huginn
huginn(view)


##How to use

### 1. http server　に設置

### 2.huginn.html

```
<td>
<canvas id="server_name1" width="100" height="100">
<script>
var server= "192.168.x.xxx:3002";
//specifies the IP-address for the server
var id = "server_name";
var title="server_name  monitor";
var maxY="16";
//Specifies the maximum number of CPU-core
campus(server,id,title,maxY);
</script>
</canvas>
</td>
```

> var server= "192.168.x.xxx:3002";

IPアドレスを指定

> var maxY="16";

CPUコア数を指定

### 3. http://xxx.xxxx.xxx.xxx/huginn.html　でアクセス




