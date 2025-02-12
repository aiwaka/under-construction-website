<script>
  import ServiceIcon from "@components/ServiceIcon.svelte";
</script>

<section class="contact-section section-item">
  <h2 id="contact">Contact</h2>
  <span>お問い合わせはメールにてお願いいたします。</span>
  <table class="contact-table">
    <tbody>
      <tr>
        <th>Mail</th>
        <td>
          <a
            href="mailto:Kw.I.KU.2525@gmail.com?subject=%E3%81%8A%E5%95%8F%E3%81%84%E5%90%88%E3%82%8F%E3%81%9B（From Under-Construction Website）"
            target="_blank"
            rel="noopener noreferrer"
          >
            Kw.I.KU.2525@gmail.com
          </a>
        </td>
      </tr>
      <tr>
        <th>GitHub</th>
        <td>
          <a
            href="https://github.com/aiwaka"
            target="_blank"
            rel="noopener noreferrer"
          >
            @aiwaka
          </a>
        </td>
      </tr>
    </tbody>
  </table>
  <div class="contact-container">
    <a
      href="mailto:Kw.I.KU.2525@gmail.com?subject=%E3%81%8A%E5%95%8F%E3%81%84%E5%90%88%E3%82%8F%E3%81%9B（From Under-Construction）"
      target="_blank"
      rel="noopener noreferrer"
    >
      <div class="contact-item mail">
        <ServiceIcon name="gmail" size="large" />
        <span>Mail</span>
      </div>
    </a>
    <a
      href="https://github.com/aiwaka"
      target="_blank"
      rel="noopener noreferrer"
    >
      <div class="contact-item github">
        <ServiceIcon name="github" size="large" />
        <span>GitHub</span>
      </div>
    </a>
  </div>
</section>

<style>
  .contact-table {
    border-collapse: collapse;
    margin: 1rem 2rem;
  }
  .contact-table tr {
    border-top: 1px solid darkslateblue;
    border-bottom: 1px solid darkslateblue;
  }
  .contact-table th,
  td {
    text-align: left;
    padding: 1rem 2rem;
  }
  @media (max-width: 1024px) {
    .contact-table {
      margin: 1rem auto;
    }
    .contact-table th,
    td {
      padding: 1rem 0.4rem;
    }
  }

  .contact-container {
    display: flex;
    margin: 7rem auto;
    justify-content: center;
  }
  .contact-item {
    display: flex;
    margin: auto 2rem;
    flex-direction: column;
    align-items: center;
  }
</style>
