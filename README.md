# Evangelion-Dataset

Description
Synthesized from the Neon Genesis Evangelion TV series (1995), The End of Evangelion (1997), the Rebuild of Evangelion movie tetralogy (2007–2021), and the original manga by Yoshiyuki Sadamoto. It has been refined to reflect psychological profiling and trauma intensities.

Format
A tibble with 50+ rows and 11 variables:
Name: Name of the character, Angel, or Evangelion Unit.
Height: Height of the entity. Numerical (cm) for humans; categorical ("Colossal" or "Variable") for Angels and Eva Units.
Eye_Color, Hair_Color: Physical descriptions of the entity. "None" for non-humanoid species.
Species: The biological or metaphysical origin (e.g., Human, Angel, Cyborg, Penguin).
Gender: The gender identity or biological sex. "None" for Angels and machines.
Origin: Country of origin or the "Moon" of birth (White Moon/Black Moon).
Roles: Primary functions held by the character (e.g., Pilot, Scientist).
Psychological_Conditions: A list-column of diagnosed or observed mental health markers (e.g., Hedgehog's Dilemma).
Trauma_Intensity: A categorical ranking (High, Medium, Low, None) based on the entity's history of emotional or physical stressors.
Character_Appearances: A comma-separated list of primary keys identifying appearances in episodes (Ep:X), movies (Movie:X), and manga (Vol.X). 
