<template>
<div>
       <li class="list-group-item">
            Server #{{ number }}
       </li>
</div>
</template>

<script>
export default {
    props: {
        number: 'integer'
    }
}

</script>