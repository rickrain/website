
<!-- 
### Synopsis 
-->
## 概要

<!-- 
Register the new control-plane node into the ClusterStatus maintained in the kubeadm-config ConfigMap 
-->
将新的控制平面节点注册到 kubeadm-config ConfigMap 中维护的 ClusterStatus 中

```
kubeadm join phase control-plane-join update-status [flags]
```

<!-- 
### Options 
-->
### 选项

<table style="width: 100%; table-layout: fixed;">
  <colgroup>
    <col span="1" style="width: 10px;" />
    <col span="1" />
  </colgroup>
  <tbody>

    <tr>
      <td colspan="2">--apiserver-advertise-address string</td>
    </tr>
    <tr>
      <td></td><td style="line-height: 130%; word-wrap: break-word;">
      <!--
      If the node should host a new control plane instance, the IP address the API Server will advertise it's listening on. If not set the default network interface will be used.
      -->
      如果该节点托管一个新的控制平面实例，则 API Server 的 IP 地址将通知其正在侦听的地址。如果未设置，将使用默认网络接口。
      </td>
    </tr>

    <tr>
      <td colspan="2">--config string</td>
    </tr>
    <tr>
      <td></td><td style="line-height: 130%; word-wrap: break-word;">
      <!--
      Path to kubeadm config file.
      -->
      到 kubeadm 配置文件的路径。
      </td>
    </tr>

    <tr>
      <td colspan="2">--control-plane</td>
    </tr>
    <tr>
      <td></td><td style="line-height: 130%; word-wrap: break-word;">
      <!--
      Create a new control plane instance on this node
      -->
      在此节点上创建一个新的控制平面实例
      </td>
    </tr>

    <tr>
      <td colspan="2">-h, --help</td>
    </tr>
    <tr>
      <td></td><td style="line-height: 130%; word-wrap: break-word;">
      <!--
      help for update-status
      -->
       update-status 操作的帮助命令
      </td>
    </tr>

    <tr>
      <td colspan="2">--node-name string</td>
    </tr>
    <tr>
      <td></td><td style="line-height: 130%; word-wrap: break-word;">
      <!--
      Specify the node name.
      -->
      指定节点名称。
      </td>
    </tr>

  </tbody>
</table>



### Options inherited from parent commands

<table style="width: 100%; table-layout: fixed;">
  <colgroup>
    <col span="1" style="width: 10px;" />
    <col span="1" />
  </colgroup>
  <tbody>

    <tr>
      <td colspan="2">--rootfs string</td>
    </tr>
    <tr>
      <td></td><td style="line-height: 130%; word-wrap: break-word;">
      <!--
      [EXPERIMENTAL] The path to the 'real' host root filesystem.
      -->
      [实验性功能] “真实” 主机根文件系统的路径。
      </td>
    </tr>

  </tbody>
</table>



<!-- 
SEE ALSO 
-->
查看其他

<!-- 
* [kubeadm join phase control-plane-join](kubeadm_join_phase_control-plane-join.md)	 - Join a machine as a control plane instance 
-->
* [kubeadm join phase control-plane-join](kubeadm_join_phase_control-plane-join.md)	 - 加入机器作为控制平面实例 

