/* BACKGROUNDS */
const backgrounds = ["bg1.jpg", "bg2.jpg", "bg3.jpg"];
let bgIndex = 0;
const bg = document.getElementById("background");

function changeBackground() {
    bg.style.backgroundImage = `url('${backgrounds[bgIndex]}')`;
    bgIndex = (bgIndex + 1) % backgrounds.length;
}
changeBackground();
setInterval(changeBackground, 6000);

/* TEXTES */
const texts = [
    "Kartoshka • Le DarkRP Sans Joueurs Cancer",
    "Le RP avant tout",
    "Respect du FearRP obligatoire",
    "Freekill = sanction",
    "Staff actif et à l’écoute",
    "Rejoignez notre Discord",
    "N'oubliez pas de DL les css content et autres..."
];

let textIndex = 0;
const textDiv = document.getElementById("loading-text");

setInterval(() => {
    textDiv.textContent = texts[textIndex];
    textIndex = (textIndex + 1) % texts.length;
}, 3000);

/* MUSIQUE AUTOMATIQUE */
const music = document.getElementById("music");

// Essayer de jouer automatiquement, boucle activée via autoplay
music.play().catch(() => {
    console.log("Musique non autorisée à jouer automatiquement (dans GMod, ça dépend du client).");
});
