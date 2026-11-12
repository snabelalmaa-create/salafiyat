# سلفتي – إدارة السلف

تطبيق ويب لإدارة سلف الموظفين: طلب سلفة، موافقة وصرف، اعتماد، وسندات استرداد.

- الواجهة: `public/index.html` (ملف واحد)
- قاعدة البيانات: Supabase (مشروع sanabel-mart، قسم `salafiyat`) عبر دوال `slf_*`
- النشر: Cloudflare Workers (assets) عبر `wrangler.jsonc`، يُنشر تلقائياً عند كل push على main
