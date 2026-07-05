<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Links</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --bg-color: #0d1117;
            --card-bg: #161b22;
            --text-color: #e6edf3;
            --text-secondary: #8b949e;
            --btn-bg: #21262d;
            --btn-hover: #30363d;
            --btn-border: #30363d;
            --accent: #58a6ff;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            display: flex;
            justify-content: center;
            align-items: flex-start;
            min-height: 100vh;
            padding: 40px 20px;
        }

        .container {
            width: 100%;
            max-width: 580px;
            text-align: center;
        }

        /* Profile Section */
        .profile {
            margin-bottom: 32px;
        }

        .profile-img {
            width: 96px;
            height: 96px;
            border-radius: 50%;
            object-fit: cover;
            border: 2px solid var(--accent);
            margin-bottom: 16px;
        }

        .name {
            font-size: 1.25rem;
            font-weight: 600;
            margin-bottom: 8px;
        }

        .bio {
            font-size: 0.95rem;
            color: var(--text-secondary);
            line-height: 1.5;
            max-width: 400px;
            margin: 0 auto;
        }

        /* Links Section */
        .links-wrapper {
            display: flex;
            flex-direction: column;
            gap: 16px;
            margin-bottom: 32px;
        }

        .link-card {
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: var(--btn-bg);
            border: 1px solid var(--btn-border);
            color: var(--text-color);
            text-decoration: none;
            padding: 16px;
            border-radius: 12px;
            font-size: 1rem;
            font-weight: 500;
            transition: transform 0.2s ease, background-color 0.2s ease, border-color 0.2s ease;
            position: relative;
        }

        .link-card:hover {
            background-color: var(--btn-hover);
            border-color: var(--accent);
            transform: translateY(-2px);
        }

        .link-card i {
            position: absolute;
            left: 20px;
            font-size: 1.2rem;
        }

        /* Social Icons Row */
        .socials {
            display: flex;
            justify-content: center;
            gap: 24px;
            margin-top: 16px;
        }

        .social-icon {
            color: var(--text-secondary);
            font-size: 1.5rem;
            transition: color 0.2s ease, transform 0.2s ease;
        }

        .social-icon:hover {
            color: var(--accent);
            transform: scale(1.1);
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="profile">
            <img class="profile-img" src="https://via.placeholder.com/150" alt="Profile Picture">
            <h1 class="name">Your Name</h1>
            <p class="bio">A brief catchphrase or short bio about who you are and what you do.</p>
        </div>

        <div class="links-wrapper">
            
            <a href="https://youtube.com" target="_blank" class="link-card">
                <i class="fab fa-youtube"></i> YouTube Channel
            </a>

            <a href="https://twitch.tv" target="_blank" class="link-card">
                <i class="fab fa-twitch"></i> Live Stream
            </a>

            <a href="https://github.com" target="_blank" class="link-card">
                <i class="fab fa-github"></i> GitHub Projects
            </a>

            <a href="https://linkedin.com" target="_blank" class="link-card">
                <i class="fab fa-linkedin"></i> Professional Profile
            </a>
            
        </div>

        <div class="socials">
            <a href="https://twitter.com" target="_blank" class="social-icon"><i class="fab fa-x-twitter"></i></a>
            <a href="https://instagram.com" target="_blank" class="social-icon"><i class="fab fa-instagram"></i></a>
            <a href="mailto:your-email@example.com" class="social-icon"><i class="fas fa-envelope"></i></a>
        </div>
    </div>

</body>
</html>

