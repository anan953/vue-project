<template>
  <aside
    class="left-sidebar"
    :class="
      Sidebar_drawer ? `show-sidebar bg-${SidebarColor}` : `bg-${SidebarColor}`
    "
  >
    <div class="scrlbar">
      <ul class="nav flex-column mb-0">
        <template v-for="(route, i) in routes">
          <!---Single Menu -->
          <li class="nav-item" :key="i" v-if="!route.childern && !route.header">
            <router-link :to="`${route.to}`" class="nav-link d-flex">
              <i :class="route.icon"></i>
            </router-link>
          </li>
        </template>
      </ul>
    </div>
  </aside>
</template>

<script>
import { mapState } from "vuex";
import SidebarData from "./SidebarData";

export default {
  name: "VerticalSidebar",
  data: () => ({
    initialShow: true,
    routes: SidebarData,
  }),
  computed: {
    ...mapState(["logoColor", "Sidebar_drawer", "SidebarColor"]),
    check() {
      return console.log(this.$router.history.current);
    },
  },
  methods: {
    showMobileSidebar() {
      this.$store.commit("SET_SIDEBAR_DRAWER", false);
    },
  },
};
</script>

<style>
</style>