<template lang="">
  <nav
    id="sidebarMenu"
    class="col-md-3 col-lg-2 d-md-block bg-light sidebar collapse"
  >
    <div class="position-sticky pt-3">
      <ul class="nav flex-column">
        <li class="nav-item">
          <router-link to="/users" class="nav-link" active-class="active">
            Users
          </router-link>
        </li>
      </ul>
    </div>
  </nav>
</template>
<script>
export default {};
</script>
