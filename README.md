ParkingManagement
=================

任务分配：
一、需求1

		1、停车：
			(1)如果有人来停车，先查看停车场1是否有空车位。
			(2)如果停车场1有空车位，登记车辆信息，发给司机停车信息，引导司机停车到停车场1。
			(3)如果停车场1无空车位，停车场2有空车位，登记车辆信息，发给司机停车信息，引导司机停车到停车场2。
			(4)如果停车场1无空车位，停车场2也无空车位，拒绝停车。
			(5)如果成功停车，相应的空车位个数减1，触发显示屏刷新，
		
		2、取车
			(1)如果有人来取车，先收卡，读取已停车的信息。
			(2)如果相应的停车场车位全为空，则不允许停车。
			(2)如果车卡一致，放行。
			(4)如果放行，相应停车场的空车位个数加1，触发显示屏刷新。


