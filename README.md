# Horiseon website semantic refactoring

## Links

* [SEE THE DEPLOYED APPLICATION HERE](https://dishdesigner.github.io/osu01-code-refactor)
* [Read the accessibility text analysis report here](accessibility-testing\text-analysis\text-analysis-report.md)
* [DROPBOX: Listen to the audio of a screen reader (NVAccess) reading the existing webpage before refactoring](https://www.dropbox.com/s/l1e7ijhnzhjp4iv/01-ScreenReader-BeforeRefactor.mp3?dl=0)
* [DROPBOX: Listen to the audio of a screen reader (NVAccess) reading the refactored webpage](https://www.dropbox.com/s/o9pcatvkn3tb9da/02-ScreenReader-AfterRefactor.mp3?dl=0)

---

## Description

* This application is a simple refactoring of the Horiseon website homepage.
* The coding of the existing page did not include semantic HTML markup that help make the page more accessible and increase SEO in search engines.
* The images placed on the page were also too high in resolution for their usage, leading to a very large page download with no increase in image quality.
* Nothing was used in the project code beyond pure HTML 5 and CSS 3. Photoshop was used to reduce the placed image resolutions to optimize page download size.
* The challenge here was to refactor the markup without making any functional changes to the page whatsoever.
* The next step in the evolution of the Horiseon website would be to address its lack of responsiveness to varying screen sizes.

---

## Notes about Alt tags

* The acceptance criteria of this assignment indicated that Alt tags needed to be added to images on the web page to improve the page accessibility. Because they were stated criteria, the Alt tags were added.
* However, testing was also carried out using screen reading software to really understand how a disabled person might listen to the page being read out loud. You can hear the audio recordings before and after here.
* <mark>It is recommended, based on that audio, that ALL THE ALT TAGS ON THE PAGE BE REMOVED AND LEFT BLANK!</mark> (alt="")
* Screen readers actually do a better job of reading the web page content cleanly in this case because all of the images are merely decorative and do nothing to further clarify the text content. They only serve to trip the screen reader up while moving in and out of figures in a seemingly random order.

---

## Screenshot

![Diagram of website refactoring](assets\diagram\01-code-refactor_before&after-diagram.png)

---
## Installation

Nothing is needed to install this project. Click the link above to see the live deployment.

---

## References

The following resources were helpful in understanding the accessibility issues involed in using semantic HTML markup:
* ["HTML: A good basis for accessibility"](https://developer.mozilla.org/en-us/docs/Learn/Accessibility/HTML)
* ["Accessibility for Everyone"](https://abookapart.com/products/accessibility-for-everyone) by A Book Apart.
* [W3Schools HTML Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)

---

## License

See MIT License file within repo.

---

## Tests

The ultimate test of any accessibily refactoring project like this is to experience the page using screen reader software that reads the page out loud. If the spoken version of the page is too complicated to decipher, then its markup is not helping the assistive technology in rendering the page in speech. People with low/no vision would find it difficult to access the page or site content.

Links for Accessibility Guidelines & Testing:
* [NVAccess screen reading software for Windows (free)](https://www.nvaccess.org/)
* [W3C Web Accessibility Initiative's Tools List](https://www.w3.org/WAI/ER/tools/)
* ["10 Free Web-Based Website Accessibility Evaluation Tools" on UsabilityGeek](https://usabilitygeek.com/10-free-web-based-web-site-accessibility-evaluation-tools/)
* [UsableNet online site testing](https://usablenet.com/automated-accessibility-testing-tool?utm_campaign=PPC%3A%20Free%20Consultation%20%5BMay%202020%5D&utm_source=ppc&utm_term=Adworkds&utm_content=ADACompliance&utm_term=%2Bwebsite%20%2Baccessibility%20%2Btest&utm_campaign=UsableNet+%7C+Decision+Stage&utm_source=adwords&utm_medium=ppc&hsa_tgt=kwd-348513897052&hsa_grp=118229728520&hsa_src=g&hsa_net=adwords&hsa_mt=b&hsa_ver=3&hsa_ad=488835815889&hsa_acc=1784308961&hsa_kw=%2Bwebsite%20%2Baccessibility%20%2Btest&hsa_cam=8115142291&gclid=CjwKCAiApNSABhAlEiwANuR9YIkIW-Qo37p9fvV_DBTo4yG8foGGS-On7Vj9LGxj_8IsLOXN8eEfexoCEa0QAvD_BwE)
* [MaxAccess Online Tool (paid service)](https://maxaccess.io/?gclid=CjwKCAiApNSABhAlEiwANuR9YJRTQgM6KobC06pYKdCsrfWDpBYV3iO6sRpvfLPGMPlkTnnHIsVuWhoC9AgQAvD_BwE)

---