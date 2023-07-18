<style>
@keyframes shake {
  0% { transform: translate(0, 0); }
  10%, 30%, 50%, 70%, 90% { transform: translate(-5px, 0); }
  20%, 40%, 60%, 80% { transform: translate(5px, 0); }
  100% { transform: translate(0, 0); }
}

.shaking-image {
  animation: shake 1s infinite;
}
</style>

![Shaking Image](matrix.jpg){:class="shaking-image"}
