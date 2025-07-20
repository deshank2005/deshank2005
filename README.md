## Hi there 👋
<style>
  body {
    background: linear-gradient(to right, #1e1e1e, #3e3e3e);
    color: white;
    font-family: 'Segoe UI', sans-serif;
  }

  .film-header {
    background: #ff3c3c;
    padding: 20px;
    text-align: center;
    font-size: 30px;
    font-weight: bold;
  }

  .film-nav {
    display: flex;
    justify-content: center;
    gap: 15px;
    background: #222;
    padding: 10px;
    flex-wrap: wrap;
  }

  .film-nav a {
    color: white;
    text-decoration: none;
    padding: 8px 15px;
    background: #444;
    border-radius: 5px;
  }

  .film-nav a:hover {
    background-color: #ff3c3c;
  }

  .movie-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
    padding: 20px;
  }

  .movie-card {
    background-color: #2a2a2a;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 0 10px black;
    text-align: center;
  }

  .movie-card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
  }

  .movie-card h3 {
    padding: 10px;
  }

  .watch-button {
    background: #ff3c3c;
    color: white;
    padding: 10px;
    margin: 0 15px 15px;
    display: inline-block;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }

  .watch-button:hover {
    background: #ff5f5f;
  }

  .film-footer {
    background: #111;
    color: #ccc;
    text-align: center;
    padding: 15px;
    font-size: 14px;
  }
</style>

<div class="film-header">🎬 Free Sinhala Subtitle Films</div>

<div class="film-nav">
  <a href="#">Home</a>
  <a href="#">Action</a>
  <a href="#">Romance</a>
  <a href="#">Comedy</a>
  <a href="#">New</a>
</div>

<div class="movie-grid">
  <div class="movie-card">
    <img src="https://placehold.co/300x180/png?text=Movie+1" alt="Movie 1">
    <h3>Movie Title 1</h3>
    <a class="watch-button" href="https://youtube.com" target="_blank">▶ Watch Now</a>
  </div>
  <div class="movie-card">
    <img src="https://placehold.co/300x180/png?text=Movie+2" alt="Movie 2">
    <h3>Movie Title 2</h3>
    <a class="watch-button" href="https://youtube.com" target="_blank">▶ Watch Now</a>
  </div>
  <div class="movie-card">
    <img src="https://placehold.co/300x180/png?text=Movie+3" alt="Movie 3">
    <h3>Movie Title 3</h3>
    <a class="watch-button" href="https://youtube.com" target="_blank">▶ Watch Now</a>
  </div>
</div>

<div class="film-footer">© 2025 FreeMovieSite | Powered by Blogger | Designed by Deshan</div>


