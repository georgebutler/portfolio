<template>
  <div class="page-wrapper with-navbar">
    <nav class="navbar">
      <div class="navbar-content">
        <button class="btn btn-action" type="button">
          <i class="fa fa-bars" aria-hidden="true" />
          <span class="sr-only">Toggle sidebar</span>
        </button>
      </div>
    </nav>

    <div class="content-wrapper">
      <Tutorial />
      <div class="alert" role="alert">
        <h4 class="alert-heading">
          Default alert
        </h4>
        This is a default alert with some content and <a href="#" class="alert-link">a link</a>.
      </div>
      <div class="alert alert-primary" role="alert">
        <h4 class="alert-heading">
          Primary alert
        </h4>
        This is a primary alert with some content and <a href="#" class="alert-link">a link</a>.
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
