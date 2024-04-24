# cc-defineExcelTable

#### 使用方法

```使用方法
 <!-- 第一行 -->
                <tr>
                    <!-- rowspan行高： 2  colspan列高： 2 -->
                    <td rowspan="2" colspan="2">项目</td>

                    <td colspan="2">{{"2021"}}</td>
                    <td colspan="2">{{"2022"}}</td>
                    <td colspan="2">{{"2023"}}</td>

                </tr>
```

#### HTML代码实现部分
```html

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


```