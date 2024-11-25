# Notas-Java
se código em Java é um exemplo de Programação Orientada a Objetos (POO), onde a lógica de cálculo de notas e médias de alunos é encapsulada dentro de uma classe.
---class----
  private double nota1;
    private double nota2;
    private double media;
    public double maior;
    public double soma;
           int qtdAluno;
    
    public void getnota1(double nota1) {
        this.nota1 = nota1;
    }
    public void setnota1(double nota1){
        this.nota1 = nota1; 
    }
    public void getnota2(double nota2){
        this.nota2 = nota2; 
    }
    public void setnota2(double nota2){
        this.nota2 = nota2;
    }
    public double maior( ){
       if(media>maior){
           maior=media;
       }
       return maior;
    }
    public double media(){
        this.media=(nota1+nota2)/2;{
         if(this.media >=6.0){
        qtdAluno++;
    }
    }
        return media;
    }
    public double soma(){
         this.soma=soma+media/2;{
    }
    return soma;
    }
}

      
-------botão------
 n.setnota1(Double.valueOf(jTnota1.getText()));
        n.setnota2(Double.valueOf(jTnota2.getText()));
        n.maior();
        jLmedia.setText("A media foi: "+n.media());
        jLmaior.setText(" "+n.maior());
        jLmediaturma.setText(" "+n.soma());
