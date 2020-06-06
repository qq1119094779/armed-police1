<template>
    <div>
      <div class="notice">
        <p>110报警联动：18:25  金水路东明路东北角金水路东明路东北角金水路东明路东北角金水路东明路东北角金水路东明路东北角</p>
      </div>
    </div>
</template>

<script>
export default {
  name: "notice"
}
</script>

<style scoped>

  .notice{
    position: absolute;
    width: 728px;
    height: 122px;
    top: 68px;
    left: 40px;
    z-index: 300;
    background: url("../../assets/notice.png");
  }
  .notice p{
    padding-left: 133px;
    line-height: 122px;
    font-size: 24px;
    color: #FFFFFF;
    text-overflow: -o-ellipsis-lastline;
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 1;
    line-clamp: 1;
    -webkit-box-orient: vertical;
  }
</style>
