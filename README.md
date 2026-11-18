# Pizza sales dashboard in Power BI

A Power BI analysis project with report files, source CSV tables, project-note screenshots and an accompanying presentation.

## Explore the report

Open either `.pbix` file in Power BI Desktop:

- `pizza_sales project.pbix`
- `pizza_sales project2.pbix`

The repository does not document which file is the final version or the differences between them. Neither is presented here as a newly verified canonical version.

If Power BI prompts for missing local data, update the source paths to the CSV files in the `pizza_sales` folder and refresh the report. No credentials should be required for those local CSV files.

## Data and files

| File | Contents |
| --- | --- |
| `pizza_sales/orders.csv` | Order records |
| `pizza_sales/order_details.csv` | Line items linking orders and pizzas |
| `pizza_sales/pizzas.csv` | Pizza IDs, sizes and prices |
| `pizza_sales/pizza_types.csv` | Pizza names, categories and ingredients |
| `data_dictionary.csv` | Field descriptions |
| `Pizza Sales Dashboard.pptx` | Project presentation |
| `Screenshot 2024-05-22 *.png` | Existing project-note screenshots |
| `link for data set.txt` | Original data-source reference |

## Project-note previews

These existing screenshots show analysis questions, transformation steps and the project workflow. They are not dashboard-result screenshots or newly generated performance results.

![Pizza sales project notes 1](<Screenshot 2024-05-22 204112.png>)

![Pizza sales project notes 2](<Screenshot 2024-05-22 204253.png>)

![Pizza sales project notes 3](<Screenshot 2024-05-22 204337.png>)

## Data source and scope

The existing source-reference file points to the [Maven Analytics Data Playground](https://www.mavenanalytics.io/data-playground?dataStructure=Multiple%20tables&order=date_added%2Cdesc&tags=Business). That link is retained as provenance, not a claim that the dataset's current download or licensing terms were verified.

The repository is an analysis exercise, not evidence of a live restaurant's commercial performance. No new revenue, growth or accuracy claims are added by this README. The Power BI files have not been opened or refreshed during this documentation update.
