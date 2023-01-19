<script setup>

    defineProps(['title', 'content', 'colorText'])
</script>
<template>
    <div class="card mt-3">
        <div class="card-body">
            <h4 class="card-title" :class="`text-${colorText}`"> 
                {{title}}
            </h4>
            <p>
                {{content}}
            </p>
        </div>
    </div>
</template>