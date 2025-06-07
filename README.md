# SmartUA Anomaly Detection Training Data
This dataset was compiled as part of the Smart University project at the University of Alicante. It was used to train and validate the eCAD system (Electricity Consumption Anomaly Detector), aimed at detecting anomalous electricity consumption in university buildings.

## 📅 Date Range
- From: January 1, 2022
- To: June 24, 2023

## 📊 Dataset Summary
- **Samples:** 50,000
- **Attributes:** 10 features + 1 label
- **Format:** CSV
- **Target variable:** `incidence` (0 = normal, 1 = anomaly)

## 📑 Columns Description

| Column                  | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| `num_wifi_conn`         | Number of active Wi-Fi connections detected in the space                    |
| `time`                  | Time of day in fractional hours (e.g., 0.25 = 00:15h)                        |
| `day`                   | Day of the week (0 = Sunday, 6 = Saturday)                                  |
| `month`                 | Month (0 = January, 11 = December)                                          |
| `career_type`           | Encoded academic program type (e.g., undergraduate, master)                 |
| `type_teaching`         | Teaching modality (e.g., lecture, lab, seminar)                             |
| `type_grade`            | Encoded study field                                                         |
| `academic_year`         | Encoded academic year (e.g., 0 = first year)                                |
| `electricity_consumption` | Energy consumption in Wh                                                   |
| `incidence`             | Label indicating normal (0) or anomalous (1) behavior                       |

## 📥 Usage
This training dataset supports research on anomaly detection in smart buildings using machine learning techniques.

## 📘 Citation
If you use this dataset, please cite the corresponding publication describing the eCAD system.

## 📄 License
This dataset is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0).  
See the [LICENSE](./LICENSE) file for details.
