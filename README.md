![image](https://user-images.githubusercontent.com/95454600/181918060-c785ef96-6db2-49e6-825f-bca383a2a7e8.png)
# Shark Attack Numbers
According to The New York Times (https://www.nytimes.com/2021/01/27/climate/sharks-population-study.html#:~:text=Oceanic%20sharks%20and%20rays%20have,according%20to%20a%20new%20study.), the population of sharks in the oceans have decreased for about 70% since 1970 mainly because of overfishing.

Since the number of sharks decreased, it is natural to think that the number of shark attacks will also decrease.

This notebook will study if there is any relashionship between the article and the number of shark attacks using to the shark attack dataframe from kaggle and bring some insights about it.

## Technology
- Python;
- VS Code.

## Services
- Github.

## Python Libraries
- Numpy;
- Pandas;
- Regex (re);
- matplotlib.pyplot.

## Initial evaluation
The shark attack file has a lot of messy data, so the numbers of shark attacks over the years look like this:
![image](https://user-images.githubusercontent.com/95454600/181918432-328c51af-3ed4-46de-9d35-93bc36b2607a.png)

## Cleaning the data
Since the article refers to the population of sharks only since 1970, we will filter the shark attacks from 1970 to 2017:
![image](https://user-images.githubusercontent.com/95454600/181918540-2cfc95d0-351d-4f0b-9b23-733bc1cef142.png)

## Using more reliable data
Most of the data from the shark attack file come from the United States of America.

![image](https://user-images.githubusercontent.com/95454600/181918750-bf2190d8-42a8-4f47-8b94-2818ff1c5558.png)

## Comparing data
As the article says that the number of sharks decreased, it is natural to think that the number of shark attacks will also decrease. But, comparing the estimate porcentage of shark population in the oceans with the number of shark attacks in the US, we can see that the decreasing number of sharks does not mean that the number of shark attacks will decrease.

![image](https://user-images.githubusercontent.com/95454600/181918926-d45c932c-646d-48d4-8cd4-a6533c969c2e.png)

We can think of some possible explanations to this. Like the increasing number of people over the years. So let's compare that to see what we get:

![image](https://user-images.githubusercontent.com/95454600/181919371-acac34ed-f7aa-427f-84e1-32a8b428aa7c.png)

It seems that there is some sort of relation between the increasing number of people and the more number of shark attacks.

Between 1970 and 2017 the US population went from 200M people to over 320M people and the number of shark attacks went from about 3 attacks per 100M people to about 15 attacks per 100M people.

## Conclusion
The United States Lifesaving Association provides some data about the number of Beach Attendance in the country. That data shows that the number of people going to beaches and participating on sea activities is growing.

Therefore we can infer that more people means more attacks. But that is not the only reason for the growth in shark attacks numbers and this analysis can go on with some nice theories and questions like:
- Is the number of sea life getting more scarce and therefore sharks are looking for more food?
- Did the available habitats for the sharks have decrease or change?
- Did the water quality influence the number of sharks or habitats?
- Have the climate change affected all these factors and how?
- Compare how the fishing activity has affected these factors.

## References
- Kaggle Shark Attacks File (https://www.kaggle.com/datasets/teajay/global-shark-attacks);
- Wikipedia (https://en.wikipedia.org/wiki/Shark_attack);
- The New York Times article (https://www.nytimes.com/2021/01/27/climate/sharks-population-study.html#:~:text=Oceanic%20sharks%20and%20rays%20have,according%20to%20a%20new%20study.);
- US population Census (https://www.census.gov/popclock/);
- Statistics from the USLA (https://www.usla.org/page/STATISTICS);
- Florida Museum of Natural History International Shark Attacks File (https://www.floridamuseum.ufl.edu/shark-attacks/)

## Version
1.0

## Author
Matheus Reali de Oliveira Fabricio (https://github.com/MatheusReali/MatheusReali)
