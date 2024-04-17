
# Introduction:

The database is grouped at *weekly* level

To identify what is going on with the database we perform some
exploratory data analysis

<img src="Introduction_files/figure-gfm/Plotting Speed-1.png" style="display: block; margin: auto;" />

We can see that the average speed decreases for Azzurropoli

Now we can check the other variables…

<img src="Introduction_files/figure-gfm/Plotting Car Crashes-1.png" style="display: block; margin: auto;" />

<img src="Introduction_files/figure-gfm/Plotting Deaths -1.png" style="display: block; margin: auto;" />

We can notice from the two graphs above that we have a “sharp” decrease
in crashes and deaths

We instead have an increase in Petrol consumption for Azzurropoli

<img src="Introduction_files/figure-gfm/Plotting Petrol -1.png" style="display: block; margin: auto;" />

While for the other variables we have same behaviour

<img src="Introduction_files/figure-gfm/Plotting -1.png" style="display: block; margin: auto;" /><img src="Introduction_files/figure-gfm/Plotting -2.png" style="display: block; margin: auto;" />

Checking that the population density is constant…

<img src="Introduction_files/figure-gfm/Plotting PopDensity-1.png" style="display: block; margin: auto;" />

Checking if the weather is constant…

<img src="Introduction_files/figure-gfm/Plotting Weather-1.png" style="display: block; margin: auto;" />

We have now understood that something happened to the variables:

- `speed`
- `carCrash`
- `pedestrianDeath`
- `energyConsumption`

The only variable that can be the cause for the other variables is
speed.

How the cities differ?

Let’s plot the cities characteristics

<img src="Introduction_files/figure-gfm/unnamed-chunk-2-1.png" style="display: block; margin: auto;" /><img src="Introduction_files/figure-gfm/unnamed-chunk-2-2.png" style="display: block; margin: auto;" /><img src="Introduction_files/figure-gfm/unnamed-chunk-2-3.png" style="display: block; margin: auto;" />

| cityName    | population | size | popDensity | city |
|:------------|-----------:|-----:|-----------:|:-----|
| Azzurropoli |     379909 |  192 |       1979 | 1    |
| Biancavilla |     453991 |   91 |       4989 | 2    |
| Lavandonia  |     271008 |  363 |        747 | 3    |
| Celestopoli |     152110 |  454 |        335 | 4    |
| Plumbeopoli |      52620 |  394 |        134 | 5    |
| Aranciopoli |     303659 |  183 |       1659 | 6    |

We subset the the traffic dataset at station level and plot the
differences between the stations

<img src="Introduction_files/figure-gfm/unnamed-chunk-4-1.png" style="display: block; margin: auto;" /><img src="Introduction_files/figure-gfm/unnamed-chunk-4-2.png" style="display: block; margin: auto;" /><img src="Introduction_files/figure-gfm/unnamed-chunk-4-3.png" style="display: block; margin: auto;" /><img src="Introduction_files/figure-gfm/unnamed-chunk-4-4.png" style="display: block; margin: auto;" /><img src="Introduction_files/figure-gfm/unnamed-chunk-4-5.png" style="display: block; margin: auto;" /><img src="Introduction_files/figure-gfm/unnamed-chunk-4-6.png" style="display: block; margin: auto;" />

As we can see from the graphs, station 4 and 7 are not treated, they
still have the same speed levels.

We can also see that there do not decrease the average car crash per
week and in number 4 do not decrease average pedestrianDeath
