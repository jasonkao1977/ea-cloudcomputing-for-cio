# 10. Hybrid Cloud Network Topology

## 視圖概述
專注於網路連接性的視圖。展示地端與雲端的物理連接路徑與流量分發策略。

## 連接元件
* [cite_start]**地端邊緣**: Edge Gateway, SD-WAN [cite: 24-25]。
* **傳輸層 (Connectivity)**:
    * [cite_start]Direct Connect (10Gbps): 主線路 [cite: 25]。
    * [cite_start]ExpressRoute (1Gbps): 備援/多雲線路 [cite: 25]。
    * [cite_start]VPN: 加密備援通道 [cite: 25]。
* [cite_start]**雲端網路**: Transit Gateway (傳輸閘道器), VPC/vNet [cite: 25]。

![Hybrid Cloud Network Topology](img/10_hybrid_network_topology.png)