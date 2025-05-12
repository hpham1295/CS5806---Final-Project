# CS5806 — Final Project  
## Quantifying Urban Heat Island Trends in the Appalachian Region Using Machine Learning and Geographically Weighted Regression

---

## Authors

- **Shashank Karki**  
  Virginia Tech, USA  
  [shashankkarki@vt.edu](mailto:shashankkarki@vt.edu)

- **Sonia Sharma**  
  Virginia Tech, USA  
  [soniasharma07@vt.edu](mailto:soniasharma07@vt.edu)

- **Nitant Rai**  
  Virginia Tech, USA  
  [nitant3@vt.edu](mailto:nitant3@vt.edu)

- **Huy Pham**  
  Virginia Tech, USA  
  [phamanhuy@vt.edu](mailto:phamanhuy@vt.edu)

---

Urban Heat Islands (UHI)—where urban areas experience significantly higher temperatures than surrounding rural regions—pose serious environmental and public health challenges, particularly in rapidly urbanizing areas. Despite its ecological, economic, and historical significance, the Appalachian region has been largely overlooked in large-scale UHI modeling efforts.

This project addresses that gap by developing a novel, high-resolution, spatially enriched dataset covering 13 Appalachian states. The dataset integrates satellite remote sensing data, topographic features, infrastructural layers, and demographic attributes. Using this comprehensive dataset, we evaluate the performance of two machine learning models—**Gradient Boosting (GB)** and **Random Forest (RF)**—alongside **Geographically Weighted Regression (GWR)**, a spatially explicit non-ML method, to model and interpret UHI intensity.

**Key findings:**
- RF slightly outperforms GB in predictive accuracy (RMSE: 2.579 vs. 2.594; R²: 0.5531 vs. 0.5475).
- GWR achieves moderate predictive performance (RMSE = 2.29, R² = 0.65) while offering stronger spatial interpretability, revealing local relationships between UHI and factors like NDVI, population density, and land surface temperature.

This hybrid approach demonstrates the value of combining predictive modeling with spatial diagnostics to support targeted UHI mitigation strategies in complex regions like Appalachia.

---

## Repository Structure

All code is organized into five Jupyter notebooks, located in the `/notebooks` folder. The dataset is available under `/data/raw`.

### Jupyter Notebooks:
- `01_data_preprocessing.ipynb` — Data cleaning and preprocessing  
- `02_data_analysis.ipynb` — Exploratory data analysis  
- `03_gradient_boosting.ipynb` — Gradient Boosting implementation  
- `04_random_forest.ipynb` — Random Forest implementation  
- `05_geographically_weighted_regression.ipynb` — GWR implementation  

---

## Resources
- 📍 **[Project Website](https://mesonia07.wixsite.com/mlproject)**  
- 📄 **[Final Report (PDF)](ML_2_Final_Report.pdf)**
