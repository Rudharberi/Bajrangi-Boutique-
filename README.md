# Bajrangi-Boutique-
Official website of Bajrangi Boutique showcasing designs, products and services 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Bajrangi Boutique</title>
    <style>
        /* Global Styles */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            background: #fff9f5;
            color: #5a3e36;
        }
        header {
            background-color: #d9c8b4;
            padding: 20px;
            text-align: center;
            border-bottom: 2px solid #ba9672;
        }
        header h1 {
            margin: 0;
            font-size: 2.8rem;
            font-weight: 700;
            font-family: 'Georgia', serif;
            letter-spacing: 2px;
            color: #4a2e1b;
        }
        header p {
            margin: 5px 0 10px;
            font-size: 1.1rem;
            font-style: italic;
            color: #6d5c4e;
        }
        .contact-info {
            font-size: 1rem;
            background-color: #e7d9ca;
            padding: 10px 0;
            border-top: 1px solid #ba9672;
            border-bottom: 1px solid #ba9672;
        }
        .contact-info a {
            color: #7a4b24;
            text-decoration: none;
            font-weight: bold;
        }
        main {
            max-width: 1000px;
            margin: 20px auto;
            padding: 0 15px;
        }
        section.description {
            background: #f7ece3;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 1px 2px 8px rgb(186 150 114 / 0.5);
            margin-bottom: 30px;
            text-align: center;
            font-size: 1.2rem;
            line-height: 1.6;
        }
        section.gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
            gap: 15px;
        }
        .gallery-item {
            position: relative;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 0 10px rgb(186 150 114 / 0.4);
            transition: transform 0.3s ease;
            background: white;
        }
        .gallery-item:hover {
            transform: scale(1.03);
        }
        .gallery-item img {
            width: 100%;
            height: auto;
            display: block;
        }
        .gallery-item .caption {
            padding: 10px;
            font-size: 1rem;
            text-align: center;
            color: #60432f;
        }
        footer {
            text-align: center;
            padding: 15px;
            background-color: #d9c8b4;
            border-top: 2px solid #ba9672;
            font-size: 0.9rem;
            color: #4a2e1b;
        }
        /* Responsive */
        @media (max-width: 600px) {
            header h1 {
                font-size: 2rem;
            }
            section.description {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Bajrangi Boutique By Ricky Dhillon</h1>
        <p>All Type Thread Handwork Embroidery & Fashion Design</p>
    </header>

    <div class="contact-info">
        Order Now via WhatsApp: <a href="https://wa.me/918221983894" target="_blank">+91 82219 83894</a><br />
        Location: Dahola Dis...
    </div>

    <main>
        <section class="description">
            <p>Welcome to Bajrangi Boutique, where craftsmanship meets elegance. We specialize in exquisite thread handwork embroidery, tailored fashion pieces, and customized designs that reflect traditional artistry with a contemporary touch. Explore our collection and discover the beauty of handcrafted fashion.</p>
        </section>

        <section class="gallery" aria-label="Product gallery">
            <!-- Gallery Image Items -->
            <article class="gallery-item">
                <img src="https://instagram.fdel1-1.fna.fbcdn.net/v/t51.2885-15/3212x2985/314007462_1260364528768845_8495660303754569004_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=8ae9d6&_nc_ohc=xxb_-E4v3NsAX-UHVfm&_nc_ht=instagram.fdel1-1.fna.fbcdn.net&edm=ANo9K5cEAAAA&oh=00_AfDI1v3LambN1YKillMG8jklxuVgiwZf-5F25RO3q6JTdA&oe=6464E17E"
                     alt="Elegant thread handwork embroidery design on fabric" />
                <div class="caption">Elegant Thread Embroidery</div>
            </article>
            
            <article class="gallery-item">
                <img src="https://instagram.fdel1-1.fna.fbcdn.net/v/t51.2885-15/320317237_1776197099399917_8434683024987071006_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=8ae9d6&_nc_ohc=uHoFbnGsDbIAX9O3dcu&_nc_ht=instagram.fdel1-1.fna.fbcdn.net&edm=ANo9K5cEAAAA&oh=00_AfDmpTuQj7FhJ9Afvud8bpV7qG2wutPX6SGnvZg_n44-dw&oe=6464B319"
                     alt="Stylish black embroidered dress with floral border" />
                <div class="caption">Contemporary Embroidered Dress</div>
            </article>

            <article class="gallery-item">
                <img src="https://instagram.fdel1-1.fna.fbcdn.net/v/t51.2885-15/321072062_864523193285854_4655613218750619920_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=8ae9d6&_nc_ohc=q6LrWzLHSFkAX8c_rnR&_nc_ht=instagram.fdel1-1.fna.fbcdn.net&edm=ANo9K5cEAAAA&oh=00_AfBn8xv-WeAid-sYBn22BAyLjsm68BXs75x_y1AS3ZsiDQ&oe=6464B021"
                     alt="Elegant embroidered shawl worn by a fashion model" />
                <div class="caption">Elegant Shawls & Scarves</div>
            </article>

            <article class="gallery-item">
                <img src="https://instagram.fdel1-1.fna.fbcdn.net/v/t51.2885-15/320984869_1290657895650778_8436615871946981162_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=8ae9d6&_nc_ohc=zvElA03R4rkAX-tESzx&_nc_ht=instagram.fdel1-1.fna.fbcdn.net&edm=ANo9K5cEAAAA&oh=00_AfC2wGxG1filvzX02pWYKGQKGWqzSOBVA0P4YnzW2UVXyQ&oe=64649567"
                     alt="Custom embroidered wedding invitation" />
                <div class="caption">Custom Wedding Invitations</div>
            </article>

            <article class="gallery-item">
                <img src="https://instagram.fdel1-1.fna.fbcdn.net/v/t51.2885-15/321432590_570893829482692_3527518463692774908_n.jpg?_nc_cat=111&ccb=1-7&_nc_sid=8ae9d6&_nc_ohc=QMy4LpPeVuIAX9XURUO&_nc_ht=instagram.fdel1-1.fna.fbcdn.net&edm=ANo9K5cEAAAA&oh=00_AfDkcFz9hrFpM2N6JzKhmDqU57WZtQfgeGiP9OhkP2TN-w&oe=6464CFB1"
                     alt="Hand embroidery shoe design" />
                <div class="caption">Hand Embroidered Shoes</div>
            </article>

            <article class="gallery-item">
                <img src="https://instagram.fdel1-1.fna.fbcdn.net/v/t51.2885-15/321166649_854063727455500_5489373830340261056_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=8ae9d6&_nc_ohc=0kpSdT8N6xAAX_htL7h&_nc_ht=instagram.fdel1-1.fna.fbcdn.net&edm=ANo9K5cEAAAA&oh=00_AfC9Mj8r2k3-KMSpNj7XFST_CqtjyVzZ6x10GTXk5KJvCw&oe=6464E18B"
                     alt="Customer sharing a selfie with Bajrangi Boutique dress" />
                <div class="caption">Happy Customers</div>
            </article>
        </section>
    </main>

    <footer>
        &copy; 2024 Bajrangi Boutique | Fashion Designer Ricky Dhillon | All rights reserved.
    </footer>
</body>
</html>
