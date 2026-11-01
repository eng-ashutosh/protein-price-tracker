# Protein Price Tracker (India)

Daily-updated protein powder prices scraped from Indian D2C brand stores and
Nutrabay via a [GitHub Actions](.github/workflows/daily-price-check.yml) cron
job. Data sources and rationale: see [SOURCES.md](SOURCES.md).

**Last checked:** 2026-11-01 16:00 IST

Full history: [`data/history.csv`](data/history.csv) &middot; latest snapshot:
[`data/latest.json`](data/latest.json)

<details>
<summary>Run it yourself / add more sources</summary>

```bash
pip install -r requirements.txt
python -m scraper.main
```

Add or remove sites in [`scraper/config.py`](scraper/config.py) — Shopify D2C
brands just need a store URL added to `SHOPIFY_STORES`, no code changes.
See [SOURCES.md](SOURCES.md) for why each current source was chosen (and
why Amazon/Flipkart/HealthKart/BigBasket aren't scraped).

</details>

---

## AS-IT-IS Nutrition

| Product | MRP | Price | Discount | ₹/100g (pack) | Stock | Link |
|---|---:|---:|---:|---:|:---:|---|
| AS-IT-IS ONE Brown Rice Protein - 27g Protein per Serving - Plant Protein - Single-Ingredient, Unflavoured (35g) | ₹175 | ₹115 | 34% | - | ✅ | [view](https://asitisnutrition.com/products/as-it-is-nutrition-brown-rice-protein-80-designed-as-meal-supplement-lab-tested-unflavoured) |
| AS-IT-IS ONE Pea Protein Isolate - 29g Protein per Serving - Plant Protein - Single-Ingredient, Unflavoured (36g sachet) | ₹175 | ₹115 | 34% | - | ✅ | [view](https://asitisnutrition.com/products/as-it-is-nutrition-pea-protein-isolate-powder) |
| AS-IT-IS ONE Soy Protein Isolate - 30g Protein per Serving - Plant Protein - Single-Ingredient, Unflavoured (35g) | ₹175 | ₹115 | 34% | - | ✅ | [view](https://asitisnutrition.com/products/as-it-is-nutrition-buy-soy-protein-isolate-powder-in-india) |
| AS-IT-IS ATOM Beginners Whey Protein - 15g Protein per Serving - With DigeZyme® Enzymes (Choco Hazel Fusion / 37g) | ₹203 | ₹124 | 39% | - | ✅ | [view](https://asitisnutrition.com/products/atom-beginners-whey-protein) |
| AS-IT-IS ATOM Performance Whey - 25g Protein per Serving - With Safed Musli, Mucuna & DigeZyme® Enzymes (Double Rich Chocolate / 45g) | ₹220 | ₹133 | 40% | - | ✅ | [view](https://asitisnutrition.com/products/as-it-is-atom-performance-whey-1kg-with-safed-musli-for-faster-recovery-highly-bioavailable) |
| AS-IT-IS ATOM Performance Whey - 25g Protein per Serving - With Safed Musli, Mucuna & DigeZyme® Enzymes (Pista Fusion / 45g) | ₹2,485 | ₹133 | 95% | - | ❌ | [view](https://asitisnutrition.com/products/as-it-is-atom-performance-whey-1kg-with-safed-musli-for-faster-recovery-highly-bioavailable) |
| AS-IT-IS ATOM Performance Whey - 25g Protein per Serving - With Safed Musli, Mucuna & DigeZyme® Enzymes (Cafe Latte / 45g) | ₹2,485 | ₹133 | 95% | - | ❌ | [view](https://asitisnutrition.com/products/as-it-is-atom-performance-whey-1kg-with-safed-musli-for-faster-recovery-highly-bioavailable) |
| AS-IT-IS ATOM Performance Whey - 25g Protein per Serving - With Safed Musli, Mucuna & DigeZyme® Enzymes (Cookie delight / 45g) | ₹2,485 | ₹133 | 95% | - | ❌ | [view](https://asitisnutrition.com/products/as-it-is-atom-performance-whey-1kg-with-safed-musli-for-faster-recovery-highly-bioavailable) |
| AS-IT-IS ATOM Performance Whey - 25g Protein per Serving - With Safed Musli, Mucuna & DigeZyme® Enzymes (Choco hazel fusion / 45g) | ₹2,485 | ₹133 | 95% | - | ❌ | [view](https://asitisnutrition.com/products/as-it-is-atom-performance-whey-1kg-with-safed-musli-for-faster-recovery-highly-bioavailable) |
| AS-IT-IS ATOM Whey Protein - 27g Protein per Serving - DigeZyme® Enzymes & 1 Billion CFU Probiotics (Double Rich Chocolate / (36g Travel Sachet)) | ₹262 | ₹158 | 40% | ₹438.89 | ✅ | [view](https://asitisnutrition.com/products/atom-whey-protein) |
| AS-IT-IS ONE Whey Protein Concentrate Sachets - 28g Protein per Serving - Unflavoured (35g Sachet (Pack of 1)) | ₹305 | ₹169 | 45% | ₹563.33 | ✅ | [view](https://asitisnutrition.com/products/whey-protein-30g-sachet) |
| AS-IT-IS ATOM Nitro Whey with Creasure® - 33g Protein, 3g Creatine per Serving - With DigeZyme® Enzymes (Double Rich Chocolate / 45g) | ₹289 | ₹175 | 39% | - | ✅ | [view](https://asitisnutrition.com/products/atom-nitro-whey-with-creatine-i-33g-protein-3g-creatine-7-4g-bcaa) |
| AS-IT-IS ATOM Nitro Whey with Creasure® - 33g Protein, 3g Creatine per Serving - With DigeZyme® Enzymes (Kesar Kulfi / 45g) | ₹3,407 | ₹175 | 95% | - | ❌ | [view](https://asitisnutrition.com/products/atom-nitro-whey-with-creatine-i-33g-protein-3g-creatine-7-4g-bcaa) |
| AS-IT-IS ATOM Nitro Whey with Creasure® - 33g Protein, 3g Creatine per Serving - With DigeZyme® Enzymes (Classic Vanilla / 45g) | ₹3,407 | ₹175 | 95% | - | ❌ | [view](https://asitisnutrition.com/products/atom-nitro-whey-with-creatine-i-33g-protein-3g-creatine-7-4g-bcaa) |
| AS-IT-IS ONE Whey Protein Concentrate Sachets - 28g Protein per Serving - Unflavoured (35g Sachet (Pack of 1) + Shaker) | ₹438 | ₹287 | 34% | ₹956.67 | ❌ | [view](https://asitisnutrition.com/products/whey-protein-30g-sachet) |

## Fast&Up

| Product | MRP | Price | Discount | ₹/100g (pack) | Stock | Link |
|---|---:|---:|---:|---:|:---:|---|
| 100% Pure & Natural Moringa Powder | ₹250 | ₹238 | 5% | - | ✅ | [view](https://in.fastandup.com/products/100-pure-natural-moringa-powder) |
| Plant Protein - Assorted Pack | ₹270 | ₹243 | 10% | - | ✅ | [view](https://in.fastandup.com/products/fast-up-plant-protein-assorted-pack) |
| Plant Protein - Rich Chocolate - Single Serving Sachet Combo Pack (Rich Chocolate / Pack of 5) | ₹450 | ₹396 | 12% | - | ✅ | [view](https://in.fastandup.com/products/plant-protein-rich-chocolate-single-serving-sachet-combo-pack) |
| Plant Protein - Rich Chocolate - Single Serving Sachet Combo Pack (Rich Chocolate / Pack of 10) | ₹900 | ₹765 | 15% | - | ✅ | [view](https://in.fastandup.com/products/plant-protein-rich-chocolate-single-serving-sachet-combo-pack) |
| Plant Protein - Rich Chocolate - Single Serving Sachet Combo Pack (Rich Chocolate / Pack of 15) | ₹1,350 | ₹1,107 | 18% | - | ✅ | [view](https://in.fastandup.com/products/plant-protein-rich-chocolate-single-serving-sachet-combo-pack) |
| Plant Protein - Cookies & Cream - 500g | ₹1,599 | ₹1,119 | 30% | ₹223.80 | ✅ | [view](https://in.fastandup.com/products/plant-protein-cookies-cream-500g) |
| Plant Protein - Rich Chocolate – 500gms | ₹1,599 | ₹1,119 | 30% | ₹223.80 | ✅ | [view](https://in.fastandup.com/products/plant-protein-powder-500gms) |
| Yeast Protein - Unflavoured - 500g | ₹1,299 | ₹1,169 | 10% | ₹233.80 | ✅ | [view](https://in.fastandup.com/products/yeast-protein-unflavoured-500g) |
| Yeast Protein - Coffee - 500g | ₹1,299 | ₹1,169 | 10% | ₹233.80 | ✅ | [view](https://in.fastandup.com/products/yeast-protein-coffee-500g) |
| Yeast Protein - Rich Chocolate - 500g | ₹1,299 | ₹1,169 | 10% | ₹233.80 | ✅ | [view](https://in.fastandup.com/products/yeast-protein-rich-chocolate-500g) |
| Yeast Protein - Cookies & Cream - 500g | ₹1,299 | ₹1,169 | 10% | ₹233.80 | ✅ | [view](https://in.fastandup.com/products/yeast-protein-cookies-cream-500g) |
| Plant Protein - Alphonso Mango - 1Kg | ₹3,115 | ₹1,962 | 37% | ₹196.20 | ✅ | [view](https://in.fastandup.com/products/plant-protein-alphonso-mango-25-servings) |
| Plant Protein - Kesar Kulfi - 1kg | ₹3,115 | ₹1,962 | 37% | ₹196.20 | ❌ | [view](https://in.fastandup.com/products/plant-protein-powder-special-festive-pack) |
| Plant Protein - Cookies & Cream - 1Kg | ₹3,115 | ₹1,962 | 37% | ₹196.20 | ✅ | [view](https://in.fastandup.com/products/plant-protein-cookies-cream-1-kg) |
| Plant Protein - Strawberry Blast - 25 Servings | ₹3,115 | ₹1,962 | 37% | - | ✅ | [view](https://in.fastandup.com/products/plant-protein-strawberry-25-servings) |

## GNC India

| Product | MRP | Price | Discount | ₹/100g (pack) | Stock | Link |
|---|---:|---:|---:|---:|:---:|---|
| Protein Wafer Bar Mini (Chocolate / 20 gm) | ₹60 | ₹28 | 53% | ₹140.00 | ✅ | [view](https://gnc.in/products/pp-protein-wafer-bar-mini-20gm) |
| Protein Wafer Bar Mini (Coffee / 20 gm) | ₹60 | ₹28 | 53% | ₹140.00 | ✅ | [view](https://gnc.in/products/pp-protein-wafer-bar-mini-20gm) |
| Protein Wafer Bar Mini (Peanut Butter / 20 gm) | ₹60 | ₹28 | 53% | ₹140.00 | ✅ | [view](https://gnc.in/products/pp-protein-wafer-bar-mini-20gm) |
| GNC High Protein Oats Dark Bliss (Chocolate) (40g) | ₹45 | ₹45 | 0% | ₹112.50 | ❌ | [view](https://gnc.in/products/gnc-high-protein-oats-dark-bliss-chocolate) |
| GNC Protein Wafer Bar (Chocolate) (Pack of 1 / Chocolate) | ₹59 | ₹55 | 7% | - | ✅ | [view](https://gnc.in/products/gnc-protein-wafer-bar-chocolate) |
| GNC Protein Wafer Bar (Peanut butter) (Pack of 1 / Peanut Butter) | ₹59 | ₹55 | 7% | - | ✅ | [view](https://gnc.in/products/gnc-protein-wafer-bar-peanut-butter) |
| GNC Protein Wafer Bar (Coffee) (Pack of 1 / Coffee) | ₹59 | ₹55 | 7% | - | ✅ | [view](https://gnc.in/products/gnc-protein-wafer-bar-coffee) |
| GNC Protein Wafer Bar (40g / Chocolate) | ₹60 | ₹55 | 8% | ₹137.50 | ✅ | [view](https://gnc.in/products/gnc-protein-wafer-bar-upsell) |
| Protein Crunch Wafer Bar 40gm (Peanut Butter) | ₹80 | ₹59 | 26% | ₹147.50 | ✅ | [view](https://gnc.in/products/protein-crunch-wafer-bar-40gm) |
| Protein Crunch Wafer Bar 40gm (Cookies & Cream) | ₹80 | ₹59 | 26% | ₹147.50 | ✅ | [view](https://gnc.in/products/protein-crunch-wafer-bar-40gm) |
| Protein Crunch Wafer Bar 40gm (Chocolate) | ₹80 | ₹59 | 26% | ₹147.50 | ✅ | [view](https://gnc.in/products/protein-crunch-wafer-bar-40gm) |
| Protein Crunch Wafer Bar 40gm (Strawberry) | ₹80 | ₹59 | 26% | ₹147.50 | ✅ | [view](https://gnc.in/products/protein-crunch-wafer-bar-40gm) |
| Protein Crunch Wafer Bar Cookies & Cream 40gm | ₹80 | ₹59 | 26% | ₹147.50 | ✅ | [view](https://gnc.in/products/protein-crunch-wafer-bar-cookies-cream-40gm) |
| Protein Crunch Wafer Bar Peanut Butter 40gm | ₹80 | ₹59 | 26% | ₹147.50 | ✅ | [view](https://gnc.in/products/protein-crunch-wafer-bar-peanut-butter-40gm) |
| GNC Select Fermented Yeast Protein Isolate (35 gm / Chocolate) | ₹149 | ₹59 | 60% | ₹168.57 | ✅ | [view](https://gnc.in/products/gnc-select-fermented-yeast-protein) |

## MyFitness

| Product | MRP | Price | Discount | ₹/100g (pack) | Stock | Link |
|---|---:|---:|---:|---:|:---:|---|
| MyFitness Peanut Butter - Chocolate - 26% Protein - Crispy - Chocolate Peanut Butter Spread (227g) | ₹159 | ₹149 | 6% | ₹65.64 | ✅ | [view](https://myfitness.co.in/products/chocolate-crispy) |
| Pro.Fitness High Protein Chocolate Oats - Dark Chocolate - Healthy Oats With Nuts, Seeds & Added Whey (375g) | ₹339 | ₹219 | 35% | ₹58.40 | ✅ | [view](https://myfitness.co.in/products/high-protein-oats-900g-27g-protein) |
| Pro.Fitness High Protein Chocolate Peanut Butter Oats - Made with MyFitness Chocolate Peanut Butter - 27% Protein - No Added Refined Sugar (375g) | ₹349 | ₹249 | 29% | ₹66.40 | ❌ | [view](https://myfitness.co.in/products/pro-fitness-high-protein-chocolate-peanut-butter-oats-made-with-myfitness-chocolate-peanut-butter-27-protein-no-added-refined-sugar) |
| Pro.Fitness Rolled Oats - 13% Protein - Healthy Oats With High Fiber and Zero Cholesterol (900g) | ₹320 | ₹269 | 16% | - | ✅ | [view](https://myfitness.co.in/products/pro-fitness-rolled-oats-900g) |
| MyFitness Peanut Butter - Classic Zero - 28% Protein - Extra Crunchy - Zero Sugar Peanut Spread (510 g) | ₹349 | ₹275 | 21% | ₹53.92 | ✅ | [view](https://myfitness.co.in/products/myfitness-zero-peanut-butter-crunchy-510g) |
| MyFitness Peanut Butter - Chocolate - 26% Protein - Crunchy - Chocolate Peanut Butter Spread (510 g) | ₹319 | ₹275 | 14% | ₹45.08 | ✅ | [view](https://myfitness.co.in/products/myfitness-chocolate-peanut-butter-crunchy) |
| MyFitness Peanut Butter - Natural Unsweetened - 31% Protein - Crunchy - Zero Sugar Peanut Butter Spread (510 g) | ₹319 | ₹275 | 14% | ₹45.08 | ✅ | [view](https://myfitness.co.in/products/myfitness-all-natural-peanut-butter-crunchy) |
| MyFitness Peanut Butter - Natural Unsweetened - 25% Protein - Smooth - Zero Sugar Peanut Butter Spread (510 g) | ₹319 | ₹275 | 14% | ₹45.08 | ✅ | [view](https://myfitness.co.in/products/myfitness-all-natural-peanut-butter-smooth) |
| MyFitness Peanut Butter - Chocolate - 26% Protein - Crispy - Chocolate Peanut Butter Spread (510 g) | ₹319 | ₹275 | 14% | ₹45.08 | ✅ | [view](https://myfitness.co.in/products/myfitness-chocolate-peanut-butter-crispy) |
| MyFitness Peanut Butter - Chocolate - 28% Protein - Smooth - Chocolate Peanut Butter Spread (510 g) | ₹319 | ₹275 | 14% | ₹45.08 | ✅ | [view](https://myfitness.co.in/products/myfitness-chocolate-peanut-butter-smooth) |
| MyFitness Peanut Butter - Original - 28% Protein - Crunchy - Classic Peanut Butter Spread (510 g) | ₹319 | ₹275 | 14% | ₹45.08 | ✅ | [view](https://myfitness.co.in/products/myfitness-original-peanut-butter-crunchy) |
| MyFitness Peanut Butter - Original - 28% Protein - Smooth - Classic Peanut Butter Spread (510 g) | ₹319 | ₹275 | 14% | ₹45.08 | ✅ | [view](https://myfitness.co.in/products/myfitness-original-peanut-butter-smooth) |
| MyFitness x Wonder Woman - Original Peanut Butter Smooth 510g - 29% Protein - High Protein (510g) | ₹379 | ₹279 | 26% | ₹54.71 | ✅ | [view](https://myfitness.co.in/products/myfitness-x-wonder-woman-original-peanut-butter-smooth-510g-29-protein-high-protein) |
| MyFitness Peanut Butter - Chocolate - 25% Protein - Almond Crunch - Chocolate Peanut Butter Spread (510 g) | ₹379 | ₹279 | 26% | ₹54.71 | ✅ | [view](https://myfitness.co.in/products/myfitness-chocolate-peanut-butter-with-almond-crunch) |
| MyFitness x Batman - Chocolate Zero Peanut Butter Extra Crunchy - 27% Protein - Zero Added Sugar - High Protein (510 g) | ₹369 | ₹299 | 19% | ₹58.63 | ✅ | [view](https://myfitness.co.in/products/myfitness-zero-chocolate-peanut-butter-crunchy-zero-sugar-extra-crunch-510g-27g-protein-10g-fiber-tasty-healthy-nut-butter-spread-cholesterol-free-zero-trans-fat-crunchy-peanut-butter) |

## Naturaltein

| Product | MRP | Price | Discount | ₹/100g (pack) | Stock | Link |
|---|---:|---:|---:|---:|:---:|---|
| The Protein Dessert E-Cook Book by Naturaltein | ₹599 | ₹399 | 33% | - | ✅ | [view](https://naturaltein.in/products/the-protein-dessert-e-cook-book-by-naturaltein) |
| Natural Plant Protein (Chocolate / 1 Box (500 g)) | ₹3,000 | ₹1,112 | 63% | ₹222.40 | ✅ | [view](https://naturaltein.in/products/plant-protein) |
| Natural Plant Protein (Mango / 1 Box (500 g)) | ₹3,000 | ₹1,112 | 63% | ₹222.40 | ✅ | [view](https://naturaltein.in/products/plant-protein) |
| Natural Plant Protein (Berry / 1 Box (500 g)) | ₹3,000 | ₹1,112 | 63% | ₹222.40 | ✅ | [view](https://naturaltein.in/products/plant-protein) |
| Natural Plant Protein (Pista / 1 Box (500 g)) | ₹3,000 | ₹1,112 | 63% | ₹222.40 | ✅ | [view](https://naturaltein.in/products/plant-protein) |
| Natural Plant Protein (Coffee / 1 Box (500 g)) | ₹3,000 | ₹1,112 | 63% | ₹222.40 | ✅ | [view](https://naturaltein.in/products/plant-protein) |
| Natural Whey Protein Concentrate (Italian Ice Cream / 1 Box (300 g)) | ₹1,424 | ₹1,299 | 9% | ₹433.00 | ❌ | [view](https://naturaltein.in/products/whey-protein-concentrate) |
| Natural Whey Protein Concentrate (Chocolate Biscoff / 1 Box (300 g)) | ₹1,424 | ₹1,399 | 2% | ₹466.33 | ❌ | [view](https://naturaltein.in/products/whey-protein-concentrate) |
| Natural Plant Protein (Chocolate / 2 Boxes (1 kg)) | ₹6,000 | ₹1,600 | 73% | ₹160.00 | ✅ | [view](https://naturaltein.in/products/plant-protein) |
| Natural Plant Protein (Mango / 2 Boxes (1 kg)) | ₹6,000 | ₹1,600 | 73% | ₹160.00 | ✅ | [view](https://naturaltein.in/products/plant-protein) |
| Natural Plant Protein (Berry / 2 Boxes (1 kg)) | ₹6,000 | ₹1,600 | 73% | ₹160.00 | ✅ | [view](https://naturaltein.in/products/plant-protein) |
| Natural Plant Protein (Pista / 2 Boxes (1 kg)) | ₹6,000 | ₹1,600 | 73% | ₹160.00 | ✅ | [view](https://naturaltein.in/products/plant-protein) |
| Natural Plant Protein (Coffee / 2 Boxes (1 kg)) | ₹6,000 | ₹1,600 | 73% | ₹160.00 | ✅ | [view](https://naturaltein.in/products/plant-protein) |
| Natural Whey Protein Isolate (Pista Kulfi / 1 Box (300 g)) | ₹1,780 | ₹1,775 | 0% | ₹591.67 | ❌ | [view](https://naturaltein.in/products/whey-protein-isolate) |
| Natural Whey Protein Isolate (Vanilla / 1 Box (300 g)) | ₹1,780 | ₹1,775 | 0% | ₹591.67 | ❌ | [view](https://naturaltein.in/products/whey-protein-isolate) |

## Nutrabay

| Product | MRP | Price | Discount | ₹/100g (pack) | Stock | Link |
|---|---:|---:|---:|---:|:---:|---|
| Nutrabay Gold Hydrolyzed Pea Protein | ₹69 | ₹49 | 29% | ₹122.50 | ✅ | [view](https://nutrabay.com/product/nutrabay-gold-hydrolyzed-pea-protein/?pId=3302532) |
| Nutrabay Pure Pea Protein Isolate | ₹669 | ₹549 | 18% | ₹109.80 | ✅ | [view](https://nutrabay.com/product/nutrabay-pure-100-pea-protein-isolate/?pId=4537768) |
| Nutrabay BioAbsorb™ Whey Protein Powder - Clinically Tested 54% Better Protein Absorption - 26g Protein/Scoop - India's 1st Protein with ProDiFi™ for No Bloating - No Added Sugar | ₹859 | ₹599 | 30% | ₹330.94 | ✅ | [view](https://nutrabay.com/product/nutrabay-bioabsorb-whey-protein/?pId=8042444) |
| TruNativ Plant Based Everyday Protein - Protein You Can Cook With! | ₹699 | ₹599 | 14% | ₹363.03 | ✅ | [view](https://nutrabay.com/product/trunativ-plant-based-everyday-protein-protein-you-can-cook-with/?pId=9485223) |
| Nutrabay Wellness Vegan Plant Protein Powder + Superfoods | ₹1,199 | ₹699 | 42% | ₹139.80 | ✅ | [view](https://nutrabay.com/product/nutrabay-wellness-vegan-plant-protein-powder-superfoods/?pId=4698878) |
| Nutrabay Gold Hydrolyzed Pea Protein | ₹1,049 | ₹799 | 24% | ₹159.80 | ✅ | [view](https://nutrabay.com/product/nutrabay-gold-hydrolyzed-pea-protein/?pId=3302532) |
| Nutrabay Gold Hydrolyzed Pea Protein | ₹1,049 | ₹799 | 24% | ₹159.80 | ✅ | [view](https://nutrabay.com/product/nutrabay-gold-hydrolyzed-pea-protein/?pId=3302532) |
| Nutrabay Gold Hydrolyzed Pea Protein | ₹1,049 | ₹799 | 24% | ₹159.80 | ✅ | [view](https://nutrabay.com/product/nutrabay-gold-hydrolyzed-pea-protein/?pId=3302532) |
| Nutrabay Pure Pea Protein Isolate | ₹1,349 | ₹849 | 37% | ₹84.90 | ✅ | [view](https://nutrabay.com/product/nutrabay-pure-100-pea-protein-isolate/?pId=4537768) |
| Nutrabay Pure Soy Protein Isolate | ₹1,349 | ₹899 | 33% | ₹89.90 | ✅ | [view](https://nutrabay.com/product/nutrabay-pure-100-soy-protein-isolate/?pId=4186049) |
| Nakpro Nutrition Platinum Soy Protein Isolate | ₹2,300 | ₹899 | 61% | ₹89.90 | ✅ | [view](https://nutrabay.com/product/nakpro-vegan-soy-protein-isolate-90-raw-pure-natural-vegetarian-plant-protein-supplement-powder/?pId=3990475) |
| Optimum Nutrition (ON) Gold Standard Whey Protein Powder | ₹1,079 | ₹999 | 7% | - | ✅ | [view](https://nutrabay.com/product/optimum-nutrition-on-100-whey-gold-standard-2/?pId=4471481) |
| Optimum Nutrition (ON) Gold Standard Whey Protein Powder | ₹1,079 | ₹999 | 7% | ₹644.52 | ✅ | [view](https://nutrabay.com/product/optimum-nutrition-on-100-whey-gold-standard-2/?pId=4471481) |
| Optimum Nutrition (ON) Gold Standard Whey Protein Powder | ₹1,079 | ₹999 | 7% | ₹644.52 | ✅ | [view](https://nutrabay.com/product/optimum-nutrition-on-100-whey-gold-standard-2/?pId=4471481) |
| Naturaltein Plant Protein | ₹3,000 | ₹999 | 67% | ₹199.80 | ✅ | [view](https://nutrabay.com/product/naturaltein-vegan-plant-protein/?pId=6742490) |

## OZiva

| Product | MRP | Price | Discount | ₹/100g (pack) | Stock | Link |
|---|---:|---:|---:|---:|:---:|---|
| Plant Protein + Pro-Digest (Chocolate) | ₹139 | ₹139 | 0% | - | ✅ | [view](https://oziva.in/products/plant-protein-pro-digest) |
| Plant Protein + Pro-Digest (Mango) | ₹139 | ₹139 | 0% | - | ✅ | [view](https://oziva.in/products/plant-protein-pro-digest) |
| Plant Protein + Pro-Digest (Vanilla) | ₹139 | ₹139 | 0% | - | ✅ | [view](https://oziva.in/products/plant-protein-pro-digest) |
| Plant Protein + ACV | ₹338 | ₹338 | 0% | - | ✅ | [view](https://oziva.in/products/protein-acv) |
| Pro-Collagen Protein Peptides Caramel - 250g | ₹799 | ₹433 | 46% | ₹173.20 | ✅ | [view](https://oziva.in/products/pro-collagen-protein-peptides-caramel-250g) |
| Vegan Collagen, Clinically Proven (Watermelon / Starter Pack-125g) | ₹499 | ₹459 | 8% | ₹367.20 | ✅ | [view](https://oziva.in/products/plant-based-collagen) |
| Plant Protein + Pro-Digest (Assorted) | ₹699 | ₹569 | 19% | - | ✅ | [view](https://oziva.in/products/plant-protein-pro-digest) |
| Plant Protein + Pro-Digest (Assorted / Starter Pack) | ₹699 | ₹569 | 19% | - | ✅ | [view](https://oziva.in/products/oziva-bioactive-plant-protein-with-25g-vegan-protein-5-5-bcaas-100-rda-vitamins-minerals-ayurvedic-herbs-for-better-endurance-stamina-muscle-recovery-1-kg) |
| Vegan Collagen, Clinically Proven (Guava Glow / Starter Pack) | ₹959 | ₹679 | 29% | - | ✅ | [view](https://oziva.in/products/plant-based-collagen) |
| Vegan Collagen, Clinically Proven (Classic / Starter Pack) | ₹959 | ₹679 | 29% | - | ✅ | [view](https://oziva.in/products/plant-based-collagen) |
| Vegan Collagen, Clinically Proven (Berry Orange / Starter Pack) | ₹959 | ₹679 | 29% | - | ✅ | [view](https://oziva.in/products/plant-based-collagen) |
| Vegan Collagen, Clinically Proven (Watermelon / Starter Pack) | ₹959 | ₹679 | 29% | - | ✅ | [view](https://oziva.in/products/plant-based-collagen) |
| Plant Protein + Pro-Digest - Assorted Flavours (Pack of 1 (5 Sachets)) | ₹699 | ₹699 | 0% | - | ✅ | [view](https://oziva.in/products/plant-protein-pro-digest-1) |
| Plant Protein + Pro-Digest - Assorted Flavours (Pack of 2 (10 Sachets)) | ₹699 | ₹699 | 0% | - | ✅ | [view](https://oziva.in/products/plant-protein-pro-digest-1) |
| Plant Protein + Pro-Digest (Strawberry) | ₹699 | ₹699 | 0% | - | ❌ | [view](https://oziva.in/products/plant-protein-pro-digest) |

## Wellbeing Nutrition

| Product | MRP | Price | Discount | ₹/100g (pack) | Stock | Link |
|---|---:|---:|---:|---:|:---:|---|
| Kids Protein Vanilla Free Sachet | ₹79 | ₹79 | 0% | - | ✅ | [view](https://wellbeingnutrition.com/products/kids-protein-vanilla-free-sachet) |
| Kids Protein Chocolate Sachet | ₹79 | ₹79 | 0% | - | ✅ | [view](https://wellbeingnutrition.com/products/kids-protein-chocolate-sachet) |
| Kids Protein Vanilla Sachet | ₹79 | ₹79 | 0% | - | ✅ | [view](https://wellbeingnutrition.com/products/kids-protein-vanilla-sachet) |
| Vegan Protein Dark Chocolate Hazelnut Sachet | ₹150 | ₹150 | 0% | - | ✅ | [view](https://wellbeingnutrition.com/products/vegan-protein-dark-chocolate-hazelnut-sachet) |
| Whey Protein Isolate Dark Chocolate Sachet (Pack of 1) | ₹160 | ₹160 | 0% | - | ❌ | [view](https://wellbeingnutrition.com/products/whey-protein-isolate-dark-chocolate-sachet) |
| Biofermented Yeast Protein Isolate 31g - 500g - Unflavoured (Pack of 1) | ₹1,799 | ₹1,529 | 15% | ₹305.80 | ✅ | [view](https://wellbeingnutrition.com/products/unflavoured-yeast-protein-powder-500g) |
| Plant Protein 22g - 500g - 3B CFU Probiotics - Dark Chocolate Hazelnut (Pack of 1) | ₹1,799 | ₹1,529 | 15% | ₹305.80 | ✅ | [view](https://wellbeingnutrition.com/products/vegan-protein-dark-chocolate-hazelnut) |
| Plant Protein 22g - 500g - 3B CFU Probiotics - Italian Cafe Mocha (Pack of 1) | ₹1,799 | ₹1,529 | 15% | ₹305.80 | ❌ | [view](https://wellbeingnutrition.com/products/vegan-protein-italian-cafe-mocha) |
| Plant Protein 22g - 500g - 3B CFU Probiotics - Belgian Dark Chocolate (Pack of 1) | ₹1,799 | ₹1,529 | 15% | ₹305.80 | ❌ | [view](https://wellbeingnutrition.com/products/vegan-protein-belgian-chocolate) |
| Plant Protein 22g - 500g - 3B CFU Probiotics - French Vanilla Caramel (Pack of 1) | ₹1,799 | ₹1,529 | 15% | ₹305.80 | ✅ | [view](https://wellbeingnutrition.com/products/vegan-protein-french-vanilla-caramel) |
| Plant Protein 22g - 500g - 3B CFU Probiotics - Canadian Mixed Berry (Pack of 1) | ₹1,799 | ₹1,529 | 15% | ₹305.80 | ✅ | [view](https://wellbeingnutrition.com/products/vegan-protein-canadian-mixed-berry) |
| Her Superfood Plant Protein - Chocolate Peanut Butter (Pack of 1) | ₹1,799 | ₹1,529 | 15% | - | ✅ | [view](https://wellbeingnutrition.com/products/superfood-plant-protein-powder-for-women) |
| Superfood Plant Protein - British Banoffee Pie (Pack of 1) | ₹1,799 | ₹1,529 | 15% | - | ✅ | [view](https://wellbeingnutrition.com/products/superfood-plant-protein-powder-in-banoffee-pie) |
| Biofermented Yeast Protein Isolate 24g- 500g -2B CFU Probiotics- 3 Digestive Enzymes - French Vanilla (Pack of 1) | ₹1,899 | ₹1,614 | 15% | ₹322.80 | ✅ | [view](https://wellbeingnutrition.com/products/yeast-protein-powder-french-vanilla-500g) |
| Biofermented Yeast Protein Isolate 24g- 500g -2B CFU Probiotics- 3 Digestive Enzymes -Mixed Berry (Pack of 1) | ₹1,899 | ₹1,614 | 15% | ₹322.80 | ✅ | [view](https://wellbeingnutrition.com/products/yeast-protein-powder-mixed-berry-500g) |


*₹/100g is price per 100g of product weight, not per gram of protein (macros aren't available from these feeds). Prices are snapshots at check time and may have changed since — always verify on the retailer's site.*
