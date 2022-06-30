<template>
    <main>
        <header>
            <Link href="/"> Home</Link>
            <Link href="/about">About</Link>
            <Link href="/contact">Contact</Link>
        </header>
        <article>
            <slot />
        </article>
        <h1 class="bg-gray-200">Hello Inertia World !!!</h1>
    </main>
</template>

<script>
import { Link } from "@inertiajs/inertia-vue3";

export default {
    components: {
        Link,
    },
};
</script>
