# minecraft-fishing-js

Minecraft Fishing Simulator Example

if (character === 'steve') {
// STEVE: Cod 70%, Salmon 20%, Tropical 5%, Puffer 5%
let randNum = Math.random();
if (randNum < 0.7) {
numCod++;
numCodSpan.innerHTML = numCod;
resultImg.src = 'img/Raw-Cod.png';
} else if (randNum < 0.9) {
numSalmon++;
numSalmonSpan.innerHTML = numSalmon;
resultImg.src = 'img/Raw-Salmon.png';
} else if (randNum < 0.95) {
numTropical++;
numTropicalSpan.innerHTML = numTropical;
resultImg.src = 'img/Tropical-Fish.png';
} else {
numPuffer++;
numPufferSpan.innerHTML = numPuffer;
resultImg.src = 'img/Pufferfish.png';
}
} else if (character === 'alex') {
// ALEX: Cod 10%, Salmon 10%, Tropical 30%, Puffer 50%
let randNum = Math.random();
if (randNum < 0.1) {
numCod++;
numCodSpan.innerHTML = numCod;
resultImg.src = 'img/Raw-Cod.png';
} else if (randNum < 0.2) {
numSalmon++;
numSalmonSpan.innerHTML = numSalmon;
resultImg.src = 'img/Raw-Salmon.png';
} else if (randNum < 0.5) {
numTropical++;
numTropicalSpan.innerHTML = numTropical;
resultImg.src = 'img/Tropical-Fish.png';
} else {
numPuffer++;
numPufferSpan.innerHTML = numPuffer;
resultImg.src = 'img/Pufferfish.png';
}
}

catchFish("steve", 0.7, 0.9, 0.95);
catchFish("alex", 0.1, 0.2, 0.5);
catchFish("villager", 0.25, 0.5, 0.75);
