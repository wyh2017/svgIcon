 <template>
  <span class="i-icon">
  <svg class="i-icon" :width="size" :height="size" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg"><path :fill="fill" d="M224 106.667h576q32 0 32 32t-32 32H224q-32 0-32-32t32-32zM544 280.363v576q0 32-32 32t-32-32v-576q0-32 32-32t32 32zM489.387 251.563a32 32 0 0 1 41.642-3.072l3.584 3.072 232.32 232.32a32 32 0 0 1-41.685 48.341l-3.584-3.115L512 319.445 302.336 529.11a32 32 0 0 1-41.685 3.115l-3.584-3.115a32 32 0 0 1-3.072-41.642l3.072-3.584 232.32-232.32z" /></svg>
  </span>
</template>
<script>
export default {
  name: "close",
  props:{
    size:{
      type:String, 
      default:'1em'
    },
    fill:{
      type:String,
      default:'red'
    }
  }
};
</script>