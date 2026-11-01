# Zadania rekrutacyjne – LLM

### Zadanie 1
Uruchomiłam model Qwen 3.5 2B w Google Colab (karta T4) przy użyciu narzędzia `ms-swift` i przetestowałam inferencję dla różnego poziomu temperatury (0, 1, 10, 1000).

### Zadanie 2
Przeprowadziłam fine-tuning LoRA modelu Qwen 3.5 2B na zbiorze `medalpaca/medical_meadow_wikidoc_patient_information`. 
* **Co udało się zrobić:** Udało mi się rozwiązać problemy z VRAM-em i ścieżkami, pomyślnie został przeprowadzony trening demonstracyjny (30 kroków w ~12 minut), uzyskując spadek loss z 2.45 do 1.84 oraz wagi w checkpoint-30.
* **Czego nie udało się zrobić** Ze względu na brak czasu nie udało mi się wykonać automatycznej ewaluacji ilościowej z użyciem metryk ROUGE i BLEU
* 
