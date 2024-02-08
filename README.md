 int num;
        String dado;
        dado =  JOptionPane.showInputDialog ("insira um numero qualquer");
           num = Integer.parseInt(dado);
           if (num >90){
           System.out.println(num +"é maior que 80.");
           } else
             if (num<50){     
          System.out.println(num + " é menor que 25");
             }  
             else
              if (num ==80){
             System.out.println("você digitou 40");
              }  
    }
}
