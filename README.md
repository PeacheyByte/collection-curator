<!-- App Logo -->
<p align="center">
  <img src="Sellventory-icon-final.png" alt="Sellventory logo" width="120">
</p>
<div style="display:flex; justify-content:center; align-items:center; gap:20px; flex-wrap:wrap; margin-top:20px;">

  <!-- Google Play -->
  <a href="https://play.google.com/store/apps/details?id=com.peachbyte.sellventory" target="_blank" rel="noopener">
    <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png"
         alt="Get it on Google Play" style="height:60px; width:auto;"/>
  </a>

  <!-- Windows download -->
  <a class="sv-btn" href="/path/to/windows-download.zip"
     style="display:inline-block; padding:12px 18px; border:1px solid #155d9a; border-radius:10px; text-decoration:none;
            font-weight:700; background:#1e6bb8; color:#fff;">
     DOWNLOAD FOR WINDOWS
  </a>

</div>


<!-- === Sellventory navigation buttons === -->
<style>
  .sv-nav{
    display:flex;justify-content:center;gap:14px;flex-wrap:wrap;margin:26px 0
  }
  .sv-btn{
    display:inline-block;
    padding:12px 18px;
    border:1px solid #155d9a;
    border-radius:10px;
    text-decoration:none;
    font-weight:700;
    font-size:0.98rem;
    background:#1e6bb8;
    color:#fff;
    line-height:1.2;
    letter-spacing:.2px;
    box-shadow:0 2px 6px rgba(0,0,0,.15);
  }
  .sv-btn:visited{color:#fff}
  .sv-btn:hover{background:#155d9a;border-color:#0f4c86;box-shadow:0 3px 10px rgba(0,0,0,.2)}
  .sv-btn:focus{outline:3px solid #99c2ff;outline-offset:2px}

  /* keep buttons readable even after they've been visited */
.sv-nav .sv-btn:link,
.sv-nav .sv-btn:visited {
  color: #fff !important;
  background: #1e6bb8 !important;
  border-color: #155d9a !important;
}

  @media (prefers-color-scheme: dark){
    .sv-btn{background:#2a7bd6;border-color:#1c5ea6}
    .sv-btn:hover{background:#1f6ac0}
  }
</style>

<div class="sv-nav">
  <a class="sv-btn" href="/">← Peacheybyte Studios</a>
  <a class="sv-btn" href="{{ site.baseurl }}/user-guide/">User Guide</a>
  <a class="sv-btn" href="{{ site.baseurl }}/changelog/">Change Log</a>
  <a class="sv-btn" href="{{ site.baseurl }}/issues/">Known Issues</a>
  <a class="sv-btn" href="{{ site.baseurl }}/roadmap/">Planned Additions</a>
</div>
<!-- === end navigation buttons === -->



<!-- Body -->
Inventory made simple — for buyers, sellers, and collectors.

The Collection Curator is built for buyers, sellers, and collectors who want a clear, reliable way to keep track of their items. Whether you are reselling at markets, managing an online store, or curating a personal collection, The Collection Curator helps you stay organised without relying on complicated tools or cloud accounts.

With The Collection Curator  you can:

- **Record your items with photos and details.** Each entry can store a picture, purchase price, notes, and custom tags, giving you a complete view of what you own or intend to sell.

- **Organise by tags and locations.** Group items by category, storage box, shelf, or any system that suits your workflow, so nothing gets lost or overlooked.

- **Track purchases and sales.** Know exactly when and where you bought an item, what you paid, and the final selling price. This makes it easy to calculate your profit and spot trends in what moves quickly.

- **Generate reports and exports.** Create spreadsheets for analysis, backup your records, or share summaries when you need them. Exporting is straightforward and works the same way across Android and the Companion desktop app.

- **Use the Windows & Linux Companion.** Work with your database on a bigger screen, making editing, browsing, and reporting faster and more comfortable.

Everything is stored locally — no logins, no hidden syncs, and no internet required. Sellventory is designed to be lightweight, dependable, and under your control.



---
{% include footer.html %}
