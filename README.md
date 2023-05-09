# Stock-Price-Prediction
Stock price prediction model using XGBoost
Using XGBoost algorithm, this code imports various Python libraries that are required for a machine learning project involving time series analysis, visualization, and modeling.

Data science libraries such as NumPy, Pandas, Matplotlib, and XGBoost comprise the first import block. NumPy and Pandas are used for data manipulation and analysis. Machine learning algorithms such as XGBoost are commonly used in regression, classification, and ranking. Visualizations can be created with Matplotlib, a plotting library.

In the second block of imports, additional visualization libraries are included that are useful for creating interactive and dynamic charts. Plotly, Plotly.io, and Plotly.graph_objects are among them. In a figure, the make_subplots function creates subplots. To work offline, the offline module of Plotly is used, and to download the JavaScript file for Plotly, the download_plotlyjs function is used.

Using the STL decomposition method, the third block of imports decomposes time series. Time series data can be broken down into trends, seasonal components, and residual components using STL decomposition.

Scikit-Learn’s warnings are muted by the fourth block of imports.

Last but not least, we initialize the notebook mode and change the default background color for all visualizations in Plotly. Additionally, it creates a custom visualization template called ‘my_template’ that can be used for all future visualizations.
