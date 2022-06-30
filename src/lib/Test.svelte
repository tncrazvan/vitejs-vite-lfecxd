<script lang="ts">
  let someProps: {
    username?: string,
    age?: number,
    details?: {
      firstname?: string,
      lastname?: string
    }
  } = {
    username: 'test'
  }

  export { someProps }
</script>

{JSON.stringify(someProps)}