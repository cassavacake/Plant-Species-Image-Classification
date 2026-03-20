<img width="750" height="751" alt="image" src="https://github.com/user-attachments/assets/002bdad9-1424-4e13-9ffd-b6aa90769827" /># Plant-Species-Image-Classification
# A. Project Overview
This project introduces a supervised learning-based multi-class image classification model developed to recognize and categorize 20 different plant species using leaf and plant images. The model was created using Google Teachable Machine, a user-friendly, web-based platform that allows the development of machine learning models without requiring advanced programming skills.

The main goal of this system is to streamline and automate the process of plant species identification through visual data. When a plant image is provided, the trained model analyzes it and predicts the appropriate species category along with a confidence score indicating the reliability of the prediction. This system can be applied in various fields, including botanical studies, biodiversity conservation, agricultural analysis, and educational environments that require quick and accurate plant identification.

The dataset used in this project consists of 5,508 images divided into 20 plant species categories. Each category contains approximately 250 to 375 labeled images, ensuring balanced representation for effective training and evaluation. The entire process—training, validation, and testing—was carried out within the Google Teachable Machine platform, after which the model was exported for deployment and further use.

# B. Plant Species
The following section documents each of the 20 plant species classes used in this classification model. For every species, a representative image, the common and scientific names, and a brief academic description are provided.

# 1. Ostrich fern
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/2479442d-d976-416e-8217-b02fc1e9ad5e" />

Attribute	                Detail
Common Name	           Ostrich fern
Scientific Name	       Matteuccia struthiopteris

Description: The fronds are dimorphic, with the deciduous green sterile fronds being almost vertical, 100–170 cm (39–67 in) tall[5] and 20–35 cm (7.9–13.8 in) broad, long-tapering to the base but short-tapering to the tip,[5] so that they resemble ostrich plumes, hence the name.[6] The fertile fronds are shorter, 40–65 cm (16–26 in) long, brown when ripe,[5] with highly modified and constricted leaf tissue curled over the sporangia; they develop in autumn, persist erect over the winter and release the spores in early spring. Along with Dryopteris goldieana, it is one of the largest species of fern in eastern North America

# 2. Water Fern
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/4af26956-8489-4d76-823a-b42bc6f1e856" />

Attribute	                Detail
Common Name	           Water Fern 
Scientific Name	        Azolla

Description: Azolla (commonly called mosquito fern, water fern, and fairy moss) is a genus of seven species of aquatic ferns in the family Salviniaceae. They are extremely reduced in form and specialized, having a significantly different appearance to other ferns and more resembling some mosses or even duckweeds. Azolla filiculoides is one of two fern species for which a reference genome has been published.[3] It is believed that this genus grew so prolifically during the Eocene (and thus absorbed such a large amount of carbon) that it triggered a global cooling event that has lasted to the present.

# 3. Pacific Maidenhair
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/2e515921-60fd-49ae-82ac-ea94a4c0bcdf" />

Attribute	                Detail
Common Name	           Pacific Maidenhair
Scientific Name	        Adiantum raddianum

Description: The Pacific Maidenhair (Adiantum raddianum), often sold as 'Pacific Maid,' is a popular indoor fern featuring delicate, bright green fronds on wiry black stems. Thriving in high humidity, it requires bright indirect light (or part/full shade) and consistent moisture. These ferns are non-toxic to pets and grow well in terrariums or bathrooms.

# 4. Fritz Luthii' Delta Maidenhair Fern
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/49855345-fb9b-4a1a-9050-d23d7af5c4e9" />
,
Attribute	                Detail
Common Name	            Fritz Luthii' Delta Maidenhair Fern
Scientific Name	        Adiantum raddianum 

Description: This lovely cultivar of A. raddianum has a distinct, large triangular shaped blade.  The pinnae are larger and more deeply lobed than on the cultivars A. raddianum ‘Brilliantelse’ and A. raddianum variegatum ‘Snowflake’, with more space between the segments.  It is more compact than A. raddianum and is noted to have stiffer stipes, which make its fronds slightly more resistant to breaking in rain and wind.  New growth emerges a bright green and fades to a blue-green as the fronds mature.  In our trials ‘Fritz Luthii’ preferred shadier conditions than both ‘Brilliantelse’ and ‘Snowflake’, since it does not produce as much pigment to protect its new fronds, making it an excellent choice for filtered shade or as a houseplant.  For best results water lightly at the base and avoid repeated saturation of the fronds.  For outdoor cultivation situate near the top or middle of a slope; when watering saturate the soil uphill from the fern so it percolates down and avoid frequent overhead watering of the fronds.

# 5.  Fine Maidenhair ferns
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/75ea3d5c-e6fb-4370-bbbf-92dce6ae376e" />

Attribute	                Detail
Common Name	            Maidenhair ferns
Scientific Name	        Adiantum raddianum

Description: Maidenhair ferns (Adiantum spp.) are delicate-looking, shade-loving plants prized for their fine, airy fronds and dark, wiry stems. They require consistent moisture, high humidity, and bright, indirect light to thrive, typically growing 12–18 inches high, though some varieties differ.

# 6. Lemon Button
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/b72b3974-e5a5-4de1-8fe6-b9b7f37d1978" />

Attribute	                Detail
Common Name	            Lemon Button
Scientific Name	       Fern Nephrolepsis cordifolia 'Duffii'

Description:"Lemon Button" is a dwarf variety of the common Boston Fern that shares its resilience and ease of cultivation indoors. Its leaves give off a slight lemony scent during spring and summer, making a really cool addition as an indoor plant for your desk or side table.

# 7. Sickle Fern
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/f7c0e9bd-3c2e-4f40-b2a7-21e576f2814b" />

Attribute	                Detail
Common Name	            Sickle Fern
Scientific Name	        Pellaea falcata

Description: Pellaea falcata (Sickle Fern) is a hardy, evergreen, rhizomatous fern native to eastern Australia, featuring dark green, leathery, sickle-shaped leaflets. Ideal for shade gardens or as a tough houseplant, it thrives in moist, well-drained, nutrient-rich soil and bright, indirect light.

# 8. Hairy Lip Fern
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/4501d477-15c4-4311-8b6e-61307a34e58f" />

Attribute	                Detail
Common Name	            Hairy Lip Fern
Scientific Name	        Myriopteris lanosa, formerly Cheilanthes lanosa

Description: The Hairy Lip Fern (Myriopteris lanosa, formerly Cheilanthes lanosa) is a hardy, drought-tolerant, evergreen fern native to the eastern US, growing 6–14 inches tall. It features olive-green, soft, hair-covered fronds with dark stems, thriving in full sun to part shade and rocky, well-drained soils.

# 9. Korean Rock Fern
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/8706a885-d67e-4b7b-b7cc-bf86f463ed84" />

Attribute	                Detail
Common Name	            Korean Rock Fern
Scientific Name	        Polystichum tsus-simense

Description: Korean Rock Fern (Polystichum tsus-simense) is a small, evergreen, shade-loving perennial native to East Asia, featuring glossy, dark green fronds with black stems and a compact, 12–18 inch, clumping habit. Award-winning and low-maintenance, it is ideal for rock gardens, containers,

# 10. Japanese Holly Fern
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/aa97df3f-f580-4d94-9e6b-0a0457d75227" />

Attribute	                Detail
Common Name	           Japanese Holly Fern
Scientific Name	        Cyrtomium falcatum,

Description: Cyrtomium falcatum, or Holly Fern, is an evergreen fern with glossy, holly-like fronds. It thrives in shaded or partially shaded areas and is adaptable to various growing conditions. Holly Fern is often used as a ground cover or border plant, adding texture and elegance to gardens. It requires regular watering and is relatively low-maintenance. With its attractive foliage, it is a popular choice for both outdoor and indoor landscaping.

# 11.  Western swordfern
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/e5012e47-561d-4908-895f-dc2693ea5dc2" />

Attribute	                Detail
Common Name	            Western swordfern
Scientific Name	         Polystichum munitum

Description: Polystichum munitum, the western swordfern,[1] is an evergreen perennial fern native to western North America, where it is one of the most abundant ferns in forested areas. It occurs along the Pacific coast from southeastern Alaska to southern California, and also inland east to southeastern British Columbia, northern Idaho and western Montana, with disjunctive populations in northern British Columbia, Canada; the Black Hills in South Dakota, United States; and Guadalupe Island off of Baja California, Mexico. Western swordfern is known to have locally naturalized in parts of Great Britain and Ireland

# 12.  Tassel Fern
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/c59beeef-562d-4d4d-a526-224ccefdaba0" />

Attribute	                Detail
Common Name	            Tassel Fern
Scientific Name	        terrestrial Polystichum polyblepharum

Description: Tassel ferns are unique,, slow-growing plants with a distinctive, cascading, or upright, tassel-like foliage, often used as ornamental houseplants or in shade gardens. Primarily, they are recognized either as epiphytic Huperzia species (often grown in hanging baskets) or the hardy, terrestrial Polystichum polyblepharum (Japanese tassel fern)

# 13. Brake ferns or Table ferns
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/9925156f-e5ec-4867-9fee-8ca53d7ce6e8" />

Attribute	                Detail
Common Name	           Brake ferns or Table ferns
Scientific Name	         Pteris

Description: Pteris tremula is a terrestrial fern, with its fronds arising from the ground up to 1.3 m (4.3 ft), rarely up to 2 m (6.6 ft) tall. The stipe is brown. The light green lacy compound fronds may reach 2 m (6.6 ft) in length and are 3-pinnate or more. The brownish sori line the undersides of the frond margins. Unlike Pteris vittata and other Pteris species, it is not able to hyperaccumulate arsenic and is damaged by levels as low as 25 mg/kg in the soil. The plant contains two cytotoxic indanonic sesquiterpenes.

# 14. Common Rasp Fern 
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/c7508ea1-74f8-4d5a-b6e0-b27ef6b64da6" />

Attribute	                Detail
Common Name	           Common Rasp Fern 
Scientific Name	         Blechnum parrisiae

Description: The Common Rasp Fern (Doodia media, also known as Blechnum parrisiae or hacksaw fern) is a hardy, evergreen perennial native to Australia, New Zealand, and the Pacific Islands. It grows 6–18 inches tall and spreads up to 3 feet, featuring tough, raspy fronds that turn pink or red when young.

# 15. Mother Fern
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/fd444974-13e6-4d84-84bc-929e91a1d26d" />

Attribute	                Detail
Common Name	           Mother Fern
Scientific Name	       Asplenium bulbiferum 

Description: The Mother Fern (Asplenium bulbiferum), also known as hen and chickens fern, is a, hardy, evergreen fern native to New Zealand, popular for its lacy, bright green fronds and unique ability to grow miniature plantlets (babies) directly on its leaves. It thrives in shade, prefers moist soil, and makes an excellent, low-maintenance houseplant or container plant.

# 16. East Indian Holly Fern
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/ad65fcca-ed48-47e5-ac7b-82834168725a" />

Attribute	                Detail
Common Name	            East Indian Holly Fern
Scientific Name	        Arachniodes simplicior 'Variegata'

Description: The East Indian Holly Fern (Arachniodes simplicior 'Variegata'*) is a top choice for indoor or shade gardening, featuring glossy green fronds with a distinctive gold stripe. It thrives in moist, well-drained soil, is deer-resistant, and thrives in USDA Zones 7–10. It’s an evergreen, low-maintenance plant that adds year-round color.

# 17. Button Fern
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/6a6d4401-fe88-481f-bcb9-1053970d6e0a" />

Attribute	                Detail
Common Name	            Button Fern
Scientific Name	        Pellaea rotundifolia

Description: The Button Fern (Pellaea rotundifolia) is a compact, slow-growing houseplant known for its small, round, forest-green leaflets resembling buttons on arching fronds. Thriving in high humidity and moderate temperatures , it requires bright, indirect light and consistent moisture, making it ideal for terrariums, north-facing windowsills, or hanging baskets.

# 18. Royal fern
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/6adc2aef-220e-4cd7-931d-5a5a7d2d88d4" />

Attribute	                Detail
Common Name	            Royal fern
Scientific Name	        Osmunda regalis

Description: Royal fern is a large perennial herb with stout ascending rhizomes that over many years build up a woody, trunk-like base covered by interwoven roots, 1 m or more high. The fronds, or leaves, arise directly from this rhizome and are very large, typically up to 120 cm but exceptionally as much as 400 cm long and 30-40 cm broad. Each frond is bipinnate, with 5–9 pairs of pinnae up to 30 cm (12 in) long, each pinna with 7–13 pairs of pinnules 2.5–6.5 cm (0.98–2.56 in) long and 1–2 cm (0.39–0.79 in) broad. Many of the fronds have a terminal fertile portion, where the blade is reduced almost to the midrib and densely covered with brown sporangia.

# 19.  Selaginella
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/bc62074d-86b5-4e3b-8230-7fed82e3631f" />

Attribute	                Detail
Common Name	            Selaginella
Scientific Name	       spikemoss or lesser clubmoss

Description: Selaginella, commonly known as spikemoss, is a genus of vascular, non-flowering plants related to ferns rather than true mosses. These moisture-loving, delicate plants feature trailing or erect stems with scale-like leaves and are popular in terrariums or as indoor plants. They require high humidity, consistent moisture, and bright, indirect light

# 20. Baby Tears
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/a6ccf057-23f1-4cbf-8246-db7f74361153" />

Attribute	                Detail
Common Name	            Baby Tears
Scientific Name	        Soleirolia soleirolii

Description: Baby Tears (Soleirolia soleirolii) is a popular, low-growing, creeping herbaceous perennial known for its tiny leaves and moss-like appearance, often used as a houseplant, in terrariums, or as a shade-loving ground cover. Thriving in high humidity, indirect light, and consistently moist soil, it grows up to 4 inches tall and spreads extensively, making it ideal for hanging baskets or cascading over container edges
