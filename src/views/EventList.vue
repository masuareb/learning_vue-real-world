<template>
  <div>
    <h1>Events Listing</h1>
    <EventCard/>
    <p>
      <router-link :to="{ name: 'event-show', params: { id: '1' }}">First Event</router-link>
    </p>
  </div>

</template>

<script>
import EventCard from "@/components/EventCard";
export default {
  components: {
    EventCard
  }
}
</script>
