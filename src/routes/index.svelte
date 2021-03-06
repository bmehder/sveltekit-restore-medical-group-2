<script>
  import Section from '$lib/Section.svelte'
  import Grid from '$lib/Grid.svelte'
  import Flex from '$lib/Flex.svelte'
  import Button from '$lib/Button.svelte'
  import CTA from '$lib/CTA.svelte'
  import Parallax from '$lib/Parallax.svelte'
</script>

<svelte:head>
  <meta
    name="description"
    content="Restore Medical Group has developed an insurance backed protocol for treating recalcitrant wounds that prove difficult to heal using conventional wound care methods."
  />
  <title>Restore Medical Group | Golden, CO</title>

  <script async src="https://www.googletagmanager.com/gtag/js?id=UA-185413763-1"></script>
  <script>
    window.dataLayer = window.dataLayer || []
    function gtag() {
      dataLayer.push(arguments)
    }
    gtag('js', new Date())

    gtag('config', 'UA-185413763-1')
  </script>
</svelte:head>

<main>
  <Section boxed>
    <img
      style="width: 100%;"
      src="/images/restore-medical-group-hero.jpg"
      alt="Header - Restore Medical Group"
    />
  </Section>

  <Section background="white" margin="-5px auto 0" padding="2em 2em 0" boxed>
    <h3>Welcome to a revolution in chronic wound care.</h3>
    <Grid columns="1fr 1fr" gap="2em">
      <article>
        <p>
          Welcome to the
          <strong>Restore Medical Group</strong>
          Wound Care division - a truly unique health care practice. Restore Medical Group has developed
          an insurance backed protocol for treating recalcitrant wounds that prove difficult to heal
          using conventional wound care methods.
        </p>

        <p>
          Our treatment protocol incorporates a combination of therapies including our exclusively
          sourced amnio products that rapidly promote healing in wound areas.
        </p>

        <p>Our approach can provide either in-clinic or on-location care options.</p>

        <p>
          <strong>Most insurance accepted, including Medicare Part B</strong>
        </p>
      </article>
      <figure>
        <img
          class="styled"
          src="/images/wound-care-restore-medical-group.jpg"
          alt="Wound Care - Restore Medical Group"
        />
      </figure>
    </Grid>
  </Section>

  <Section boxed background="white" padding="2em">
    <hr />
  </Section>

  <Section background="white" padding="1em 2em" boxed>
    <h4>Identifying Patients</h4>
    <Grid columns="1fr 1fr" gap="2em">
      <div>
        <p>
          When evaluating patients for this protocol please consider the following before
          recommending care.
        </p>
        <figure>
          <img
            src="/images/qualified-patients.jpg"
            alt="Qualified Patients - Restore Medical Group"
          />
        </figure>
      </div>
      <article>
        <p>When evaluating patients referral please consider the following contraindications:</p>
        <ul>
          <li>infected wound,</li>
          <li>active cancer treatment,</li>
          <li>and/or immunosuppressive treatment.</li>
        </ul>

        <h5>Pre-Assessment</h5>
        <p>
          Restore Medical will conduct assessment and amnio products preauthorization on all
          patients prior to treatment to ensure the protocol is applicable and insurance is
          confirmed for the treatment.
        </p>

        <h5>Location</h5>
        <p>
          No need to drive, we will come to you! Our flexible mobile service is available if
          transportation and mobility is a problem. We bill your insurance for the visit so there is
          no cash fee involved. Additionally, we have multiple clinic locations available for
          evaluations and treatments if you'd prefer.
        </p>
      </article>
    </Grid>
  </Section>

  <Section boxed background="white" padding="2em">
    <hr />
  </Section>

  <Section background="white" padding="0.5em 2em 3em" boxed>
    <div style="text-align:center;">
      <h4>Testimonials</h4>
      <blockquote>
        "Restore Medical Group was the last chance for me."
        <cite>-Maxine (Patient)</cite>
      </blockquote>
      <p>Check out the testimonials from previous patients.</p>
      <Button background="dodgerblue" url="/testimonials" color="white" rounded shadow uppercase
        >Watch The Videos</Button
      >
    </div>
  </Section>

  <Section boxed background="url(images/snow.jpg) center center/cover" height="500px">
    <Parallax speed="0.1">
      <Flex align="start" gap="2em">
        <CTA
          heading="We travel to you!"
          subtitle="To schedule an on-site patient evaluation appointment, please call (720) 678-9868."
          href="tel:7206789868"
          buttonText="Call Today!"
          src="/images/transportation-restore-medical-group.jpg"
        />
      </Flex>
    </Parallax>
  </Section>
</main>

<style>
  .styled {
    width: 100%;
    border-radius: 4px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.24);
  }
  h3 {
    margin-bottom: 1.5rem;
    text-align: center;
  }
  hr {
    border-top: 1px solid #eee;
  }
  blockquote {
    display: inline-block;
    padding: 1.5rem;
    font-style: italic;
    font-size: 1.5rem;
  }
  cite {
    display: block;
    margin-top: 1rem;
    font-size: 1.2rem;
  }
</style>
