<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Personal Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            background-image: url('https://picsum.photos/id/296/1600/900');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            background-attachment: fixed; /* Background image fixed */
        }
        header {
            background-color: rgba(76, 175, 80, 0.8); /* Semi-transparent green */
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        section {
            padding: 2em;
            background-color: rgba(255, 255, 255, 0.9); /* Semi-transparent white */
            margin: 50px 0;
        }
        .content {
            max-width: 800px;
            margin: auto;
            background: rgba(255, 255, 255, 0.95); /* Semi-transparent white */
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .video-wrapper {
            display: flex;
            justify-content: center;
        }
        .map-wrapper {
            display: flex;
            justify-content: center; /* Center the map horizontally */
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            left: 0;
            right: 0;
            z-index: 1; /* Ensure footer is above background image */
        }
        .social-media {
            margin-top: 1em;
        }
        .social-media a {
            margin: 0 10px;
            text-decoration: none;
            color: #4CAF50;
        }
        .contact-form label {
            display: block;
            margin-top: 10px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        .contact-form button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>Selamat datang ke RF3World (Singapura)</h1>
    <nav>
        <ul>
            <li><a href="#home">Pengenalan</a></li>
            <li><a href="#about">Tentang Kami</a></li>
            <li><a href="#blog">Perkhidmatan Kami</a></li>
            <li><a href="#resources">Cari Kami</a></li>
            <li><a href="#contact">Hubungi Kami</a></li>
        </ul>
    </nav>
</header>

<section id="home">
    <div class="content">
        <h2>Pengenalan</h2>
        <p>Banyak yang menganggap menakluki sebuah gunung sangat menakutkan, namun yang lebih mencabar ialah menerima kelemahan kita dan mengambil tindakan yang diperlukan dengan berani. </p>
    </div>
</section>

<section id="about">
    <div class="content">
        <h2>Tentang Kami</h2>
        <p>Sering kali, kita merasa tidak berdaya disebabkan masalah kesihatan, komitmen kewangan, keadaan yang tidak dijangka, dan ketidakpastian hidup. Royalty Vitality ditubuhkan untuk menyediakan peluang bagi peningkatan diri dan pemberdayaan apabila hidup berubah. Misi kami adalah untuk menyokong individu dalam mengatasi cabaran ini dan membantu mereka mencapai kestabilan dan vitaliti.</p>
        <div class="video-wrapper">
            <iframe width="800" height="450" src="https://www.youtube.com/embed/Hy6j9o8FYb0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </div>
</section>

<section id="services">
    <div class="content">
        <h2>Perkhidmatan Kami</h2>
        <p>Program Sokongan Kesihatan: Pelan khusus untuk meningkatkan kesejahteraan fizikal dan mental.</p>
        <p> Panduan Kewangan: Nasihat pakar untuk mengurus dan memperbaiki kesihatan kewangan anda.</p>
        <p>Bimbingan Hidup: Bimbingan peribadi untuk membantu anda mengharungi cabaran hidup.</p>
        <p>Sokongan Komuniti: Rangkaian individu yang berpikiran sama menawarkan sokongan dan dorongan bersama.</p>
        <!-- Blog posts will go here -->
    </div>
</section>

<section id="resources">
    <div class="content">
        <h2>Cari Kami</h2>
        <div class="map-wrapper">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3988.5665570290416!2d103.80240337412135!3d1.4352697612970964!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31da13004b2d554b%3A0x78829c3624d9246d!2sPrimz%20BizHub!5e0!3m2!1sen!2ssg!4v1718863480362!5m2!1sen!2ssg" 
                width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </div>
        <p>HP Kami: +65 8774 1661.</p>
        <!-- Resource links will go here -->
    </div>
</section>

<section id="contact">
    <div class="content">
        <h2>Sama ada anda mempunyai soalan, memerlukan maklumat lanjut, atau bersedia untuk menyertai, hubungi kami. Kami ingin mendengar daripada anda!</h2>
        <form action="https://formspree.io/f/xvoeeqzv" method="POST" class="contact-form">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>
            <label for="whatsApp">WhatsApp (Sertakan kod negara anda, eg: +65 1234 5678)</label>
            <input type="text" id="whatsApp" name="whatsApp" required>
            <label for="message">Message</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <button type="submit">Send</button>
        </form>
    </div>
</section>

<footer>
    <p>&copy; 2024 Royalty Vitality. All rights reserved.</p>
    <div class="social-media">
        <a href="#">Facebook</a>
        <a href="#">Twitter</a>
        <a href="#">LinkedIn</a>
    </div>
</footer>
</body>
</html>
