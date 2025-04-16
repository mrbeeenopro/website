<template>
  <div class="grid grid-cols-2 gap-4">
    <ProjectCard
      title="Docker-optimaze"
      description="Simple, fast docker java for pteroactyl"
      cover="/assets/images/projects/pee.jpg"
      href="https://github.com/mrbeeenopro/dockeroptimaze"
    />
    <ProjectCard
      title="lemem forum"
      description="a forum by lemem team"
      cover="/assets/images/projects/blueprint.jpg"
      href="https://forum.mangovn.xyz"
    />
    <ProjectCard
      title="mchbee.cloud"
      description="private hosting in Vietnam "
      cover="/assets/images/projects/logo.jpg"
      href="https://mchbee.cloud"
    />
    <ProjectCard
      title="idk :3"
      description="this page powerd by emma"
      cover="/assets/images/projects/emma.jpg"
      href="https://prpl.wtf/"
    />
  </div>
</template>

<script>
import ProjectCard from "~/components/ProjectCard.vue";

export default {
  components: {
    ProjectCard,
  },
};
</script>
