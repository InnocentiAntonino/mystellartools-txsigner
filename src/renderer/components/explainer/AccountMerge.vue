<template>
    <div>
        <table>
            <tr>
                <td><b>Destination</b></td>
                <td><span v-text="operation.destination"></span></td>
            </tr>
        </table>
    </div>
</template>

<script>
  export default {
    props: ['operation']
  }
</script>