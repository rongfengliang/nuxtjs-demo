<template>
 <div class="demo">
     {{idmessage}}
 </div>
</template>
<script>
export default {
  data ({params}) {
    return {
      idmessage: params.id
    }
  }
}
</script>

