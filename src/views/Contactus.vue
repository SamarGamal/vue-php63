<template>
    <section>
        <Caption />
        <Cards />
    </section>
</template>

<script>
import Caption from '@/components/contactus/caption.vue'
import Cards from '@/components/contactus/cards.vue'

export default{
    name: "Contactus",
    components: {
        Caption,
        Cards
    }
}
</script>