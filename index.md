<style>
  .nexus-page {
    font-family: "Inter", "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    color: #0f1720;
    margin: 0;
    padding: 0;
  }

  .nexus-grid {
    display: grid;
    grid-template-columns: 46% 54%;
    min-height: 100vh;
    background: #d3d4d5;
  }

  .left-column {
    background: #285f7f;
    color: #fff;
  }

  .hero-title {
    background: #1f4f6b;
    font-weight: 700;
    font-size: clamp(1.8rem, 2.9vw, 3rem);
    line-height: 1.22;
    letter-spacing: 0.02rem;
    padding: 3.2rem 3.4rem;
  }

  .content {
    padding: 2.2rem 3.4rem 2.8rem;
    font-size: 1.12rem;
    line-height: 1.65;
  }

  .content h2 {
    margin: 0 0 0.85rem;
    font-size: 1.9rem;
    font-weight: 700;
  }

  .content h3 {
    margin: 2rem 0 0.7rem;
    font-size: 1.7rem;
    font-weight: 700;
  }

  .right-column {
    display: flex;
    flex-direction: column;
    background: #d3d4d5;
  }

  .image-panel {
    min-height: 62vh;
    background:
      linear-gradient(rgba(23, 39, 35, 0.2), rgba(23, 39, 35, 0.2)),
      radial-gradient(circle at 60% 30%, #647785 0%, #485865 25%, #2e3d45 48%, #1d272b 100%);
    position: relative;
    overflow: hidden;
  }

  .image-panel::after {
    content: "";
    position: absolute;
    inset: 48% 0 0;
    background: linear-gradient(180deg, rgba(186, 193, 200, 0.5), rgba(146, 153, 157, 0.8));
    clip-path: polygon(0 42%, 20% 38%, 32% 47%, 44% 38%, 61% 45%, 74% 40%, 100% 46%, 100% 100%, 0 100%);
  }

  .facts {
    padding: 2rem 2.4rem 2.6rem;
    font-size: 1.1rem;
    line-height: 1.55;
    color: #121212;
  }

  .facts p {
    margin: 0 0 0.8rem;
  }

  .facts strong {
    font-weight: 800;
  }

  @media (max-width: 960px) {
    .nexus-grid {
      grid-template-columns: 1fr;
    }

    .image-panel {
      min-height: 38vh;
    }

    .hero-title,
    .content,
    .facts {
      padding-left: 1.4rem;
      padding-right: 1.4rem;
    }
  }
</style>

<div class="nexus-page">
  <section class="nexus-grid">
    <div class="left-column">
      <div class="hero-title">
        Natur og kraft: Press, påvirkninger og muligheter for utvikling av vannkraft i vernede vassdrag (NEXUS)
      </div>

      <div class="content">
        <h2>Bakgrunn:</h2>
        <p>
          Energiomstilling for å møte klimautfordringene og forpliktelsene til å stoppe tap av biologisk mangfold
          som fastsatt i naturavtalen er på kollisjonskurs. Forslag om å vurdere ny vannkraft i vernede vassdrag
          generer kontroverser. Debatten har imidlertid begrenset grunnlag i etablert kunnskap. Gjennom å utvikle
          en verktøykasse for å evaluere mulige konsekvenser av ny kraft i vernede vassdrag skal NEXUS bidra til å
          flytte debatten fra en debatt om kunnskapsgrunnlaget til en debatt om prioriteringer mellom ulike samfunnsmål.
        </p>

        <h3>Mål for prosjektet:</h3>
        <p>
          Utvikle scenarier som vil gir mulighet for å vurdere effekten av ny vannkraftproduksjon i vernede
          vassdrag i et påvirkningsrom langs aksene (i) energiproduksjon, (ii) påvirkning på biologisk mangfold,
          (iii) fordeler og ulemper for andre brukerinteresser.
        </p>
      </div>
    </div>

    <div class="right-column">
      <div class="image-panel" aria-label="Illustrasjon av vassdrag og natur"></div>
      <div class="facts">
        <p><strong>Ansvarlig organisasjon:</strong> Norges Teknisk Naturvitenskapelige Universitet <strong>Prosjektleder:</strong> Anders Gravbrøt Finstad</p>
        <p><strong>Partnere:</strong> Sintef Energi AS, Artsdatabanken, Verdal Kommune</p>
        <p><strong>Prosjektperiode:</strong> 2025-2028</p>
        <p><strong>Prosjekttype:</strong> Kompetansebyggende prosjekt for næringslivet</p>
        <p><strong>Offentlig finansiering:</strong> 11.3 mill. kroner</p>
        <p><strong>Nettside:</strong> ntnu.no/xxx</p>
        <p><strong>Prosjektnummer:</strong> 353075</p>
      </div>
    </div>
  </section>
</div>
