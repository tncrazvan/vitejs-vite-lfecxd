<script lang="ts">
  import Test from './lib/Test.svelte'
  import test from './lib/test' //it works with ".ts" files
</script>


<Test sm=100 md=200 lg=400/>
<br/>
{JSON.stringify(test)} &lt;== comes from "test.ts"