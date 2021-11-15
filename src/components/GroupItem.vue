<template>
  <div>
    <ul class="flexC">
      <div class="box-img-icon-blu">
        <img :src="require('@/assets/' + img)" alt=""/>
      </div>

      <li class="icon-blu-main">
        {{ tittle }}
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "GroupItem",
  props: ["tittle","img"],
};
</script>
