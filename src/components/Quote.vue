<template>
  <div class="col-sm-6 col-md-4 col-lg-3 text-center">
<div class="panel panel-default">
<div class="panel-body quote">
    <slot></slot>
</div>
</div>
  </div>
</template>

<script>


export default {

}
</script>

<style>
.panel-body {
    font-family: cursive;
    font-size: 24px;
    color: #6e6e6e;
    border: 2px solid lightgray;
    border-radius: 5px;
    margin: 20px 2px;
}

.quote {
    cursor:pointer;
}

.quote:hover {
    background-color: #ffe2e2;
}


</style>
