# Introducao-PHP

// programa para categorias de uma competicao de natacao

 $categorias = [];
 
 $categorias [] = 'infantil';
 
 $categorias [] = 'adolescente';
 
 $categorias [] = 'adulto';
 
 $categorias [] = 'idoso';
 

$nome = 'Eduardo';

$idade = 28;

if($idade >= 6 && $idade <= 12)

{

    for($i = 0; $i <= count($categorias); $i++)
    
    { 
    
        if ($categorias[$i] == 'infantil')
        
            echo " O nadador " . $nome . " Compete na categoria infantil";            
      }
}

else if($idade >= 13 && $idade <= 18)

{

    for($i =0; $i <= count($categorias); $i++)
    
    { 
    
        if ($categorias[$i] == 'adolescente')
        
            echo " O nadador". $nome . " Compete na categoria adolescente";
            
      }
      
}

else

{

    for($i =0; $i <= count($categorias); $i++)
    
    { 
    
        if ($categorias[$i] == 'adulto')
        
            echo " O nadador". $nome. " Compete na categoria adulto";
            
      }
}
