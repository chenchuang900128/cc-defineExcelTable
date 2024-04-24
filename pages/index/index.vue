<template>
	<view class="content">


		<div class="table">
			<table>
				<!-- 第一行 -->
				<tr>
					<!-- rowspan行高： 2  colspan列高： 2 -->
					<td rowspan="2" colspan="2">项目</td>

					<td colspan="2">{{"2021"}}</td>
					<td colspan="2">{{"2022"}}</td>
					<td colspan="2">{{"2023"}}</td>

				</tr>


				<!-- 第二行 -->
				<tr>

					<td>指标值</td>
					<td>同比</td>
					<td>指标值</td>
					<td>同比</td>
					<td>指标值</td>
					<td>同比</td>


				</tr>

				<!-- 第三行 -->
				<tr>
					<td rowspan="5">公司历年情况</td>
					<td>营业金额（万元）</td>
					<td>{{"Num"}}</td>
					<td>{{"Yoy"}}</td>
					<td>{{"Num"}}</td>
					<td>{{"Yoy"}}</td>
					<td>{{"Num"}}</td>
					<td>{{"Yoy"}}</td>
				</tr>

				<!-- 第四行 -->
				<tr>
					<td>营业税额（万元）</td>
					<td>{{"Num"}}</td>
					<td>{{"Yoy"}}</td>
					<td>{{"Num"}}</td>
					<td>{{"Yoy"}}</td>
					<td>{{"Num"}}</td>
					<td>{{"Yoy"}}</td>
				</tr>
				<!-- 第五行 -->
				<tr>
					<td>营业数量（张）</td>
					<td>{{"Num"}}</td>
					<td>{{"Yoy"}}</td>
					<td>{{"Num"}}</td>
					<td>{{"Yoy"}}</td>
					<td>{{"Num"}}</td>
					<td>{{"Yoy"}}</td>
				</tr>
				<!-- 第六行 -->
				<tr>
					<td>供应商数量（个）</td>
					<td>{{"Num"}}</td>
					<td>{{"Yoy"}}</td>
					<td>{{"Num"}}</td>
					<td>{{"Yoy"}}</td>
					<td>{{"Num"}}</td>
					<td>{{"Yoy"}}</td>
				</tr>
				<!-- 第七行 -->
				<tr>
					<td>供应商稳定性（%）</td>
					<td>{{"Num"}}</td>
					<td>{{"Yoy"}}</td>
					<td>{{"Num"}}</td>
					<td>{{"Yoy"}}</td>
					<td>{{"Num"}}</td>
					<td>{{"Yoy"}}</td>
				</tr>

			</table>
		</div>




	</view>
</template>

<script>
	export default {
		data() {
			return {

			}
		},
		onLoad() {

		}
	}
</script>

<style scoped>
	.content {
		display: flex;
		flex-direction: column;
	
	}
	
	
	
	.table {
		margin: 0px 10px;
		width: calc(100vw - 20px);
		text-align: center;
		background-color: white;
	}
	
	.table table {
		border-right: 1px solid #000;
		border-bottom: 1px solid #000;
		/* 设置边缘间距0 */
		border-spacing: 0;
		/* 用于表格属性, 表示表格的两边框合并为一条 */
		border-collapse: collapse
	}
	
	.table table td {
		border-left: 1px solid #000;
		border-top: 1px solid #000;
		text-align: center;
		font-size: 12px;
		font-weight: bold;
		border-right: 1px solid #000;
	
	}
	
	.table table tr td {
		width: 12.5%;
	}
	
	
	.table table tr:first-child {
	
		background-color: rgb(204, 236, 255);
	}
	
	.table table tr:nth-child(2) {
	
		background-color: rgb(204, 236, 255);
	}
</style>