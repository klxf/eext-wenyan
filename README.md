![wywywy](https://github.com/user-attachments/assets/5adaaeb0-48f3-450a-b04a-45ba0df3e014)
<p align="center">
  <a href="https://github.com/klxf/eext-wenyan/releases/tag/v0.0.2">【体验预览版】</a>
</p>

# 吾有一术

## 简介
阿巴阿巴

## 完成进度

🔴未完成；🟡部分完成；🟢已完成

| 方法                                                                                                                    | 实现                                                                 | 枚举                                                                                                    | 实现         |
|:--------------------------------------------------------------------------------------------------------------------- |:------------------------------------------------------------------:| ----------------------------------------------------------------------------------------------------- |:----------:|
| [SYS_Log.add()](https://prodocs.lceda.cn/cn/api/reference/pro-api.sys_log.add.html)                                   | 🟢<br>錄日誌                                                          | [ESYS_LogType](https://prodocs.lceda.cn/cn/api/reference/pro-api.esys_logtype.html)                   | 🟢<br>日誌之屬 |
| [SYS_Log.clear()](https://prodocs.lceda.cn/cn/api/reference/pro-api.sys_log.clear.html)                               | 🟢<br>毀日誌                                                          | [ESYS_ToastMessageType](https://prodocs.lceda.cn/cn/api/reference/pro-api.esys_toastmessagetype.html) | 🟢<br>吐司之屬 |
| [SYS_Message.showToastMessage()](https://prodocs.lceda.cn/cn/api/reference/pro-api.sys_message.showtoastmessage.html) | 🟢<br>[吐司傳信](https://github.com/klxf/eext-wenyan/wiki/傳信之術#吐司傳信)   |                                                                                                       |            |
| [SYS_Unit.getSystemDataUnit()](https://prodocs.lceda.cn/cn/api/reference/pro-api.sys_unit.getsystemdataunit.html)     | 🟢<br>[獲系統跨度](https://github.com/klxf/eext-wenyan/wiki/轉制之術#獲系統跨度) |                                                                                                       |            |
| [SCH_Drc.check()](https://prodocs.lceda.cn/cn/api/reference/pro-api.sch_drc.check.html)                               | 🟢<br>[依繪圖之法察](https://github.com/klxf/eext-wenyan/wiki/依繪圖之法察)    |                                                                                                       |            |
| [SCH_PrimitiveWire.create()](https://prodocs.lceda.cn/cn/api/reference/pro-api.sch_primitivewire.create.html)         | 🟢<br>[紙上繪線](https://github.com/klxf/eext-wenyan/wiki/繪圖之術#紙上繪線)   |                                                                                                       |            |
| [PCB_PrimitiveLine.create()](https://prodocs.lceda.cn/cn/api/reference/pro-api.sch_primitiveline.create.html)         | 🟢<br>[板上繪線](https://github.com/klxf/eext-wenyan/wiki/繪圖之術#板上繪線)   | [EPCB_LayerId](https://prodocs.lceda.cn/cn/api/reference/pro-api.epcb_layerid.html)                   | 🟡<br>板層   |
| [PCB_PrimitiveVia.create()](https://prodocs.lceda.cn/cn/api/reference/pro-api.pcb_primitivevia.html)                  | 🟢<br>板上繪孔                                                         | [EPCB_PrimitiveViaType](https://prodocs.lceda.cn/cn/api/reference/pro-api.epcb_primitiveviatype.html) | 🟢<br>過孔之屬 |

## 示例代码
- 绘制希尔伯特曲线：[繪希氏圖.wy](https://github.com/klxf/eext-hilbert-creator/blob/master/src/%E7%B9%AA%E5%B8%8C%E6%B0%8F%E5%9C%96.wy)
