## Installing

1. `npm install d3-vs-plots`

2. `npm install d3`


## Example


## Scatter Plot

```javascript
const attributes = {
  dataset: [] //Array of dataset
  graph_attributes: {
    axis_color: "BLACK",
    point_color: "BLACK",
    point_shape: "circle",
    point_size: 2
  }
}
```

```javascript
  import * as plots from 'd3-vs-plots';

  componentDidMount() {
    plots.ring_plot.create_ring_plot(attributes)
  }

  render() {
    return (
      <div className="App">
        <div id="graph"></div>
      </div>
    );
  }
```

## Ring Plot

```javascript
const attributes = {
  dataset: [] //Array of dataset
  graph_attributes: {
    axis_color:"BLACK",
    fill_color:"none",
    ring_thickness:1,
    stroke_color:"BLACK"
    }
}
```

```javascript
  import * as plots from 'd3-vs-plots';

  componentDidMount() {
    plots.scatter_plot.create_scatter_plot(attributes)
  }

  render() {
    return (
      <div className="App">
        <div id="graph"></div>
      </div>
    );
  }
```