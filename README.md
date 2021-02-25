# lg2-novamente

package  Exceções_ControleErros ;

 classe  pública Exce ção {

	public  static  void  main ( String [] args ) {
		
		tente {
			
			int [] vetor =  new  int [ 4 ];
			
			Sistema . para fora . println ( " Antes da exceção " );

			vetor [ 4 ] =  1 ;
			
			Sistema . para fora . println ( " Esse texto não será impresso " );	
	
	} 
		catch ( exceção ArrayIndexOutOfBoundsException ) {
		
		Sistema . para fora . println ( " Exceção ao acessar um índice do vetor que não existe " );
	}
	
	Sistema . para fora . println ( " Esse texto será impresso após a exceção " );

    }
}
