# GREEN: A city-specific building energy performance grading system

GREEN is a novel building energy performance grading system based on __machine learning__ and __city benchmarking data__. The grading process is detailed below:


<img src="data/GREEN_methodology.png" width="654" height="384" title="GREEN methodology">

GREEN uses __XGBoost__ to model energy performance and __K Means__ to cluster the model errors into interpretable grades.

The power of GREEN lies mainly on three axes:
- Advanced modeling techniques that capture non-linear relationships in the data and assign grades in an intelligent way.
- Volume of data. GREEN is trained and validated on more than 7,500 residential buildings in New York City.
- Contextualization. GREEN is a market-specific index, meaning the model is specifically trained on and for New York City buildings. This allows to capture energy dynamics that describe a particular building stock.

_Note: Although GREEN grades are currently available for New York City, its system design is scalable and reproducible to any city with available energy benchmarking data._

<img src="data/sankeyGREEN.png" title="GREEN vs. EnergyStar" width="600" height="500">


Full implementation details for every step can be found in [this notebook](https://github.com/spapadopoulos/GREENgrading/blob/master/notebooks/GREEN%20grading%20method.ipynb).

More details in the GREEN method, its applications, and policy implications for climate action in cities can be found in [this paper](https://www.sciencedirect.com/science/article/pii/S030626191831612X).


