联想小新Air14 2018 clover
enovo-XIAOXIN-Ari14-2018-Clover

主要配置：
  1.CPU i5-8250U
  2.GPU UHD620(独显屏蔽)
  3.声卡 Realtek ALC236
  4.无线网卡  BCM94352(联想专用,缺口和原装不一样不影响)


V2:2019/09/30
触摸板正常,变频正常,跑软件时频率上的去,耳机有些小问题,可以打补丁修复,我懒得弄了
  

V1:2018/11/24
目前在10.14 - 10.14.1 使用没多大问题
情况如下：
  1.显卡使用Intel FB-Patcher驱动，可以不用仿冒其他ID即可驱动，如若单纯只仿冒ID驱动界面会很卡
  2.声卡外放驱动正常，耳机接口声音会有噪音
  3.HDMI显示正常，声音还未修复
  4.触摸板可使用，有轻微漂移现象
  5.蓝牙 wifi双系统都可使用，切换系统后要重新配对
  6.hidpi可开启，如果开启失败请检查是否有以下配置
    <key>RtVariables</key>
    	<dict>
		    <key>BooterConfig</key>
	    	<string>0x28</string>
		    <key>CsrActiveConfig</key>
		    <string>0x67</string>
	    </dict>
