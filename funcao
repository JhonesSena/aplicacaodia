#Ontribution jhonessena

function diadasemana($data) {
 $diasemana = array('Domingo', 'Segunda-Feira', 'Terça-Feira', 'Quarta-Feira', 'Quinta-Feira', 'Sexta-Feira', 'Sabado');
$diasemana_numero = date('w', strtotime($data));
$dia_da_semana =  $diasemana[$diasemana_numero]; //sema  
return $dia_da_semana;
 
}


#######################################################
function QueDiaeHoje($data_hoje,$mes_nome,$semana) {
$data = $data_hoje ; //$ano.'-'.$mes.'-'.$dia;

$partes = explode("/", $data);
$dia = $partes[0];
$ano = $partes[2];

$diasemana = array('Domingo', 'Segunda-Feira', 'Terça-Feira', 'Quarta-Feira', 'Quinta-Feira', 'Sexta-Feira', 'Sabado');
$diasemana_numero = date('w', strtotime($data));
$dia_da_semana =  $diasemana[$diasemana_numero]; //semana

    $mes_extenso = array(
        'Jan' => 'Janeiro',
        'Feb' => 'Fevereiro',
        'Mar' => 'Marco',
        'Apr' => 'Abril',
        'May' => 'Maio',
        'Jun' => 'Junho',
        'Jul' => 'Julho',
        'Aug' => 'Agosto',
        'Nov' => 'Novembro',
        'Sep' => 'Setembro',
        'Oct' => 'Outubro',
        'Dec' => 'Dezembro'
    );	
   	 $dia_hoje =  " Dia ". $dia. " de " .$mes_extenso["$mes_nome"]. " de " .$ano ;
	
	return $dia_hoje; 
}	
