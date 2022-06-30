<script>
  const input = {
    sm: 400,
    md: 600,
    lg: 1200,
  }

  //remove the comment bellow and see the error
  //export default input

  const {
    sm,
    md,
    lg,
  }  = $$restProps
</script>

{JSON.stringify({
    sm,
    md,
    lg,
})} &lt;== comes from "$$props"