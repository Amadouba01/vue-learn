<template>
    <div>
        <TopNav />
        <GoogleForm/>
        <GoogleFooter/>
    </div>
</template>

<script>
    import GoogleForm from '@/components/GoogleForm.vue';
    import TopNav from '@/components/TopNav.vue';
    import GoogleFooter from '@/components/GoogleFooter.vue';
    export default {
        components:{
            GoogleForm,
            TopNav,
            GoogleFooter
        }
    }
</script>

<style scoped>

</style>