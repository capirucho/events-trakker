<template>
  <div>
    <h1>Events Listings</h1>
    <EventCard />
    <BaseIcon />
  </div>
</template>
<script>
import EventCard from '@/components/EventCard.vue';

export default {
  components: {
    EventCard
  }
};
</script>
