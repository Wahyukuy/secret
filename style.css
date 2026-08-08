const container = document.getElementById("love-container");

function createLove() {
    // Jangan membuat love ketika portrait
    if (window.innerHeight > window.innerWidth) {
        return;
    }

    const love = document.createElement("div");

    love.classList.add("love");
    love.innerHTML = "♥";

    // Posisi horizontal random
    love.style.left = Math.random() * 100 + "vw";

    // Ukuran random
    const size = Math.random() * 25 + 10;
    love.style.fontSize = size + "px";

    // Kecepatan random
    const duration = Math.random() * 4 + 3;
    love.style.animationDuration = duration + "s";

    // Warna pink
    const pinkColors = [
        "#ff1493",
        "#ff69b4",
        "#ff85c1",
        "#ff4fa3",
        "#ffb6c1",
        "#ff007f"
    ];

    const color =
        pinkColors[Math.floor(Math.random() * pinkColors.length)];

    love.style.color = color;

    // Glow
    love.style.filter =
        `drop-shadow(0 0 ${Math.random() * 8 + 3}px ${color})`;

    container.appendChild(love);

    // Hapus love setelah selesai
    setTimeout(() => {
        love.remove();
    }, duration * 1000 + 500);
}

// Hujan love terus-menerus
setInterval(createLove, 80);
