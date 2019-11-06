---
title: "Dodatek B: Ukázkový plán posuzování kvality"
---

V duchu rady _Chtějte důkazy místo slibů_ nabízíme ukázkový plán posuzování kvality (QASP), který byste měli zařadit do svých agilních poptávkových dokumentů.

| **Oblast** | **Výkonnostní ukazatele** | **Přijatelná úroveň kvality** | **Způsob kontroly**
|---|---|---|---|
| Testování | Kód odevzdaný na základě objednávky musí být z větší části pokrytý automatickými testy. Zdrojový kód je verzovaný ve veřejném repository a zůstává ve vlastnictví státu. | Aspoň 90% pokrytí testy | Kombinace ruční kontroly a automatických testů |
| Vývojářské standardy | [GSA 18F Front-End Guide](https://frontend.18f.gov/) | Žádná varování od linteru, žádná varování od překladače | Kombinace ruční kontroly a automatických testů |
| Přístupnost | Web Content Accessibility Guidelines 2.1 AA | Žádné chyby nahlášené automatickým skenerem, žádné chyby nalezené ruční kontrolou | [Pa11y](https://github.com/pa11y/pa11y) |
| Nasazení | Kód se musí úspěšně přeložit a nasadit do testovacího prostředí | Úspěšný build jedním příkazem |Kombinace ruční kontroly a automatických testů |
| Dokumentace | Existuje seznam všech závislostí a jejich licencí. Hlavní funkce zdrojového kódu a softwaru jsou dokumentované. Zdrojový kód je komentovaný způsobem, který umožňuje automatické generování dokumentace (například [JSDoc](http://usejsdoc.org/)). Existuje systémový diagram celého systému. | Kombinace ruční kontroly a automatických testů, pokud jsou k dispozici | Ruční kontrola |
| Bezpečnost | [OWASP Application Security Verification Standard 3.0](https://www.owasp.org/images/6/67/OWASPApplicationSecurityVerificationStandard3.0.pdf) | V kódu nesmí být žádné statické nebo dynamické bezpečnostní problémy střední a vyšší úrovně | Čisté výstupy ze statického SaaS testu (například [npm audit](https://docs.npmjs.com/cli/audit)) a [OWASP ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project), falešně pozitivní výsledky jsou uvedené v dokumentaci |
| Analýza uživatelských požadavků | Analýza požadavků a testování použitelnosti musí probíhat pravidelně během celého vývoje, nejen na jeho začátku. | Výstupy z testování použitelnosti a dalších analýz jsou k dispozici na konci každého vhodného sprintu, podle plánu dodavatele | Ruční kontrola |
