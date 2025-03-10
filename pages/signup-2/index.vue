<template>
    <div>
        <SectionsSignup2Section1 />
    </div>
</template>

<script setup>
    definePageMeta({
        layout: "no-header-footer",
    })

    useHead({
           title: 'Signup-2 Goodwill Insurance company',
          meta: [
          { name: 'description', content: 'This site is signup us' },
          { name: 'keywords', content: 'Nuxt 3, Vuetify, Web Development' },
    { name: 'author', content: 'Your Name' },
    { name: 'robots', content: 'index, follow' },

    // Open Graph (Facebook, LinkedIn)
    { property: 'og:title', content: 'Your Website Title' },
    { property: 'og:description', content: 'A short description for social media.' },
    { property: 'og:image', content: 'https://example.com/image.jpg' },
    { property: 'og:url', content: 'https://example.com' },
    { property: 'og:type', content: 'website' },

    // Twitter Card
    { name: 'twitter:card', content: 'summary_large_image' },
    { name: 'twitter:title', content: 'Your Website Title' },
    { name: 'twitter:description', content: 'A short description for Twitter.' },
    { name: 'twitter:image', content: 'https://example.com/image.jpg' }
    
          ],
          bodyAttrs: {
              class: "navbar-light"
          },
          script: [
    {
      src: "https://www.googletagmanager.com/gtag/js?id=GTM-KBRZQ85B",
      async: true
    },
    {
      innerHTML: `
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());
        gtag('config', 'GTM-KBRZQ85B');
      `,
      type: "text/javascript"
    }
  ]
      })
  
</script>