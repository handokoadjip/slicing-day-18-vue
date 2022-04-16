<template>
  <JumbotronComponent />
  <JourneyComponent />
  <ExperienceComponent />
  <UpcomingClassComponent />
  <SubscribeComponent />
</template>

<script>
import JumbotronComponent from "@/components/JumbotronComponent.vue";
import JourneyComponent from "@/components/JourneyComponent.vue";
import ExperienceComponent from "@/components/ExperienceComponent.vue";
import UpcomingClassComponent from "@/components/UpcomingClassComponent.vue";
import SubscribeComponent from "@/components/SubscribeComponent.vue";

export default {
  name: "HomePage",
  components: {
    JumbotronComponent,
    JourneyComponent,
    ExperienceComponent,
    UpcomingClassComponent,
    SubscribeComponent,
  },
  mounted() {
    document.title = "Afrian Hanafi | Makers Workshop"
  }
}
</script>
