<header>
<a id="header-logo-anchor" href="/">
  <picture id="header-logo-pictureset">
    <source srcset="/favicon.png" media="(max-width: 600px)" />
    <source
      srcset="/svelther-logo_dark.png"
      media="(prefers-color-scheme: light)"
    />
    <source
      srcset="/svelther-logo_light.png"
      media="(prefers-color-scheme: dark)"
    />
    <img src="/svelther-logo_light.png" alt="Svelther icon" height="50" />
  </picture>
</a>
  <button class="header-button" aria-label="Search"><i class="fa-solid fa-magnifying-glass-location"></i></button>
  <input
    type="search"
    name="search-city"
    id="header-search"
    placeholder="Search by city"
    aria-label="Search by city"
  />
  <ul id="header-ul">
    <li>
      <a
        href="http://github.com/glovek08"
        aria-label="glovek08 Github"
        class="header-link"
        target="_blank"
        ><i class="fa-brands fa-github"></i>
      </a>
    </li>
  </ul>
</header>

<style>
  header {
    outline: 1px solid red;
    margin-top: 0;
    margin-bottom: auto;
    padding: 0 10px;
    width: 100%;
    max-width: 100dvw;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow-y: auto;
  }
  #header-logo-anchor {
    /* outline: 1px solid yellow; */
    margin-left: 5px;
    margin-right: auto;
    display: block;
    transition: 
      transform ease-in-out 300ms,
      filter ease-in-out 400ms;
    filter: grayscale(1);
  }
  #header-logo-anchor:hover {
    transform-origin: center;
    transform: scale(1.05);
    filter: grayscale(0);
  }
  #header-logo-pictureset {
    display: block;
  }
  #header-ul {
    /* outline: 1px solid white; */
    margin-left: auto;
    margin-right: 5px;
    margin-bottom: 5px;
    margin-top: 5px;
    max-width: 50%;
    padding: 0 5px;
    height: 100%;
    min-height: 50px;
    list-style: none;
    display: flex;
    align-items: center;
    justify-content: flex-end;
  }
  #header-ul li {
    /* outline: 1px solid red; */
    margin: 0;
    padding: 0;
    font-size: 2rem;
  }
  .header-link {
    cursor: pointer;
    transition: color ease-in-out 200ms;
    color: var(--font-primary);
  }
  .header-link:hover {
    color: var(--accent);
  }
  #header-search {
    border-radius: 20px;
    padding: 5px 10px;
  }
  .header-button {
    /* outline: 1px solid red; */
    background: none;
    color: var(--font-primary);
    border: none;
    font-size: 1.5rem;
    margin-right: 5px;
    position: relative;
    top: 2px;
    cursor: pointer;
    transform: scale(1);
    will-change: transform;
    transition:
      color 200ms ease-in-out,
      transform 100ms ease-in-out;
    backface-visibility: hidden;
  }
  .header-button:hover {
    transform-origin: center;
    color: var(--accent);
    transform: scale(1.3);
  }
  @media screen and (max-width: 800px) {
  /* Styles for small screens */
    
  }
</style>
