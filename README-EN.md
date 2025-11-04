<div align="center">

<img src="logs/log.jpeg" alt="Logo" width="30%">

[English](./README-EN.md) | [中文文档](./README.md)

</div>

# Pig Weight Estimation Task - Leaderboard

Welcome to the **Pig Weight Estimation Task Leaderboard**!  
This project presents the latest research performance on the pig weight estimation task and ranks them based on evaluation metrics such as MAPE and RMSE.

## Todolist
### 1. Data and Metrics Display
- [x] Leaderboard website setup  
- [ ] Collect and organize public results from research teams  

### 2. Page Optimization / Frontend Enhancement
- [x] Add auto-refresh function (update daily)  
- [x] Support metric sorting (click column headers)  
- [ ] Support filtering by modality (RGB, Depth, Thermal, etc.)  
- [ ] Add tooltip or abstract pop-ups for each method  

### 3. Content Update
- [ ] Add paper and code links for leaderboard entries  
- [ ] Add "Method Description" and "Dataset Introduction" sections  
- [ ] Compile reference list (with DOI / arXiv links)  

### 4. Future Work
- [ ] Open leaderboard submission interface (PR / JSON format submission)  

---

## Task Description

The goal of this task is to estimate pig body weight based on various sensor data (e.g., RGB images, depth maps, etc.).  
Participants are required to develop models that accurately predict pig weight and provide their evaluation results.

## Leaderboard
![Leaderboard](logs/1.jpeg)

## Evaluation Metrics

We use the following metrics to evaluate model performance:

- **MAPE** (Mean Absolute Percentage Error): Average percentage difference between predicted and actual values.  
- **RMSE** (Root Mean Squared Error): Root mean square of the prediction error.  
- **MAE** (Mean Absolute Error): Average absolute difference between predicted and actual values.  
- **R²**: Coefficient of determination between predictions and ground truth.

## Dataset

The dataset includes images of different pigs with corresponding weight data, covering multiple postures and environmental conditions.  
For detailed dataset information, please refer to the [Dataset Link](https://example.com).

## Contributors

Thanks to the following contributors for their efforts on this project.  
Contributions are always welcome!

- Peiguang Xin (xin1099477816@163.com)
