<template>
    <nav class="mt-6">
        <ul class="list-disc">
            <li>
                <Link class="text-blue-500 hover:underline" href="/">Home</Link>
            </li>
            <li>
                <Link class="text-blue-500 hover:underline" href="/about">About</Link>
            </li>
            <li>
                <Link class="text-blue-500 hover:underline" href="/contact">Contact</Link>
            </li>
            <li>
                <Link :data="{foo:'Bar'}" as="button" class="text-blue-500 hover:underline" href="/logout"
                      method="post">Log out
                </Link>
            </li>
        </ul>
    </nav>
</template>

<script>
export default {
    name: "Navbar"
}
</script>

<style scoped>

</style>
