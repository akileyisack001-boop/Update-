WAAMINIO RUNZEWE — MWONGOZO WA KUSANIKISHA NETLIFY
==================================================

MUHIMU
- Huu ni mradi wa Netlify wenye tovuti ya umma, dashboard ya msimamizi na Netlify Function.
- Netlify Blobs huhifadhi masomo na faili zilizopakiwa.
- Huwezi kutumia index.html peke yake; pakia folda/mradi wote ili Functions ziweze kufanya kazi.
- Upload ya moja kwa moja imewekewa kikomo cha MB 4 kwa faili. Video kubwa tumia YouTube URL.
- Hifadhi hii inahitaji Netlify Functions na Netlify Blobs kuwezeshwa kwenye site yako.

HATUA 1: TENGENEZA SITE
1. Fungua https://app.netlify.com/ kwenye Chrome na ingia.
2. Bonyeza Add new site / Import an existing project (au deploy manually).
3. Kwa njia rahisi ya deploy manually, fungua https://app.netlify.com/drop na pakia ZIP iliyofunguliwa (unzip) ya mradi huu. Ikiwa Netlify Drop haitengenezi Functions kwa deploy hiyo, tumia GitHub import.
4. Njia inayopendekezwa: fungua GitHub, tengeneza repository mpya, upload mafaili yote ya mradi huu (si ZIP yenyewe), kisha Netlify > Add new site > Import from Git.
5. Build command: acha tupu. Publish directory: .

HATUA 2: WEKA SIRI ZA MSIMAMIZI
Netlify Dashboard > Site configuration > Environment variables > Add a variable.
Ongeza:
ADMIN_PASSWORD = nenosiri lako refu la siri (usiweke hapa kwenye mazungumzo).
ADMIN_SESSION_SECRET = maandishi marefu ya siri yasiyopungua herufi 40; tumia password generator.
Baada ya kuweka variables, redeploy site.

HATUA 3: WASHA NETLIFY BLOBS
Netlify Functions zitatumia Netlify Blobs kwa kuhifadhi maudhui. Hakikisha site ime-deploy kupitia Netlify na Functions zimeonekana kwenye dashboard.

HATUA 4: TUMIA WEBSITE
Tovuti ya wageni: https://JINA-LA-SITE.netlify.app/
Dashboard: https://JINA-LA-SITE.netlify.app/admin.html
Ingia kwa ADMIN_PASSWORD uliyoweka kwenye Netlify.
Andika somo, weka maandishi au HTML, chagua MP3/video ndogo au weka YouTube URL, kisha Hifadhi. Baada ya hapo bonyeza Chapisha kwenye orodha ya machapisho ili somo lionekane kwa wageni.

MUHIMU KUHUSU USALAMA
- Usishare ADMIN_PASSWORD wala ADMIN_SESSION_SECRET.
- Usitumie password rahisi.
- HTML unayoweka inaonyeshwa kwenye iframe sandbox, lakini usibandike code usiyoamini.
- Huu ni mwanzo wa mfumo wa msingi; fanya majaribio ya login, kuchapisha, kusikiliza na kufuta kabla ya kuweka masomo mengi.
