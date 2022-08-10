# SRTM-Data-View
// Map.addLayer (srtm);
// Map.addLayer (eeObject, visParams, name, shown, opacity);

// Map.addLayer (
//   eeObject, 
//   visParams, 
//   name, 
//   shown, 
//   opacity
// );

Map.addLayer(srtm,{min:0, max:1000, palette: 'yellow,purple'},'srtm');
