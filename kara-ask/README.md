# KARA AŞK – Bölüm 1: İhanet (Épisode 1 : La Trahison)

A 40-second vertical (9:16) 3D soap opera with cockroach actors, rendered live in the browser with Three.js.

- `index.html`: the episode. Open it and press play. The score is generated in the browser with Web Audio. Dialogue is spoken through the browser's Turkish text-to-speech voice when the device has one. Subtitles are in French, with the Turkish line shown underneath.
- `index.html?capture`: the same scene without the player UI. It exposes `window.KARA.renderAt(t)` and `window.KARA.renderAudio()` so you can export frames.

## Shot list

| Time | Shot |
|---|---|
| 0–4 s | Istanbul skyline at night (Bosphorus bridge, mosques), title card |
| 4–9 s | Wide shot of the dinner; Ayşe's phone buzzes |
| 9–11 s | Close-up of the message: "Abim bunu asla öğrenmemeli… ♥" |
| 11–13.6 s | Mehmet narrows his eyes |
| 13.6–18.6 s | Mehmet stands and slams the table: "AYŞE! SEN BENİ NASIL ALDATIRSIN?!" |
| 18.6–23.6 s | Ayşe, crying: "MEHMET, SANA ANLATMAM GEREKEN BİR ŞEY VAR!" |
| 23.6–28.6 s | Mustafa stands: "ABİ... SANA BİR ŞEY SÖYLEMEM LAZIM." |
| 28.6–35.6 s | Heartbeat, three zooms in a row, extreme close-up of Mehmet's shocked face |
| 35.6–40 s | "Devam edecek… / À suivre" |

---

# KARA AŞK – Bölüm 2: Sır (Épisode 2 : Le Secret)

`bolum2.html`: a 70-second vertical episode, with an MP4 export in `kara-ask-bolum2.mp4`.

## Series character designs (keep these identical in future episodes)

| | Shell | Hair | Eyes | Wardrobe |
|---|---|---|---|---|
| **Mehmet** | glossy dark brown `#2c1309`, tallest (scale 1.12) | slicked-back black pompadour, sideburns | amber-brown | black suit, white shirt, dark tie, red pocket square, gold watch on left wrist, black trousers and shoes |
| **Ayşe** | shiny chestnut `#6a3214` (scale 0.95) | long dark hair with a side-swept fringe and front locks | green, with lashes | red satin evening gown, gold necklace with ruby pendant, gold hoop earrings, gold bracelet, red lips |
| **Mustafa** | glossy dark brown `#3a1a0b`, athletic chest | dark textured quiff | warm brown | white open-collar shirt, gold chain, black trousers, black belt with gold buckle |

The designs are built by `makeActor()` in `bolum2.html`.

## Shot list

| Time | Shot |
|---|---|
| 0–10 s | Skyline and title card "Bölüm 2: Sır"; wide shot with a recap of episode 1 |
| 10.5–15 s | Mehmet: "Mustafa! Bana her şeyi anlat!" |
| 15–24 s | Mustafa, nervous: "Abi... Ayşe'yle aramızda bir şey yok. Ama sana yıllardır saklanan bir gerçek var." |
| 24–30 s | Ayşe, crying: "Mustafa, sus! Ona söyleyemezsin!" |
| 30–35 s | Mehmet: "NE?! BENDEN NE SAKLIYORSUNUZ?!" |
| 35–44.5 s | Mustafa takes a deep breath: "Abi... Ayşe seninle evlenmeden önce benim nişanlımdı." |
| 44.5–50 s | Mehmet freezes: dolly-zoom (vertigo) shot, red light |
| 50–59 s | Mehmet slowly turns towards Ayşe; she cries |
| 58–61 s | Heels in the corridor, three loud knocks; everyone turns to the door |
| 61–65 s | Door close-up, a shadow under it: "MEHMET! GERÇEKLERİ ÖĞRENMEYE HAZIR MISIN?" |
| 65 s | Cut to black, end card |
