<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
<script>
    var oct1 = 100
    var oct2 = 64
    var oct3 = 22 
    var oct4 = 0
    var c = 0
    var ip = `${oct1}.${oct2}.${oct3}.${oct4}`
    function acesso_remoto(){
        for(c = 0; c < 10; c++){
            ip = `${oct1}.${oct2}.${oct3}.${oct4}:2323`
            oct4++ 
            document.location.href = `http://${ip}`
        }
    }
</script>
</html>
