# Book-Recommendation-System
## Description :books:
This project aims to develop a book recommendation system using the **[Goodbooks-10K dataset](https://github.com/zygmuntz/goodbooks-10k)**.  
The primary goal is to enhance the reading experience by providing personalized book recommendations through:
- **Item-based collaborative filtering**
- **User-based collaborative filtering**

By employing advanced collaborative filtering techniques, the project seeks to significantly improve user
engagement and satisfaction with tailored book suggestions.

## Methods and Approach :bulb:
The methodology adopted for this project involving several
critical stages:  
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Algorithm Selection Implementation and Optimization

## How to Use it :gear:
Enter the book name and the number of book recommendations with the following command in the last cell of [jupyternotebook](./notebooks/1.0-thc-Item_Based_Recommender_System.ipynb):
```
get_recommendations({Book Name}, books_info, 'Adjusted_Cosine', {Number of Recommendation})
```
## Technologies :desktop_computer:
- Python 3.8
- Pandas, Numpy, Scikit-learn, Matplotlib

## Future Works :memo:
1. Implementing hybrid approaches that combine user-based and item-based
collaborative filtering
2. Update Project Structure
3. Build a Discord Bot with interactive features

