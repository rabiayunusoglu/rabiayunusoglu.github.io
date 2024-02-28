<script setup>
import ExampleCard from "../Components/ExampleCard.vue";
import MaterialBadge from "../../../components/MaterialBadge.vue";

// images
import imgSigninCover from "@/assets/img/signin-cover.png";
</script>
<template>
  <section class="py-5">
    <div class="container">
      <div class="row">
        <div class="row text-center my-sm-5 mt-5">
          <div class="col-lg-6 mx-auto">
            <MaterialBadge color="success" class="mb-3"
              >Hello World</MaterialBadge
            >
            <h2 class="">With our coded pages</h2>
            <p class="lead">
              The easiest way to get started is to use one of our <br />
              pre-built example pages.
            </p>
          </div>
        </div>
      </div>
    </div>
   
  </section>
</template>
