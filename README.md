# Impacto-de-Proyectos-de-Unidades-Regionales
<!doctype html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="initial-scale=1,user-scalable=no,maximum-scale=1,width=device-width">
        <meta name="mobile-web-app-capable" content="yes">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <link rel="stylesheet" href="css/leaflet.css">
        <link rel="stylesheet" href="css/qgis2web.css"><link rel="stylesheet" href="css/fontawesome-all.min.css">
        <link rel="stylesheet" href="css/leaflet-control-geocoder.Geocoder.css">
        <link rel="stylesheet" href="css/leaflet-measure.css">
        <style>
        html, body, #map {
            width: 100%;
            height: 100%;
            padding: 0;
            margin: 0;
        }
        </style>
        <title></title>
    </head>
    <body>
        <div id="map">
        </div>
        <script src="js/qgis2web_expressions.js"></script>
        <script src="js/leaflet.js"></script>
        <script src="js/leaflet-svg-shape-markers.min.js"></script>
        <script src="js/leaflet.rotatedMarker.js"></script>
        <script src="js/leaflet.pattern.js"></script>
        <script src="js/leaflet-hash.js"></script>
        <script src="js/Autolinker.min.js"></script>
        <script src="js/rbush.min.js"></script>
        <script src="js/labelgun.min.js"></script>
        <script src="js/labels.js"></script>
        <script src="js/leaflet-control-geocoder.Geocoder.js"></script>
        <script src="js/leaflet-measure.js"></script>
        <script src="data/Chiapas_0.js"></script>
        <script src="data/Sonora_1.js"></script>
        <script src="data/Veracruz_2.js"></script>
        <script src="data/Puebla_3.js"></script>
        <script src="data/Oaxaca_4.js"></script>
        <script src="data/BajaCalifornia_5.js"></script>
        <script src="data/BajaCalifornia_6.js"></script>
        <script src="data/Yucatn_7.js"></script>
        <script src="data/Michoacn_8.js"></script>
        <script src="data/Quertaro_9.js"></script>
        <script src="data/Durango_10.js"></script>
        <script src="data/Morelos_11.js"></script>
        <script src="data/Chihuahua_12.js"></script>
        <script src="data/Yucatn_13.js"></script>
        <script src="data/Chiapas_14.js"></script>
        <script src="data/Quertaro_15.js"></script>
        <script src="data/Durango_16.js"></script>
        <script src="data/Michoacn_17.js"></script>
        <script src="data/Chihuahua_18.js"></script>
        <script src="data/UnidadesRegionales_22.js"></script>
        <script>
        var map = L.map('map', {
            zoomControl:true, maxZoom:28, minZoom:1
        }).fitBounds([[-5.995462429335492,-120.50712848074072],[33.53374080139646,-81.78536175095039]]);
        var hash = new L.Hash(map);
        map.attributionControl.setPrefix('<a href="https://github.com/tomchadwin/qgis2web" target="_blank">qgis2web</a> &middot; <a href="https://leafletjs.com" title="A JS library for interactive maps">Leaflet</a> &middot; <a href="https://qgis.org">QGIS</a>');
        var autolinker = new Autolinker({truncate: {length: 30, location: 'smart'}});
        var measureControl = new L.Control.Measure({
            position: 'topleft',
            primaryLengthUnit: 'meters',
            secondaryLengthUnit: 'kilometers',
            primaryAreaUnit: 'sqmeters',
            secondaryAreaUnit: 'hectares'
        });
        measureControl.addTo(map);
        document.getElementsByClassName('leaflet-control-measure-toggle')[0]
        .innerHTML = '';
        document.getElementsByClassName('leaflet-control-measure-toggle')[0]
        .className += ' fas fa-ruler';
        var bounds_group = new L.featureGroup([]);
        function setBounds() {
        }
        function pop_Chiapas_0(feature, layer) {
        }

        function style_Chiapas_0_0() {
            return {
                pane: 'pane_Chiapas_0',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(128,17,25,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(219,30,42,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_Chiapas_0');
        map.getPane('pane_Chiapas_0').style.zIndex = 400;
        map.getPane('pane_Chiapas_0').style['mix-blend-mode'] = 'normal';
        var layer_Chiapas_0 = new L.geoJson(json_Chiapas_0, {
            attribution: '',
            interactive: true,
            dataVar: 'json_Chiapas_0',
            layerName: 'layer_Chiapas_0',
            pane: 'pane_Chiapas_0',
            onEachFeature: pop_Chiapas_0,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_Chiapas_0_0(feature));
            },
        });
        bounds_group.addLayer(layer_Chiapas_0);
        map.addLayer(layer_Chiapas_0);
        function pop_Sonora_1(feature, layer) {
        }

        function style_Sonora_1_0() {
            return {
                pane: 'pane_Sonora_1',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(128,17,25,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(219,30,42,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_Sonora_1');
        map.getPane('pane_Sonora_1').style.zIndex = 401;
        map.getPane('pane_Sonora_1').style['mix-blend-mode'] = 'normal';
        var layer_Sonora_1 = new L.geoJson(json_Sonora_1, {
            attribution: '',
            interactive: true,
            dataVar: 'json_Sonora_1',
            layerName: 'layer_Sonora_1',
            pane: 'pane_Sonora_1',
            onEachFeature: pop_Sonora_1,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_Sonora_1_0(feature));
            },
        });
        bounds_group.addLayer(layer_Sonora_1);
        map.addLayer(layer_Sonora_1);
        function pop_Veracruz_2(feature, layer) {
        }

        function style_Veracruz_2_0() {
            return {
                pane: 'pane_Veracruz_2',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(128,17,25,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(219,30,42,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_Veracruz_2');
        map.getPane('pane_Veracruz_2').style.zIndex = 402;
        map.getPane('pane_Veracruz_2').style['mix-blend-mode'] = 'normal';
        var layer_Veracruz_2 = new L.geoJson(json_Veracruz_2, {
            attribution: '',
            interactive: true,
            dataVar: 'json_Veracruz_2',
            layerName: 'layer_Veracruz_2',
            pane: 'pane_Veracruz_2',
            onEachFeature: pop_Veracruz_2,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_Veracruz_2_0(feature));
            },
        });
        bounds_group.addLayer(layer_Veracruz_2);
        map.addLayer(layer_Veracruz_2);
        function pop_Puebla_3(feature, layer) {
        }

        function style_Puebla_3_0() {
            return {
                pane: 'pane_Puebla_3',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(128,17,25,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(219,30,42,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_Puebla_3');
        map.getPane('pane_Puebla_3').style.zIndex = 403;
        map.getPane('pane_Puebla_3').style['mix-blend-mode'] = 'normal';
        var layer_Puebla_3 = new L.geoJson(json_Puebla_3, {
            attribution: '',
            interactive: true,
            dataVar: 'json_Puebla_3',
            layerName: 'layer_Puebla_3',
            pane: 'pane_Puebla_3',
            onEachFeature: pop_Puebla_3,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_Puebla_3_0(feature));
            },
        });
        bounds_group.addLayer(layer_Puebla_3);
        map.addLayer(layer_Puebla_3);
        function pop_Oaxaca_4(feature, layer) {
        }

        function style_Oaxaca_4_0() {
            return {
                pane: 'pane_Oaxaca_4',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(128,17,25,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(219,30,42,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_Oaxaca_4');
        map.getPane('pane_Oaxaca_4').style.zIndex = 404;
        map.getPane('pane_Oaxaca_4').style['mix-blend-mode'] = 'normal';
        var layer_Oaxaca_4 = new L.geoJson(json_Oaxaca_4, {
            attribution: '',
            interactive: true,
            dataVar: 'json_Oaxaca_4',
            layerName: 'layer_Oaxaca_4',
            pane: 'pane_Oaxaca_4',
            onEachFeature: pop_Oaxaca_4,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_Oaxaca_4_0(feature));
            },
        });
        bounds_group.addLayer(layer_Oaxaca_4);
        map.addLayer(layer_Oaxaca_4);
        function pop_BajaCalifornia_5(feature, layer) {
        }

        function style_BajaCalifornia_5_0() {
            return {
                pane: 'pane_BajaCalifornia_5',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(128,17,25,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(219,30,42,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_BajaCalifornia_5');
        map.getPane('pane_BajaCalifornia_5').style.zIndex = 405;
        map.getPane('pane_BajaCalifornia_5').style['mix-blend-mode'] = 'normal';
        var layer_BajaCalifornia_5 = new L.geoJson(json_BajaCalifornia_5, {
            attribution: '',
            interactive: true,
            dataVar: 'json_BajaCalifornia_5',
            layerName: 'layer_BajaCalifornia_5',
            pane: 'pane_BajaCalifornia_5',
            onEachFeature: pop_BajaCalifornia_5,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_BajaCalifornia_5_0(feature));
            },
        });
        bounds_group.addLayer(layer_BajaCalifornia_5);
        map.addLayer(layer_BajaCalifornia_5);
        function pop_BajaCalifornia_6(feature, layer) {
        }

        function style_BajaCalifornia_6_0() {
            return {
                pane: 'pane_BajaCalifornia_6',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(128,17,25,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(219,30,42,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_BajaCalifornia_6');
        map.getPane('pane_BajaCalifornia_6').style.zIndex = 406;
        map.getPane('pane_BajaCalifornia_6').style['mix-blend-mode'] = 'normal';
        var layer_BajaCalifornia_6 = new L.geoJson(json_BajaCalifornia_6, {
            attribution: '',
            interactive: true,
            dataVar: 'json_BajaCalifornia_6',
            layerName: 'layer_BajaCalifornia_6',
            pane: 'pane_BajaCalifornia_6',
            onEachFeature: pop_BajaCalifornia_6,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_BajaCalifornia_6_0(feature));
            },
        });
        bounds_group.addLayer(layer_BajaCalifornia_6);
        map.addLayer(layer_BajaCalifornia_6);
        function pop_Yucatn_7(feature, layer) {
        }

        function style_Yucatn_7_0() {
            return {
                pane: 'pane_Yucatn_7',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(128,17,25,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(219,30,42,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_Yucatn_7');
        map.getPane('pane_Yucatn_7').style.zIndex = 407;
        map.getPane('pane_Yucatn_7').style['mix-blend-mode'] = 'normal';
        var layer_Yucatn_7 = new L.geoJson(json_Yucatn_7, {
            attribution: '',
            interactive: true,
            dataVar: 'json_Yucatn_7',
            layerName: 'layer_Yucatn_7',
            pane: 'pane_Yucatn_7',
            onEachFeature: pop_Yucatn_7,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_Yucatn_7_0(feature));
            },
        });
        bounds_group.addLayer(layer_Yucatn_7);
        map.addLayer(layer_Yucatn_7);
        function pop_Michoacn_8(feature, layer) {
        }

        function style_Michoacn_8_0() {
            return {
                pane: 'pane_Michoacn_8',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(128,17,25,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(219,30,42,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_Michoacn_8');
        map.getPane('pane_Michoacn_8').style.zIndex = 408;
        map.getPane('pane_Michoacn_8').style['mix-blend-mode'] = 'normal';
        var layer_Michoacn_8 = new L.geoJson(json_Michoacn_8, {
            attribution: '',
            interactive: true,
            dataVar: 'json_Michoacn_8',
            layerName: 'layer_Michoacn_8',
            pane: 'pane_Michoacn_8',
            onEachFeature: pop_Michoacn_8,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_Michoacn_8_0(feature));
            },
        });
        bounds_group.addLayer(layer_Michoacn_8);
        map.addLayer(layer_Michoacn_8);
        function pop_Quertaro_9(feature, layer) {
        }

        function style_Quertaro_9_0() {
            return {
                pane: 'pane_Quertaro_9',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(128,17,25,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(219,30,42,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_Quertaro_9');
        map.getPane('pane_Quertaro_9').style.zIndex = 409;
        map.getPane('pane_Quertaro_9').style['mix-blend-mode'] = 'normal';
        var layer_Quertaro_9 = new L.geoJson(json_Quertaro_9, {
            attribution: '',
            interactive: true,
            dataVar: 'json_Quertaro_9',
            layerName: 'layer_Quertaro_9',
            pane: 'pane_Quertaro_9',
            onEachFeature: pop_Quertaro_9,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_Quertaro_9_0(feature));
            },
        });
        bounds_group.addLayer(layer_Quertaro_9);
        map.addLayer(layer_Quertaro_9);
        function pop_Durango_10(feature, layer) {
        }

        function style_Durango_10_0() {
            return {
                pane: 'pane_Durango_10',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(128,17,25,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(219,30,42,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_Durango_10');
        map.getPane('pane_Durango_10').style.zIndex = 410;
        map.getPane('pane_Durango_10').style['mix-blend-mode'] = 'normal';
        var layer_Durango_10 = new L.geoJson(json_Durango_10, {
            attribution: '',
            interactive: true,
            dataVar: 'json_Durango_10',
            layerName: 'layer_Durango_10',
            pane: 'pane_Durango_10',
            onEachFeature: pop_Durango_10,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_Durango_10_0(feature));
            },
        });
        bounds_group.addLayer(layer_Durango_10);
        map.addLayer(layer_Durango_10);
        function pop_Morelos_11(feature, layer) {
        }

        function style_Morelos_11_0() {
            return {
                pane: 'pane_Morelos_11',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(128,17,25,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(219,30,42,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_Morelos_11');
        map.getPane('pane_Morelos_11').style.zIndex = 411;
        map.getPane('pane_Morelos_11').style['mix-blend-mode'] = 'normal';
        var layer_Morelos_11 = new L.geoJson(json_Morelos_11, {
            attribution: '',
            interactive: true,
            dataVar: 'json_Morelos_11',
            layerName: 'layer_Morelos_11',
            pane: 'pane_Morelos_11',
            onEachFeature: pop_Morelos_11,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_Morelos_11_0(feature));
            },
        });
        bounds_group.addLayer(layer_Morelos_11);
        map.addLayer(layer_Morelos_11);
        function pop_Chihuahua_12(feature, layer) {
        }

        function style_Chihuahua_12_0() {
            return {
                pane: 'pane_Chihuahua_12',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(128,17,25,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(219,30,42,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_Chihuahua_12');
        map.getPane('pane_Chihuahua_12').style.zIndex = 412;
        map.getPane('pane_Chihuahua_12').style['mix-blend-mode'] = 'normal';
        var layer_Chihuahua_12 = new L.geoJson(json_Chihuahua_12, {
            attribution: '',
            interactive: true,
            dataVar: 'json_Chihuahua_12',
            layerName: 'layer_Chihuahua_12',
            pane: 'pane_Chihuahua_12',
            onEachFeature: pop_Chihuahua_12,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_Chihuahua_12_0(feature));
            },
        });
        bounds_group.addLayer(layer_Chihuahua_12);
        map.addLayer(layer_Chihuahua_12);
        function pop_Yucatn_13(feature, layer) {
        }

        function style_Yucatn_13_0() {
            return {
                pane: 'pane_Yucatn_13',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(247,225,55,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(250,255,57,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_Yucatn_13');
        map.getPane('pane_Yucatn_13').style.zIndex = 413;
        map.getPane('pane_Yucatn_13').style['mix-blend-mode'] = 'normal';
        var layer_Yucatn_13 = new L.geoJson(json_Yucatn_13, {
            attribution: '',
            interactive: true,
            dataVar: 'json_Yucatn_13',
            layerName: 'layer_Yucatn_13',
            pane: 'pane_Yucatn_13',
            onEachFeature: pop_Yucatn_13,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_Yucatn_13_0(feature));
            },
        });
        bounds_group.addLayer(layer_Yucatn_13);
        map.addLayer(layer_Yucatn_13);
        function pop_Chiapas_14(feature, layer) {
        }

        function style_Chiapas_14_0() {
            return {
                pane: 'pane_Chiapas_14',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(247,225,55,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(250,255,57,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_Chiapas_14');
        map.getPane('pane_Chiapas_14').style.zIndex = 414;
        map.getPane('pane_Chiapas_14').style['mix-blend-mode'] = 'normal';
        var layer_Chiapas_14 = new L.geoJson(json_Chiapas_14, {
            attribution: '',
            interactive: true,
            dataVar: 'json_Chiapas_14',
            layerName: 'layer_Chiapas_14',
            pane: 'pane_Chiapas_14',
            onEachFeature: pop_Chiapas_14,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_Chiapas_14_0(feature));
            },
        });
        bounds_group.addLayer(layer_Chiapas_14);
        map.addLayer(layer_Chiapas_14);
        function pop_Quertaro_15(feature, layer) {
        }

        function style_Quertaro_15_0() {
            return {
                pane: 'pane_Quertaro_15',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(247,225,55,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(250,255,57,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_Quertaro_15');
        map.getPane('pane_Quertaro_15').style.zIndex = 415;
        map.getPane('pane_Quertaro_15').style['mix-blend-mode'] = 'normal';
        var layer_Quertaro_15 = new L.geoJson(json_Quertaro_15, {
            attribution: '',
            interactive: true,
            dataVar: 'json_Quertaro_15',
            layerName: 'layer_Quertaro_15',
            pane: 'pane_Quertaro_15',
            onEachFeature: pop_Quertaro_15,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_Quertaro_15_0(feature));
            },
        });
        bounds_group.addLayer(layer_Quertaro_15);
        map.addLayer(layer_Quertaro_15);
        function pop_Durango_16(feature, layer) {
        }

        function style_Durango_16_0() {
            return {
                pane: 'pane_Durango_16',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(247,225,55,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(250,255,57,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_Durango_16');
        map.getPane('pane_Durango_16').style.zIndex = 416;
        map.getPane('pane_Durango_16').style['mix-blend-mode'] = 'normal';
        var layer_Durango_16 = new L.geoJson(json_Durango_16, {
            attribution: '',
            interactive: true,
            dataVar: 'json_Durango_16',
            layerName: 'layer_Durango_16',
            pane: 'pane_Durango_16',
            onEachFeature: pop_Durango_16,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_Durango_16_0(feature));
            },
        });
        bounds_group.addLayer(layer_Durango_16);
        map.addLayer(layer_Durango_16);
        function pop_Michoacn_17(feature, layer) {
        }

        function style_Michoacn_17_0() {
            return {
                pane: 'pane_Michoacn_17',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(247,225,55,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(250,255,57,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_Michoacn_17');
        map.getPane('pane_Michoacn_17').style.zIndex = 417;
        map.getPane('pane_Michoacn_17').style['mix-blend-mode'] = 'normal';
        var layer_Michoacn_17 = new L.geoJson(json_Michoacn_17, {
            attribution: '',
            interactive: true,
            dataVar: 'json_Michoacn_17',
            layerName: 'layer_Michoacn_17',
            pane: 'pane_Michoacn_17',
            onEachFeature: pop_Michoacn_17,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_Michoacn_17_0(feature));
            },
        });
        bounds_group.addLayer(layer_Michoacn_17);
        map.addLayer(layer_Michoacn_17);
        function pop_Chihuahua_18(feature, layer) {
        }

        function style_Chihuahua_18_0() {
            return {
                pane: 'pane_Chihuahua_18',
                radius: 4.0,
                opacity: 1,
                color: 'rgba(247,225,55,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(250,255,57,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_Chihuahua_18');
        map.getPane('pane_Chihuahua_18').style.zIndex = 418;
        map.getPane('pane_Chihuahua_18').style['mix-blend-mode'] = 'normal';
        var layer_Chihuahua_18 = new L.geoJson(json_Chihuahua_18, {
            attribution: '',
            interactive: true,
            dataVar: 'json_Chihuahua_18',
            layerName: 'layer_Chihuahua_18',
            pane: 'pane_Chihuahua_18',
            onEachFeature: pop_Chihuahua_18,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.circleMarker(latlng, style_Chihuahua_18_0(feature));
            },
        });
        bounds_group.addLayer(layer_Chihuahua_18);
        map.addLayer(layer_Chihuahua_18);
        map.createPane('pane_OpenStreetMap_19');
        map.getPane('pane_OpenStreetMap_19').style.zIndex = 419;
        var layer_OpenStreetMap_19 = L.tileLayer('http://tile.openstreetmap.org/{z}/{x}/{y}.png', {
            pane: 'pane_OpenStreetMap_19',
            opacity: 1.0,
            attribution: '',
            minZoom: 1,
            maxZoom: 28,
        });
        layer_OpenStreetMap_19;
        map.addLayer(layer_OpenStreetMap_19);
        map.createPane('pane_OpenStreetMap_20');
        map.getPane('pane_OpenStreetMap_20').style.zIndex = 420;
        var layer_OpenStreetMap_20 = L.tileLayer('http://tile.openstreetmap.org/{z}/{x}/{y}.png', {
            pane: 'pane_OpenStreetMap_20',
            opacity: 1.0,
            attribution: '',
            minZoom: 1,
            maxZoom: 28,
        });
        layer_OpenStreetMap_20;
        map.addLayer(layer_OpenStreetMap_20);
        map.createPane('pane_GoogleTerrain_21');
        map.getPane('pane_GoogleTerrain_21').style.zIndex = 421;
        var layer_GoogleTerrain_21 = L.tileLayer('https://mt1.google.com/vt/lyrs=p&x={x}&y={y}&z={z}', {
            pane: 'pane_GoogleTerrain_21',
            opacity: 1.0,
            attribution: '<a href="https://www.google.at/permissions/geoguidelines/attr-guide.html">Map data ©2015 Google</a>',
            minZoom: 1,
            maxZoom: 28,
            minNativeZoom: 0,
            maxNativeZoom: 20
        });
        layer_GoogleTerrain_21;
        map.addLayer(layer_GoogleTerrain_21);
        function pop_UnidadesRegionales_22(feature, layer) {
            var popupContent = '<table>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['qc_id'] !== null ? autolinker.link(feature.properties['qc_id'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['unidades r'] !== null ? autolinker.link(feature.properties['unidades r'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['municipios'] !== null ? autolinker.link(feature.properties['municipios'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['datos'] !== null ? autolinker.link(feature.properties['datos'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['latitud'] !== null ? autolinker.link(feature.properties['latitud'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['longitud'] !== null ? autolinker.link(feature.properties['longitud'].toLocaleString()) : '') + '</td>\
                    </tr>\
                </table>';
            layer.bindPopup(popupContent, {maxHeight: 400});
        }

        function style_UnidadesRegionales_22_0() {
            return {
                pane: 'pane_UnidadesRegionales_22',
                shape: 'diamond',
                radius: 5.6,
                opacity: 1,
                color: 'rgba(246,80,20,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 2.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(255,116,57,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_UnidadesRegionales_22');
        map.getPane('pane_UnidadesRegionales_22').style.zIndex = 422;
        map.getPane('pane_UnidadesRegionales_22').style['mix-blend-mode'] = 'normal';
        var layer_UnidadesRegionales_22 = new L.geoJson(json_UnidadesRegionales_22, {
            attribution: '',
            interactive: true,
            dataVar: 'json_UnidadesRegionales_22',
            layerName: 'layer_UnidadesRegionales_22',
            pane: 'pane_UnidadesRegionales_22',
            onEachFeature: pop_UnidadesRegionales_22,
            pointToLayer: function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.shapeMarker(latlng, style_UnidadesRegionales_22_0(feature));
            },
        });
        bounds_group.addLayer(layer_UnidadesRegionales_22);
        map.addLayer(layer_UnidadesRegionales_22);
        var osmGeocoder = new L.Control.Geocoder({
            collapsed: true,
            position: 'topleft',
            text: 'Search',
            title: 'Testing'
        }).addTo(map);
        document.getElementsByClassName('leaflet-control-geocoder-icon')[0]
        .className += ' fa fa-search';
        document.getElementsByClassName('leaflet-control-geocoder-icon')[0]
        .title += 'Search for a place';
        var baseMaps = {};
        L.control.layers(baseMaps,{'<img src="legend/UnidadesRegionales_22.png" /> Unidades Regionales': layer_UnidadesRegionales_22,"Google Terrain": layer_GoogleTerrain_21,"OpenStreetMap": layer_OpenStreetMap_20,"OpenStreetMap": layer_OpenStreetMap_19,'<img src="legend/Chihuahua_18.png" /> Chihuahua': layer_Chihuahua_18,'<img src="legend/Michoacn_17.png" /> Michoacán': layer_Michoacn_17,'<img src="legend/Durango_16.png" /> Durango': layer_Durango_16,'<img src="legend/Quertaro_15.png" /> Querétaro': layer_Quertaro_15,'<img src="legend/Chiapas_14.png" /> Chiapas': layer_Chiapas_14,'<img src="legend/Yucatn_13.png" /> Yucatán': layer_Yucatn_13,'<img src="legend/Chihuahua_12.png" /> Chihuahua': layer_Chihuahua_12,'<img src="legend/Morelos_11.png" /> Morelos': layer_Morelos_11,'<img src="legend/Durango_10.png" /> Durango': layer_Durango_10,'<img src="legend/Quertaro_9.png" /> Querétaro': layer_Quertaro_9,'<img src="legend/Michoacn_8.png" /> Michoacán': layer_Michoacn_8,'<img src="legend/Yucatn_7.png" /> Yucatán': layer_Yucatn_7,'<img src="legend/BajaCalifornia_6.png" /> Baja California': layer_BajaCalifornia_6,'<img src="legend/BajaCalifornia_5.png" /> Baja California': layer_BajaCalifornia_5,'<img src="legend/Oaxaca_4.png" /> Oaxaca': layer_Oaxaca_4,'<img src="legend/Puebla_3.png" /> Puebla': layer_Puebla_3,'<img src="legend/Veracruz_2.png" /> Veracruz': layer_Veracruz_2,'<img src="legend/Sonora_1.png" /> Sonora': layer_Sonora_1,'<img src="legend/Chiapas_0.png" /> Chiapas': layer_Chiapas_0,},{collapsed:false}).addTo(map);
        setBounds();
        </script>
    </body>
</html>
