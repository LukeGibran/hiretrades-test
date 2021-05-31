<template>
  <section class="section section-one">
    <div class="container-fluid">
      <div class="main-content sectionOne">
        <div class="main-column">
          <div class="header-text">
            <h1>Australia's most trusted trades provider</h1>
          </div>
          <div class="form">
            <div class="form-wrapper">
              <div class="form-group">
                <label for="">What trade do you need?</label>
                <div class="relative-container">
                  <input
                    type="text"
                    class="form-control"
                    placeholder="e.g Plumber, Electricians"
                  />

                  <div class="icon">
                    <i class="bx bxs-purchase-tag"></i>
                  </div>
                </div>
              </div>
              <div class="form-group">
                <label for="">Postcode or Suburb</label>
                <div class="relative-container">
                  <input
                    type="text"
                    class="form-control"
                    placeholder="e.g Sydney"
                  />
                  <div class="icon">
                    <i class="bx bxs-map"></i>
                  </div>
                </div>
              </div>

              <button class="btn btn-secondary btn-large">Post a job</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "SectionOne",
};
</script>