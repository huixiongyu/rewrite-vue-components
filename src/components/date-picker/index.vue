<template>
    <div class="date-picker">
        <input type="text" placeholder="选择日期">
        <div class="picker-box">
            <div class="picker-header">
                <div class="pre">《</div>
                <div class="year-month">
                    <span class="year">2020年</span>
                    <span class="month">3月</span>
                </div>
                <div class="next">》</div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
  name: 'date-picker',
};
</script>
<style lang="scss" scoped>
    .date-picker{
        color: #606266;
    }
    .picker-box{
        width: 324px;
        border: 1px solid #e4e7ed;
        background: #fff;
        border-radius: 4px;
        .picker-header{
            height: 50px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
    }
</style>
