(function () {
    "use strict";

    // TODO: Add your ion access token from cesium.com/ion/
    Cesium.Ion.defaultAccessToken = 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJqdGkiOiJlZjMxMjA3Yi1lMzc4LTRjMzAtOGI0NC03MDJiZjA4NWVjNzIiLCJpZCI6MTUzNzQsInNjb3BlcyI6WyJhc3IiLCJnYyJdLCJpYXQiOjE1Njc2OTQ2MzJ9.TTza1qUu1MDdy3jZEfHZJkip2y8IHZEc0_oKE6_I_pw';

    //////////////////////////////////////////////////////////////////////////
    // Creating the Viewer
    //////////////////////////////////////////////////////////////////////////

    var viewer = new Cesium.Viewer('cesiumContainer', {
         shouldAnimate: true,
    });
    
    // Load a drone flight path from a CZML file
    viewer.dataSources.add(
        Cesium.CzmlDataSource.load('./Source/Data/ephemeris.czml')
    );

    viewer.camera.flyHome(0);
    
    
    
    
    
}());
