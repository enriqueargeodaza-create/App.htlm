# App.htlm. <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Social Alpha | App Hub</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>

    <header class="app-header">
        <div class="header-content">
            <div class="logo">ALPHA-X</div>
            <div class="search-box">
                <i class="fas fa-search"></i>
                <input type="text" placeholder="Explorar contenidos y canales...">
            </div>
            <div class="user-actions">
                <button class="btn-live"><i class="fas fa-broadcast-tower"></i> LIVE</button>
                <i class="fas fa-paper-plane nav-icon"></i> <i class="fas fa-bell nav-icon"></i>
                <img src="https://via.placeholder.com/35" alt="Perfil" class="avatar-min">
            </div>
        </div>
    </header>

    <div class="app-layout">
        <nav class="side-nav">
            <div class="nav-section">
                <h3>MENÚ</h3>
                <a href="App.html" class="nav-link active"><i class="fas fa-home"></i> Inicio</a>
                <a href="#" class="nav-link"><i class="fas fa-fire"></i> Tendencias</a>
                <a href="#" class="nav-link"><i class="fas fa-bookmark"></i> Guardados</a>
            </div>
            <div class="nav-section">
                <h3>MIS CANALES</h3>
                <div class="channel-item"><i class="fas fa-circle" style="color: #00ff00;"></i> Rumble Live</div>
                <div class="channel-item"><i class="fas fa-hashtag"></i> Tech_News</div>
                <div class="channel-item"><i class="fas fa-users"></i> Gerencia General</div>
            </div>
        </nav>

        <main class="app-feed">
            <div class="post-creator">
                <img src="https://via.placeholder.com/50" alt="User" class="avatar">
                <div class="input-group">
                    <textarea placeholder="¿Qué está pasando en el mundo?"></textarea>
                    <div class="toolbar">
                        <div class="tools">
                            <i class="far fa-image"></i>
                            <i class="fas fa-video"></i>
                            <i class="far fa-chart-bar"></i>
                        </div>
                        <button class="btn-main">Publicar</button>
                    </div>
                </div>
            </div>

            <article class="feed-post">
                <div class="post-info">
                    <strong>Enrique Argeo Daza</strong> <span class="handle">@gerencia • 2h</span>
                </div>
                <p class="post-text">Bienvenidos a la fase oficial de lanzamiento. La red social está operativa. 🚀</p>
                <div class="media-container">
                    <div class="video-overlay">
                        <i class="fas fa-play-circle"></i>
                    </div>
                    <img src="https://via.placeholder.com/800x450/1c2732/ffffff?text=Video+Streaming+Rumble+Style" alt="Video">
                </div>
                <div class="post-stats">
                    <span><i class="far fa-comment"></i> 128</span>
                    <span><i class="fas fa-retweet"></i> 450</span>
                    <span><i class="far fa-heart"></i> 2.4k</span>
                    <span><i class="fas fa-share-alt"></i></span>
                </div>
            </article>
        </main>

        <aside class="side-trends">
            <div class="trends-card">
                <h3>Qué está pasando</h3>
                <div class="trend-box">
                    <span>Tecnología • Tendencia</span>
                    <p>#SocialAlpha2026</p>
                    <span>10.5K posts</span>
                </div>
                <div class="trend-box">
                    <span>Política • Tendencia</span>
                    <p>#LibertadDigital</p>
                    <span>8,432 posts</span>
                </div>
            </div>
        </aside>
    </div>

</body>
</html>
