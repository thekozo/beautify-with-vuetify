</template>

<template>
  <div>
    <iframe ref="myFrame" src="https://tradingeconomics.com/commodities" @load="onFrameLoad"></iframe>
  </div>
</template>

<script>
export default {
  methods: {
    onFrameLoad() {
      // Lấy tham chiếu đến phần tử iframe
      const myFrame = this.$refs.myFrame;
      
      // Lấy tham chiếu đến document bên trong iframe
      const iframeDoc = myFrame.contentDocument || myFrame.contentWindow.document;
      
      // Lấy tham chiếu đến phần tử cần xóa
      const menu = iframeDoc.getElementById('ctl00_NavigationUC1_ctl00_menu');
      
      // Xóa phần tử menu
      menu.parentNode.removeChild(menu);
    }
  }
};
</script>
