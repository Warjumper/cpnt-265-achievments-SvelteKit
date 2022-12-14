<script>
  export let title = "Ninja Gaming"
</script>

<div class="title">
  <img class="logo" src="/joystick.png" alt="SNES controller">
  <h1>{title}</h1>
</div>

<style>
.title {
  display: flex;
}
.title img {
  display: inline-block;
  height: 40px;
  width: 40px;
  margin-top: 20px;
  padding-left: 20px;
  filter: invert(88%) sepia(18%) saturate(886%) hue-rotate(199deg) brightness(100%) contrast(90%)
} 
.title h1 {
  margin-left: 10px;
}
</style>