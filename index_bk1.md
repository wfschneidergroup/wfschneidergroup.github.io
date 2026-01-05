---
layout: default
---
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>
  /* --- RESEARCH SECTION STYLES --- */
  .full-width-research {
    margin-left: calc(-50vw + 50%);
    margin-right: calc(-50vw + 50%);
    width: 100vw;
    position: relative;
    left: 50%;
    margin-left: -50vw;
    padding-top: 2rem;
    padding-bottom: 3rem;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .title-box-container {
    background-color: #003366; 
    padding: 1rem 2.5rem;
    margin-bottom: 3.5rem;
    width: fit-content;
    border-radius: 4px;
    text-align: center;
    box-shadow: 0 4px 15px rgba(0,0,0,0.2);
  }

  .research-section-title {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif !important;
  font-weight: 700;
  color: #ffffff !important;
  margin-bottom: 0 !important;
  font-size: 1.75rem;
  letter-spacing: 0.5px;
  font-style: normal !important;
  }

  .research-card {
    transition: transform 0.3s ease, box-shadow 0.3s ease, background-color 0.3s ease;
    border: 1px solid rgba(255,255,255,0.2) !important;
    min-height: 220px;
    border-radius: 8px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    position: relative; 
    cursor: pointer;
  }
  .stretched-link::after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1;
  content: "";
}

  .research-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 12px 24px rgba(0, 51, 102, 0.3) !important;
    filter: brightness(1.1);
  }

  /* Four Shades of Transparent Blue */
  .shade-1 { background-color: rgba(0, 82, 155, 0.75) !important; }
  .shade-2 { background-color: rgba(5, 93, 175, 0.75) !important; }
  .shade-3 { background-color: rgba(3, 59, 115, 0.8) !important; }
  .shade-4 { background-color: rgba(0, 38, 76, 0.85) !important; }

  .research-card .card-title { 
    font-size: 1.35rem; 
    font-weight: bold;
    color: #ffffff; 
    margin-bottom: 15px;
  }
  
  .research-card .card-text { 
    font-size: 0.95rem; 
    line-height: 1.5;
    color: #ffffff; 
    opacity: 0.95;
    margin-bottom: 20px;
  }

  .btn-borderless {
    background: none !important;
    border: none !important;
    font-weight: 700;
    text-decoration: none;
    padding: 0;
    font-size: 1rem;
    color: #ffffff !important; 
    margin-left: auto;
    margin-right: auto;
    display: inline-block;
  }
  
  .btn-borderless:hover {
    text-decoration: underline;
  }

  /* --- RESOURCES SECTION STYLES --- */
  .resources-section {
    margin-top: 50px;
    padding: 40px 0;
    border-top: 1px solid #dee2e6;
  }

  .resource-heading {
    font-family: inherit;
    font-weight: 700;
    color: #003366;
    font-size: 1.5rem;
    margin-bottom: 20px;
    font-style: normal !important;
    letter-spacing: 0.5px;
  }

  .resource-link-list {
    list-style: none;
    padding-left: 0;
  }

  .resource-link-list li {
    margin-bottom: 10px;
    font-size: 1rem;
  }

  .resource-link-list a {
    color: #003366;
    text-decoration: none;
    transition: color 0.2s;
    font-weight: 500;
  }

  .resource-link-list a:hover {
    text-decoration: underline;
  }

  .button-container {
    display: flex;
    flex-wrap: wrap;
    gap: 15px; /* Spacing between Wiki and GitHub buttons */
    margin-top: 1.5rem;
  }

  .btn-outline-nd {
    border: 1px solid #003366;
    color: #003366;
    background: transparent;
    padding: 4px 12px;
    font-size: 0.85rem;
    border-radius: 4px;
    font-weight: 600;
    transition: all 0.3s;
    display: inline-flex;
    align-items: center;
    text-decoration: none;
  }

  .btn-outline-nd:hover {
    background: #003366;
    color: #fff !important;
    text-decoration: none;
  }

  .btn-outline-nd i {
    margin-right: 6px;
  }

  /* Responsive adjustment for resource headings */
  @media (max-width: 768px) {
    .button-container { justify-content: center; }
    .resources-section .text-md-left { text-align: center; }
  }
  /* --- PAPER CARD STYLES --- */
  .paper-card {
    border: 1px solid #dee2e6 !important;
    transition: all 0.3s ease;
    border-radius: 8px;
    overflow: hidden;
  }

  .paper-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.1) !important;
  }

  .paper-image-container {
    height: 180px; /* Fixed height for all thumbnails */
    overflow: hidden;
    background: #fff;
    display: flex;
    align-items: center;
    justify-content: center;
    border-bottom: 1px solid #eee;
  }

  .paper-img {
    width: 100%;
    height: 100%;
    object-fit: contain; /* Keeps the full research figure visible */
    padding: 10px;
  }

  .paper-link-text {
    color: #003366 !important; /* Matches your header blue */
    font-weight: 600;
    text-decoration: none;
    font-size: 0.9rem;
  }

  .paper-link-text:hover {
    text-decoration: underline;
  }
</style>


<div class="full-width-research">
  <div class="title-box-container">
    <h2 class="research-section-title">Schneider Group Research Areas</h2>
  </div>

  <div class="container-fluid">
    <div class="row px-5 justify-content-center">
      
      <div class="col-md-3 mb-4">
        <div class="card h-100 research-card shade-3 shadow-sm text-center">
          <div class="card-body d-flex flex-column justify-content-center align-items-center">
            <h3 class="card-title">Zeolites for NOx Reduction</h3>
            <!-- <p class="card-text">Molecular speciation in zeolites for emissions control.</p> -->
            <a href="pages/research/zeolites_for_nox_reduction" class="btn-borderless stretched-link mt-auto">Explore →</a>
          </div>
        </div>
      </div>

      <div class="col-md-3 mb-4">
        <div class="card h-100 research-card shade-2 shadow-sm text-center">
          <div class="card-body d-flex flex-column justify-content-center align-items-center">
            <h3 class="card-title">Catalysis at Metal Surfaces</h3>
            <!-- <p class="card-text">Decoding reaction mechanisms on metal surfaces.</p> -->
            <a href="pages/research/catalysis_at_metal_surfaces" class="btn-borderless stretched-link mt-auto">Explore →</a>
          </div>
        </div>
      </div>

      <div class="col-md-3 mb-4">
        <div class="card h-100 research-card shade-3 shadow-sm text-center">
          <div class="card-body d-flex flex-column justify-content-center align-items-center">
            <h3 class="card-title">Catalysis for Shale Gas</h3>
            <!-- <p class="card-text">Catalytic strategies for light alkane conversion.</p> -->
            <a href="pages/research/catalysis_for_shale_gas" class="btn-borderless stretched-link mt-auto">Explore →</a>
          </div>
        </div>
      </div>

      <div class="col-md-3 mb-4">
        <div class="card h-100 research-card shade-2 shadow-sm text-center">
          <div class="card-body d-flex flex-column justify-content-center align-items-center">
            <h3 class="card-title"> Plasma-enabled Catalysis </h3>
            <!-- <p class="card-text">Non-thermal pathways for sustainable manufacturing.</p> -->
            <a href="pages/research/plasma_enabled_catalysis" class="btn-borderless stretched-link mt-auto">Explore →</a>
          </div>
        </div>
      </div>

    </div>
  </div>
  <div class="row px-5 justify-content-center mt-4">
    
    <div class="col-md-3 mb-4">
      <div class="card h-100 paper-card">
        <div class="paper-image-container">
          <img src="group_data/home_photos/N2O_NOx_Raghav_2025.jpg" class="card-img-top paper-img" alt="Zeolite Paper">
        </div>
        <div class="card-body text-center p-3">
          <a href="https://pubs.acs.org/doi/full/10.1021/acs.energyfuels.5c02308" class="paper-link-text">Read our recent Zeolite for NOx Reduction Paper →</a>
        </div>
      </div>
    </div>

    <div class="col-md-3 mb-4">
      <div class="card h-100 paper-card">
        <div class="paper-image-container">
          <img src="/group_data/research_images/Catalysis_at_Metal_surface_image.jpg" class="card-img-top paper-img" alt="Metal Surfaces Paper">
        </div>
        <div class="card-body text-center p-3">
          <a href="https://doi.org/10.1021/acscatal.4c05560" class="paper-link-text">Read our recent Catalysis at Metal Surface Paper →</a>
        </div>
      </div>
    </div>

    <div class="col-md-3 mb-4">
      <div class="card h-100 paper-card">
        <div class="paper-image-container">
          <img src="/group_data/research_images/N_Mehra_Catalysis_Shale_Gas.gif" class="card-img-top paper-img" alt="Shale Gas Paper">
        </div>
        <div class="card-body text-center p-3">
          <a href="https://doi.org/10.1039/D4CY00684D" class="paper-link-text">Read our recent Catalysis of Shale Gas Paper →</a>
        </div>
      </div>
    </div>

    <div class="col-md-3 mb-4">
      <div class="card h-100 paper-card">
        <div class="paper-image-container">
          <img src="/group_data/home_photos/Plasma_Review_Denver_2025.jpg" class="card-img-top paper-img" alt="Plasma Paper">
        </div>
        <div class="card-body text-center p-3">
          <a href="https://doi.org/10.1016/j.cogsc.2024.100987" class="paper-link-text">Read our recent Review on Plasma-enabled Catalysis →</a>
        </div>
      </div>
    </div>

  </div>
</div>

<div class="resources-section">
  <div class="container">
    <div class="row">
      
      <div class="col-md-6 mb-4 text-center text-md-left">
        <h4 class="resource-heading">Group Overview</h4>
        <ul class="resource-link-list">
          <li>Browse our <a href="pages/group/bill_schneider">Principal Investigator</a></li>
          <li>Meet our <a href="pages/group/current_lab_members">Lab Members</a></li>
          <li>View <a href="pages/publications">Publications</a> & <a href="pages/group/group_photo">Photos</a></li>
          <li>Check <a href="pages/resources">Resources</a> & <a href="pages/group/available_positions">Available Positions</a></li>
        </ul>
        <div class="button-container">
          <a href="https://github.com/wfschneidergroup/wiki" class="btn-outline-nd">
            <i class="fab fa-github"></i> Group Wiki
          </a>
          <a href="https://github.com/wfschneidergroup" class="btn-outline-nd">
            <i class="fab fa-github"></i> Group GitHub
          </a>
        </div>
      </div>

      <div class="col-md-6 mb-4 text-center text-md-left">
        <!-- <h4 class="resource-heading">University Affiliations</h4> -->
        <p class="text-muted">For more information on chemical engineering and chemistry at Notre Dame, visit:</p>
        <ul class="resource-link-list">
          <li><a href="https://cbe.nd.edu/" target="_blank">Department of Chemical and Biomolecular Engineering</a></li>
          <li><a href="https://chemistry.nd.edu/" target="_blank">Department of Chemistry & Biochemistry</a></li>
        </ul>
        <div class="button-container">
        <a href="https://twitter.com/profwschneider" target="_blank" class="btn-outline-nd">
          @profwschneider&nbsp;&nbsp;
          <img src="group_data/people_photos/twitter_logo.jpg" 
               alt="Twitter Logo" 
               style="height: 14px; width: auto; margin-right: 8px; vertical-align: middle;">
         </a>

        <a href="https://www.linkedin.com/in/williamfschneider/" target="_blank" class="btn-outline-nd">
          @williamfschneider&nbsp;
          <img src="group_data/people_photos/LinkedIn_logo_initials.png" 
               alt="LinkedIn Logo" 
               style="height: 14px; width: auto; margin-right: 8px; vertical-align: middle;">
         </a>
         </div>
      </div>

    </div>
  </div>
</div>
