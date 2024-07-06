<script setup lang="ts">
import HomeItem from './HomeItem.vue'
import MeetupIcon from './icons/IconMeetup.vue'
import YouTubeIcon from './icons/IconYouTube.vue'
import SlackIcon from './icons/IconSlack.vue'
import PythonIcon from './icons/IconPython.vue'
</script>

<template>
  <HomeItem>
    <template #icon>
      <MeetupIcon />
    </template>
    <template #heading>Join Us</template>

    Join us twice a month for engaging talks, workshops, and delightful dinners! Check out our group
    on
    <a href="https://www.meetup.com/OrlandoPython/" target="_blank" rel="noopener">Meetup</a>
    for our upcoming virtual and in-person meetings.
  </HomeItem>

  <HomeItem>
    <template #icon>
      <YouTubeIcon />
    </template>
    <template #heading>Watch Us</template>

    Check out some of our past meetings on our
    <a
      href="https://www.youtube.com/channel/UCmkllD-uGD4J5wAzCWxF3qQ"
      target="_blank"
      rel="noopener"
      >YouTube channel</a
    >
    including talks and workshops.
  </HomeItem>

  <HomeItem>
    <template #icon>
      <SlackIcon />
    </template>
    <template #heading>Talk With Us</template>

    If you're in Orlando, join us in the
    <a href="https://orlandodevs.com/slack/" target="_blank" rel="noopener"
      >Orlando Devs Slack group</a
    >. We also have a
    <a href="https://www.meetup.com/orlandopython/discussions/" target="_blank" rel="noopener"
      >discussions page in Meetup</a
    >.
  </HomeItem>

  <HomeItem>
    <template #icon>
      <PythonIcon />
    </template>
    <template #heading>Support Us</template>

    Want to give a talk or find other ways to help support the group,
    <a href="mailto:orlando.python@gmail.com">email us</a>
    or reach out on any of the platforms above.
  </HomeItem>
</template>
