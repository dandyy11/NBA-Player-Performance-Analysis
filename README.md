# NBA-Player-Performance-Analysis
Comprehensive analysis of NBA player performance using the all_seasons dataset. Includes descriptive analysis of player metrics, diagnostic analysis of performance against age and height, and predictive modeling to estimate points per game based on age, height, and weight. 

### Dataset
- **All Seasons Dataset:** A dataset containing player performance metrics and physical attributes across multiple seasons, including age, height, weight, points, rebounds, and assists.
- 
### Objectives
1. **Descriptive Analysis:** Provide an overview of player metrics, including average age, height, weight, points, rebounds, and assists. Analyze player distribution by team and country.
2. **Diagnostic Analysis:** Explore relationships between player performance (points, rebounds, and assists) and age using scatter plots and regression lines. Investigate the correlation between player height and rebounds.
3. **Predictive Analysis:** Develop a linear regression model to predict a player's points per game based on age, height, and weight. Evaluate model performance using metrics like Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).

### Repository Structure
- `NBA-Player-Performance-Analysis.Rmd` - R Markdown file for descriptive analysis, including summary statistics and distribution analysis, diagnostic analysis, including scatter plots and regression analysis of player performance, predictive modeling using linear regression.
- `Detailed_Report.pdf` - PDF file with a comprehensive report summarizing all analyses and findings.


### Findings
1. **Descriptive Analysis:** 
   - The average age of players is 27.0 years, with an average height of 200.6 cm and an average weight of 100.3 kg.
   - The top 5 teams by player count include CLE, TOR, MIA, DAL, and WAS.
   - The majority of players are from the USA, followed by Canada, France, Australia, and Spain.
   
2. **Diagnostic Analysis:** 
   - Player performance metrics (points, rebounds, assists) show varied relationships with age, suggesting optimal performance peaks at certain ages.
   - A positive correlation exists between player height and rebounds, indicating taller players are more likely to secure rebounds.
   
3. **Predictive Analysis:** 
   - A linear regression model was developed to predict a player's points per game based on age, height, and weight.
   - The model achieved an RMSE of 6.04, indicating moderate predictive accuracy. Coefficients suggest a small positive influence of age and weight, while height shows a negative influence on points per game.

### Conclusion
The analysis of NBA player performance reveals several insightful trends and relationships. Descriptive statistics provide a solid understanding of player demographics, including their average age, height, and weight, along with team and country distributions. In diagnostic analysis, relationships between player performance and attributes like age and height illustrate how these factors influence scoring, rebounding, and assisting capabilities. The analysis suggests that performance tends to peak at specific age ranges and that taller players generally secure more rebounds.

The predictive model, while moderately accurate, provides a baseline understanding of how age, height, and weight may impact points per game. Although the model shows a limited predictive accuracy, with an RMSE of 6.04, it highlights that age and weight have a slight positive impact on scoring, whereas height presents a minor negative influence. Future modeling approaches could explore more complex techniques to improve accuracy and incorporate additional player performance metrics.


### How to Use
To reproduce the analyses, clone this repository and open the R Markdown files (`.Rmd`). You can knit these files in RStudio to generate the HTML or Markdown outputs.
```bash
# Clone the repository
https://github.com/dandyy11/NBA-Player-Performance-Analysis.git

### Contact
For questions or suggestions, please contact Salman Imtiaz at salman.imtiaz414@gmail.com
