
# INOVITI FRONTEND DEV PRACTICAL TEST


## GOAL
Test candidates expertise in building reusable ui components.

### TASKS
For the following, The candidate may use any of the ui frameworks below to accomplish tasks.
1. vuejs
2. angular
3. reactjs

#### 1. Chart Component

create a chart component that enables visualization of a set of data. You may use any chart library of your choice ie: [chartjs](https://www.chartjs.org/)



##### input:
 a. `series`
sample value
```
series = {
    data: [100, 10, 14]
    categories: [isodate1, isodate2, isodate3]
}
```
 b. `chartType` - enables changing the display type of the chart.
possible values: `line`, `bar`


#### 2. Tree List Component
Create a tree list component where each node is expanded and collapsed.

##### input:
a. `tree`
Sample values
```
tree = [
        {
            label: "node1",
            children: [
                {
                    label: "node1-child"
                }
            ]
        },
        {
            label: "node2"
        },
        {
            label: "node3"
        }
    ]
]
```
### ADDITIONAL TASKS
1. Create a video explainer showing the components in action.
2. Optional, use storybook



