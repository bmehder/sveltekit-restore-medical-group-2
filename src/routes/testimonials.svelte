<script>
  import Section from '$lib/Section.svelte'
</script>

<svelte:head>
  <meta
    name="description"
    content="Watch video testimonials from patients who have been helped by Restore Medical Group."
  />
  <title>Restore Medical Group | Testimonials | Golden, CO</title>

  <script
    async
    src="https://www.googletagmanager.com/gtag/js?id=UA-185413763-1"></script>
  <script>
    window.dataLayer = window.dataLayer || []
    function gtag() {
      dataLayer.push(arguments)
    }
    gtag('js', new Date())

    gtag('config', 'UA-185413763-1')
  </script>
</svelte:head>

<Section background="white" padding="2em" boxed>
  <h3>Testimonials</h3>
  <div>
    <iframe
      src="https://player.vimeo.com/video/540318619?title=0&byline=0&portrait=0"
      frameborder="0"
      allow="autoplay; fullscreen; picture-in-picture"
      allowfullscreen
      title="Restore Osteo Testimonial Video"
    />
  </div>
  <p>
    Richard has wounds on both legs. In this video, he talks about his
    experience at Restore Medical Group, and we share some before and after
    pictures.
  </p>
</Section>

<Section background="white" padding="0 2em 4em" boxed>
  <div>
    <iframe
      src="https://player.vimeo.com/video/584160193?h=67a9d56dfe&title=0&byline=0"
      width="640"
      height="360"
      frameborder="0"
      allow="autoplay; fullscreen; picture-in-picture"
      allowfullscreen
      title="Maxine's Testimonial"
    />
  </div>
</Section>

<Section background="white" padding="0 2em 4em" boxed>
  <div>
    <iframe
      title="vimeo-player"
      src="https://player.vimeo.com/video/622656173?h=f802c0f0f3"
      width="640"
      height="360"
      frameborder="0"
      allowfullscreen
    />
  </div>
</Section>

<style>
  h3 {
    text-align: center;
  }
  div {
    padding-top: 56.25%;
    position: relative;
  }
  iframe {
    position: absolute;
    top: 0px;
    left: 0;
    width: 100%;
    height: 100%;
  }
  p {
    padding: 2em;
  }
</style>
