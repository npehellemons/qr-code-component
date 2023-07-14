<script>

</script>

<div class="container">
   <div class="container__card">
        <div class="container__card-qrcode">
            <img src="/image-qr-code.png" alt="">
        </div>
        <div class="container__card-text">
            <p>Improve your front-end<br> skills by building projects</p>
            <small>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</small>
        </div>
   </div>
</div>

<footer>
    <p>
        Challenge by <a href="https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H" target="_blank"> Frontendmentor.io</a>
    </p>
</footer>

<style>
    .container {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        height: 100vh;
    }

    .container__card {
        width: 290px;
            height: 450px;
        padding: 15px;
        background: #fff;
        border-radius: 15px;
        box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
    }

    @media (max-width: 375px) {
        .container__card {
            width: 300px;
            height: 450px;
        }
    }

    .container__card-qrcode img {
        width: 100%;
        height: auto;
        border-radius: 10px;
    }

    .container__card-text {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        text-align: center;
    }

    .container__card-text p {
        color: hsl(218, 44%, 22%);
        font-size: 20px;
        font-family: 'Outfit', sans-serif;
        font-weight: 700;
    }

    .container__card-text small {
        color: hsl(220, 15%, 55%);
        font-family: 'Outfit', sans-serif;
        font-weight: 400;
        font-size: 15px;
        padding-inline: 25px;
    }

    footer {
        position: absolute;
        bottom: 0;
        left: 0;
        right: 0;
        text-align: center;
        padding: 15px;
        font-size: 15px;
        color: hsl(220, 15%, 55%);
        font-family: 'Outfit', sans-serif;
    }

    footer a {
        color: hsl(218, 44%, 22%);
        text-decoration: none;
    }
</style>