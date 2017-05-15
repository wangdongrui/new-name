# new-name
<!DOCTYPE html>
<html lang="en" ng-app="car">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        *{
            -webkit-user-select: none;
            -moz-user-select: none;
            -ms-user-select: none;
            user-select: none;
        }
        input+label{
            background-color: #0fe7ff;
        }
        input:checked+label{
            background-color: #ff3561;
        }
    </style>
</head>
<body>
<div>
    <input type="checkbox" id="nao" ng-checked="cc">
    <label for="nao">nao</label>
</div>

<div>
    <input type="checkbox" id="nao1" ng-checked="cc">
    <label for="nao1">nao</label>
</div>
<div>
    <input type="checkbox" id="nao2" ng-checked="cc">
    <label for="nao2">nao</label>
</div>
<div>
    <input type="checkbox" id="nao3" ng-checked="cc">
    <label for="nao3">nao</label>
</div>
</body>
</html>
