<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>formulario</title>
    <link real="stylesheet" href="style.css">
</head>
<body>
    
        <forn>
            <header class="header">
        
                <div class="menu container">
                    <a href="a" class="logo">Logo</a>
                    <input type="checkbox" id="menu"/>
                    <label for="menu">
                        <img src="imagen/menu.png" class="menu-icono" alt="menu">
                    </label>
                    <nav class="navbar">
                        <ul>
                            <li><a href="#">Inicio</a></li>
                            <li><a href="#">Servicios</a></li>
                            <li><a href="#">productos</a></li>
                            <li><a href="#">contactos</a></li>
                        </ul>
                    </nav>
                </div>
                <div class="header-content container">
                    <div class="header-txt"> 
                        <h1>Factura tu <span>compra</span><br>aqui<br></h1>
                    </div>
                </div>
            </header>
            <h2>Factura</h2>
            <div id="ctl00_ContentPlaceHolder1_DivFacturar" class="tabcontents">
                <div class="row justify-content-center">
                    <div class="col-9 col-sm-9 col-md-4 input-group-text">
                        <label style="text-align: right; font-weight: bold; color: #2bff00; font-size: large; align-items: end; display: flex;">*&nbsp</label>
                        <input name="ctl00$ContentPlaceHolder1$txtMemRFC" type="text" maxlength="17" id="ctl00_ContentPlaceHolder1_txtMemRFC" class="form-control shadow-sm bg-white rounded text-uppercase TxtPH" placeholder="RFC" onkeypress="return soloLetrasNum(event)" />
                        <span data-bs-toggle="tooltip" data-bs-placement="top" style="align-items: center; display: flex;">
                            <i class="bi bi-align-end invisible"></i>
                        </span>
                    </div>
                    <div class="col-9 col-sm-9 col-md-4 input-group-text">
                        <label style="text-align: right; font-weight: bold; color: transparent; align-items: end; display: flex;">*&nbsp</label>
                        <input name="ctl00$ContentPlaceHolder1$txtCP" type="text" maxlength="5" id="ctl00_ContentPlaceHolder1_txtCP" class="form-control shadow-sm bg-white TxtPH" onkeypress="return soloNum(event)" placeholder="Código postal" />
                        <span data-bs-toggle="tooltip" data-bs-placement="top" style="align-items: center; display: flex;">
                            <i class="bi bi-align-end invisible"></i>
                        </span>
                    </div>
                </div>

                <div class="row mt-3 justify-content-center">
                    <div class="col-9 col-sm-9 col-md-4 input-group-text">
                        <label style="text-align: right; font-weight: bold; color: #2bff00; font-size: large; align-items: end; display: flex;">*&nbsp</label>
                        <input name="ctl00$ContentPlaceHolder1$txtTC" type="text" maxlength="25" id="ctl00_ContentPlaceHolder1_txtTC" class="form-control shadow-sm bg-white TxtPH" onkeypress="return soloNum(event)" placeholder="cedula fiscal" />
                        <span data-bs-toggle="tooltip" data-bs-placement="top" title="Ayuda" style="align-items: center; display: flex;">
                            
                        </span>
                    </div>
                    <div class="col-9 col-sm-9 col-md-4 input-group-text">
                        <label style="text-align: right; font-weight: bold; color: #2bff00; font-size: large; align-items: end; display: flex;">*&nbsp</label>
                        <input name="ctl00$ContentPlaceHolder1$txtTR" type="text" maxlength="5" id="ctl00_ContentPlaceHolder1_txtTR" class="form-control shadow-sm bg-white TxtPH" onkeypress="return soloNum(event)" placeholder="" />
                        <span data-bs-toggle="tooltip" data-bs-placement="top" title="Ayuda" style="align-items: center; display: flex;">
                            
                        </span>
                    </div>
                </div>
            </div>
            <input type="submit" class="btn" value="Facturar">


        </forn> 
</body>
</html>
