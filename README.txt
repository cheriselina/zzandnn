ZZXNN IMAGE GALLERY — VERCEL READY

FILES
- index.html
- style.css
- images/  ← put your own images here

HOW TO ADD YOUR IMAGES

1. Put your photos inside the images folder.
   Example:
   images/photo1.jpg
   images/photo2.jpg

2. In index.html, replace a placeholder like:
   <div class="placeholder">01</div>

   with:
   <img src="images/photo1.jpg" alt="favorite moment">

3. Add this CSS to style.css if you use images:
   .card img {
     width: 100%;
     display: block;
     object-fit: cover;
     border-radius: 3px;
   }

DEPLOY TO VERCEL

1. Go to https://vercel.com/
2. Create/sign in to your account.
3. Create a new project.
4. Upload/import this website folder.
5. Deploy.
6. Vercel will give you a temporary .vercel.app address.

CONNECT ZZXNN.COM

After you own zzxnn.com:
1. Open your Vercel project.
2. Go to Settings → Domains.
3. Add zzxnn.com.
4. Follow Vercel's DNS instructions.
5. HTTPS will be set up automatically.

You can edit all titles/captions directly in index.html.
