
<script>
export default {
  name: "Footer",
};
</script>

<style>
.footer {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  -webkit-box-shadow: 0px -3px 7px 0px rgba(50, 50, 50, 0.53);
  -moz-box-shadow: 0px -3px 7px 0px rgba(50, 50, 50, 0.53);
  box-shadow: 0px -3px 7px 0px rgba(50, 50, 50, 0.53);
  height: 50px;
  background-color: white;
}

.items {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: row;
}

.item {
  margin: 10px 50px;
}

.image {
  width: 30px;
  height: 30px;
}
</style>