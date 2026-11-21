# Video Editor Library — Upload Steps (GitHub Pages)

Ye folder ek ready static site hai. Isay GitHub par daalte hi Video Editor app ke liye
online Trending / Material library live ho jayegi. Koi card ya bank details nahi chahiye,
sirf ek free GitHub account chahiye.

Is folder me 3 files hain:
- `library.json` — asli library data (templates + materials). App isi file ko padhta hai.
- `index.html` — library ki simple page, browser me khulegi.
- `README.md` — ye wali file (steps).

## Upload steps

1. GitHub par account bana lo (sirf email se banta hai, card nahi mangta).
2. GitHub par ek **naya public repo** banao, naam rakho: `video-editor-library`
   - "Public" hi rakhna, warna app file nahi padh payega.
3. Us repo me is folder ki teeno files **upload** kar do
   (repo page par "Add file" → "Upload files").
4. Repo ki **Settings → Pages** me jao.
5. "Build and deployment" me Source: **Deploy from a branch** chuno,
   branch: **main** (folder: `/ (root)`) aur Save kar do.
6. 1–2 minute me site live ho jayegi. Site ka URL aisa hoga:
   `https://<username>.github.io/video-editor-library/`
   (`<username>` ki jagah tumhara GitHub username hoga.)
7. Library file ka URL ye hoga:
   `https://<username>.github.io/video-editor-library/library.json`

## App me jodna

1. Video Editor app kholo → neeche **Me** tab.
2. **Online Library** wale hisse me upar wala site URL (ya seedha `library.json` wala URL)
   daalo aur **Load Library** dabao.
3. Neeche status me "Library: online" dikhega. Ab Trending, Templates aur Material me
   online templates/materials built-in ke saath dikhne lagenge.
4. Naya template add karna ho to sirf `library.json` edit karke GitHub par update kar do —
   naya APK nahi banana padega, app khud nayi list le lega.

## Dhyaan do

- Repo **public** hona chahiye — library sabke liye khuli hogi, koi private cheez isme mat daalna.
- Ek file 100 MB se badi nahi honi chahiye (humari files bahut chhoti hain, koi dikkat nahi).
- URL me galti ho ya net band ho to app chup chaap built-in presets par chalta rahega, band nahi hoga.
