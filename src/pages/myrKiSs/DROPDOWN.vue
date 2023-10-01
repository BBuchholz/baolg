<script setup>
import MyriadDropDown from '../../components/MyriadDropDown.vue'
import MyriadDropDownContent from '../../components/MyriadDropDownContent.vue'
</script>

<template>
  <div class="display">
    <p>Got It Working From Tutorial: </p>
    <a
      target="_blank"
      href="https://medium.com/@ronnow/dropdowns-in-vue-the-right-way-8ff9e8f36d4a"
    >Dropdowns in Vue: The Right Way</a>
  </div>
  <div class="display">
    <MyriadDropDown>
      <MyriadDropDownContent>
        <p>Action 1</p>
        <p>Action 2</p>
        <p>Action 3</p>
      </MyriadDropDownContent>
    </MyriadDropDown>
  </div>
</template>
