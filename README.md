# Controle-de-notas
Controle de notas para professores.

ApproveOrReprove (note1, note2, note3)

 {

    let media = (note1 * 3) + (note2 *3) + (note3 * 4) / 10;

 (if media < 5) {return "reproved"} 
      (else if(media<= 7) {return "recovery"}
            (else > 7) {return "Approved";}
  
}

  ApproveOrReprove(5,5 10);
