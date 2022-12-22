<style>

* {
    background-color: #000000;
    font: Inconsolata, monospace;
    color: white;
    text-shadow: 0 0 10px #C8C8C8;
    text-align: center;
}

body {
    font-family:. 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-image: radial-gradient(rgba(0, 150, 0, 0.75), black 90%);
    z-index: 10;
}

h1, h2 {
    color: white !important;
    text-shadow: 0 0 10px #C8C8C8;
}

@keyframes rotate {
    0% {
        transform: rotate(3deg);
    }
    100% {
        transform: rotate(-3deg);
    }
}
@keyframes gradientBackground {
    0% {
        background-position: 0% 50%;
    }
    50% {
        background-position: 100% 50%;
    }
    100% {
        background-position: 0% 50%;
    }
}
@keyframes fadeIn {
    0% {
        opacity: 0;
    }
    66% {
        opacity: 0;
    }
    100% {
        opacity: 1;
    }
}
.container {
    font-family:
        system-ui,
        -apple-system,
        'Segoe UI',
        Roboto,
        Helvetica,
        Arial,
        sans-serif,
        'Apple Color Emoji',
        'Segoe UI Emoji';
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin: 0;
    width: 100%;
    height: 400px;
    background: linear-gradient(-45deg, #fc5c7d, #6a82fb, #05dfd7);
    background-size: 600% 400%;
    animation: gradientBackground 10s ease infinite;
    border-radius: 10px;
    color: white;
    text-align: center;
}
h1 {
    font-size: 50px;
    line-height: 1.3;
    letter-spacing: 5px;
    text-transform: uppercase;
    text-shadow:
        0 1px 0 #efefef,
        0 2px 0 #efefef,
        0 3px 0 #efefef,
        0 4px 0 #efefef,
        0 12px 5px rgba(0, 0, 0, 0.1);
    animation: rotate ease-in-out 1s infinite alternate;
    background: -webkit-linear-gradient(transparent, transparent);
}
p {
    font-size: 20px;
    text-shadow: 0 1px 0 #efefef;
    background: -webkit-linear-gradient(transparent, transparent);
}

ul, li {
    padding: 0;
    margin: 0;
    text-align: center;
    background: -webkit-linear-gradient(transparent, transparent);
}

</style>


<div class="container">
    <h1>Taha Belkhiri</h1>
    <p>Welcome to my github profile!</p>
    <ul>
        <li>👋 Hi, I’m @belkhiritaha
        <li>👀 I’m interested in cybersecurity and web development
        <li>🌱 I’m currently enrolled in a Networks and Cybersecurity Engineering Degree
        <li>📫 How to reach me:
        <ul>
            <li>📧 Email: taha.belkhiri@etu.uca.fr
            <li>📱 Discord: Sorry Im Blind#0369
        </ul>
        <li>🌐 Website: perso.isima.fr/~tabelkhiri
    </ul>
</div>


<h1>📊 My Github Stats</h1>
<img src="https://github-readme-stats.vercel.app/api?username=belkhiritaha&show_icons=true&theme=radical" alt="belkhiritaha's github stats" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=belkhiritaha&layout=compact&theme=radical" alt="belkhiritaha's github stats" />