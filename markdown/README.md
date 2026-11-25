# 📚 Каталог научных статей в формате Markdown

В данной папке (`markdown/`) представлены полные тексты и аналитические материалы по всем 27 ключевым научным публикациям палеогеномики из [`search/basis-literature.md`](../search/basis-literature.md).

## 🚀 Особенности конвертации и очистки
1. **Точная верстка и порядок чтения**: Тексты извлечены с помощью `pymupdf4llm` с использованием GNN-модели разметки колонок (`pymupdf-layout`), исключены паразитные векторные линии-разделители, корректно обработаны буквицы (*Drop Caps*).
2. **Очистка бегущих колонтитулов**: Удалены повторяющиеся верхние и нижние колонтитулы журналов (*PNAS, Science, Nature, Cell*), номера страниц и метаданные выпусков, вклинивавшиеся в середину предложений.
3. **Интеллектуальная фильтрация ссылок (References)**: Исключены громоздкие списки библиографических цитат (`*(References list omitted for brevity)*`), при этом **строго сохранены**:
   - Методы и протоколы исследований (`Materials and Methods` / `Online Methods`)
   - Доступность данных и кода (`Data and Code Availability`, ссылки на GitHub, Zenodo, репозитории ENA/NCBI/SRA)
   - Приложения и расширенные данные (`Supplementary Materials`, `Extended Data`)
4. **Таблицы и иллюстрации**: Сложные научные таблицы сохранены в HTML/GFM, а оригинальные рисунки и графики сохранены в `markdown/images/`.

---

## 📊 Сводная таблица статей (Все 27 статей переведены из PDF)

| № | Файл статьи | Объем (слов / симв.) | Methods | Data / GitHub | Suppl. | Таблицы | Иллюстрации |
| :-: | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **01** | [`01_Krings_1997_Neandertal_DNA_Sequences.md`](01_Krings_1997_Neandertal_DNA_Sequences.md) | 7,619 сл. / 51,443 зн. | — | — | — | ✅ | 7 рис. |
| **02** | [`02_Briggs_2007_Patterns_of_Damage_aDNA.md`](02_Briggs_2007_Patterns_of_Damage_aDNA.md) | 5,891 сл. / 39,108 зн. | — | — | — | ✅ | 10 рис. |
| **03** | [`03_Green_2010_Draft_Neandertal_Genome.md`](03_Green_2010_Draft_Neandertal_Genome.md) | 12,548 сл. / 98,519 зн. | — | — | — | ✅ | 6 рис. |
| **04** | [`04_Gansauge_Meyer_2013_ssDNA_Library_Prep.md`](04_Gansauge_Meyer_2013_ssDNA_Library_Prep.md) | 7,799 сл. / 55,405 зн. | — | — | ✅ | ✅ | 2 рис. |
| **05** | [`05_Meyer_2012_High_Coverage_Denisovan_Genome.md`](05_Meyer_2012_High_Coverage_Denisovan_Genome.md) | 4,665 сл. / 32,086 зн. | — | — | ✅ | ✅ | 5 рис. |
| **06** | [`06_Prufer_2014_Complete_Genome_Altai_Neanderthal.md`](06_Prufer_2014_Complete_Genome_Altai_Neanderthal.md) | 6,775 сл. / 52,347 зн. | — | — | ✅ | ✅ | 10 рис. |
| **07** | [`07_Prufer_2017_High_Coverage_Vindija_Neandertal.md`](07_Prufer_2017_High_Coverage_Vindija_Neandertal.md) | 3,269 сл. / 23,021 зн. | — | ✅ | ✅ | ✅ | 4 рис. |
| **08** | [`08_Mafessoni_2020_Chagyrskaya_Neandertal_Genome.md`](08_Mafessoni_2020_Chagyrskaya_Neandertal_Genome.md) | 3,518 сл. / 24,435 зн. | ✅ | ✅ | — | — | 5 рис. |
| **09** | [`09_Skov_2022_Neanderthal_Social_Organization.md`](09_Skov_2022_Neanderthal_Social_Organization.md) | 10,138 сл. / 81,109 зн. | — | ✅ | ✅ | ✅ | 10 рис. |
| **10** | [`10_Slimak_2024_Thorin_Neanderthal_Isolation.md`](10_Slimak_2024_Thorin_Neanderthal_Isolation.md) | 17,516 сл. / 120,270 зн. | — | ✅ | ✅ | — | 7 рис. |
| **11** | [`11_Slon_2017_Neandertal_Denisovan_DNA_Sediments.md`](11_Slon_2017_Neandertal_Denisovan_DNA_Sediments.md) | 3,764 сл. / 25,658 зн. | — | — | ✅ | — | 5 рис. |
| **12** | [`12_Vernot_2021_Sediment_Nuclear_Paleogenomics.md`](12_Vernot_2021_Sediment_Nuclear_Paleogenomics.md) | 6,583 сл. / 47,283 зн. | ✅ | — | ✅ | ✅ | 10 рис. |
| **13** | [`13_Petr_2020_Replacement_Neanderthal_Y_Chromosome.md`](13_Petr_2020_Replacement_Neanderthal_Y_Chromosome.md) | 3,211 сл. / 21,884 зн. | — | — | ✅ | — | 3 рис. |
| **14** | [`14_Slon_2018_Denisova_11_Denny_First_Gen_Hybrid.md`](14_Slon_2018_Denisova_11_Denny_First_Gen_Hybrid.md) | 4,244 сл. / 37,584 зн. | — | ✅ | ✅ | ✅ | 7 рис. |
| **15** | [`15_Chen_2019_Xiahe_Mandible_Denisovan_Proteomics.md`](15_Chen_2019_Xiahe_Mandible_Denisovan_Proteomics.md) | 8,591 сл. / 62,602 зн. | — | ✅ | ✅ | ✅ | 14 рис. |
| **16** | [`16_Zhang_2020_Denisovan_DNA_Baishiya_Sediments.md`](16_Zhang_2020_Denisovan_DNA_Baishiya_Sediments.md) | 3,641 сл. / 25,420 зн. | — | ✅ | ✅ | ✅ | 4 рис. |
| **17** | [`17_Sankararaman_2014_Landscape_Neanderthal_Ancestry.md`](17_Sankararaman_2014_Landscape_Neanderthal_Ancestry.md) | 6,192 сл. / 49,118 зн. | — | — | ✅ | ✅ | 5 рис. |
| **18** | [`18_Huerta_Sanchez_2014_EPAS1_Tibetan_Denisovan_Adaptation.md`](18_Huerta_Sanchez_2014_EPAS1_Tibetan_Denisovan_Adaptation.md) | 8,045 сл. / 53,365 зн. | — | — | ✅ | ✅ | 3 рис. |
| **19** | [`19_Dannemann_Kelso_2017_Neanderthal_Phenotypes_UK_Biobank.md`](19_Dannemann_Kelso_2017_Neanderthal_Phenotypes_UK_Biobank.md) | 6,336 сл. / 52,399 зн. | — | — | — | ✅ | 3 рис. |
| **20** | [`20_Zeberg_Paabo_2020_Neanderthal_COVID19_Risk_Locus.md`](20_Zeberg_Paabo_2020_Neanderthal_COVID19_Risk_Locus.md) | 2,850 сл. / 22,803 зн. | — | ✅ | ✅ | ✅ | 16 рис. |
| **21** | [`21_Zeberg_Paabo_2021_OAS1_Protective_Neanderthal_Locus.md`](21_Zeberg_Paabo_2021_OAS1_Protective_Neanderthal_Locus.md) | 3,474 сл. / 23,433 зн. | ✅ | ✅ | — | — | 5 рис. |
| **22** | [`22_Fu_2015_Oase_1_Recent_Neanderthal_Ancestor.md`](22_Fu_2015_Oase_1_Recent_Neanderthal_Ancestor.md) | 5,379 сл. / 65,289 зн. | — | ✅ | ✅ | ✅ | 6 рис. |
| **23** | [`23_Hajdinjak_2021_Bacho_Kiro_Neanderthal_Ancestry.md`](23_Hajdinjak_2021_Bacho_Kiro_Neanderthal_Ancestry.md) | 7,083 сл. / 51,581 зн. | — | ✅ | ✅ | ✅ | 13 рис. |
| **24** | [`24_Brown_2004_Homo_floresiensis_Discovery.md`](24_Brown_2004_Homo_floresiensis_Discovery.md) | 25,921 сл. / 175,685 зн. | — | — | ✅ | ✅ | 36 рис. |
| **25** | [`25_Tucci_2018_Flores_Pygmies_Genomics.md`](25_Tucci_2018_Flores_Pygmies_Genomics.md) | 3,199 сл. / 22,307 зн. | — | ✅ | — | ✅ | 4 рис. |
| **26** | [`26_Meyer_2016_Sima_de_los_Huesos_Nuclear_DNA.md`](26_Meyer_2016_Sima_de_los_Huesos_Nuclear_DNA.md) | 4,903 сл. / 35,169 зн. | — | ✅ | ✅ | ✅ | 12 рис. |
| **27** | [`27_Zhang_2026_TRACE_Archaic_Introgression_ARG.md`](27_Zhang_2026_TRACE_Archaic_Introgression_ARG.md) | 6,202 сл. / 43,514 зн. | — | — | ✅ | ✅ | 9 рис. |
