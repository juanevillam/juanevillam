# Hi · Hola · 你好, I'm Juan Villa

**Software developer** from Venezuela. I build native mobile apps and web products, and I build them the way I play games: going for the platinum.

Since 2022 I've been the frontend lead at [Crol](https://www.crol.mx), a cloud ERP for small and mid-sized businesses in Mexico. On my own time I build my own apps.

## My apps

### Sound Shaper

A music player for your own MP3s. Change the speed live, shape the equalizer and the effects (preserve pitch, echo, next room), and save your favorite seconds as clips. Everything lives on your phone and works offline.

- **Preserve pitch that works on music.** The audio library shipped a time-stretcher tuned for voice, which tore music apart. I patched its C++ and replaced it with a phase vocoder.
- **No more crackling on Android.** The audio stream asked for a 2 ms callback, too short to fit the vocoder's FFT. I reconfigured it to 26.7 ms.
- **Its own backend.** A Cloudflare Worker deletes media from Cloudinary for the signed-in person, so the app doesn't need Firebase's paid plan.
- Home Screen widgets, Lock Screen and Dynamic Island controls, and a library you arrange by dragging covers.

<p>
  <img src="assets/sound-shaper-library.png" width="200" alt="Sound Shaper library" />
  <img src="assets/sound-shaper-player.png" width="200" alt="Sound Shaper player" />
  <img src="assets/sound-shaper-shape.png" width="200" alt="Sound Shaper equalizer and effects" />
  <img src="assets/sound-shaper-new-clip.png" width="200" alt="Sound Shaper clip editor" />
</p>

### Topper

A social app for rankings of anything, like Letterboxd for tops: your favorite games, albums, movies. Follow people, agree or push back on their order, comment, and earn PlayStation-style trophies along the way.

<p>
  <img src="assets/topper-home.png" width="200" alt="Topper home" />
  <img src="assets/topper-explore.png" width="200" alt="Topper explore" />
  <img src="assets/topper-top-detail.png" width="200" alt="A top in Topper" />
  <img src="assets/topper-profile.png" width="200" alt="Topper profile" />
</p>

### Both apps

- iOS and Android from one codebase (React Native + Expo), with truly native UI: SwiftUI on iOS, Jetpack Compose on Android.
- A shared monorepo: design system, PlayStation-style trophies and widget plumbing live in packages both apps use.
- Every screen measured pixel by pixel against Apple's own apps, in light and dark.
- Every app speaks English, Spanish and Chinese.

## Work

**Lead Frontend Developer · Crol** (Feb 2022 – present)
Web and mobile apps for sales, electronic invoicing (CFDI), inventory and real-time reports. I built Crol's mobile app, used by major clients across Mexico, took our codebases from JavaScript to TypeScript, React to Next.js and Expo to bare React Native, and integrated the BBPOS SDK for Bluetooth card payments.

**Frontend Developer · Freelance** (Feb 2021 – Jan 2022)
Custom websites for clients in Spain and Argentina.

## Stack

`TypeScript` `React Native` `Expo` `SwiftUI` `Jetpack Compose` `Next.js` `React` `Astro` `Redux` `Firebase` `Cloudflare Workers` `C++` `Figma`

## Contact

[![LinkedIn](https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&style=for-the-badge)](https://linkedin.com/in/juanevillam)
[![Email](https://img.shields.io/static/v1?message=Email&logo=gmail&label=&color=D14836&logoColor=white&style=for-the-badge)](mailto:juanesvillamendoza@gmail.com)
[![Instagram](https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&style=for-the-badge)](https://instagram.com/juanevillam)
