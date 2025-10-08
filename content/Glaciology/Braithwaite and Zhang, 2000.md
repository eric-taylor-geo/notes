2024-09-06 20:57

Paper: [[3 - Tags/Glaciology|Glaciology]] [[Glaciology - Coursework]]

DOI:

URL:

Tags: [[Glaciology - PDD]] [[Glaciology - Model]]

Status: #read-detailed
# Sensitivity of mass balance of five Swiss glaciers to temperature changes assessed by tuning a degree-day model

**Mass Balance and Degree-Day Model**

-	Simplest way to link mass-balance data to climate is by correlation of mass-balance measurements with climate data.
-	Mass balance of the glacier is characterised by observed mass-balance values at regular altitude intervals on the glacier.
-	The observed balance at the jth altitude is $b_j$.
-	The corresponding mean specific balance for the whole glacier is defined by:

$$
\bar{b} = \frac{1}{S} \sum_{j=1}^{J} s_j b_j
$$

-	Where $s_j$ is the area of the j^th altitude band and $S$ is the total area of the glacier.
-	Modelled balance at jth altitude is given by:

$$
b_j^* = c_j^* - a_j^*
$$
- Where $c_j^*$ and $a_j^*$ are the annual accumulation and annual ablation at the specified altitude in the model.
- The annual ablation is made up of a sum of ice ablation and snow ablation and is calculated by the degree-day model (Braithwaite and Olesen, 1989)
$$
a_j^* =k_jPDD_i + k_sPDD_s
$$
- PDDx are the annual positive degree-day sums (sum of positive air temperatures measured at screen height above the glacier at a given altitude (not the same due to various factors) idk what
- Kx is the degree-day factor for ice and snow melt – this degree-day model can be applied to other glacial areas if appropriate K values are known.
- Snowmelt generally has a lower degree-day factor than ice melt – but no evidence that any single set of universal factors can be applied to all situations.
-	Modelled mass bass balance is then given by:
$$
b_j^* = c_j^* - k_i PDD_i - k_s PDD_i - k_s PDD_s\
$$
- Degree day sum for snowmelt period is given by:
$$
PDD_s = \frac{c_j}{k_s}\
$$
- Snow accumulation at a given altitude is estimated for each month from the monthly mean temperature and monthly preciptation with an assumption that the proportion of preciptation falling as snow is a function of the probability that air temperatures within the month lie above or below freezing – probability is estimated from monthly mean temperature assuming that temperatures are distributed normally with a standard deviation of 4 degrees.
![[Pasted image 20240906211143.png]]
- Estimation of accumulation makes two assumptions:
	- Preciptation falls as snow if the air temperature is below 0
	- The probability of preciptation occurring (in whatever form) is independent of the air temperature
- Neither assumption is perfect – however their effects may negate each other. That is, snow often falls when surface temperatures are above the freezing point, but precipitation in the alps also generally occurs in the colder part of a summer month)
- Modelled rain (Mean * (1-p(snow)) is assumed to simply run off the glacier and not contribute to mass balance.
- Annual snow accumulation _c­j*_ in the model is calculated by summing the calculated accumulation for each month.

- Degree-day total is calculated for each month from the monthly mean temperature according to the [[Braithwaite, 1985]] model – assumes that temperatures are normally distributed within the month
- Annual degree-day total is then calculated by summing monthly totals.
- Mass balance is then calculated using above equations
