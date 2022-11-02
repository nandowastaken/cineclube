<template>
    <div class="infoMeetings">
        <AboutUs/>
        <HowWeWork/>
        <NextMeeting/>
    </div>
    

</template>

<script>
    import { defineComponent } from 'vue';
    import AboutUs from '../components/AboutUs';
    import HowWeWork from '../components/HowWeWork';
    import NextMeeting from '../components/NextMeeting';

    export default defineComponent({
        name: 'InfoMeetings',
        components: {
            AboutUs,
            HowWeWork,
            NextMeeting
        }
    })
</script>

<style>

    @media only screen and (min-width: 1280px) {
        .infoMeetings {
            display: flex;
            flex-direction: row;
        }
    }

</style>