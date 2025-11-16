
2F Soluções - Site Estático (pronto para hospedar)
---------------------------------------------

Arquivos incluídos:
- index.html
- assets/logo.svg
- assets/unified-card.svg

Como usar:
1. Extraia o ZIP e abra index.html em um navegador para testar localmente.
2. Para hospedar em produção, envie todos os arquivos para seu provedor (Netlify, Vercel, Firebase Hosting, qualquer hospedagem estática ou seu próprio servidor).
3. O site usa Tailwind via CDN (https://cdn.tailwindcss.com) para simplicidade. Em produção, é recomendável compilar Tailwind localmente para otimização.

Personalização rápida:
- Alterar e-mail de contato e telefone: abra index.html e edite as strings 'contato@2fsolucoes.com' e '(11) 9 9999-0000' no rodapé e no formulário.
- Alterar cores: edite os valores hex (por exemplo #062234 e #1f8ed6) no arquivo index.html para combinar sua identidade visual.
- Substituir imagens: coloque arquivos com mesmo nome na pasta assets ou altere os caminhos no index.html.

Formulário:
- O formulário está configurado para enviar via mailto: (envia o e-mail pelo cliente de e-mail do usuário).
- Para integrar com backend, substitua o atributo 'action' do <form> por seu endpoint e remova enctype="text/plain".
- Para integração com WhatsApp ou CRM, podemos atualizar o formulário para enviar dados via fetch/AJAX — me diga qual serviço quer usar.

Se quiser, eu:
- gero uma versão otimizada (HTML + CSS minificados);
- crio arquivos para SEO (sitemap, robots.txt);
- configuro formulário para enviar para o seu e-mail via API (ex: formspree, getform, or your backend).

Contato:
Se preferir, diga quais valores exatos (logo, e-mail, telefone, endereço, redes sociais) que eu já substituo nos arquivos e re-crio o ZIP.


Updated: optimized version, removed simulator aside, added privacy.html and updated contact details and logo.
