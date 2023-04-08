Plotly.toImage('myPlot', {format: 'png', height: 500, width: 700}).then(function (url) {
  var img = document.createElement('img');
  img.src = url;
  document.body.appendChild(img);
});


