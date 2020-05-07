<header>
  <navbar type="dark">
    <a slot="brand" href="{{baseUrl}}/index.html" title="Home" class="navbar-brand">CS2030 AY19/20 Special Term</a>
    <dropdown text="Guides" class="nav-link">
      <li><a href="{{baseUrl}}/contents/guides/settingUpLabEnv.html" class="dropdown-item">Setting Up Lab Environment</a></li>
      <li><a href="{{baseUrl}}/contents/guides/settingUpJava.html" class="dropdown-item">Setting Up Java</a></li>
      <li><a href="{{baseUrl}}/contents/guides/settingUpVim.html" class="dropdown-item">Setting Up Vim</a></li>
      <li><a href="{{baseUrl}}/contents/guides/settingUpMacVim.html" class="dropdown-item">Setting Up MacVim</a></li>
      <li><a href="{{baseUrl}}/contents/guides/settingUpCheckstyle.html" class="dropdown-item">Setting Up Checkstyle</a></li>
    </dropdown>
    <dropdown text="Links" class="nav-link">
        <li><a href="https://www.comp.nus.edu.sg/~cs2030/style/" class="dropdown-item" target="_blank">CS2030 Java Style Guide</a></li>
        <li><a href="https://www.comp.nus.edu.sg/~cs2030/javadoc/" class="dropdown-item" target="_blank">CS2030 Javadoc Specification</a></li>
        <li><a href="https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html" class="dropdown-item" target="_blank">JDK 11 Download Link</a></li>
        <li><a href="https://codecrunch.comp.nus.edu.sg/" class="dropdown-item" target="_blank">Codecrunch</a></li>
        <li><a href="https://github.com/nus-cs2030/1920-st" class="dropdown-item" target="_blank">Github Repo</a></li>
        <li><a href="https://piazza.com/class/k9wlj14hz59682/" class="dropdown-item" target="_blank">Piazza Forum</a></li>
    </dropdown>
    <li slot="right">
      <form class="navbar-form">
        <searchbar :data="searchData" placeholder="Search" :on-hit="searchCallback" menu-align-right></searchbar>
      </form>
    </li>
  </navbar>
</header>
