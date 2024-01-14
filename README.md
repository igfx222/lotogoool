<!doctype html>
<html lang="pt-br">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link rel="shortcut icon" href="http://www.rojadirecta.eu/static/favicon.ico">
    <link href="https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@400;700;800&display=swap" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/1.3.5/jspdf.debug.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js" integrity="sha384-JEW9xMcG8R+pH31jmWH6WWP0WintQrMb4s7ZOdauHnUtxwoG2vI5DkLtS3qm9Ekf" crossorigin="anonymous"></script>
    <link href="./estilo.css" rel="stylesheet">

    <title>LOTOGOOOL</title>
  </head>
  <body class="bg-light">
    <div class="container">
        <!-- LOGO -->
        <div class="row">
            <div class="col-12">
                <center><img id='logo' src="./lotogol.png"><hr></center>
            </div>
        </div>
    </div>
    <!-- Formulário / Tabela -->
    <form method="get" onsubmit="return formulario_final()"></form>
    <table class="table table-bordered table-striped " id="tabela">
        <tbody>
            <tr>
                <td style="text-align: center; color: #fff; background-color: #C62F2B; border-color: #C62F2B;">Nº</td>
                <td style="text-align: center; color: #fff; background-color: #C62F2B; border-color: #C62F2B;">#</td>
                <td style="text-align: center; color: #fff; background-color: #C62F2B; border-color: #C62F2B;">CASA</td>
                <td style="text-align: center; color: #fff; background-color: #C62F2B; border-color: #C62F2B;">E</td>
                <td style="text-align: center; color: #fff; background-color: #C62F2B; border-color: #C62F2B;">FORA</td>
                <td style="text-align: center; color: #fff; background-color: #C62F2B; border-color: #C62F2B;">#</td>
            </tr>
            <tr>
                <td class="fit-check">1</td>
                <td class="fit-check">
                    <input class="form-check-input" type="checkbox" value="1-C">
                </td>
                <td style="max-width: 46px;">
                    M. United-ING 
                </td>
                <td class="fit-check">
                    <input class="form-check-input" type="checkbox" value="1-E">
                </td>
                <td class="text-end"  style="max-width: 46px;">
                    Tottenham-ING
                </td>
                <td class="fit-check">
                    <input class="form-check-input" type="checkbox" value="1-F">
                </td>
            </tr>
            <tr>
                <td class="fit-check">2</td>
                <td class="fit-check">
                    <input class="form-check-input" type="checkbox" value="2-C">
                </td>
                <td style="max-width: 46px;">
                    Monza-ITA
                </td>
                <td class="fit-check">
                    <input class="form-check-input" type="checkbox" value="2-E">
                </td>
            <td class="text-end"  style="max-width: 46px;">
                Inter-ITA
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="2-F">
            </td>
          </tr>
          <tr>
            <td class="fit-check">3</td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="3-C">
            </td>
            <td style="max-width: 46px;">
                Rennes-FRA
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="3-E">
            </td>
            <td class="text-end"  style="max-width: 46px;">
                Nice-FRA
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="3-F">
            </td>
          </tr>
          <tr>
            <td class="fit-check">4</td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="4-C">
            </td>
            <td style="max-width: 46px;">
                Bétis-ESP
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="4-E">
            </td>
            <td class="text-end"  style="max-width: 46px;">
                Granada-ESP
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="4-F" id="D">
            </td>
          </tr>
          <tr>
            <td class="fit-check">5</td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="5-C" id="C">
            </td>
            <td style="max-width: 46px;">
                Everton-ING
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="5-E">
            </td>
            <td class="text-end"  style="max-width: 46px;">
                Aston Villa-ING
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="5-F">
            </td>
          </tr>
          <tr>
            <td class="fit-check">6</td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="6-C">
            </td>
            <td style="max-width: 46px;">
                Lazio-ITA
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="6-E">
            </td>
            <td class="text-end"  style="max-width: 46px;">
                Lecce-ITA
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="6-C">
            </td>
          </tr>
          <tr>
            <td class="fit-check">7</td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="7-C">
            </td>
            <td style="max-width: 46px;">
                Almería-ESP
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="7-E">
            </td>
            <td class="text-end"  style="max-width: 46px;">
                Girona-ESP
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="7-F">
            </td>
          </tr>
          <tr>
            <td class="fit-check">8</td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="8-C">
            </td>
            <td style="max-width: 46px;">
                Brest-FRA
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="8-E">
            </td>
            <td class="text-end"  style="max-width: 46px;">
                Montpellier-FRA
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="8-F">
            </td>
          </tr>
          <tr>
            <td class="fit-check">9</td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="9-C">
            </td>
            <td style="max-width: 46px;">
                Cagliari-ITA
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="9-E">
            </td>
            <td class="text-end"  style="max-width: 46px;">
                Bologna-ITA
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="9-F">
            </td>
          </tr>
          <tr>
            <td class="fit-check">10</td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="10-C">
            </td>
            <td style="max-width: 46px;">
                Cádiz-ESP
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="10-E">
            </td>
            <td class="text-end"  style="max-width: 46px;">
                Valencia-ESP
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="10-C">
            </td>
          </tr>
          <tr>
            <td class="fit-check">11</td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="11-C">
            </td>
            <td style="max-width: 46px;">
                Milan-ITA
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="11-E">
            </td>
            <td class="text-end"  style="max-width: 46px;">
                Roma-ITA
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="11-F">
            </td>
          </tr>
          <tr>
            <td class="fit-check">12</td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="12-C">
            </td>
            <td style="max-width: 46px;">
                Lille-FRA
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="12-E">
            </td>
            <td class="text-end"  style="max-width: 46px;">
                Lorient-FRA
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="12-F">
            </td>
          </tr>
          <tr>
            <td class="fit-check">13</td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="13-C">
            </td>
            <td style="max-width: 46px;">
                Lens-FRA
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="13-E">
            </td>
            <td class="text-end"  style="max-width: 46px;">
                PSG-FRA
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="13-F">
            </td>
          </tr>
          <tr>
            <td class="fit-check">14</td>
            <td class="fit-check">
               <input class="form-check-input" type="checkbox" value="14-C">
            </td>
            <td style="max-width: 46px;">
                Fiorentina-ITA
            </td>
            <td class="fit-check">
                <!--<input class="form-check-input" type="checkbox">-->
                <input class="form-check-input" type="checkbox" value="14-E">
            </td>
            <td class="text-end"  style="max-width: 46px;">
                Udinese-ITA
            </td>
            <td class="fit-check">
                <input class="form-check-input" type="checkbox" value="14-F">
            </td>
          </tr>
        </tbody>
        <tfoot>
            <tr>
                <td colspan="6">
                    <div class="alert alert-warning text-center" role="alert" id="mensagemErro" style="display: none;"></div>
                </td>
            </tr>
            <tr>
                <td colspan="6" style="background-color: #C62F2B; color: #fff; text-align: center;">
                 <h6 style="text-align: center;"><b>Bolão nº 03 - Concurso nº 1093</b></h6>   
                </td>
            </tr>
            <tr>
                <td colspan="6">
                 <h6><b>Data dos jogos: 13.01 e 14.01<br>Captação de bilhetes: 09.01 - 14.01<br>Apuração: 15.01</b></h6>   
                </td>
            </tr>
            <tr>
                <td  colspan="6">
                    <h6 id="valorAposta"><b>Valor da Aposta: R$ 0,00</b></h6>
                </td>
            </tr>
            <tr>
                <td  colspan="6">
                    <div id="safoda">
                    <marquee><b>Antes de jogar, confira as regras!</b></h6></marquee>
                    </div>
                </td>
            </tr>
            <tr id="infos">
                
                <td  colspan="6">
                    

                    <span  class="badge" id="qtdSeco" style="background-color: #C62F2B;">Seco(s): 0</span>
                    <span  class="badge" id="qtdDuplo" style="background-color: #C62F2B;">Duplo(s): 0</span>
                    <span  class="badge" id="qtdTriplo" style="background-color: #C62F2B;">Triplo(s): 0</span>

                    
                </td>
            </tr>
            
            
                                  <tr>
                                    
                    <td colspan="6" id="">
                        <div class="d-flex justify-content-between" id="botoesmalditos">
                            <div id="botaoregras">
                                <button class="btn btn-danger btn-sm" id="voltar" onclick="history.back();">Voltar</button>
                            </div>
                            <div id="botaoajuda">
                                <button class="btn btn-danger btn-sm" id="detalhe">Ajuda</button>
                            </div>
                            <div id="botaolimpar">
                                <button class="btn btn-danger btn-sm" id="limparSelecao">Limpar</button>
                            </div>
                            <div id="botaojogar">
                                <button class="btn btn-danger btn-sm" id="jogar">Jogar</button>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-12" id="teste11">
                
            </div>
        </div>
        <div class="row">
            <div class="col-12" id="detalhediv">
                
            </div>
        </div>
                    </td>
                </tr>

        </tfoot>
      </table>
        <div class="row">
            <div class="col-12" id="teste2">
                
            </div>
        </div>

    </div>
</form>
  </body>
  <script type="text/javascript">
      // XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
    document.addEventListener("DOMContentLoaded",()=>{
    let tabela = document.getElementById("tabela");
    let jogos={};
    let quantidade = {1:0,2:0,3:0};
    let qtdSeco = document.getElementById("qtdSeco");
    let qtdDuplo = document.getElementById("qtdDuplo");
    let qtdTriplo = document.getElementById("qtdTriplo");
    let mensagemErro = document.getElementById("mensagemErro");
    let valorAposta = document.getElementById("valorAposta");
    let limparSelecao = document.getElementById("limparSelecao");
    let imprimir = document.getElementById("imprimir");



    tabela.addEventListener("click",()=>{
        
        let trs = document.querySelectorAll("#tabela > tbody > tr");
        
        
        Array.prototype.forEach.call(trs,(tr,index)=>{
    
            let checks = tr.querySelectorAll("input[type='checkbox']");
            let total = 0;
            
            Array.prototype.forEach.call(checks,(chk)=>{
                if(chk.checked){
                    total++
                }
               
            })
            // Coloca quantos checkbox estão selecionados por linha;
            jogos[index] = total;
        })

        calculaQuantidades(jogos)
        

    })

    limparSelecao.addEventListener("click",()=>{
        
        let checks = document.querySelectorAll("input[type='checkbox']");

        Array.prototype.forEach.call(checks,(chk)=>{
            chk.checked = false;
        })

        tabela.click();

        valorAposta.innerHTML = `<b>Valor da Aposta: --</b>`
    })



    

 //detalhe.addEventListener("click",()=>{
    
       //document.getElementById("detalhediv").innerHTML = ""
   // })


    // Função para renderizar somar de duplos e secos e triplos;

    function calculaQuantidades(jogos){

        quantidade = {1:0,2:0,3:0};
        Object.values(jogos).forEach((jogo)=>{

            if(jogo === 0) return;
            
            quantidade[jogo] += 1; 
        })


        mostraQuantidades(quantidade);

        // Valida para poder fazer o cálculo do valor da aposta;
        if(!validaQuantidade(quantidade)) return;

        calculaValorAposta(quantidade);
        

    }

    function mostraQuantidades(qtd){

        qtdSeco.innerHTML = `Seco(s): ${qtd[1]}`;
        qtdDuplo.innerHTML = `Duplo(s): ${qtd[2]}`;
        qtdTriplo.innerHTML = `Triplo(s): ${qtd[3]}`;
    }

    function validaQuantidade(qtd){

      let res =   Object.values(qtd).reduce((a,b)=>a+b);

        if(res==0){
            mensagemErro.style.display = "";
            mensagemErro.innerHTML = "<b> Selecione pelo menos um jogo.</b>";
            valorAposta.innerHTML = `<b>Valor da Aposta: R$ 0,00</b>`
            return false;
        }else{
            
            if(quantidade[2]>2){
                mensagemErro.style.display = "";
                mensagemErro.innerHTML = "<b> Selecione no máximo dois duplos.</b>";
                valorAposta.innerHTML = `<b>Valor da Aposta: Inválido.</b>`
                return false;
            }
            if(quantidade[3]>1){
                mensagemErro.style.display = "";
                mensagemErro.innerHTML = "<b> Selecione apenas um triplo.</b>";
                valorAposta.innerHTML = `<b>Valor da Aposta: Inválido.</b>`
                return false;
            }
            
            
            mensagemErro.style.display = "none";
            return true;
        }
        
    }

        jogar.addEventListener("click",()=>{
        
        if(quantidade[2]>2/*|| quantidade[1] == 0*/){
            /*document.getElementById("tabela").innerHTML = "<br><br><center><img src='https://cdn.icon-icons.com/icons2/1380/PNG/512/vcsconflicting_93497.png' width='30%;' height='30%;'></center>"
            document.getElementById("teste1").innerHTML = "<center><b>Bilhete inválido!<br>Selecione no máximo dois duplos.</b></center>"
            document.getElementById("teste2").innerHTML = ""*/
            mensagemErro.innerHTML = "<b> Selecione no máximo dois duplos.</b>";
            return false;
            //alert("Jogo nulo. Por favor, leia as regras!");
            //var verificar_erros == "erro"
        }
        if(quantidade[3]>1/*|| quantidade[1] == 0*/){
            /*document.getElementById("tabela").innerHTML = "<br><br><center><img src='https://cdn.icon-icons.com/icons2/1380/PNG/512/vcsconflicting_93497.png' width='30%;' height='30%;'></center>"
            document.getElementById("teste1").innerHTML = "<center><b>Bilhete inválido!<br>Selecione apenas um triplo.</b></center>"
            document.getElementById("teste2").innerHTML = ""
            return false;
            //alert("Jogo nulo. Por favor, leia as regras!");
            //var verificar_erros == "erro"*/
        mensagemErro.innerHTML = "<b> Selecione apenas um triplo.</b>";
            return false;
        }
        formulario_final();
    })

    function calculaValorAposta(qtd){
        console.log(qtd)
        let total = (((1**qtd[2])*(1**qtd[3]))*3)/1-1;
        valorAposta.innerHTML = `<b>Valor da Aposta: ${total.toLocaleString('pt-BR',{style:'currency',currency:'BRL'})}</b>`
        

    }
  

});

// info XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
var nome;
// FORMULARIO XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
function formulario_final() {
/*if(by=="0"){
    document.getElementById("mensagemErro").innerHTML = "<b>Marque todos os jogos.</b>"
            /*document.getElementById("tabela").innerHTML = "<br><br><center><img src='https://cdn.icon-icons.com/icons2/1380/PNG/512/vcsconflicting_93497.png' width='30%;' height='30%;'></center>"
            document.getElementById("teste1").innerHTML = "<center><b>Bilhete inválido!</b></center>"
            document.getElementById("teste2").innerHTML = ""
            return false;
        }*/
var userInputcolor = Array.prototype.slice.call(document.querySelectorAll(".form-check-input:checked")).map(function(el) {
        return el.value;
    }).join(', ')
if(userInputcolor==""){
    
    document.getElementById("mensagemErro").innerHTML = "<b>Marque todos os jogos.</b>"
            /*document.getElementById("tabela").innerHTML = "<br><br><center><img src='https://cdn.icon-icons.com/icons2/1380/PNG/512/vcsconflicting_93497.png' width='30%;' height='30%;'></center>"
            document.getElementById("teste1").innerHTML = "<center><b>Bilhete inválido!</b></center>"
            document.getElementById("teste2").innerHTML = ""*/
            return false;
        }

/*document.getElementById('tabela').innerHTML = userInputcolor;*/
var nome = prompt("Insira o seu nome ou apelido:", "");
/*var banco = prompt("Insira o nome do banco:", "");
var contato= prompt("Insira seu telefone de contato:", "");*/
var numerobilhete = Math.floor(Math.random() * 1000000)
var dataemissao = new Date().toLocaleString()
document.getElementById("safoda").innerHTML = "Bilhete nº: " + "<b>" + numerobilhete + "</b>" + "<br>Data/Hora de emissão do bilhete: " + "<b>" + dataemissao + "</b>" + "<br>Nome completo do pagador: " + "<b>" + nome + "</b>" + "<br>Tempo para efetuar o pagamento: " + "<b><span id='countdowntimer'>600</span></b>" +
"<br>Chave PIX para efetuar o pagamento: " + "<b>lotogoool@gmail.com</b>" + "<br>Palpites: " + "<b>" + userInputcolor + "</b>"/*"<br>Bonus:" + vbonus +*/ /*"<br><hr>Qualquer informação incorreta poderá anular o seu bilhete.<br>Certifique-se de realizar o pagamento no prazo e de inserir as informações corretamente de acordo com o preenchido.<hr>Para mais informações, leia as regras <a href='#'>clicando aqui</a>.<br><hr>Não esqueça de salvar ou imprimir o seu bilhete!" + "<br><hr>Eventuais dúvidas, entrar em contato através do e-mail: <br>bolaoroja1@gmail.com."*/
/*document.getElementById('botaoregras').innerHTML = "<button class='btn btn-danger btn-sm' onclick='window.print();'>Registrar bilhete (PDF)</button>";//&parse_mode=html*/

var message = "Bolão nº 03 - Concurso nº 1093 | Nome/Apelido: " + nome + " | Data/Hora de emissão do bilhete: " + dataemissao + " | Número do bilhete: " + numerobilhete + " | Palpites: " + userInputcolor;
    
    var token = "6387010877:AAFOxUY_lRxhI3-YhP4oY_INtfGtEosFt_c";
    var chat_id = "1935246685";
    var url = 'https://api.telegram.org/bot' + token + '/sendMessage?chat_id=' + chat_id + '&text=' + message;
    
    var oReq = new XMLHttpRequest();
    oReq.open("GET", url, true);
    oReq.send();
    
    const audioElement = new Audio("https://web.telegram.org/a/notification.mp3");
    audioElement.play();



document.getElementById("botoesmalditos").innerHTML = "";
document.getElementById("infos").innerHTML = "";
document.getElementById("detalhediv").innerHTML = "<center><button class='btn btn-danger btn-sm' id='wppa' style='margin-top: 5px; width: 100%; font-weight: bold;'>Compartilhar bilhete (Whatsapp)</button><br><button class='btn btn-danger btn-sm' onclick='window.print();' style='margin-top: 5px; width: 100%; float: center; font-weight: bold;''>Imprimir bilhete</button><br><button class='btn btn-danger btn-sm' onclick='document.location.reload();' style='margin-top: 5px; margin-bottom: 5px; width: 100%; float: center; font-weight: bold;'>Jogar novamente</button></center>"
tempo();

/*document.getElementById("teste11").innerHTML = "<b>Você tem <span id='countdowntimer'>600 </span> segundos para realizar o seu pagamento, via PIX, para a chave bolaoroja1@gmail.com.</b>"*/

wppa.addEventListener("click",()=>{
        window.open("https://api.whatsapp.com/send?text=Bolão nº 03 - Concurso nº 1093. Nome/Apelido: " + nome + ". Bilhete nº: " + numerobilhete + ". Data/Hora de emissão do bilhete: " + dataemissao + ". Palpites: " + userInputcolor);
    })
/*if(banco==""){
            document.getElementById("tabela").innerHTML = "<br><br><center><img src='https://cdn.icon-icons.com/icons2/1380/PNG/512/vcsconflicting_93497.png' width='30%;' height='30%;'></center>"
            document.getElementById("teste1").innerHTML = "<center><b>Bilhete inválido!</b></center>"
            document.getElementById("teste2").innerHTML = ""
            return false;
        }
if(contato==""){
            document.getElementById("tabela").innerHTML = "<br><br><center><img src='https://cdn.icon-icons.com/icons2/1380/PNG/512/vcsconflicting_93497.png' width='30%;' height='30%;'></center>"
            document.getElementById("teste1").innerHTML = "<center><b>Bilhete inválido!</b></center>"
            document.getElementById("teste2").innerHTML = ""
            return false;
        }*/

if(nome==""){
            alert("Por favor, certifique-se de ter preencher o seu nome ou apelido.")
            location.reload();
            return false;
        }

}

function wpp(){
    window.open('https://api.whatsapp.com/send?text=' + nome);
}

  </script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/html2pdf.js/0.10.1/html2pdf.bundle.min.js"></script>
<script>
</script>

  <script type="text/javascript">
    function tempo(){
        var timeleft = 600;
    var downloadTimer = setInterval(function(){
    timeleft--;
    document.getElementById("countdowntimer").textContent = timeleft;
    if(timeleft <= 0)
        clearInterval(downloadTimer);
    },1000);
    }
</script>
</html>
