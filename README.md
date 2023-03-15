
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ISF2023: Reconciliation of structured time series with graphs

<!-- badges: start -->
<!-- badges: end -->

Slides and notes for a talk at the 43rd International Symposium on
Forecasting (25-28th June 2023) in Charlottesville, Virginia USA.

#### Abstract

It is intuitive to describe the relationship between time series in
hierarchical and grouped structures using graphs. Hierarchical time
series structures are typically visualised with polytrees, where each
series is represented by a node and edges connect series to their
disaggregated series. Grouped time series structures are shown as
multiple disjoint polytrees, with each polytree showing a different
order of disaggregation by the grouping variables. All hierarchical and
grouped time series can be described by directed acyclical graphs
(DAGs).

Using DAGs to represent the structure of a coherent collection of time
series enables more flexible reconciliation structures than those
possible in hierarchical and grouped designs. Graph structures can
represent partial reconciliation via disjoint graphs, removing redundant
aggregation with unbalanced trees, and allow sparse aggregation of
series from different aggregation levels. Utilising a graph structure to
describe the coherency of time series also enables improved interfaces
for analysing specific areas of a hierarchy.

This talk will discuss how graphs can be used to represent a wide
variety of coherent time series structures and demonstrate the
advantages of using them in data exploration and forecast
reconciliation.

#### Structure

- The basics of reconciliation
- Hierarchical coherence
- Grouped coherence
- Graph coherence
- Disjoint graphs (cross-validation, incomplete reconciliation)
- Unbalanced trees
- Data exploration with graphs
- Forecast reconciliation on graphs

### Format

17 minute talk with 3 minutes for questions.
