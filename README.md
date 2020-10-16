# stock_dashboard
A simple streamlit dashboard to show stockprices


Follwing the tutorial of the "Data Professor" on Youtube [for a Streamlit Stock Web App](https://www.youtube.com/watch?v=JUSFaWkAASI&list=PLtqF5YXg7GLmCvTswG32NqQypOuYkPRUE&index=10) I created a version of the WebApp that functions a little differently.
I use Plotly instead of matplotlib to give the user more interactivity, and the possibility to see the exact closing point for any given date. I also opted for a direct selection of the company instead of displaying X number of companies for a given selected sector. Finally I decided to make the data-table display optional.


If you have streamlit installed you can run the app locally. Use your terminal or (conda)prompt navigate to the directory and run: streamlit run dashboard.py