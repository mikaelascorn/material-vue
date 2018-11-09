<template>
  <div id="app">
    <div class="md-layout md-gutter md-dense">
       <div class="md-layout-item">
        <md-field>
          <label for="question1">Security Question</label>
          <md-select v-model="question1" name="question1" id="question1">
            <md-option value="1">Lorem ipsum dolor sit amet consectetur.</md-option>
            <md-option value="2">Lorem ipsum dolor sit amet consectetur.</md-option>
            <md-option value="3">Lorem ipsum dolor sit amet consectetur.</md-option>
            <md-option value="4">Lorem ipsum dolor sit amet consectetur.</md-option>
          </md-select>
        </md-field>
      </div>
    </div>
    <div class="md-layout md-gutter md-dense">
       <div class="md-layout-item">
        <md-field>
          <label for="question2">Security Question</label>
          <md-select v-model="question2" name="question2" id="question2">
            <md-option value="5">Lorem ipsum dolor sit amet consectetur.</md-option>
            <md-option value="6">Lorem ipsum dolor sit amet consectetur.</md-option>
            <md-option value="7">Lorem ipsum dolor sit amet consectetur.</md-option>
            <md-option value="8">Lorem ipsum dolor sit amet consectetur.</md-option>
          </md-select>
        </md-field>
      </div>
    </div>
  </div>

</template>

<script>

export default {
  name: 'App',
  
}
</script>

<style>
#app {
  margin: 50px;
}
.md-list-item-content {
  background-color: white;  
  font-family: 'Lato';
  line-height: 24px;
  letter-spacing: 0.14px;
}
.md-theme-default {
  min-width: fit-content;
  overflow: none;
}
</style>
