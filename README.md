# Testing
 ##### Checking connection to data at start of project - chrome dev tool
~~~~
  var ndx = crossfilter(salaryData);
  undefined
  var dim= ndx.dimension(dc.pluck('rank'));
  undefined
  var group = dim.group();
  undefined
  group.all();
  (3) [{…}, {…}, {…}]
  0: {key: "AssocProf", value: 64}
  1: {key: "AsstProf", value: 67}
  2: {key: "Prof", value: 266}
  length: 3
  __proto__: Array(0)

~~~~