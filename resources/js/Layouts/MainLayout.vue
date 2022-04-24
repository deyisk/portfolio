<template>
<div class="main h-14 flex">
    <div class="main-left w-1/2">
    <span class="text-4xl">Deyis Karakas</span>
    </div>

    <div class="main-right grid w-1/2">
    <div>About Me</div>
    <div>Works</div>
    <div>Contact</div>
    <div>
        <a href="/resume-deyis.pdf">Resume</a>
    </div>
    </div>
    
</div>
<main>
    <slot>
    </slot>
</main>
</template>

<script>
import { defineComponent } from 'vue'
import { Head, Link } from '@inertiajs/inertia-vue3';

    export default defineComponent({
        components: {
            Head,
            Link,
            
        },
    })
</script>
