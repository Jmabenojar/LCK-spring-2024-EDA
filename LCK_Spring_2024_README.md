
# LCK Spring 2024 Player Statistics Dataset

## Description
This dataset provides detailed statistics for the LCK (League of Legends Champions Korea) Spring 2024 season. It includes information about players, champions, and matches, meticulously cleaned and organized to support analysis, visualization, and predictive modeling.

---

## Contents
The dataset contains the following key components:

### **1. Player Statistics**
- `player`: Name of the player.
- `country`: Country of origin.
- `games`: Total number of games played.
- `win_rate`: Percentage of games won.
- `kda`: Kill/Death/Assist ratio.
- `avg_kills`: Average kills per game.
- `avg_deaths`: Average deaths per game.
- `avg_assists`: Average assists per game.

### **2. Champion Statistics**
- `player`: Name of the player associated with the champion.
- `champion`: Name of the champion used by the player.
- `games_played`: Total games played with the champion.
- `win_rate`: Percentage of games won with the champion.
- `kda`: Average Kill/Death/Assist ratio with the champion.

### **3. Match List**
- `player`: Name of the player.
- `champion`: Name of the champion used in the match.
- `result`: Result of the match (Win or Defeat).
- `score`: Kill/Death/Assist statistics of the player in the match.
- `duration`: Duration of the match in seconds.
- `date`: Date of the match in DD/MM/YYYY format.
- `game`: Specific game identification in the tournament.
- `tournament`: Name of the tournament where the match took place.

---

## Data Collection
The data was collected from the [Gol.gg](https://gol.gg) platform using Python-based web scraping tools:

- **Libraries Used**: `BeautifulSoup`, `Selenium`
- **Processing**: Raw data was cleaned and organized using `Pandas` for consistency and usability.

---

## Applications
This dataset is suitable for:
1. **Exploratory Data Analysis (EDA)**:
   - Visualize player and champion performance trends.
2. **Machine Learning**:
   - Develop predictive models for match outcomes.
3. **Sports Analytics**:
   - Analyze patterns in champion picks and player strategies.

---

## Tools and Recommended Libraries
- **Python**: For data manipulation and analysis.
  - Libraries: `Pandas`, `Matplotlib`, `Seaborn`
- **Visualization**: Tools like `Plotly` and `Dash`.
- **Excel**: For manual validation and sharing.

---

## Column Descriptions
Here are the detailed descriptions for all columns in the dataset:

### **LCK 2024 Spring Stats**
| Column Name   | Description                              |
|---------------|------------------------------------------|
| `player`      | Name of the player.                     |
| `country`     | Country of origin.                      |
| `games`       | Total number of games played.           |
| `win_rate`    | Percentage of games won.                |
| `kda`         | Kill/Death/Assist ratio.                |
| `avg_kills`   | Average kills per game.                 |
| `avg_deaths`  | Average deaths per game.                |
| `avg_assists` | Average assists per game.               |

### **Champions Match List 2024**
| Column Name    | Description                               |
|----------------|-------------------------------------------|
| `player`       | Name of the player associated with the champion. |
| `champion`     | Name of the champion used by the player.  |
| `games_played` | Total games played with the champion.     |
| `win_rate`     | Percentage of games won with the champion.|
| `kda`          | Average Kill/Death/Assist ratio with the champion. |

### **Match List Spring 2024**
| Column Name    | Description                               |
|----------------|-------------------------------------------|
| `player`       | Name of the player.                      |
| `champion`     | Name of the champion used in the match.   |
| `result`       | Result of the match (Win or Defeat).      |
| `score`        | Kill/Death/Assist statistics of the player in the match. |
| `duration`     | Duration of the match in seconds.         |
| `date`         | Date of the match in DD/MM/YYYY format.   |
| `game`         | Specific game identification in the tournament. |
| `tournament`   | Name of the tournament where the match took place. |

---

## License
This dataset is shared under the **CC BY 4.0 License**, allowing reuse with proper attribution.

---

## Acknowledgments
The dataset was created using statistics from [Gol.gg](https://gol.gg) and processed with Python. Special thanks to the League of Legends esports community for inspiration.
