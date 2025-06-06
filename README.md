# CH9121配置工具NetModuleConfig.zip

## 软件介绍

CH9121配置工具内附使用说明和电路原理图。该工具允许用户配置CH9121模块的网络参数，并提供了详细的使用说明和配置示例。通过该工具，用户可以轻松地搜索、配置和管理CH9121模块。

## 使用说明

1. **搜索设备**：
   - 运行NetModuleConfig.exe后，点击“搜索设备”按钮，设备列表会显示出当前子网内的所有CH9121模块。

   2. **配置设备参数**：
      - 在设备列表中双击某个模块，可以获取该模块的当前配置信息。
         - 在左侧的参数设置区域，根据实际需求修改模块的参数，如网络模式、IP地址、端口等。
            - 修改完成后，点击“配置设备参数”按钮，模块会自动重启并应用新的配置。

            3. **查看配置结果**：
               - 配置完成后，稍等片刻，再次点击“搜索设备”按钮，找到刚刚配置的模块，查看配置结果是否正确。

               ## 配置示例

               ### 示例：CH9121工作在TCP客户端模式

               1. **硬件连接**：
                  - 将CH9121模块通过网线与计算机直接相连，或者将模块和计算机接入到同一个局域网内。

                  2. **计算机端设置**：
                     - 运行串口与TCP/UDP调试工具，创建TCP服务器。
                        - 设置如下：
                             - 协议类型：TCP SERVER
                                  - 本地IP：192.168.1.100
                                       - 端口：1000
                                            - 当前连接状态：TCP服务器监听中

                                            3. **模块参数设置**：
                                               - 运行NetModuleConfig.exe，设置模块参数。
                                                  - 根据实际需求修改模块参数，设置网络方式为TCP CLIENT，目的IP和目的端口与TCP SERVER的IP和端口一致：192.168.1.100:1000。
                                                     - 根据需求修改波特率等参数，然后点击“配置模块”。

                                                     4. **数据收发测试**：
                                                        - 此时计算机端串口调试软件显示CH9121模块客户端已连接。
                                                           - 选好串口参数，打开串口即可进行数据收发测试。

                                                           ## 注意事项

                                                           - 确保计算机和模块在同一网络环境下，以便正确搜索和配置模块。
                                                           - 配置完成后，模块会自动重启，请耐心等待配置生效。
                                                           - 如有任何问题，请参考附带的使用说明和电路原理图。

                                                           ---

                                                           通过以上步骤，您可以轻松配置和管理CH9121模块，实现网络通信功能。

                                                           ## 下载链接
                                                           [CH9121配置工具NetModuleConfig.zip](https://pan.quark.cn/s/fbfdf4b743e7) 

                                                           (备用: [备用下载](https://pan.baidu.com/s/1QRpLe-1oUWC1iatvIgODdA?pwd=1234))
