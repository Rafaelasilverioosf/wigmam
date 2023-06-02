%%[
VAR @Subscriberkey, @EmailAddress, @DES_NOMBREProperCase, @DES_NOMBRE 

SET @EmailAddress = [EmailAddress] 
SET @Subscriberkey = [Subscriberkey]
SET @DES_NOMBRE =  AttributeValue("DES_NOMBRE")
SET @DES_NOMBREProperCase = ProperCase(@DES_NOMBRE)

SET @pageurl = CloudPagesURL(1542,"EmailAddress", @EmailAddress, "Subscriberkey", @Subscriberkey)

IF EMPTY(@DES_NOMBRE) THEN
  SET @Subject = "¡Hola!"
  SET @body = ""
ELSE
  SET @Subject = CONCAT("", @DES_NOMBREProperCase, "")
  SET @body = CONCAT(" ",@DES_NOMBREProperCase, "")
ENDIF

]%%

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" 
xmlns:v="urn:schemas-microsoft-com:vml"
xmlns:o="urn:schemas-microsoft-com:office:office"
xmlns:w="urn:schemas-microsoft-com:office:word">
<head>
<meta http-equiv="X-UA-Compatible" content="IE=edge"/>
<meta name="format-detection" content="telephone=no" />
<meta name="viewport" content="width=device-width, initial-scale=1"/>
<meta name="apple-mobile-web-app-capable" content="yes" />
<custom name="opencounter" type="tracking"/>
<title></title>
<style type="text/css">
  
  </style>

<!--[if mso]><style type="text/css">
table { font-family: Arial, sans-serif; }
</style><![endif]-->

<!--[if gte mso 9]>
<xml>
<o:OfficeDocumentSettings>
<o:AllowPNG/>
<o:PixelsPerInch>96</o:PixelsPerInch>
</o:OfficeDocumentSettings>
</xml>
<![endif]-->
<head>

<body topmargin="0" leftmargin="0" style="background:#f7f7f7; color:#394348; font-family: Arial, Helvetica Neue, Helvetica, sans-serif, OpenSans; font-size:16px; line-height:20px;" yahoo="fix" alink="#2c67c7" link="#2c67c7" marginheight="0" marginwidth="0" bgcolor="#ffffff" text="#394348">

<!-- pre-header SF -->
<table role="presentation" class="preheader" width="100%" border="0" cellspacing="0" cellpadding="0" style="display:none !important; max-height:0 !important; overflow:hidden !important; font-size:0 !important;">
  <tr>
    <td></td>
  </tr>
</table>
<!-- /pre-header SF --> 
<!-- MODULE: view-in-browser-link SF -->
<table role="presentation" class="LIMON-SECTION" bgcolor="#ffffff" align="center" border="0" cellpadding="0" cellspacing="0" width="100%" style="table-layout:fixed;">
  <tr>
    <td align="center">
      <table role="presentation" class="LIMON-PANEL" align="center" border="0" cellpadding="0" cellspacing="0" width="600" style="width:600px; min-width:600px;">
        <tr>
              <td align="center" style="font-family: Arial, Helvetica, sans-serif; font-size: 12px; color: #999999;">Si no pod&eacute;s ver este mensaje correctamente hac&eacute; <a href="%%view_email_url%%" style="color: #666666; text-decoration: underline;">click aqu&iacute;</a>.</td>            
         </tr>
      </table>
    </td>
  </tr>
</table>
<!-- /MODULE: view-in-browser-link SF -->

<!-- DESTACADOS-->
<table class="LIMON-SECTION" width="100%" border="0" cellspacing="0" cellpadding="0" bgcolor="#ffffff" role="presentation" style="table-layout:fixed">
  <tr>
  <td style="font-size:0px">&nbsp;</td>
  <td align="center" width="600" bgcolor="white" style="width:600px; min-width:600px;" class="LIMON-PANEL">
<table role="presentation" border="0" cellpadding="0" cellspacing="0" width="100%">
  <tr>
    <td >
     
      <table role="presentation" border="0" cellspacing="0" cellpadding="0">
        <tr>
<td><table width="100%" border="0" cellspacing="0" cellpadding="0">
            
              <!--AUTO 2-->
              <tr>
                <td><img src="https://image.ar-mail.ford.com/lib/fe3411747364047c741373/m/1/bb216347-d0bd-4079-8a3f-0a76e88e336d.jpg" class="U-RESPONSIVE-IMAGE" width="600" height="228" alt="Guía 360 Territory" border="0" style="display:block; border:0"/></td>
              </tr>
              <!--/AUTO 2-->
              
        
            </table></td>        
</tr>
      </table>    
    </td>
  </tr>
</table>
</td>
    <td style="font-size:0px">&nbsp;</td>
  </tr>
</table> 
<!-- /DESTACADOS -->
 <!--txt1-->
<table class="LIMON-SECTION" width="100%" border="0" cellspacing="0" cellpadding="0" bgcolor="#ffffff" role="presentation" style="table-layout:fixed">
  <tr>
  <td style="font-size:0px">&nbsp;</td>
  <td align="center" width="600" bgcolor="#ffffff" style="width:600px; min-width:600px;" class="LIMON-PANEL">
<table role="presentation" border="0" cellpadding="0" cellspacing="0" width="100%">
  <tr>
    <td class="mobile_margins" style="padding-right:40px; padding-left:40px; padding-bottom:35px;">
    

<table role="presentation" width="100%" border="0" cellspacing="0" cellpadding="0">

  
  <tr>
    <td align="left" style="font-family: Arial, Helvetica Neue, Helvetica, sans-serif, OpenSans; font-size:17px; line-height:19px; color:#000000; padding-bottom:25px; text-align: left; padding-top:30px; font-weight: bold" class="body_copy">Hola%%=v(@body)=%%, </td>
  </tr>
  <tr>
    <td align="left" style="font-family: Arial, Helvetica Neue, Helvetica, sans-serif, OpenSans; font-size:14px; line-height:21px; color:#000000;  text-align: left; " class="body_copy"><span style="font-size: 16px">¡Felicitaciones por obtener tu <strong>Territory</strong>! </span><br />
      Estás a un paso de descubrir una experiencia de manejo inteligente y placentera con la Nueva Territory.</td>
  </tr>
 
</table>


    </td>
  </tr>
</table>
</td>
    <td style="font-size:0px">&nbsp;</td>
  </tr>
</table> 
<!--/txt1-->


<!--box 1-->
<table class="LIMON-SECTION" width="100%" border="0" cellspacing="0" cellpadding="0" bgcolor="#ffffff" role="presentation" style="table-layout:fixed">
  <tr>
  <td style="font-size:0px">&nbsp;</td>
  <td align="center" width="600" bgcolor="#ffffff" style="width:600px; min-width:600px;" class="LIMON-PANEL">
<table role="presentation" border="0" cellpadding="0" cellspacing="0" width="100%">
  <tr>
    <td >
      

 <!-- body-copy--dark-grey SF -->
 <table width="100%" border="0" cellspacing="0" cellpadding="0">
   <tbody>
     
     <tr>
       <td style="padding-right: 20px" class="Padright_none"><table role="presentation"  width="100%" border="0" cellspacing="0" cellpadding="0">
         <tr>
           <td ><table role="presentation" align="right" width="240" border="0" cellspacing="0" cellpadding="0" class="U-FULLWIDTH" style="width:240px; min-width:240px;">
             <tr>
                 <td valign="top" class="mobile_margins"><table role="presentation" width="100%" border="0" cellspacing="0" cellpadding="0">
  
  <tr>
    <td align="right" style="font-family:Verdana, Helvetica Neue, Helvetica, sans-serif, OpenSans; font-size:14px; line-height:18px; color:#0a115a; padding-top:60px; font-weight: bold; text-align:right" class="body_copy mob_txt_center mob_padTop_none">SISTEMA DE CONECTIVIDAD  CON PANTALLA MULTI-TÁCTIL  DE 10” SYNC TOUCH </td>
  </tr>
  <tr>
    <td align="right" style="font-family:Verdana, Helvetica Neue, Helvetica, sans-serif, OpenSans; font-size:12px; color:#0a115a; padding-top:2px; text-align:right; padding-bottom: 60px" class="body_copy mob_txt_center">Compatible con Android Auto  y Apple Car Play Wireless.</td>
  </tr>
</table></td>
               </tr>
           </table><table role="presentation" align="left" width="300" border="0" cellspacing="0" cellpadding="0" class="U-FULLWIDTH" style="width:300px; min-width:300px;">
             <tr>
                 <td valign="top"><img src="https://image.ar-mail.ford.com/lib/fe3411747364047c741373/m/1/fab2de1c-6c4f-4796-82ee-5793331479da.jpg" width="300" height="216" alt="" class="U-RESPONSIVE-IMAGE" style="display:block; border:10"/></td>
               </tr>
           </table></td>
         </tr>
       </table></td>
     </tr>
   </tbody>
 </table> <!-- /body-copy--dark-grey SF -->
    </td>
  </tr>
</table>
</td>
    <td style="font-size:0px">&nbsp;</td>
  </tr>
</table> 
<!-- /box1->

<!--box 2-->
<table class="LIMON-SECTION" width="100%" border="0" cellspacing="0" cellpadding="0" bgcolor="#ffffff" role="presentation" style="table-layout:fixed">
  <tr>
  <td style="font-size:0px">&nbsp;</td>
  <td align="center" width="600" bgcolor="#ffffff" style="width:600px; min-width:600px;" class="LIMON-PANEL">
<table role="presentation" border="0" cellpadding="0" cellspacing="0" width="100%">
  <tr>
    <td >
      

 <!-- body-copy--dark-grey SF -->
 <table width="100%" border="0" cellspacing="0" cellpadding="0">
   <tbody>
     
     <tr>
       <td style="padding-left: 20px; background-color: #00025c" class="Padleft_none" ><table role="presentation"  width="100%" border="0" cellspacing="0" cellpadding="0">
         <tr>
           <td ><table role="presentation" align="left" width="255" border="0" cellspacing="0" cellpadding="0" class="U-FULLWIDTH" style="width:255px; min-width:255px;">
             <tr>
                 <td valign="top" class="mobile_margins"><table role="presentation" width="100%" border="0" cellspacing="0" cellpadding="0">
  
  <tr>
    <td align="right" style="font-family:Verdana, Helvetica Neue, Helvetica, sans-serif, OpenSans; font-size:15px; line-height:19px; color:#ffffff; padding-top:15px; font-weight: bold; text-align:left;" class="mob_txt_center">SISTEMA DE ESTACIONAMIENTO ASISTIDO CON CÁMARA 360</td>
  </tr>
  <tr>
    <td align="right" style="font-family:Verdana, Helvetica Neue, Helvetica, sans-serif, OpenSans; font-size:12px; color:#ffffff; padding-top:2px; text-align:left; padding-bottom: 20px" class="body_copy mob_txt_center">Durante la marcha el sistema monitorea el camino buscando espacios vacíos. Una vez encontrado, el conductor debe pasar al cambio que le solicita el sistema en pantalla y a partir de ese momento solo debe operar el acelerador y freno.</td>
  </tr>
</table></td>
               </tr>
           </table><table role="presentation" align="right" width="300" border="0" cellspacing="0" cellpadding="0" class="U-FULLWIDTH" style="width:300px; min-width:300px;">
             <tr>
                 <td valign="top"><img src="https://image.ar-mail.ford.com/lib/fe3411747364047c741373/m/1/ffad6991-9248-41ea-8cec-dddb6be0d968.jpg" width="300" height="216" alt="" class="U-RESPONSIVE-IMAGE" style="display:block; border:0"/></td>
               </tr>
           </table></td>
         </tr>
       </table></td>
     </tr>
   </tbody>
 </table> <!-- /body-copy--dark-grey SF -->
    </td>
  </tr>
</table>
</td>
    <td style="font-size:0px">&nbsp;</td>
  </tr>
</table> 
<!-- /box2->

 <!--box 1-->
<table class="LIMON-SECTION" width="100%" border="0" cellspacing="0" cellpadding="0" bgcolor="#ffffff" role="presentation" style="table-layout:fixed">
  <tr>
  <td style="font-size:0px">&nbsp;</td>
  <td align="center" width="600" bgcolor="#ffffff" style="width:600px; min-width:600px;" class="LIMON-PANEL">
<table role="presentation" border="0" cellpadding="0" cellspacing="0" width="100%">
  <tr>
    <td >
      

 <!-- body-copy--dark-grey SF -->
 <table width="100%" border="0" cellspacing="0" cellpadding="0">
   <tbody>
     
     <tr>
       <td style="padding-right: 20px" class="Padright_none"><table role="presentation"  width="100%" border="0" cellspacing="0" cellpadding="0">
         <tr>
           <td ><table role="presentation" align="right" width="240" border="0" cellspacing="0" cellpadding="0" class="U-FULLWIDTH" style="width:240px; min-width:240px;">
             <tr>
                 <td valign="top" class="mobile_margins"><table role="presentation" width="100%" border="0" cellspacing="0" cellpadding="0">
  
  <tr>
    <td align="right" style="font-family:Verdana, Helvetica Neue, Helvetica, sans-serif, OpenSans; font-size:14px; line-height:18px; color:#0a115a; padding-top:50px; font-weight: bold; text-align:right" class="body_copy mob_txt_center mob_padTop">ALERTA DE COLISIÓN FRONTAL CON FRENADO AUTÓNOMO DE EMERGENCIA</td>
  </tr>
  <tr>
    <td align="right" style="font-family:Verdana, Helvetica Neue, Helvetica, sans-serif, OpenSans; font-size:12px; color:#0a115a; padding-top:2px; text-align:right; padding-bottom:10px" class="body_copy mob_txt_center">Ante una posible colisión el sistema indicará al conductor y accionará automáticamente los frenos. </td>
  </tr>
</table></td>
               </tr>
           </table><table role="presentation" align="left" width="300" border="0" cellspacing="0" cellpadding="0" class="U-FULLWIDTH" style="width:300px; min-width:300px;">
             <tr>
                 <td valign="top"><img src="https://image.ar-mail.ford.com/lib/fe3411747364047c741373/m/1/1adb0c7f-7c4a-4b72-a636-c3b878c0663d.jpg" width="300" height="216" alt="" class="U-RESPONSIVE-IMAGE" style="display:block; border:0"/></td>
               </tr>
           </table></td>
         </tr>
       </table></td>
     </tr>
   </tbody>
 </table> <!-- /body-copy--dark-grey SF -->
    </td>
  </tr>
</table>
</td>
    <td style="font-size:0px">&nbsp;</td>
  </tr>
</table> 
<!-- /box1->

<!--box 2-->
<table class="LIMON-SECTION" width="100%" border="0" cellspacing="0" cellpadding="0" bgcolor="#ffffff" role="presentation" style="table-layout:fixed">
  <tr>
  <td style="font-size:0px">&nbsp;</td>
  <td align="center" width="600" bgcolor="#ffffff" style="width:600px; min-width:600px;" class="LIMON-PANEL">
<table role="presentation" border="0" cellpadding="0" cellspacing="0" width="100%">
  <tr>
    <td >
      

 <!-- body-copy--dark-grey SF -->
 <table width="100%" border="0" cellspacing="0" cellpadding="0" style="line-height: 1.2;">
   <tbody>
     
     <tr>
       <td style="padding-left: 20px; background-color: #00025c" class="Padleft_none" ><table role="presentation"  width="100%" border="0" cellspacing="0" cellpadding="0">
         <tr>
           <td ><table role="presentation" align="left" width="280" border="0" cellspacing="0" cellpadding="0" class="U-FULLWIDTH" style="width:280px; min-width:280px;">
             <tr>
                 <td valign="top" class="mobile_margins"><table role="presentation" width="100%" border="0" cellspacing="0" cellpadding="0">
  
  <tr>
    <td align="right" style="font-family:Verdana, Helvetica Neue, Helvetica, sans-serif, OpenSans; font-size:15px; line-height:18px; color:#ffffff; padding-top:60px; font-weight: bold; text-align:left;" class="mob_txt_center mob_padTop">ALERTA DE CAMBIO DE CARRIL</td>
  </tr>
  <tr>
    <td align="right" style="font-family:Verdana, Helvetica Neue, Helvetica, sans-serif, OpenSans; font-size:12px; color:#ffffff; padding-top:2px; text-align:left; padding-bottom: 30px" class="body_copy mob_txt_center">El vehículo alertará al conductor cuando detecte que el mismo se desvía del carril.</td>
  </tr>
</table></td>
               </tr>
           </table><table role="presentation" align="right" width="300" border="0" cellspacing="0" cellpadding="0" class="U-FULLWIDTH" style="width:300px; min-width:300px;">
             <tr>
                 <td valign="top"><img src="https://image.ar-mail.ford.com/lib/fe3411747364047c741373/m/1/08ed5362-d09a-49a0-8a9a-9b9bbf9583b8.jpg" width="300" height="216" alt="" class="U-RESPONSIVE-IMAGE" style="display:block; border:0"/></td>
               </tr>
           </table></td>
         </tr>
       </table></td>
     </tr>
   </tbody>
 </table> <!-- /body-copy--dark-grey SF -->
    </td>
  </tr>
</table>
</td>
    <td style="font-size:0px">&nbsp;</td>
  </tr>
</table> 
<!-- /box2-> 

 






  <!--cta-->
<table class="LIMON-SECTION" width="100%" border="0" cellspacing="0" cellpadding="0" bgcolor="#ffffff" role="presentation" style="table-layout:fixed">
  <tr>
  <td style="font-size:0px">&nbsp;</td>
  <td align="center" width="600" bgcolor="#FFFFFF" style="width:600px; min-width:600px;" class="LIMON-PANEL">
<table role="presentation" border="0" cellpadding="0" cellspacing="0" width="100%">
  <tr>
    <td style="padding:10px;"><table role="presentation"  width="100%" border="0" cellspacing="0" cellpadding="0">
      
      <tr>
        <td align="center" style="padding-top:60px; padding-bottom:10px;" class="mobile_margins"><table border="0" width="210" cellpadding="0" cellspacing="0" align="center">
      <tr>
        <td style="font-family: Verdana, Geneva, sans-serif;font-size:13px;text-align:center;"><div>
          <!--[if mso]><v:roundrect xmlns:v="urn:schemas-microsoft-com:vml" xmlns:w="urn:schemas-microsoft-com:office:word" style="height:41px;v-text-anchor:middle;width:210px;" arcsize="35%" stroke="f" fillcolor="#00085b"><w:anchorlock/><center><![endif]-->
          <a href="#" style="background-color:#00085b;border-radius:30px;color:#FFFFFF;display:inline-block;font-family: Arial, Helvetica, Verdana, Geneva, sans-serif;font-size:13px;line-height:37px;text-align:center;text-decoration:none;width:210px;-webkit-text-size-adjust:none;" target="_blank">Conocé más</a>
          <!--[if mso]></center></v:roundrect><![endif]-->
        </div></td>
      </tr>
    </table></td>
      </tr>
    </table></td>
  </tr>
</table>
</td>
    <td style="font-size:0px">&nbsp;</td>
  </tr>
</table> 
<!-- /cta-->
 <!--txt1-->
<table class="LIMON-SECTION" width="100%" border="0" cellspacing="0" cellpadding="0" bgcolor="#ffffff" role="presentation" style="table-layout:fixed">
  <tr>
  <td style="font-size:0px">&nbsp;</td>
  <td align="center" width="600" bgcolor="#ffffff" style="width:600px; min-width:600px;" class="LIMON-PANEL">
<table role="presentation" border="0" cellpadding="0" cellspacing="0" width="100%">
  <tr>
    <td class="mobile_margins" style="padding-right:40px; padding-left:40px; padding-bottom:55px;">
    

<table role="presentation" width="100%" border="0" cellspacing="0" cellpadding="0">

  
  
  <tr>
    <td align="left" style="font-family: Arial, Helvetica Neue, Helvetica, sans-serif, OpenSans; font-size:16px; line-height:23px; color:#7b7b7a;  text-align: center; " class="body_copy">Antes de retirar tu vehículo, consultá con tu asesor sobre las ventajas que ofrece el servicio <a href="https://www.ford.com.ar/posventa/ford-protect/" style="color: #009fe3">FORD <strong>PROTECT</strong>(*)</sup></a></td>
  </tr>
 
</table>


    </td>
  </tr>
</table>
</td>
    <td style="font-size:0px">&nbsp;</td>
  </tr>
</table> 
<!--/txt1-->
 <!--ford pass -->
<table class="LIMON-SECTION" width="100%" border="0" cellspacing="0" cellpadding="0" bgcolor="#ffffff" role="presentation" style="table-layout:fixed">
  <tr>
  <td style="font-size:0px">&nbsp;</td>
  <td align="center" width="600" bgcolor="#f8f8f8" style="width:600px; min-width:600px;" class="LIMON-PANEL">
<table role="presentation" border="0" cellpadding="0" cellspacing="0" width="100%">
  <tr>
    <td class="mobile_margins" style="padding-right:40px; padding-left:40px; padding-bottom:35px; padding-top:35px">
    

<table role="presentation" width="100%" border="0" cellspacing="0" cellpadding="0">

  
  
  <tr>
    <td align="center" style="font-family: Arial, Helvetica Neue, Helvetica, sans-serif, OpenSans; font-size:16px; line-height:23px; color:#7b7b7a;  text-align: center; padding-bottom: 25px" class="body_copy"><img src="https://image.ar-mail.ford.com/lib/fe3411747364047c741373/m/1/b301600a-be3c-445f-b327-0d7921cb6448.png" width="83" height="65" alt="FordPass"/></td>
  </tr>
  <tr>
    <td align="center" style="font-family: Arial, Helvetica Neue, Helvetica, sans-serif, OpenSans; font-size:18px; line-height:23px; color:#000e45;  text-align: center; padding-bottom: 20px " class="body_copy">¿Sabías que también podés descargarte FordPass?</td>
  </tr>
  <tr>
    <td align="left" style="font-family: Arial, Helvetica Neue, Helvetica, sans-serif, OpenSans; font-size:12px; line-height:18px; color:#000e45;  text-align: center; " class="body_copy">Desarrollamos una app exclusiva para que te relaciones con tu Ford y te muevas de forma inteligente: Vas a poder agendar el service de tu vehículo en cualquier concesionario oficial, disponer de asistencia mecánica las 24 hs, recibir alertas de mantenimiento y comunicarte con nuetro equipo de expertos. </td>
  </tr>
  <tr>
    <td align="center" style="padding-top:30px; padding-bottom:20px;" class="mobile_margins"><table border="0" width="210" cellpadding="0" cellspacing="0" align="center">
      <tr>
        <td style="font-family: Verdana, Geneva, sans-serif;font-size:13px;text-align:center;"><div>
          <!--[if mso]><v:roundrect xmlns:v="urn:schemas-microsoft-com:vml" xmlns:w="urn:schemas-microsoft-com:office:word" style="height:41px;v-text-anchor:middle;width:210px;" arcsize="35%" stroke="f" fillcolor="#00085b"><w:anchorlock/><center><![endif]-->
          <a href="https://www.ford.com.ar/posventa/fordpass/descargar/" style="background-color:#00085b;border-radius:30px;color:#FFFFFF;display:inline-block;font-family: Arial, Helvetica, Verdana, Geneva, sans-serif;font-size:13px;line-height:37px;text-align:center;text-decoration:none;width:210px;-webkit-text-size-adjust:none;" target="_blank">Descargá Fordpass</a>
          <!--[if mso]></center></v:roundrect><![endif]-->
        </div></td>
      </tr>
    </table></td>
  </tr>
 
</table>


    </td>
  </tr>
</table>
</td>
    <td style="font-size:0px">&nbsp;</td>
  </tr>
</table> 
<!--/fordpass-->
 
  <!--cta-->
<table class="LIMON-SECTION" width="100%" border="0" cellspacing="0" cellpadding="0" bgcolor="#ffffff" role="presentation" style="table-layout:fixed">
  <tr>
  <td style="font-size:0px">&nbsp;</td>
  <td align="center" width="600" bgcolor="#FFFFFF" style="width:600px; min-width:600px;" class="LIMON-PANEL">
<table role="presentation" border="0" cellpadding="0" cellspacing="0" width="100%">
  <tr>
    <td  class="mobile_margins"><table role="presentation"  width="100%" border="0" cellspacing="0" cellpadding="0">
      
      <tr>
        <td align="center" style="padding-top:30px; padding-bottom:17px;" class="mobile_margins"><img src="https://image.ar-mail.ford.com/lib/fe3411747364047c741373/m/1/b73902b4-0e1d-4f39-916a-e2a08f58340a.png" width="282" height="34" alt="FORDI" class="U-RESPONSIVE-IMAGE"/></td>
      </tr>
      <tr>
      <td align="center" valign="top"  style="font-family:Arial, Helvetica Neue, Helvetica, sans-serif, OpenSans; font-size:12px; line-height:15px; color:#000000; text-align:center;" class="body_copy ">Chateá con FORDi las 24 hrs</td>
      </tr>
      <tr>
        <td align="center" style="padding-top:30px; padding-bottom:40px;"><table border="0" width="240" cellpadding="0" cellspacing="0" align="center">
      <tr>
        <td style="font-family: Verdana, Geneva, sans-serif;font-size:13px;text-align:center;"><div>
          <!--[if mso]><v:roundrect xmlns:v="urn:schemas-microsoft-com:vml" xmlns:w="urn:schemas-microsoft-com:office:word" style="height:41px;v-text-anchor:middle;width:240px;" arcsize="35%" stroke="f" fillcolor="#00085b"><w:anchorlock/><center><![endif]-->
          <a href="https://api.whatsapp.com/send/?phone=5491135909236&text=Hola%21&type=phone_number&app_absent=0 " style="background-color:#00085b;border-radius:30px;color:#FFFFFF;display:inline-block;font-family: Arial, Helvetica, Verdana, Geneva, sans-serif;font-size:13px;line-height:37px;text-align:center;text-decoration:none;width:240px;-webkit-text-size-adjust:none;" target="_blank">Ir a WhatsApp&nbsp;   <span style="font-size: 15px">&gt;</span></a>
          <!--[if mso]></center></v:roundrect><![endif]-->
        </div></td>
      </tr>
    </table></td>
      </tr>
    </table></td>
  </tr>
</table>
</td>
    <td style="font-size:0px">&nbsp;</td>
  </tr>
</table> 
<!-- /cta-->
  <!--redes-->
<table class="LIMON-SECTION" width="100%" border="0" cellspacing="0" cellpadding="0" bgcolor="#ffffff" role="presentation" style="table-layout:fixed">
  <tr>
  <td style="font-size:0px">&nbsp;</td>
  <td align="center" width="600" bgcolor="#FFFFFF" style="width:600px; min-width:600px;" class="LIMON-PANEL">
<table role="presentation" border="0" cellpadding="0" cellspacing="0" width="100%">
  <tr>
    <td style="padding:0px;"><table role="presentation"  width="100%" border="0" cellspacing="0" cellpadding="0">
      
      <tr>
        <td align="center" style="padding-top:30px; padding-bottom:40px; padding-left: 45px; padding-right: 45px; border-top:1px solid #EEEEEE" class="mobile_margins" ><table width="100%"  border="0" align="center" cellpadding="0" cellspacing="0" class="U-FULLWIDTH" role="presentation">
             <tr>
               <td valign="top" align="center"><table width="100%" border="0" align="left" cellpadding="0" cellspacing="0">
                 <tbody>
                   <tr>
                     <td align="center" valign="top"  style="font-family:Arial, Helvetica Neue, Helvetica, sans-serif, OpenSans; font-size:12px; line-height:15px; color:#00095b; text-align:center; padding-bottom: 20px" class="body_copy "><strong>Encontranos en:</strong></td>
                   </tr>
            <tr>
                     <td align="center" valign="top" ><table width="184" border="0" cellspacing="0" cellpadding="0">
                       <tbody>
                       <tr>
                           <td><table width="100%" border="0" cellspacing="0" cellpadding="0">
                             <tbody>
                               <tr>
                                 <td style="padding-right: 20px"><a href="https://www.facebook.com/fordargentina"><img src="https://image.ar-mail.ford.com/lib/fe3411747364047c741373/m/1/5c9170be-9ad7-4440-a03a-990751f9fd48.png" width="27" height="26" alt="Facebook" border="0" style="display:block; -ms-interpolation-mode: bicubic;" /></a></td>
                                 <td style="padding-right: 20px"><a href="https://www.instagram.com/fordargentina"><img src="https://image.ar-mail.ford.com/lib/fe3411747364047c741373/m/1/4cb83d83-f907-4ca3-865e-d32c24ff1fa4.png" width="27" height="27" alt="Instagram" border="0" style="display:block; -ms-interpolation-mode: bicubic;" /></a></td>
                                 <td style="padding-right: 20px"><a href="https://www.youtube.com/user/fordargentina8/featured"><img src="https://image.ar-mail.ford.com/lib/fe3411747364047c741373/m/1/fd6e8da4-dc54-4316-9be1-1333118d1a5e.png" width="38" height="27" alt="" border="0" style="display:block; -ms-interpolation-mode: bicubic;" /></a></td>
                                 <td ><a href="https://www.linkedin.com/company/fordargentina"><img src="https://image.ar-mail.ford.com/lib/fe3411747364047c741373/m/1/ad89f67a-ed45-4f44-9331-d35795dcfb14.png" width="27" height="27" alt="" border="0" style="display:block; -ms-interpolation-mode: bicubic;" /></a></td>
                               </tr>
                             </tbody>
                           </table></td>
                         </tr>
                         <tr>
                           <td align="center" style="padding-top:27px; padding-bottom: 20px"><a href="http://www.ford.com.ar?emailid=newsletter-home"><img src="https://image.ar-mail.ford.com/lib/fe3411747364047c741373/m/1/b6d7c194-0892-49b0-bb9a-24b4f0215abb.png" width="92" height="23" alt="" border="0" style="display:block; -ms-interpolation-mode: bicubic;" /></a></td>
                         </tr>
                         <tr>
                           <td align="center"><img src="https://image.ar-mail.ford.com/lib/fe3411747364047c741373/m/1/63d95a38-4699-458d-ba85-0ba7c5ea54f8.png" width="143" height="12" alt="" border="0" style="display:block; -ms-interpolation-mode: bicubic;" /></td>
                         </tr>
                       </tbody>
                     </table></td>
                   </tr>
                   
                 </tbody>
               </table></td>
             </tr>
         </table></td>
      </tr>
    </table></td>
  </tr>
</table>
</td>
    <td style="font-size:0px">&nbsp;</td>
  </tr>
</table> 
<!-- /cta-->
 <!-- FOOTER -->
<table class="LIMON-SECTION" width="100%" border="0" cellspacing="0" cellpadding="0" bgcolor="#ffffff" role="presentation" style="table-layout:fixed">
  <tr>
  <td style="font-size:0px">&nbsp;</td>
  <td align="center" width="600" bgcolor="#ffffff" style="width:600px; min-width:600px;" class="LIMON-PANEL">
<table role="presentation" border="0" cellpadding="0" cellspacing="0" width="100%">
  <tr>
    <td >
     
      <table role="presentation" border="0" cellpadding="0" cellspacing="0" width="100%">
  <tr>
    <td>
<!-- mobile-footer -->
<!--[if !mso 9]><!-->
<div class="mobilecontent" style="display:none; max-height:0px; overflow:hidden;">
  <table role="presentation" border="0" cellspacing="0" cellpadding="0">
    <tr>
      <td ><a href="http://www.ford.com.ar" target="_blank"><img src="https://image.ar-mail.ford.com/lib/fe3411747364047c741373/m/1/72fcb6d2-2b87-4b38-a27c-4f67eeef3981.png" width="600" height="100" class="U-RESPONSIVE-IMAGE" border="0" style="display:block; -ms-interpolation-mode: bicubic;" alt="Ford logo" /></a></td>
    </tr>
  </table>
</div>
<!--<![endif]--> 
<!-- /mobile-footer-->
<!-- desktop footer-->
      <table role="presentation" class="mob_hide" border="0" cellspacing="0" cellpadding="0">
        <tr>
    <td ><a href="http://www.ford.com.ar?emailid=newsletter-home" target="_blank"><img src="https://image.ar-mail.ford.com/lib/fe3411747364047c741373/m/1/22993031-fcb3-4b47-bd8c-86fdf661900c.png" width="600" height="106" class="U-RESPONSIVE-IMAGE" border="0" style="display:block; -ms-interpolation-mode: bicubic;" alt="Ford logo" /></a></td>
        </tr>
      </table>  
<!-- /desktop footer-->  
    </td>
  </tr>
</table>


    </td>
  </tr>
</table>
</td>
    <td style="font-size:0px">&nbsp;</td>
  </tr>
</table> 
 <!--/FOOTER-->
 
 
<table class="LIMON-SECTION" width="100%" border="0" cellspacing="0" cellpadding="0" bgcolor="#ffffff" role="presentation" style="table-layout:fixed">
  <tr>
  <td style="font-size:0px">&nbsp;</td>
  <td align="center" width="600" bgcolor="#01095c" style="width:600px; min-width:600px;" class="LIMON-PANEL">
<table role="presentation" border="0" cellpadding="0" cellspacing="0" width="100%">
  <tr>
    <td  style="padding:10px; padding-bottom:10px; padding-top: 20px"> 
      <!-- smallprint--left--dark-grey SF -->
<table role="presentation" width="100%" border="0" cellspacing="0" cellpadding="0">
 
  <tr>
    <td align="left" style="font-family: Arial, Helvetica Neue, Helvetica, sans-serif, OpenSans; font-size:9px; line-height:12px; text-align:justify;color:#ffffff; padding-top:0; padding-bottom:0px;" class="smallprint">Usted tiene el derecho de solicitar el retiro o el bloqueo total o parcial de sus datos personales que cargó en la base de datos de Ford Argentina S.C.A., incluyendo el dejar de recibir comunicaciones con fines publicitarios en la presente casilla. Para desuscribirse haga <a href="%%=RedirectTo(CloudPagesURL(1542))=%%" style="color:#636363;">click aquí</a>.   
      El titular podrá en cualquier momento solicitar el retiro o bloqueo de su nombre de los bancos de datos a los que se refiere el presente artículo (art. 27, inc. 3, Ley 25.326). En toda comunicación con fines de publicidad que se realice por correo, teléfono, correo electrónico, Internet u otro medio a distancia a conocer, se deberá indicar, en forma expresa y destacada, la posibilidad del titular del dato de solicitar el retiro o bloqueo, total o parcial, de su nombre de la base de datos.<br><p>
      Dirección del remitente: %%member_busname%% %%member_addr%% %%member_city%% %%member_state%% %%member_postalcode%% %%member_country%%<br><p> </td>
  </tr>
</table>
<!-- /smallprint--left--dark-grey SF --></td>
  </tr>
</table>
</td>
    <td style="font-size:0px">&nbsp;</td>
  </tr>
</table>

</html>
</body>
