<script lang="ts">
  import { ElNotification } from 'element-plus';

  export default {
    mounted () {
      ElNotification.success({
        title: '推广大使计划2.0全新发布',
        message: '<a href="https://element-plus.org" target="_blank">点击查看详情</a>',
        dangerouslyUseHTMLString: true,
        offset: 100,
        duration: 5000,
      })
    }
  }
</script>