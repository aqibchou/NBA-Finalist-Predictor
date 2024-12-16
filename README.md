# NBA-Final-Four-Hall-of-Fame-Predictor
**Basketball team finalist predictor; Link to dataset is provided as cbb.csv**

The Python machine learning project using Pandas, NumPy, and Scikit-Learn is designed to analyze a database of various basketball teams and make predictions on which teams are likely to reach the finals based on their different properties.

The project aims to explore the data to gain insights into the teams' attributes such as their past performance, player stats, and other characteristics that may impact their chances of success in the tournament. The project utilizes various machine learning algorithms such as decision trees and logistic regression to build predictive models that can accurately forecast the outcomes of the tournament.

To accomplish this task, the project first preprocesses the data by cleaning, transforming, and normalizing it to ensure consistency and prepare it for analysis. The project then splits the data into training and testing datasets to evaluate the performance of the models.

After creating the models, the project evaluates their accuracy and F1 score to determine which algorithm is most effective. The models' outputs are then presented to facilitate an intuitive understanding of the predictions.

In conclusion, this Python machine learning project is designed to provide a robust analysis of basketball teams' performance and identify which teams are likely to reach the finals based on their various properties. The project utilizes machine learning algorithms to build predictive models, enabling stakeholders to make informed decisions on team selection and management.

**INFORMATION ON DATASET:**

The dataframe shows:

**TEAM**	The Division I college basketball school

**CONF**	The Athletic Conference in which the school participates in (A10 = Atlantic 10, ACC = Atlantic Coast Conference, AE = America East, Amer = American, ASun = ASUN, B10 = Big Ten, B12 = Big 12, BE = Big East, BSky = Big Sky, BSth = Big South, BW = Big West, CAA = Colonial Athletic Association, CUSA = Conference USA, Horz = Horizon League, Ivy = Ivy League, MAAC = Metro Atlantic Athletic Conference, MAC = Mid-American Conference, MEAC = Mid-Eastern Athletic Conference, MVC = Missouri Valley Conference, MWC = Mountain West, NEC = Northeast Conference, OVC = Ohio Valley Conference, P12 = Pac-12, Pat = Patriot League, SB = Sun Belt, SC = Southern Conference, SEC = South Eastern Conference, Slnd = Southland Conference, Sum = Summit League, SWAC = Southwestern Athletic Conference, WAC = Western Athletic Conference, WCC = West Coast Conference)

**G**	Number of games played

**W**	Number of games won

**ADJOE**	Adjusted Offensive Efficiency (An estimate of the offensive efficiency (points scored per 100 possessions) a team would have against the average Division I defense)

**BARTHAG**	Power Rating (Chance of beating an average Division I team)

**EFG_O**	Effective Field Goal Percentage Shot

**EFG_D**	Effective Field Goal Percentage Allowed

**TOR**	Turnover Percentage Allowed (Turnover Rate)

**TORD**	Turnover Percentage Committed (Steal Rate)

**ORB**	Offensive Rebound Percentage

**DRB**	Defensive Rebound Percentage

**FTR**	Free Throw Rate (How often the given team shoots Free Throws)

**FTRD**	Free Throw Rate Allowed

**2P_O**	Two-Point Shooting Percentage

**2P_D**	Two-Point Shooting Percentage Allowed

**3P_O**	Three-Point Shooting Percentage

**3P_D**	Three-Point Shooting Percentage Allowed

**ADJ_T**	Adjusted Tempo (An estimate of the tempo (possessions per 40 minutes) a team would have against the team that wants to play at an average Division I tempo)

**WAB**	Wins Above Bubble (The bubble refers to the cut off between making the NCAA March Madness Tournament and not making it)

**POSTSEASON**	Round where the given team was eliminated or where their season ended (R68 = First Four, R64 = Round of 64, R32 = Round of 32, S16 = Sweet Sixteen, E8 = Elite Eight, F4 = Final Four, 2ND = Runner-up, Champion = Winner of the NCAA March Madness Tournament for that given year)

**SEED**	Seed in the NCAA March Madness Tournament

**YEAR**	 Season
