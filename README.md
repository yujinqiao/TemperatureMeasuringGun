# TemperatureMeasuringGun
红外测温枪学习方案
功能描述:

注：按键分为上、下、左、右按键

实现了测温功能、采集电压功能和预警处理提示功能

1、按左键，直接退出主界面
2、按右键，进入选择测温、测压界面
3、按住上键，进行测温，当出现发烧情况会蜂鸣器+红灯闪烁报警，不同的发烧程度，报警的频率不同
   发烧越严重，频率很快 （在主界面不可直接进入）
4、按下键，进行测压，当低压时，蜂鸣器+绿灯闪烁报警提示（在主界面不可直接进入）
 
 

人的发烧温度： //发热分为： 低热 ：37.2～38℃；中等度热：38．1～39℃：高热：39．1～41℃； 
	                              超高热 ：41℃以上




注：测温时，不能贴到肉上，需要离肉0.5cm左右

V2版本把u8、u16、u32修改成标准的uint8_t/uint16_t/uint32_t 