<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Static Website</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@glidejs/glide/dist/css/glide.core.min.css">
</head>
<body>
    <header>
        <h1>Welcome to Our Website</h1>
    </header>
    <section class="top-section">
        <h2>Top Section</h2>
        <img src="http://via.placeholder.com/2550x550" alt="Placeholder Image">
    </section>
    <section class="grid-section">
        <div class="grid-container">
            <img src="https://placeholderimage.dev/150" alt="Placeholder Image">
            <img src="https://placeholderimage.dev/150" alt="Placeholder Image">
            <img src="https://placeholderimage.dev/150" alt="Placeholder Image">
        </div>
    </section>
    <section class="flex-section">
        <div class="flex-container">
            <div class="flex-item">Item 1</div>
            <div class="flex-item">Item 2</div>
            <div class="flex-item">Item 3</div>
        </div>
    </section>
    <section class="carousel">
        <div class="glide">
            <div class="glide__track" data-glide-el="track">
                <ul class="glide__slides">
                    <li class="glide__slide"><img src="https://placeholderimage.dev/2550x550" alt="Placeholder Image"></li>
                    <li class="glide__slide"><img src="https://placeholderimage.dev/2550x550" alt="Placeholder Image"></li>
                    <li class="glide__slide"><img src="https://placeholderimage.dev/2550x550" alt="Placeholder Image"></li>
                </ul>
            </div>
            <div class="glide__arrows" data-glide-el="controls">
                <button class="glide__arrow glide__arrow--left" data-glide-dir="<">Prev</button>
                <button class="glide__arrow glide__arrow--right" data-glide-dir=">">Next</button>
            </div>
        </div>
    </section>
    <footer>
        <p>Footer Content</p>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/@glidejs/glide"></script>
    <script src="scripts.js"></script>
</body>
</html>
