AI Filmcraft portfolio - static site (no build step).
Deploy: vercel --prod   (run inside this folder), or drag the folder into vercel.com/new.
Add a project: copy its media into assets/pN/, its prompts into prompts/pN.txt, then add an entry in data.js (see mk script fields: id, slug, title, cat, desc, thumb, film, clips, shots, file).
Local test: python3 -m http.server 8000
