# Multimodal-Framework-Using-Heatmaps-and-Performance-Stats
This repository is for MIT Sloan Sports Analytics research paper.

# Multimodal Framework Using Heatmaps and Performance Stats

This repository supports the MIT Sloan Sports Analytics Conference research submission.  
It contains code and data for positional classification in football using both heatmap images and performance statistics.

---

## 📁 Repository Structure

File NameDescriptionMIT1_Aggregate_Player_Stats_on_World_Cup.ipynbExtracts player-level stats from event dataMIT2_Aggregating_Mean_Tactical_KPIs_by_Position.ipynbComputes per-minute KPIs by positionMIT3_Generating_and_Flipping_Heatmaps.ipynbCreates and vertically flips pass heatmapsMIT4_Positional_Classification_by_Heatmap_CNN.ipynbCNN-based classification using heatmap imagesMIT5_Random_Forest_Classification_of_KPI.ipynbRandom Forest classification using stats onlyMIT6_Multimodal_Classification_by_Heatmap_and_KPI.ipynbCombines image and stats for multimodal classificationLICENSEMIT License| `README.md` | This file |
---

## 🚀 How to Run (Google Colab Recommended)

1. Open each notebook in [Google Colab
2. Mount your Google Drive.
3. Ensure the following folders and files are available:
   - `/content/drive/MyDrive/MIT_Sloan/heatmaps_all/` (heatmap images)
   - `/content/drive/MyDrive/MIT_Sloan/position_stats_mean_per_min_small_class.csv` (stats CSV)
4. Run notebooks in order from MIT1 to MIT6.

---

## 📊 Key Features

- Positional classification using CNN and Random Forest
- Tactical KPI normalization and visualization
- Multimodal fusion with gated attention
- Evaluation metrics: Accuracy, F1-score, ROC AUC, Confusion Matrix

---

## 📜 License

This project is licensed under the MIT License.  
See the LICENSE file for details.
