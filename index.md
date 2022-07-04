

```markdown
<!DOCTYPE html>
<head>    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_83816bb3c3974ca79a2dae977656b52b {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
            </style>
        
</head>
<body>    
    
            <div class="folium-map" id="map_83816bb3c3974ca79a2dae977656b52b" ></div>
        
</body>
<script>    
    
            var map_83816bb3c3974ca79a2dae977656b52b = L.map(
                "map_83816bb3c3974ca79a2dae977656b52b",
                {
                    center: [37.5916375, -80.5434095],
                    crs: L.CRS.EPSG3857,
                    zoom: 7,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var circle_marker_e5eea750322a45e8837c199f70a93d93 = L.circleMarker(
                [37.718726, -78.155744],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_e5eea750322a45e8837c199f70a93d93.bindTooltip(
                `<div>
                     Boston Hill (1733)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_ce0ec236ce51483c8fc6cf9702eedf3f = L.circleMarker(
                [37.7238024, -78.85130675],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_ce0ec236ce51483c8fc6cf9702eedf3f.bindTooltip(
                `<div>
                     Mountain Retreat (1836)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_7ae9bd7060e94ecdb0bbc518a862d795 = L.circleMarker(
                [38.13878725, -84.4115087605337],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_7ae9bd7060e94ecdb0bbc518a862d795.bindTooltip(
                `<div>
                     Elk Hill (1797)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_29d18643e5444bb296a6cf728e9ba2ce = L.circleMarker(
                [37.518948310601445, -79.33082301888368],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_29d18643e5444bb296a6cf728e9ba2ce.bindTooltip(
                `<div>
                     Verdant Vale (1785)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_dcf2a59aaa0d470da7f40ea635f6a91a = L.circleMarker(
                [37.54273504281624, -78.84049865809332],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_dcf2a59aaa0d470da7f40ea635f6a91a.bindTooltip(
                `<div>
                     Below Centre Hill (1744)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_bcb15c39599c4f2dac73ad485ab6326f = L.circleMarker(
                [37.58710272517427, -78.60815065821053],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_bcb15c39599c4f2dac73ad485ab6326f.bindTooltip(
                `<div>
                     Mulberry Grove (1771)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_5c9a5110e1914c8582eb79b57e901635 = L.circleMarker(
                [37.64043923737374, -78.98282804040404],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_5c9a5110e1914c8582eb79b57e901635.bindTooltip(
                `<div>
                     Mountain View (1780)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_31c23a49480c4920a2ed3cae3ad800db = L.circleMarker(
                [37.71161, -78.871395],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_31c23a49480c4920a2ed3cae3ad800db.bindTooltip(
                `<div>
                     Oak Ridge (1801)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_601117a48f454646a1362b75325672c0 = L.circleMarker(
                [37.78120498795181, -78.99797809638554],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_601117a48f454646a1362b75325672c0.bindTooltip(
                `<div>
                     Three Springs (1854)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_b9c11e78f99e4e56a2075bc2c44b06c6 = L.circleMarker(
                [37.60859542150336, -78.81979581107808],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_b9c11e78f99e4e56a2075bc2c44b06c6.bindTooltip(
                `<div>
                     Struman (1802)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_c3e8b2552155405d85143c1155bd250b = L.circleMarker(
                [37.57763929810295, -78.81985671853579],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_c3e8b2552155405d85143c1155bd250b.bindTooltip(
                `<div>
                     Fernley (1860)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_bc74f44233b4473891e36957760f6436 = L.circleMarker(
                [37.68963284526518, -78.70487053560802],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_bc74f44233b4473891e36957760f6436.bindTooltip(
                `<div>
                     Edgewood (1790)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_3932ace1287048ddb00af9e90c3d81a4 = L.circleMarker(
                [37.670721, -78.799764],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_3932ace1287048ddb00af9e90c3d81a4.bindTooltip(
                `<div>
                     Glenmore (1820)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_0bcdd99095944a138e94f63dbfad419b = L.circleMarker(
                [37.597467764654745, -78.81136601377533],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_0bcdd99095944a138e94f63dbfad419b.bindTooltip(
                `<div>
                     Clover Plains (1739)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_f94dd2af66f24e80b92ecd7e81c6776e = L.circleMarker(
                [37.66779810573013, -78.83663589525054],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_f94dd2af66f24e80b92ecd7e81c6776e.bindTooltip(
                `<div>
                     Inglewood (1829)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_6f899f442627476ab4f2c634039b1892 = L.circleMarker(
                [37.639006296673664, -79.02270644876447],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_6f899f442627476ab4f2c634039b1892.bindTooltip(
                `<div>
                     Winton (1771)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_1f42a24016ab49aa963da36beb7aedbe = L.circleMarker(
                [37.4518145, -77.4447058],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_1f42a24016ab49aa963da36beb7aedbe.bindTooltip(
                `<div>
                     Ampt Hill (1835)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_e6cc47976d2c4582aebc0ea760760f33 = L.circleMarker(
                [36.7694576, -78.9176817],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_e6cc47976d2c4582aebc0ea760760f33.bindTooltip(
                `<div>
                     Banister Lodge (1830)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_3344463163884373bef916c7ec8a8027 = L.circleMarker(
                [37.0501416, -78.9441801],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_3344463163884373bef916c7ec8a8027.bindTooltip(
                `<div>
                     Staunton Hill (1848)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_189e1e2fa58947d39008ecdbb6bb3049 = L.circleMarker(
                [37.582087, -78.8444624],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_189e1e2fa58947d39008ecdbb6bb3049.bindTooltip(
                `<div>
                     Rose Hill (1811)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_6ee566df54544f5d99d2c88f38c09dae = L.circleMarker(
                [37.5468094, -78.8494619],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_6ee566df54544f5d99d2c88f38c09dae.bindTooltip(
                `<div>
                     Centre Hill (1744)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_413fd68b7c53487fbabc4943f759bfe2 = L.circleMarker(
                [37.737577, -79.033034],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_413fd68b7c53487fbabc4943f759bfe2.bindTooltip(
                `<div>
                     Harewood (1810)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_40fd01eabfb943ddbd1fbfb39fe2e894 = L.circleMarker(
                [37.564051, -78.839138],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_40fd01eabfb943ddbd1fbfb39fe2e894.bindTooltip(
                `<div>
                     Above Centre Hill (1744)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_b9e1b75f25234c77840f63179a160328 = L.circleMarker(
                [37.690947, -78.689215],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_b9e1b75f25234c77840f63179a160328.bindTooltip(
                `<div>
                     Traveler's Rest (1724)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_47e6222dd646471e9d2de76be89f8420 = L.circleMarker(
                [37.6659763, -78.7222377],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_47e6222dd646471e9d2de76be89f8420.bindTooltip(
                `<div>
                     Midway (1801)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_8524bb67fc0e4338994f9b938b745998 = L.circleMarker(
                [37.623535, -78.806715],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_8524bb67fc0e4338994f9b938b745998.bindTooltip(
                `<div>
                     Green Hill (1762)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_4926b5a445ee4ed5b3c13086b82f3122 = L.circleMarker(
                [37.6398653, -78.7239039],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_4926b5a445ee4ed5b3c13086b82f3122.bindTooltip(
                `<div>
                     Soldier's Joy (1783)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_b145aba1e95e42fd9b8c5ff1ab0ae11f = L.circleMarker(
                [37.9540298, -78.5294569],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_b145aba1e95e42fd9b8c5ff1ab0ae11f.bindTooltip(
                `<div>
                     Redlands Estate (1792)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_9d14c690be5b4e3ab87368276ddaa80f = L.circleMarker(
                [37.678995, -78.826381],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_9d14c690be5b4e3ab87368276ddaa80f.bindTooltip(
                `<div>
                     Belmont (Findlay Mountain) (1810)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_a699950ed4db4fa18d379deed51d6038 = L.circleMarker(
                [37.644952, -78.808547],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_a699950ed4db4fa18d379deed51d6038.bindTooltip(
                `<div>
                     Rectory (1831)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_011c76c76f634e55bf55578139315127 = L.circleMarker(
                [37.42063145, -79.14391316337719],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_011c76c76f634e55bf55578139315127.bindTooltip(
                `<div>
                     Point of Honor (1753)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_97f37df656454ba5beb7ee055da25edd = L.circleMarker(
                [37.648232, -78.786149],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_97f37df656454ba5beb7ee055da25edd.bindTooltip(
                `<div>
                     Norwood (1856)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_02b41b6bd01243f991c17c6984c2064f = L.circleMarker(
                [37.638972, -78.8199],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_02b41b6bd01243f991c17c6984c2064f.bindTooltip(
                `<div>
                     Forkfield (1832)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_5acf1d542353461980eacf86a32bdabb = L.circleMarker(
                [37.641064, -78.74392],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_5acf1d542353461980eacf86a32bdabb.bindTooltip(
                `<div>
                     Rock Cliff (1840)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_b090b3af1af3408d8b4e8642be0658c0 = L.circleMarker(
                [37.652564, -78.789243],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_b090b3af1af3408d8b4e8642be0658c0.bindTooltip(
                `<div>
                     Benvenue (1840)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_c4f9bd8de23046bb97f252a5f7b62e1c = L.circleMarker(
                [37.644853, -78.769285],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_c4f9bd8de23046bb97f252a5f7b62e1c.bindTooltip(
                `<div>
                     Union Hill (1775)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_dba60db8429e4a43804f6ad15b78e428 = L.circleMarker(
                [37.643264, -78.759654],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_dba60db8429e4a43804f6ad15b78e428.bindTooltip(
                `<div>
                     Colleton (1760)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_b5cce1f4e650423eada4cae0b03b6d1e = L.circleMarker(
                [38.088871, -78.290939],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_b5cce1f4e650423eada4cae0b03b6d1e.bindTooltip(
                `<div>
                     Castle Hill (1764)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_ebc0841974c74c5f8ad374dd36edbdb7 = L.circleMarker(
                [36.701736, -78.965004],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_ebc0841974c74c5f8ad374dd36edbdb7.bindTooltip(
                `<div>
                     Tarover (1856)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_4cc5098df01344438fe2541986f86b44 = L.circleMarker(
                [37.02307, -78.57699],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_4cc5098df01344438fe2541986f86b44.bindTooltip(
                `<div>
                     Ingleside (1810)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_21edc70d726346da9c7c0b1b2e13cacf = L.circleMarker(
                [37.3541, -78.35201],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_21edc70d726346da9c7c0b1b2e13cacf.bindTooltip(
                `<div>
                     Greenfield (1771)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_2ba953e3d7af488b8e3232c03e37b7c0 = L.circleMarker(
                [37.68536, -78.71663],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_2ba953e3d7af488b8e3232c03e37b7c0.bindTooltip(
                `<div>
                     Bon Aire (1798)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_c7ea88bcaf7a4d8cb149dbe576006e68 = L.circleMarker(
                [37.776973, -78.973479],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_c7ea88bcaf7a4d8cb149dbe576006e68.bindTooltip(
                `<div>
                     Blue Rock (1816)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_424feec14c5643d68d7f2921f731839e = L.circleMarker(
                [37.693873, -77.933004],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_424feec14c5643d68d7f2921f731839e.bindTooltip(
                `<div>
                     Lickinghole Creek (1726)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_04a3a92ad7d94b1192fbbebdf1e3b004 = L.circleMarker(
                [37.658768183235416, -78.69051189449506],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_04a3a92ad7d94b1192fbbebdf1e3b004.bindTooltip(
                `<div>
                     Repton (1785)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_77248761e6e14f439c75c0eb06db81bd = L.circleMarker(
                [37.658968183235416, -78.69071189449507],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_77248761e6e14f439c75c0eb06db81bd.bindTooltip(
                `<div>
                     Montevideo (1809)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_9b6c74f266fc4a28af826deaaa2dff4d = L.circleMarker(
                [37.665961112008574, -78.6848610015568],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_9b6c74f266fc4a28af826deaaa2dff4d.bindTooltip(
                `<div>
                     Yellow Gravel (1785)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_d3db8c8b94574b78bd25c9b55d4b6891 = L.circleMarker(
                [37.666161112008574, -78.6850610015568],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_d3db8c8b94574b78bd25c9b55d4b6891.bindTooltip(
                `<div>
                     Sion Hill (1785)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_723c44291e9448cfb319eab957789641 = L.circleMarker(
                [37.648946, -78.801605],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_723c44291e9448cfb319eab957789641.bindTooltip(
                `<div>
                     Montezuma (1790)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_ede720d8936542beb33e087cadf3068c = L.circleMarker(
                [37.649146, -78.801805],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_ede720d8936542beb33e087cadf3068c.bindTooltip(
                `<div>
                     Spring Hill (1790)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_a421745ccfab477581c94207eae7432d = L.circleMarker(
                [37.69055, -78.6999],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_a421745ccfab477581c94207eae7432d.bindTooltip(
                `<div>
                     Liberty Hall (1776)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_084ecb78d9ec41979e1ec1326b7ee3b7 = L.circleMarker(
                [37.69075, -78.7001],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_084ecb78d9ec41979e1ec1326b7ee3b7.bindTooltip(
                `<div>
                     Swan Creek (1742)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_marker_97b62e8629804442819bf9ca31e52579 = L.circleMarker(
                [37.67577, -78.73576],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "black", "fillOpacity": 0.9, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            circle_marker_97b62e8629804442819bf9ca31e52579.bindTooltip(
                `<div>
                     Belmont (Mayo Creek) (1820)
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_765fd42c97614a84b3ae367baf7eaeea = L.circle(
                [37.6431981, -78.8089069],
                {"bubblingMouseEvents": true, "color": "crimson", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "crimson", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 20000, "stroke": true, "weight": 3}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
    
            var tile_layer_e7c9f5ff59d645319efad3e31fc54a67 = L.tileLayer(
                "https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",
                {"attribution": "Data by \u0026copy; \u003ca href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eODbL\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_83816bb3c3974ca79a2dae977656b52b);
        
</script>

