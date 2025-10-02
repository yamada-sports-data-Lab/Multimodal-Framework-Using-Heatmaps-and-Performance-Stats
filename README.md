# Multimodal-Framework-Using-Heatmaps-and-Performance-Stats
This repository is for MIT Sloan Sports Analytics research paper.

# Multimodal Framework Using Heatmaps and Performance Stats

This repository supports the MIT Sloan Sports Analytics Conference research submission.  
It contains code and data for positional classification in football using both heatmap images and performance statistics.

---

## 📁 Repository Structure

FileDescription
1. MIT1_Aggregate Player Stats on World cup |Extracts player-level stats from event data
2. MIT2_Aggregating_Mean_Tactical_KPIs_by_Position |Computes per-minute KPIs by position
3. MIT3_Generating_and_Flipping_Heatmaps` | Creates and vertically flips pass heatmaps
4. MIT4_Positional_Classification_by_Heatmap_CNN` | CNN-based classification using heatmap images
5. MIT5_Random_Forest_Classification_of_KPI` | Random Forest classification using stats only
6. MIT6_Multimodal_Classification_by_Heatmap_and_KPI` | Combines image and stats for multimodal classification
7. LICENSE | MIT License |
8. README.md` | This file |

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
