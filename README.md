# movie-explorer
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Movie Explorer - Star Wars: Revenge of the Sith</title>
  <style>
    /* Basic Reset and Body Styles */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #000;
      color: #fff;
      line-height: 1.6;
    }
    
    a {
      text-decoration: none;
      color: #fff;
    }
    
    /* Header and Navigation */
    header {
      background-color: #111;
      padding: 20px;
      text-align: center;
    }
    
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    
    nav {
      margin-top: 10px;
    }
    
    nav ul {
      list-style: none;
      padding: 0;
      display: inline-block;
    }
    
    nav ul li {
      display: inline;
      margin: 0 10px;
    }
    
    /* Hero Section */
    .hero {
      position: relative;
      background-image: url('https://via.placeholder.com/1200x600.png?text=Revenge+of+the+Sith');
      background-size: cover;
      background-position: center;
      height: 60vh;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    
    .hero h2 {
      background-color: rgba(0, 0, 0, 0.5);
      padding: 20px;
      font-size: 2em;
    }
    
    /* Content Sections */
    .content {
      padding: 20px;
      background-color: #222;
      margin-bottom: 10px;
    }
    
    .content h2 {
      margin-top: 0;
    }
    
    /* Responsive iframe for trailer */
    .responsive-iframe {
      position: relative;
      overflow: hidden;
      width: 100%;
      padding-top: 56.25%; /* 16:9 Aspect Ratio */
    }
    
    .responsive-iframe iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
    }
    
    /* Footer */
    footer {
      background-color: #111;
      padding: 10px;
      text-align: center;
    }
  </style>
</head>
<body>
  <!-- Header with Navigation -->
  <header>
    <h1>Movie Explorer</h1>
    <nav>
      <ul>
        <li><a href="#overview">Overview</a></li>
        <li><a href="#cast">Cast</a></li>
        <li><a href="#trailer">Trailer</a></li>
        <li><a href="#gallery">Gallery</a></li>
      </ul>
    </nav>
  </header>
  
  <!-- Hero Section -->
  <section class="hero">
    <h2>Star Wars: Revenge of the Sith</h2>
  </section>
  
  <!-- Overview Section -->
  <section class="content" id="overview">
    <h2>Overview</h2>
    <p>
      <em>Star Wars: Revenge of the Sith</em> is the third installment of the Star Wars prequel trilogy.
      This epic film chronicles the tragic fall of Anakin Skywalker as he turns to the dark side, becoming Darth Vader,
      and marks the beginning of the Galactic Empire. It bridges the events between the prequel and original trilogies,
      showcasing intense action, political intrigue, and dramatic character transformations.
    </p>
  </section>
  
  <!-- Cast Section -->
  <section class="content" id="cast">
    <h2>Main Cast</h2>
    <ul>
      <li>Hayden Christensen as Anakin Skywalker / Darth Vader</li>
      <li>Ewan McGregor as Obi-Wan Kenobi</li>
      <li>Natalie Portman as Padmé Amidala</li>
      <li>Samuel L. Jackson as Mace Windu</li>
      <li>Christopher Lee as Count Dooku</li>
    </ul>
  </section>
  
  <!-- Trailer Section -->
  <section class="content" id="trailer">
    <h2>Trailer</h2>
    <div class="responsive-iframe">
      <iframe src="https://www.youtube.com/embed/5UnjrG_N8hU" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </section>
  
  <!-- Gallery Section -->
  <section class="content" id="gallery">
    <h2>Gallery</h2>
    <p>Image gallery coming soon! Replace this text with your favorite stills from the movie.</p>
  </section>
  
  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Movie Explorer</p>
  </footer>
</body>
</html>

