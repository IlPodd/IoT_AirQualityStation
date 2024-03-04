<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>SmartStations</title>
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.1/jquery.min.js"></script>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/chart.js@2.8.0"></script>
</head>
<body>

<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">

        <a class="navbar-brand" href="/index">Air QualIoT Station</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="/">Home<span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="/GetZones">Zones Geodata</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="/History">Data History</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="/RealTime">Data in Real Time</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="/ControlPanel">Access the control panel</a>
                </li>


            </ul>
        </div>
    </div>
</nav>
<div class="container">

    {% block content %}


    {% endblock %}
</div>



</body>
</html>
