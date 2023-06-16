<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

प्रथमं nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) , ततः `direnv allow` संस्थापयितुं अनुशंसितं भवति ( निर्देशिकायां प्रविष्टस्य अनन्तरं [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) स्वयमेव निष्पादितं भविष्यति) ।

अर्थः अस्ति : जापानी, कोरियाई, आङ्ग्लभाषायां चीनीभाषायां अनुवादः, अन्येषु सर्वेषु भाषासु आङ्ग्लभाषायां अनुवादः। यदि भवान् केवलं चीनीभाषायाः आङ्ग्लभाषायाः च समर्थनं कर्तुम् इच्छति तर्हि केवलं `zh: en` लिखितुं शक्नोति ।

अर्थः अस्ति : जापानी, कोरियाई, आङ्ग्लभाषायां चीनीभाषायां अनुवादः, अन्येषु सर्वेषु भाषासु आङ्ग्लभाषायां अनुवादः। यदि भवान् केवलं चीनीभाषायाः आङ्ग्लभाषायाः च समर्थनं कर्तुम् इच्छति तर्हि केवलं `zh: en` लिखितुं शक्नोति ।

* [अग्र-अन्त-सङ्केतः](https://github.com/xxai-art/web)
* [समग्ररूपेण साइट् कृते भाषापैक्](https://github.com/xxai-art/web/tree/main/i18n)
* [प्रवेशमॉड्यूलानां कृते भाषापैक्](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [वेबसाइट बहुभाषी दस्तावेजीकरण](https://github.com/xxai-doc)

अग्रभागस्य प्रोग्रामिंगभाषा [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) अस्ति, यत् coffeescript वाक्यविन्यासस्य आधारेण केचन विशेषताः योजयति, पश्यन्तु [./coffee_plus.md](./coffee_plus.md) ।

## जालपुटानां दस्तावेजानां च अन्तर्राष्ट्रीयकरणम्

निम्नलिखित ३ परियोजनासु निर्माणं कुर्वन्तु

* [@ w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  प्रत्ययः `.mdt` अस्ति, बाह्यसञ्चिकानां सन्दर्भार्थं `<+ ./coffee_plus/import.js>` सदृशं वाक्यविन्यासं उपयोक्तुं शक्नुवन्ति, तथा च `.md` प्रत्ययेन सह markdown जनयितुं शक्नुवन्ति ।

* [@ w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  Markdown अनुवादः कोड्-लिङ्क्-अनुवादं न करिष्यति, अनुवादितवाक्यानि च संग्रहयिष्यति । यदि अनुवादः परिवर्तितः परन्तु मूलपाठः परिवर्तितः नास्ति तर्हि पुनः तस्य निष्पादनेन अनुवादस्य परिवर्तनं न अधिलिख्यते ।

* [@ w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  `yaml` उत्पन्नजालस्थलानां अनुवादार्थं भाषासञ्चिकाः ।

### दस्तावेज अनुवाद स्वचालन निर्देश

कोड भण्डारं [xxai-art/doc](https://github.com/xxai-art/doc) पश्यन्तु

प्रथमं nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) , ततः `direnv allow` संस्थापयितुं अनुशंसितं भवति ( निर्देशिकायां प्रविष्टस्य अनन्तरं [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) स्वयमेव निष्पादितं भविष्यति) ।

शतशः भाषासु अनुवादितं विशालं कोड आधारं परिहरितुं अहं प्रत्येकस्य भाषायाः कृते पृथक् कोड आधारं निर्मितवान् तथा च कोड आधारस्य संग्रहणार्थं संस्थां निर्मितवान्

वातावरणचरं `GITHUB_ACCESS_TOKEN` सेट् कृत्वा ततः [create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) चालयित्वा स्वयमेव कोडभण्डारं निर्मास्यति ।

अवश्यं, भवान् तत् कोड आधारे अपि स्थापयितुं शक्नोति ।

अनुवाद लिपि सन्दर्भ [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

लिपिसङ्केतस्य व्याख्या निम्नलिखितरूपेण भवति ।

[bunx](https://bun.sh/docs/cli/bunx) npx इत्यस्य प्रतिस्थापनम् अस्ति, यत् द्रुततरम् अस्ति । अवश्यं, यदि भवतां समीपे bun संस्थापितम् नास्ति तर्हि तस्य स्थाने `npx` उपयोगं कर्तुं शक्नोति ।

`bunx mdt zh` zh निर्देशिकायां `.mdt` `.md` इति रेण्डर् करोति, अधः २ लिङ्क् कृतानि सञ्चिकाः पश्यन्तु

* [कॉफी_प्लस.मडत](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [कॉफी_प्लस.मड](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` अनुवादस्य मूलसङ्केतः अस्ति (यदि भवतां केवलं `nodejs` संस्थापितम् अस्ति, परन्तु `bun` तथा `direnv` संस्थापितम् नास्ति, तर्हि अनुवादार्थं `npx i18n` अपि चालयितुं शक्नोति) ।

इदं [i18n.yml इत्यस्य](https://github.com/xxai-art/doc/blob/main/i18n.yml) विश्लेषणं करिष्यति , अस्मिन् दस्तावेजे `i18n.yml` इत्यस्य विन्यासः निम्नलिखितरूपेण अस्ति ।

```
en:
zh: ja ko en
```

अर्थः अस्ति : जापानी, कोरियाई, आङ्ग्लभाषायां चीनीभाषायां अनुवादः, अन्येषु सर्वेषु भाषासु आङ्ग्लभाषायां अनुवादः। यदि भवान् केवलं चीनीभाषायाः आङ्ग्लभाषायाः च समर्थनं कर्तुम् इच्छति तर्हि केवलं `zh: en` लिखितुं शक्नोति ।

अन्तिमः [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) अस्ति, यत् प्रत्येकस्य भाषायाः `README.md` इत्यस्य मुख्यशीर्षकस्य प्रथमस्य उपशीर्षकस्य च मध्ये सामग्रीं निष्कास्य `README.md` इति प्रविष्टिं जनयति । कोडः अतीव सरलः अस्ति, भवान् स्वयमेव तत् अवलोकयितुं शक्नोति ।

निःशुल्क-अनुवादाय गूगल-एपिआइ-इत्यस्य उपयोगः भवति । यदि भवान् गूगलं प्राप्तुं न शक्नोति तर्हि कृपया प्रॉक्सी विन्यस्य सेट् कुर्वन्तु, यथा:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

अनुवादस्क्रिप्ट् `.i18n` निर्देशिकायां अनुवादितं संग्रहणं जनयिष्यति, कृपया `git status` सह तस्य जाँचं कुर्वन्तु तथा च पुनः पुनः अनुवादं परिहरितुं कोडभण्डारं योजयन्तु ।

कृपया प्रत्येकं वारं अनुवादं परिवर्तयितुं `bunx i18n` चालयन्तु ।

यदि मूलपाठः अनुवादश्च एकस्मिन् समये परिवर्तितः भवति तर्हि संग्रहणं भ्रमितं भविष्यति, अतः यदि भवान् परिवर्तनं कर्तुम् इच्छति तर्हि केवलं एकं परिवर्तयितुं शक्नोति, ततः सञ्चिकां अद्यतनीकर्तुं `bunx i18n` चालयितुं शक्नोति
