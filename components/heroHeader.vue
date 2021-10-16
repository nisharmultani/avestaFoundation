<template>
  <div>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      style="text-shadow: 1px 1px 2px #333"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <b-carousel-slide>
        <template #img>
          <img
            class="d-block img-fluid w-100"
            width="1024"
            src="https://picsum.photos/1024/480/?image=52"
            alt="image slot"
            caption="First slide"
          />
        </template>
      </b-carousel-slide>
      <b-carousel-slide>
        <template #img>
          <img
            caption="second slide"
            class="d-block img-fluid w-100"
            width="1024"
            src="https://picsum.photos/1024/480/?image=54"
            alt="image slot"
          />
        </template>
      </b-carousel-slide>
      <b-carousel-slide>
        <template #img>
          <img
            caption="thred slide"
            class="d-block img-fluid w-100"
            width="1024"
            src="https://picsum.photos/1024/480/?image=58"
            alt="image slot"
          />
        </template>
      </b-carousel-slide>
      <b-carousel-slide>
        <template #img>
          <img
            caption="fourth slide"
            class="d-block img-fluid w-100"
            width="1024"
            src="https://picsum.photos/1024/480/?image=55"
            alt="image slot"
          />
        </template>
      </b-carousel-slide>
      <b-carousel-slide>
        <template #img>
          <img
            caption="fift slide"
            class="d-block img-fluid w-100"
            width="1024"
            src="https://picsum.photos/1024/480/?image=58"
            alt="image slot"
          />
        </template>
      </b-carousel-slide>
      <b-carousel-slide>
        <template #img>
          <img
            caption="fift slide"
            class="d-block img-fluid w-100"
            width="1024"
            src="https://picsum.photos/1024/480/?image=58"
            alt="image slot"
          />
        </template>
      </b-carousel-slide>
    </b-carousel>
  </div>
</template>

<script>
export default {
  data() {
    return {
      slide: 0,
      sliding: null,
    };
  },
  methods: {
    onSlideStart(slide) {
      this.sliding = true;
    },
    onSlideEnd(slide) {
      this.sliding = false;
    },
  },
};
</script>

<style scoped>
img {
  height: 530px;
}
</style>