# Insights

## Overview

```vega
{
  "$schema": "https://vega.github.io/schema/vega-lite/v6.json",
  "width": 800,
  "height": 300,
  "title": "Top 10 Repositories by Visitors",
  "data": {
    "values": [
      {"repository": "github-context-tools", "views": 38}, {"repository": "git-unified-diff-parse", "views": 15}, {"repository": "node-cluster-sqs-consumer", "views": 6}
    ]
  },
  "mark": {
    "type": "bar",
    "color": "#ff7f0e"
  },
  "encoding": {
    "y": {"field": "repository", "type": "nominal", "title": "Repository", "sort": "-x"},
    "x": {"field": "views", "type": "quantitative", "title": "Total Views"}
  }
}
```


```vega
{
  "$schema": "https://vega.github.io/schema/vega-lite/v6.json",
  "width": 800,
  "height": 300,
  "title": "Top 10 Repositories by Git Clones",
  "data": {
    "values": [
      {"repository": "github-context-tools", "clones": 57}, {"repository": "node-cluster-sqs-consumer", "clones": 5}, {"repository": "git-unified-diff-parse", "clones": 5}
    ]
  },
  "mark": {
    "type": "bar",
    "color": "#ff7f0e"
  },
  "encoding": {
    "y": {"field": "repository", "type": "nominal", "title": "Repository", "sort": "-x"},
    "x": {"field": "clones", "type": "quantitative", "title": "Total Clones"}
  }
}
```

## Repository Breakdown

### kruthis123/github-context-tools

[![GitHub Repo](https://img.shields.io/badge/-Repository-white?logo=github&logoColor=181717&style=social)](https://github.com/kruthis123/github-context-tools)&nbsp;
[![GitHub Stars](https://img.shields.io/github/stars/kruthis123/github-context-tools?style=social)](https://github.com/kruthis123/github-context-tools/stargazers)&nbsp;
[![GitHub Forks](https://img.shields.io/github/forks/kruthis123/github-context-tools?style=social)](https://github.com/kruthis123/github-context-tools/network/members)&nbsp;
[![GitHub Watchers](https://img.shields.io/github/watchers/kruthis123/github-context-tools?style=social)](https://github.com/kruthis123/github-context-tools/watchers)


```vega
{
  "$schema": "https://vega.github.io/schema/vega-lite/v6.json",
  "width": 800,
  "title": "Visitors for kruthis123/github-context-tools",
  "data": {
    "values": [
      {"date": "2026-05-13", "type": "Total Views", "value": 0},
      {"date": "2026-05-14", "type": "Total Views", "value": 0},
      {"date": "2026-05-15", "type": "Total Views", "value": 0},
      {"date": "2026-05-16", "type": "Total Views", "value": 0},
      {"date": "2026-05-17", "type": "Total Views", "value": 0},
      {"date": "2026-05-18", "type": "Total Views", "value": 0},
      {"date": "2026-05-19", "type": "Total Views", "value": 0},
      {"date": "2026-05-20", "type": "Total Views", "value": 0},
      {"date": "2026-05-21", "type": "Total Views", "value": 0},
      {"date": "2026-05-22", "type": "Total Views", "value": 0},
      {"date": "2026-05-23", "type": "Total Views", "value": 0},
      {"date": "2026-05-24", "type": "Total Views", "value": 38},
      {"date": "2026-05-25", "type": "Total Views", "value": 0},
      {"date": "2026-05-26", "type": "Total Views", "value": 0},
      {"date": "2026-05-13", "type": "Unique Views", "value": 0},
      {"date": "2026-05-14", "type": "Unique Views", "value": 0},
      {"date": "2026-05-15", "type": "Unique Views", "value": 0},
      {"date": "2026-05-16", "type": "Unique Views", "value": 0},
      {"date": "2026-05-17", "type": "Unique Views", "value": 0},
      {"date": "2026-05-18", "type": "Unique Views", "value": 0},
      {"date": "2026-05-19", "type": "Unique Views", "value": 0},
      {"date": "2026-05-20", "type": "Unique Views", "value": 0},
      {"date": "2026-05-21", "type": "Unique Views", "value": 0},
      {"date": "2026-05-22", "type": "Unique Views", "value": 0},
      {"date": "2026-05-23", "type": "Unique Views", "value": 0},
      {"date": "2026-05-24", "type": "Unique Views", "value": 19},
      {"date": "2026-05-25", "type": "Unique Views", "value": 0},
      {"date": "2026-05-26", "type": "Unique Views", "value": 0}
    ]
  },
  "mark": "line",
  "encoding": {
    "x": {
      "field": "date",
      "type": "temporal",
      "title": "Date",
      "scale": { "type": "utc" },
      "axis": {
        "format": "%Y-%m-%d",
        "labelAngle": -45,
        "labelOverlap": false,
        "tickCount": {"interval": "day", "step": 1}
      }
    },
    "y": {"field": "value", "type": "quantitative", "title": "Views"},
    "color": {
      "field": "type",
      "type": "nominal",
      "legend": {
        "title": null
      }
    },
    "tooltip": [
      { "field": "date", "type": "temporal", "title": "Date" },
      { "field": "type", "type": "nominal", "title": "Metric" },
      { "field": "value", "type": "quantitative", "title": "Value" }
    ]
  }
}
```


```vega
{
  "$schema": "https://vega.github.io/schema/vega-lite/v6.json",
  "width": 800,
  "title": "Git Clones for kruthis123/github-context-tools",
  "data": {
    "values": [
      {"date": "2026-05-13", "type": "Total Clones", "value": 0},
      {"date": "2026-05-14", "type": "Total Clones", "value": 0},
      {"date": "2026-05-15", "type": "Total Clones", "value": 0},
      {"date": "2026-05-16", "type": "Total Clones", "value": 0},
      {"date": "2026-05-17", "type": "Total Clones", "value": 0},
      {"date": "2026-05-18", "type": "Total Clones", "value": 0},
      {"date": "2026-05-19", "type": "Total Clones", "value": 0},
      {"date": "2026-05-20", "type": "Total Clones", "value": 0},
      {"date": "2026-05-21", "type": "Total Clones", "value": 0},
      {"date": "2026-05-22", "type": "Total Clones", "value": 0},
      {"date": "2026-05-23", "type": "Total Clones", "value": 0},
      {"date": "2026-05-24", "type": "Total Clones", "value": 52},
      {"date": "2026-05-25", "type": "Total Clones", "value": 2},
      {"date": "2026-05-26", "type": "Total Clones", "value": 3},
      {"date": "2026-05-13", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-14", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-15", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-16", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-17", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-18", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-19", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-20", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-21", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-22", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-23", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-24", "type": "Unique Clones", "value": 34},
      {"date": "2026-05-25", "type": "Unique Clones", "value": 2},
      {"date": "2026-05-26", "type": "Unique Clones", "value": 1}
    ]
  },
  "mark": "line",
  "encoding": {
    "x": {
      "field": "date",
      "type": "temporal",
      "title": "Date",
      "scale": { "type": "utc" },
      "axis": {
        "format": "%Y-%m-%d",
        "labelAngle": -45,
        "labelOverlap": false,
        "tickCount": {"interval": "day", "step": 1}
      }
    },
    "y": {"field": "value", "type": "quantitative", "title": "Clones"},
    "color": {
      "field": "type",
      "type": "nominal",
      "legend": {
        "title": null
      }
    },
    "tooltip": [
      { "field": "date", "type": "temporal", "title": "Date" },
      { "field": "type", "type": "nominal", "title": "Metric" },
      { "field": "value", "type": "quantitative", "title": "Value" }
    ]
  }
}
```

| Referral Source | Views | Unique Visitors |
|-|-|-|
| github.com | 9 | 1 |
| pypi.org | 1 | 1 |

### kruthis123/node-cluster-sqs-consumer

[![GitHub Repo](https://img.shields.io/badge/-Repository-white?logo=github&logoColor=181717&style=social)](https://github.com/kruthis123/node-cluster-sqs-consumer)&nbsp;
[![GitHub Stars](https://img.shields.io/github/stars/kruthis123/node-cluster-sqs-consumer?style=social)](https://github.com/kruthis123/node-cluster-sqs-consumer/stargazers)&nbsp;
[![GitHub Forks](https://img.shields.io/github/forks/kruthis123/node-cluster-sqs-consumer?style=social)](https://github.com/kruthis123/node-cluster-sqs-consumer/network/members)&nbsp;
[![GitHub Watchers](https://img.shields.io/github/watchers/kruthis123/node-cluster-sqs-consumer?style=social)](https://github.com/kruthis123/node-cluster-sqs-consumer/watchers)


```vega
{
  "$schema": "https://vega.github.io/schema/vega-lite/v6.json",
  "width": 800,
  "title": "Visitors for kruthis123/node-cluster-sqs-consumer",
  "data": {
    "values": [
      {"date": "2026-05-13", "type": "Total Views", "value": 0},
      {"date": "2026-05-14", "type": "Total Views", "value": 0},
      {"date": "2026-05-15", "type": "Total Views", "value": 0},
      {"date": "2026-05-16", "type": "Total Views", "value": 6},
      {"date": "2026-05-17", "type": "Total Views", "value": 0},
      {"date": "2026-05-18", "type": "Total Views", "value": 0},
      {"date": "2026-05-19", "type": "Total Views", "value": 0},
      {"date": "2026-05-20", "type": "Total Views", "value": 0},
      {"date": "2026-05-21", "type": "Total Views", "value": 0},
      {"date": "2026-05-22", "type": "Total Views", "value": 0},
      {"date": "2026-05-23", "type": "Total Views", "value": 0},
      {"date": "2026-05-24", "type": "Total Views", "value": 0},
      {"date": "2026-05-25", "type": "Total Views", "value": 0},
      {"date": "2026-05-26", "type": "Total Views", "value": 0},
      {"date": "2026-05-13", "type": "Unique Views", "value": 0},
      {"date": "2026-05-14", "type": "Unique Views", "value": 0},
      {"date": "2026-05-15", "type": "Unique Views", "value": 0},
      {"date": "2026-05-16", "type": "Unique Views", "value": 1},
      {"date": "2026-05-17", "type": "Unique Views", "value": 0},
      {"date": "2026-05-18", "type": "Unique Views", "value": 0},
      {"date": "2026-05-19", "type": "Unique Views", "value": 0},
      {"date": "2026-05-20", "type": "Unique Views", "value": 0},
      {"date": "2026-05-21", "type": "Unique Views", "value": 0},
      {"date": "2026-05-22", "type": "Unique Views", "value": 0},
      {"date": "2026-05-23", "type": "Unique Views", "value": 0},
      {"date": "2026-05-24", "type": "Unique Views", "value": 0},
      {"date": "2026-05-25", "type": "Unique Views", "value": 0},
      {"date": "2026-05-26", "type": "Unique Views", "value": 0}
    ]
  },
  "mark": "line",
  "encoding": {
    "x": {
      "field": "date",
      "type": "temporal",
      "title": "Date",
      "scale": { "type": "utc" },
      "axis": {
        "format": "%Y-%m-%d",
        "labelAngle": -45,
        "labelOverlap": false,
        "tickCount": {"interval": "day", "step": 1}
      }
    },
    "y": {"field": "value", "type": "quantitative", "title": "Views"},
    "color": {
      "field": "type",
      "type": "nominal",
      "legend": {
        "title": null
      }
    },
    "tooltip": [
      { "field": "date", "type": "temporal", "title": "Date" },
      { "field": "type", "type": "nominal", "title": "Metric" },
      { "field": "value", "type": "quantitative", "title": "Value" }
    ]
  }
}
```


```vega
{
  "$schema": "https://vega.github.io/schema/vega-lite/v6.json",
  "width": 800,
  "title": "Git Clones for kruthis123/node-cluster-sqs-consumer",
  "data": {
    "values": [
      {"date": "2026-05-13", "type": "Total Clones", "value": 0},
      {"date": "2026-05-14", "type": "Total Clones", "value": 0},
      {"date": "2026-05-15", "type": "Total Clones", "value": 0},
      {"date": "2026-05-16", "type": "Total Clones", "value": 4},
      {"date": "2026-05-17", "type": "Total Clones", "value": 0},
      {"date": "2026-05-18", "type": "Total Clones", "value": 0},
      {"date": "2026-05-19", "type": "Total Clones", "value": 0},
      {"date": "2026-05-20", "type": "Total Clones", "value": 0},
      {"date": "2026-05-21", "type": "Total Clones", "value": 1},
      {"date": "2026-05-22", "type": "Total Clones", "value": 0},
      {"date": "2026-05-23", "type": "Total Clones", "value": 0},
      {"date": "2026-05-24", "type": "Total Clones", "value": 0},
      {"date": "2026-05-25", "type": "Total Clones", "value": 0},
      {"date": "2026-05-26", "type": "Total Clones", "value": 0},
      {"date": "2026-05-13", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-14", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-15", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-16", "type": "Unique Clones", "value": 1},
      {"date": "2026-05-17", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-18", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-19", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-20", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-21", "type": "Unique Clones", "value": 1},
      {"date": "2026-05-22", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-23", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-24", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-25", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-26", "type": "Unique Clones", "value": 0}
    ]
  },
  "mark": "line",
  "encoding": {
    "x": {
      "field": "date",
      "type": "temporal",
      "title": "Date",
      "scale": { "type": "utc" },
      "axis": {
        "format": "%Y-%m-%d",
        "labelAngle": -45,
        "labelOverlap": false,
        "tickCount": {"interval": "day", "step": 1}
      }
    },
    "y": {"field": "value", "type": "quantitative", "title": "Clones"},
    "color": {
      "field": "type",
      "type": "nominal",
      "legend": {
        "title": null
      }
    },
    "tooltip": [
      { "field": "date", "type": "temporal", "title": "Date" },
      { "field": "type", "type": "nominal", "title": "Metric" },
      { "field": "value", "type": "quantitative", "title": "Value" }
    ]
  }
}
```

| Referral Source | Views | Unique Visitors |
|-|-|-|
| github.com | 6 | 1 |

### kruthis123/git-unified-diff-parse

[![GitHub Repo](https://img.shields.io/badge/-Repository-white?logo=github&logoColor=181717&style=social)](https://github.com/kruthis123/git-unified-diff-parse)&nbsp;
[![GitHub Stars](https://img.shields.io/github/stars/kruthis123/git-unified-diff-parse?style=social)](https://github.com/kruthis123/git-unified-diff-parse/stargazers)&nbsp;
[![GitHub Forks](https://img.shields.io/github/forks/kruthis123/git-unified-diff-parse?style=social)](https://github.com/kruthis123/git-unified-diff-parse/network/members)&nbsp;
[![GitHub Watchers](https://img.shields.io/github/watchers/kruthis123/git-unified-diff-parse?style=social)](https://github.com/kruthis123/git-unified-diff-parse/watchers)


```vega
{
  "$schema": "https://vega.github.io/schema/vega-lite/v6.json",
  "width": 800,
  "title": "Visitors for kruthis123/git-unified-diff-parse",
  "data": {
    "values": [
      {"date": "2026-05-14", "type": "Total Views", "value": 0},
      {"date": "2026-05-15", "type": "Total Views", "value": 0},
      {"date": "2026-05-16", "type": "Total Views", "value": 1},
      {"date": "2026-05-17", "type": "Total Views", "value": 9},
      {"date": "2026-05-18", "type": "Total Views", "value": 1},
      {"date": "2026-05-19", "type": "Total Views", "value": 0},
      {"date": "2026-05-20", "type": "Total Views", "value": 0},
      {"date": "2026-05-21", "type": "Total Views", "value": 0},
      {"date": "2026-05-22", "type": "Total Views", "value": 0},
      {"date": "2026-05-23", "type": "Total Views", "value": 2},
      {"date": "2026-05-24", "type": "Total Views", "value": 2},
      {"date": "2026-05-25", "type": "Total Views", "value": 0},
      {"date": "2026-05-26", "type": "Total Views", "value": 0},
      {"date": "2026-05-27", "type": "Total Views", "value": 0},
      {"date": "2026-05-14", "type": "Unique Views", "value": 0},
      {"date": "2026-05-15", "type": "Unique Views", "value": 0},
      {"date": "2026-05-16", "type": "Unique Views", "value": 1},
      {"date": "2026-05-17", "type": "Unique Views", "value": 1},
      {"date": "2026-05-18", "type": "Unique Views", "value": 1},
      {"date": "2026-05-19", "type": "Unique Views", "value": 0},
      {"date": "2026-05-20", "type": "Unique Views", "value": 0},
      {"date": "2026-05-21", "type": "Unique Views", "value": 0},
      {"date": "2026-05-22", "type": "Unique Views", "value": 0},
      {"date": "2026-05-23", "type": "Unique Views", "value": 1},
      {"date": "2026-05-24", "type": "Unique Views", "value": 1},
      {"date": "2026-05-25", "type": "Unique Views", "value": 0},
      {"date": "2026-05-26", "type": "Unique Views", "value": 0},
      {"date": "2026-05-27", "type": "Unique Views", "value": 0}
    ]
  },
  "mark": "line",
  "encoding": {
    "x": {
      "field": "date",
      "type": "temporal",
      "title": "Date",
      "scale": { "type": "utc" },
      "axis": {
        "format": "%Y-%m-%d",
        "labelAngle": -45,
        "labelOverlap": false,
        "tickCount": {"interval": "day", "step": 1}
      }
    },
    "y": {"field": "value", "type": "quantitative", "title": "Views"},
    "color": {
      "field": "type",
      "type": "nominal",
      "legend": {
        "title": null
      }
    },
    "tooltip": [
      { "field": "date", "type": "temporal", "title": "Date" },
      { "field": "type", "type": "nominal", "title": "Metric" },
      { "field": "value", "type": "quantitative", "title": "Value" }
    ]
  }
}
```


```vega
{
  "$schema": "https://vega.github.io/schema/vega-lite/v6.json",
  "width": 800,
  "title": "Git Clones for kruthis123/git-unified-diff-parse",
  "data": {
    "values": [
      {"date": "2026-05-14", "type": "Total Clones", "value": 1},
      {"date": "2026-05-15", "type": "Total Clones", "value": 0},
      {"date": "2026-05-16", "type": "Total Clones", "value": 0},
      {"date": "2026-05-17", "type": "Total Clones", "value": 2},
      {"date": "2026-05-18", "type": "Total Clones", "value": 0},
      {"date": "2026-05-19", "type": "Total Clones", "value": 1},
      {"date": "2026-05-20", "type": "Total Clones", "value": 1},
      {"date": "2026-05-21", "type": "Total Clones", "value": 0},
      {"date": "2026-05-22", "type": "Total Clones", "value": 0},
      {"date": "2026-05-23", "type": "Total Clones", "value": 0},
      {"date": "2026-05-24", "type": "Total Clones", "value": 0},
      {"date": "2026-05-25", "type": "Total Clones", "value": 0},
      {"date": "2026-05-26", "type": "Total Clones", "value": 0},
      {"date": "2026-05-27", "type": "Total Clones", "value": 0},
      {"date": "2026-05-14", "type": "Unique Clones", "value": 1},
      {"date": "2026-05-15", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-16", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-17", "type": "Unique Clones", "value": 2},
      {"date": "2026-05-18", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-19", "type": "Unique Clones", "value": 1},
      {"date": "2026-05-20", "type": "Unique Clones", "value": 1},
      {"date": "2026-05-21", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-22", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-23", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-24", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-25", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-26", "type": "Unique Clones", "value": 0},
      {"date": "2026-05-27", "type": "Unique Clones", "value": 0}
    ]
  },
  "mark": "line",
  "encoding": {
    "x": {
      "field": "date",
      "type": "temporal",
      "title": "Date",
      "scale": { "type": "utc" },
      "axis": {
        "format": "%Y-%m-%d",
        "labelAngle": -45,
        "labelOverlap": false,
        "tickCount": {"interval": "day", "step": 1}
      }
    },
    "y": {"field": "value", "type": "quantitative", "title": "Clones"},
    "color": {
      "field": "type",
      "type": "nominal",
      "legend": {
        "title": null
      }
    },
    "tooltip": [
      { "field": "date", "type": "temporal", "title": "Date" },
      { "field": "type", "type": "nominal", "title": "Metric" },
      { "field": "value", "type": "quantitative", "title": "Value" }
    ]
  }
}
```

| Referral Source | Views | Unique Visitors |
|-|-|-|
| pypi.org | 11 | 1 |
| github.com | 4 | 1 |

