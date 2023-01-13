<script lang="ts">
  import "../site.css";
</script>

<main class="wrapper">
  <nav class="navigation">
    <section class="container">
      <a class="navigation-title">
        <h1 class="title">Title</h1>
      </a>
      <ul class="navigation-list float-right">
        <li class="navigation-item">
          <a class="navigation-link" href="#popover-grid">Docs</a>
        </li>
        <li class="navigation-item">
          <a class="navigation-link" href="#popover-grid">Docs</a>
        </li>
      </ul>
    </section>
  </nav>

  <header class="header">
    <section class="container">
      <h1>Welcome to SvelteKit</h1>
      <p>
        Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
      </p>
    </section>
  </header>
  <div class="content blue">
    <section class="container">Text here</section>
  </div>

  <div class="content">
    <section class="container">Text here</section>
  </div>

  <div class="content orange">
    <section class="container">Text here</section>
  </div>
</main>

<style>
  .content {
    padding-top: 5rem;
    padding-bottom: 5rem;
    background-color: var(--bg);
  }

  .content.orange {
    background-color: var(--orange);
    color: white;
  }

  .content.green {
    background-color: var(--green);
    color: white;
  }

  .content.blue {
    background-color: var(--blue);
    color: white;
  }
  .content.yellow {
    background-color: var(--yellow);
    color: white;
  }
  .content.pink {
    background-color: var(--pink);
    color: white;
  }

  .content.inverted {
    background-color: var(--inverted);
    color: white;
  }
</style>
