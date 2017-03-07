<DOCTYPE html>
<html>
        <head>
            <title>Lista de Compras</title>
            <meta charset="UTF8" />
            <script type="text/javascript">
                    function ClicarNoBotao(fruta)
                    {
                        if(fruta == 'morangos')
                        {
                         ComprarFruta(fruta, document.getElementById('NdeMorangos').value); 
                    }
                        if(fruta == 'bananas')
                        {
                         ComprarFruta(fruta, document.getElementById('NdeBananas').value); 
                    }
                        if(fruta == 'macas')
                        {
                         ComprarFruta(fruta, document.getElementById('NdeMacas').value); 
                    }
                        if(fruta == 'peras')
                        {
                         ComprarFruta(fruta, document.getElementById('NdePeras').value); 
                    }
                    }

                    function ComprarFruta(fruta,mensagem)
                    {
                          if(mensagem)
                        {
                            alert ("Você precisa de  " + mensagem + "  " + fruta);
                        }
                        else
                        {
                            alert("Informe a quantidade de " + fruta);
                        }
                    }





            
                 </script>
             <link rel="stylesheet" type="text/css" href="style.css"/>
           
        </head>

            <body>
                <div class="tudo">
                <div class="tarefa">
                  <p>
                    tarefa 1: lista de compras
                  </p>
                  <br/>
                  <table>
                      <thead>
                          <tr>
                            <th>fruta</th>
                            <th>imagem</th>
                            <th>quantidade</th>
                            <th>Ação</th>
                          </tr>                                

                      </thead>
                          <tbody>
                              <tr>
                                <td>Maça</td>
                                <td> <img width=10px src="http://www.imagenspng.com.br/wp-content/uploads/2015/04/branca-de-neve-cute-maca-01.png" /></td>
                                <td><input type="text"  ID="NdeMacas" /> </td>
                                <td> <input type="button" onclick="ClicarNoBotao('macas')"></td>
                                    <!-- TR é uma nova LINHA -->
                              </tr>
                                <td>Pêra</td>
                                <td> <img src="http://bs.simplusmedia.com/i/f/o/saude/conteudo/Pera.jpg" width= 10px> </td>
                                <td> <input type="text" ID="NdePeras" /> </td>
                                <td><input type="button" onclick="ClicarNoBotao('peras')"/></td>
                              </tr>

                               <tr>
                                   <td>Banana</td>
                                   <td><img src="http://bs.simplusmedia.com/i/730/838/banana-beneficios.jpg" width=20px/></td>
                                   <td><input type="text" ID="NdeBananas"/></td>
                                   <td><input type="button" onclick="ClicarNoBotao('bananas')"/></td>
                                </tr>

                                   <td>Morango</td>
                                   <td><img src="http://cdn5.colorir.com/desenhos/color/201343/morango-feliz-comida-frutas-pintado-por-majestade-1044358.jpg" width=10px/> </td>
                                   <td> <input type="text"  ID="NdeMorangos"/> </td>
                                   <td> <input type="button" onclick="ClicarNoBotao('morangos')"/> </td>



                                </tr>           



                          <tbody>

                 </table>

                 <!--
                </div>
                    
                    <div class="frutas">
                    <h1> FRUTAS </h1>
                        <br />
                        <div class="maca">
                          <p1 style="font-style:oblique; font-family:Lucida Sans"> Maçãs 
                            <div> <input type="text"  ID="NdeMacas" />
                                                                      
                            <input type="image" src="http://www.imagenspng.com.br/wp-content/uploads/2015/04/branca-de-neve-cute-maca-01.png" alt="maca" onclick="ClicarNoBotao('macas')" > 
                            </img>
                            </div> 
                            
                        </p1>
                        </div>
                        <div class="pera">
                            <p2 style="font-style:oblique; font-family:Lucida Sans"> Pêras <br/>
                            <input type="text" ID="NdePeras" />
                            
                           <input type="image" src="http://bs.simplusmedia.com/i/f/o/saude/conteudo/Pera.jpg" alt="pera" onclick="ClicarNoBotao('peras')" />
                            </img>
                            </p2>
                        </div>

                        <div class="banana"
                            <p3 style="font-style:oblique;font-family:Lucida Sans "> Bananas </p3> <br/>
                            <input type="text" ID="NdeBananas"/>
                            
                           <input type="image" src="http://bs.simplusmedia.com/i/730/838/banana-beneficios.jpg" alt="banana" onclick="ClicarNoBotao('bananas')"/>
                            </img>


                        </div>
                            <div class="morango">
                            <p1 style="font-style:oblique;font-family:Lucida Sans "> Morangos <br/>
                            <input type="text"  ID="NdeMorangos"/>
                            
                          <input type="image" src="http://cdn5.colorir.com/desenhos/color/201343/morango-feliz-comida-frutas-pintado-por-majestade-1044358.jpg" alt="morango" onclick="ClicarNoBotao('morangos')"/> 
                          
                            </p1>
                            </div>
                    </div>
                    -->
                          <div class="hackerman"  <p12 style="font-size:9px; text-align:right"> by Hackerman
                                </p12> </div>
                                </div>
                </body>
</html>
