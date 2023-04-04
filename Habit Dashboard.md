
> [!info]
> This page gives you a dashboard to see your progress with the habits you want to track
> 
> Click on...
> 
> - The title of the calendar to view your progress on other daily habits
> - A specific day to view the value for the entry that day `1, 0`, or if it was blank
> - The `<` and `>` icons to go back or forward a month, or the dot to go to the current month (which can show an error if no entries are found for the current month)
> 



```tracker
searchType: dvField
searchTarget: workout, meditation
startDate: 2023-01-01
endDate: 2023-04-30
datasetName: Workout, Meditation
folder: Calendar
month:
  annotation: 💪, 🧘‍♂️
```

> [!info] 
> You can see the code to create these charts by hovering to the right of a chart and clicking the `</>` button!
> 
> Order matters in these charts. If you have multilple items you wish to track, the order is set by what you list in the `searchTarget`. You need to make the `datasetName` and `annotation` lists match.


```tracker
searchType: dvField
searchTarget: mood
datasetName: Mood
folder: Calendar
line:
    title: "Mood"
    yAxisLabel: Mood
    lineColor: "#d65d0e"
    yAxisTickInterval: 1
    yAxisTickLabelFormat: i
    yMin: 0
```


## Next Steps

Review the [[+Calendar]] page