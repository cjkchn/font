<template>
	<div class="back">
		<div class="ant-page-header">
			<div class="ant-page-header-heading">
				<div class="ant-page-header-heading-left">
					<span class="ant-page-header-heading-title">北京博珥佐特软件科技有限公司上海分公司
					</span>
				</div>
			</div>
			<div class="ant-page-header-content">
				北京博珥佐特软件科技有限公司上海分公司成立于2017年01月24日，注册地位于上海市闵行区新龙路1333弄111号501室，法定代表人为KIM
				KIHO。经营范围包括技术推广服务，计算机系统服务，电脑图文设计、制作，销售电子产品、计算机、软件及辅助设备、文具用品、机械设备。 【依法须经批准的项目，经相关部门批准后方可开展经营活动】
				<div class="list-card__link">
					<a>
						<span class="app-iconify anticon"
							style="font-size: 16px; color: rgb(24, 144, 255); display: inline-flex;"></span>
						<i class="el-icon-document"></i>
					</a>

				</div>
			</div>
		</div>
		<div class="overflow-hidden vben-page-wrapper-content">
			<div class="list-card__content">
				<div class="ant-list ant-list-split">
					<div class="ant-spin-nested-loading">
						<div class="ant-spin-container">
							<div class="ant-row" style="margin-left: -8px; margin-right: -8px; row-gap: 0px;">

								<div class="ant-col ant-col-6" style="padding-left: 70px; padding-right: 8px;">
									<li class="ant-list-item">
										<div class="ant-card ant-card-bordered ant-card-hoverable list-card__card">
											<div class="ant-card-body" @mouseover="mouseOver" @mouseleave="mouseLeave"
												:style="active">
												<div class="list-card__card-title">
													<span class="icon app-iconify anticon icon"
														style="font-size: 16px; color: rgb(24, 144, 255); display: inline-flex;">
														<img style="margin:0 8px 0 0; height: 25px; width: 25px;;"
															src="../assets/pt1-manager.png" />
													</span>
													<span style="position:relative;width:100px;height:100px;top:-6px;">
														<a style="font-weight: 700;text-decoration : none;color: #551a8b;"
															:href="'http://123.60.37.11:81/ptl-manager/#/login'">ptl-manager</a>
													</span>

													<div
														style="margin: 10px 8px 20px 10px;border-top:1px dotted #C0C0C0;width: 300px;">
													</div>

													<a>项目负责人:安部长</a><br /><br />
													<a>创建时间:2021年5月15日</a>
												</div>
												<div class="list-card__card-detail"> 物流智能分拣系统，提高分拣效率，
													优化分拣流程，提升出单数量。针对目前国内大多数物流分拣集散中心仍采用成本较高,效率和准确率较低的人工分拣方式。 </div>
											</div>
											<div class="hover_container" v-if="showHover">
												显示内容
											</div>
										</div>
									</li>
								</div>



								<div class="ant-col ant-col-6" style="padding-left: 80px; padding-right: 8px;">
									<li class="ant-list-item">
										<div class="ant-card ant-card-bordered ant-card-hoverable list-card__card">
											<div class="ant-card-body" @mouseover="mouseOvertwo"
												@mouseleave="mouseLeavetwo" :style="activetwo">
												<div class="list-card__card-title">
													<span class="icon app-iconify anticon icon"
														style="font-size: 16px; color: rgb(24, 144, 255); display: inline-flex;">
														<i></i>
													</span>
													<img style="margin:0 8px 0 0; height: 25px; width: 25px;;"
														src="../assets/pt1-manager.png" />
													<span style="position:relative;width:100px;height:100px;top:-6px;">
														<a style="font-weight: 700;text-decoration : none;color: #551a8b;"
															:href="'http://123.60.37.11:81/ptl-operator/#/login'">ptl-operator</a>
													</span>
													<div
														style="margin: 10px 8px 20px 10px;border-top:1px dotted #C0C0C0;width: 300px;">
													</div>
													<a>项目负责人:安部长</a><br /><br />
													<a>创建时间:2021年5月15日</a>
												</div>
												<div class="list-card__card-detail">物流智能分拣系统，提高分拣效率，
													优化分拣流程，提升出单数量。针对目前国内大多数物流分拣集散中心仍采用成本较高,效率和准确率较低的人工分拣方式。 </div>
											</div>

										</div>
									</li>
								</div>
								<div class="ant-col ant-col-6" style="padding-left: 80px; padding-right: 8px;">
									<li class="ant-list-item">
										<div class="ant-card ant-card-bordered ant-card-hoverable list-card__card">
											<div class="ant-card-body" @mouseover="mouseOverThree"
												@mouseleave="mouseLeaveThree" :style="activeThree">
												<div class="list-card__card-title">
													<span class="icon app-iconify anticon icon"
														style="font-size: 16px; color: rgb(24, 144, 255); display: inline-flex;">
														<img style="margin:0 8px 0 0; height: 25px; width: 25px;;"
															src="../assets/Visitor.png" />
													</span>
													<span style="position:relative;width:100px;height:100px;top:-6px;">
														<a style="font-weight: 700;text-decoration : none ;color: #551a8b;"
															:href="'http://123.60.37.11:82/#/dashboard/analysis'">Visitor</a>
													</span>
													<div
														style="margin: 10px 8px 20px 10px;border-top:1px dotted #C0C0C0;width: 300px;">
													</div>
													<a>项目负责人:安部长</a><br /><br />
													<a>创建时间:2021年8月24日</a>
												</div>
												<div class="list-card__card-detail">访客系统针对各个工厂出入申请，临时访
													客管理，统计以及处理应急情况一套系统。<br /><br /><br /></div>
											</div>

										</div>
									</li>
								</div><br /><br /><br /><br /><br /><br />
								<div class="ant-col ant-col-6" style="padding-left: 69px; padding-right: 8px;">
									<li class="ant-list-item">
										<div class="ant-card ant-card-bordered ant-card-hoverable list-card__card">
											<div class="ant-card-body" @mouseover="mouseOverFour"
												@mouseleave="mouseLeaveFour" :style="activeFour">
												<div class="list-card__card-title">
													<span class="icon app-iconify anticon icon"
														style="font-size: 16px; color: rgb(24, 144, 255); display: inline-flex;">
														<i></i>
													</span>
													<img style="margin:0 8px 0 0; height: 25px; width: 25px;;"
														src="../assets/WMS.png" />
													<span style="position:relative;width:100px;height:100px;top:-6px;">
														<a style="font-weight: 700;text-decoration:none;color: #551a8b;"
															:href="'http://123.60.37.11:84/dataview/user/login '">WMS</a>
													</span>
													<div
														style="margin: 10px 8px 20px 10px;border-top:1px dotted #C0C0C0;width: 300px;">
													</div>
													<a>项目负责人:安部长</a><br /><br />
													<a>创建时间:2021年11月19日</a>
												</div>
												<div class="list-card__card-detail"> WMS是仓库管理系统(Warehouse Management
													System)
													的缩写，仓库管理系统是通过入库业务、出库业务、仓库调拨、库存调拨和虚仓管理等功能，对批次管理、物料对应、库存盘点、质检管理、虚仓管理和即时库存管理等功能综合运用的管理系统。
												</div>
											</div>

										</div>
									</li>
								</div>


							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {
  props: {
    msg: String
  },
  data() {
    return {
		count: 0,
		showHover: false,
		active: "",
		activetwo: "",
		activeThree: "",
		activeFour: ""
    }
	},
	methods: {
		// 移入
		mouseOver() {
			this.active = "box-shadow:0px 0px 8px #000	;";
			// 操作dom 获取p标签改变其样式
		},
		// 移出
		mouseLeave() {
			this.active = "";
		},
		mouseOvertwo() {
			this.activetwo = "box-shadow:0px 0px 10px #000;";
		},
		mouseLeavetwo() {
			this.activetwo = "";
		},
		mouseOverThree() {
			this.activeThree = "box-shadow:0px 0px 10px #000;";
		},
		mouseLeaveThree() {
			this.activeThree = "";
		},
		mouseOverFour() {
			this.activeFour = "box-shadow:0px 0px 10px #000;";
		},
		mouseLeaveFour() {
			this.activeFour = "";
		}
	}
	
}
</script>

<style>







	/* //这是白的背景 */
	.back{
		background-color: #f0f2f5;
		width: 100%;
		height: 100%;
	}
	.ant-page-header {
	    box-sizing: border-box;
	    margin: 0;
	    color: #000000d9;
	    font-size: 14px;
	    font-variant: tabular-nums;
	    line-height: 1.5715;
	    list-style: none;
	    font-feature-settings: tnum;
	    position: relative;
	    padding: 16px 24px;
	    background-color: #fff;
		/* border: 1px solid black; */
	}
	
	.ant-page-header-heading {
	    display: flex;
	    justify-content: space-between;
	}
	
	.ant-page-header-heading-left {
	    display: flex;
	    align-items: center;
	    margin: 4px 0;
	    overflow: hidden;
	}
	
	.ant-page-header-heading-title {
	    margin-right: 12px;
	    margin-bottom: 0;
	    color: #000000d9;
	    font-weight: 600;
	    font-size: 25px;
	    line-height: 32px;
	    overflow: hidden;
	    white-space: nowrap;
	    text-overflow: ellipsis;
	}
	
	.ant-page-header-content {
	    padding-top: 12px;
	}
	
	.list-card__link {
	    margin-top: 10px;
	    font-size: 14px;
	}
	
	.size-color {
		color: #0960bd;
		text-decoration: none;
		background-color: transparent;
		outline: none;
		cursor: pointer;
		transition: color .3s;
		margin-right: 30px;
	}
	
	.vben-page-wrapper .vben-page-wrapper-content {
	    margin: 16px;
	}
	
	.ant-spin-container {
	    position: relative;
	    transition: opacity .3s;
	}
	
	.ant-col-6 {
	    display: inline-block;
	    flex: 0 0 25%;
	    max-width: 25%;
	}
	
	.ant-col {
	    position: relative;
	    max-width: 100%;
	    min-height: 1px;

	}
	
	.ant-list-item {
	    display: flex;
	    align-items: center;
	    justify-content: space-between;
	    padding: 12px 0;
	    color: #000000d9;
	}
	
	.ant-list-split .ant-list-item:last-child {
	    border-bottom: none;
	}
	
	.list-card__card {
	    width: 100%;
	    margin-bottom: -8px;
	}
	
	.ant-card-body {
	    padding: 24px;
		border-radius: 10px;
	}
	
	.list-card__card-title {
	    margin-bottom: 5px;
	    font-size: 16px;
	    font-weight: 500;
	    color: #000000d9;
	}
	
	.list-card__card-detail {
	    padding-top: 10px;
	    padding-left: 30px;
	    font-size: 14px;
	    color: #00000073;
	}
	
	.ant-list * {
	    outline: none;
	}
	
	.vben-page-wrapper-content {
	    margin: 16px;
	}
	
	.ant-layout, .ant-layout * {
	    box-sizing: border-box;
	}
	
	.ant-col-6 {
		width: 368.42px;
		height: 200px;
		
	}
	
	.ant-card-body {
		background-color: #fff;
	}
		.hover_container {
			width: 366px;
			height: 260px;
			border: 1px solid #ccc;
			border-radius: 8px;
			text-align: center;
			line-height: 98px;
			position: absolute;
			left: 70px;
			top: 70%;
			z-index: 99;
			transform: translateY(-50%);
		}
</style>