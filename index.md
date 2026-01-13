---
layout: default
---
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>
/* This ensures the text inside the header stays aligned with your cards */
.page-header > * {
  max-width: 1100px; /* Match the max-width of your research cards */
  margin-left: auto;
  margin-right: auto;
  padding: 0 20px;
}
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
    font-family: "Futura", "Trebuchet MS", Arial, sans-serif !important;
    font-weight: 700;
    color: #ffffff !important;
    margin-bottom: 0 !important;
    font-size: 1.75rem;
    letter-spacing: 0.5px;
    font-style: normal !important;
  }

  /* Shared Card Logic */
  .research-card, .paper-card {
    display: flex;
    flex-direction: column;
    height: 100%; 
    min-height: 280px; 
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    border-radius: 8px;
    overflow: hidden;
    position: relative; /* Essential for stretched-link */
    text-decoration: none !important; /* Removes underline from whole card */
  }

  /* Vertical & Horizontal Centering for Row 1 */
  .research-card .card-body {
    flex: 1 1 auto;
    display: flex;
    flex-direction: column;
    justify-content: center; 
    align-items: center;     
    text-align: center;
    padding: 20px !important;
  }

  .research-card {
    border: 1px solid rgba(255,255,255,0.2) !important;
    cursor: pointer;
  }

  .research-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 12px 24px rgba(0, 51, 102, 0.4) !important;
    filter: brightness(1.1);
  }

  .research-card .card-title { 
    font-family: "Futura", "Trebuchet MS", Arial, sans-serif !important;
    font-size: 1.35rem; 
    font-weight: bold;
    color: #ffffff; 
    margin-bottom: 10px;
  }

  .btn-borderless {
    font-weight: 700;
    font-size: 1rem;
    color: #ffffff !important; 
  }

  /* Paper Card Logic (Row 2) */
  .paper-card { height: 100%; display: flex; flex-direction: column; border: 1px solid #dee2e6 !important; background: #fff; cursor: pointer; }
  .paper-card:hover { transform: translateY(-8px); box-shadow: 0 12px 24px rgba(0,0,0,0.1) !important; }
  
  .paper-image-container {
    height: 180px;
    aspect-ratio: 4 / 3; 
    overflow: hidden;
    background: #fff;
    display: flex;
    align-items: center;
    justify-content: center;
    border-bottom: 1px solid #eee;
    padding: 10px;
  }

  .paper-img {
    max-width: 100% !important;
    max-height: 100% !important;
    object-fit: contain;
    display: block;
    transition: transform 0.5s ease;
  }

  .paper-card:hover .paper-img { transform: scale(1.1); }

  /* Four Shades of Transparent Blue */
  .shade-1 { background-color: rgba(0, 82, 155, 0.75) !important; }
  .shade-2 { background-color: rgba(5, 93, 175, 0.75) !important; }
  .shade-3 { background-color: rgba(3, 59, 115, 0.8) !important; }
  .shade-4 { background-color: rgba(0, 38, 76, 0.85) !important; }

  .paper-link-text { color: #003366 !important; font-weight: 600; text-decoration: none; font-size: 0.9rem; }
  
  /* Resources Styles */
  .resources-section { margin-top: 50px; padding: 40px 0; border-top: 1px solid #dee2e6; }
  .resource-heading { font-weight: 700; color: #003366; font-size: 1.5rem; margin-bottom: 20px; }
  .resource-link-list { list-style: none; padding-left: 0; }
  .resource-link-list a { color: #003366; text-decoration: none; font-weight: 500; }
  .btn-outline-nd { border: 1px solid #003366; color: #003366; padding: 4px 12px; border-radius: 4px; font-weight: 600; text-decoration: none; display: inline-flex; align-items: center; }
  .btn-outline-nd:hover { background: #003366; color: #fff !important; }
</style>

<div class="full-width-research">
  <div class="title-box-container">
    <h2 class="research-section-title">Schneider Group Research Areas</h2>
  </div>

  <div class="container-fluid">
    <div class="row px-5 justify-content-center">
      
      <div class="col-md-3 mb-4">
        <a href="pages/research/zeolites_for_nox_reduction" class="card research-card shade-3 shadow-sm">
          <div class="card-body">
            <h3 class="card-title">Zeolites for NOx Reduction</h3>
            <span class="btn-borderless">Explore →</span>
          </div>
        </a>
      </div>

      <div class="col-md-3 mb-4">
        <a href="pages/research/catalysis_at_metal_surfaces" class="card research-card shade-2 shadow-sm">
          <div class="card-body">
            <h3 class="card-title">Catalysis at Metal Surfaces</h3>
            <span class="btn-borderless">Explore →</span>
          </div>
        </a>
      </div>

      <div class="col-md-3 mb-4">
        <a href="pages/research/catalysis_for_shale_gas" class="card research-card shade-3 shadow-sm">
          <div class="card-body">
            <h3 class="card-title">Catalysis for Shale Gas</h3>
            <span class="btn-borderless">Explore →</span>
          </div>
        </a>
      </div>

      <div class="col-md-3 mb-4">
        <a href="pages/research/plasma_enabled_catalysis" class="card research-card shade-2 shadow-sm">
          <div class="card-body">
            <h3 class="card-title">Plasma-enabled Catalysis</h3>
            <span class="btn-borderless">Explore →</span>
          </div>
        </a>
      </div>

    </div>

    <div class="row px-5 justify-content-center mt-2">
      <div class="col-md-3 mb-4">
        <div class="card paper-card text-center">
          <div class="paper-image-container"><a href="https://pubs.acs.org/doi/full/10.1021/acs.energyfuels.5c02308" target="_blank" rel="noopener noreferrer">
          <img src="group_data/home_photos/N2O_NOx_Raghav_2025.jpg" class="paper-img">
        </a></div>
          <div class="card-body p-3">
            <a href="https://pubs.acs.org/doi/full/10.1021/acs.energyfuels.5c02308" target="_blank" rel="noopener noreferrer" class="paper-link-text stretched-link">Read our recent Paper on Zeolite for NOx Reduction →</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-4">
        <div class="card paper-card text-center">
          <div class="paper-image-container"><a href="https://doi.org/10.1021/acscatal.4c05560" target="_blank" rel="noopener noreferrer">
          <img src="/group_data/research_images/Catalysis_at_Metal_surface_image.jpg" class="paper-img">
        </a></div>
          <div class="card-body p-3">
            <a href="https://doi.org/10.1021/acscatal.4c05560" target="_blank" rel="noopener noreferrer" class="paper-link-text stretched-link">Read our recent Paper on Catalysis at Metal Surface →</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-4">
        <div class="card paper-card text-center">
          <div class="paper-image-container"><a href="https://doi.org/10.1039/D4CY00684D" target="_blank" rel="noopener noreferrer">
          <img src="/group_data/research_images/N_Mehra_Catalysis_Shale_Gas.gif" class="paper-img">
        </a></div>
          <div class="card-body p-3">
            <a href="https://doi.org/10.1039/D4CY00684D" target="_blank" rel="noopener noreferrer" class="paper-link-text stretched-link">Read our recent Paper on Catalysis for Shale Gas →</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-4">
        <div class="card paper-card text-center">
          <div class="paper-image-container"><a href="https://doi.org/10.1016/j.cogsc.2024.100987" target="_blank" rel="noopener noreferrer">
          <img src="/group_data/home_photos/Plasma_Review_Denver_2025.jpg" class="paper-img">
        </a></div>
          <div class="card-body p-3">
            <a href="https://doi.org/10.1016/j.cogsc.2024.100987" target="_blank" rel="noopener noreferrer" class="paper-link-text stretched-link">Read our recent Review on Plasma-enabled Catalysis →</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
<div class="resources-section">
  <div class="container">
    <div class="row">
      
      <div class="col-md-6 mb-4 text-center text-md-left">
        <!-- <h4 class="resource-heading">Group Overview</h4> -->
        <p class="text-muted">Group Overview</p>
        <ul class="resource-link-list">
          <!-- <li>Browse our <a href="pages/group/bill_schneider">PI</a></li> -->
          <li>Meet our <a href="pages/group/bill_schneider">Principal Investigator</a> & <a href="pages/group/current_lab_members">Lab Members</a></li>
          <li>View <a href="pages/publications">Publications</a> & <a href="pages/group/group_photo">Photos</a></li>
          <li>Check <a href="pages/resources">Resources</a> & <a href="pages/group/available_positions">Available Positions</a></li>
        </ul>
        <div class="button-container">
          <a href="https://github.com/wfschneidergroup/wiki" class="btn-outline-nd">
            <i class="fab fa-github"></i> &nbsp;Group Wiki
          </a>
          <a href="https://github.com/wfschneidergroup" class="btn-outline-nd">
            <i class="fab fa-github"></i> &nbsp;Group GitHub
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
