# Clutch Arena

Static site. `index.html` (players) aur `admin.html` (tum) ko Vercel / Netlify pe daal do.

## Done (Supabase me already apply ho chuka)
- RLS ON, sirf read policies, anon/authenticated ke write grants hata diye
- Private buckets, admin RPCs, admin storage read policy

## Tumhare 2 kaam
1. Site pe apne number se Register karo, phir `supabase-admin-setup.sql` me number badal ke SQL Editor me chalao. Uske baad `/admin.html` me login karo.
2. Supabase > Authentication > Providers > Email > "Confirm email" OFF karo (warna signup fail hoga).

## Test
Ek test booking karo, receipt bhejo, admin.html me Mark paid dabao. UPI pe Rs 1 ka test payment bhi kar lo.
