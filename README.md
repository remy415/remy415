# 👋 About me: Jack of All Trades, King of Some Trades. 👋
## 👀 I’m interested in...
  * ✨✨✨ __`Cool technology`__ ✨✨✨

  * Finding ~~lazy~~ **`optimized` execution strategies** for tasks
  * Learning a little bit about everything, mastering interesting or effective techniques/tools
  * Discovering my niche in the industry
  * Consulting: I love matching requirement to solution and I love educating. <br>
## 🌱 I’m currently learning: ~~All the things.~~ K-U-B-E-R-N-E-T-E-S<br>
### K8S (mostly Rancher/K3S)
  Currently have 1 bare-metal node: `8C Ryzen 1800X, 64GB RAM, and 2TB storage.`<br><br>
    Installed Harvester, currently experimenting with creating multiple node VMs for "HA" Cluster setup controlled by a rancher VM/cluster.
    
  Future projects: 
- [ ] Importing SBC nodes
- [ ] Configure load balancing/ingress (Likely NGINX)
- [ ] Set up Unifi controller as a container
- [ ] Benchmark/run ML/AI workloads. Also considering blockchain, mining, or crowdsourced scientific number crunching projects.

### SBCs
  - Purchased a Turing Pi 2 Mobo through KickStarter, supported compute cards are: <br>

| Vendor |	Model |	CPU |	Cores	| RAM | PRICE |
| :---------:    |:-------:    |     :---:    |     :---:    |     :---:    | :---: |
| Raspberry Pi |	CM4 |	Broadcom BCM2711 |	4 |	2, 4, 8 | $$ |
| Nvidia	Jetson  |	Nano |	Quad-core ARM Cortex-A57 MPCore |	4 |	2, 4 | $$ |
| Nvidia	Jetson  |	TX2 NX | Dual-core NVIDIA Denver 2, Quad-core ARM A57 Complex	| 6	| 4 | $$ |
| Nvidia	Jetson |	Xavier NX |	NVIDIA Carmel ARM®v8.2 |	6	| 8 |	 $$ |
| Turing Pi	 |	TCM	 |	TBA	 |	TBA |		TBA | TBA |

  - Currently own a small cluster of 4 Khadas VIM3s, 2x VIM3 Basic and 2x VIM3 Pro.
    - Specs:
    ```
      - 2GB RAM/16GB eMMC (VIM3 Basic) / 4GB RAM/32GB eMMC (VIM3 Pro)
      - Amlogic A311D SoC:
        - x4 Cortex A73 performance-cores (2.2Ghz)
        - x2 Cortex A53 efficiency-cores (1.8Ghz)
      - NPU
        - 5 TOP (tera-operations) "neural processing unit". Great small/low power ML/AI accelerator
      ```
      - Compatible with NVMe drives. Speeds top out around 500 MB/s, not fantastic but not terrible either. Recommend WD Blue 512MB NVMe, low-power to support system stability due to device being powered over USB-C port and the inconsistency of USB Power bricks.
    - Waiting for 2x M.2 expansion cards to arrive to set up the NVMe drives
    - Installed the ARM64 Ubuntu distro, overlayed with K3S. Haven't quite figuered out how to connect it to my cluster, having minor issues with things like Helm not recognizing the aarch64 distro when installing Rancher. I think I've gotten it figured out, there just aren't enough hours in the day to resolve it.
    - Khadas provides small "rescue" boot image that can install new OSes through hosted cloud images on their servers. Very convenient for testing/troubleshooting!
## 💞️ I’m looking to collaborate on ...
K8S, Rancher, or SBC Clusters :)
## 📫 How to reach me ...
Feel free to reach out on Github.
<!---
remy415/remy415 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
